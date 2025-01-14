<!-- 10-Header -->  
[![Smart Data Models](https://smartdatamodels.org/wp-content/uploads/2022/01/SmartDataModels_logo.png "Logo")](https://smartdatamodels.org)  
エンティティカタログレコード  
==============<!-- /10-Header -->  
<!-- 15-License -->  
[オープン・ライセンス](https://github.com/smart-data-models//dataModel.DCAT-AP/blob/master/CatalogueRecord/LICENSE.md)  
[文書は自動的に生成される](https://docs.google.com/presentation/d/e/2PACX-1vTs-Ng5dIAwkg91oTTUdt8ua7woBXhPnwavZ0FxgR8BsAI_Ek3C5q97Nd94HS8KhP-r_quD4H0fgyt3/pub?start=false&loop=false&delayms=3000#slide=id.gb715ace035_0_60)  
<!-- /15-License -->  
<!-- 20-Description -->  
グローバルな記述**DCAT-AP規格2.1.1**に従ったデータセットに属するカタログレコードである。  
バージョン: 1.0.1  
<!-- /20-Description -->  
<!-- 30-PropertiesList -->  

## プロパティのリスト  

<sup><sub>[*] 属性に型がない場合は、複数の型があるか、異なるフォーマット/パターンがある可能性があるためです</sub></sup>。  
- `address[object]`: 郵送先住所  . Model: [https://schema.org/address](https://schema.org/address)- `areaServed[string]`: サービスまたは提供品が提供される地理的地域  . Model: [https://schema.org/Text](https://schema.org/Text)- `conformsTo[string]`: プロパティ。Model:'http://purl.org/dc/terms/Standard'。このプロパティは、データセットのメタデータが準拠する Application Profile を参照します。  . Model: [http://purl.org/dc/terms/Standard](http://purl.org/dc/terms/Standard)- `description[array]`: プロパティ。モデル:'http://www.w3.org/2000/01/rdf-schema#Literal'.このプロパティには、記録のフリーテキスト説明が含まれる。このプロパティは、並行言語版の説明のために繰り返すことができます。  . Model: [http://www.w3.org/2000/01/rdf-schema#Literal](http://www.w3.org/2000/01/rdf-schema#Literal)- `id[*]`: エンティティの一意識別子  - `issued[string]`: プロパティ。Model:'http://www.w3.org/2000/01/rdf-schema#Literal'.このプロパティには、データセットの説明がカタログに掲載された日付が含まれます。  . Model: [http://www.w3.org/2000/01/rdf-schema#Literal](http://www.w3.org/2000/01/rdf-schema#Literal)- `language[array]`: プロパティ。Model:'http://purl.org/dc/terms/LinguisticSystem'。このプロパティは、データセットのタイトルや説明などを記述するテキストメタデータで使用される言語を指します。メタデータが複数の言語で提供される場合は、このプロパティを繰り返すことができます。  . Model: [http://purl.org/dc/terms/LinguisticSystem](http://purl.org/dc/terms/LinguisticSystem)- `location[*]`: アイテムへの Geojson 参照。Point、LineString、Polygon、MultiPoint、MultiLineString、MultiPolygon のいずれか。  - `modified[string]`: プロパティ。モデル:'http://www.w3.org/2000/01/rdf-schema#Literal'.このプロパティには、カタログエントリが変更または修正された最新の日付が含まれます。  . Model: [http://www.w3.org/2000/01/rdf-schema#Literal](http://www.w3.org/2000/01/rdf-schema#Literal)- `primaryTopic[string]`: プロパティ。Model:'http://www.w3.org/ns/dcat#Dataset'。このプロパティは、カタログレコードを、そのレコードに記述されているデータセット、データサービス、またはカタログにリンクします。  . Model: [http://www.w3.org/ns/dcat#Dataset](http://www.w3.org/ns/dcat#Dataset)- `source[string]`: プロパティ。Model:'http://www.w3.org/ns/dcat#CatalogRecord'。このプロパティは、データセットのメタデータを作成する際に使用された元のメタデータを参照します。  . Model: [http://www.w3.org/ns/dcat#CatalogRecord](http://www.w3.org/ns/dcat#CatalogRecord)- `status[string]`: プロパティ。Model:'http://www.w3.org/2004/02/skos/core#Concept'.このプロパティは、カタログ内のデータセットのエントリの最新リビジョンのタイプを参照します。  . Model: [http://www.w3.org/2004/02/skos/core#Concept](http://www.w3.org/2004/02/skos/core#Concept)- `title[array]`: プロパティ。モデル:'http://www.w3.org/2000/01/rdf-schema#Literal'.このプロパティは、カタログレコードに与えられた名前を含む。このプロパティは、名前の並行言語バージョンに対して繰り返すことができます。  . Model: [http://www.w3.org/2000/01/rdf-schema#Literal](http://www.w3.org/2000/01/rdf-schema#Literal)- `type[string]`: プロパティ。NGSI エンティティタイプ。CatalogueRecordでなければならない。  <!-- /30-PropertiesList -->  
<!-- 35-RequiredProperties -->  
必須プロパティ  
- `id`  - `modified`  - `primaryTopic`  - `type`  <!-- /35-RequiredProperties -->  
<!-- 40-RequiredProperties -->  
DCAT-APバージョン2.1.1](https://joinup.ec.europa.eu/collection/semantic-interoperability-community-semic/solution/dcat-application-profile-data-portals-europe/release/211)より引用。  
<!-- /40-RequiredProperties -->  
<!-- 50-DataModelHeader -->  
## プロパティのデータモデル記述  
アルファベット順（クリックで詳細表示）  
<!-- /50-DataModelHeader -->  
<!-- 60-ModelYaml -->  
<details><summary><strong>full yaml details</strong></summary>    
```yaml  
CatalogueRecord:    
  description: This is a Catalogue Record belonging to a dataset according to the DCAT-AP standard 2.1.1    
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
    conformsTo:    
      description: 'Property. Model:''http://purl.org/dc/terms/Standard''. This property refers to an Application Profile that the Dataset''s metadata conforms to'    
      type: string    
      x-ngsi:    
        model: http://purl.org/dc/terms/Standard    
        type: Property    
    description:    
      description: "Property. Model:'http://www.w3.org/2000/01/rdf-schema#Literal'. This property contains a free-text account of the record. This property can be repeated for parallel language versions of the description"    
      items:    
        description: Property. Every language description    
        type: string    
      type: array    
      x-ngsi:    
        model: "http://www.w3.org/2000/01/rdf-schema#Literal"    
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
    issued:    
      description: "Property. Model:'http://www.w3.org/2000/01/rdf-schema#Literal'. This property contains the date on which the description of the Dataset was included in the Catalogue."    
      format: date-time    
      type: string    
      x-ngsi:    
        model: "http://www.w3.org/2000/01/rdf-schema#Literal"    
        type: Property    
    language:    
      description: 'Property. Model:''http://purl.org/dc/terms/LinguisticSystem''. This property refers to a language used in the textual metadata describing titles, descriptions, etc. of the Dataset. This property can be repeated if the metadata is provided in multiple languages'    
      items:    
        description: Property. Every language tag    
        type: string    
      type: array    
      x-ngsi:    
        model: http://purl.org/dc/terms/LinguisticSystem    
        type: Property    
    location:    
      description: 'Geojson reference to the item. It can be Point, LineString, Polygon, MultiPoint, MultiLineString or MultiPolygon'    
      oneOf:    
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
      description: "Property. Model:'http://www.w3.org/2000/01/rdf-schema#Literal'. This property contains the most recent date on which the Catalogue entry was changed or modified."    
      format: date-time    
      type: string    
      x-ngsi:    
        model: "http://www.w3.org/2000/01/rdf-schema#Literal"    
        type: Property    
    primaryTopic:    
      description: "Property. Model:'http://www.w3.org/ns/dcat#Dataset'. This property links the Catalogue Record to the Dataset, Data service or Catalog described in the record."    
      type: string    
      x-ngsi:    
        model: "http://www.w3.org/ns/dcat#Dataset"    
        type: Property    
    source:    
      description: "Property. Model:'http://www.w3.org/ns/dcat#CatalogRecord'. This property refers to the original metadata that was used in creating metadata for the Dataset."    
      type: string    
      x-ngsi:    
        model: "http://www.w3.org/ns/dcat#CatalogRecord"    
        type: Property    
    status:    
      description: "Property. Model:'http://www.w3.org/2004/02/skos/core#Concept'. This property refers to the type of the latest revision of a Dataset's entry in the Catalogue."    
      type: string    
      x-ngsi:    
        model: "http://www.w3.org/2004/02/skos/core#Concept"    
        type: Property    
    title:    
      description: "Property. Model:'http://www.w3.org/2000/01/rdf-schema#Literal'. This property contains a name given to the Catalogue Record. This property can be repeated for parallel language versions of the name."    
      items:    
        type: string    
      type: array    
      x-ngsi:    
        model: "http://www.w3.org/2000/01/rdf-schema#Literal"    
        type: Property    
    type:    
      description: Property. NGSI entity type. It has to be CatalogueRecord    
      enum:    
        - CatalogueRecord    
      type: string    
      x-ngsi:    
        type: Property    
  required:    
    - id    
    - type    
    - primaryTopic    
    - modified    
  type: object    
  x-derived-from: ""    
  x-disclaimer: 'Redistribution and use in source and binary forms, with or without modification, are permitted  provided that the license conditions are met. Copyleft (c) 2022 Contributors to Smart Data Models Program'    
  x-license-url: https://github.com/smart-data-models/dataModel.DCAT-AP/blob/master/CatalogueRecord/LICENSE.md    
  x-model-schema: https://smart-data-models.github.io/dataModel.DCAT-AP/CatalogueRecord/schema.json    
  x-model-tags: ""    
  x-version: 1.0.1    
```  
</details>    
<!-- /60-ModelYaml -->  
<!-- 70-MiddleNotes -->  
<!-- /70-MiddleNotes -->  
<!-- 80-Examples -->  
## ペイロードの例  
#### CatalogueRecord NGSI-v2 キー値の例  
JSON-LD形式のCatalogueRecordのkey-valuesの例である。これはNGSI-v2と互換性があり、`options=keyValues`を使用すると個々のエンティティのコンテキストデータを返す。  
<details><summary><strong>show/hide example</strong></summary>    
```json  
{  
  "id": "urn:ngsi-ld:CatalogueRecord:id:KFTL:88140679",  
  "type": "CatalogueRecord",  
  "description": ["Catalogue record of the solar system open data portal"],  
  "location": {  
    "type": "Point",  
    "coordinates": [  
      36.633152,  
      -85.183315  
    ]  
  },  
  "address": {  
    "streetAddress": "2, rue Mercier",  
    "addressLocality": "Luxembourg",  
    "addressRegion": "Luxembourg",  
    "addressCountry": "Luxembourg",  
    "postalCode": "2985",  
    "postOfficeBoxNumber": ""  
  },  
  "areaServed": "European Union and beyond",  
  "primaryTopic": "Public administration",  
  "modified": "2021-07-02T18:37:55Z",  
  "conformsTo": "DCAT Application profile for data portals in Europe",  
  "language": [  
    "EN",  
    "ES"  
  ],  
  "title": [  
    "Example of catalogue record",  
    "Ejemplo de registro de catálogo"  
  ]  
}  
```  
</details>  
#### CatalogueRecord NGSI-v2 正規化例  
以下は、正規化されたJSON-LD形式のCatalogueRecordの例である。これは、オプションを使用しない場合、NGSI-v2と互換性があり、個々のエンティティのコンテキストデータを返します。  
<details><summary><strong>show/hide example</strong></summary>    
```json  
{  
  "id": "urn:ngsi-ld:CatalogueRecord:id:KFTL:88140679",  
  "type": "CatalogueRecord",  
  "modified": {  
    "type": "DateTime",  
    "value": "2021-07-02T18:37:55Z"  
  },  
  "location": {  
    "type": "geo:json",  
    "value": {  
      "type": "Point",  
      "coordinates": [  
        36.633152,  
        -85.183315  
      ]  
    }  
  },  
  "address": {  
    "type": "PostalAdress",  
    "value": {  
      "streetAddress": "2, rue Mercier",  
      "addressLocality": "Luxembourg",  
      "addressRegion": "Luxembourg",  
      "addressCountry": "Luxembourg",  
      "postalCode": "2985",  
      "postOfficeBoxNumber": ""  
    }  
  },  
  "areaServed": {  
    "type": "Text",  
    "value": "European Union and beyond"  
  },  
  "primaryTopic": {  
    "type": "Text",  
    "value": "Public administration"  
  },  
  "language": {  
    "type": "array",  
    "value": [  
      "EN",  
      "ES"  
    ]  
  },  
  "title": {  
    "type": "array",  
    "value": [  
      "Example of catalogue record",  
      "Ejemplo de registro de catálogo"  
    ]  
  }  
}  
```  
</details>  
#### CatalogueRecord NGSI-LD キー値の例  
これはJSON-LD形式のCatalogueRecordをkey-valuesとした例である。options=keyValues`を使うとNGSI-LDと互換性があり、個々のエンティティのコンテキストデータを返す。  
<details><summary><strong>show/hide example</strong></summary>    
```json  
{  
    "id": "urn:ngsi-ld:CatalogueRecord:id:KFTL:88140679",  
    "type": "CatalogueRecord",  
    "address": {  
        "streetAddress": "2, rue Mercier",  
        "addressLocality": "Luxembourg",  
        "addressRegion": "Luxembourg",  
        "addressCountry": "Luxembourg",  
        "postalCode": "2985",  
        "postOfficeBoxNumber": ""  
    },  
    "areaServed": "European Union and beyond",  
    "modified": "2021-07-02T18:37:55Z",  
    "description": ["Catalogue record of the solar system open data portal"],  
    "language": [  
        "EN",  
        "ES"  
    ],  
    "location": {  
        "type": "Point",  
        "coordinates": [  
            36.633152,  
            -85.183315  
        ]  
    },  
    "primaryTopic": "Public administration",  
    "title": [  
        "Example of catalogue record",  
        "Ejemplo de registro de cat\u00e1logo"  
    ],  
    "@context": [  
        "https://raw.githubusercontent.com/smart-data-models/dataModel.DCAT-AP/master/context.jsonld"  
    ]  
}  
```  
</details>  
#### CatalogueRecord NGSI-LD 正規化例  
以下は、正規化された JSON-LD 形式の CatalogueRecord の例である。これは、オプションを使用しない場合はNGSI-LDと互換性があり、個々のエンティティのコンテキストデータを返します。  
<details><summary><strong>show/hide example</strong></summary>    
```json  
{  
  "id": "urn:ngsi-ld:CatalogueRecord:id:KFTL:88140679",  
  "type": "CatalogueRecord",  
  "address": {  
    "type": "Property",  
    "value": {  
      "streetAddress": "2, rue Mercier",  
      "addressLocality": "Luxembourg",  
      "addressRegion": "Luxembourg",  
      "addressCountry": "Luxembourg",  
      "postalCode": "2985",  
      "postOfficeBoxNumber": ""  
    }  
  },  
  "language": {  
    "type": "Property",  
    "value": [  
      "EN",  
      "ES"  
    ]  
  },  
  "listingDate": {  
    "type": {  
      "@type": "Property",  
      "@value": "2021-07-02T18:37:55Z"  
    }  
  },  
  "location": {  
    "type": "GeoProperty",  
    "value": {  
      "type": "Point",  
      "coordinates": [  
        36.633152,  
        -85.183315  
      ]  
    }  
  },  
  "modified": {  
    "type": {  
      "@type": "Property",  
      "@value": "2021-07-02T18:37:55Z"  
    }  
  },  
  "primaryTopic": {  
    "type": "Property",  
    "value": "Public administration"  
  },  
  "title": {  
    "type": "Property",  
    "value": [  
      "Example of catalogue record",  
      "Ejemplo de registro de cat\u00e1logo"  
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
マグニチュード単位の扱い方については、[FAQ 10](https://smartdatamodels.org/index.php/faqs/)を参照のこと。  
<!-- /95-Units -->  
<!-- 97-LastFooter -->  
---  
[Smart Data Models](https://smartdatamodels.org) +++ [Contribution Manual](https://bit.ly/contribution_manual) +++ [About](https://bit.ly/Introduction_SDM)<!-- /97-LastFooter -->  
