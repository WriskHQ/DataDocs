# Entitlements Schema Schema

```txt
#/properties/profile/properties/data/properties/drivingLicence/properties/entitlements/items#/properties/profile/properties/data/properties/drivingLicence/properties/entitlements/items
```

An explanation about the purpose of this instance.


| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                       |
| :------------------ | ---------- | -------------- | ------------ | :---------------- | --------------------- | ------------------- | ------------------------------------------------------------------------------------------------ |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [policy_transaction.schema.json\*](../out/policy_transaction.schema.json "open original schema") |

## items Type

`object` ([Entitlements Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-drivinglicence-schema-properties-the-entitlements-schema-entitlements-schema.md))

## items Default Value

The default value is:

```json
{}
```

## items Examples

```json
{
  "type": "F",
  "code": "B",
  "validFrom": "2000-11-01"
}
```

# Entitlements Schema Properties

| Property                | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| :---------------------- | -------- | -------- | -------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [code](#code)           | `string` | Required | cannot be null | [The Root Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-drivinglicence-schema-properties-the-entitlements-schema-entitlements-schema-properties-the-code-schema.md "\#/properties/profile/properties/data/properties/drivingLicence/properties/entitlements/items/properties/code#/properties/profile/properties/data/properties/drivingLicence/properties/entitlements/items/properties/code")                |
| [type](#type)           | `string` | Required | cannot be null | [The Root Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-drivinglicence-schema-properties-the-entitlements-schema-entitlements-schema-properties-the-type-schema.md "\#/properties/profile/properties/data/properties/drivingLicence/properties/entitlements/items/properties/type#/properties/profile/properties/data/properties/drivingLicence/properties/entitlements/items/properties/type")                |
| [validFrom](#validFrom) | `string` | Required | cannot be null | [The Root Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-drivinglicence-schema-properties-the-entitlements-schema-entitlements-schema-properties-the-validfrom-schema.md "\#/properties/profile/properties/data/properties/drivingLicence/properties/entitlements/items/properties/validFrom#/properties/profile/properties/data/properties/drivingLicence/properties/entitlements/items/properties/validFrom") |

## code

An explanation about the purpose of this instance.


`code`

-   is required
-   Type: `string` ([The Code Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-drivinglicence-schema-properties-the-entitlements-schema-entitlements-schema-properties-the-code-schema.md))
-   cannot be null
-   defined in: [The Root Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-drivinglicence-schema-properties-the-entitlements-schema-entitlements-schema-properties-the-code-schema.md "\#/properties/profile/properties/data/properties/drivingLicence/properties/entitlements/items/properties/code#/properties/profile/properties/data/properties/drivingLicence/properties/entitlements/items/properties/code")

### code Type

`string` ([The Code Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-drivinglicence-schema-properties-the-entitlements-schema-entitlements-schema-properties-the-code-schema.md))

### code Examples

```json
"B"
```

```json
"B auto"
```

## type

An explanation about the purpose of this instance.


`type`

-   is required
-   Type: `string` ([The Type Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-drivinglicence-schema-properties-the-entitlements-schema-entitlements-schema-properties-the-type-schema.md))
-   cannot be null
-   defined in: [The Root Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-drivinglicence-schema-properties-the-entitlements-schema-entitlements-schema-properties-the-type-schema.md "\#/properties/profile/properties/data/properties/drivingLicence/properties/entitlements/items/properties/type#/properties/profile/properties/data/properties/drivingLicence/properties/entitlements/items/properties/type")

### type Type

`string` ([The Type Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-drivinglicence-schema-properties-the-entitlements-schema-entitlements-schema-properties-the-type-schema.md))

### type Examples

```json
"F"
```

```json
"P"
```

## validFrom

An explanation about the purpose of this instance.


`validFrom`

-   is required
-   Type: `string` ([The Validfrom Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-drivinglicence-schema-properties-the-entitlements-schema-entitlements-schema-properties-the-validfrom-schema.md))
-   cannot be null
-   defined in: [The Root Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-drivinglicence-schema-properties-the-entitlements-schema-entitlements-schema-properties-the-validfrom-schema.md "\#/properties/profile/properties/data/properties/drivingLicence/properties/entitlements/items/properties/validFrom#/properties/profile/properties/data/properties/drivingLicence/properties/entitlements/items/properties/validFrom")

### validFrom Type

`string` ([The Validfrom Schema](policy_transaction-properties-the-profile-schema-properties-the-data-schema-properties-the-drivinglicence-schema-properties-the-entitlements-schema-entitlements-schema-properties-the-validfrom-schema.md))

### validFrom Examples

```json
"2000-11-01"
```
