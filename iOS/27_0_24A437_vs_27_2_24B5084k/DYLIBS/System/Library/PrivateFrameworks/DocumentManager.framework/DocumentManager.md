## DocumentManager

> `/System/Library/PrivateFrameworks/DocumentManager.framework/DocumentManager`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x338fc` | `0x33a80` | **`+0x184`** |
| `__TEXT.__oslogstring` | `0x33c8` | `0x348c` | **`+0xc4`** |
| `__DATA_CONST.__const` | `0x1730` | `0x1708` | **`-0x28`** |
| `__AUTH_CONST.__cfstring` | `0x4260` | `0x4280` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x2a70` | `0x2a90` | **`+0x20`** |
| `__TEXT.__cstring` | `0x4dde` | `0x4df6` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x630` | `0x638` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0xdc0` | `0xdb8` | **`-0x8`** |
| `__TEXT.__gcc_except_tab` | `0x8ac` | `0x8b0` | **`+0x4`** |

### Other Changes

```diff

-401.0.0.0.0
+401.1.5.0.0

-  Functions: 1251
-  Symbols:   2238
-  CStrings:  843
+  Functions: 1253
+  Symbols:   2237
+  CStrings:  846
Symbols:
+ GCC_except_table52
+ GCC_except_table60
+ GCC_except_table76
+ _OBJC_CLASS_$_DOCStateRestorationCrashGuard
- GCC_except_table54
- GCC_except_table61
- ___38-[DOCSmartFolderDatabase initWithURL:]_block_invoke
- ___41-[DOCSmartFolderDatabase purgeOldEntries]_block_invoke
- ___block_descriptor_48_e8_32s_e5_v8?0ls32l8
CStrings:
+ "%s: Skipping the most recent interface state because repeated launch crashes suppressed state restoration"
+ "%s: Skipping the saved state because repeated launch crashes suppressed state restoration"
+ "accessibilityIdentifier"
```
