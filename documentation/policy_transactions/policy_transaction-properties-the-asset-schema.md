# The Asset Schema Schema

```txt
#/properties/asset#/properties/asset
```

An object that describes an insurable asset and it's relationship to the insured.


| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                          |
| :------------------ | ---------- | -------------- | ------------ | :---------------- | --------------------- | ------------------- | --------------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [policy_transaction.schema.json\*](../../out/policy_transaction.schema.json "open original schema") |

## asset Type

`object` ([The Asset Schema](policy_transaction-properties-the-asset-schema.md))

## asset Default Value

The default value is:

```json
{}
```

## asset Examples

```json
{
  "id": "asst_oZmLHSrOwIaHPH3L",
  "data": {
    "noClaimsDiscount": 9,
    "annualMileage": 5000,
    "racBlackBox": true,
    "usage": "SocialDomesticPleasure",
    "specificationTimestamp": "2019-10-15T15:54:12.345Z",
    "overnightLocation": "PublicRoadNearHome",
    "legalOwner": "PolicyHolder",
    "specification": {
      "insuranceGroup": 32,
      "transmission": "AUTOMATIC",
      "numberOfSeats": 5,
      "year": 2018,
      "model": "X2",
      "licencePlate": "DG18 MFK",
      "value": 31550,
      "make": "BMW",
      "fuel": "DIESEL",
      "steering": "RHD"
    },
    "modifications": false,
    "registeredKeeper": "PolicyHolder"
  },
  "user_id": "email|5da5ec2ad6be3073e989943b",
  "code": "itm_kTKwvEyaHiUEFVTw",
  "created_at": "2019-10-15T15:56:46Z",
  "type": "Vehicle"
}
```

# The Asset Schema Properties

| Property                  | Type     | Required | Nullable       | Defined by                                                                                                                                                                                |
| :------------------------ | -------- | -------- | -------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [id](#id)                 | `string` | Required | cannot be null | [The Root Schema](policy_transaction-properties-the-asset-schema-properties-the-id-schema.md "\#/properties/asset/properties/id#/properties/asset/properties/id")                         |
| [code](#code)             | `string` | Required | cannot be null | [The Root Schema](policy_transaction-properties-the-asset-schema-properties-the-code-schema.md "\#/properties/asset/properties/code#/properties/asset/properties/code")                   |
| [type](#type)             | `string` | Required | cannot be null | [The Root Schema](policy_transaction-properties-the-asset-schema-properties-the-type-schema.md "\#/properties/asset/properties/type#/properties/asset/properties/type")                   |
| [user_id](#user_id)       | `string` | Required | cannot be null | [The Root Schema](policy_transaction-properties-the-asset-schema-properties-the-user_id-schema.md "\#/properties/asset/properties/user_id#/properties/asset/properties/user_id")          |
| [data](#data)             | `object` | Required | cannot be null | [The Root Schema](policy_transaction-properties-the-asset-schema-properties-the-data-schema.md "\#/properties/asset/properties/data#/properties/asset/properties/data")                   |
| [created_at](#created_at) | `string` | Required | cannot be null | [The Root Schema](policy_transaction-properties-the-asset-schema-properties-the-created_at-schema.md "\#/properties/asset/properties/created_at#/properties/asset/properties/created_at") |

## id

A unique identifier for the version of the asset.


`id`

-   is required
-   Type: `string` ([The Id Schema](policy_transaction-properties-the-asset-schema-properties-the-id-schema.md))
-   cannot be null
-   defined in: [The Root Schema](policy_transaction-properties-the-asset-schema-properties-the-id-schema.md "\#/properties/asset/properties/id#/properties/asset/properties/id")

### id Type

`string` ([The Id Schema](policy_transaction-properties-the-asset-schema-properties-the-id-schema.md))

### id Examples

```json
"asst_oZmLHSrOwIaHPH3L"
```

## code

A unique idenitifer for the asset over it's lifetime.


`code`

-   is required
-   Type: `string` ([The Code Schema](policy_transaction-properties-the-asset-schema-properties-the-code-schema.md))
-   cannot be null
-   defined in: [The Root Schema](policy_transaction-properties-the-asset-schema-properties-the-code-schema.md "\#/properties/asset/properties/code#/properties/asset/properties/code")

### code Type

`string` ([The Code Schema](policy_transaction-properties-the-asset-schema-properties-the-code-schema.md))

### code Examples

```json
"itm_kTKwvEyaHiUEFVTw"
```

## type

The type of asset.


`type`

-   is required
-   Type: `string` ([The Type Schema](policy_transaction-properties-the-asset-schema-properties-the-type-schema.md))
-   cannot be null
-   defined in: [The Root Schema](policy_transaction-properties-the-asset-schema-properties-the-type-schema.md "\#/properties/asset/properties/type#/properties/asset/properties/type")

### type Type

`string` ([The Type Schema](policy_transaction-properties-the-asset-schema-properties-the-type-schema.md))

### type Examples

```json
"Vehicle"
```

## user_id

The user id of which the asset belongs to.


`user_id`

-   is required
-   Type: `string` ([The User_id Schema](policy_transaction-properties-the-asset-schema-properties-the-user_id-schema.md))
-   cannot be null
-   defined in: [The Root Schema](policy_transaction-properties-the-asset-schema-properties-the-user_id-schema.md "\#/properties/asset/properties/user_id#/properties/asset/properties/user_id")

### user_id Type

`string` ([The User_id Schema](policy_transaction-properties-the-asset-schema-properties-the-user_id-schema.md))

### user_id Examples

```json
"email|5da5ec2ad6be3073e989943b"
```

## data

An object that describes the asset and it's relationship to the user.


`data`

-   is required
-   Type: `object` ([The Data Schema](policy_transaction-properties-the-asset-schema-properties-the-data-schema.md))
-   cannot be null
-   defined in: [The Root Schema](policy_transaction-properties-the-asset-schema-properties-the-data-schema.md "\#/properties/asset/properties/data#/properties/asset/properties/data")

### data Type

`object` ([The Data Schema](policy_transaction-properties-the-asset-schema-properties-the-data-schema.md))

### data Default Value

The default value is:

```json
{}
```

### data Examples

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

## created_at

The datetime the asset version was created.


`created_at`

-   is required
-   Type: `string` ([The Created_at Schema](policy_transaction-properties-the-asset-schema-properties-the-created_at-schema.md))
-   cannot be null
-   defined in: [The Root Schema](policy_transaction-properties-the-asset-schema-properties-the-created_at-schema.md "\#/properties/asset/properties/created_at#/properties/asset/properties/created_at")

### created_at Type

`string` ([The Created_at Schema](policy_transaction-properties-the-asset-schema-properties-the-created_at-schema.md))

### created_at Examples

```json
"2019-10-15T15:56:46Z"
```
