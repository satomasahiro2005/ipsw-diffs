## abmlite

> `/usr/bin/abmlite`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1c3d4` | `0x1c960` | **`+0x58c`** |
| `__TEXT.__gcc_except_tab` | `0x20bc` | `0x20f4` | **`+0x38`** |
| `__DATA_CONST.__const` | `0x520` | `0x540` | **`+0x20`** |
| `__DATA.__bss` | `0x48` | `0x58` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x2d8` | `0x2e8` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0x8b0` | `0x8c0` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x470` | `0x478` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x560` | `0x568` | **`+0x8`** |
| `__TEXT.__cstring` | `0xa53` | `0xa59` | **`+0x6`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__TEXT.__init_offsets`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-1563.0.0.0.0
+1570.0.0.0.0

-  Functions: 173
-  Symbols:   356
-  CStrings:  162
+  Functions: 175
+  Symbols:   360
+  CStrings:  163
Symbols:
+ __ZN12capabilities5trace22supportedModemFeaturesEv
+ __ZN12capabilities5traceanENS0_12ModemFeatureES1_
+ __ZN3abm18kTraceMultiChannelE
+ __ZN3abm23kKeyMultiChannelEnabledE
CStrings:
+ "v8@?0"
```
