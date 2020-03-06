# The Data Schema Schema

```txt
#/properties/asset/properties/data#/properties/asset/properties/data
```

An explanation about the purpose of this instance.


| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                       |
| :------------------ | ---------- | -------------- | ------------ | :---------------- | --------------------- | ------------------- | ------------------------------------------------------------------------------------------------ |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [policy_transaction.schema.json\*](../out/policy_transaction.schema.json "open original schema") |

## data Type

`object` ([The Data Schema](policy_transaction-properties-the-asset-schema-properties-the-data-schema.md))

## data Default Value

The default value is:

```json
{}
```

## data Examples

```json
{
  "annualMileage": 5000,
  "noClaimsDiscount": 9,
  "racBlackBox": true,
  "usage": "SocialDomesticPleasure",
  "specificationTimestamp": "2019-10-15T15:54:12.345Z",
  "overnightLocation": "PublicRoadNearHome",
  "legalOwner": "PolicyHolder",
  "specification": {
    "model": "X2",
    "licencePlate": "DG18 MFK",
    "year": 2018,
    "value": 31550,
    "make": "BMW",
    "fuel": "DIESEL",
    "steering": "RHD",
    "insuranceGroup": 32,
    "transmission": "AUTOMATIC",
    "numberOfSeats": 5
  },
  "modifications": false,
  "registeredKeeper": "PolicyHolder"
}
```

# The Data Schema Properties

