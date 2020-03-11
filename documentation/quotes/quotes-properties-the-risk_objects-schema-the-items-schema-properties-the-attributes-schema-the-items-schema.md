# The Items Schema Schema

```txt
#/properties/risk_objects/items/properties/attributes/items#/properties/risk_objects/items/properties/attributes/items
```

An explanation about the purpose of this instance.


| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                  |
| :------------------ | ---------- | -------------- | ------------ | :---------------- | --------------------- | ------------------- | --------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [quotes.schema.json\*](../../out/quotes.schema.json "open original schema") |

## items Type

`object` ([The Items Schema](quotes-properties-the-risk_objects-schema-the-items-schema-properties-the-attributes-schema-the-items-schema.md))

## items Default Value

The default value is:

```json
{}
```

## items Examples

```json
{
  "name": "LegalOwner",
  "value": "PolicyHolder"
}
```

```json
{
  "name": "RegisteredKeeper",
  "value": "PolicyHolder"
}
```

```json
{
  "name": "VehicleAge",
  "value": "14"
}
```

```json
{
  "name": "VehicleFuel",
  "value": "Petrol"
}
```

```json
{
  "name": "VehicleInsuranceGroup",
  "value": "7"
}
```

```json
{
  "name": "VehicleModifications",
  "value": "false"
}
```

```json
{
  "name": "VehicleNumberOfSeats",
  "value": ""
}
```

```json
{
  "name": "VehicleSteering",
  "value": "RHD"
}
```

```json
{
  "name": "VehicleTransmission",
  "value": "Manual"
}
```

```json
{
  "name": "VehicleValue",
  "value": "1350.0"
}
```

```json
{
  "name": "ABI Code",
  "value": ""
}
```

```json
{
  "name": "Make",
  "value": "Vauxhall"
}
```

```json
{
  "name": "Model",
  "value": "Corsa"
}
```

```json
{
  "name": "Variant",
  "value": ""
}
```

```json
{
  "name": "Year",
  "value": "2006"
}
```

```json
{
  "name": "Overnight Location",
  "value": "Driveway"
}
```

# The Items Schema Properties

| Property        | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                                                                 |
| :-------------- | -------- | -------- | -------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [name](#name)   | `string` | Required | cannot be null | [The Root Schema](quotes-properties-the-risk_objects-schema-the-items-schema-properties-the-attributes-schema-the-items-schema-properties-the-name-schema.md "\#/properties/risk_objects/items/properties/attributes/items/properties/name#/properties/risk_objects/items/properties/attributes/items/properties/name")    |
| [value](#value) | `string` | Required | cannot be null | [The Root Schema](quotes-properties-the-risk_objects-schema-the-items-schema-properties-the-attributes-schema-the-items-schema-properties-the-value-schema.md "\#/properties/risk_objects/items/properties/attributes/items/properties/value#/properties/risk_objects/items/properties/attributes/items/properties/value") |

## name

An explanation about the purpose of this instance.


`name`

-   is required
-   Type: `string` ([The Name Schema](quotes-properties-the-risk_objects-schema-the-items-schema-properties-the-attributes-schema-the-items-schema-properties-the-name-schema.md))
-   cannot be null
-   defined in: [The Root Schema](quotes-properties-the-risk_objects-schema-the-items-schema-properties-the-attributes-schema-the-items-schema-properties-the-name-schema.md "\#/properties/risk_objects/items/properties/attributes/items/properties/name#/properties/risk_objects/items/properties/attributes/items/properties/name")

### name Type

`string` ([The Name Schema](quotes-properties-the-risk_objects-schema-the-items-schema-properties-the-attributes-schema-the-items-schema-properties-the-name-schema.md))

### name Examples

```json
"LegalOwner"
```

## value

An explanation about the purpose of this instance.


`value`

-   is required
-   Type: `string` ([The Value Schema](quotes-properties-the-risk_objects-schema-the-items-schema-properties-the-attributes-schema-the-items-schema-properties-the-value-schema.md))
-   cannot be null
-   defined in: [The Root Schema](quotes-properties-the-risk_objects-schema-the-items-schema-properties-the-attributes-schema-the-items-schema-properties-the-value-schema.md "\#/properties/risk_objects/items/properties/attributes/items/properties/value#/properties/risk_objects/items/properties/attributes/items/properties/value")

### value Type

`string` ([The Value Schema](quotes-properties-the-risk_objects-schema-the-items-schema-properties-the-attributes-schema-the-items-schema-properties-the-value-schema.md))

### value Examples

```json
"PolicyHolder"
```
