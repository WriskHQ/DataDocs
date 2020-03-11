# The Items Schema Schema

```txt
#/properties/risk_objects/items#/properties/risk_objects/items
```

An explanation about the purpose of this instance.


| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                  |
| :------------------ | ---------- | -------------- | ------------ | :---------------- | --------------------- | ------------------- | --------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [quotes.schema.json\*](../../out/quotes.schema.json "open original schema") |

## items Type

`object` ([The Items Schema](quotes-properties-the-risk_objects-schema-the-items-schema.md))

## items Default Value

The default value is:

```json
{}
```

## items Examples

```json
{
  "risk_object_id": "itm-hjTr3odd2mUXjqe7",
  "other_attributes": [],
  "attributes": [
    {
      "name": "LegalOwner",
      "value": "PolicyHolder"
    },
    {
      "name": "RegisteredKeeper",
      "value": "PolicyHolder"
    },
    {
      "name": "VehicleAge",
      "value": "14"
    },
    {
      "name": "VehicleFuel",
      "value": "Petrol"
    },
    {
      "name": "VehicleInsuranceGroup",
      "value": "7"
    },
    {
      "name": "VehicleModifications",
      "value": "false"
    },
    {
      "name": "VehicleNumberOfSeats",
      "value": ""
    },
    {
      "name": "VehicleSteering",
      "value": "RHD"
    },
    {
      "name": "VehicleTransmission",
      "value": "Manual"
    },
    {
      "name": "VehicleValue",
      "value": "1350.0"
    },
    {
      "name": "ABI Code",
      "value": ""
    },
    {
      "name": "Make",
      "value": "Vauxhall"
    },
    {
      "name": "Model",
      "value": "Corsa"
    },
    {
      "name": "Variant",
      "value": ""
    },
    {
      "name": "Year",
      "value": "2006"
    },
    {
      "name": "Overnight Location",
      "value": "Driveway"
    }
  ],
  "coverages": [
    {
      "type": "driver_injury",
      "gross_premium": "1.33929",
      "co_payment": "0.00000",
      "excess": "0.00000",
      "limit": "1.00000"
    },
    {
      "co_payment": "0.00000",
      "excess": "0.00000",
      "limit": "1.00000",
      "type": "accessories",
      "gross_premium": "0.89286"
    },
    {
      "co_payment": "0.00000",
      "excess": "0.00000",
      "limit": "1.00000",
      "type": "misfuelling",
      "gross_premium": "1.11607"
    },
    {
      "co_payment": "0.00000",
      "excess": "600.00000",
      "limit": "1.00000",
      "type": "foreign_travel",
      "gross_premium": "2.23214"
    },
    {
      "gross_premium": "1.07143",
      "co_payment": "0.00000",
      "excess": "0.00000",
      "limit": "1.00000",
      "type": "backup_ride"
    },
    {
      "type": "damage_to_car",
      "gross_premium": "13.38367",
      "co_payment": "0.00000",
      "excess": "600.00000",
      "limit": "1.00000"
    }
  ],
  "discounts": []
}
```

# The Items Schema Properties

