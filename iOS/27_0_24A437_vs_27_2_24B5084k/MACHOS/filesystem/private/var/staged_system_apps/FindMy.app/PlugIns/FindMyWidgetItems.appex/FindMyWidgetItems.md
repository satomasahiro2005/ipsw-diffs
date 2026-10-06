## FindMyWidgetItems

> `/private/var/staged_system_apps/FindMy.app/PlugIns/FindMyWidgetItems.appex/FindMyWidgetItems`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x33c0c` | `0x281c0` | **`-0xba4c`** |
| `__DATA.__bss` | `0x20c8` | `0x15d8` | **`-0xaf0`** |
| `__TEXT.__auth_stubs` | `0x2500` | `0x1d80` | **`-0x780`** |
| `__TEXT.__const` | `0x25d4` | `0x1f04` | **`-0x6d0`** |
| `__TEXT.__eh_frame` | `0xe1c` | `0x7c4` | **`-0x658`** |
| `__DATA.__data` | `0x1d88` | `0x1858` | **`-0x530`** |
| `__DATA_CONST.__auth_got` | `0x1288` | `0xec8` | **`-0x3c0`** |
| `__DATA_CONST.__auth_ptr` | `0xb38` | `0x810` | **`-0x328`** |
| `__TEXT.__swift5_typeref` | `0x2992` | `0x26a0` | **`-0x2f2`** |
| `__TEXT.__unwind_info` | `0xb78` | `0x8d8` | **`-0x2a0`** |
| `__TEXT.__objc_stubs` | `0x260` | `0xa0` | **`-0x1c0`** |
| `__DATA_CONST.__got` | `0x618` | `0x478` | **`-0x1a0`** |
| `__DATA_CONST.__const` | `0x1080` | `0xf30` | **`-0x150`** |
| `__TEXT.__cstring` | `0x960` | `0x840` | **`-0x120`** |
| `__TEXT.__oslogstring` | `0x34e` | `0x24e` | **`-0x100`** |
| `__TEXT.__objc_methname` | `0x16c` | `0x70` | **`-0xfc`** |
| `__TEXT.__swift5_assocty` | `0x330` | `0x248` | **`-0xe8`** |
| `__TEXT.__swift5_fieldmd` | `0xa18` | `0x938` | **`-0xe0`** |
| `__TEXT.__swift5_reflstr` | `0x8b7` | `0x7d7` | **`-0xe0`** |
| `__TEXT.__constg_swiftt` | `0xbf4` | `0xb1c` | **`-0xd8`** |
| `__DATA.__objc_selrefs` | `0x98` | `0x28` | **`-0x70`** |
| `__TEXT.__swift5_capture` | `0x1e0` | `0x17c` | **`-0x64`** |
| `__TEXT.__swift5_proto` | `0xfc` | `0xa4` | **`-0x58`** |
| `__TEXT.__swift_as_cont` | `0x8c` | `0x44` | **`-0x48`** |
| `__TEXT.__swift_as_entry` | `0x80` | `0x38` | **`-0x48`** |
| `__TEXT.__swift_as_ret` | `0x84` | `0x3c` | **`-0x48`** |
| `__TEXT.__objc_methtype` | `0x75` | `0x30` | **`-0x45`** |
| `__DATA.__common` | `0x120` | `0xf0` | **`-0x30`** |
| `__TEXT.__swift5_builtin` | `0x50` | `0x3c` | **`-0x14`** |
| `__TEXT.__swift5_types` | `0xdc` | `0xc8` | **`-0x14`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__swift5_entry`

### Other Changes

```diff

-470.30.6.14.34
+470.31.6.16.26

-  - /System/Library/PrivateFrameworks/SPOwner.framework/SPOwner

-  Functions: 952
-  Symbols:   192
-  CStrings:  121
+  Functions: 769
+  Symbols:   178
+  CStrings:  88
Symbols:
+ __swiftEmptySetSingleton
+ _objc_release_x25
+ _objc_retain_x26
+ _objc_retain_x27
+ _swift_setDeallocating
- _OBJC_CLASS_$_NSError
- _OBJC_CLASS_$_SPApplicationBeacon
- _OBJC_CLASS_$_SPOwnerSession
- _OBJC_CLASS_$_SPSimpleBeaconContext
- _SPBeaconTypeAccessory
- _SPBeaconTypeDurian
- __Block_copy
- __Block_release
- _bzero
- _objc_release
- _objc_release_x28
- _objc_retain_x23
- _swift_arrayInitWithCopy
- _swift_arrayInitWithTakeBackToFront
- _swift_arrayInitWithTakeFrontToBack
- _swift_release_x12
- _swift_retain_x2
- _swift_retain_x20
- _swift_unknownObjectRelease
CStrings:
- "%s"
- "%s - appBeacons.count: %{public}ld"
- "%s - compactMap %s"
- "%s - did receive fetchWithOptions: %s"
- "%s - error: %{public}@"
- "%s - ids: %{public}s"
- "%s - result: %s"
- "%s - will call fetchWithOptions: %s"
- "Fatal error"
- "FindMyWidgetItems/WidgetItemEntity.swift"
- "ITEM_ENTITY_TITLE"
- "WidgetItemEntityQuery"
- "batteryLevel"
- "com.apple.findmy"
- "com.findmy.itementity"
- "connected"
- "customDefaultResult()"
- "destination"
- "fetchModels(options:)"
- "fmipItemContext"
- "fmipItemContextForBeaconUUIDs:"
- "identifier"
- "initWithDomain:code:userInfo:"
- "isAppleAudioAccessory"
- "name"
- "owner"
- "privateApplicationBeacons(context:)"
- "role"
- "roleEmoji"
- "startUpdatingApplicationBeaconsWithContext:collectionDifference:completion:"
- "type"
- "v20@?0B8@\"NSError\"12"
- "v24@?0@\"NSOrderedCollectionDifference\"8@\"NSError\"16"
```
