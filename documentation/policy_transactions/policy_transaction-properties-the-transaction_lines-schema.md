# The Transaction_lines Schema Schema

```txt
#/properties/transaction_lines#/properties/transaction_lines
```

A line of insurance cover that has been charged/refunded to the customer.


| Abstract            | Extensible | Status         | Identifiable            | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                          |
| :------------------ | ---------- | -------------- | ----------------------- | :---------------- | --------------------- | ------------------- | --------------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | Unknown identifiability | Forbidden         | Allowed               | none                | [policy_transaction.schema.json\*](../../out/policy_transaction.schema.json "open original schema") |

## transaction_lines Type

`object[]` ([Transaction Lines](policy_transaction-properties-the-transaction_lines-schema-transaction-lines.md))

## transaction_lines Default Value

The default value is:

```json
[]
```

## transaction_lines Examples

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