| Property                              | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                        |
| :------------------------------------ | -------- | -------- | -------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [attributes](#attributes)             | `array`  | Required | cannot be null | [The Root Schema](quotes-properties-the-risk_objects-schema-the-items-schema-properties-the-attributes-schema.md "\#/properties/risk_objects/items/properties/attributes#/properties/risk_objects/items/properties/attributes")                   |
| [coverages](#coverages)               | `array`  | Required | cannot be null | [The Root Schema](quotes-properties-the-risk_objects-schema-the-items-schema-properties-the-coverages-schema.md "\#/properties/risk_objects/items/properties/coverages#/properties/risk_objects/items/properties/coverages")                      |
| [discounts](#discounts)               | `array`  | Required | cannot be null | [The Root Schema](quotes-properties-the-risk_objects-schema-the-items-schema-properties-the-discounts-schema.md "\#/properties/risk_objects/items/properties/discounts#/properties/risk_objects/items/properties/discounts")                      |
| [other_attributes](#other_attributes) | `array`  | Required | cannot be null | [The Root Schema](quotes-properties-the-risk_objects-schema-the-items-schema-properties-the-other_attributes-schema.md "\#/properties/risk_objects/items/properties/other_attributes#/properties/risk_objects/items/properties/other_attributes") |
| [risk_object_id](#risk_object_id)     | `string` | Required | cannot be null | [The Root Schema](quotes-properties-the-risk_objects-schema-the-items-schema-properties-the-risk_object_id-schema.md "\#/properties/risk_objects/items/properties/risk_object_id#/properties/risk_objects/items/properties/risk_object_id")       |

## attributes

An explanation about the purpose of this instance.


`attributes`

-   is required
-   Type: `object[]` ([The Items Schema](quotes-properties-the-risk_objects-schema-the-items-schema-properties-the-attributes-schema-the-items-schema.md))
-   cannot be null
-   defined in: [The Root Schema](quotes-properties-the-risk_objects-schema-the-items-schema-properties-the-attributes-schema.md "\#/properties/risk_objects/items/properties/attributes#/properties/risk_objects/items/properties/attributes")

### attributes Type

`object[]` ([The Items Schema](quotes-properties-the-risk_objects-schema-the-items-schema-properties-the-attributes-schema-the-items-schema.md))

### attributes Default Value

The default value is:

```json
[]
```

## coverages

An explanation about the purpose of this instance.


`coverages`

-   is required
-   Type: `object[]` ([The Items Schema](quotes-properties-the-risk_objects-schema-the-items-schema-properties-the-coverages-schema-the-items-schema.md))
-   cannot be null
-   defined in: [The Root Schema](quotes-properties-the-risk_objects-schema-the-items-schema-properties-the-coverages-schema.md "\#/properties/risk_objects/items/properties/coverages#/properties/risk_objects/items/properties/coverages")

### coverages Type

`object[]` ([The Items Schema](quotes-properties-the-risk_objects-schema-the-items-schema-properties-the-coverages-schema-the-items-schema.md))

### coverages Default Value

The default value is:

```json
[]
```

## discounts

An explanation about the purpose of this instance.


`discounts`

-   is required
-   Type: `array` ([The Discounts Schema](quotes-properties-the-risk_objects-schema-the-items-schema-properties-the-discounts-schema.md))
-   cannot be null
-   defined in: [The Root Schema](quotes-properties-the-risk_objects-schema-the-items-schema-properties-the-discounts-schema.md "\#/properties/risk_objects/items/properties/discounts#/properties/risk_objects/items/properties/discounts")

### discounts Type

`array` ([The Discounts Schema](quotes-properties-the-risk_objects-schema-the-items-schema-properties-the-discounts-schema.md))

### discounts Default Value

The default value is:

```json
[]
```

## other_attributes

An explanation about the purpose of this instance.


`other_attributes`

-   is required
-   Type: `array` ([The Other_attributes Schema](quotes-properties-the-risk_objects-schema-the-items-schema-properties-the-other_attributes-schema.md))
-   cannot be null
-   defined in: [The Root Schema](quotes-properties-the-risk_objects-schema-the-items-schema-properties-the-other_attributes-schema.md "\#/properties/risk_objects/items/properties/other_attributes#/properties/risk_objects/items/properties/other_attributes")

### other_attributes Type

`array` ([The Other_attributes Schema](quotes-properties-the-risk_objects-schema-the-items-schema-properties-the-other_attributes-schema.md))

### other_attributes Default Value

The default value is:

```json
[]
```

## risk_object_id

An explanation about the purpose of this instance.


`risk_object_id`

-   is required
-   Type: `string` ([The Risk_object_id Schema](quotes-properties-the-risk_objects-schema-the-items-schema-properties-the-risk_object_id-schema.md))
-   cannot be null
-   defined in: [The Root Schema](quotes-properties-the-risk_objects-schema-the-items-schema-properties-the-risk_object_id-schema.md "\#/properties/risk_objects/items/properties/risk_object_id#/properties/risk_objects/items/properties/risk_object_id")

### risk_object_id Type

`string` ([The Risk_object_id Schema](quotes-properties-the-risk_objects-schema-the-items-schema-properties-the-risk_object_id-schema.md))

### risk_object_id Examples

```json
"itm-hjTr3odd2mUXjqe7"
```
