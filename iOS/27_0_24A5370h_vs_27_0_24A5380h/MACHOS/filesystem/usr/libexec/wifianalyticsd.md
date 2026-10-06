## wifianalyticsd

> `/usr/libexec/wifianalyticsd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__objc_methname` | `0xe0cf` | `0xe12f` | **`+0x60`** |
| `__TEXT.__objc_stubs` | `0x8e00` | `0x8e60` | **`+0x60`** |
| `__DATA_CONST.__got` | `0x458` | `0x478` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0x2ee0` | `0x2ef8` | **`+0x18`** |
| `__TEXT.__text` | `0x97cf8` | `0x97d04` | **`+0xc`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__cstring`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_typeref`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-825.53.0.0.0
+825.56.0.0.0

-  Symbols:   553
-  CStrings:  6225
+  Symbols:   554
+  CStrings:  6228
Symbols:
+ _OBJC_CLASS_$_WAModelTemplateLRU
Functions:
~ sub_100016b24 : 496 -> 468
~ sub_10008a5bc -> sub_10008a5a0 : 1204 -> 1244
CStrings:
+ "\"WiFiAnalytics_executables-825.56\""
+ "Jul  1 2026 23:27:17"
+ "WiFiAnalytics_executables-825.56"
+ "WiFiAnalytics_executables-825.56 Jul  1 2026 23:27:16"
+ "getMessageInstanceForKey:andGroupType:encodedSizeOut:"
+ "initWithBudgetBytes:"
+ "setTemplate:forKey:encodedSize:"
+ "templateForKey:"
- "\"WiFiAnalytics_executables-825.53\""
- "Jun 16 2026 21:52:44"
- "WiFiAnalytics_executables-825.53"
- "WiFiAnalytics_executables-825.53 Jun 16 2026 21:52:40"
- "getMessageInstanceForKey:andGroupType:"
```
