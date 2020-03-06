# Policy Transaction Schema

```txt
http://example.com/example.json
```

The root schema comprises the entire JSON document.


| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                        |
| :------------------ | ---------- | -------------- | ------------ | :---------------- | --------------------- | ------------------- | ------------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [policy_transaction.schema.json](../../out/policy_transaction.schema.json "open original schema") |

## Policy Transaction Type

`object` ([Policy Transaction](policy_transaction.md))

# Policy Transaction Properties

| Property                                          | Type      | Required | Nullable       | Defined by                                                                                                                                                         |
| :------------------------------------------------ | --------- | -------- | -------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [policy_id](#policy_id)                           | `string`  | Required | cannot be null | [Policy Transaction](policy_transaction-properties-the-policy_id-schema.md "\#/properties/policy_id#/properties/policy_id")                                        |
| [transaction_id](#transaction_id)                 | `string`  | Required | cannot be null | [Policy Transaction](policy_transaction-properties-the-transaction_id-schema.md "\#/properties/transaction_id#/properties/transaction_id")                         |
| [quote_id](#quote_id)                             | `string`  | Required | cannot be null | [Policy Transaction](policy_transaction-properties-the-quote_id-schema.md "\#/properties/quote_id#/properties/quote_id")                                           |
| [period_number](#period_number)                   | `integer` | Required | cannot be null | [Policy Transaction](policy_transaction-properties-the-period_number-schema.md "\#/properties/period_number#/properties/period_number")                            |
| [transaction_created_at](#transaction_created_at) | `string`  | Required | cannot be null | [Policy Transaction](policy_transaction-properties-the-transaction_created_at-schema.md "\#/properties/transaction_created_at#/properties/transaction_created_at") |
| [transaction_type](#transaction_type)             | `string`  | Required | cannot be null | [Policy Transaction](policy_transaction-properties-the-transaction_type-schema.md "\#/properties/transaction_type#/properties/transaction_type")                   |
| [policy_inception](#policy_inception)             | `string`  | Required | cannot be null | [Policy Transaction](policy_transaction-properties-the-policy_inception-schema.md "\#/properties/policy_inception#/properties/policy_inception")                   |
| [transaction_lines](#transaction_lines)           | `array`   | Required | cannot be null | [Policy Transaction](policy_transaction-properties-the-transaction_lines-schema.md "\#/properties/transaction_lines#/properties/transaction_lines")                |
| [risk_factors](#risk_factors)                     | `array`   | Required | cannot be null | [Policy Transaction](policy_transaction-properties-the-risk_factors-schema.md "\#/properties/risk_factors#/properties/risk_factors")                               |
| [asset](#asset)                                   | `object`  | Required | cannot be null | [Policy Transaction](policy_transaction-properties-the-asset-schema.md "\#/properties/asset#/properties/asset")                                                    |
| [profile](#profile)                               | `object`  | Required | cannot be null | [Policy Transaction](policy_transaction-properties-the-profile-schema.md "\#/properties/profile#/properties/profile")                                              |
| [cover_start](#cover_start)                       | `string`  | Required | cannot be null | [Policy Transaction](policy_transaction-properties-the-cover_start-schema.md "\#/properties/cover_start#/properties/cover_start")                                  |
| [period_start](#period_start)                     | `string`  | Required | cannot be null | [Policy Transaction](policy_transaction-properties-the-period_start-schema.md "\#/properties/period_start#/properties/period_start")                               |
| [period_end](#period_end)                         | `string`  | Required | cannot be null | [Policy Transaction](policy_transaction-properties-the-period_end-schema.md "\#/properties/period_end#/properties/period_end")                                     |
| [usage_meter_start](#usage_meter_start)           | `integer` | Required | cannot be null | [Policy Transaction](policy_transaction-properties-the-usage_meter_start-schema.md "\#/properties/usage_meter_start#/properties/usage_meter_start")                |
| [usage_meter_end](#usage_meter_end)               | `integer` | Required | cannot be null | [Policy Transaction](policy_transaction-properties-the-usage_meter_end-schema.md "\#/properties/usage_meter_end#/properties/usage_meter_end")                      |
| [usage_start](#usage_start)                       | `integer` | Required | cannot be null | [Policy Transaction](policy_transaction-properties-the-usage_start-schema.md "\#/properties/usage_start#/properties/usage_start")                                  |
| [usage_end](#usage_end)                           | `integer` | Required | cannot be null | [Policy Transaction](policy_transaction-properties-the-usage_end-schema.md "\#/properties/usage_end#/properties/usage_end")                                        |
| [\_premium_per_mile](#_premium_per_mile)          | `integer` | Required | cannot be null | [Policy Transaction](policy_transaction-properties-the-_premium_per_mile-schema.md "\#/properties/\_premium_per_mile#/properties/\_premium_per_mile")              |

## policy_id

A unique identifier for a policy


`policy_id`

-   is required
-   Type: `string` ([The Policy_id Schema](policy_transaction-properties-the-policy_id-schema.md))
-   cannot be null
-   defined in: [Policy Transaction](policy_transaction-properties-the-policy_id-schema.md "\#/properties/policy_id#/properties/policy_id")

### policy_id Type

`string` ([The Policy_id Schema](policy_transaction-properties-the-policy_id-schema.md))

### policy_id Examples

```json
"pcy_1D2gnm6nKwlHISCH"
```

## transaction_id

A unique identifier for this policy transaction


`transaction_id`

-   is required
-   Type: `string` ([The Transaction_id Schema](policy_transaction-properties-the-transaction_id-schema.md))
-   cannot be null
-   defined in: [Policy Transaction](policy_transaction-properties-the-transaction_id-schema.md "\#/properties/transaction_id#/properties/transaction_id")

### transaction_id Type

`string` ([The Transaction_id Schema](policy_transaction-properties-the-transaction_id-schema.md))

### transaction_id Examples

```json
"ptxn_7nuAFtakj2KDEEtG"
```

## quote_id

A unique identifier for this version of the quote


`quote_id`

-   is required
-   Type: `string` ([The Quote_id Schema](policy_transaction-properties-the-quote_id-schema.md))
-   cannot be null
-   defined in: [Policy Transaction](policy_transaction-properties-the-quote_id-schema.md "\#/properties/quote_id#/properties/quote_id")

### quote_id Type

`string` ([The Quote_id Schema](policy_transaction-properties-the-quote_id-schema.md))

### quote_id Examples

```json
"quo_ARDUSHH94rE4k9x5"
```

## period_number

The policy period this transaction occured within.


`period_number`

-   is required
-   Type: `integer` ([The Period_number Schema](policy_transaction-properties-the-period_number-schema.md))
-   cannot be null
-   defined in: [Policy Transaction](policy_transaction-properties-the-period_number-schema.md "\#/properties/period_number#/properties/period_number")

### period_number Type

`integer` ([The Period_number Schema](policy_transaction-properties-the-period_number-schema.md))

### period_number Examples

```json
0
```

## transaction_created_at

When the transaction was created


`transaction_created_at`

-   is required
-   Type: `string` ([The Transaction_created_at Schema](policy_transaction-properties-the-transaction_created_at-schema.md))
-   cannot be null
-   defined in: [Policy Transaction](policy_transaction-properties-the-transaction_created_at-schema.md "\#/properties/transaction_created_at#/properties/transaction_created_at")

### transaction_created_at Type

`string` ([The Transaction_created_at Schema](policy_transaction-properties-the-transaction_created_at-schema.md))

### transaction_created_at Examples

```json
"2019-10-15T16:08:25Z"
```

## transaction_type

The type of transaction that occured


`transaction_type`

-   is required
-   Type: `string` ([The Transaction_type Schema](policy_transaction-properties-the-transaction_type-schema.md))
-   cannot be null
-   defined in: [Policy Transaction](policy_transaction-properties-the-transaction_type-schema.md "\#/properties/transaction_type#/properties/transaction_type")

### transaction_type Type

`string` ([The Transaction_type Schema](policy_transaction-properties-the-transaction_type-schema.md))

### transaction_type Examples

```json
"RENEW"
```

```json
"ADJREMOVE"
```

```json
"ADD"
```

```json
"REMOVE"
```

```json
"NEW"
```

```json
"ADJADD"
```

```json
"CANCEL"
```

## policy_inception

When the policy incepted.


`policy_inception`

-   is required
-   Type: `string` ([The Policy_inception Schema](policy_transaction-properties-the-policy_inception-schema.md))
-   cannot be null
-   defined in: [Policy Transaction](policy_transaction-properties-the-policy_inception-schema.md "\#/properties/policy_inception#/properties/policy_inception")

### policy_inception Type

`string` ([The Policy_inception Schema](policy_transaction-properties-the-policy_inception-schema.md))

### policy_inception Examples

```json
"2019-10-15T15:58:54Z"
```

## transaction_lines

A line of insurance cover that has been charged/refunded to the customer.


`transaction_lines`

-   is required
-   Type: `object[]` ([The Transaction Lines schema](policy_transaction-properties-the-transaction_lines-schema-the-transaction-lines-schema.md))
-   cannot be null
-   defined in: [Policy Transaction](policy_transaction-properties-the-transaction_lines-schema.md "\#/properties/transaction_lines#/properties/transaction_lines")

### transaction_lines Type

`object[]` ([The Transaction Lines schema](policy_transaction-properties-the-transaction_lines-schema-the-transaction-lines-schema.md))

### transaction_lines Default Value

The default value is:

```json
[]
```

### transaction_lines Examples

```json
[
  {
    "transaction_id": 123,
    "excess": 0,
    "transaction_premium": -3.799191,
    "cover_code": "ncb_protection",
    "agency_commission": -0.339214,
    "transaction_premium_tax": -0.4,
    "sum_insured": 1,
    "cover_period_start": "2019-10-15T16:08:25Z"
  },
  {
    "cover_period_start": "2019-10-15T16:08:25Z",
    "transaction_id": "ptxn_RAFcoctw4UC9bE92",
    "excess": 250,
    "transaction_premium": -2.499468,
    "cover_code": "foreign_travel",
    "agency_commission": -0.223167,
    "transaction_premium_tax": -0.2678,
    "sum_insured": 1
  }
]
```

## risk_factors

An array that describes the factors which are used to price the insurance risk.


`risk_factors`

-   is required
-   Type: `object[]` ([The Risk Factors Schema](policy_transaction-properties-the-risk_factors-schema-the-risk-factors-schema.md))
-   cannot be null
-   defined in: [Policy Transaction](policy_transaction-properties-the-risk_factors-schema.md "\#/properties/risk_factors#/properties/risk_factors")

### risk_factors Type

`object[]` ([The Risk Factors Schema](policy_transaction-properties-the-risk_factors-schema-the-risk-factors-schema.md))

### risk_factors Default Value

The default value is:

```json
[]
```

### risk_factors Examples

```json
[
  {
    "factor_level_code": "false",
    "factor_code": "AdvisedByDoctorNotToDrive"
  },
  {
    "factor_level_code": "41",
    "factor_code": "Age"
  }
]
```

## asset

An object that describes an insurable asset and it's relationship to the insured.


`asset`

-   is required
-   Type: `object` ([The Asset Schema](policy_transaction-properties-the-asset-schema.md))
-   cannot be null
-   defined in: [Policy Transaction](policy_transaction-properties-the-asset-schema.md "\#/properties/asset#/properties/asset")

### asset Type

`object` ([The Asset Schema](policy_transaction-properties-the-asset-schema.md))

### asset Default Value

The default value is:

```json
{}
```

### asset Examples

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

## profile

An object that describes the customer.


`profile`

-   is required
-   Type: `object` ([The Profile Schema](policy_transaction-properties-the-profile-schema.md))
-   cannot be null
-   defined in: [Policy Transaction](policy_transaction-properties-the-profile-schema.md "\#/properties/profile#/properties/profile")

### profile Type

`object` ([The Profile Schema](policy_transaction-properties-the-profile-schema.md))

### profile Default Value

The default value is:

```json
{}
```

### profile Examples

```json
{
  "id": "prfl_6dT4lFDfce1aKz4f",
  "data": {
    "dvlaUnawareOfMedicalCondition": false,
    "firstName": "Joe",
    "employmentStatus": "ED",
    "vehicleClaimsHistory": [],
    "homeOwnership": "Own",
    "dateOfBirth": "1977-11-11",
    "address": {
      "type": "Residential",
      "countryName": "United Kingdom",
      "pcaId": "GB|RM|B|15592178",
      "postalCode": "N40 3UP",
      "countryIso2": "GB",
      "city": "London",
      "countryIso3": "GBR",
      "buildingName": "19C",
      "street": "Woodland Rise",
      "sortingNumber1": "62123",
      "line1": "19C Bogland Rise",
      "domesticId": "15592178",
      "languageAlternatives": "ENG",
      "barcode": "(N403UP2AH)",
      "label": "19C Bogland Rise\nLONDON\nN40 3UP\nUNITED KINGDOM",
      "countryIsoNumber": "826",
      "dataLevel": "Premise",
      "adminAreaName": "Haringey",
      "language": "ENG"
    },
    "lastName": "Bloggs",
    "bankrupt": false,
    "advisedByDoctorNotToDrive": false,
    "email": "Joey+Who+Bloggs@wrisk.co",
    "drivingLicence": {
      "convictions": [],
      "status": "FC",
      "entitlements": [
        {
          "code": "B",
          "validFrom": "2000-11-01",
          "type": "F"
        }
      ],
      "regionOfIssue": "GB"
    },
    "maritalStatus": "Married",
    "unsatisfiedCCJs": false,
    "vehicleClaimsHistoryTimestamp": "2019-10-15T15:54:55.521Z",
    "previouslyRefusedInsurance": false,
    "property": {},
    "unspentCriminalConvictions": false,
    "dateOfBirthTimestamp": "2019-10-15T15:54:30.205Z"
  },
  "user_id": "email|5da5ec2ad6be3073e989943b",
  "policyholder_code": "email|5da5ec2ad6be3073e989943b",
  "created_at": "2019-10-15T15:56:46Z"
}
```

## cover_start

An explanation about the purpose of this instance.


`cover_start`

-   is required
-   Type: `string` ([The Cover_start Schema](policy_transaction-properties-the-cover_start-schema.md))
-   cannot be null
-   defined in: [Policy Transaction](policy_transaction-properties-the-cover_start-schema.md "\#/properties/cover_start#/properties/cover_start")

### cover_start Type

`string` ([The Cover_start Schema](policy_transaction-properties-the-cover_start-schema.md))

### cover_start Examples

```json
"2019-10-15T16:08:25Z"
```

## period_start

An explanation about the purpose of this instance.


`period_start`

-   is required
-   Type: `string` ([The Period_start Schema](policy_transaction-properties-the-period_start-schema.md))
-   cannot be null
-   defined in: [Policy Transaction](policy_transaction-properties-the-period_start-schema.md "\#/properties/period_start#/properties/period_start")

### period_start Type

`string` ([The Period_start Schema](policy_transaction-properties-the-period_start-schema.md))

### period_start Examples

```json
"2019-10-15T15:58:54Z"
```

## period_end

An explanation about the purpose of this instance.


`period_end`

-   is required
-   Type: `string` ([The Period_end Schema](policy_transaction-properties-the-period_end-schema.md))
-   cannot be null
-   defined in: [Policy Transaction](policy_transaction-properties-the-period_end-schema.md "\#/properties/period_end#/properties/period_end")

### period_end Type

`string` ([The Period_end Schema](policy_transaction-properties-the-period_end-schema.md))

### period_end Examples

```json
"2019-11-15T16:58:54Z"
```

## usage_meter_start

An explanation about the purpose of this instance.


`usage_meter_start`

-   is required
-   Type: `integer` ([The Usage_meter_start Schema](policy_transaction-properties-the-usage_meter_start-schema.md))
-   cannot be null
-   defined in: [Policy Transaction](policy_transaction-properties-the-usage_meter_start-schema.md "\#/properties/usage_meter_start#/properties/usage_meter_start")

### usage_meter_start Type

`integer` ([The Usage_meter_start Schema](policy_transaction-properties-the-usage_meter_start-schema.md))

### usage_meter_start Examples

```json
0
```

## usage_meter_end

An explanation about the purpose of this instance.


`usage_meter_end`

-   is required
-   Type: `integer` ([The Usage_meter_end Schema](policy_transaction-properties-the-usage_meter_end-schema.md))
-   cannot be null
-   defined in: [Policy Transaction](policy_transaction-properties-the-usage_meter_end-schema.md "\#/properties/usage_meter_end#/properties/usage_meter_end")

### usage_meter_end Type

`integer` ([The Usage_meter_end Schema](policy_transaction-properties-the-usage_meter_end-schema.md))

### usage_meter_end Examples

```json
0
```

## usage_start

An explanation about the purpose of this instance.


`usage_start`

-   is required
-   Type: `integer` ([The Usage_start Schema](policy_transaction-properties-the-usage_start-schema.md))
-   cannot be null
-   defined in: [Policy Transaction](policy_transaction-properties-the-usage_start-schema.md "\#/properties/usage_start#/properties/usage_start")

### usage_start Type

`integer` ([The Usage_start Schema](policy_transaction-properties-the-usage_start-schema.md))

### usage_start Examples

```json
0
```

## usage_end

An explanation about the purpose of this instance.


`usage_end`

-   is required
-   Type: `integer` ([The Usage_end Schema](policy_transaction-properties-the-usage_end-schema.md))
-   cannot be null
-   defined in: [Policy Transaction](policy_transaction-properties-the-usage_end-schema.md "\#/properties/usage_end#/properties/usage_end")

### usage_end Type

`integer` ([The Usage_end Schema](policy_transaction-properties-the-usage_end-schema.md))

### usage_end Examples

```json
0
```

## \_premium_per_mile

An explanation about the purpose of this instance.


`_premium_per_mile`

-   is required
-   Type: `integer` ([The \_premium_per_mile Schema](policy_transaction-properties-the-_premium_per_mile-schema.md))
-   cannot be null
-   defined in: [Policy Transaction](policy_transaction-properties-the-_premium_per_mile-schema.md "\#/properties/\_premium_per_mile#/properties/\_premium_per_mile")

### \_premium_per_mile Type

`integer` ([The \_premium_per_mile Schema](policy_transaction-properties-the-_premium_per_mile-schema.md))

### \_premium_per_mile Examples

```json
0
```
