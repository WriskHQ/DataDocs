# The Drivinglicence Schema Schema

```txt
#/properties/profile/properties/data/properties/drivingLicence#/properties/profile/properties/data/properties/drivingLicence
```

An explanation about the purpose of this instance.


| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                       |
| :------------------ | ---------- | -------------- | ------------ | :---------------- | --------------------- | ------------------- | ------------------------------------------------------------------------------------------------ |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [policy_transaction.schema.json\*](../out/policy_transaction.schema.json "open original schema") |

## drivingLicence Type

`object` ([The Drivinglicence Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-drivinglicence-schema.md))

## drivingLicence Default Value

The default value is:

```json
{}
```

## drivingLicence Examples

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

# The Drivinglicence Schema Properties

| Property                        | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                                                                                                   |
| :------------------------------ | -------- | -------- | -------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [status](#status)               | `string` | Required | cannot be null | [The Root Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-drivinglicence-schema-properties-the-status-schema.md "\#/properties/profile/properties/data/properties/drivingLicence/properties/status#/properties/profile/properties/data/properties/drivingLicence/properties/status")                      |
| [convictions](#convictions)     | `array`  | Required | cannot be null | [The Root Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-drivinglicence-schema-properties-the-convictions-schema.md "\#/properties/profile/properties/data/properties/drivingLicence/properties/convictions#/properties/profile/properties/data/properties/drivingLicence/properties/convictions")       |
| [entitlements](#entitlements)   | `array`  | Required | cannot be null | [The Root Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-drivinglicence-schema-properties-entitlements.md "\#/properties/profile/properties/data/properties/drivingLicence/properties/entitlements#/properties/profile/properties/data/properties/drivingLicence/properties/entitlements")               |
| [regionOfIssue](#regionOfIssue) | `string` | Required | cannot be null | [The Root Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-drivinglicence-schema-properties-the-regionofissue-schema.md "\#/properties/profile/properties/data/properties/drivingLicence/properties/regionOfIssue#/properties/profile/properties/data/properties/drivingLicence/properties/regionOfIssue") |

## status

An explanation about the purpose of this instance.


`status`

-   is required
-   Type: `string` ([The Status Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-drivinglicence-schema-properties-the-status-schema.md))
-   cannot be null
-   defined in: [The Root Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-drivinglicence-schema-properties-the-status-schema.md "\#/properties/profile/properties/data/properties/drivingLicence/properties/status#/properties/profile/properties/data/properties/drivingLicence/properties/status")

### status Type

`string` ([The Status Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-drivinglicence-schema-properties-the-status-schema.md))

### status Examples

```json
"FC"
```

## convictions

An explanation about the purpose of this instance.


`convictions`

-   is required
-   Type: `array` ([The Convictions Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-drivinglicence-schema-properties-the-convictions-schema.md))
-   cannot be null
-   defined in: [The Root Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-drivinglicence-schema-properties-the-convictions-schema.md "\#/properties/profile/properties/data/properties/drivingLicence/properties/convictions#/properties/profile/properties/data/properties/drivingLicence/properties/convictions")

### convictions Type

`array` ([The Convictions Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-drivinglicence-schema-properties-the-convictions-schema.md))

### convictions Default Value

The default value is:

```json
[]
```

## entitlements

Describes Entitlements attached to a customers Driving Licence.


`entitlements`

-   is required
-   Type: `object[]` ([Entitlements Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-drivinglicence-schema-properties-entitlements-entitlements-schema.md))
-   cannot be null
-   defined in: [The Root Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-drivinglicence-schema-properties-entitlements.md "\#/properties/profile/properties/data/properties/drivingLicence/properties/entitlements#/properties/profile/properties/data/properties/drivingLicence/properties/entitlements")

### entitlements Type

`object[]` ([Entitlements Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-drivinglicence-schema-properties-entitlements-entitlements-schema.md))

### entitlements Default Value

The default value is:

```json
[]
```

## regionOfIssue

An explanation about the purpose of this instance.


`regionOfIssue`

-   is required
-   Type: `string` ([The Regionofissue Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-drivinglicence-schema-properties-the-regionofissue-schema.md))
-   cannot be null
-   defined in: [The Root Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-drivinglicence-schema-properties-the-regionofissue-schema.md "\#/properties/profile/properties/data/properties/drivingLicence/properties/regionOfIssue#/properties/profile/properties/data/properties/drivingLicence/properties/regionOfIssue")

### regionOfIssue Type

`string` ([The Regionofissue Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-drivinglicence-schema-properties-the-regionofissue-schema.md))

### regionOfIssue Examples

```json
"GB"
```
