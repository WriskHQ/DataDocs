# README

## Top-level Schemas

-   [Policy Transaction](./policy_transaction.md "The root schema comprises the entire JSON document") – `http://example.com/example.json`

## Other Schemas

### Objects

-   [Entitlements](./policy_transaction-properties-the-profile-schema-properties-the-profile-data-schema-properties-the-drivinglicence-schema-properties-the-entitlements-schema-entitlements.md "An explanation about the purpose of this instance") – `#/properties/profile/properties/data/properties/drivingLicence/properties/entitlements/items#/properties/profile/properties/data/properties/drivingLicence/properties/entitlements/items`
-   [The Address Schema](./policy_transaction-properties-the-profile-schema-properties-the-profile-data-schema-properties-the-address-schema.md "An explanation about the purpose of this instance") – `#/properties/profile/properties/data/properties/address#/properties/profile/properties/data/properties/address`
-   [The Asset Data Schema](./policy_transaction-properties-the-asset-schema-properties-the-asset-data-schema.md "An object that describes the asset and it's relationship to the user") – `#/properties/asset/properties/data#/properties/asset/properties/data`
-   [The Asset Schema](./policy_transaction-properties-the-asset-schema.md "An object that describes an insurable asset and it's relationship to the insured") – `#/properties/asset#/properties/asset`
-   [The Drivinglicence Schema](./policy_transaction-properties-the-profile-schema-properties-the-profile-data-schema-properties-the-drivinglicence-schema.md "An explanation about the purpose of this instance") – `#/properties/profile/properties/data/properties/drivingLicence#/properties/profile/properties/data/properties/drivingLicence`
-   [The Profile Data Schema](./policy_transaction-properties-the-profile-schema-properties-the-profile-data-schema.md "An explanation about the purpose of this instance") – `#/properties/profile/properties/data#/properties/profile/properties/data`
-   [The Profile Schema](./policy_transaction-properties-the-profile-schema.md "An object that describes the customer") – `#/properties/profile#/properties/profile`
-   [The Property Schema](./policy_transaction-properties-the-profile-schema-properties-the-profile-data-schema-properties-the-property-schema.md "An explanation about the purpose of this instance") – `#/properties/profile/properties/data/properties/property#/properties/profile/properties/data/properties/property`
-   [The Risk Factors Schema](./policy_transaction-properties-the-risk_factors-schema-the-risk-factors-schema.md "A single rating factor") – `#/properties/risk_factors/items#/properties/risk_factors/items`
-   [The Specification Schema](./policy_transaction-properties-the-asset-schema-properties-the-asset-data-schema-properties-the-specification-schema.md "The speification of the vehicle") – `#/properties/asset/properties/data/properties/specification#/properties/asset/properties/data/properties/specification`
-   [Transaction Lines](./policy_transaction-properties-the-transaction_lines-schema-transaction-lines.md "A object describing the lines of insurance being charged/refunded") – `#/properties/transaction_lines/items#/properties/transaction_lines/items`

### Arrays

-   [The Convictions Schema](./policy_transaction-properties-the-profile-schema-properties-the-profile-data-schema-properties-the-drivinglicence-schema-properties-the-convictions-schema.md "An explanation about the purpose of this instance") – `#/properties/profile/properties/data/properties/drivingLicence/properties/convictions#/properties/profile/properties/data/properties/drivingLicence/properties/convictions`
-   [The Entitlements Schema](./policy_transaction-properties-the-profile-schema-properties-the-profile-data-schema-properties-the-drivinglicence-schema-properties-the-entitlements-schema.md "Describes Entitlements attached to a customers Driving Licence") – `#/properties/profile/properties/data/properties/drivingLicence/properties/entitlements#/properties/profile/properties/data/properties/drivingLicence/properties/entitlements`
-   [The Risk_factors Schema](./policy_transaction-properties-the-risk_factors-schema.md "An array that describes the factors which are used to price the insurance risk") – `#/properties/risk_factors#/properties/risk_factors`
-   [The Transaction_lines Schema](./policy_transaction-properties-the-transaction_lines-schema.md "A line of insurance cover that has been charged/refunded to the customer") – `#/properties/transaction_lines#/properties/transaction_lines`
-   [The Vehicleclaimshistory Schema](./policy_transaction-properties-the-profile-schema-properties-the-profile-data-schema-properties-the-vehicleclaimshistory-schema.md "An explanation about the purpose of this instance") – `#/properties/profile/properties/data/properties/vehicleClaimsHistory#/properties/profile/properties/data/properties/vehicleClaimsHistory`

## Version Note

The schemas linked above follow the JSON Schema Spec version: `http://json-schema.org/draft-07/schema`
