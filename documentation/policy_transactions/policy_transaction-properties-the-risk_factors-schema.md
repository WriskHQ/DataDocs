# The Risk_factors Schema Schema

```txt
#/properties/risk_factors#/properties/risk_factors
```

An array that describes the factors which are used to price the insurance risk.


| Abstract            | Extensible | Status         | Identifiable            | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                          |
| :------------------ | ---------- | -------------- | ----------------------- | :---------------- | --------------------- | ------------------- | --------------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | Unknown identifiability | Forbidden         | Allowed               | none                | [policy_transaction.schema.json\*](../../out/policy_transaction.schema.json "open original schema") |

## risk_factors Type

`object[]` ([The Risk Factors Schema](policy_transaction-properties-the-risk_factors-schema-the-risk-factors-schema.md))

## risk_factors Default Value

The default value is:

```json
[]
```

## risk_factors Examples

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
