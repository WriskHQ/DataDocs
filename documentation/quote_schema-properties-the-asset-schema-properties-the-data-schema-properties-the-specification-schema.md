# The Specification Schema Schema

```txt
#/properties/asset/properties/data/properties/specification#/properties/asset/properties/data/properties/specification
```

An explanation about the purpose of this instance.


| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                           |
| :------------------ | ---------- | -------------- | ------------ | :---------------- | --------------------- | ------------------- | ------------------------------------------------------------------------------------ |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [quote_schema.schema.json\*](../out/quote_schema.schema.json "open original schema") |

## specification Type

`object` ([The Specification Schema](quote_schema-properties-the-asset-schema-properties-the-data-schema-properties-the-specification-schema.md))

## specification Default Value

The default value is:

```json
{}
```

## specification Examples

```json
{
  "insuranceGroup": 32,
  "transmission": "AUTOMATIC",
  "numberOfSeats": 5,
  "licencePlate": "DG18 MFK",
  "model": "X2",
  "year": 2018,
  "value": 31550,
  "make": "BMW",
  "fuel": "DIESEL",
  "steering": "RHD"
}
```

# The Specification Schema Properties

| Property                          | Type      | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                                                                                       |
| :-------------------------------- | --------- | -------- | -------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [fuel](#fuel)                     | `string`  | Required | cannot be null | [The Root Schema](quote_schema-properties-the-asset-schema-properties-the-data-schema-properties-the-specification-schema-properties-the-fuel-schema.md "\#/properties/asset/properties/data/properties/specification/properties/fuel#/properties/asset/properties/data/properties/specification/properties/fuel")                               |
| [make](#make)                     | `string`  | Required | cannot be null | [The Root Schema](quote_schema-properties-the-asset-schema-properties-the-data-schema-properties-the-specification-schema-properties-the-make-schema.md "\#/properties/asset/properties/data/properties/specification/properties/make#/properties/asset/properties/data/properties/specification/properties/make")                               |
| [year](#year)                     | `integer` | Required | cannot be null | [The Root Schema](quote_schema-properties-the-asset-schema-properties-the-data-schema-properties-the-specification-schema-properties-the-year-schema.md "\#/properties/asset/properties/data/properties/specification/properties/year#/properties/asset/properties/data/properties/specification/properties/year")                               |
| [model](#model)                   | `string`  | Required | cannot be null | [The Root Schema](quote_schema-properties-the-asset-schema-properties-the-data-schema-properties-the-specification-schema-properties-the-model-schema.md "\#/properties/asset/properties/data/properties/specification/properties/model#/properties/asset/properties/data/properties/specification/properties/model")                            |
| [value](#value)                   | `integer` | Required | cannot be null | [The Root Schema](quote_schema-properties-the-asset-schema-properties-the-data-schema-properties-the-specification-schema-properties-the-value-schema.md "\#/properties/asset/properties/data/properties/specification/properties/value#/properties/asset/properties/data/properties/specification/properties/value")                            |
| [steering](#steering)             | `string`  | Required | cannot be null | [The Root Schema](quote_schema-properties-the-asset-schema-properties-the-data-schema-properties-the-specification-schema-properties-the-steering-schema.md "\#/properties/asset/properties/data/properties/specification/properties/steering#/properties/asset/properties/data/properties/specification/properties/steering")                   |
| [licencePlate](#licencePlate)     | `string`  | Required | cannot be null | [The Root Schema](quote_schema-properties-the-asset-schema-properties-the-data-schema-properties-the-specification-schema-properties-the-licenceplate-schema.md "\#/properties/asset/properties/data/properties/specification/properties/licencePlate#/properties/asset/properties/data/properties/specification/properties/licencePlate")       |
| [transmission](#transmission)     | `string`  | Required | cannot be null | [The Root Schema](quote_schema-properties-the-asset-schema-properties-the-data-schema-properties-the-specification-schema-properties-the-transmission-schema.md "\#/properties/asset/properties/data/properties/specification/properties/transmission#/properties/asset/properties/data/properties/specification/properties/transmission")       |
| [numberOfSeats](#numberOfSeats)   | `integer` | Required | cannot be null | [The Root Schema](quote_schema-properties-the-asset-schema-properties-the-data-schema-properties-the-specification-schema-properties-the-numberofseats-schema.md "\#/properties/asset/properties/data/properties/specification/properties/numberOfSeats#/properties/asset/properties/data/properties/specification/properties/numberOfSeats")    |
| [insuranceGroup](#insuranceGroup) | `integer` | Required | cannot be null | [The Root Schema](quote_schema-properties-the-asset-schema-properties-the-data-schema-properties-the-specification-schema-properties-the-insurancegroup-schema.md "\#/properties/asset/properties/data/properties/specification/properties/insuranceGroup#/properties/asset/properties/data/properties/specification/properties/insuranceGroup") |

## fuel

An explanation about the purpose of this instance.


`fuel`

-   is required
-   Type: `string` ([The Fuel Schema](quote_schema-properties-the-asset-schema-properties-the-data-schema-properties-the-specification-schema-properties-the-fuel-schema.md))
-   cannot be null
-   defined in: [The Root Schema](quote_schema-properties-the-asset-schema-properties-the-data-schema-properties-the-specification-schema-properties-the-fuel-schema.md "\#/properties/asset/properties/data/properties/specification/properties/fuel#/properties/asset/properties/data/properties/specification/properties/fuel")

### fuel Type

`string` ([The Fuel Schema](quote_schema-properties-the-asset-schema-properties-the-data-schema-properties-the-specification-schema-properties-the-fuel-schema.md))

### fuel Examples

```json
"DIESEL"
```

## make

An explanation about the purpose of this instance.


`make`

-   is required
-   Type: `string` ([The Make Schema](quote_schema-properties-the-asset-schema-properties-the-data-schema-properties-the-specification-schema-properties-the-make-schema.md))
-   cannot be null
-   defined in: [The Root Schema](quote_schema-properties-the-asset-schema-properties-the-data-schema-properties-the-specification-schema-properties-the-make-schema.md "\#/properties/asset/properties/data/properties/specification/properties/make#/properties/asset/properties/data/properties/specification/properties/make")

### make Type

`string` ([The Make Schema](quote_schema-properties-the-asset-schema-properties-the-data-schema-properties-the-specification-schema-properties-the-make-schema.md))

### make Examples

```json
"BMW"
```

## year

An explanation about the purpose of this instance.


`year`

-   is required
-   Type: `integer` ([The Year Schema](quote_schema-properties-the-asset-schema-properties-the-data-schema-properties-the-specification-schema-properties-the-year-schema.md))
-   cannot be null
-   defined in: [The Root Schema](quote_schema-properties-the-asset-schema-properties-the-data-schema-properties-the-specification-schema-properties-the-year-schema.md "\#/properties/asset/properties/data/properties/specification/properties/year#/properties/asset/properties/data/properties/specification/properties/year")

### year Type

`integer` ([The Year Schema](quote_schema-properties-the-asset-schema-properties-the-data-schema-properties-the-specification-schema-properties-the-year-schema.md))

### year Examples

```json
2018
```

## model

An explanation about the purpose of this instance.


`model`

-   is required
-   Type: `string` ([The Model Schema](quote_schema-properties-the-asset-schema-properties-the-data-schema-properties-the-specification-schema-properties-the-model-schema.md))
-   cannot be null
-   defined in: [The Root Schema](quote_schema-properties-the-asset-schema-properties-the-data-schema-properties-the-specification-schema-properties-the-model-schema.md "\#/properties/asset/properties/data/properties/specification/properties/model#/properties/asset/properties/data/properties/specification/properties/model")

### model Type

`string` ([The Model Schema](quote_schema-properties-the-asset-schema-properties-the-data-schema-properties-the-specification-schema-properties-the-model-schema.md))

### model Examples

```json
"X2"
```

## value

An explanation about the purpose of this instance.


`value`

-   is required
-   Type: `integer` ([The Value Schema](quote_schema-properties-the-asset-schema-properties-the-data-schema-properties-the-specification-schema-properties-the-value-schema.md))
-   cannot be null
-   defined in: [The Root Schema](quote_schema-properties-the-asset-schema-properties-the-data-schema-properties-the-specification-schema-properties-the-value-schema.md "\#/properties/asset/properties/data/properties/specification/properties/value#/properties/asset/properties/data/properties/specification/properties/value")

### value Type

`integer` ([The Value Schema](quote_schema-properties-the-asset-schema-properties-the-data-schema-properties-the-specification-schema-properties-the-value-schema.md))

### value Examples

```json
31550
```

## steering

An explanation about the purpose of this instance.


`steering`

-   is required
-   Type: `string` ([The Steering Schema](quote_schema-properties-the-asset-schema-properties-the-data-schema-properties-the-specification-schema-properties-the-steering-schema.md))
-   cannot be null
-   defined in: [The Root Schema](quote_schema-properties-the-asset-schema-properties-the-data-schema-properties-the-specification-schema-properties-the-steering-schema.md "\#/properties/asset/properties/data/properties/specification/properties/steering#/properties/asset/properties/data/properties/specification/properties/steering")

### steering Type

`string` ([The Steering Schema](quote_schema-properties-the-asset-schema-properties-the-data-schema-properties-the-specification-schema-properties-the-steering-schema.md))

### steering Examples

```json
"RHD"
```

## licencePlate

An explanation about the purpose of this instance.


`licencePlate`

-   is required
-   Type: `string` ([The Licenceplate Schema](quote_schema-properties-the-asset-schema-properties-the-data-schema-properties-the-specification-schema-properties-the-licenceplate-schema.md))
-   cannot be null
-   defined in: [The Root Schema](quote_schema-properties-the-asset-schema-properties-the-data-schema-properties-the-specification-schema-properties-the-licenceplate-schema.md "\#/properties/asset/properties/data/properties/specification/properties/licencePlate#/properties/asset/properties/data/properties/specification/properties/licencePlate")

### licencePlate Type

`string` ([The Licenceplate Schema](quote_schema-properties-the-asset-schema-properties-the-data-schema-properties-the-specification-schema-properties-the-licenceplate-schema.md))

### licencePlate Examples

```json
"DG18 MFK"
```

## transmission

An explanation about the purpose of this instance.


`transmission`

-   is required
-   Type: `string` ([The Transmission Schema](quote_schema-properties-the-asset-schema-properties-the-data-schema-properties-the-specification-schema-properties-the-transmission-schema.md))
-   cannot be null
-   defined in: [The Root Schema](quote_schema-properties-the-asset-schema-properties-the-data-schema-properties-the-specification-schema-properties-the-transmission-schema.md "\#/properties/asset/properties/data/properties/specification/properties/transmission#/properties/asset/properties/data/properties/specification/properties/transmission")

### transmission Type

`string` ([The Transmission Schema](quote_schema-properties-the-asset-schema-properties-the-data-schema-properties-the-specification-schema-properties-the-transmission-schema.md))

### transmission Examples

```json
"AUTOMATIC"
```

## numberOfSeats

An explanation about the purpose of this instance.


`numberOfSeats`

-   is required
-   Type: `integer` ([The Numberofseats Schema](quote_schema-properties-the-asset-schema-properties-the-data-schema-properties-the-specification-schema-properties-the-numberofseats-schema.md))
-   cannot be null
-   defined in: [The Root Schema](quote_schema-properties-the-asset-schema-properties-the-data-schema-properties-the-specification-schema-properties-the-numberofseats-schema.md "\#/properties/asset/properties/data/properties/specification/properties/numberOfSeats#/properties/asset/properties/data/properties/specification/properties/numberOfSeats")

### numberOfSeats Type

`integer` ([The Numberofseats Schema](quote_schema-properties-the-asset-schema-properties-the-data-schema-properties-the-specification-schema-properties-the-numberofseats-schema.md))

### numberOfSeats Examples

```json
5
```

## insuranceGroup

An explanation about the purpose of this instance.


`insuranceGroup`

-   is required
-   Type: `integer` ([The Insurancegroup Schema](quote_schema-properties-the-asset-schema-properties-the-data-schema-properties-the-specification-schema-properties-the-insurancegroup-schema.md))
-   cannot be null
-   defined in: [The Root Schema](quote_schema-properties-the-asset-schema-properties-the-data-schema-properties-the-specification-schema-properties-the-insurancegroup-schema.md "\#/properties/asset/properties/data/properties/specification/properties/insuranceGroup#/properties/asset/properties/data/properties/specification/properties/insuranceGroup")

### insuranceGroup Type

`integer` ([The Insurancegroup Schema](quote_schema-properties-the-asset-schema-properties-the-data-schema-properties-the-specification-schema-properties-the-insurancegroup-schema.md))

### insuranceGroup Examples

```json
32
```
