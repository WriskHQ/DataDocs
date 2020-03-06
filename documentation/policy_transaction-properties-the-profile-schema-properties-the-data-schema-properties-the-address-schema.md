# The Address Schema Schema

```txt
#/properties/profile/properties/data/properties/address#/properties/profile/properties/data/properties/address
```

An explanation about the purpose of this instance.


| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                       |
| :------------------ | ---------- | -------------- | ------------ | :---------------- | --------------------- | ------------------- | ------------------------------------------------------------------------------------------------ |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [policy_transaction.schema.json\*](../out/policy_transaction.schema.json "open original schema") |

## address Type

`object` ([The Address Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-address-schema.md))

## address Default Value

The default value is:

```json
{}
```

## address Examples

```json
{
  "type": "Residential",
  "countryName": "United Kingdom",
  "pcaId": "GB|RM|B|15592178",
  "postalCode": "N40 3UP",
  "city": "London",
  "countryIso2": "GB",
  "countryIso3": "GBR",
  "street": "Woodland Rise",
  "buildingName": "19C",
  "sortingNumber1": "62123",
  "line1": "19C Woodland Rise",
  "domesticId": "15592178",
  "languageAlternatives": "ENG",
  "barcode": "(N403UP2AH)",
  "label": "19C Woodland Rise\nLONDON\nN40 3UP\nUNITED KINGDOM",
  "countryIsoNumber": "826",
  "dataLevel": "Premise",
  "adminAreaName": "Haringey",
  "language": "ENG"
}
```

# The Address Schema Properties

