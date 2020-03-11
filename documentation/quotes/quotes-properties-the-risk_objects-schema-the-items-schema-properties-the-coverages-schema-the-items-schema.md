# The Items Schema Schema

```txt
#/properties/risk_objects/items/properties/coverages/items#/properties/risk_objects/items/properties/coverages/items
```

An explanation about the purpose of this instance.


| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                  |
| :------------------ | ---------- | -------------- | ------------ | :---------------- | --------------------- | ------------------- | --------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [quotes.schema.json\*](../../out/quotes.schema.json "open original schema") |

## items Type

`object` ([The Items Schema](quotes-properties-the-risk_objects-schema-the-items-schema-properties-the-coverages-schema-the-items-schema.md))

## items Default Value

The default value is:

```json
{}
```

## items Examples

```json
{
  "gross_premium": "1.33929",
  "co_payment": "0.00000",
  "excess": "0.00000",
  "limit": "1.00000",
  "type": "driver_injury"
}
```

```json
{
  "co_payment": "0.00000",
  "excess": "0.00000",
  "limit": "1.00000",
  "type": "accessories",
  "gross_premium": "0.89286"
}
```

```json
{
  "co_payment": "0.00000",
  "excess": "0.00000",
  "limit": "1.00000",
  "type": "misfuelling",
  "gross_premium": "1.11607"
}
```

```json
{
  "co_payment": "0.00000",
  "excess": "600.00000",
  "limit": "1.00000",
  "type": "foreign_travel",
  "gross_premium": "2.23214"
}
```

```json
{
  "co_payment": "0.00000",
  "excess": "0.00000",
  "limit": "1.00000",
  "type": "backup_ride",
  "gross_premium": "1.07143"
}
```

```json
{
  "type": "damage_to_car",
  "gross_premium": "13.38367",
  "co_payment": "0.00000",
  "excess": "600.00000",
  "limit": "1.00000"
}
```

# The Items Schema Properties

