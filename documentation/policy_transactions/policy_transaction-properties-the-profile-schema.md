# The Profile Schema Schema

```txt
#/properties/profile#/properties/profile
```

An object that describes the customer.


| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                          |
| :------------------ | ---------- | -------------- | ------------ | :---------------- | --------------------- | ------------------- | --------------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [policy_transaction.schema.json\*](../../out/policy_transaction.schema.json "open original schema") |

## profile Type

`object` ([The Profile Schema](policy_transaction-properties-the-profile-schema.md))

## profile Default Value

The default value is:

```json
{}
```

## profile Examples

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

# The Profile Schema Properties

| Property                                | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                           |
| :-------------------------------------- | -------- | -------- | -------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [id](#id)                               | `string` | Required | cannot be null | [The Root Schema](policy_transaction-properties-the-profile-schema-properties-the-id-schema.md "\#/properties/profile/properties/id#/properties/profile/properties/id")                                              |
| [user_id](#user_id)                     | `string` | Required | cannot be null | [The Root Schema](policy_transaction-properties-the-profile-schema-properties-the-user_id-schema.md "\#/properties/profile/properties/user_id#/properties/profile/properties/user_id")                               |
| [data](#data)                           | `object` | Required | cannot be null | [The Root Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema.md "\#/properties/profile/properties/data#/properties/profile/properties/data")                                        |
| [created_at](#created_at)               | `string` | Required | cannot be null | [The Root Schema](policy_transaction-properties-the-profile-schema-properties-the-created_at-schema.md "\#/properties/profile/properties/created_at#/properties/profile/properties/created_at")                      |
| [policyholder_code](#policyholder_code) | `string` | Required | cannot be null | [The Root Schema](policy_transaction-properties-the-profile-schema-properties-the-policyholder_code-schema.md "\#/properties/profile/properties/policyholder_code#/properties/profile/properties/policyholder_code") |

## id

An explanation about the purpose of this instance.


`id`

-   is required
-   Type: `string` ([The Id Schema](policy_transaction-properties-the-profile-schema-properties-the-id-schema.md))
-   cannot be null
-   defined in: [The Root Schema](policy_transaction-properties-the-profile-schema-properties-the-id-schema.md "\#/properties/profile/properties/id#/properties/profile/properties/id")

### id Type

`string` ([The Id Schema](policy_transaction-properties-the-profile-schema-properties-the-id-schema.md))

### id Examples

```json
"prfl_6dT4lFDfce1aKz4f"
```

## user_id

An explanation about the purpose of this instance.


`user_id`

-   is required
-   Type: `string` ([The User_id Schema](policy_transaction-properties-the-profile-schema-properties-the-user_id-schema.md))
-   cannot be null
-   defined in: [The Root Schema](policy_transaction-properties-the-profile-schema-properties-the-user_id-schema.md "\#/properties/profile/properties/user_id#/properties/profile/properties/user_id")

### user_id Type

`string` ([The User_id Schema](policy_transaction-properties-the-profile-schema-properties-the-user_id-schema.md))

### user_id Examples

```json
"email|5da5ec2ad6be3073e989943b"
```

## data

An explanation about the purpose of this instance.


`data`

-   is required
-   Type: `object` ([The Data Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema.md))
-   cannot be null
-   defined in: [The Root Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema.md "\#/properties/profile/properties/data#/properties/profile/properties/data")

### data Type

`object` ([The Data Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema.md))

### data Default Value

The default value is:

```json
{}
```

### data Examples

```json
{
  "vehicleClaimsHistoryTimestamp": "2019-10-15T15:54:55.521Z",
  "previouslyRefusedInsurance": false,
  "property": {},
  "unspentCriminalConvictions": false,
  "dateOfBirthTimestamp": "2019-10-15T15:54:30.205Z",
  "dvlaUnawareOfMedicalCondition": false,
  "firstName": "Joe",
  "employmentStatus": "ED",
  "vehicleClaimsHistory": [],
  "dateOfBirth": "1977-11-11",
  "homeOwnership": "Own",
  "address": {
    "barcode": "(N403UP2AH)",
    "label": "19C Woodland Rise\nLONDON\nN40 3UP\nUNITED KINGDOM",
    "countryIsoNumber": "826",
    "dataLevel": "Premise",
    "adminAreaName": "Haringey",
    "language": "ENG",
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
    "languageAlternatives": "ENG"
  },
  "lastName": "Bloggs",
  "bankrupt": false,
  "email": "Joey+Who+Bloggs@wrisk.co",
  "advisedByDoctorNotToDrive": false,
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
  "unsatisfiedCCJs": false
}
```

## created_at

An explanation about the purpose of this instance.


`created_at`

-   is required
-   Type: `string` ([The Created_at Schema](policy_transaction-properties-the-profile-schema-properties-the-created_at-schema.md))
-   cannot be null
-   defined in: [The Root Schema](policy_transaction-properties-the-profile-schema-properties-the-created_at-schema.md "\#/properties/profile/properties/created_at#/properties/profile/properties/created_at")

### created_at Type

`string` ([The Created_at Schema](policy_transaction-properties-the-profile-schema-properties-the-created_at-schema.md))

### created_at Examples

```json
"2019-10-15T15:56:46Z"
```

## policyholder_code

An explanation about the purpose of this instance.


`policyholder_code`

-   is required
-   Type: `string` ([The Policyholder_code Schema](policy_transaction-properties-the-profile-schema-properties-the-policyholder_code-schema.md))
-   cannot be null
-   defined in: [The Root Schema](policy_transaction-properties-the-profile-schema-properties-the-policyholder_code-schema.md "\#/properties/profile/properties/policyholder_code#/properties/profile/properties/policyholder_code")

### policyholder_code Type

`string` ([The Policyholder_code Schema](policy_transaction-properties-the-profile-schema-properties-the-policyholder_code-schema.md))

### policyholder_code Examples

```json
"email|5da5ec2ad6be3073e989943b"
```
