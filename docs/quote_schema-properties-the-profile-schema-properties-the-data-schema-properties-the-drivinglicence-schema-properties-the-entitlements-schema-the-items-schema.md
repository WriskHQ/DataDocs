# The Items Schema Schema

```txt
#/properties/profile/properties/data/properties/drivingLicence/properties/entitlements/items#/properties/profile/properties/data/properties/drivingLicence/properties/entitlements/items
```

An explanation about the purpose of this instance.


| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                           |
| :------------------ | ---------- | -------------- | ------------ | :---------------- | --------------------- | ------------------- | ------------------------------------------------------------------------------------ |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [quote_schema.schema.json\*](../out/quote_schema.schema.json "open original schema") |

## items Type

`object` ([The Items Schema](quote_schema-properties-the-profile-schema-properties-the-data-schema-properties-the-drivinglicence-schema-properties-the-entitlements-schema-the-items-schema.md))

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

# The Items Schema Properties

| Property                | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| :---------------------- | -------- | -------- | -------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [code](#code)           | `string` | Required | cannot be null | [The Root Schema](quote_schema-properties-the-profile-schema-properties-the-data-schema-properties-the-drivinglicence-schema-properties-the-entitlements-schema-the-items-schema-properties-the-code-schema.md "\#/properties/profile/properties/data/properties/drivingLicence/properties/entitlements/items/properties/code#/properties/profile/properties/data/properties/drivingLicence/properties/entitlements/items/properties/code")                |
| [type](#type)           | `string` | Required | cannot be null | [The Root Schema](quote_schema-properties-the-profile-schema-properties-the-data-schema-properties-the-drivinglicence-schema-properties-the-entitlements-schema-the-items-schema-properties-the-type-schema.md "\#/properties/profile/properties/data/properties/drivingLicence/properties/entitlements/items/properties/type#/properties/profile/properties/data/properties/drivingLicence/properties/entitlements/items/properties/type")                |
| [validFrom](#validFrom) | `string` | Required | cannot be null | [The Root Schema](quote_schema-properties-the-profile-schema-properties-the-data-schema-properties-the-drivinglicence-schema-properties-the-entitlements-schema-the-items-schema-properties-the-validfrom-schema.md "\#/properties/profile/properties/data/properties/drivingLicence/properties/entitlements/items/properties/validFrom#/properties/profile/properties/data/properties/drivingLicence/properties/entitlements/items/properties/validFrom") |

## code

An explanation about the purpose of this instance.


`code`

-   is required
-   Type: `string` ([The Code Schema](quote_schema-properties-the-profile-schema-properties-the-data-schema-properties-the-drivinglicence-schema-properties-the-entitlements-schema-the-items-schema-properties-the-code-schema.md))
-   cannot be null
-   defined in: [The Root Schema](quote_schema-properties-the-profile-schema-properties-the-data-schema-properties-the-drivinglicence-schema-properties-the-entitlements-schema-the-items-schema-properties-the-code-schema.md "\#/properties/profile/properties/data/properties/drivingLicence/properties/entitlements/items/properties/code#/properties/profile/properties/data/properties/drivingLicence/properties/entitlements/items/properties/code")

### code Type

`string` ([The Code Schema](quote_schema-properties-the-profile-schema-properties-the-data-schema-properties-the-drivinglicence-schema-properties-the-entitlements-schema-the-items-schema-properties-the-code-schema.md))

### code Examples

```json
"B"
```

## type

An explanation about the purpose of this instance.


`type`

-   is required
-   Type: `string` ([The Type Schema](quote_schema-properties-the-profile-schema-properties-the-data-schema-properties-the-drivinglicence-schema-properties-the-entitlements-schema-the-items-schema-properties-the-type-schema.md))
-   cannot be null
-   defined in: [The Root Schema](quote_schema-properties-the-profile-schema-properties-the-data-schema-properties-the-drivinglicence-schema-properties-the-entitlements-schema-the-items-schema-properties-the-type-schema.md "\#/properties/profile/properties/data/properties/drivingLicence/properties/entitlements/items/properties/type#/properties/profile/properties/data/properties/drivingLicence/properties/entitlements/items/properties/type")

### type Type

`string` ([The Type Schema](quote_schema-properties-the-profile-schema-properties-the-data-schema-properties-the-drivinglicence-schema-properties-the-entitlements-schema-the-items-schema-properties-the-type-schema.md))

### type Examples

```json
"F"
```

## validFrom

An explanation about the purpose of this instance.


`validFrom`

-   is required
-   Type: `string` ([The Validfrom Schema](quote_schema-properties-the-profile-schema-properties-the-data-schema-properties-the-drivinglicence-schema-properties-the-entitlements-schema-the-items-schema-properties-the-validfrom-schema.md))
-   cannot be null
-   defined in: [The Root Schema](quote_schema-properties-the-profile-schema-properties-the-data-schema-properties-the-drivinglicence-schema-properties-the-entitlements-schema-the-items-schema-properties-the-validfrom-schema.md "\#/properties/profile/properties/data/properties/drivingLicence/properties/entitlements/items/properties/validFrom#/properties/profile/properties/data/properties/drivingLicence/properties/entitlements/items/properties/validFrom")

### validFrom Type

`string` ([The Validfrom Schema](quote_schema-properties-the-profile-schema-properties-the-data-schema-properties-the-drivinglicence-schema-properties-the-entitlements-schema-the-items-schema-properties-the-validfrom-schema.md))

### validFrom Examples

```json
"2000-11-01"
```
