<!-- 10-Header -->
  
[![Smart Data Models](https://smartdatamodels.org/wp-content/uploads/2022/01/SmartDataModels_logo.png "Logo")](https://smartdatamodels.org)  

エンティティカタログDCAT-AP  
=================
<!-- /10-Header -->
  
<!-- 15-License -->
  

[オープンライセンス](https://github.com/smart-data-models//dataModel.DCAT-AP/blob/master/CatalogueDCAT-AP/LICENSE.md)  

[文書が自動的に生成されます](https://docs.google.com/presentation/d/e/2PACX-1vTs-Ng5dIAwkg91oTTUdt8ua7woBXhPnwavZ0FxgR8BsAI_Ek3C5q97Nd94HS8KhP-r_quD4H0fgyt3/pub?start=false&loop=false&delayms=3000#slide=id.gb715ace035_0_60)  
<!-- /15-License -->
  
<!-- 20-Description -->
  

グローバルな記述です：**DCAT-AP仕様に準拠したデータセットのカタログ**。  

バージョン：0.0.2  
<!-- /20-Description -->
  
<!-- 30-PropertiesList -->
  


## プロパティ一覧  


<sup><sub>[*] 属性に型がない場合は、複数の型や異なるフォーマット/パターンを持つ可能性があるためです</sub></sup>。  
- `address[object]`: 郵送先住所  . Model: [https://schema.org/address](https://schema.org/address)
- `alternateName[string]`: このアイテムの別称  
- `areaServed[string]`: サービスまたは提供されるアイテムが提供される地理的な地域  . Model: [https://schema.org/Text](https://schema.org/Text)
- `catalogue[array]`: 関係です。モデル：'dcat:catalog'.このプロパティは、このカタログのコンテキストで関心のある内容を持つカタログを参照する  . Model: [dcat:catalog](dcat:catalog)
- `creator[string]`: プロパティです。モデル:'https://schema.org/Text'.このプロパティは、カタログの制作を主に担当するエンティティを指します  . Model: [https://schema.org/Text](https://schema.org/Text)
- `dataProvider[string]`: 調和されたデータエンティティの提供者を識別する一連の文字。  
- `dataset[array]`: 関係。このプロパティは、カタログと、カタログの一部であるDatasetをリンクします。モデル:'dcat:Dataset'  . Model: [dcat:Dataset](dcat:Dataset)
- `dateCreated[string]`: エンティティの作成タイムスタンプ。これは通常、ストレージプラットフォームによって割り当てられる。  
- `dateModified[string]`: エンティティの最終更新のタイムスタンプ。これは通常、ストレージプラットフォームによって割り当てられる。  
- `description[string]`: このアイテムの説明  
- `hasPart[array]`: 関係です。モデル:'https://schema.org/URL'.このプロパティは、記述されたカタログの一部である関連カタログを参照します。  . Model: [https://schema.org/URL](https://schema.org/URL)
- `homepage[string]`: プロパティです。モデル：'foaf:homepage'.このプロパティは、カタログのメインページとして機能するウェブページを参照する。  . Model: [foaf:homepage](foaf:homepage)
- `id[*]`: エンティティの一意な識別子  
- `isPartOf[string]`: 関係です。モデル:'https://schema.org/URL'.このプロパティは、記述されたカタログが物理的または論理的に含まれる関連カタログを指します。  . Model: [https://schema.org/URL](https://schema.org/URL)
- `language[array]`: プロパティです。Model:'dct:language'.このプロパティは、カタログのデータセットのタイトルや説明などを記述するテキストメタデータで使用される言語を指します。このプロパティは、メタデータが複数の言語で提供される場合に繰り返すことができる。  . Model: [dct:language](dct:language)
- `licence[string]`: プロパティです。Model:'dct:license'.このプロパティは、カタログの使用または再利用が可能なライセンスを指す。  . Model: [dct:license](dct:license)
- `location[*]`: アイテムへの Geojson 参照。Point, LineString, Polygon, MultiPoint, MultiLineString, MultiPolygon のいずれかである。  
- `modificationDate[string]`: プロパティです。モデル:'https://schema.org/DateTime'.このプロパティには、カタログが修正された最新の日付が含まれます。  . Model: [https://schema.org/DateTime](https://schema.org/DateTime)
- `name[string]`: この項目の名称です。  
- `owner[array]`: 所有者の固有IDを参照するJSONエンコードされた文字列を含むリストです。  
- `publisher[string]`: プロパティです。モデル:'https://schema.org/Text'.このプロパティは、カタログを利用可能にする責任を負うエンティティ（組織）を指します。モデル:'dct:publisher'  . Model: [dct:publisher](dct:publisher)
- `record[array]`: 関係を示す。このプロパティは、カタログの一部であるカタログレコードを参照します。  
- `releaseDate[string]`: プロパティです。モデル:'https://schema.org/DateTime'.このプロパティには、カタログの正式発行（発行など）の日付が含まれています。  . Model: [https://schema.org/DateTime](https://schema.org/DateTime)
- `rights[string]`: プロパティです。モデル：'dct:rights'.このプロパティは、カタログに関連する権利を指定するステートメントを参照する。  . Model: [dct:rights](dct:rights)
- `seeAlso[*]`: アイテムに関する追加リソースを指す URI のリスト。  
- `service[array]`: プロパティです。このプロパティは、カタログに掲載されているサイトまたはエンドポイントを指します。モデル:'dcat:DataService'  . Model: [dcat:DataService](dcat:DataService)
- `source[string]`: エンティティデータの元のソースをURLとして与える一連の文字。ソースプロバイダの完全修飾ドメイン名、またはソースオブジェクトのURLであることが推奨されます。  
- `spatial_geographic[array]`: ジオプロパティ。このプロパティは、カタログの対象となる地理的な領域を指す。モデル：'dct:spatial'  . Model: [dct:spatial](dct:spatial)
- `themes[array]`: プロパティです。Model:'dcat:themeTaxonomy'.このプロパティは、CatalogueのDatasetを分類するために使用される知識組織システムを指します。  . Model: [dcat:themeTaxonomy](dcat:themeTaxonomy)
- `title[array]`: プロパティです。モデル:'https://schema.org/URL'.このプロパティには、カタログに与えられた名前が含まれています。このプロパティは、名前の並行言語版に対して繰り返すことができる。モデル:'rdfs:Literal'。  . Model: [rdfs:Literal](rdfs:Literal)
- `type[string]`: プロパティです。モデル：'https://schema.org/Text'.CatalogueDCAT-APである必要があります。  . Model: [https://schema.org/Text](https://schema.org/Text)
<!-- /30-PropertiesList -->
  
<!-- 35-RequiredProperties -->
  

必須プロパティ  
- `dataset`  
- `description`  
- `id`  
- `publisher`  
- `title`  
- `type`  
<!-- /35-RequiredProperties -->
  
<!-- 40-RequiredProperties -->
  

このデータモデルと主題DCAT-APの他のものは、彼らの使用のために適応されており、追加のコンテキストが含まれることが推奨されるであろう。[https://raw.githubusercontent.com/SEMICeu/DCAT-AP/master/releases/1.1/dcat-ap_1.1.jsonld" ](https://raw.githubusercontent.com/SEMICeu/DCAT-AP/master/releases/1.1/dcat-ap_1.1.jsonld)  
<!-- /40-RequiredProperties -->
  
<!-- 50-DataModelHeader -->
  

## プロパティのデータモデル記述  

アルファベット順（クリックで詳細表示）  
<!-- /50-DataModelHeader -->
  
<!-- 60-ModelYaml -->
  
<details><summary><strong>full yaml details</strong></summary>    

```yaml  
CatalogueDCAT-AP:    
  description: Catalogue of datasets compliant with DCAT-AP specification.    
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
    alternateName:    
      description: An alternative name for this item    
      type: string    
      x-ngsi:    
        type: Property    
    areaServed:    
      description: The geographic area where a service or offered item is provided    
      type: string    
      x-ngsi:    
        model: https://schema.org/Text    
        type: Property    
    catalogue:    
      description: 'Relationship. Model:''dcat:catalog''. This property refers to a catalog whose contents are of interest in the context of this catalog'    
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
        model: dcat:catalog    
        type: Relationship    
    creator:    
      description: 'Property. Model:''https://schema.org/Text''. This property refers to the entity primarily responsible for producing the catalogue'    
      type: string    
      x-ngsi:    
        model: https://schema.org/Text    
        type: Property    
    dataProvider:    
      description: A sequence of characters identifying the provider of the harmonised data entity.    
      type: string    
      x-ngsi:    
        type: Property    
    dataset:    
      description: 'Relationship. This property links the Catalogue with a Dataset that is part of the Catalogue. Model:''dcat:Dataset'''    
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
        model: dcat:Dataset    
        type: Relationship    
    dateCreated:    
      description: Entity creation timestamp. This will usually be allocated by the storage platform.    
      format: date-time    
      type: string    
      x-ngsi:    
        type: Property    
    dateModified:    
      description: Timestamp of the last modification of the entity. This will usually be allocated by the storage platform.    
      format: date-time    
      type: string    
      x-ngsi:    
        type: Property    
    description:    
      description: A description of this item    
      type: string    
      x-ngsi:    
        type: Property    
    hasPart:    
      description: 'Relationship. Model:''https://schema.org/URL''. This property refers to a related Catalogue that is part of the described Catalogue'    
      items:    
        format: uri    
        type: string    
      type: array    
      x-ngsi:    
        model: https://schema.org/URL    
        type: Relationship    
    homepage:    
      description: 'Property. Model:''foaf:homepage''. This property refers to a web page that acts as the main page for the Catalogue.'    
      format: uri    
      type: string    
      x-ngsi:    
        model: foaf:homepage    
        type: Property    
    id:    
      anyOf: &cataloguedcat-ap_-_properties_-_owner_-_items_-_anyof    
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
      description: 'Relationship. Model:''https://schema.org/URL''. This property refers to a related Catalogue in which the described Catalogue is physically or logically included.'    
      format: uri    
      type: string    
      x-ngsi:    
        model: https://schema.org/URL    
        type: Relationship    
    language:    
      description: 'Property. Model:''dct:language''. This property refers to a language used in the textual metadata describing titles, descriptions, etc. of the Datasets in the Catalogue. This property can be repeated if the  metadata is provided in multiple languages.'    
      items:    
        type: string    
      type: array    
      x-ngsi:    
        model: dct:language    
        type: Property    
    licence:    
      description: 'Property. Model:''dct:license''. This property refers to the licence under which the Catalogue can be used or reused.'    
      type: string    
      x-ngsi:    
        model: dct:license    
        type: Property    
    location:    
      description: 'Geojson reference to the item. It can be Point, LineString, Polygon, MultiPoint, MultiLineString or MultiPolygon'    
      oneOf: &cataloguedcat-ap_-_properties_-_spatial_geographic_-_items_-_oneof    
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
    modificationDate:    
      description: 'Property. Model:''https://schema.org/DateTime''. This property contains the most recent date on which the Catalogue was modified.'    
      format: date-time    
      type: string    
      x-ngsi:    
        model: https://schema.org/DateTime    
        type: Property    
    name:    
      description: The name of this item.    
      type: string    
      x-ngsi:    
        type: Property    
    owner:    
      description: A List containing a JSON encoded sequence of characters referencing the unique Ids of the owner(s)    
      items:    
        anyOf: *cataloguedcat-ap_-_properties_-_owner_-_items_-_anyof    
        description: Property. Unique identifier of the entity    
      type: array    
      x-ngsi:    
        type: Property    
    publisher:    
      description: 'Property. Model:''https://schema.org/Text''. This property refers to an entity (organisation) responsible for making the Catalogue available. Model:''dct:publisher'''    
      type: string    
      x-ngsi:    
        model: dct:publisher    
        type: Property    
    record:    
      description: Relationship. This property refers to a Catalogue Record that is part of the Catalogue    
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
        type: Relationship    
    releaseDate:    
      description: 'Property. Model:''https://schema.org/DateTime''. This property contains the date of formal issuance (e.g., publication) of the Catalogue.'    
      format: date-time    
      type: string    
      x-ngsi:    
        model: https://schema.org/DateTime    
        type: Property    
    rights:    
      description: 'Property. Model:''dct:rights''. This property refers to a statement that specifies rights associated with the Catalogue.'    
      type: string    
      x-ngsi:    
        model: dct:rights    
        type: Property    
    seeAlso:    
      description: list of uri pointing to additional resources about the item    
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
    service:    
      description: 'Property. This property refers to a site or end-point that is listed in the catalog. Model:''dcat:DataService'''    
      items:    
        type: string    
      type: array    
      x-ngsi:    
        model: dcat:DataService    
        type: Property    
    source:    
      description: 'A sequence of characters giving the original source of the entity data as a URL. Recommended to be the fully qualified domain name of the source provider, or the URL to the source object.'    
      type: string    
      x-ngsi:    
        type: Property    
    spatial_geographic:    
      description: 'GeoProperty. This property refers to a geographical area covered by the Catalogue. Model:''dct:spatial'''    
      items:    
        description: 'GeoProperty. Geojson reference to the item. It can be Point, LineString, Polygon, MultiPoint, MultiLineString or MultiPolygon'    
        oneOf: *cataloguedcat-ap_-_properties_-_spatial_geographic_-_items_-_oneof    
      type: array    
      x-ngsi:    
        model: dct:spatial    
    themes:    
      description: 'Property. Model:''dcat:themeTaxonomy''. This property refers to a knowledge organization system used to classify the Catalogue''s Datasets.'    
      items:    
        type: string    
      type: array    
      x-ngsi:    
        model: dcat:themeTaxonomy    
        type: Property    
    title:    
      description: 'Property. Model:''https://schema.org/URL''. This property contains a name given to the Catalogue. This property can be repeated for parallel language versions of the name. Model:''rdfs:Literal'''    
      items:    
        type: string    
      type: array    
      x-ngsi:    
        model: rdfs:Literal    
        type: Property    
    type:    
      description: 'Property. Model:''https://schema.org/Text''. It has to be CatalogueDCAT-AP'    
      enum:    
        - CatalogueDCAT-AP    
      type: string    
      x-ngsi:    
        model: https://schema.org/Text    
        type: Property    
  required:    
    - id    
    - type    
    - dataset    
    - description    
    - publisher    
    - title    
  type: object    
  x-derived-from: ""    
  x-disclaimer: 'Redistribution and use in source and binary forms, with or without modification, are permitted  provided that the license conditions are met. Copyleft (c) 2022 Contributors to Smart Data Models Program'    
  x-license-url: https://github.com/smart-data-models/dataModel.DCAT-AP/blob/master/CatalogueDCAT-AP/LICENSE.md    
  x-model-schema: https://smart-data-models.github.io/dataModel.DCAT-AP/CatalogueDCAT-AP/schema.json    
  x-model-tags: ""    
  x-version: 0.0.2    
```  
</details>    
<!-- /60-ModelYaml -->
  
<!-- 70-MiddleNotes -->
  
<!-- /70-MiddleNotes -->
  
<!-- 80-Examples -->
  

## ペイロードの例  

#### CatalogueDCAT-AP NGSI-v2 key-values Example  

ここでは、CatalogueDCAT-APをJSON-LD形式でkey-valuesとした例を示します。これは、`options=keyValues`を使用した場合にNGSI-v2と互換性があり、個々のエンティティのコンテキストデータを返します。  
<details><summary><strong>show/hide example</strong></summary>    

```json  

{  
  "id": "urn:ngsi-ld:Catalogue:id:LMVP:18269678",  
  "type": "CatalogueDCAT-AP",  
  "dateCreated": "1980-03-03T10:01:24Z",  
  "dateModified": "1987-12-04T10:44:40Z",  
  "source": "",  
  "name": "Catalogue",  
  "alternateName": "",  
  "description": "Interesting art recently book girl yard represent book. Garden style wish blood your ground size.",  
  "dataProvider": "european open data portal",  
  "owner": [  
    "urn:ngsi-ld:Catalogue:ZYKY:89462950"  
  ],  
  "seeAlso": [  
    "urn:ngsi-ld:Catalogue:ILBA:60770941"  
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
  "releaseDate": "2004-08-22T22:32:47Z",  
  "spatial_geographic": [  
    {  
      "type": "Point",  
      "coordinates": [  
        57.234944,  
        52.840273  
      ]  
    }  
  ],  
  "themes": [  
    "Want couple him finally responsibility begin. Coach join down new major. Happy yard letter then return member.",  
    "Politics road two question offer white. Recognize fight keep blue person create be. Radio edge or improve less special future. Itself detail computer exist."  
  ],  
  "modificationDate": "1982-09-02T03:16:28Z",  
  "hasPart": [  
    "urn:ngsi-ld:Catalogue:hasPart:GVZM:66676591"  
  ],  
  "isPartOf": "urn:ngsi-ld:Catalogue:isPartOf:NXBZ:88517287",  
  "record": [  
    "Catalogue.items.HLGA.73285516",  
    "Catalogue.items.IHOB.85266800"  
  ],  
  "rights": "",  
  "catalogue": [  
    "urn:ngsi-ld:Catalogue:items:LZMQ:44249979",  
    "urn:ngsi-ld:Catalogue:items:PECX:02526105"  
  ],  
  "creator": "Role fact sport shoulder blue direction probably order."  
}  
```  
</details>  

#### CatalogueDCAT-AP NGSI-v2 正規化例  

JSON-LD形式のCatalogueDCAT-APを正規化した例を示します。これは、オプションを使用しない場合、NGSI-v2と互換性があり、個々のエンティティのコンテキストデータを返します。  
<details><summary><strong>show/hide example</strong></summary>    

```json  

{  
  "id": "urn:ngsi-ld:Catalogue:id:LMVP:18269678",  
  "type": "CatalogueDCAT-AP",  
  "dateCreated": {  
    "type": "DateTime",  
    "value": "1980-03-03T10:01:24Z"  
  },  
  "dateModified": {  
    "type": "DateTime",  
    "value": "1987-12-04T10:44:40Z"  
  },  
  "source": {  
    "type": "Text",  
    "value": ""  
  },  
  "name": {  
    "type": "Text",  
    "value": "Catalogue"  
  },  
  "alternateName": {  
    "type": "Text",  
    "value": ""  
  },  
  "description": {  
    "type": "Text",  
    "value": "Interesting art recently book girl yard represent book. Garden style wish blood your ground size."  
  },  
  "dataProvider": {  
    "type": "Text",  
    "value": "european open data portal"  
  },  
  "owner": {  
    "type": "Array",  
    "value": [  
      "urn:ngsi-ld:Catalogue:ZYKY:89462950"  
    ]  
  },  
  "seeAlso": {  
    "type": "Array",  
    "value": [  
      "urn:ngsi-ld:Catalogue:ILBA:60770941"  
    ]  
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
    "type": "object",  
    "value": "urn:ngsi-ld:Catalogue:dataset:ZBCW:95668818"  
  },  
  "publisher": {  
    "type": "Property",  
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
    "type": "string",  
    "value": "urn:ngsi-ld:Catalogue:homepage:ZFAW:13633782"  
  },  
  "language": {  
    "type": "Array",  
    "value": [  
      "Town size computer way. Since challenge phone state listen south low.",  
      "Eight once single. Build every kid."  
    ]  
  },  
  "licence": {  
    "type": "Property",  
    "value": "Improve social simply court week debate bad. Structure ago cup head point. Above much can own course."  
  },  
  "releaseDate": {  
    "type": "DateTime",  
    "value": "2004-08-22T22:32:47Z"  
  },  
  "spatial_geographic": {  
    "type": "Property",  
    "value": {  
      "type": "Point",  
      "coordinates": [  
        57.234944,  
        52.840273  
      ]  
    }  
  },  
  "themes": {  
    "type": "Array",  
    "value": [  
      "Want couple him finally responsibility begin. Coach join down new major. Happy yard letter then return member.",  
      "Politics road two question offer white. Recognize fight keep blue person create be. Radio edge or improve less special future. Itself detail computer exist."  
    ]  
  },  
  "modificationDate": {  
    "type": "DateTime",  
    "value": "1982-09-02T03:16:28Z"  
  },  
  "hasPart": {  
    "type": "object",  
    "value": "urn:ngsi-ld:Catalogue:hasPart:GVZM:66676591"  
  },  
  "isPartOf": {  
    "type": "object",  
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
    "type": "Property",  
    "value": "Open source"  
  },  
  "catalogue": {  
    "type": "Array",  
    "value": [  
      "urn:ngsi-ld:Catalogue:items:LZMQ:44249979",  
      "urn:ngsi-ld:Catalogue:items:PECX:02526105"  
    ]  
  },  
  "creator": {  
    "type": "Text",  
    "value": "Role fact sport shoulder blue direction probably order."  
  }  
}  
```  
</details>  

#### CatalogueDCAT-AP NGSI-LD キー値例  

ここでは、CatalogueDCAT-APをJSON-LD形式でkey-valuesとした例を示します。これは、`options=keyValues`を使用した場合にNGSI-LDと互換性があり、個々のエンティティのコンテキストデータを返します。  
<details><summary><strong>show/hide example</strong></summary>    

```json  

{  
    "id": "urn:ngsi-ld:Catalogue:id:LMVP:18269678",  
    "type": "CatalogueDCAT-AP",  
    "address": {  
        "streetAddress": "2 Rue Mercier",  
        "addressLocality": "Luxembourg",  
        "addressRegion": "Luxembourg",  
        "addressCountry": "Luxembourg",  
        "postalCode": "2985 ",  
        "postOfficeBoxNumber": "",  
        "areaServed": "European Union"  
    },  
    "alternateName": "",  
    "catalogue": [  
        "urn:ngsi-ld:Catalogue:items:LZMQ:44249979",  
        "urn:ngsi-ld:Catalogue:items:PECX:02526105"  
    ],  
    "creator": "Role fact sport shoulder blue direction probably order.",  
    "dataProvider": "european open data portal",  
    "dataset": [  
        "urn:ngsi-ld:Catalogue:dataset:ZBCW:95668818"  
    ],  
    "dateCreated": "1980-03-03T10:01:24Z",  
    "dateModified": "1987-12-04T10:44:40Z",  
    "description": "Interesting art recently book girl yard represent book. Garden style wish blood your ground size.",  
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
    "modificationDate": "1982-09-02T03:16:28Z",  
    "name": "Catalogue",  
    "owner": [  
        "urn:ngsi-ld:Catalogue:ZYKY:89462950"  
    ],  
    "publisher": "Spanish data portal",  
    "record": [  
        "Catalogue.items.HLGA.73285516",  
        "Catalogue.items.IHOB.85266800"  
    ],  
    "releaseDate": "2004-08-22T22:32:47Z",  
    "rights": "",  
    "seeAlso": [  
        "urn:ngsi-ld:Catalogue:ILBA:60770941"  
    ],  
    "source": "",  
    "spatial_geographic": [  
        {  
            "type": "Point",  
            "coordinates": [  
                57.234944,  
                52.840273  
            ]  
        }  
    ],  
    "themes": [  
        "Want couple him finally responsibility begin. Coach join down new major. Happy yard letter then return member.",  
        "Politics road two question offer white. Recognize fight keep blue person create be. Radio edge or improve less special future. Itself detail computer exist."  
    ],  
    "title": [  
        "title first",  
        "Secondary title."  
    ],  
    "@context": [  
        "https://raw.githubusercontent.com/SEMICeu/DCAT-AP/master/releases/1.1/dcat-ap_1.1.jsonld",  
        "https://raw.githubusercontent.com/smart-data-models/dataModel.DCAT-AP/master/context.jsonld"  
    ]  
}  
```  
</details>  

#### CatalogueDCAT-AP NGSI-LD 正規化例  

JSON-LD形式のCatalogueDCAT-APを正規化した例を示します。オプションを使用しない場合のNGSI-LDとの互換性があり、個々のエンティティのコンテキストデータを返します。  
<details><summary><strong>show/hide example</strong></summary>    

```json  

{  
  "id": "urn:ngsi-ld:Catalogue:id:LMVP:18269678",  
  "type": "CatalogueDCAT-AP",  
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
  "alternateName": {  
    "type": "Property",  
    "value": ""  
  },  
  "catalogue": {  
    "type": "Relationship",  
    "value": [  
      "urn:ngsi-ld:Catalogue:items:LZMQ:44249979",  
      "urn:ngsi-ld:Catalogue:items:PECX:02526105"  
    ]  
  },  
  "creator": {  
    "type": "Property",  
    "value": ""  
  },  
  "dataProvider": {  
    "type": "Property",  
    "value": "European open data portal"  
  },  
  "dataset": {  
    "type": "Relationship",  
    "object": [  
      "urn:ngsi-ld:Catalogue:dataset:ZBCW:95668818"  
    ]  
  },  
  "dateCreated": {  
    "type": "Property",  
    "value": {  
      "@type": "DateTime",  
      "@value": "2020-03-03T10:01:24Z"  
    }  
  },  
  "dateModified": {  
    "type": "Property",  
    "value": {  
      "@type": "DateTime",  
      "@value": "2021-07-04T10:44:40Z"  
    }  
  },  
  "description": {  
    "type": "Property",  
    "value": ""  
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
    "value": [  
      "Creative Commons 3.0 International"  
    ]  
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
  "modificationDate": {  
    "type": "DateTime",  
    "value": "1982-09-02T03:16:28Z"  
  },  
  "name": {  
    "type": "Property",  
    "value": "Catalogue"  
  },  
  "owner": {  
    "type": "Property",  
    "value": [  
      "urn:ngsi-ld:Catalogue:ZYKY:89462950"  
    ]  
  },  
  "publisher": {  
    "type": "Property",  
    "value": "Spain open data portal"  
  },  
  "record": {  
    "type": "Property",  
    "value": [  
      "Catalogue.items.HLGA.73285516",  
      "Catalogue.items.IHOB.85266800"  
    ]  
  },  
  "releaseDate": {  
    "type": "DateTime",  
    "value": "2004-08-22T22:32:47Z"  
  },  
  "rights": {  
    "type": "Property",  
    "value": ""  
  },  
  "seeAlso": {  
    "type": "Property",  
    "value": [  
      "urn:ngsi-ld:Catalogue:ILBA:60770941"  
    ]  
  },  
  "source": {  
    "type": "Property",  
    "value": ""  
  },  
  "spatial_geographic": {  
    "type": "GeoProperty",  
    "value": {  
      "type": "Point",  
      "coordinates": [  
        57.234944,  
        52.840273  
      ]  
    }  
  },  
  "themes": {  
    "type": "Property",  
    "value": [  
      "Want couple him finally responsibility begin. Coach join down new major. Happy yard letter then return member.",  
      "Politics road two question offer white. Recognize fight keep blue person create be. Radio edge or improve less special future. Itself detail computer exist."  
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
    "https://raw.githubusercontent.com/SEMICeu/DCAT-AP/master/releases/1.1/dcat-ap_1.1.jsonld",  
    "https://raw.githubusercontent.com/smart-data-models/dataModel.DCAT-AP/master/context.jsonld"  
  ]  
}  
```  
</details><!-- /80-Examples -->
  
<!-- 90-FooterNotes -->
  
<!-- /90-FooterNotes -->
  
<!-- 95-Units -->
  

マグニチュード単位の扱いについては、[FAQ 10](https://smartdatamodels.org/index.php/faqs/)を参照してください。  
<!-- /95-Units -->
  
<!-- 97-LastFooter -->
  
---  

[Smart Data Models](https://smartdatamodels.org) +++ [Contribution Manual](https://bit.ly/contribution_manual) +++ [About](https://bit.ly/Introduction_SDM)<!-- /97-LastFooter -->
  