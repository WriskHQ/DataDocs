# The Root Schema Schema

```txt
http://example.com/example.json
```

The root schema comprises the entire JSON document.


| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                |
| :------------------ | ---------- | -------------- | ------------ | :---------------- | --------------------- | ------------------- | ------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [quotes.schema.json](../../out/quotes.schema.json "open original schema") |

## The Root Schema Type

`object` ([The Root Schema](quotes.md))

# The Root Schema Properties

| Property                                  | Type     | Required | Nullable       | Defined by                                                                                                                              |
| :---------------------------------------- | -------- | -------- | -------------- | :-------------------------------------------------------------------------------------------------------------------------------------- |
| [attributes](#attributes)                 | `array`  | Required | cannot be null | [The Root Schema](quotes-properties-the-attributes-schema.md "\#/properties/attributes#/properties/attributes")                         |
| [class_of_business](#class_of_business)   | `string` | Required | cannot be null | [The Root Schema](quotes-properties-the-class_of_business-schema.md "\#/properties/class_of_business#/properties/class_of_business")    |
| [currency](#currency)                     | `string` | Required | cannot be null | [The Root Schema](quotes-properties-the-currency-schema.md "\#/properties/currency#/properties/currency")                               |
| [gross_premium](#gross_premium)           | `string` | Required | cannot be null | [The Root Schema](quotes-properties-the-gross_premium-schema.md "\#/properties/gross_premium#/properties/gross_premium")                |
| [net_premium](#net_premium)               | `string` | Required | cannot be null | [The Root Schema](quotes-properties-the-net_premium-schema.md "\#/properties/net_premium#/properties/net_premium")                      |
| [other_attributes](#other_attributes)     | `array`  | Required | cannot be null | [The Root Schema](quotes-properties-the-other_attributes-schema.md "\#/properties/other_attributes#/properties/other_attributes")       |
| [partner_name](#partner_name)             | `string` | Required | cannot be null | [The Root Schema](quotes-properties-the-partner_name-schema.md "\#/properties/partner_name#/properties/partner_name")                   |
| [payment_frequency](#payment_frequency)   | `string` | Required | cannot be null | [The Root Schema](quotes-properties-the-payment_frequency-schema.md "\#/properties/payment_frequency#/properties/payment_frequency")    |
| [policy_expiry](#policy_expiry)           | `string` | Required | cannot be null | [The Root Schema](quotes-properties-the-policy_expiry-schema.md "\#/properties/policy_expiry#/properties/policy_expiry")                |
| [policy_id](#policy_id)                   | `string` | Required | cannot be null | [The Root Schema](quotes-properties-the-policy_id-schema.md "\#/properties/policy_id#/properties/policy_id")                            |
| [policy_inception](#policy_inception)     | `string` | Required | cannot be null | [The Root Schema](quotes-properties-the-policy_inception-schema.md "\#/properties/policy_inception#/properties/policy_inception")       |
| [product_id](#product_id)                 | `string` | Required | cannot be null | [The Root Schema](quotes-properties-the-product_id-schema.md "\#/properties/product_id#/properties/product_id")                         |
| [product_name](#product_name)             | `string` | Required | cannot be null | [The Root Schema](quotes-properties-the-product_name-schema.md "\#/properties/product_name#/properties/product_name")                   |
| [quote_id](#quote_id)                     | `string` | Required | cannot be null | [The Root Schema](quotes-properties-the-quote_id-schema.md "\#/properties/quote_id#/properties/quote_id")                               |
| [risk_objects](#risk_objects)             | `array`  | Required | cannot be null | [The Root Schema](quotes-properties-the-risk_objects-schema.md "\#/properties/risk_objects#/properties/risk_objects")                   |
| [status](#status)                         | `string` | Required | cannot be null | [The Root Schema](quotes-properties-the-status-schema.md "\#/properties/status#/properties/status")                                     |
| [total_commissions](#total_commissions)   | `string` | Required | cannot be null | [The Root Schema](quotes-properties-the-total_commissions-schema.md "\#/properties/total_commissions#/properties/total_commissions")    |
| [total_premium](#total_premium)           | `string` | Required | cannot be null | [The Root Schema](quotes-properties-the-total_premium-schema.md "\#/properties/total_premium#/properties/total_premium")                |
| [total_taxes](#total_taxes)               | `string` | Required | cannot be null | [The Root Schema](quotes-properties-the-total_taxes-schema.md "\#/properties/total_taxes#/properties/total_taxes")                      |
| [transaction_stored](#transaction_stored) | `string` | Required | cannot be null | [The Root Schema](quotes-properties-the-transaction_stored-schema.md "\#/properties/transaction_stored#/properties/transaction_stored") |

## attributes

An explanation about the purpose of this instance.


`attributes`

-   is required
-   Type: `object[]` ([The Items Schema](quotes-properties-the-attributes-schema-the-items-schema.md))
-   cannot be null
-   defined in: [The Root Schema](quotes-properties-the-attributes-schema.md "\#/properties/attributes#/properties/attributes")

### attributes Type

`object[]` ([The Items Schema](quotes-properties-the-attributes-schema-the-items-schema.md))

### attributes Default Value

The default value is:

```json
[]
```

## class_of_business

An explanation about the purpose of this instance.


`class_of_business`

-   is required
-   Type: `string` ([The Class_of_business Schema](quotes-properties-the-class_of_business-schema.md))
-   cannot be null
-   defined in: [The Root Schema](quotes-properties-the-class_of_business-schema.md "\#/properties/class_of_business#/properties/class_of_business")

### class_of_business Type

`string` ([The Class_of_business Schema](quotes-properties-the-class_of_business-schema.md))

### class_of_business Examples

```json
"Motor"
```

## currency

An explanation about the purpose of this instance.


`currency`

-   is required
-   Type: `string` ([The Currency Schema](quotes-properties-the-currency-schema.md))
-   cannot be null
-   defined in: [The Root Schema](quotes-properties-the-currency-schema.md "\#/properties/currency#/properties/currency")

### currency Type

`string` ([The Currency Schema](quotes-properties-the-currency-schema.md))

### currency Examples

```json
"GBP"
```

## gross_premium

An explanation about the purpose of this instance.


`gross_premium`

-   is required
-   Type: `string` ([The Gross_premium Schema](quotes-properties-the-gross_premium-schema.md))
-   cannot be null
-   defined in: [The Root Schema](quotes-properties-the-gross_premium-schema.md "\#/properties/gross_premium#/properties/gross_premium")

### gross_premium Type

`string` ([The Gross_premium Schema](quotes-properties-the-gross_premium-schema.md))

### gross_premium Examples

```json
"20.03546"
```

## net_premium

An explanation about the purpose of this instance.


`net_premium`

-   is required
-   Type: `string` ([The Net_premium Schema](quotes-properties-the-net_premium-schema.md))
-   cannot be null
-   defined in: [The Root Schema](quotes-properties-the-net_premium-schema.md "\#/properties/net_premium#/properties/net_premium")

### net_premium Type

`string` ([The Net_premium Schema](quotes-properties-the-net_premium-schema.md))

### net_premium Examples

```json
"20.03546"
```

## other_attributes

An explanation about the purpose of this instance.


`other_attributes`

-   is required
-   Type: `array` ([The Other_attributes Schema](quotes-properties-the-other_attributes-schema.md))
-   cannot be null
-   defined in: [The Root Schema](quotes-properties-the-other_attributes-schema.md "\#/properties/other_attributes#/properties/other_attributes")

### other_attributes Type

`array` ([The Other_attributes Schema](quotes-properties-the-other_attributes-schema.md))

### other_attributes Default Value

The default value is:

```json
[]
```

## partner_name

An explanation about the purpose of this instance.


`partner_name`

-   is required
-   Type: `string` ([The Partner_name Schema](quotes-properties-the-partner_name-schema.md))
-   cannot be null
-   defined in: [The Root Schema](quotes-properties-the-partner_name-schema.md "\#/properties/partner_name#/properties/partner_name")

### partner_name Type

`string` ([The Partner_name Schema](quotes-properties-the-partner_name-schema.md))

### partner_name Examples

```json
"WRISK"
```

## payment_frequency

An explanation about the purpose of this instance.


`payment_frequency`

-   is required
-   Type: `string` ([The Payment_frequency Schema](quotes-properties-the-payment_frequency-schema.md))
-   cannot be null
-   defined in: [The Root Schema](quotes-properties-the-payment_frequency-schema.md "\#/properties/payment_frequency#/properties/payment_frequency")

### payment_frequency Type

`string` ([The Payment_frequency Schema](quotes-properties-the-payment_frequency-schema.md))

### payment_frequency Examples

```json
"MONTHLY"
```

## policy_expiry

An explanation about the purpose of this instance.


`policy_expiry`

-   is required
-   Type: `string` ([The Policy_expiry Schema](quotes-properties-the-policy_expiry-schema.md))
-   cannot be null
-   defined in: [The Root Schema](quotes-properties-the-policy_expiry-schema.md "\#/properties/policy_expiry#/properties/policy_expiry")

### policy_expiry Type

`string` ([The Policy_expiry Schema](quotes-properties-the-policy_expiry-schema.md))

### policy_expiry Examples

```json
"2070-03-11T11:16:56Z"
```

## policy_id

An explanation about the purpose of this instance.


`policy_id`

-   is required
-   Type: `string` ([The Policy_id Schema](quotes-properties-the-policy_id-schema.md))
-   cannot be null
-   defined in: [The Root Schema](quotes-properties-the-policy_id-schema.md "\#/properties/policy_id#/properties/policy_id")

### policy_id Type

`string` ([The Policy_id Schema](quotes-properties-the-policy_id-schema.md))

### policy_id Examples

```json
"pcy-pv34TjV2zwjXOkzD"
```

## policy_inception

An explanation about the purpose of this instance.


`policy_inception`

-   is required
-   Type: `string` ([The Policy_inception Schema](quotes-properties-the-policy_inception-schema.md))
-   cannot be null
-   defined in: [The Root Schema](quotes-properties-the-policy_inception-schema.md "\#/properties/policy_inception#/properties/policy_inception")

### policy_inception Type

`string` ([The Policy_inception Schema](quotes-properties-the-policy_inception-schema.md))

### policy_inception Examples

```json
"2020-03-11T11:16:56Z"
```

## product_id

An explanation about the purpose of this instance.


`product_id`

-   is required
-   Type: `string` ([The Product_id Schema](quotes-properties-the-product_id-schema.md))
-   cannot be null
-   defined in: [The Root Schema](quotes-properties-the-product_id-schema.md "\#/properties/product_id#/properties/product_id")

### product_id Type

`string` ([The Product_id Schema](quotes-properties-the-product_id-schema.md))

### product_id Examples

```json
"RAC_PAYD"
```

## product_name

An explanation about the purpose of this instance.


`product_name`

-   is required
-   Type: `string` ([The Product_name Schema](quotes-properties-the-product_name-schema.md))
-   cannot be null
-   defined in: [The Root Schema](quotes-properties-the-product_name-schema.md "\#/properties/product_name#/properties/product_name")

### product_name Type

`string` ([The Product_name Schema](quotes-properties-the-product_name-schema.md))

### product_name Examples

```json
"Pay As You Drive"
```

## quote_id

An explanation about the purpose of this instance.


`quote_id`

-   is required
-   Type: `string` ([The Quote_id Schema](quotes-properties-the-quote_id-schema.md))
-   cannot be null
-   defined in: [The Root Schema](quotes-properties-the-quote_id-schema.md "\#/properties/quote_id#/properties/quote_id")

### quote_id Type

`string` ([The Quote_id Schema](quotes-properties-the-quote_id-schema.md))

### quote_id Examples

```json
"quo-1svCsu4WYnDEktOF"
```

## risk_objects

An explanation about the purpose of this instance.


`risk_objects`

-   is required
-   Type: `object[]` ([The Items Schema](quotes-properties-the-risk_objects-schema-the-items-schema.md))
-   cannot be null
-   defined in: [The Root Schema](quotes-properties-the-risk_objects-schema.md "\#/properties/risk_objects#/properties/risk_objects")

### risk_objects Type

`object[]` ([The Items Schema](quotes-properties-the-risk_objects-schema-the-items-schema.md))

### risk_objects Default Value

The default value is:

```json
[]
```

## status

An explanation about the purpose of this instance.


`status`

-   is required
-   Type: `string` ([The Status Schema](quotes-properties-the-status-schema.md))
-   cannot be null
-   defined in: [The Root Schema](quotes-properties-the-status-schema.md "\#/properties/status#/properties/status")

### status Type

`string` ([The Status Schema](quotes-properties-the-status-schema.md))

### status Examples

```json
"QUOTED"
```

## total_commissions

An explanation about the purpose of this instance.


`total_commissions`

-   is required
-   Type: `string` ([The Total_commissions Schema](quotes-properties-the-total_commissions-schema.md))
-   cannot be null
-   defined in: [The Root Schema](quotes-properties-the-total_commissions-schema.md "\#/properties/total_commissions#/properties/total_commissions")

### total_commissions Type

`string` ([The Total_commissions Schema](quotes-properties-the-total_commissions-schema.md))

### total_commissions Examples

```json
"0.00000"
```

## total_premium

An explanation about the purpose of this instance.


`total_premium`

-   is required
-   Type: `string` ([The Total_premium Schema](quotes-properties-the-total_premium-schema.md))
-   cannot be null
-   defined in: [The Root Schema](quotes-properties-the-total_premium-schema.md "\#/properties/total_premium#/properties/total_premium")

### total_premium Type

`string` ([The Total_premium Schema](quotes-properties-the-total_premium-schema.md))

### total_premium Examples

```json
"22.44000"
```

## total_taxes

An explanation about the purpose of this instance.


`total_taxes`

-   is required
-   Type: `string` ([The Total_taxes Schema](quotes-properties-the-total_taxes-schema.md))
-   cannot be null
-   defined in: [The Root Schema](quotes-properties-the-total_taxes-schema.md "\#/properties/total_taxes#/properties/total_taxes")

### total_taxes Type

`string` ([The Total_taxes Schema](quotes-properties-the-total_taxes-schema.md))

### total_taxes Examples

```json
"2.40454"
```

## transaction_stored

An explanation about the purpose of this instance.


`transaction_stored`

-   is required
-   Type: `string` ([The Transaction_stored Schema](quotes-properties-the-transaction_stored-schema.md))
-   cannot be null
-   defined in: [The Root Schema](quotes-properties-the-transaction_stored-schema.md "\#/properties/transaction_stored#/properties/transaction_stored")

### transaction_stored Type

`string` ([The Transaction_stored Schema](quotes-properties-the-transaction_stored-schema.md))

### transaction_stored Examples

```json
"2020-03-11T11:16:56Z"
```
