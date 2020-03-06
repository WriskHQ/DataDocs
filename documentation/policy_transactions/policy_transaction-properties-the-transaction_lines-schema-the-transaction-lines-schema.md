# The Transaction Lines schema Schema

```txt
#/properties/transaction_lines/items#/properties/transaction_lines/items
```

A object describing the lines of insurance being charged/refunded.


| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                          |
| :------------------ | ---------- | -------------- | ------------ | :---------------- | --------------------- | ------------------- | --------------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [policy_transaction.schema.json\*](../../out/policy_transaction.schema.json "open original schema") |

## items Type

`object` ([The Transaction Lines schema](policy_transaction-properties-the-transaction_lines-schema-the-transaction-lines-schema.md))

## items Default Value

The default value is:

```json
{}
```

## items Examples

```json
{
  "transaction_id": 123,
  "excess": 0,
  "transaction_premium": -3.799191,
  "cover_code": "ncb_protection",
  "agency_commission": -0.339214,
  "transaction_premium_tax": -0.4,
  "sum_insured": 1,
  "cover_period_start": "2019-10-15T16:08:25Z"
}
```

```json
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
```

# The Transaction Lines schema Properties

| Property                                            | Type      | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                                                       |
| :-------------------------------------------------- | --------- | -------- | -------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [transaction_id](#transaction_id)                   | `string`  | Required | cannot be null | [Policy Transaction](policy_transaction-properties-the-transaction_lines-schema-the-transaction-lines-schema-properties-the-transaction_id-schema.md "\#/properties/transaction_lines/items/properties/transaction_id#/properties/transaction_lines/items/properties/transaction_id")                            |
| [cover_code](#cover_code)                           | `string`  | Required | cannot be null | [Policy Transaction](policy_transaction-properties-the-transaction_lines-schema-the-transaction-lines-schema-properties-the-cover_code-schema.md "\#/properties/transaction_lines/items/properties/cover_code#/properties/transaction_lines/items/properties/cover_code")                                        |
| [transaction_premium](#transaction_premium)         | `number`  | Required | cannot be null | [Policy Transaction](policy_transaction-properties-the-transaction_lines-schema-the-transaction-lines-schema-properties-the-transaction_premium-schema.md "\#/properties/transaction_lines/items/properties/transaction_premium#/properties/transaction_lines/items/properties/transaction_premium")             |
| [transaction_premium_tax](#transaction_premium_tax) | `number`  | Required | cannot be null | [Policy Transaction](policy_transaction-properties-the-transaction_lines-schema-the-transaction-lines-schema-properties-the-transaction_premium_tax-schema.md "\#/properties/transaction_lines/items/properties/transaction_premium_tax#/properties/transaction_lines/items/properties/transaction_premium_tax") |
| [agency_commission](#agency_commission)             | `number`  | Required | cannot be null | [Policy Transaction](policy_transaction-properties-the-transaction_lines-schema-the-transaction-lines-schema-properties-the-agency_commission-schema.md "\#/properties/transaction_lines/items/properties/agency_commission#/properties/transaction_lines/items/properties/agency_commission")                   |
| [sum_insured](#sum_insured)                         | `integer` | Required | cannot be null | [Policy Transaction](policy_transaction-properties-the-transaction_lines-schema-the-transaction-lines-schema-properties-the-sum_insured-schema.md "\#/properties/transaction_lines/items/properties/sum_insured#/properties/transaction_lines/items/properties/sum_insured")                                     |
| [excess](#excess)                                   | `integer` | Required | cannot be null | [Policy Transaction](policy_transaction-properties-the-transaction_lines-schema-the-transaction-lines-schema-properties-the-excess-schema.md "\#/properties/transaction_lines/items/properties/excess#/properties/transaction_lines/items/properties/excess")                                                    |
| [cover_period_start](#cover_period_start)           | `string`  | Required | cannot be null | [Policy Transaction](policy_transaction-properties-the-transaction_lines-schema-the-transaction-lines-schema-properties-the-cover_period_start-schema.md "\#/properties/transaction_lines/items/properties/cover_period_start#/properties/transaction_lines/items/properties/cover_period_start")                |

## transaction_id

The transaction 


`transaction_id`

-   is required
-   Type: `string` ([The Transaction_id Schema](policy_transaction-properties-the-transaction_lines-schema-the-transaction-lines-schema-properties-the-transaction_id-schema.md))
-   cannot be null
-   defined in: [Policy Transaction](policy_transaction-properties-the-transaction_lines-schema-the-transaction-lines-schema-properties-the-transaction_id-schema.md "\#/properties/transaction_lines/items/properties/transaction_id#/properties/transaction_lines/items/properties/transaction_id")

### transaction_id Type

`string` ([The Transaction_id Schema](policy_transaction-properties-the-transaction_lines-schema-the-transaction-lines-schema-properties-the-transaction_id-schema.md))

### transaction_id Examples

```json
"ptxn_7nuAFtakj2KDEEtG"
```

## cover_code

A code that describes the line of cover


`cover_code`

-   is required
-   Type: `string` ([The Cover_code Schema](policy_transaction-properties-the-transaction_lines-schema-the-transaction-lines-schema-properties-the-cover_code-schema.md))
-   cannot be null
-   defined in: [Policy Transaction](policy_transaction-properties-the-transaction_lines-schema-the-transaction-lines-schema-properties-the-cover_code-schema.md "\#/properties/transaction_lines/items/properties/cover_code#/properties/transaction_lines/items/properties/cover_code")

### cover_code Type

`string` ([The Cover_code Schema](policy_transaction-properties-the-transaction_lines-schema-the-transaction-lines-schema-properties-the-cover_code-schema.md))

### cover_code Examples

```json
"ncb_protection"
```

```json
"driver_injury"
```

```json
"misfuelling"
```

```json
"damage_to_car"
```

```json
"foreign_travel"
```

```json
"backup_ride"
```

```json
"legal_expenses"
```

## transaction_premium

The total premium due for this line of cover on this transaction


`transaction_premium`

-   is required
-   Type: `number` ([The Transaction_premium Schema](policy_transaction-properties-the-transaction_lines-schema-the-transaction-lines-schema-properties-the-transaction_premium-schema.md))
-   cannot be null
-   defined in: [Policy Transaction](policy_transaction-properties-the-transaction_lines-schema-the-transaction-lines-schema-properties-the-transaction_premium-schema.md "\#/properties/transaction_lines/items/properties/transaction_premium#/properties/transaction_lines/items/properties/transaction_premium")

### transaction_premium Type

`number` ([The Transaction_premium Schema](policy_transaction-properties-the-transaction_lines-schema-the-transaction-lines-schema-properties-the-transaction_premium-schema.md))

### transaction_premium Examples

```json
3.79
```

## transaction_premium_tax

The total Insurance Premium Tax due for this line of cover on this transaction


`transaction_premium_tax`

-   is required
-   Type: `number` ([The Transaction_premium_tax Schema](policy_transaction-properties-the-transaction_lines-schema-the-transaction-lines-schema-properties-the-transaction_premium_tax-schema.md))
-   cannot be null
-   defined in: [Policy Transaction](policy_transaction-properties-the-transaction_lines-schema-the-transaction-lines-schema-properties-the-transaction_premium_tax-schema.md "\#/properties/transaction_lines/items/properties/transaction_premium_tax#/properties/transaction_lines/items/properties/transaction_premium_tax")

### transaction_premium_tax Type

`number` ([The Transaction_premium_tax Schema](policy_transaction-properties-the-transaction_lines-schema-the-transaction-lines-schema-properties-the-transaction_premium_tax-schema.md))

### transaction_premium_tax Examples

```json
0.4
```

## agency_commission

The Commission to be kept by Wrisk and it's distribution partner for this transaction


`agency_commission`

-   is required
-   Type: `number` ([The Agency_commission Schema](policy_transaction-properties-the-transaction_lines-schema-the-transaction-lines-schema-properties-the-agency_commission-schema.md))
-   cannot be null
-   defined in: [Policy Transaction](policy_transaction-properties-the-transaction_lines-schema-the-transaction-lines-schema-properties-the-agency_commission-schema.md "\#/properties/transaction_lines/items/properties/agency_commission#/properties/transaction_lines/items/properties/agency_commission")

### agency_commission Type

`number` ([The Agency_commission Schema](policy_transaction-properties-the-transaction_lines-schema-the-transaction-lines-schema-properties-the-agency_commission-schema.md))

### agency_commission Examples

```json
0.33
```

## sum_insured

The amount insured on this transaction - Not applicable to car insurance.


`sum_insured`

-   is required
-   Type: `integer` ([The Sum_insured Schema](policy_transaction-properties-the-transaction_lines-schema-the-transaction-lines-schema-properties-the-sum_insured-schema.md))
-   cannot be null
-   defined in: [Policy Transaction](policy_transaction-properties-the-transaction_lines-schema-the-transaction-lines-schema-properties-the-sum_insured-schema.md "\#/properties/transaction_lines/items/properties/sum_insured#/properties/transaction_lines/items/properties/sum_insured")

### sum_insured Type

`integer` ([The Sum_insured Schema](policy_transaction-properties-the-transaction_lines-schema-the-transaction-lines-schema-properties-the-sum_insured-schema.md))

### sum_insured Examples

```json
1
```

## excess

The customers' excess for this line of cover.


`excess`

-   is required
-   Type: `integer` ([The Excess Schema](policy_transaction-properties-the-transaction_lines-schema-the-transaction-lines-schema-properties-the-excess-schema.md))
-   cannot be null
-   defined in: [Policy Transaction](policy_transaction-properties-the-transaction_lines-schema-the-transaction-lines-schema-properties-the-excess-schema.md "\#/properties/transaction_lines/items/properties/excess#/properties/transaction_lines/items/properties/excess")

### excess Type

`integer` ([The Excess Schema](policy_transaction-properties-the-transaction_lines-schema-the-transaction-lines-schema-properties-the-excess-schema.md))

### excess Examples

```json
0
```

## cover_period_start

The start of the period in which the transaction was created


`cover_period_start`

-   is required
-   Type: `string` ([The Cover_period_start Schema](policy_transaction-properties-the-transaction_lines-schema-the-transaction-lines-schema-properties-the-cover_period_start-schema.md))
-   cannot be null
-   defined in: [Policy Transaction](policy_transaction-properties-the-transaction_lines-schema-the-transaction-lines-schema-properties-the-cover_period_start-schema.md "\#/properties/transaction_lines/items/properties/cover_period_start#/properties/transaction_lines/items/properties/cover_period_start")

### cover_period_start Type

`string` ([The Cover_period_start Schema](policy_transaction-properties-the-transaction_lines-schema-the-transaction-lines-schema-properties-the-cover_period_start-schema.md))

### cover_period_start Examples

```json
"2019-10-15T16:08:25Z"
```
