# The Risk Factors Schema Schema

```txt
#/properties/risk_factors/items#/properties/risk_factors/items
```

A single rating factor


| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                          |
| :------------------ | ---------- | -------------- | ------------ | :---------------- | --------------------- | ------------------- | --------------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [policy_transaction.schema.json\*](../../out/policy_transaction.schema.json "open original schema") |

## items Type

`object` ([The Risk Factors Schema](policy_transaction-properties-the-risk_factors-schema-the-risk-factors-schema.md))

## items Default Value

The default value is:

```json
{}
```

## items Examples

```json
{
  "factor_level_code": "false",
  "factor_code": "AdvisedByDoctorNotToDrive"
}
```

```json
{
  "factor_level_code": "41",
  "factor_code": "Age"
}
```

# The Risk Factors Schema Properties

| Property                                | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                              |
| :-------------------------------------- | -------- | -------- | -------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [factor_code](#factor_code)             | `string` | Required | cannot be null | [The Root Schema](policy_transaction-properties-the-risk_factors-schema-the-risk-factors-schema-properties-the-factor_code-schema.md "\#/properties/risk_factors/items/properties/factor_code#/properties/risk_factors/items/properties/factor_code")                   |
| [factor_level_code](#factor_level_code) | `string` | Required | cannot be null | [The Root Schema](policy_transaction-properties-the-risk_factors-schema-the-risk-factors-schema-properties-the-factor_level_code-schema.md "\#/properties/risk_factors/items/properties/factor_level_code#/properties/risk_factors/items/properties/factor_level_code") |

## factor_code

The key for any given risk factor.


`factor_code`

-   is required
-   Type: `string` ([The Factor_code Schema](policy_transaction-properties-the-risk_factors-schema-the-risk-factors-schema-properties-the-factor_code-schema.md))
-   cannot be null
-   defined in: [The Root Schema](policy_transaction-properties-the-risk_factors-schema-the-risk-factors-schema-properties-the-factor_code-schema.md "\#/properties/risk_factors/items/properties/factor_code#/properties/risk_factors/items/properties/factor_code")

### factor_code Type

`string` ([The Factor_code Schema](policy_transaction-properties-the-risk_factors-schema-the-risk-factors-schema-properties-the-factor_code-schema.md))

### factor_code Examples

```json
"AdvisedByDoctorNotToDrive"
```

## factor_level_code

The value for any given risk factor.


`factor_level_code`

-   is required
-   Type: `string` ([The Factor_level_code Schema](policy_transaction-properties-the-risk_factors-schema-the-risk-factors-schema-properties-the-factor_level_code-schema.md))
-   cannot be null
-   defined in: [The Root Schema](policy_transaction-properties-the-risk_factors-schema-the-risk-factors-schema-properties-the-factor_level_code-schema.md "\#/properties/risk_factors/items/properties/factor_level_code#/properties/risk_factors/items/properties/factor_level_code")

### factor_level_code Type

`string` ([The Factor_level_code Schema](policy_transaction-properties-the-risk_factors-schema-the-risk-factors-schema-properties-the-factor_level_code-schema.md))

### factor_level_code Examples

```json
"false"
```
