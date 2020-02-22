[Polkadot JS API](../README.md) › [Globals](../globals.md) › ["extrinsic/v2/Extrinsic"](../modules/_extrinsic_v2_extrinsic_.md) › [ExtrinsicV2](_extrinsic_v2_extrinsic_.extrinsicv2.md)

# Class: ExtrinsicV2 <**S, T, V, E**>

**`name`** GenericExtrinsicV2

**`description`** 
The second generation of compact extrinsics

## Type parameters

▪ **S**: *TypesDef*

▪ **T**: *object*

▪ **V**: *object*

▪ **E**: *object*

## Hierarchy

  ↳ [Struct](_codec_struct_.struct.md)

  ↳ **ExtrinsicV2**

## Implements

* [Codec](../interfaces/_types_codec_.codec.md)
* [IExtrinsicImpl](../interfaces/_types_extrinsic_.iextrinsicimpl.md)

## Index

### Constructors

* [constructor](_extrinsic_v2_extrinsic_.extrinsicv2.md#constructor)

### Properties

* [registry](_extrinsic_v2_extrinsic_.extrinsicv2.md#registry)

### Accessors

* [Type](_extrinsic_v2_extrinsic_.extrinsicv2.md#type)
* [defKeys](_extrinsic_v2_extrinsic_.extrinsicv2.md#defkeys)
* [encodedLength](_extrinsic_v2_extrinsic_.extrinsicv2.md#encodedlength)
* [hash](_extrinsic_v2_extrinsic_.extrinsicv2.md#hash)
* [isEmpty](_extrinsic_v2_extrinsic_.extrinsicv2.md#isempty)
* [method](_extrinsic_v2_extrinsic_.extrinsicv2.md#method)
* [signature](_extrinsic_v2_extrinsic_.extrinsicv2.md#signature)
* [version](_extrinsic_v2_extrinsic_.extrinsicv2.md#version)

### Methods

* [addSignature](_extrinsic_v2_extrinsic_.extrinsicv2.md#addsignature)
* [eq](_extrinsic_v2_extrinsic_.extrinsicv2.md#eq)
* [get](_extrinsic_v2_extrinsic_.extrinsicv2.md#get)
* [getAtIndex](_extrinsic_v2_extrinsic_.extrinsicv2.md#getatindex)
* [sign](_extrinsic_v2_extrinsic_.extrinsicv2.md#sign)
* [signFake](_extrinsic_v2_extrinsic_.extrinsicv2.md#signfake)
* [toArray](_extrinsic_v2_extrinsic_.extrinsicv2.md#toarray)
* [toHex](_extrinsic_v2_extrinsic_.extrinsicv2.md#tohex)
* [toHuman](_extrinsic_v2_extrinsic_.extrinsicv2.md#tohuman)
* [toJSON](_extrinsic_v2_extrinsic_.extrinsicv2.md#tojson)
* [toRawType](_extrinsic_v2_extrinsic_.extrinsicv2.md#torawtype)
* [toString](_extrinsic_v2_extrinsic_.extrinsicv2.md#tostring)
* [toU8a](_extrinsic_v2_extrinsic_.extrinsicv2.md#tou8a)
* [typesToMap](_extrinsic_v2_extrinsic_.extrinsicv2.md#static-typestomap)
* [with](_extrinsic_v2_extrinsic_.extrinsicv2.md#static-with)

## Constructors

###  constructor

\+ **new ExtrinsicV2**(`registry`: [Registry](../interfaces/_types_registry_.registry.md), `value?`: [Uint8Array](_codec_raw_.raw.md#static-uint8array) | [ExtrinsicValueV2](../interfaces/_extrinsic_v2_extrinsic_.extrinsicvaluev2.md) | Call, `__namedParameters`: object): *[ExtrinsicV2](_extrinsic_v2_extrinsic_.extrinsicv2.md)*

*Overrides [Struct](_codec_struct_.struct.md).[constructor](_codec_struct_.struct.md#constructor)*

*Defined in [packages/types/src/extrinsic/v2/Extrinsic.ts:27](https://github.com/polkadot-js/api/blob/196a0891b/packages/types/src/extrinsic/v2/Extrinsic.ts#L27)*

**Parameters:**

▪ **registry**: *[Registry](../interfaces/_types_registry_.registry.md)*

▪`Optional`  **value**: *[Uint8Array](_codec_raw_.raw.md#static-uint8array) | [ExtrinsicValueV2](../interfaces/_extrinsic_v2_extrinsic_.extrinsicvaluev2.md) | Call*

▪`Default value`  **__namedParameters**: *object*= {}

Name | Type |
------ | ------ |
`isSigned` | undefined &#124; false &#124; true |

**Returns:** *[ExtrinsicV2](_extrinsic_v2_extrinsic_.extrinsicv2.md)*

## Properties

###  registry

• **registry**: *[Registry](../interfaces/_types_registry_.registry.md)*

*Implementation of [IExtrinsicImpl](../interfaces/_types_extrinsic_.iextrinsicimpl.md).[registry](../interfaces/_types_extrinsic_.iextrinsicimpl.md#registry)*

*Inherited from [Struct](_codec_struct_.struct.md).[registry](_codec_struct_.struct.md#registry)*

*Defined in [packages/types/src/codec/Struct.ts:106](https://github.com/polkadot-js/api/blob/196a0891b/packages/types/src/codec/Struct.ts#L106)*

## Accessors

###  Type

• **get Type**(): *E*

*Inherited from [Struct](_codec_struct_.struct.md).[Type](_codec_struct_.struct.md#type)*

*Defined in [packages/types/src/codec/Struct.ts:168](https://github.com/polkadot-js/api/blob/196a0891b/packages/types/src/codec/Struct.ts#L168)*

**`description`** Returns the Type description to sthe structure

**Returns:** *E*

___

###  defKeys

• **get defKeys**(): *string[]*

*Inherited from [Struct](_codec_struct_.struct.md).[defKeys](_codec_struct_.struct.md#defkeys)*

*Defined in [packages/types/src/codec/Struct.ts:146](https://github.com/polkadot-js/api/blob/196a0891b/packages/types/src/codec/Struct.ts#L146)*

**`description`** The available keys for this enum

**Returns:** *string[]*

___

###  encodedLength

• **get encodedLength**(): *number*

*Overrides [Struct](_codec_struct_.struct.md).[encodedLength](_codec_struct_.struct.md#encodedlength)*

*Defined in [packages/types/src/extrinsic/v2/Extrinsic.ts:58](https://github.com/polkadot-js/api/blob/196a0891b/packages/types/src/extrinsic/v2/Extrinsic.ts#L58)*

**`description`** The length of the value when encoded as a Uint8Array

**Returns:** *number*

___

###  hash

• **get hash**(): *H256*

*Inherited from [Struct](_codec_struct_.struct.md).[hash](_codec_struct_.struct.md#hash)*

*Defined in [packages/types/src/codec/Struct.ts:192](https://github.com/polkadot-js/api/blob/196a0891b/packages/types/src/codec/Struct.ts#L192)*

**`description`** returns a hash of the contents

**Returns:** *H256*

___

###  isEmpty

• **get isEmpty**(): *boolean*

*Inherited from [Struct](_codec_struct_.struct.md).[isEmpty](_codec_struct_.struct.md#isempty)*

*Defined in [packages/types/src/codec/Struct.ts:153](https://github.com/polkadot-js/api/blob/196a0891b/packages/types/src/codec/Struct.ts#L153)*

**`description`** Checks if the value is an empty value

**Returns:** *boolean*

___

###  method

• **get method**(): *Call*

*Defined in [packages/types/src/extrinsic/v2/Extrinsic.ts:65](https://github.com/polkadot-js/api/blob/196a0891b/packages/types/src/extrinsic/v2/Extrinsic.ts#L65)*

**`description`** The [Call](_generic_call_.call.md) this extrinsic wraps

**Returns:** *Call*

___

###  signature

• **get signature**(): *ExtrinsicSignatureV2*

*Defined in [packages/types/src/extrinsic/v2/Extrinsic.ts:72](https://github.com/polkadot-js/api/blob/196a0891b/packages/types/src/extrinsic/v2/Extrinsic.ts#L72)*

**`description`** The [ExtrinsicSignatureV2](_extrinsic_v2_extrinsicsignature_.extrinsicsignaturev2.md)

**Returns:** *ExtrinsicSignatureV2*

___

###  version

• **get version**(): *number*

*Defined in [packages/types/src/extrinsic/v2/Extrinsic.ts:79](https://github.com/polkadot-js/api/blob/196a0891b/packages/types/src/extrinsic/v2/Extrinsic.ts#L79)*

**`description`** The version for the signature

**Returns:** *number*

## Methods

###  addSignature

▸ **addSignature**(`signer`: Address | [Uint8Array](_codec_raw_.raw.md#static-uint8array) | string, `signature`: [Uint8Array](_codec_raw_.raw.md#static-uint8array) | string, `payload`: [ExtrinsicPayloadValue](../interfaces/_types_extrinsic_.extrinsicpayloadvalue.md) | [Uint8Array](_codec_raw_.raw.md#static-uint8array) | string): *[ExtrinsicV2](_extrinsic_v2_extrinsic_.extrinsicv2.md)*

*Implementation of [IExtrinsicImpl](../interfaces/_types_extrinsic_.iextrinsicimpl.md)*

*Defined in [packages/types/src/extrinsic/v2/Extrinsic.ts:86](https://github.com/polkadot-js/api/blob/196a0891b/packages/types/src/extrinsic/v2/Extrinsic.ts#L86)*

**`description`** Add an [ExtrinsicSignatureV2](_extrinsic_v2_extrinsicsignature_.extrinsicsignaturev2.md) to the extrinsic (already generated)

**Parameters:**

Name | Type |
------ | ------ |
`signer` | Address &#124; [Uint8Array](_codec_raw_.raw.md#static-uint8array) &#124; string |
`signature` | [Uint8Array](_codec_raw_.raw.md#static-uint8array) &#124; string |
`payload` | [ExtrinsicPayloadValue](../interfaces/_types_extrinsic_.extrinsicpayloadvalue.md) &#124; [Uint8Array](_codec_raw_.raw.md#static-uint8array) &#124; string |

**Returns:** *[ExtrinsicV2](_extrinsic_v2_extrinsic_.extrinsicv2.md)*

___

###  eq

▸ **eq**(`other?`: any): *boolean*

*Implementation of [IExtrinsicImpl](../interfaces/_types_extrinsic_.iextrinsicimpl.md)*

*Inherited from [Struct](_codec_struct_.struct.md).[eq](_codec_struct_.struct.md#eq)*

*Defined in [packages/types/src/codec/Struct.ts:199](https://github.com/polkadot-js/api/blob/196a0891b/packages/types/src/codec/Struct.ts#L199)*

**`description`** Compares the value of the input to see if there is a match

**Parameters:**

Name | Type |
------ | ------ |
`other?` | any |

**Returns:** *boolean*

___

###  get

▸ **get**(`name`: keyof S): *[Codec](../interfaces/_types_codec_.codec.md) | undefined*

*Inherited from [Struct](_codec_struct_.struct.md).[get](_codec_struct_.struct.md#get)*

*Overrides [BTreeMap](_codec_btreemap_.btreemap.md).[get](_codec_btreemap_.btreemap.md#get)*

*Defined in [packages/types/src/codec/Struct.ts:207](https://github.com/polkadot-js/api/blob/196a0891b/packages/types/src/codec/Struct.ts#L207)*

**`description`** Returns a specific names entry in the structure

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`name` | keyof S | The name of the entry to retrieve  |

**Returns:** *[Codec](../interfaces/_types_codec_.codec.md) | undefined*

___

###  getAtIndex

▸ **getAtIndex**(`index`: number): *[Codec](../interfaces/_types_codec_.codec.md)*

*Inherited from [Struct](_codec_struct_.struct.md).[getAtIndex](_codec_struct_.struct.md#getatindex)*

*Defined in [packages/types/src/codec/Struct.ts:214](https://github.com/polkadot-js/api/blob/196a0891b/packages/types/src/codec/Struct.ts#L214)*

**`description`** Returns the values of a member at a specific index (Rather use get(name) for performance)

**Parameters:**

Name | Type |
------ | ------ |
`index` | number |

**Returns:** *[Codec](../interfaces/_types_codec_.codec.md)*

___

###  sign

▸ **sign**(`account`: [IKeyringPair](../interfaces/_types_interfaces_.ikeyringpair.md), `options`: [SignatureOptions](../interfaces/_types_extrinsic_.signatureoptions.md)): *[ExtrinsicV2](_extrinsic_v2_extrinsic_.extrinsicv2.md)*

*Implementation of [IExtrinsicImpl](../interfaces/_types_extrinsic_.iextrinsicimpl.md)*

*Defined in [packages/types/src/extrinsic/v2/Extrinsic.ts:95](https://github.com/polkadot-js/api/blob/196a0891b/packages/types/src/extrinsic/v2/Extrinsic.ts#L95)*

**`description`** Sign the extrinsic with a specific keypair

**Parameters:**

Name | Type |
------ | ------ |
`account` | [IKeyringPair](../interfaces/_types_interfaces_.ikeyringpair.md) |
`options` | [SignatureOptions](../interfaces/_types_extrinsic_.signatureoptions.md) |

**Returns:** *[ExtrinsicV2](_extrinsic_v2_extrinsic_.extrinsicv2.md)*

___

###  signFake

▸ **signFake**(`signer`: Address | [Uint8Array](_codec_raw_.raw.md#static-uint8array) | string, `options`: [SignatureOptions](../interfaces/_types_extrinsic_.signatureoptions.md)): *[ExtrinsicV2](_extrinsic_v2_extrinsic_.extrinsicv2.md)*

*Implementation of [IExtrinsicImpl](../interfaces/_types_extrinsic_.iextrinsicimpl.md)*

*Defined in [packages/types/src/extrinsic/v2/Extrinsic.ts:104](https://github.com/polkadot-js/api/blob/196a0891b/packages/types/src/extrinsic/v2/Extrinsic.ts#L104)*

**`describe`** Adds a fake signature to the extrinsic

**Parameters:**

Name | Type |
------ | ------ |
`signer` | Address &#124; [Uint8Array](_codec_raw_.raw.md#static-uint8array) &#124; string |
`options` | [SignatureOptions](../interfaces/_types_extrinsic_.signatureoptions.md) |

**Returns:** *[ExtrinsicV2](_extrinsic_v2_extrinsic_.extrinsicv2.md)*

___

###  toArray

▸ **toArray**(): *[Codec](../interfaces/_types_codec_.codec.md)[]*

*Inherited from [Struct](_codec_struct_.struct.md).[toArray](_codec_struct_.struct.md#toarray)*

*Defined in [packages/types/src/codec/Struct.ts:221](https://github.com/polkadot-js/api/blob/196a0891b/packages/types/src/codec/Struct.ts#L221)*

**`description`** Converts the Object to an standard JavaScript Array

**Returns:** *[Codec](../interfaces/_types_codec_.codec.md)[]*

___

###  toHex

▸ **toHex**(): *string*

*Inherited from [Struct](_codec_struct_.struct.md).[toHex](_codec_struct_.struct.md#tohex)*

*Defined in [packages/types/src/codec/Struct.ts:228](https://github.com/polkadot-js/api/blob/196a0891b/packages/types/src/codec/Struct.ts#L228)*

**`description`** Returns a hex string representation of the value

**Returns:** *string*

___

###  toHuman

▸ **toHuman**(`isExtended?`: undefined | false | true): *[AnyJson](../modules/_types_helpers_.md#anyjson)*

*Implementation of [IExtrinsicImpl](../interfaces/_types_extrinsic_.iextrinsicimpl.md)*

*Inherited from [Struct](_codec_struct_.struct.md).[toHuman](_codec_struct_.struct.md#tohuman)*

*Defined in [packages/types/src/codec/Struct.ts:235](https://github.com/polkadot-js/api/blob/196a0891b/packages/types/src/codec/Struct.ts#L235)*

**`description`** Converts the Object to to a human-friendly JSON, with additional fields, expansion and formatting of information

**Parameters:**

Name | Type |
------ | ------ |
`isExtended?` | undefined &#124; false &#124; true |

**Returns:** *[AnyJson](../modules/_types_helpers_.md#anyjson)*

___

###  toJSON

▸ **toJSON**(): *[AnyJson](../modules/_types_helpers_.md#anyjson)*

*Implementation of [IExtrinsicImpl](../interfaces/_types_extrinsic_.iextrinsicimpl.md)*

*Inherited from [Struct](_codec_struct_.struct.md).[toJSON](_codec_struct_.struct.md#tojson)*

*Defined in [packages/types/src/codec/Struct.ts:249](https://github.com/polkadot-js/api/blob/196a0891b/packages/types/src/codec/Struct.ts#L249)*

**`description`** Converts the Object to JSON, typically used for RPC transfers

**Returns:** *[AnyJson](../modules/_types_helpers_.md#anyjson)*

___

###  toRawType

▸ **toRawType**(): *string*

*Implementation of [IExtrinsicImpl](../interfaces/_types_extrinsic_.iextrinsicimpl.md)*

*Inherited from [Struct](_codec_struct_.struct.md).[toRawType](_codec_struct_.struct.md#torawtype)*

*Defined in [packages/types/src/codec/Struct.ts:273](https://github.com/polkadot-js/api/blob/196a0891b/packages/types/src/codec/Struct.ts#L273)*

**`description`** Returns the base runtime type name for this instance

**Returns:** *string*

___

###  toString

▸ **toString**(): *string*

*Implementation of [IExtrinsicImpl](../interfaces/_types_extrinsic_.iextrinsicimpl.md)*

*Inherited from [Struct](_codec_struct_.struct.md).[toString](_codec_struct_.struct.md#tostring)*

*Defined in [packages/types/src/codec/Struct.ts:282](https://github.com/polkadot-js/api/blob/196a0891b/packages/types/src/codec/Struct.ts#L282)*

**`description`** Returns the string representation of the value

**Returns:** *string*

___

###  toU8a

▸ **toU8a**(`isBare?`: [BareOpts](../modules/_types_helpers_.md#bareopts)): *[Uint8Array](_codec_raw_.raw.md#static-uint8array)*

*Implementation of [IExtrinsicImpl](../interfaces/_types_extrinsic_.iextrinsicimpl.md)*

*Inherited from [Struct](_codec_struct_.struct.md).[toU8a](_codec_struct_.struct.md#tou8a)*

*Defined in [packages/types/src/codec/Struct.ts:290](https://github.com/polkadot-js/api/blob/196a0891b/packages/types/src/codec/Struct.ts#L290)*

**`description`** Encodes the value as a Uint8Array as per the SCALE specifications

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`isBare?` | [BareOpts](../modules/_types_helpers_.md#bareopts) | true when the value has none of the type-specific prefixes (internal)  |

**Returns:** *[Uint8Array](_codec_raw_.raw.md#static-uint8array)*

___

### `Static` typesToMap

▸ **typesToMap**(`registry`: [Registry](../interfaces/_types_registry_.registry.md), `Types`: Record‹string, [Constructor](../interfaces/_types_codec_.constructor.md)›): *Record‹string, string›*

*Inherited from [Struct](_codec_struct_.struct.md).[typesToMap](_codec_struct_.struct.md#static-typestomap)*

*Defined in [packages/types/src/codec/Struct.ts:262](https://github.com/polkadot-js/api/blob/196a0891b/packages/types/src/codec/Struct.ts#L262)*

**Parameters:**

Name | Type |
------ | ------ |
`registry` | [Registry](../interfaces/_types_registry_.registry.md) |
`Types` | Record‹string, [Constructor](../interfaces/_types_codec_.constructor.md)› |

**Returns:** *Record‹string, string›*

___

### `Static` with

▸ **with**<**S**>(`Types`: S): *[Constructor](../interfaces/_types_codec_.constructor.md)‹[Struct](_codec_struct_.struct.md)‹S››*

*Inherited from [Struct](_codec_struct_.struct.md).[with](_codec_struct_.struct.md#static-with)*

*Defined in [packages/types/src/codec/Struct.ts:123](https://github.com/polkadot-js/api/blob/196a0891b/packages/types/src/codec/Struct.ts#L123)*

**Type parameters:**

▪ **S**: *TypesDef*

**Parameters:**

Name | Type |
------ | ------ |
`Types` | S |

**Returns:** *[Constructor](../interfaces/_types_codec_.constructor.md)‹[Struct](_codec_struct_.struct.md)‹S››*