| Property                        | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                                                                                      |
| :------------------------------ | -------- | -------- | -------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [co_payment](#co_payment)       | `string` | Required | cannot be null | [The Root Schema](quotes-properties-the-risk_objects-schema-the-items-schema-properties-the-coverages-schema-the-items-schema-properties-the-co_payment-schema.md "\#/properties/risk_objects/items/properties/coverages/items/properties/co_payment#/properties/risk_objects/items/properties/coverages/items/properties/co_payment")          |
| [excess](#excess)               | `string` | Required | cannot be null | [The Root Schema](quotes-properties-the-risk_objects-schema-the-items-schema-properties-the-coverages-schema-the-items-schema-properties-the-excess-schema.md "\#/properties/risk_objects/items/properties/coverages/items/properties/excess#/properties/risk_objects/items/properties/coverages/items/properties/excess")                      |
| [gross_premium](#gross_premium) | `string` | Required | cannot be null | [The Root Schema](quotes-properties-the-risk_objects-schema-the-items-schema-properties-the-coverages-schema-the-items-schema-properties-the-gross_premium-schema.md "\#/properties/risk_objects/items/properties/coverages/items/properties/gross_premium#/properties/risk_objects/items/properties/coverages/items/properties/gross_premium") |
| [limit](#limit)                 | `string` | Required | cannot be null | [The Root Schema](quotes-properties-the-risk_objects-schema-the-items-schema-properties-the-coverages-schema-the-items-schema-properties-the-limit-schema.md "\#/properties/risk_objects/items/properties/coverages/items/properties/limit#/properties/risk_objects/items/properties/coverages/items/properties/limit")                         |
| [type](#type)                   | `string` | Required | cannot be null | [The Root Schema](quotes-properties-the-risk_objects-schema-the-items-schema-properties-the-coverages-schema-the-items-schema-properties-the-type-schema.md "\#/properties/risk_objects/items/properties/coverages/items/properties/type#/properties/risk_objects/items/properties/coverages/items/properties/type")                            |

## co_payment

An explanation about the purpose of this instance.


`co_payment`

-   is required
-   Type: `string` ([The Co_payment Schema](quotes-properties-the-risk_objects-schema-the-items-schema-properties-the-coverages-schema-the-items-schema-properties-the-co_payment-schema.md))
-   cannot be null
-   defined in: [The Root Schema](quotes-properties-the-risk_objects-schema-the-items-schema-properties-the-coverages-schema-the-items-schema-properties-the-co_payment-schema.md "\#/properties/risk_objects/items/properties/coverages/items/properties/co_payment#/properties/risk_objects/items/properties/coverages/items/properties/co_payment")

### co_payment Type

`string` ([The Co_payment Schema](quotes-properties-the-risk_objects-schema-the-items-schema-properties-the-coverages-schema-the-items-schema-properties-the-co_payment-schema.md))

### co_payment Examples

```json
"0.00000"
```

## excess

An explanation about the purpose of this instance.


`excess`

-   is required
-   Type: `string` ([The Excess Schema](quotes-properties-the-risk_objects-schema-the-items-schema-properties-the-coverages-schema-the-items-schema-properties-the-excess-schema.md))
-   cannot be null
-   defined in: [The Root Schema](quotes-properties-the-risk_objects-schema-the-items-schema-properties-the-coverages-schema-the-items-schema-properties-the-excess-schema.md "\#/properties/risk_objects/items/properties/coverages/items/properties/excess#/properties/risk_objects/items/properties/coverages/items/properties/excess")

### excess Type

`string` ([The Excess Schema](quotes-properties-the-risk_objects-schema-the-items-schema-properties-the-coverages-schema-the-items-schema-properties-the-excess-schema.md))

### excess Examples

```json
"0.00000"
```

## gross_premium

An explanation about the purpose of this instance.


`gross_premium`

-   is required
-   Type: `string` ([The Gross_premium Schema](quotes-properties-the-risk_objects-schema-the-items-schema-properties-the-coverages-schema-the-items-schema-properties-the-gross_premium-schema.md))
-   cannot be null
-   defined in: [The Root Schema](quotes-properties-the-risk_objects-schema-the-items-schema-properties-the-coverages-schema-the-items-schema-properties-the-gross_premium-schema.md "\#/properties/risk_objects/items/properties/coverages/items/properties/gross_premium#/properties/risk_objects/items/properties/coverages/items/properties/gross_premium")

### gross_premium Type

`string` ([The Gross_premium Schema](quotes-properties-the-risk_objects-schema-the-items-schema-properties-the-coverages-schema-the-items-schema-properties-the-gross_premium-schema.md))

### gross_premium Examples

```json
"1.33929"
```

## limit

An explanation about the purpose of this instance.


`limit`

-   is required
-   Type: `string` ([The Limit Schema](quotes-properties-the-risk_objects-schema-the-items-schema-properties-the-coverages-schema-the-items-schema-properties-the-limit-schema.md))
-   cannot be null
-   defined in: [The Root Schema](quotes-properties-the-risk_objects-schema-the-items-schema-properties-the-coverages-schema-the-items-schema-properties-the-limit-schema.md "\#/properties/risk_objects/items/properties/coverages/items/properties/limit#/properties/risk_objects/items/properties/coverages/items/properties/limit")

### limit Type

`string` ([The Limit Schema](quotes-properties-the-risk_objects-schema-the-items-schema-properties-the-coverages-schema-the-items-schema-properties-the-limit-schema.md))

### limit Examples

```json
"1.00000"
```

## type

An explanation about the purpose of this instance.


`type`

-   is required
-   Type: `string` ([The Type Schema](quotes-properties-the-risk_objects-schema-the-items-schema-properties-the-coverages-schema-the-items-schema-properties-the-type-schema.md))
-   cannot be null
-   defined in: [The Root Schema](quotes-properties-the-risk_objects-schema-the-items-schema-properties-the-coverages-schema-the-items-schema-properties-the-type-schema.md "\#/properties/risk_objects/items/properties/coverages/items/properties/type#/properties/risk_objects/items/properties/coverages/items/properties/type")

### type Type

`string` ([The Type Schema](quotes-properties-the-risk_objects-schema-the-items-schema-properties-the-coverages-schema-the-items-schema-properties-the-type-schema.md))

### type Examples

```json
"driver_injury"
```
