エンティティエージェントDCAT-AP  
===================









- `agentName`  



<details><summary><strong>full yaml details</strong></summary>    

AgentDCAT-AP:    
  description: 'Agent Schema meeting DCAT-AP 2.0 specification'    
  properties:    
    address:    
      description: 'The mailing address'    
      properties:    
        addressCountry:    
          description: 'Property. The country. For example, Spain. Model:''https://schema.org/addressCountry'''    
          type: string    
        addressLocality:    
          description: 'Property. The locality in which the street address is, and which is in the region. Model:''https://schema.org/addressLocality'''    
          type: string    
        addressRegion:    
          description: 'Property. The region in which the locality is, and which is in the country. Model:''https://schema.org/addressRegion'''    
          type: string    
        postOfficeBoxNumber:    
          description: 'Property. The post office box number for PO box addresses. For example, 03578. Model:''https://schema.org/postOfficeBoxNumber'''    
          type: string    
        postalCode:    
          description: 'Property. The postal code. For example, 24004. Model:''https://schema.org/https://schema.org/postalCode'''    
          type: string    
        streetAddress:    
          description: 'Property. The street address. Model:''https://schema.org/streetAddress'''    
          type: string    
      type: object    
      x-ngsi:    
        model: https://schema.org/address    
        type: Property    
    agentName:    
      description: 'This property contains a free-text account of the Distribution. This property can be repeated for parallel language versions of the description'    
      items:    
        minitems: 1    
        type: string    
      type: array    
      x-ngsi:    
        model: dct:description    
        type: Property    
    agentType:    
      description: 'This property refers to a type of the agent that makes the Catalogue or Dataset available'    
      type: string    
      x-ngsi:    
        model: dct:type    
        type: Property    
    alternateName:    
      description: 'An alternative name for this item'    
      type: string    
      x-ngsi:    
        type: Property    
    areaServed:    
      description: 'The geographic area where a service or offered item is provided'    
      type: string    
      x-ngsi:    
        model: https://schema.org/Text    
        type: Property    
    dataProvider:    
      description: 'A sequence of characters identifying the provider of the harmonised data entity.'    
      type: string    
      x-ngsi:    
        type: Property    
    dateCreated:    
      description: 'Entity creation timestamp. This will usually be allocated by the storage platform.'    
      format: date-time    
      type: string    
      x-ngsi:    
        type: Property    
    dateModified:    
      description: 'Timestamp of the last modification of the entity. This will usually be allocated by the storage platform.'    
      format: date-time    
      type: string    
      x-ngsi:    
        type: Property    
    description:    
      description: 'A description of this item'    
      type: string    
      x-ngsi:    
        type: Property    
    id:    
      anyOf: &agentdcat-ap_-_properties_-_owner_-_items_-_anyof    
        - description: 'Property. Identifier format of any NGSI entity'    
          maxLength: 256    
          minLength: 1    
          pattern: ^[\w\-\.\{\}\$\+\*\[\]`|~^@!,:\\]+$    
          type: string    
        - description: 'Property. Identifier format of any NGSI entity'    
          format: uri    
          type: string    
      description: 'Unique identifier of the entity'    
      x-ngsi:    
        type: Property    
    location:    
      description: 'Geojson reference to the item. It can be Point, LineString, Polygon, MultiPoint, MultiLineString or MultiPolygon'    
      oneOf:    
        - description: 'Geoproperty. Geojson reference to the item. Point'    
          properties:    
            bbox:    
              items:    
                type: number    
              minItems: 4    
              type: array    
            coordinates:    
              items:    
                type: number    
              minItems: 2    
              type: array    
            type:    
              enum:    
                - Point    
              type: string    
          required:    
            - type    
            - coordinates    
          title: 'GeoJSON Point'    
          type: object    
        - description: 'Geoproperty. Geojson reference to the item. LineString'    
          properties:    
            bbox:    
              items:    
                type: number    
              minItems: 4    
              type: array    
            coordinates:    
              items:    
                items:    
                  type: number    
                minItems: 2    
                type: array    
              minItems: 2    
              type: array    
            type:    
              enum:    
                - LineString    
              type: string    
          required:    
            - type    
            - coordinates    
          title: 'GeoJSON LineString'    
          type: object    
        - description: 'Geoproperty. Geojson reference to the item. Polygon'    
          properties:    
            bbox:    
              items:    
                type: number    
              minItems: 4    
              type: array    
            coordinates:    
              items:    
                items:    
                  items:    
                    type: number    
                  minItems: 2    
                  type: array    
                minItems: 4    
                type: array    
              type: array    
            type:    
              enum:    
                - Polygon    
              type: string    
          required:    
            - type    
            - coordinates    
          title: 'GeoJSON Polygon'    
          type: object    
        - description: 'Geoproperty. Geojson reference to the item. MultiPoint'    
          properties:    
            bbox:    
              items:    
                type: number    
              minItems: 4    
              type: array    
            coordinates:    
              items:    
                items:    
                  type: number    
                minItems: 2    
                type: array    
              type: array    
            type:    
              enum:    
                - MultiPoint    
              type: string    
          required:    
            - type    
            - coordinates    
          title: 'GeoJSON MultiPoint'    
          type: object    
        - description: 'Geoproperty. Geojson reference to the item. MultiLineString'    
          properties:    
            bbox:    
              items:    
                type: number    
              minItems: 4    
              type: array    
            coordinates:    
              items:    
                items:    
                  items:    
                    type: number    
                  minItems: 2    
                  type: array    
                minItems: 2    
                type: array    
              type: array    
            type:    
              enum:    
                - MultiLineString    
              type: string    
          required:    
            - type    
            - coordinates    
          title: 'GeoJSON MultiLineString'    
          type: object    
        - description: 'Geoproperty. Geojson reference to the item. MultiLineString'    
          properties:    
            bbox:    
              items:    
                type: number    
              minItems: 4    
              type: array    
            coordinates:    
              items:    
                items:    
                  items:    
                    items:    
                      type: number    
                    minItems: 2    
                    type: array    
                  minItems: 4    
                  type: array    
                type: array    
              type: array    
            type:    
              enum:    
                - MultiPolygon    
              type: string    
          required:    
            - type    
            - coordinates    
          title: 'GeoJSON MultiPolygon'    
          type: object    
      x-ngsi:    
        type: Geoproperty    
    name:    
      description: 'The name of this item.'    
      type: string    
      x-ngsi:    
        type: Property    
    owner:    
      description: 'A List containing a JSON encoded sequence of characters referencing the unique Ids of the owner(s)'    
      items:    
        anyOf: *agentdcat-ap_-_properties_-_owner_-_items_-_anyof    
        description: 'Property. Unique identifier of the entity'    
      type: array    
      x-ngsi:    
        type: Property    
    seeAlso:    
      description: 'list of uri pointing to additional resources about the item'    
      oneOf:    
        - items:    
            format: uri    
            type: string    
          minItems: 1    
          type: array    
        - format: uri    
          type: string    
      x-ngsi:    
        type: Property    
    source:    
      description: 'A sequence of characters giving the original source of the entity data as a URL. Recommended to be the fully qualified domain name of the source provider, or the URL to the source object.'    
      type: string    
      x-ngsi:    
        type: Property    
    type:    
      description: 'NGSI Entity type. It has to be AgentDCAT-AP'    
      enum:    
        - AgentDCAT-AP    
      type: string    
      x-ngsi:    
        type: Property    
  required:    
    - id    
    - type    
    - agentName    
  type: object    
  version: 0.0.1    
```  
</details>    





  "id": "urn:ngsi-ld:id:ZLHO:07918336",  
  "type": "AgentDCAT-AP",  
  "dateCreated": "1988-07-01T14:50:52Z",  
  "dateModified": "2000-06-02T13:25:42Z",  
  "source": "Any source for an Agent.",  
  "name": "Agent 10.",  
  "alternateName": "Agent-10.",  
  "description": "organization the Agent 10 belongs to.",  
  "dataProvider": "",  
  "owner": [  
    "urn:ngsi-ld:Agent:TBSV:39232621"  
  ],  
  "seeAlso": [  
    "urn:ngsi-ld:AgentAECY:13995407"  
  ],  
  "location": {  
    "type": "Point",  
    "coordinates": [  
      12.934074,  
      -149.532943  
    ]  
  },  
  "address": {  
    "streetAddress": "2 Rue Mercier",  
    "addressLocality": "Luxembourg",  
    "addressRegion": "Luxembourg",  
    "addressCountry": "Luxembourg",  
    "postalCode": "2985 ",  
    "postOfficeBoxNumber": "",  
    "areaServed": "European Union"  
  },  
  "agentName": [  
    "Agent 10",  
    "Agente 10"  
  ],  
  "agentType": "EU Publications office"  
}  
```  




  "id": "urn:ngsi-ld:id:ZLHO:07918336",  
  "type": "AgentDCAT-AP",  
  "dateCreated": {  
    "type": "DateTime",  
    "value": "1988-07-01T14:50:52Z"  
  },  
  "dateModified": {  
    "type": "DateTime",  
    "value": "2000-06-02T13:25:42Z"  
  },  
  "source": {  
    "type": "Text",  
    "value": "Any source for an Agent."  
  },  
  "name": {  
    "type": "Text",  
    "value": "Agent 10."  
  },  
  "alternateName": {  
    "type": "Text",  
    "value": "Agent-10."  
  },  
  "description": {  
    "type": "Text",  
    "value": "organization the Agent 10 belongs to."  
  },  
  "dataProvider": {  
    "type": "Text",  
    "value": ""  
  },  
  "owner": {  
    "type": "array",  
    "value": [  
      "urn:ngsi-ld:Agent:TBSV:39232621"  
    ]  
  },  
  "seeAlso": {  
    "type": "array",  
    "value": [  
      "urn:ngsi-ld:AgentAECY:13995407"  
    ]  
  },  
  "location": {  
    "type": "geo:json",  
    "value": {  
      "type": "Point",  
      "coordinates": [  
        12.934074,  
        -149.532943  
      ]  
    }  
  },  
  "address": {  
    "type": "StructuredValue",  
    "value": {  
      "streetAddress": "2 Rue Mercier",  
      "addressLocality": "Luxembourg",  
      "addressRegion": "Luxembourg",  
      "addressCountry": "Luxembourg",  
      "postalCode": "2985 ",  
      "postOfficeBoxNumber": "",  
      "areaServed": "European Union"  
    }  
  },  
  "agentName": {  
    "type": "array",  
    "value": [  
      "Agent 10",  
      "Agente 10"  
    ]  
  },  
  "agentType": {  
    "type": "Text",  
    "value": "EU Publications office"  
  }  
}  
```  




  "id": "urn:ngsi-ld:id:ZLHO:07918336",  
  "type": "AgentDCAT-AP",  
  "dateCreated": "1988-07-01T14:50:52Z",  
  "dateModified": "2000-06-02T13:25:42Z",  
  "source": "Any source for an Agent.",  
  "name": "Agent 10.",  
  "alternateName": "Agent-10.",  
  "description": "organization the Agent 10 belongs to.",  
  "dataProvider": "",  
  "owner": [  
    "urn:ngsi-ld:Agent:TBSV:39232621"  
  ],  
  "seeAlso": [  
    "urn:ngsi-ld:AgentAECY:13995407"  
  ],  
  "location": {  
    "type": "Point",  
    "coordinates": [  
      12.934074,  
      -149.532943  
    ]  
  },  
  "address": {  
    "streetAddress": "2 Rue Mercier",  
    "addressLocality": "Luxembourg",  
    "addressRegion": "Luxembourg",  
    "addressCountry": "Luxembourg",  
    "postalCode": "2985 ",  
    "postOfficeBoxNumber": "",  
    "areaServed": "European Union"  
  },  
  "agentName": [  
    "Agent 10",  
    "Agente 10"  
  ],  
  "agentType": "EU Publications office",  
  "@context": [  
    "https://smartdatamodels.org/context.jsonld"  
  ]  
}  
```  




  "id": "urn:ngsi-ld:id:ZLHO:07918336",  
  "type": "AgentDCAT-AP",  
  "dateCreated": {  
    "type": "Property",  
    "value": {  
      "@type": "DateTime",  
      "@value": "1988-07-01T14:50:52Z"  
    }  
  },  
  "dateModified": {  
    "type": "Property",  
    "value": {  
      "@type": "DateTime",  
      "@value": "2000-06-02T13:25:42Z"  
    }  
  },  
  "source": {  
    "type": "Property",  
    "value": "Any source for an Agent."  
  },  
  "name": {  
    "type": "Property",  
    "value": "Agent 10."  
  },  
  "alternateName": {  
    "type": "Property",  
    "value": "Agent-10."  
  },  
  "description": {  
    "type": "Property",  
    "value": "organization the Agent 10 belongs to."  
  },  
  "dataProvider": {  
    "type": "Property",  
    "value": ""  
  },  
  "owner": {  
    "type": "Property",  
    "value": [  
      "urn:ngsi-ld:Agent:TBSV:39232621"  
    ]  
  },  
  "seeAlso": {  
    "type": "Property",  
    "value": [  
      "urn:ngsi-ld:AgentAECY:13995407"  
    ]  
  },  
  "location": {  
    "type": "Geoproperty",  
    "value": {  
      "type": "Point",  
      "coordinates": [  
        12.934074,  
        -149.532943  
      ]  
    }  
  },  
  "address": {  
    "type": "Property",  
    "value": {  
      "streetAddress": "2 Rue Mercier",  
      "addressLocality": "Luxembourg",  
      "addressRegion": "Luxembourg",  
      "addressCountry": "Luxembourg",  
      "postalCode": "2985 ",  
      "postOfficeBoxNumber": "",  
      "areaServed": "European Union"  
    }  
  },  
  "agentName": {  
    "type": "Property",  
    "value": [  
      "Agent 10",  
      "Agente 10"  
    ]  
  },  
  "agentType": {  
    "type": "Property",  
    "value":  
      "EU Publications office"  
  },  
  "@context": [  
    "https://smartdatamodels.org/context.jsonld"  
  ]  
}  
```  