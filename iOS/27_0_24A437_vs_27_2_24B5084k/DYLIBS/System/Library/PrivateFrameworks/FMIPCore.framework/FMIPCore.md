## FMIPCore

> `/System/Library/PrivateFrameworks/FMIPCore.framework/FMIPCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1d0058` | `0x1d1610` | **`+0x15b8`** |
| `__DATA.__bss` | `0x13800` | `0x12580` | **`-0x1280`** |
| `__TEXT.__const` | `0x13ebc` | `0x1352c` | **`-0x990`** |
| `__AUTH_CONST.__const` | `0x12f59` | `0x128c1` | **`-0x698`** |
| `__AUTH.__data` | `0x4fb8` | `0x5340` | **`+0x388`** |
| `__TEXT.__eh_frame` | `0x49e8` | `0x46c0` | **`-0x328`** |
| `__TEXT.__swift5_fieldmd` | `0x6100` | `0x5e1c` | **`-0x2e4`** |
| `__TEXT.__unwind_info` | `0x4f78` | `0x4db8` | **`-0x1c0`** |
| `__AUTH_CONST.__auth_got` | `0x14a8` | `0x1610` | **`+0x168`** |
| `__DATA.__data` | `0x1af0` | `0x19a8` | **`-0x148`** |
| `__TEXT.__constg_swiftt` | `0x69e8` | `0x68b4` | **`-0x134`** |
| `__TEXT.__swift5_reflstr` | `0x5571` | `0x5481` | **`-0xf0`** |
| `__TEXT.__swift5_typeref` | `0x43c9` | `0x42df` | **`-0xea`** |
| `__TEXT.__cstring` | `0x555c` | `0x54bc` | **`-0xa0`** |
| `__TEXT.__swift5_proto` | `0xeb8` | `0xe24` | **`-0x94`** |
| `__TEXT.__oslogstring` | `0xaa50` | `0xaad0` | **`+0x80`** |
| `__AUTH_CONST.__objc_const` | `0xf250` | `0xf1e8` | **`-0x68`** |
| `__AUTH.__objc_data` | `0x11b8` | `0x1208` | **`+0x50`** |
| `__TEXT.__swift5_types` | `0x600` | `0x5d4` | **`-0x2c`** |
| `__TEXT.__swift5_assocty` | `0xd50` | `0xd38` | **`-0x18`** |
| `__DATA.__common` | `0x380` | `0x388` | **`+0x8`** |
| `__DATA_CONST.__const` | `0x448` | `0x450` | **`+0x8`** |

### Other Changes

```diff

-470.30.6.14.34
+470.31.6.16.26

+  - /System/Library/PrivateFrameworks/FindMyCore.framework/FindMyCore

+  - /usr/lib/swift/libswiftIntents.dylib

+  - /usr/lib/swift/libswift_StringProcessing.dylib

-  Functions: 8929
-  Symbols:   423
-  CStrings:  1422
+  Functions: 8812
+  Symbols:   424
+  CStrings:  1414
Symbols:
+ __swift_FORCE_LOAD_$_swiftIntents
CStrings:
+ "FMIPDevice:\n    -- id: %s,\n    -- name: %s,\n    -- baId: %s\n    -- isAccessory: %{bool}d\n    -- onlineLocation: %s\n    -- offlineLocation: %s\n    -- bestLocation: %s\n    -- itemGroup: %s\n    -- itemGroupItemsId: %s\n    -- deviceConnectedType: %s\n    -- deviceAssociatedWithBeacon: %s\n    -- productCapabilities: %ld"
+ "FMIPManager: Failed to instantiate demo beacon refreshing controller due to error: %s"
+ "companionDeviceIdentifier"
- "FMIPDevice:\n    -- id: %s,\n    -- name: %s,\n    -- baId: %s\n    -- isAccessory: %{bool}d\n    -- onlineLocation: %s\n    -- offlineLocation: %s\n    -- bestLocation: %s\n    -- itemGroup: %s\n    -- itemGroupItemsId: %s\n    -- deviceConnectedType: %s\n    -- deviceAssociatedWithBeacon: %s"
- "MacBookPro16_1-spacegray"
- "airpods"
- "categoryTemplate"
- "iMacPro"
- "iMacPro1_1-silver"
- "iPad"
- "iPhone"
- "iphone11ProMax-1-2-0"
- "macbookPro"
- "watch"
```