| Property                                      | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                                                                                                   |
| :-------------------------------------------- | -------- | -------- | -------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [city](#city)                                 | `string` | Required | cannot be null | [The Root Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-address-schema-properties-the-city-schema.md "\#/properties/profile/properties/data/properties/address/properties/city#/properties/profile/properties/data/properties/address/properties/city")                                                 |
| [type](#type)                                 | `string` | Required | cannot be null | [The Root Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-address-schema-properties-the-type-schema.md "\#/properties/profile/properties/data/properties/address/properties/type#/properties/profile/properties/data/properties/address/properties/type")                                                 |
| [label](#label)                               | `string` | Required | cannot be null | [The Root Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-address-schema-properties-the-label-schema.md "\#/properties/profile/properties/data/properties/address/properties/label#/properties/profile/properties/data/properties/address/properties/label")                                              |
| [line1](#line1)                               | `string` | Required | cannot be null | [The Root Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-address-schema-properties-the-line1-schema.md "\#/properties/profile/properties/data/properties/address/properties/line1#/properties/profile/properties/data/properties/address/properties/line1")                                              |
| [pcaId](#pcaId)                               | `string` | Required | cannot be null | [The Root Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-address-schema-properties-the-pcaid-schema.md "\#/properties/profile/properties/data/properties/address/properties/pcaId#/properties/profile/properties/data/properties/address/properties/pcaId")                                              |
| [street](#street)                             | `string` | Required | cannot be null | [The Root Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-address-schema-properties-the-street-schema.md "\#/properties/profile/properties/data/properties/address/properties/street#/properties/profile/properties/data/properties/address/properties/street")                                           |
| [barcode](#barcode)                           | `string` | Required | cannot be null | [The Root Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-address-schema-properties-the-barcode-schema.md "\#/properties/profile/properties/data/properties/address/properties/barcode#/properties/profile/properties/data/properties/address/properties/barcode")                                        |
| [language](#language)                         | `string` | Required | cannot be null | [The Root Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-address-schema-properties-the-language-schema.md "\#/properties/profile/properties/data/properties/address/properties/language#/properties/profile/properties/data/properties/address/properties/language")                                     |
| [dataLevel](#dataLevel)                       | `string` | Required | cannot be null | [The Root Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-address-schema-properties-the-datalevel-schema.md "\#/properties/profile/properties/data/properties/address/properties/dataLevel#/properties/profile/properties/data/properties/address/properties/dataLevel")                                  |
| [domesticId](#domesticId)                     | `string` | Required | cannot be null | [The Root Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-address-schema-properties-the-domesticid-schema.md "\#/properties/profile/properties/data/properties/address/properties/domesticId#/properties/profile/properties/data/properties/address/properties/domesticId")                               |
| [postalCode](#postalCode)                     | `string` | Required | cannot be null | [The Root Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-address-schema-properties-the-postalcode-schema.md "\#/properties/profile/properties/data/properties/address/properties/postalCode#/properties/profile/properties/data/properties/address/properties/postalCode")                               |
| [countryIso2](#countryIso2)                   | `string` | Required | cannot be null | [The Root Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-address-schema-properties-the-countryiso2-schema.md "\#/properties/profile/properties/data/properties/address/properties/countryIso2#/properties/profile/properties/data/properties/address/properties/countryIso2")                            |
| [countryIso3](#countryIso3)                   | `string` | Required | cannot be null | [The Root Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-address-schema-properties-the-countryiso3-schema.md "\#/properties/profile/properties/data/properties/address/properties/countryIso3#/properties/profile/properties/data/properties/address/properties/countryIso3")                            |
| [countryName](#countryName)                   | `string` | Required | cannot be null | [The Root Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-address-schema-properties-the-countryname-schema.md "\#/properties/profile/properties/data/properties/address/properties/countryName#/properties/profile/properties/data/properties/address/properties/countryName")                            |
| [buildingName](#buildingName)                 | `string` | Required | cannot be null | [The Root Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-address-schema-properties-the-buildingname-schema.md "\#/properties/profile/properties/data/properties/address/properties/buildingName#/properties/profile/properties/data/properties/address/properties/buildingName")                         |
| [adminAreaName](#adminAreaName)               | `string` | Required | cannot be null | [The Root Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-address-schema-properties-the-adminareaname-schema.md "\#/properties/profile/properties/data/properties/address/properties/adminAreaName#/properties/profile/properties/data/properties/address/properties/adminAreaName")                      |
| [sortingNumber1](#sortingNumber1)             | `string` | Required | cannot be null | [The Root Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-address-schema-properties-the-sortingnumber1-schema.md "\#/properties/profile/properties/data/properties/address/properties/sortingNumber1#/properties/profile/properties/data/properties/address/properties/sortingNumber1")                   |
| [countryIsoNumber](#countryIsoNumber)         | `string` | Required | cannot be null | [The Root Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-address-schema-properties-the-countryisonumber-schema.md "\#/properties/profile/properties/data/properties/address/properties/countryIsoNumber#/properties/profile/properties/data/properties/address/properties/countryIsoNumber")             |
| [languageAlternatives](#languageAlternatives) | `string` | Required | cannot be null | [The Root Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-address-schema-properties-the-languagealternatives-schema.md "\#/properties/profile/properties/data/properties/address/properties/languageAlternatives#/properties/profile/properties/data/properties/address/properties/languageAlternatives") |

## city

An explanation about the purpose of this instance.


`city`

-   is required
-   Type: `string` ([The City Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-address-schema-properties-the-city-schema.md))
-   cannot be null
-   defined in: [The Root Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-address-schema-properties-the-city-schema.md "\#/properties/profile/properties/data/properties/address/properties/city#/properties/profile/properties/data/properties/address/properties/city")

### city Type

`string` ([The City Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-address-schema-properties-the-city-schema.md))

### city Examples

```json
"London"
```

## type

An explanation about the purpose of this instance.


`type`

-   is required
-   Type: `string` ([The Type Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-address-schema-properties-the-type-schema.md))
-   cannot be null
-   defined in: [The Root Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-address-schema-properties-the-type-schema.md "\#/properties/profile/properties/data/properties/address/properties/type#/properties/profile/properties/data/properties/address/properties/type")

### type Type

`string` ([The Type Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-address-schema-properties-the-type-schema.md))

### type Examples

```json
"Residential"
```

## label

An explanation about the purpose of this instance.


`label`

-   is required
-   Type: `string` ([The Label Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-address-schema-properties-the-label-schema.md))
-   cannot be null
-   defined in: [The Root Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-address-schema-properties-the-label-schema.md "\#/properties/profile/properties/data/properties/address/properties/label#/properties/profile/properties/data/properties/address/properties/label")

### label Type

`string` ([The Label Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-address-schema-properties-the-label-schema.md))

### label Examples

```json
"19C Woodland Rise\nLONDON\nN40 3UP\nUNITED KINGDOM"
```

## line1

An explanation about the purpose of this instance.


`line1`

-   is required
-   Type: `string` ([The Line1 Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-address-schema-properties-the-line1-schema.md))
-   cannot be null
-   defined in: [The Root Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-address-schema-properties-the-line1-schema.md "\#/properties/profile/properties/data/properties/address/properties/line1#/properties/profile/properties/data/properties/address/properties/line1")

### line1 Type

`string` ([The Line1 Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-address-schema-properties-the-line1-schema.md))

### line1 Examples

```json
"19C Woodland Rise"
```

## pcaId

An explanation about the purpose of this instance.


`pcaId`

-   is required
-   Type: `string` ([The Pcaid Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-address-schema-properties-the-pcaid-schema.md))
-   cannot be null
-   defined in: [The Root Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-address-schema-properties-the-pcaid-schema.md "\#/properties/profile/properties/data/properties/address/properties/pcaId#/properties/profile/properties/data/properties/address/properties/pcaId")

### pcaId Type

`string` ([The Pcaid Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-address-schema-properties-the-pcaid-schema.md))

### pcaId Examples

```json
"GB|RM|B|15592178"
```

## street

An explanation about the purpose of this instance.


`street`

-   is required
-   Type: `string` ([The Street Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-address-schema-properties-the-street-schema.md))
-   cannot be null
-   defined in: [The Root Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-address-schema-properties-the-street-schema.md "\#/properties/profile/properties/data/properties/address/properties/street#/properties/profile/properties/data/properties/address/properties/street")

### street Type

`string` ([The Street Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-address-schema-properties-the-street-schema.md))

### street Examples

```json
"Woodland Rise"
```

## barcode

An explanation about the purpose of this instance.


`barcode`

-   is required
-   Type: `string` ([The Barcode Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-address-schema-properties-the-barcode-schema.md))
-   cannot be null
-   defined in: [The Root Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-address-schema-properties-the-barcode-schema.md "\#/properties/profile/properties/data/properties/address/properties/barcode#/properties/profile/properties/data/properties/address/properties/barcode")

### barcode Type

`string` ([The Barcode Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-address-schema-properties-the-barcode-schema.md))

### barcode Examples

```json
"(N403UP2AH)"
```

## language

An explanation about the purpose of this instance.


`language`

-   is required
-   Type: `string` ([The Language Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-address-schema-properties-the-language-schema.md))
-   cannot be null
-   defined in: [The Root Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-address-schema-properties-the-language-schema.md "\#/properties/profile/properties/data/properties/address/properties/language#/properties/profile/properties/data/properties/address/properties/language")

### language Type

`string` ([The Language Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-address-schema-properties-the-language-schema.md))

### language Examples

```json
"ENG"
```

## dataLevel

An explanation about the purpose of this instance.


`dataLevel`

-   is required
-   Type: `string` ([The Datalevel Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-address-schema-properties-the-datalevel-schema.md))
-   cannot be null
-   defined in: [The Root Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-address-schema-properties-the-datalevel-schema.md "\#/properties/profile/properties/data/properties/address/properties/dataLevel#/properties/profile/properties/data/properties/address/properties/dataLevel")

### dataLevel Type

`string` ([The Datalevel Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-address-schema-properties-the-datalevel-schema.md))

### dataLevel Examples

```json
"Premise"
```

## domesticId

An explanation about the purpose of this instance.


`domesticId`

-   is required
-   Type: `string` ([The Domesticid Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-address-schema-properties-the-domesticid-schema.md))
-   cannot be null
-   defined in: [The Root Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-address-schema-properties-the-domesticid-schema.md "\#/properties/profile/properties/data/properties/address/properties/domesticId#/properties/profile/properties/data/properties/address/properties/domesticId")

### domesticId Type

`string` ([The Domesticid Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-address-schema-properties-the-domesticid-schema.md))

### domesticId Examples

```json
"15592178"
```

## postalCode

An explanation about the purpose of this instance.


`postalCode`

-   is required
-   Type: `string` ([The Postalcode Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-address-schema-properties-the-postalcode-schema.md))
-   cannot be null
-   defined in: [The Root Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-address-schema-properties-the-postalcode-schema.md "\#/properties/profile/properties/data/properties/address/properties/postalCode#/properties/profile/properties/data/properties/address/properties/postalCode")

### postalCode Type

`string` ([The Postalcode Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-address-schema-properties-the-postalcode-schema.md))

### postalCode Examples

```json
"N40 3UP"
```

## countryIso2

An explanation about the purpose of this instance.


`countryIso2`

-   is required
-   Type: `string` ([The Countryiso2 Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-address-schema-properties-the-countryiso2-schema.md))
-   cannot be null
-   defined in: [The Root Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-address-schema-properties-the-countryiso2-schema.md "\#/properties/profile/properties/data/properties/address/properties/countryIso2#/properties/profile/properties/data/properties/address/properties/countryIso2")

### countryIso2 Type

`string` ([The Countryiso2 Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-address-schema-properties-the-countryiso2-schema.md))

### countryIso2 Examples

```json
"GB"
```

## countryIso3

An explanation about the purpose of this instance.


`countryIso3`

-   is required
-   Type: `string` ([The Countryiso3 Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-address-schema-properties-the-countryiso3-schema.md))
-   cannot be null
-   defined in: [The Root Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-address-schema-properties-the-countryiso3-schema.md "\#/properties/profile/properties/data/properties/address/properties/countryIso3#/properties/profile/properties/data/properties/address/properties/countryIso3")

### countryIso3 Type

`string` ([The Countryiso3 Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-address-schema-properties-the-countryiso3-schema.md))

### countryIso3 Examples

```json
"GBR"
```

## countryName

An explanation about the purpose of this instance.


`countryName`

-   is required
-   Type: `string` ([The Countryname Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-address-schema-properties-the-countryname-schema.md))
-   cannot be null
-   defined in: [The Root Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-address-schema-properties-the-countryname-schema.md "\#/properties/profile/properties/data/properties/address/properties/countryName#/properties/profile/properties/data/properties/address/properties/countryName")

### countryName Type

`string` ([The Countryname Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-address-schema-properties-the-countryname-schema.md))

### countryName Examples

```json
"United Kingdom"
```

## buildingName

An explanation about the purpose of this instance.


`buildingName`

-   is required
-   Type: `string` ([The Buildingname Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-address-schema-properties-the-buildingname-schema.md))
-   cannot be null
-   defined in: [The Root Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-address-schema-properties-the-buildingname-schema.md "\#/properties/profile/properties/data/properties/address/properties/buildingName#/properties/profile/properties/data/properties/address/properties/buildingName")

### buildingName Type

`string` ([The Buildingname Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-address-schema-properties-the-buildingname-schema.md))

### buildingName Examples

```json
"19C"
```

## adminAreaName

An explanation about the purpose of this instance.


`adminAreaName`

-   is required
-   Type: `string` ([The Adminareaname Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-address-schema-properties-the-adminareaname-schema.md))
-   cannot be null
-   defined in: [The Root Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-address-schema-properties-the-adminareaname-schema.md "\#/properties/profile/properties/data/properties/address/properties/adminAreaName#/properties/profile/properties/data/properties/address/properties/adminAreaName")

### adminAreaName Type

`string` ([The Adminareaname Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-address-schema-properties-the-adminareaname-schema.md))

### adminAreaName Examples

```json
"Haringey"
```

## sortingNumber1

An explanation about the purpose of this instance.


`sortingNumber1`

-   is required
-   Type: `string` ([The Sortingnumber1 Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-address-schema-properties-the-sortingnumber1-schema.md))
-   cannot be null
-   defined in: [The Root Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-address-schema-properties-the-sortingnumber1-schema.md "\#/properties/profile/properties/data/properties/address/properties/sortingNumber1#/properties/profile/properties/data/properties/address/properties/sortingNumber1")

### sortingNumber1 Type

`string` ([The Sortingnumber1 Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-address-schema-properties-the-sortingnumber1-schema.md))

### sortingNumber1 Examples

```json
"62123"
```

## countryIsoNumber

An explanation about the purpose of this instance.


`countryIsoNumber`

-   is required
-   Type: `string` ([The Countryisonumber Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-address-schema-properties-the-countryisonumber-schema.md))
-   cannot be null
-   defined in: [The Root Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-address-schema-properties-the-countryisonumber-schema.md "\#/properties/profile/properties/data/properties/address/properties/countryIsoNumber#/properties/profile/properties/data/properties/address/properties/countryIsoNumber")

### countryIsoNumber Type

`string` ([The Countryisonumber Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-address-schema-properties-the-countryisonumber-schema.md))

### countryIsoNumber Examples

```json
"826"
```

## languageAlternatives

An explanation about the purpose of this instance.


`languageAlternatives`

-   is required
-   Type: `string` ([The Languagealternatives Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-address-schema-properties-the-languagealternatives-schema.md))
-   cannot be null
-   defined in: [The Root Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-address-schema-properties-the-languagealternatives-schema.md "\#/properties/profile/properties/data/properties/address/properties/languageAlternatives#/properties/profile/properties/data/properties/address/properties/languageAlternatives")

### languageAlternatives Type

`string` ([The Languagealternatives Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-address-schema-properties-the-languagealternatives-schema.md))

### languageAlternatives Examples

```json
"ENG"
```