| Property                                          | Type      | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                               |
| :------------------------------------------------ | --------- | -------- | -------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [usage](#usage)                                   | `string`  | Required | cannot be null | [The Root Schema](policy_transaction-properties-the-asset-schema-properties-the-data-schema-properties-the-usage-schema.md "\#/properties/asset/properties/data/properties/usage#/properties/asset/properties/data/properties/usage")                                                    |
| [legalOwner](#legalOwner)                         | `string`  | Required | cannot be null | [The Root Schema](policy_transaction-properties-the-asset-schema-properties-the-data-schema-properties-the-legalowner-schema.md "\#/properties/asset/properties/data/properties/legalOwner#/properties/asset/properties/data/properties/legalOwner")                                     |
| [racBlackBox](#racBlackBox)                       | `boolean` | Required | cannot be null | [The Root Schema](policy_transaction-properties-the-asset-schema-properties-the-data-schema-properties-the-racblackbox-schema.md "\#/properties/asset/properties/data/properties/racBlackBox#/properties/asset/properties/data/properties/racBlackBox")                                  |
| [annualMileage](#annualMileage)                   | `integer` | Required | cannot be null | [The Root Schema](policy_transaction-properties-the-asset-schema-properties-the-data-schema-properties-the-annualmileage-schema.md "\#/properties/asset/properties/data/properties/annualMileage#/properties/asset/properties/data/properties/annualMileage")                            |
| [modifications](#modifications)                   | `boolean` | Required | cannot be null | [The Root Schema](policy_transaction-properties-the-asset-schema-properties-the-data-schema-properties-the-modifications-schema.md "\#/properties/asset/properties/data/properties/modifications#/properties/asset/properties/data/properties/modifications")                            |
| [specification](#specification)                   | `object`  | Required | cannot be null | [The Root Schema](policy_transaction-properties-the-asset-schema-properties-the-data-schema-properties-the-specification-schema.md "\#/properties/asset/properties/data/properties/specification#/properties/asset/properties/data/properties/specification")                            |
| [noClaimsDiscount](#noClaimsDiscount)             | `integer` | Required | cannot be null | [The Root Schema](policy_transaction-properties-the-asset-schema-properties-the-data-schema-properties-the-noclaimsdiscount-schema.md "\#/properties/asset/properties/data/properties/noClaimsDiscount#/properties/asset/properties/data/properties/noClaimsDiscount")                   |
| [registeredKeeper](#registeredKeeper)             | `string`  | Required | cannot be null | [The Root Schema](policy_transaction-properties-the-asset-schema-properties-the-data-schema-properties-the-registeredkeeper-schema.md "\#/properties/asset/properties/data/properties/registeredKeeper#/properties/asset/properties/data/properties/registeredKeeper")                   |
| [overnightLocation](#overnightLocation)           | `string`  | Required | cannot be null | [The Root Schema](policy_transaction-properties-the-asset-schema-properties-the-data-schema-properties-the-overnightlocation-schema.md "\#/properties/asset/properties/data/properties/overnightLocation#/properties/asset/properties/data/properties/overnightLocation")                |
| [specificationTimestamp](#specificationTimestamp) | `string`  | Required | cannot be null | [The Root Schema](policy_transaction-properties-the-asset-schema-properties-the-data-schema-properties-the-specificationtimestamp-schema.md "\#/properties/asset/properties/data/properties/specificationTimestamp#/properties/asset/properties/data/properties/specificationTimestamp") |

## usage

An explanation about the purpose of this instance.


`usage`

-   is required
-   Type: `string` ([The Usage Schema](policy_transaction-properties-the-asset-schema-properties-the-data-schema-properties-the-usage-schema.md))
-   cannot be null
-   defined in: [The Root Schema](policy_transaction-properties-the-asset-schema-properties-the-data-schema-properties-the-usage-schema.md "\#/properties/asset/properties/data/properties/usage#/properties/asset/properties/data/properties/usage")

### usage Type

`string` ([The Usage Schema](policy_transaction-properties-the-asset-schema-properties-the-data-schema-properties-the-usage-schema.md))

### usage Examples

```json
"SocialDomesticPleasure"
```

## legalOwner

An explanation about the purpose of this instance.


`legalOwner`

-   is required
-   Type: `string` ([The Legalowner Schema](policy_transaction-properties-the-asset-schema-properties-the-data-schema-properties-the-legalowner-schema.md))
-   cannot be null
-   defined in: [The Root Schema](policy_transaction-properties-the-asset-schema-properties-the-data-schema-properties-the-legalowner-schema.md "\#/properties/asset/properties/data/properties/legalOwner#/properties/asset/properties/data/properties/legalOwner")

### legalOwner Type

`string` ([The Legalowner Schema](policy_transaction-properties-the-asset-schema-properties-the-data-schema-properties-the-legalowner-schema.md))

### legalOwner Examples

```json
"PolicyHolder"
```

## racBlackBox

An explanation about the purpose of this instance.


`racBlackBox`

-   is required
-   Type: `boolean` ([The Racblackbox Schema](policy_transaction-properties-the-asset-schema-properties-the-data-schema-properties-the-racblackbox-schema.md))
-   cannot be null
-   defined in: [The Root Schema](policy_transaction-properties-the-asset-schema-properties-the-data-schema-properties-the-racblackbox-schema.md "\#/properties/asset/properties/data/properties/racBlackBox#/properties/asset/properties/data/properties/racBlackBox")

### racBlackBox Type

`boolean` ([The Racblackbox Schema](policy_transaction-properties-the-asset-schema-properties-the-data-schema-properties-the-racblackbox-schema.md))

### racBlackBox Examples

```json
true
```

## annualMileage

An explanation about the purpose of this instance.


`annualMileage`

-   is required
-   Type: `integer` ([The Annualmileage Schema](policy_transaction-properties-the-asset-schema-properties-the-data-schema-properties-the-annualmileage-schema.md))
-   cannot be null
-   defined in: [The Root Schema](policy_transaction-properties-the-asset-schema-properties-the-data-schema-properties-the-annualmileage-schema.md "\#/properties/asset/properties/data/properties/annualMileage#/properties/asset/properties/data/properties/annualMileage")

### annualMileage Type

`integer` ([The Annualmileage Schema](policy_transaction-properties-the-asset-schema-properties-the-data-schema-properties-the-annualmileage-schema.md))

### annualMileage Examples

```json
5000
```

## modifications

An explanation about the purpose of this instance.


`modifications`

-   is required
-   Type: `boolean` ([The Modifications Schema](policy_transaction-properties-the-asset-schema-properties-the-data-schema-properties-the-modifications-schema.md))
-   cannot be null
-   defined in: [The Root Schema](policy_transaction-properties-the-asset-schema-properties-the-data-schema-properties-the-modifications-schema.md "\#/properties/asset/properties/data/properties/modifications#/properties/asset/properties/data/properties/modifications")

### modifications Type

`boolean` ([The Modifications Schema](policy_transaction-properties-the-asset-schema-properties-the-data-schema-properties-the-modifications-schema.md))

### modifications Examples

```json
false
```

## specification

An explanation about the purpose of this instance.


`specification`

-   is required
-   Type: `object` ([The Specification Schema](policy_transaction-properties-the-asset-schema-properties-the-data-schema-properties-the-specification-schema.md))
-   cannot be null
-   defined in: [The Root Schema](policy_transaction-properties-the-asset-schema-properties-the-data-schema-properties-the-specification-schema.md "\#/properties/asset/properties/data/properties/specification#/properties/asset/properties/data/properties/specification")

### specification Type

`object` ([The Specification Schema](policy_transaction-properties-the-asset-schema-properties-the-data-schema-properties-the-specification-schema.md))

### specification Default Value

The default value is:

```json
{}
```

### specification Examples

```json
{
  "insuranceGroup": 32,
  "transmission": "AUTOMATIC",
  "numberOfSeats": 5,
  "licencePlate": "DG18 MFK",
  "model": "X2",
  "year": 2018,
  "value": 31550,
  "make": "BMW",
  "fuel": "DIESEL",
  "steering": "RHD"
}
```

## noClaimsDiscount

An explanation about the purpose of this instance.


`noClaimsDiscount`

-   is required
-   Type: `integer` ([The Noclaimsdiscount Schema](policy_transaction-properties-the-asset-schema-properties-the-data-schema-properties-the-noclaimsdiscount-schema.md))
-   cannot be null
-   defined in: [The Root Schema](policy_transaction-properties-the-asset-schema-properties-the-data-schema-properties-the-noclaimsdiscount-schema.md "\#/properties/asset/properties/data/properties/noClaimsDiscount#/properties/asset/properties/data/properties/noClaimsDiscount")

### noClaimsDiscount Type

`integer` ([The Noclaimsdiscount Schema](policy_transaction-properties-the-asset-schema-properties-the-data-schema-properties-the-noclaimsdiscount-schema.md))

### noClaimsDiscount Examples

```json
9
```

## registeredKeeper

An explanation about the purpose of this instance.


`registeredKeeper`

-   is required
-   Type: `string` ([The Registeredkeeper Schema](policy_transaction-properties-the-asset-schema-properties-the-data-schema-properties-the-registeredkeeper-schema.md))
-   cannot be null
-   defined in: [The Root Schema](policy_transaction-properties-the-asset-schema-properties-the-data-schema-properties-the-registeredkeeper-schema.md "\#/properties/asset/properties/data/properties/registeredKeeper#/properties/asset/properties/data/properties/registeredKeeper")

### registeredKeeper Type

`string` ([The Registeredkeeper Schema](policy_transaction-properties-the-asset-schema-properties-the-data-schema-properties-the-registeredkeeper-schema.md))

### registeredKeeper Examples

```json
"PolicyHolder"
```

## overnightLocation

An explanation about the purpose of this instance.


`overnightLocation`

-   is required
-   Type: `string` ([The Overnightlocation Schema](policy_transaction-properties-the-asset-schema-properties-the-data-schema-properties-the-overnightlocation-schema.md))
-   cannot be null
-   defined in: [The Root Schema](policy_transaction-properties-the-asset-schema-properties-the-data-schema-properties-the-overnightlocation-schema.md "\#/properties/asset/properties/data/properties/overnightLocation#/properties/asset/properties/data/properties/overnightLocation")

### overnightLocation Type

`string` ([The Overnightlocation Schema](policy_transaction-properties-the-asset-schema-properties-the-data-schema-properties-the-overnightlocation-schema.md))

### overnightLocation Examples

```json
"PublicRoadNearHome"
```

## specificationTimestamp

An explanation about the purpose of this instance.


`specificationTimestamp`

-   is required
-   Type: `string` ([The Specificationtimestamp Schema](policy_transaction-properties-the-asset-schema-properties-the-data-schema-properties-the-specificationtimestamp-schema.md))
-   cannot be null
-   defined in: [The Root Schema](policy_transaction-properties-the-asset-schema-properties-the-data-schema-properties-the-specificationtimestamp-schema.md "\#/properties/asset/properties/data/properties/specificationTimestamp#/properties/asset/properties/data/properties/specificationTimestamp")

### specificationTimestamp Type

`string` ([The Specificationtimestamp Schema](policy_transaction-properties-the-asset-schema-properties-the-data-schema-properties-the-specificationtimestamp-schema.md))

### specificationTimestamp Examples

```json
"2019-10-15T15:54:12.345Z"
```
