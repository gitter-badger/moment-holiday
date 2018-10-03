[Moment Holiday (by Nesto)](../README.md) > [api](../modules/api.md)

# Package: api

![MOMENT-HOLIDAY](https://raw.githubusercontent.com/nesto-software/moment-holiday/master/docs/assets/images/moment-holiday.png)

Handling holidays with 💪 typings using TypeScript
--------------------------------------------------

This is the api package. It contains the methods which are directly callable by the client. For more information visit the [docs](https://nesto-software.github.io/moment-holiday/docs/).

## Index

### Modules

* ["moment"](api._moment_.md)
* [__global](api.__global.md)

### Classes

* [AbstractMomentHoliday](../classes/api.abstractmomentholiday.md)
* [AsyncMomentHoliday](../classes/api.asyncmomentholiday.md)
* [HolidayDefinitionFactoryRegistry](../classes/api.holidaydefinitionfactoryregistry.md)
* [SyncMomentHoliday](../classes/api.syncmomentholiday.md)

### Type aliases

* [AdministrativeUnitIdentifier](api.md#administrativeunitidentifier)
* [AustrianCountryIdentifier](api.md#austriancountryidentifier)
* [CountryAbbreviation](api.md#countryabbreviation)
* [CountryIdentifier](api.md#countryidentifier)
* [CountryName](api.md#countryname)
* [GermanCountryIdentifier](api.md#germancountryidentifier)
* [RegionIdentifier](api.md#regionidentifier)
* [StateIdentifier](api.md#stateidentifier)

### Variables

* [momentRange](api.md#momentrange)
* [momentRange](api.md#momentrange-1)

### Functions

* [MomentHolidayFactoryMethod](api.md#momentholidayfactorymethod)
* [addExpectToContainObject](api.md#addexpecttocontainobject)

---

## Type aliases

<a id="administrativeunitidentifier"></a>

###  AdministrativeUnitIdentifier

**Ƭ AdministrativeUnitIdentifier**: * [StateIdentifier](api.md#stateidentifier) &#124; [RegionIdentifier](api.md#regionidentifier)
*

*Defined in [packages/api/src/abstract-moment-holiday.ts:288](https://github.com/nesto-software/moment-holiday/blob/72ce1a6/packages/api/src/abstract-moment-holiday.ts#L288)*

___
<a id="austriancountryidentifier"></a>

###  AustrianCountryIdentifier

**Ƭ AustrianCountryIdentifier**: * [AustrianCountryName](_node_modules__nesto_software_moment_holiday_austria_src_austrian_holiday_definition_factory_.md#austriancountryname) &#124; [AustrianCountryAbbrevition](_node_modules__nesto_software_moment_holiday_austria_src_austrian_holiday_definition_factory_.md#austriancountryabbrevition)
*

*Defined in [packages/api/src/abstract-moment-holiday.ts:278](https://github.com/nesto-software/moment-holiday/blob/72ce1a6/packages/api/src/abstract-moment-holiday.ts#L278)*

___
<a id="countryabbreviation"></a>

###  CountryAbbreviation

**Ƭ CountryAbbreviation**: * [GermanCountryAbbrevition](_node_modules__nesto_software_moment_holiday_germany_src_german_holiday_definition_factory_.md#germancountryabbrevition) &#124; [AustrianCountryAbbrevition](_node_modules__nesto_software_moment_holiday_austria_src_austrian_holiday_definition_factory_.md#austriancountryabbrevition)
*

*Defined in [packages/api/src/abstract-moment-holiday.ts:282](https://github.com/nesto-software/moment-holiday/blob/72ce1a6/packages/api/src/abstract-moment-holiday.ts#L282)*

___
<a id="countryidentifier"></a>

###  CountryIdentifier

**Ƭ CountryIdentifier**: * [GermanCountryIdentifier](api.md#germancountryidentifier) &#124; [AustrianCountryIdentifier](api.md#austriancountryidentifier)
*

*Defined in [packages/api/src/abstract-moment-holiday.ts:283](https://github.com/nesto-software/moment-holiday/blob/72ce1a6/packages/api/src/abstract-moment-holiday.ts#L283)*

___
<a id="countryname"></a>

###  CountryName

**Ƭ CountryName**: * [GermanCountryName](_node_modules__nesto_software_moment_holiday_germany_src_german_holiday_definition_factory_.md#germancountryname) &#124; [AustrianCountryName](_node_modules__nesto_software_moment_holiday_austria_src_austrian_holiday_definition_factory_.md#austriancountryname)
*

*Defined in [packages/api/src/abstract-moment-holiday.ts:281](https://github.com/nesto-software/moment-holiday/blob/72ce1a6/packages/api/src/abstract-moment-holiday.ts#L281)*

___
<a id="germancountryidentifier"></a>

###  GermanCountryIdentifier

**Ƭ GermanCountryIdentifier**: * [GermanCountryName](_node_modules__nesto_software_moment_holiday_germany_src_german_holiday_definition_factory_.md#germancountryname) &#124; [GermanCountryAbbrevition](_node_modules__nesto_software_moment_holiday_germany_src_german_holiday_definition_factory_.md#germancountryabbrevition)
*

*Defined in [packages/api/src/abstract-moment-holiday.ts:277](https://github.com/nesto-software/moment-holiday/blob/72ce1a6/packages/api/src/abstract-moment-holiday.ts#L277)*

___
<a id="regionidentifier"></a>

###  RegionIdentifier

**Ƭ RegionIdentifier**: *[GermanRegionAbbreviation](_node_modules__nesto_software_moment_holiday_germany_src_german_holiday_definition_factory_.md#germanregionabbreviation)*

*Defined in [packages/api/src/abstract-moment-holiday.ts:285](https://github.com/nesto-software/moment-holiday/blob/72ce1a6/packages/api/src/abstract-moment-holiday.ts#L285)*

___
<a id="stateidentifier"></a>

###  StateIdentifier

**Ƭ StateIdentifier**: *[GermanStateAbbreviation](_node_modules__nesto_software_moment_holiday_germany_src_german_holiday_definition_factory_.md#germanstateabbreviation)*

*Defined in [packages/api/src/abstract-moment-holiday.ts:284](https://github.com/nesto-software/moment-holiday/blob/72ce1a6/packages/api/src/abstract-moment-holiday.ts#L284)*

___

## Variables

<a id="momentrange"></a>

### `<Const>` momentRange

**● momentRange**: *`any`* =  extendMoment(momentNamespace)

*Defined in [packages/api/src/async-moment-holiday.ts:13](https://github.com/nesto-software/moment-holiday/blob/72ce1a6/packages/api/src/async-moment-holiday.ts#L13)*

___
<a id="momentrange-1"></a>

### `<Const>` momentRange

**● momentRange**: *`any`* =  extendMoment(momentNamespace)

*Defined in [packages/api/src/sync-moment-holiday.ts:15](https://github.com/nesto-software/moment-holiday/blob/72ce1a6/packages/api/src/sync-moment-holiday.ts#L15)*

___

## Functions

<a id="momentholidayfactorymethod"></a>

###  MomentHolidayFactoryMethod

▸ **MomentHolidayFactoryMethod**(country: *[GermanCountryIdentifier](api.md#germancountryidentifier)*, ...administrativeUnits: *`Array`< [GermanStateAbbreviation](_node_modules__nesto_software_moment_holiday_germany_src_german_holiday_definition_factory_.md#germanstateabbreviation) &#124; [GermanRegionAbbreviation](_node_modules__nesto_software_moment_holiday_germany_src_german_holiday_definition_factory_.md#germanregionabbreviation) &#124; "ALL">*): [SyncMomentHoliday](../classes/api.syncmomentholiday.md)

▸ **MomentHolidayFactoryMethod**(country: *[AustrianCountryIdentifier](api.md#austriancountryidentifier)*, ...administrativeUnits: *`Array`<"ALL">*): [SyncMomentHoliday](../classes/api.syncmomentholiday.md)

▸ **MomentHolidayFactoryMethod**(country: *[CountryIdentifier](api.md#countryidentifier)*, ...administrativeUnits: *`Array`< [AdministrativeUnitIdentifier](api.md#administrativeunitidentifier) &#124; "ALL">*): [SyncMomentHoliday](../classes/api.syncmomentholiday.md)

*Defined in [packages/api/src/abstract-moment-holiday.ts:290](https://github.com/nesto-software/moment-holiday/blob/72ce1a6/packages/api/src/abstract-moment-holiday.ts#L290)*

Returns a moment holiday configuration for the given entities. If you provide a country only, you get the country holidays only. If you provide the state identifier "ALL", then all state holidays will be merged with the country holidays. If you provide any states identifiers other then "ALL", then those states's holidays will be merged with the country holidays.

**Parameters:**

| Param | Type | Description |
| ------ | ------ | ------ |
| country | [GermanCountryIdentifier](api.md#germancountryidentifier) |  the country to look up |
| `Rest` administrativeUnits | `Array`< [GermanStateAbbreviation](_node_modules__nesto_software_moment_holiday_germany_src_german_holiday_definition_factory_.md#germanstateabbreviation) &#124; [GermanRegionAbbreviation](_node_modules__nesto_software_moment_holiday_germany_src_german_holiday_definition_factory_.md#germanregionabbreviation) &#124; "ALL"> |  the administrative unit(s) to look up |

**Returns:** [SyncMomentHoliday](../classes/api.syncmomentholiday.md)
a moment holiday configuration which is configured to compute holidays for the given country and units

*Defined in [packages/api/src/abstract-moment-holiday.ts:293](https://github.com/nesto-software/moment-holiday/blob/72ce1a6/packages/api/src/abstract-moment-holiday.ts#L293)*

Returns a moment holiday configuration for the given entities. If you provide a country only, you get the country holidays only. If you provide the state identifier "ALL", then all state holidays will be merged with the country holidays. If you provide any states identifiers other then "ALL", then those states's holidays will be merged with the country holidays.

**Parameters:**

| Param | Type | Description |
| ------ | ------ | ------ |
| country | [AustrianCountryIdentifier](api.md#austriancountryidentifier) |  the country to look up |
| `Rest` administrativeUnits | `Array`<"ALL"> |  the administrative unit(s) to look up |

**Returns:** [SyncMomentHoliday](../classes/api.syncmomentholiday.md)
a moment holiday configuration which is configured to compute holidays for the given country and units

*Defined in [packages/api/src/abstract-moment-holiday.ts:297](https://github.com/nesto-software/moment-holiday/blob/72ce1a6/packages/api/src/abstract-moment-holiday.ts#L297)*

Returns a moment holiday configuration for the given entities. If you provide a country only, you get the country holidays only. If you provide the state identifier "ALL", then all state holidays will be merged with the country holidays. If you provide any states identifiers other then "ALL", then those states's holidays will be merged with the country holidays.

**Parameters:**

| Param | Type | Description |
| ------ | ------ | ------ |
| country | [CountryIdentifier](api.md#countryidentifier) |  the country to look up |
| `Rest` administrativeUnits | `Array`< [AdministrativeUnitIdentifier](api.md#administrativeunitidentifier) &#124; "ALL"> |  the administrative unit(s) to look up |

**Returns:** [SyncMomentHoliday](../classes/api.syncmomentholiday.md)
a moment holiday configuration which is configured to compute holidays for the given country and units

___
<a id="addexpecttocontainobject"></a>

### `<Const>` addExpectToContainObject

▸ **addExpectToContainObject**(): `void`

*Defined in [packages/api/test/unit/extend-expect-by-to-contain-object.ts:2](https://github.com/nesto-software/moment-holiday/blob/72ce1a6/packages/api/test/unit/extend-expect-by-to-contain-object.ts#L2)*

**Returns:** `void`

___

