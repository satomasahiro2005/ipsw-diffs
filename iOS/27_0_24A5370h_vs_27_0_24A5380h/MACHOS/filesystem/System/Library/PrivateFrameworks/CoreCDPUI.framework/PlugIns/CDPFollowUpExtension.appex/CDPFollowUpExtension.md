## CDPFollowUpExtension

> `/System/Library/PrivateFrameworks/CoreCDPUI.framework/PlugIns/CDPFollowUpExtension.appex/CDPFollowUpExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x61dc` | `0x62b0` | **`+0xd4`** |
| `__TEXT.__oslogstring` | `0xe79` | `0xed0` | **`+0x57`** |
| `__TEXT.__gcc_except_tab` | `0x19c` | `0x1bc` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x1480` | `0x14a0` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0x688` | `0x690` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x238` | `0x240` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1d0` | `0x1d8` | **`+0x8`** |
| `__TEXT.__objc_methname` | `0x181e` | `0x1825` | **`+0x7`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-442.0.0.0.0
+444.0.0.0.0

-  Functions: 145
-  Symbols:   155
-  CStrings:  389
+  Functions: 146
+  Symbols:   156
+  CStrings:  391
Symbols:
+ _CDPFollowUpItemUserInfoKeyTelemetryFlowID
Functions:
~ sub_1000015a4 : 2204 -> 2332
+ sub_100006a00
CStrings:
+ "CDPFollowUpViewController: No persisted telemetryFlowID for item %@; minted fresh UUID"
+ "length"
```
