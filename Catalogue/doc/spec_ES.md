<!-- 10-Header -->  
[![Smart Data Models](https://smartdatamodels.org/wp-content/uploads/2022/01/SmartDataModels_logo.png "Logo")](https://smartdatamodels.org)  
Entidad: Catálogo  
=================<!-- /10-Header -->  
<!-- 15-License -->  
[Licencia abierta](https://github.com/smart-data-models//dataModel.DCAT-AP/blob/master/Catalogue/LICENSE.md)  
[documento generado automáticamente](https://docs.google.com/presentation/d/e/2PACX-1vTs-Ng5dIAwkg91oTTUdt8ua7woBXhPnwavZ0FxgR8BsAI_Ek3C5q97Nd94HS8KhP-r_quD4H0fgyt3/pub?start=false&loop=false&delayms=3000#slide=id.gb715ace035_0_60)  
<!-- /15-License -->  
<!-- 20-Description -->  
Descripción global: **Catálogo de conjuntos de datos conformes con la especificación DCAT-AP versión 2.1.1.**.  
versión: 1.0.1  
<!-- /20-Description -->  
<!-- 30-PropertiesList -->  

## Lista de propiedades  

<sup><sub>[*] Si no hay un tipo en un atributo es porque puede tener varios tipos o diferentes formatos/patrones</sub></sup>.  
- `address[object]`: La dirección postal  . Model: [https://schema.org/address](https://schema.org/address)- `areaServed[string]`: La zona geográfica en la que se presta un servicio o se ofrece un artículo  . Model: [https://schema.org/Text](https://schema.org/Text)- `catalog[array]`: Relación. Modelo:'http://www.w3.org/ns/dcat#Catalog'. Esta propiedad se refiere a un catálogo cuyo contenido es de interés en el contexto de este catálogo  . Model: [http://www.w3.org/ns/dcat#Catalog](http://www.w3.org/ns/dcat#Catalog)- `creator[array]`: Relación. Modelo:'http://xmlns.com/foaf/0.1/Agent'. Las entidades principalmente responsables de la elaboración del catálogo  . Model: [http://xmlns.com/foaf/0.1/Agent](http://xmlns.com/foaf/0.1/Agent)- `dataset[array]`: Relación. Esta propiedad vincula el Catálogo con un Conjunto de Datos que forma parte del Catálogo. Modelo:'http://www.w3.org/ns/dcat#dataset'  . Model: [http://www.w3.org/ns/dcat#dataset](http://www.w3.org/ns/dcat#dataset)- `description[array]`: Propiedad. Esta propiedad contiene una cuenta de texto libre de  
del Catálogo. Esta propiedad puede repetirse para versiones lingüísticas paralelas de la descripción. Para más información sobre cuestiones multilingües, consulte la sección 8 del documento pdf https://codeload.github.com/SEMICeu/DCAT-AP/zip/refs/tags/v2.1.1.  - `hasPart[array]`: Relación. Modelo:'http://www.w3.org/ns/dcat#Catalog'. Esta propiedad hace referencia a un Catálogo relacionado que forma parte del Catálogo descrito  . Model: [http://www.w3.org/ns/dcat#Catalog](http://www.w3.org/ns/dcat#Catalog)- `homepage[string]`: Propiedad. Modelo:'http://xmlns.com/foaf/0.1/homepage'. Esta propiedad hace referencia a una página web que actúa como página principal del Catálogo.  . Model: [http://xmlns.com/foaf/0.1/homepage](http://xmlns.com/foaf/0.1/homepage)- `id[*]`: Identificador único de la entidad  - `isPartOf[string]`: Relación. Modelo:'http://www.w3.org/ns/dcat#Catalog'. Esta propiedad se refiere a un Catálogo relacionado en el que el Catálogo descrito está física o lógicamente incluido.  . Model: [http://www.w3.org/ns/dcat#Catalog](http://www.w3.org/ns/dcat#Catalog)- `issued[string]`: Propiedad. Modelo:'http://www.w3.org/2000/01/rdf-schema#Literal'. Esta propiedad contiene la fecha de emisión formal (por ejemplo, publicación) del Catálogo.  . Model: [http://www.w3.org/2000/01/rdf-schema#Literal](http://www.w3.org/2000/01/rdf-schema#Literal)- `language[array]`: Propiedad. Modelo:'http://purl.org/dc/terms/LinguisticSystem'. Esta propiedad se refiere a un idioma utilizado en los metadatos textuales que describen títulos, descripciones, etc. de los Conjuntos de Datos del Catálogo. Esta propiedad puede repetirse si los metadatos se proporcionan en varios idiomas.  . Model: [http://purl.org/dc/terms/LinguisticSystem](http://purl.org/dc/terms/LinguisticSystem)- `licence[string]`: Propiedad. Modelo:'http://purl.org/dc/terms/LicenseDocument'. Esta propiedad se refiere a la licencia bajo la cual puede utilizarse o reutilizarse el Catálogo.  . Model: [http://purl.org/dc/terms/LicenseDocument](http://purl.org/dc/terms/LicenseDocument)- `location[*]`: Referencia Geojson al elemento. Puede ser Point, LineString, Polygon, MultiPoint, MultiLineString o MultiPolygon.  - `modified[string]`: Propiedad. Modelo:'http://www.w3.org/2000/01/rdf-schema#Literal'. Esta propiedad contiene la fecha más reciente en la que se modificó el Catálogo.  . Model: [http://www.w3.org/2000/01/rdf-schema#Literal](http://www.w3.org/2000/01/rdf-schema#Literal)- `publisher[string]`: Propiedad. Esta propiedad se refiere a una entidad (organización) responsable de poner a disposición el Catálogo. Modelo:'http://xmlns.com/foaf/0.1/Agent'  . Model: [http://xmlns.com/foaf/0.1/Agent](http://xmlns.com/foaf/0.1/Agent)- `record[array]`: Relación. Esta propiedad se refiere a un Registro de Catálogo que forma parte del Catálogo. Modelo:'http://www.w3.org/ns/dcat#CatalogRecord'  . Model: [http://www.w3.org/ns/dcat#CatalogRecord](http://www.w3.org/ns/dcat#CatalogRecord)- `rights[string]`: Propiedad. Modelo:'http://purl.org/dc/terms/RightsStatement'. Esta propiedad se refiere a una declaración que especifica los derechos asociados al Catálogo.  . Model: [http://purl.org/dc/terms/RightsStatement](http://purl.org/dc/terms/RightsStatement)- `service[array]`: Relación. Esta propiedad se refiere a un sitio o punto final (Servicio de Datos) que figura en el Catálogo. Dado que los Catálogos vacíos suelen ser indicios de problemas, esta propiedad debe combinarse con el conjunto de datos de la propiedad anterior para implementar una comprobación de Catálogo vacío Modelo:'http://www.w3.org/ns/dcat#DataService'  . Model: [As empty Catalogues are usually indications of problems, this property should be combined with the previous property dataset to implement an empty Catalogue check http://www.w3.org/ns/dcat#DataService](As empty Catalogues are usually indications of problems, this property should be combined with the previous property dataset to implement an empty Catalogue check http://www.w3.org/ns/dcat#DataService)- `spatial[array]`: GeoPropiedad. Modelo:'http://purl.org/dc/terms/Location'. Esta propiedad se refiere a un área geográfica cubierta por el Catálogo.  . Model: [http://purl.org/dc/terms/Location](http://purl.org/dc/terms/Location)- `themeTaxonomy[array]`: Propiedad. Modelo:'http://www.w3.org/2004/02/skos/core#ConceptScheme'. Esta propiedad se refiere a un sistema de organización del conocimiento utilizado para clasificar los Conjuntos de Datos del Catálogo.  . Model: [http://www.w3.org/2004/02/skos/core#ConceptScheme](http://www.w3.org/2004/02/skos/core#ConceptScheme)- `title[array]`: Propiedad. Modelo:'http://www.w3.org/2000/01/rdf-schema#Literal'. Esta propiedad contiene un nombre dado al Catálogo. Esta propiedad puede repetirse para versiones lingüísticas paralelas del nombre. Modelo:'rdfs:Literal'  . Model: [rdfs:Literal](rdfs:Literal)- `type[string]`: Propiedad. Modelo:'https://schema.org/Text'. Tiene que ser Catálogo  . Model: [https://schema.org/Text](https://schema.org/Text)<!-- /30-PropertiesList -->  
<!-- 35-RequiredProperties -->  
Propiedades requeridas  
- `description`  - `id`  - `publisher`  - `title`  - `type`  <!-- /35-RequiredProperties -->  
<!-- 40-RequiredProperties -->  
Este modelo de datos y otros de la asignatura DCAT-AP están siendo adaptados para su uso y sería recomendable que se incluyera contexto adicional. [https://raw.githubusercontent.com/SEMICeu/DCAT-AP/master/releases/1.1/dcat-ap_1.1.jsonld" ](https://raw.githubusercontent.com/SEMICeu/DCAT-AP/master/releases/1.1/dcat-ap_1.1.jsonld)  
<!-- /40-RequiredProperties -->  
<!-- 50-DataModelHeader -->  
## Descripción de las propiedades del modelo de datos  
Ordenados alfabéticamente (pulse para más detalles)  
<!-- /50-DataModelHeader -->  
<!-- 60-ModelYaml -->  
<details><summary><strong>full yaml details</strong></summary>    
```yaml  
Catalogue:    
  description: Catalogue of datasets compliant with DCAT-AP specification version 2.1.1.    
  properties:    
    address:    
      description: The mailing address    
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
        district:    
          description: 'A district is a type of administrative division that, in some countries, is managed by the local government.'    
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
        streetNr:    
          description: Number identifying a specific property on a public street.    
          type: string    
      type: object    
      x-ngsi:    
        model: https://schema.org/address    
        type: Property    
    areaServed:    
      description: The geographic area where a service or offered item is provided    
      type: string    
      x-ngsi:    
        model: https://schema.org/Text    
        type: Property    
    catalog:    
      description: "Relationship. Model:'http://www.w3.org/ns/dcat#Catalog'. This property refers to a catalog whose contents are of interest in the context of this catalog"    
      items:    
        anyOf:    
          - description: Property. Identifier format of any NGSI entity    
            maxLength: 256    
            minLength: 1    
            pattern: ^[\w\-\.\{\}\$\+\*\[\]`|~^@!,:\\]+$    
            type: string    
          - description: Property. Identifier format of any NGSI entity    
            format: uri    
            type: string    
        description: 'Relationship. Every link to the contents of interest to the catalog '    
      type: array    
      x-ngsi:    
        model: "http://www.w3.org/ns/dcat#Catalog"    
        type: Relationship    
    creator:    
      description: 'Relationship. Model:''http://xmlns.com/foaf/0.1/Agent''. The entities primarily responsible for producing the catalogue'    
      items:    
        description: 'Relationship. Model:''http://xmlns.com/foaf/0.1/Agent''. The link to an entity primarily responsible for producing the catalogue'    
        type: string    
      type: array    
      x-ngsi:    
        model: http://xmlns.com/foaf/0.1/Agent    
        type: Relationship    
    dataset:    
      description: "Relationship. This property links the Catalogue with a Dataset that is part of the Catalogue. Model:'http://www.w3.org/ns/dcat#dataset'"    
      items:    
        anyOf:    
          - description: Property. Identifier format of any NGSI entity    
            maxLength: 256    
            minLength: 1    
            pattern: ^[\w\-\.\{\}\$\+\*\[\]`|~^@!,:\\]+$    
            type: string    
          - description: Property. Identifier format of any NGSI entity    
            format: uri    
            type: string    
      type: array    
      x-ngsi:    
        model: "http://www.w3.org/ns/dcat#dataset"    
        type: Relationship    
    description:    
      description: |-    
        Property. This property contains a free-text account of    
        the Catalogue. This property can be repeated for parallel language versions of the description. For further information on multilingual issues, please refer to section 8 of the pdf document https://codeload.github.com/SEMICeu/DCAT-AP/zip/refs/tags/v2.1.1    
      items:    
        description: Property. Catalog description in different languages    
        type: string    
      type: array    
      x-ngsi:    
        type: Property    
    hasPart:    
      description: "Relationship. Model:'http://www.w3.org/ns/dcat#Catalog'. This property refers to a related Catalogue that is part of the described Catalogue"    
      items:    
        description: Relationship. Every link to the related catalog    
        format: uri    
        type: string    
      type: array    
      x-ngsi:    
        model: "http://www.w3.org/ns/dcat#Catalog"    
        type: Relationship    
    homepage:    
      description: 'Property. Model:''http://xmlns.com/foaf/0.1/homepage''. This property refers to a web page that acts as the main page for the Catalogue.'    
      format: uri    
      type: string    
      x-ngsi:    
        model: http://xmlns.com/foaf/0.1/homepage    
        type: Property    
    id:    
      anyOf:    
        - description: Property. Identifier format of any NGSI entity    
          maxLength: 256    
          minLength: 1    
          pattern: ^[\w\-\.\{\}\$\+\*\[\]`|~^@!,:\\]+$    
          type: string    
        - description: Property. Identifier format of any NGSI entity    
          format: uri    
          type: string    
      description: Unique identifier of the entity    
      x-ngsi:    
        type: Property    
    isPartOf:    
      description: "Relationship. Model:'http://www.w3.org/ns/dcat#Catalog'. This property refers to a related Catalogue in which the described Catalogue is physically or logically included."    
      format: uri    
      type: string    
      x-ngsi:    
        model: "http://www.w3.org/ns/dcat#Catalog"    
        type: Relationship    
    issued:    
      description: "Property. Model:'http://www.w3.org/2000/01/rdf-schema#Literal'. This property contains the date of formal issuance (e.g., publication) of the Catalogue."    
      format: date-time    
      type: string    
      x-ngsi:    
        model: "http://www.w3.org/2000/01/rdf-schema#Literal"    
        type: Property    
    language:    
      description: 'Property. Model:''http://purl.org/dc/terms/LinguisticSystem''. This property refers to a language used in the textual metadata describing titles, descriptions, etc. of the Datasets in the Catalogue. This property can be repeated if the  metadata is provided in multiple languages.'    
      items:    
        description: Property. Individual identifiers of the language    
        type: string    
      type: array    
      x-ngsi:    
        model: http://purl.org/dc/terms/LinguisticSystem    
        type: Property    
    licence:    
      description: 'Property. Model:''http://purl.org/dc/terms/LicenseDocument''. This property refers to the licence under which the Catalogue can be used or reused.'    
      type: string    
      x-ngsi:    
        model: http://purl.org/dc/terms/LicenseDocument    
        type: Property    
    location:    
      description: 'Geojson reference to the item. It can be Point, LineString, Polygon, MultiPoint, MultiLineString or MultiPolygon'    
      oneOf: &catalogue_-_properties_-_spatial_-_items_-_oneof    
        - description: GeoProperty. Geojson reference to the item. Point    
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
          title: GeoJSON Point    
          type: object    
        - description: GeoProperty. Geojson reference to the item. LineString    
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
          title: GeoJSON LineString    
          type: object    
        - description: GeoProperty. Geojson reference to the item. Polygon    
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
          title: GeoJSON Polygon    
          type: object    
        - description: GeoProperty. Geojson reference to the item. MultiPoint    
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
          title: GeoJSON MultiPoint    
          type: object    
        - description: GeoProperty. Geojson reference to the item. MultiLineString    
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
          title: GeoJSON MultiLineString    
          type: object    
        - description: GeoProperty. Geojson reference to the item. MultiLineString    
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
          title: GeoJSON MultiPolygon    
          type: object    
      x-ngsi:    
        type: GeoProperty    
    modified:    
      description: "Property. Model:'http://www.w3.org/2000/01/rdf-schema#Literal'. This property contains the most recent date on which the Catalogue was modified."    
      format: date-time    
      type: string    
      x-ngsi:    
        model: "http://www.w3.org/2000/01/rdf-schema#Literal"    
        type: Property    
    publisher:    
      description: 'Property. This property refers to an entity (organisation) responsible for making the Catalogue available. Model:''http://xmlns.com/foaf/0.1/Agent'''    
      type: string    
      x-ngsi:    
        model: http://xmlns.com/foaf/0.1/Agent    
        type: Property    
    record:    
      description: "Relationship. This property refers to a Catalogue Record that is part of the Catalogue. Model:'http://www.w3.org/ns/dcat#CatalogRecord'"    
      items:    
        anyOf:    
          - description: Property. Identifier format of any NGSI entity    
            maxLength: 256    
            minLength: 1    
            pattern: ^[\w\-\.\{\}\$\+\*\[\]`|~^@!,:\\]+$    
            type: string    
          - description: Property. Identifier format of any NGSI entity    
            format: uri    
            type: string    
        description: Relationship. Link to the catalog record    
      type: array    
      x-ngsi:    
        model: "http://www.w3.org/ns/dcat#CatalogRecord"    
        type: Relationship    
    rights:    
      description: 'Property. Model:''http://purl.org/dc/terms/RightsStatement''. This property refers to a statement that specifies rights associated with the Catalogue.'    
      type: string    
      x-ngsi:    
        model: http://purl.org/dc/terms/RightsStatement    
        type: Property    
    service:    
      description: "Relationship. This property refers to a site or end-point (Data Service) that is listed in the Catalogue. As empty Catalogues are usually indications of problems, this property should be combined with the previous property dataset to implement an empty Catalogue check Model:'http://www.w3.org/ns/dcat#DataService'"    
      items:    
        anyOf:    
          - description: Property. Identifier format of any NGSI entity    
            maxLength: 256    
            minLength: 1    
            pattern: ^[\w\-\.\{\}\$\+\*\[\]`|~^@!,:\\]+$    
            type: string    
          - description: Property. Identifier format of any NGSI entity    
            format: uri    
            type: string    
        description: Property. NGSI-LD id of the different services linked to the catalogue    
      type: array    
      x-ngsi:    
        model: "As empty Catalogues are usually indications of problems, this property should be combined with the previous property dataset to implement an empty Catalogue check http://www.w3.org/ns/dcat#DataService"    
        type: Relationship    
    spatial:    
      description: 'GeoProperty. Model:''http://purl.org/dc/terms/Location''. This property refers to a geographical area covered by the Catalogue.'    
      items:    
        description: 'GeoProperty. Geojson reference to the item. It can be Point, LineString, Polygon, MultiPoint, MultiLineString or MultiPolygon'    
        oneOf: *catalogue_-_properties_-_spatial_-_items_-_oneof    
      type: array    
      x-ngsi:    
        model: http://purl.org/dc/terms/Location    
        type: GeoProperty    
    themeTaxonomy:    
      description: "Property. Model:'http://www.w3.org/2004/02/skos/core#ConceptScheme'. This property refers to a knowledge organization system used to classify the Catalogue's Datasets."    
      items:    
        type: string    
      type: array    
      x-ngsi:    
        model: "http://www.w3.org/2004/02/skos/core#ConceptScheme"    
        type: Property    
    title:    
      description: "Property. Model:'http://www.w3.org/2000/01/rdf-schema#Literal'. This property contains a name given to the Catalogue. This property can be repeated for parallel language versions of the name. Model:'rdfs:Literal'"    
      items:    
        description: Property. Title in different languages    
        type: string    
      type: array    
      x-ngsi:    
        model: rdfs:Literal    
        type: Property    
    type:    
      description: 'Property. Model:''https://schema.org/Text''. It has to be Catalogue'    
      enum:    
        - Catalogue    
      type: string    
      x-ngsi:    
        model: https://schema.org/Text    
        type: Property    
  required:    
    - id    
    - type    
    - description    
    - publisher    
    - title    
  type: object    
  x-derived-from: ""    
  x-disclaimer: 'Redistribution and use in source and binary forms, with or without modification, are permitted  provided that the license conditions are met. Copyleft (c) 2022 Contributors to Smart Data Models Program'    
  x-license-url: https://github.com/smart-data-models/dataModel.DCAT-AP/blob/master/Catalogue/LICENSE.md    
  x-model-schema: https://smart-data-models.github.io/dataModel.DCAT-AP/Catalogue/schema.json    
  x-model-tags: ""    
  x-version: 1.0.1    
```  
</details>    
<!-- /60-ModelYaml -->  
<!-- 70-MiddleNotes -->  
<!-- /70-MiddleNotes -->  
<!-- 80-Examples -->  
## Ejemplo de carga útil  
#### Catálogo de valores clave NGSI-v2 Ejemplo  
He aquí un ejemplo de Catálogo en formato JSON-LD como valores-clave. Esto es compatible con NGSI-v2 cuando se utiliza `options=keyValues` y devuelve los datos de contexto de una entidad individual.  
<details><summary><strong>show/hide example</strong></summary>    
```json  
{  
  "id": "urn:ngsi-ld:Catalogue:id:LMVP:18269678",  
  "type": "Catalogue",  
  "description": [  
    "Interesting art recently book girl yard represent book. Garden style wish blood your ground size."  
  ],  
  "location": {  
    "type": "Point",  
    "coordinates": [  
      -83.400987,  
      0.152532  
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
  "dataset": [  
    "urn:ngsi-ld:Catalogue:dataset:ZBCW:95668818"  
  ],  
  "publisher": "Spanish data portal",  
  "title": [  
    "title first",  
    "Secondary title."  
  ],  
  "homepage": "ngsi-ld:Catalogue:homepage:ZFAW:13633782",  
  "language": [  
    "ES",  
    "DE"  
  ],  
  "licence": "Creative Commons 3.0 International",  
  "issued": "2004-08-22T22:32:47Z",  
  "spatial": [  
    {  
      "type": "Point",  
      "coordinates": [  
        57.234944,  
        52.840273  
      ]  
    }  
  ],  
  "themeTaxonomy": [  
    "Want couple him finally responsibility begin. Coach join down new major. Happy yard letter then return member.",  
    "Politics road two question offer white. Recognize fight keep blue person create be. Radio edge or improve less special future. Itself detail computer exist."  
  ],  
  "modified": "1982-09-02T03:16:28Z",  
  "hasPart": [  
    "urn:ngsi-ld:Catalogue:hasPart:GVZM:66676591"  
  ],  
  "isPartOf": "urn:ngsi-ld:Catalogue:isPartOf:NXBZ:88517287",  
  "record": [  
    "Catalogue.items.HLGA.73285516",  
    "Catalogue.items.IHOB.85266800"  
  ],  
  "rights": "",  
  "catalog": [  
    "urn:ngsi-ld:Catalogue:items:LZMQ:44249979",  
    "urn:ngsi-ld:Catalogue:items:PECX:02526105"  
  ],  
  "creator": [""]  
}  
```  
</details>  
#### Catálogo NGSI-v2 normalizado Ejemplo  
He aquí un ejemplo de Catálogo en formato JSON-LD normalizado. Esto es compatible con NGSI-v2 cuando no se utilizan opciones y devuelve los datos de contexto de una entidad individual.  
<details><summary><strong>show/hide example</strong></summary>    
```json  
{  
  "id": "urn:ngsi-ld:Catalogue:id:LMVP:18269678",  
  "type": "Catalogue",  
  "description": {  
    "type": "array",  
    "value": ["Interesting art recently book girl yard represent book. Garden style wish blood your ground size."]  
  },  
  "location": {  
    "type": "geo:json",  
    "value": {  
      "type": "Point",  
      "coordinates": [  
        -83.400987,  
        0.152532  
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
  "dataset": {  
    "type": "array",  
    "value": ["urn:ngsi-ld:Catalogue:dataset:ZBCW:95668818"]  
  },  
  "publisher": {  
    "type": "Text",  
    "value": "spanish open data portal"  
  },  
  "title": {  
    "type": "Array",  
    "value": [  
      "Hair commercial free civil. Figure American film despite few. Box watch cold act mean thank music people. Third fill us.",  
      "Technology life low standard second."  
    ]  
  },  
  "homepage": {  
    "type": "Text",  
    "value": "urn:ngsi-ld:Catalogue:homepage:ZFAW:13633782"  
  },  
  "language": {  
    "type": "array",  
    "value": [  
      "Town size computer way. Since challenge phone state listen south low.",  
      "Eight once single. Build every kid."  
    ]  
  },  
  "licence": {  
    "type": "Text",  
    "value": "Improve social simply court week debate bad. Structure ago cup head point. Above much can own course."  
  },  
  "issued": {  
    "type": "DateTime",  
    "value": "2004-08-22T22:32:47Z"  
  },  
  "spatial": {  
    "type": "geo:json",  
    "value": {  
      "type": "Point",  
      "coordinates": [  
        57.234944,  
        52.840273  
      ]  
    }  
  },  
  "themeTaxonomy": {  
    "type": "array",  
    "value": [  
      "Tourism",  
      "Economy"  
    ]  
  },  
  "modified": {  
    "type": "DateTime",  
    "value": "1982-09-02T03:16:28Z"  
  },  
  "hasPart": {  
    "type": "array",  
    "value": ["urn:ngsi-ld:Catalogue:hasPart:GVZM:66676591"]  
  },  
  "isPartOf": {  
    "type": "Text",  
    "value": "urn:ngsi-ld:Catalogue:isPartOf:NXBZ:88517287"  
  },  
  "record": {  
    "type": "Array",  
    "value": [  
      "urn:ngsi-ld:Catalogue:items:HLGA:73285516",  
      "urn:ngsi-ld:Catalogue:items:IHOB:85266800"  
    ]  
  },  
  "rights": {  
    "type": "Text",  
    "value": "Open source"  
  },  
  "catalog": {  
    "type": "Array",  
    "value": [  
      "urn:ngsi-ld:Catalogue:items:LZMQ:44249979",  
      "urn:ngsi-ld:Catalogue:items:PECX:02526105"  
    ]  
  },  
  "creator": {  
    "type": "array",  
    "value": ["Role fact sport shoulder blue direction probably order."]  
  }  
}  
```  
</details>  
#### Catálogo de valores clave NGSI-LD Ejemplo  
He aquí un ejemplo de Catálogo en formato JSON-LD como valores-clave. Esto es compatible con NGSI-LD cuando se utiliza `options=keyValues` y devuelve los datos de contexto de una entidad individual.  
<details><summary><strong>show/hide example</strong></summary>    
```json  
{  
  "id": "urn:ngsi-ld:Catalogue:id:LMVP:18269678",  
  "type": "Catalogue",  
  "address": {  
    "streetAddress": "2 Rue Mercier",  
    "addressLocality": "Luxembourg",  
    "addressRegion": "Luxembourg",  
    "addressCountry": "Luxembourg",  
    "postalCode": "2985 ",  
    "postOfficeBoxNumber": "",  
    "areaServed": "European Union"  
  },  
  "catalogue": [  
    "urn:ngsi-ld:Catalogue:items:LZMQ:44249979",  
    "urn:ngsi-ld:Catalogue:items:PECX:02526105"  
  ],  
  "creator": ["Role fact sport shoulder blue direction probably order."],  
  "dataset": [  
    "urn:ngsi-ld:Catalogue:dataset:ZBCW:95668818"  
  ],  
  "description": [  
    "Interesting art recently book girl yard represent book. Garden style wish blood your ground size."  
  ],  
  "hasPart": [  
    "urn:ngsi-ld:Catalogue:hasPart:GVZM:66676591"  
  ],  
  "homepage": "ngsi-ld:Catalogue:homepage:ZFAW:13633782",  
  "isPartOf": "urn:ngsi-ld:Catalogue:isPartOf:NXBZ:88517287",  
  "language": [  
    "ES",  
    "DE"  
  ],  
  "licence": "Creative Commons 3.0 International",  
  "location": {  
    "type": "Point",  
    "coordinates": [  
      -83.400987,  
      0.152532  
    ]  
  },  
  "modified": "1982-09-02T03:16:28Z",  
  "publisher": "Spanish data portal",  
  "record": [  
    "Catalogue.items.HLGA.73285516",  
    "Catalogue.items.IHOB.85266800"  
  ],  
  "issued": "2004-08-22T22:32:47Z",  
  "rights": "",  
  "spatial": [  
    {  
      "type": "Point",  
      "coordinates": [  
        57.234944,  
        52.840273  
      ]  
    }  
  ],  
  "themeTaxonomy": [  
    "Want couple him finally responsibility begin. Coach join down new major. Happy yard letter then return member.",  
    "Politics road two question offer white. Recognize fight keep blue person create be. Radio edge or improve less special future. Itself detail computer exist."  
  ],  
  "title": [  
    "title first",  
    "Secondary title."  
  ],  
  "@context": [  
    "https://raw.githubusercontent.com/smart-data-models/dataModel.DCAT-AP/master/context.jsonld"  
  ]  
}  
```  
</details>  
#### Catálogo NGSI-LD normalizado Ejemplo  
He aquí un ejemplo de Catálogo en formato JSON-LD normalizado. Esto es compatible con NGSI-LD cuando no se utilizan opciones y devuelve los datos de contexto de una entidad individual.  
<details><summary><strong>show/hide example</strong></summary>    
```json  
{  
  "id": "urn:ngsi-ld:Catalogue:id:LMVP:18269678",  
  "type": "Catalogue",  
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
  "catalog": {  
    "type": "Relationship",  
    "value": [  
      "urn:ngsi-ld:Catalogue:items:LZMQ:44249979",  
      "urn:ngsi-ld:Catalogue:items:PECX:02526105"  
    ]  
  },  
  "creator": {  
    "type": "Relationship",  
    "object": [""]  
  },  
  "dataset": {  
    "type": "Relationship",  
    "object": [  
      "urn:ngsi-ld:Catalogue:dataset:ZBCW:95668818"  
    ]  
  },  
  "description": {  
    "type": "Property",  
    "value": [""]  
  },  
  "hasPart": {  
    "type": "Relationship",  
    "object": [  
      "urn:ngsi-ld:Catalogue:hasPart:GVZM:66676591"  
    ]  
  },  
  "homepage": {  
    "type": "Property",  
    "value": "Catalogue:homepage:ZFAW:13633782"  
  },  
  "isPartOf": {  
    "type": "Relationship",  
    "object": "urn:ngsi-ld:Catalogue:isPartOf:NXBZ:88517287"  
  },  
  "language": {  
    "type": "Property",  
    "value": [  
      "ES",  
      "DE"  
    ]  
  },  
  "licence": {  
    "type": "Property",  
    "value":  
      "Creative Commons 3.0 International"  
  },  
  "location": {  
    "type": "GeoProperty",  
    "value": {  
      "type": "Point",  
      "coordinates": [  
        -83.400987,  
        0.152532  
      ]  
    }  
  },  
  "modified": {  
    "type": "Property",  
    "value": {  
      "@type": "DateTime",  
      "@value": "1982-09-02T03:16:28Z"  
    }  
  },  
  "publisher": {  
    "type": "Property",  
    "value": "Spain open data portal"  
  },  
  "record": {  
    "type": "Relationship",  
    "value": [  
      "Catalogue.items.HLGA.73285516",  
      "Catalogue.items.IHOB.85266800"  
    ]  
  },  
  "issued": {  
    "type": "Property",  
    "value": {  
      "@type": "DateTime",  
      "@value": "2004-08-22T22:32:47Z"  
    }  
  },  
  "rights": {  
    "type": "Property",  
    "value": ""  
  },  
  "spatial": {  
    "type": "GeoProperty",  
    "value": {  
      "type": "Point",  
      "coordinates": [  
        57.234944,  
        52.840273  
      ]  
    }  
  },  
  "themeTaxonomy": {  
    "type": "Property",  
    "value": [  
      "Tourism",  
      "Economy"  
    ]  
  },  
  "title": {  
    "type": "Property",  
    "value": [  
      "New catalogue",  
      "Nuevo catalogo"  
    ]  
  },  
  "@context": [  
    "https://raw.githubusercontent.com/smart-data-models/dataModel.DCAT-AP/master/context.jsonld"  
  ]  
}  
```  
</details><!-- /80-Examples -->  
<!-- 90-FooterNotes -->  
<!-- /90-FooterNotes -->  
<!-- 95-Units -->  
Consulte [FAQ 10](https://smartdatamodels.org/index.php/faqs/) para obtener una respuesta sobre cómo tratar las unidades de magnitud.  
<!-- /95-Units -->  
<!-- 97-LastFooter -->  
---  
[Smart Data Models](https://smartdatamodels.org) +++ [Contribution Manual](https://bit.ly/contribution_manual) +++ [About](https://bit.ly/Introduction_SDM)<!-- /97-LastFooter -->  
