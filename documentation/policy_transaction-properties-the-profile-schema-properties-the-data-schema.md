# The Data Schema Schema

```txt
#/properties/profile/properties/data#/properties/profile/properties/data
```

An explanation about the purpose of this instance.


| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                       |
| :------------------ | ---------- | -------------- | ------------ | :---------------- | --------------------- | ------------------- | ------------------------------------------------------------------------------------------------ |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [policy_transaction.schema.json\*](../out/policy_transaction.schema.json "open original schema") |

## data Type

`object` ([The Data Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema.md))

## data Default Value

The default value is:

```json
{}
```

## data Examples

```json
{
  "vehicleClaimsHistoryTimestamp": "2019-10-15T15:54:55.521Z",
  "previouslyRefusedInsurance": false,
  "property": {},
  "unspentCriminalConvictions": false,
  "dateOfBirthTimestamp": "2019-10-15T15:54:30.205Z",
  "dvlaUnawareOfMedicalCondition": false,
  "firstName": "Benedikt",
  "employmentStatus": "ED",
  "vehicleClaimsHistory": [],
  "dateOfBirth": "1977-11-11",
  "homeOwnership": "Own",
  "address": {
    "barcode": "(N103UP2AH)",
    "label": "19C Woodland Rise\nLONDON\nN10 3UP\nUNITED KINGDOM",
    "countryIsoNumber": "826",
    "dataLevel": "Premise",
    "adminAreaName": "Haringey",
    "language": "ENG",
    "type": "Residential",
    "countryName": "United Kingdom",
    "pcaId": "GB|RM|B|15592178",
    "postalCode": "N10 3UP",
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
  "lastName": "Heiss",
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

# The Data Schema Properties

| Property                                                        | Type      | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                                                          |
| :-------------------------------------------------------------- | --------- | -------- | -------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [email](#email)                                                 | `string`  | Required | cannot be null | [The Root Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-email-schema.md "\#/properties/profile/properties/data/properties/email#/properties/profile/properties/data/properties/email")                                                                         |
| [address](#address)                                             | `object`  | Required | cannot be null | [The Root Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-address-schema.md "\#/properties/profile/properties/data/properties/address#/properties/profile/properties/data/properties/address")                                                                   |
| [bankrupt](#bankrupt)                                           | `boolean` | Required | cannot be null | [The Root Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-bankrupt-schema.md "\#/properties/profile/properties/data/properties/bankrupt#/properties/profile/properties/data/properties/bankrupt")                                                                |
| [lastName](#lastName)                                           | `string`  | Required | cannot be null | [The Root Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-lastname-schema.md "\#/properties/profile/properties/data/properties/lastName#/properties/profile/properties/data/properties/lastName")                                                                |
| [property](#property)                                           | `object`  | Required | cannot be null | [The Root Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-property-schema.md "\#/properties/profile/properties/data/properties/property#/properties/profile/properties/data/properties/property")                                                                |
| [firstName](#firstName)                                         | `string`  | Required | cannot be null | [The Root Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-firstname-schema.md "\#/properties/profile/properties/data/properties/firstName#/properties/profile/properties/data/properties/firstName")                                                             |
| [dateOfBirth](#dateOfBirth)                                     | `string`  | Required | cannot be null | [The Root Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-dateofbirth-schema.md "\#/properties/profile/properties/data/properties/dateOfBirth#/properties/profile/properties/data/properties/dateOfBirth")                                                       |
| [homeOwnership](#homeOwnership)                                 | `string`  | Required | cannot be null | [The Root Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-homeownership-schema.md "\#/properties/profile/properties/data/properties/homeOwnership#/properties/profile/properties/data/properties/homeOwnership")                                                 |
| [maritalStatus](#maritalStatus)                                 | `string`  | Required | cannot be null | [The Root Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-maritalstatus-schema.md "\#/properties/profile/properties/data/properties/maritalStatus#/properties/profile/properties/data/properties/maritalStatus")                                                 |
| [drivingLicence](#drivingLicence)                               | `object`  | Required | cannot be null | [The Root Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-drivinglicence-schema.md "\#/properties/profile/properties/data/properties/drivingLicence#/properties/profile/properties/data/properties/drivingLicence")                                              |
| [unsatisfiedCCJs](#unsatisfiedCCJs)                             | `boolean` | Required | cannot be null | [The Root Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-unsatisfiedccjs-schema.md "\#/properties/profile/properties/data/properties/unsatisfiedCCJs#/properties/profile/properties/data/properties/unsatisfiedCCJs")                                           |
| [employmentStatus](#employmentStatus)                           | `string`  | Required | cannot be null | [The Root Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-employmentstatus-schema.md "\#/properties/profile/properties/data/properties/employmentStatus#/properties/profile/properties/data/properties/employmentStatus")                                        |
| [dateOfBirthTimestamp](#dateOfBirthTimestamp)                   | `string`  | Required | cannot be null | [The Root Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-dateofbirthtimestamp-schema.md "\#/properties/profile/properties/data/properties/dateOfBirthTimestamp#/properties/profile/properties/data/properties/dateOfBirthTimestamp")                            |
| [vehicleClaimsHistory](#vehicleClaimsHistory)                   | `array`   | Required | cannot be null | [The Root Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-vehicleclaimshistory-schema.md "\#/properties/profile/properties/data/properties/vehicleClaimsHistory#/properties/profile/properties/data/properties/vehicleClaimsHistory")                            |
| [advisedByDoctorNotToDrive](#advisedByDoctorNotToDrive)         | `boolean` | Required | cannot be null | [The Root Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-advisedbydoctornottodrive-schema.md "\#/properties/profile/properties/data/properties/advisedByDoctorNotToDrive#/properties/profile/properties/data/properties/advisedByDoctorNotToDrive")             |
| [previouslyRefusedInsurance](#previouslyRefusedInsurance)       | `boolean` | Required | cannot be null | [The Root Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-previouslyrefusedinsurance-schema.md "\#/properties/profile/properties/data/properties/previouslyRefusedInsurance#/properties/profile/properties/data/properties/previouslyRefusedInsurance")          |
| [unspentCriminalConvictions](#unspentCriminalConvictions)       | `boolean` | Required | cannot be null | [The Root Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-unspentcriminalconvictions-schema.md "\#/properties/profile/properties/data/properties/unspentCriminalConvictions#/properties/profile/properties/data/properties/unspentCriminalConvictions")          |
| [dvlaUnawareOfMedicalCondition](#dvlaUnawareOfMedicalCondition) | `boolean` | Required | cannot be null | [The Root Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-dvlaunawareofmedicalcondition-schema.md "\#/properties/profile/properties/data/properties/dvlaUnawareOfMedicalCondition#/properties/profile/properties/data/properties/dvlaUnawareOfMedicalCondition") |
| [vehicleClaimsHistoryTimestamp](#vehicleClaimsHistoryTimestamp) | `string`  | Required | cannot be null | [The Root Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-vehicleclaimshistorytimestamp-schema.md "\#/properties/profile/properties/data/properties/vehicleClaimsHistoryTimestamp#/properties/profile/properties/data/properties/vehicleClaimsHistoryTimestamp") |

## email

An explanation about the purpose of this instance.


`email`

-   is required
-   Type: `string` ([The Email Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-email-schema.md))
-   cannot be null
-   defined in: [The Root Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-email-schema.md "\#/properties/profile/properties/data/properties/email#/properties/profile/properties/data/properties/email")

### email Type

`string` ([The Email Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-email-schema.md))

### email Examples

```json
"Joey+Who+Bloggs@wrisk.co"
```

## address

An explanation about the purpose of this instance.


`address`

-   is required
-   Type: `object` ([The Address Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-address-schema.md))
-   cannot be null
-   defined in: [The Root Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-address-schema.md "\#/properties/profile/properties/data/properties/address#/properties/profile/properties/data/properties/address")

### address Type

`object` ([The Address Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-address-schema.md))

### address Default Value

The default value is:

```json
{}
```

### address Examples

```json
{
  "type": "Residential",
  "countryName": "United Kingdom",
  "pcaId": "GB|RM|B|15592178",
  "postalCode": "N10 3UP",
  "city": "London",
  "countryIso2": "GB",
  "countryIso3": "GBR",
  "street": "Woodland Rise",
  "buildingName": "19C",
  "sortingNumber1": "62123",
  "line1": "19C Woodland Rise",
  "domesticId": "15592178",
  "languageAlternatives": "ENG",
  "barcode": "(N103UP2AH)",
  "label": "19C Woodland Rise\nLONDON\nN10 3UP\nUNITED KINGDOM",
  "countryIsoNumber": "826",
  "dataLevel": "Premise",
  "adminAreaName": "Haringey",
  "language": "ENG"
}
```

## bankrupt

An explanation about the purpose of this instance.


`bankrupt`

-   is required
-   Type: `boolean` ([The Bankrupt Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-bankrupt-schema.md))
-   cannot be null
-   defined in: [The Root Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-bankrupt-schema.md "\#/properties/profile/properties/data/properties/bankrupt#/properties/profile/properties/data/properties/bankrupt")

### bankrupt Type

`boolean` ([The Bankrupt Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-bankrupt-schema.md))

### bankrupt Examples

```json
false
```

## lastName

An explanation about the purpose of this instance.


`lastName`

-   is required
-   Type: `string` ([The Lastname Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-lastname-schema.md))
-   cannot be null
-   defined in: [The Root Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-lastname-schema.md "\#/properties/profile/properties/data/properties/lastName#/properties/profile/properties/data/properties/lastName")

### lastName Type

`string` ([The Lastname Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-lastname-schema.md))

### lastName Examples

```json
"Heiss"
```

## property

An explanation about the purpose of this instance.


`property`

-   is required
-   Type: `object` ([The Property Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-property-schema.md))
-   cannot be null
-   defined in: [The Root Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-property-schema.md "\#/properties/profile/properties/data/properties/property#/properties/profile/properties/data/properties/property")

### property Type

`object` ([The Property Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-property-schema.md))

### property Default Value

The default value is:

```json
{}
```

### property Examples

```json
{}
```

## firstName

An explanation about the purpose of this instance.


`firstName`

-   is required
-   Type: `string` ([The Firstname Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-firstname-schema.md))
-   cannot be null
-   defined in: [The Root Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-firstname-schema.md "\#/properties/profile/properties/data/properties/firstName#/properties/profile/properties/data/properties/firstName")

### firstName Type

`string` ([The Firstname Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-firstname-schema.md))

### firstName Examples

```json
"Benedikt"
```

## dateOfBirth

An explanation about the purpose of this instance.


`dateOfBirth`

-   is required
-   Type: `string` ([The Dateofbirth Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-dateofbirth-schema.md))
-   cannot be null
-   defined in: [The Root Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-dateofbirth-schema.md "\#/properties/profile/properties/data/properties/dateOfBirth#/properties/profile/properties/data/properties/dateOfBirth")

### dateOfBirth Type

`string` ([The Dateofbirth Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-dateofbirth-schema.md))

### dateOfBirth Examples

```json
"1977-11-11"
```

## homeOwnership

An explanation about the purpose of this instance.


`homeOwnership`

-   is required
-   Type: `string` ([The Homeownership Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-homeownership-schema.md))
-   cannot be null
-   defined in: [The Root Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-homeownership-schema.md "\#/properties/profile/properties/data/properties/homeOwnership#/properties/profile/properties/data/properties/homeOwnership")

### homeOwnership Type

`string` ([The Homeownership Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-homeownership-schema.md))

### homeOwnership Examples

```json
"Own"
```

## maritalStatus

An explanation about the purpose of this instance.


`maritalStatus`

-   is required
-   Type: `string` ([The Maritalstatus Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-maritalstatus-schema.md))
-   cannot be null
-   defined in: [The Root Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-maritalstatus-schema.md "\#/properties/profile/properties/data/properties/maritalStatus#/properties/profile/properties/data/properties/maritalStatus")

### maritalStatus Type

`string` ([The Maritalstatus Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-maritalstatus-schema.md))

### maritalStatus Examples

```json
"Married"
```

## drivingLicence

An explanation about the purpose of this instance.


`drivingLicence`

-   is required
-   Type: `object` ([The Drivinglicence Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-drivinglicence-schema.md))
-   cannot be null
-   defined in: [The Root Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-drivinglicence-schema.md "\#/properties/profile/properties/data/properties/drivingLicence#/properties/profile/properties/data/properties/drivingLicence")

### drivingLicence Type

`object` ([The Drivinglicence Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-drivinglicence-schema.md))

### drivingLicence Default Value

The default value is:

```json
{}
```

### drivingLicence Examples

```json
{
  "status": "FC",
  "entitlements": [
    {
      "code": "B",
      "validFrom": "2000-11-01",
      "type": "F"
    }
  ],
  "regionOfIssue": "GB",
  "convictions": []
}
```

## unsatisfiedCCJs

An explanation about the purpose of this instance.


`unsatisfiedCCJs`

-   is required
-   Type: `boolean` ([The Unsatisfiedccjs Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-unsatisfiedccjs-schema.md))
-   cannot be null
-   defined in: [The Root Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-unsatisfiedccjs-schema.md "\#/properties/profile/properties/data/properties/unsatisfiedCCJs#/properties/profile/properties/data/properties/unsatisfiedCCJs")

### unsatisfiedCCJs Type

`boolean` ([The Unsatisfiedccjs Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-unsatisfiedccjs-schema.md))

### unsatisfiedCCJs Examples

```json
false
```

## employmentStatus

An explanation about the purpose of this instance.


`employmentStatus`

-   is required
-   Type: `string` ([The Employmentstatus Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-employmentstatus-schema.md))
-   cannot be null
-   defined in: [The Root Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-employmentstatus-schema.md "\#/properties/profile/properties/data/properties/employmentStatus#/properties/profile/properties/data/properties/employmentStatus")

### employmentStatus Type

`string` ([The Employmentstatus Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-employmentstatus-schema.md))

### employmentStatus Examples

```json
"ED"
```

## dateOfBirthTimestamp

An explanation about the purpose of this instance.


`dateOfBirthTimestamp`

-   is required
-   Type: `string` ([The Dateofbirthtimestamp Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-dateofbirthtimestamp-schema.md))
-   cannot be null
-   defined in: [The Root Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-dateofbirthtimestamp-schema.md "\#/properties/profile/properties/data/properties/dateOfBirthTimestamp#/properties/profile/properties/data/properties/dateOfBirthTimestamp")

### dateOfBirthTimestamp Type

`string` ([The Dateofbirthtimestamp Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-dateofbirthtimestamp-schema.md))

### dateOfBirthTimestamp Examples

```json
"2019-10-15T15:54:30.205Z"
```

## vehicleClaimsHistory

An explanation about the purpose of this instance.


`vehicleClaimsHistory`

-   is required
-   Type: `array` ([The Vehicleclaimshistory Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-vehicleclaimshistory-schema.md))
-   cannot be null
-   defined in: [The Root Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-vehicleclaimshistory-schema.md "\#/properties/profile/properties/data/properties/vehicleClaimsHistory#/properties/profile/properties/data/properties/vehicleClaimsHistory")

### vehicleClaimsHistory Type

`array` ([The Vehicleclaimshistory Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-vehicleclaimshistory-schema.md))

### vehicleClaimsHistory Default Value

The default value is:

```json
[]
```

## advisedByDoctorNotToDrive

An explanation about the purpose of this instance.


`advisedByDoctorNotToDrive`

-   is required
-   Type: `boolean` ([The Advisedbydoctornottodrive Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-advisedbydoctornottodrive-schema.md))
-   cannot be null
-   defined in: [The Root Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-advisedbydoctornottodrive-schema.md "\#/properties/profile/properties/data/properties/advisedByDoctorNotToDrive#/properties/profile/properties/data/properties/advisedByDoctorNotToDrive")

### advisedByDoctorNotToDrive Type

`boolean` ([The Advisedbydoctornottodrive Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-advisedbydoctornottodrive-schema.md))

### advisedByDoctorNotToDrive Examples

```json
false
```

## previouslyRefusedInsurance

An explanation about the purpose of this instance.


`previouslyRefusedInsurance`

-   is required
-   Type: `boolean` ([The Previouslyrefusedinsurance Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-previouslyrefusedinsurance-schema.md))
-   cannot be null
-   defined in: [The Root Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-previouslyrefusedinsurance-schema.md "\#/properties/profile/properties/data/properties/previouslyRefusedInsurance#/properties/profile/properties/data/properties/previouslyRefusedInsurance")

### previouslyRefusedInsurance Type

`boolean` ([The Previouslyrefusedinsurance Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-previouslyrefusedinsurance-schema.md))

### previouslyRefusedInsurance Examples

```json
false
```

## unspentCriminalConvictions

An explanation about the purpose of this instance.


`unspentCriminalConvictions`

-   is required
-   Type: `boolean` ([The Unspentcriminalconvictions Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-unspentcriminalconvictions-schema.md))
-   cannot be null
-   defined in: [The Root Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-unspentcriminalconvictions-schema.md "\#/properties/profile/properties/data/properties/unspentCriminalConvictions#/properties/profile/properties/data/properties/unspentCriminalConvictions")

### unspentCriminalConvictions Type

`boolean` ([The Unspentcriminalconvictions Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-unspentcriminalconvictions-schema.md))

### unspentCriminalConvictions Examples

```json
false
```

## dvlaUnawareOfMedicalCondition

An explanation about the purpose of this instance.


`dvlaUnawareOfMedicalCondition`

-   is required
-   Type: `boolean` ([The Dvlaunawareofmedicalcondition Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-dvlaunawareofmedicalcondition-schema.md))
-   cannot be null
-   defined in: [The Root Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-dvlaunawareofmedicalcondition-schema.md "\#/properties/profile/properties/data/properties/dvlaUnawareOfMedicalCondition#/properties/profile/properties/data/properties/dvlaUnawareOfMedicalCondition")

### dvlaUnawareOfMedicalCondition Type

`boolean` ([The Dvlaunawareofmedicalcondition Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-dvlaunawareofmedicalcondition-schema.md))

### dvlaUnawareOfMedicalCondition Examples

```json
false
```

## vehicleClaimsHistoryTimestamp

An explanation about the purpose of this instance.


`vehicleClaimsHistoryTimestamp`

-   is required
-   Type: `string` ([The Vehicleclaimshistorytimestamp Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-vehicleclaimshistorytimestamp-schema.md))
-   cannot be null
-   defined in: [The Root Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-vehicleclaimshistorytimestamp-schema.md "\#/properties/profile/properties/data/properties/vehicleClaimsHistoryTimestamp#/properties/profile/properties/data/properties/vehicleClaimsHistoryTimestamp")

### vehicleClaimsHistoryTimestamp Type

`string` ([The Vehicleclaimshistorytimestamp Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-vehicleclaimshistorytimestamp-schema.md))

### vehicleClaimsHistoryTimestamp Examples

```json
"2019-10-15T15:54:55.521Z"
```
