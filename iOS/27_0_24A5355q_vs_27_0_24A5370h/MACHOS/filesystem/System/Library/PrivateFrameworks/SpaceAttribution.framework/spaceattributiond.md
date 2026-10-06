## spaceattributiond

> `/System/Library/PrivateFrameworks/SpaceAttribution.framework/spaceattributiond`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x41668` | `0x422d0` | **`+0xc68`** |
| `__TEXT.__objc_methname` | `0x8ce0` | `0x8ea5` | **`+0x1c5`** |
| `__TEXT.__objc_stubs` | `0x7700` | `0x7880` | **`+0x180`** |
| `__DATA_CONST.__cfstring` | `0x2fc0` | `0x30e0` | **`+0x120`** |
| `__DATA_CONST.__const` | `0x1770` | `0x1880` | **`+0x110`** |
| `__DATA.__objc_const` | `0x4680` | `0x4740` | **`+0xc0`** |
| `__TEXT.__objc_methlist` | `0x3018` | `0x30b8` | **`+0xa0`** |
| `__TEXT.__cstring` | `0x37b3` | `0x384e` | **`+0x9b`** |
| `__DATA.__objc_selrefs` | `0x2368` | `0x23d8` | **`+0x70`** |
| `__TEXT.__gcc_except_tab` | `0x1998` | `0x1948` | **`-0x50`** |
| `__TEXT.__objc_methtype` | `0x1201` | `0x1227` | **`+0x26`** |
| `__TEXT.__unwind_info` | `0xed0` | `0xee8` | **`+0x18`** |
| `__DATA.__bss` | `0x200` | `0x210` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x374` | `0x384` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0xa10` | `0xa00` | **`-0x10`** |
| `__DATA_CONST.__auth_got` | `0x518` | `0x510` | **`-0x8`** |
| `__DATA_CONST.__got` | `0x240` | `0x248` | **`+0x8`** |
| `__TEXT.__oslogstring` | `0x58a6` | `0x58aa` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`

### Other Changes

```diff

-488.0.0.0.0
+490.0.0.0.0

+  - /System/Library/Frameworks/AVFoundation.framework/AVFoundation

-  Functions: 1488
+  Functions: 1511

-  CStrings:  2813
+  CStrings:  2847
Symbols:
+ _OBJC_CLASS_$_AVProVideoStorage
- _objc_retain_x9
CStrings:
+ "%@-%@"
+ "1a"
+ "@48@0:8@16i24i28I32i36i40B44"
+ "@52@0:8i16i20I24i28i32Q36Q44"
+ "ACCESSED"
+ "ACCESSED_AND_INDEXED"
+ "Category"
+ "Fading bundleID %@ Category %@"
+ "For bundleID %@, volRol %@, category %@, residency %@, numOfEvents30d is %@, numOfPristineFiles %@, numOfPristine30d %@, numOfAveragedDays %@"
+ "INDEXED"
+ "NA(%u)"
+ "NA-%@"
+ "PRISTINE"
+ "Processing bundleID %@, category %@, residency %@"
+ "SDA: end denominator processing."
+ "SDTelCategoryKeysTranslationTable"
+ "TB,V_isAccessed"
+ "TB,V_isIndexed"
+ "TQ,V_stateAndCategory"
+ "Ti,V_category"
+ "_category"
+ "_isAccessed"
+ "_isIndexed"
+ "_stateAndCategory"
+ "adjAveragesForBundleId:volType:volPath:category:residency:WithNumOfPristine:sizeOfPristine:numOfDays:"
+ "can't find dir for dir-key %llu"
+ "category"
+ "categoryDesc:"
+ "categoryFromAccessed:andIndexed:"
+ "categoryNumDesc:"
+ "com.apple.camera.vcc"
+ "getElemForBundleId:volType:category:residency:urgency:state:create:"
+ "getElemForVolType:category:residency:urgency:state:age:size:"
+ "getNumAndSizeOfEventsFor:category:residency:reply:"
+ "getNumAndSizeOfEventsForBundleId:volType:category:residency:reply:"
+ "i24@0:8B16B20"
+ "iNode %@, size %@, dirstats %@, state %@, category %@, residency %@, Purgency %@, isDirectory %@"
+ "isAccessed"
+ "isIndexed"
+ "isSupported"
+ "logEventForBundleID:volType:urgency:state:category:residency:inode:age:size:nanoSecSinceUpdate:"
+ "processPurgeableDirectoriesWithDictionary:"
+ "setCategory:"
+ "setIsAccessed:"
+ "setIsIndexed:"
+ "setStateAndCategory:"
+ "stateAndCategory"
+ "updateVolType:category:residency:urgency:state:age:size:nanoSecSinceUpdate:"
+ "upsertBundleID:volType:category:urgency:state:residency:age:size:nanoSecSinceUpdate:"
+ "v32@?0@\"NSNumber\"8@\"NSDictionary\"16^B24"
+ "v32@?0@\"NSString\"8i16I20@\"SDADataBaseAveElement\"24"
+ "v36@0:8i16i20I24@?28"
+ "v44@0:8@16i24i28I32@?36"
+ "v52@?0@\"NSString\"8i16i20I24i28i32@\"SDAHistogramElement\"36^B44"
+ "v60@0:8i16i20I24i28i32Q36Q44Q52"
+ "v68@0:8@16i24@28i36I40Q44Q52Q60"
+ "v68@0:8@16i24i28i32i36I40Q44Q52Q60"
+ "v76@0:8@16i24i28i32i36I40Q44Q52Q60Q68"
- "1Q"
- "@44@0:8@16i24I28i32i36B40"
- "@48@0:8i16I20i24i28Q32Q40"
- "For bundleID %@, volRol %@, residency %@, numOfEvents30d is %@, numOfPristineFiles %@, numOfPristine30d %@, numOfAveragedDays %@"
- "SDA: end denominator processing:"
- "USE_STATE_X_DISCARDED with dirstats id %llu with no accumulated size"
- "adjAveragesForBundleId:volType:volPath:residency:WithNumOfPristine:sizeOfPristine:numOfDays:"
- "can't find dir for dir-key %llu and dirstats-id %llu"
- "getElemForBundleId:volType:residency:urgency:state:create:"
- "getElemForVolType:residency:urgency:state:age:size:"
- "getNumAndSizeOfEventsFor:residency:reply:"
- "getNumAndSizeOfEventsForBundleId:volType:residency:reply:"
- "iNode %@, size %@, dirstats %@, state %@, residency %@, Purgency %@, isDirectory %@"
- "logEventForBundleID:volType:urgency:state:residency:inode:age:size:nanoSecSinceUpdate:"
- "updateVolType:residency:urgency:state:age:size:nanoSecSinceUpdate:"
- "upsertBundleID:volType:urgency:state:residency:age:size:nanoSecSinceUpdate:"
- "v28@?0@\"NSString\"8I16@\"SDADataBaseAveElement\"20"
- "v32@0:8i16I20@?24"
- "v40@0:8@16i24I28@?32"
- "v48@?0@\"NSString\"8i16I20i24i28@\"SDAHistogramElement\"32^B40"
- "v56@0:8i16I20i24i28Q32Q40Q48"
- "v64@0:8@16i24@28I36Q40Q48Q56"
- "v64@0:8@16i24i28i32I36Q40Q48Q56"
- "v72@0:8@16i24i28i32I36Q40Q48Q56Q64"
```
