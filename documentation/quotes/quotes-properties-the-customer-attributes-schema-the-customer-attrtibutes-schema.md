# The Customer Attrtibutes Schema Schema

```txt
#/properties/attributes/items#/properties/attributes/items
```

A Key Value Store of specified attributes for the customer.


| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                  |
| :------------------ | ---------- | -------------- | ------------ | :---------------- | --------------------- | ------------------- | --------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [quotes.schema.json\*](../../out/quotes.schema.json "open original schema") |

## items Type

`object` ([The Customer Attrtibutes Schema](quotes-properties-the-customer-attributes-schema-the-customer-attrtibutes-schema.md))

## items Default Value

The default value is:

```json
{}
```

## items Examples

```json
{
  "name": "User ID",
  "value": "email|5db6d0aad6be3073e95c3fcf"
}
```

```json
{
  "name": "Postcode",
  "value": "CW2 6QU"
}
```

```json
{
  "name": "DateOfBirth",
  "value": "1981-01-01"
}
```

```json
{
  "name": "DrivingLicenceDate",
  "value": "2001-01-01"
}
```

```json
{
  "name": "AdvisedByDoctorNotToDrive",
  "value": "false"
}
```

```json
{
  "name": "Age",
  "value": "39"
}
```

```json
{
  "name": "AnnualMileage",
  "value": "9000"
}
```

```json
{
  "name": "AreaGroup",
  "value": "16"
}
```

```json
{
  "name": "AreaStoredTheftGroup",
  "value": "1"
}
```

```json
{
  "name": "Bankrupt",
  "value": "false"
}
```

```json
{
  "name": "ClaimsHistoryCount",
  "value": "0"
}
```

```json
{
  "name": "DrivingConvictionsCount",
  "value": "0"
}
```

```json
{
  "name": "DrivingLicenceType",
  "value": "FullGB"
}
```

```json
{
  "name": "DrivingLicenceYearsHeld",
  "value": "19"
}
```

```json
{
  "name": "DvlaUnawareOfMedicalCondition",
  "value": "false"
}
```

```json
{
  "name": "EmployerBusinessGroup",
  "value": ""
}
```

```json
{
  "name": "EmploymentStatus",
  "value": "RE"
}
```

```json
{
  "name": "HomeOwnership",
  "value": "Own"
}
```

```json
{
  "name": "MaritalStatus",
  "value": "Married"
}
```

```json
{
  "name": "NoClaimsDiscount",
  "value": "0"
}
```

```json
{
  "name": "OccupationGroup",
  "value": ""
}
```

```json
{
  "name": "OvernightLocation",
  "value": "Driveway"
}
```

```json
{
  "name": "PreviouslyRefusedInsurance",
  "value": "false"
}
```

```json
{
  "name": "UnsatisfiedCCJs",
  "value": "false"
}
```

```json
{
  "name": "UnspentCriminalConvictions",
  "value": "false"
}
```

```json
{
  "name": "Usage",
  "value": "SocialDomesticPleasure"
}
```

```json
{
  "name": "Premium per mile",
  "value": "0.06"
}
```

# The Customer Attrtibutes Schema Properties

| Property        | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                         |
| :-------------- | -------- | -------- | -------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [name](#name)   | `string` | Required | cannot be null | [The Root Schema](quotes-properties-the-customer-attributes-schema-the-customer-attrtibutes-schema-properties-the-name-schema.md "\#/properties/attributes/items/properties/name#/properties/attributes/items/properties/name")    |
| [value](#value) | `string` | Required | cannot be null | [The Root Schema](quotes-properties-the-customer-attributes-schema-the-customer-attrtibutes-schema-properties-the-value-schema.md "\#/properties/attributes/items/properties/value#/properties/attributes/items/properties/value") |

## name

The key for the given attribute.


`name`

-   is required
-   Type: `string` ([The Name Schema](quotes-properties-the-customer-attributes-schema-the-customer-attrtibutes-schema-properties-the-name-schema.md))
-   cannot be null
-   defined in: [The Root Schema](quotes-properties-the-customer-attributes-schema-the-customer-attrtibutes-schema-properties-the-name-schema.md "\#/properties/attributes/items/properties/name#/properties/attributes/items/properties/name")

### name Type

`string` ([The Name Schema](quotes-properties-the-customer-attributes-schema-the-customer-attrtibutes-schema-properties-the-name-schema.md))

### name Examples

```json
"User ID"
```

## value

The value of a given attribute.


`value`

-   is required
-   Type: `string` ([The Value Schema](quotes-properties-the-customer-attributes-schema-the-customer-attrtibutes-schema-properties-the-value-schema.md))
-   cannot be null
-   defined in: [The Root Schema](quotes-properties-the-customer-attributes-schema-the-customer-attrtibutes-schema-properties-the-value-schema.md "\#/properties/attributes/items/properties/value#/properties/attributes/items/properties/value")

### value Type

`string` ([The Value Schema](quotes-properties-the-customer-attributes-schema-the-customer-attrtibutes-schema-properties-the-value-schema.md))

### value Examples

```json
"email|5db6d0aad6be3073e95c3fcf"
```
