## ValidUpdater

> `/usr/libexec/ValidUpdater`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x60dc` | `0x690c` | **`+0x830`** |
| `__DATA_CONST.__const` | `0x428` | `0x518` | **`+0xf0`** |
| `__TEXT.__auth_stubs` | `0x870` | `0x900` | **`+0x90`** |
| `__TEXT.__eh_frame` | `0x530` | `0x5c0` | **`+0x90`** |
| `__TEXT.__const` | `0x15a` | `0x1d4` | **`+0x7a`** |
| `__TEXT.__swift5_capture` | `0x1c8` | `0x214` | **`+0x4c`** |
| `__DATA_CONST.__auth_got` | `0x440` | `0x488` | **`+0x48`** |
| `__TEXT.__unwind_info` | `0x238` | `0x278` | **`+0x40`** |
| `__TEXT.__constg_swiftt` | `0x48` | `0x74` | **`+0x2c`** |
| `__TEXT.__objc_methname` | `0x230` | `0x254` | **`+0x24`** |
| `__DATA_CONST.__got` | `0xe0` | `0x100` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x160` | `0x180` | **`+0x20`** |
| `__TEXT.__swift5_fieldmd` | `0x10` | `0x2c` | **`+0x1c`** |
| `__TEXT.__swift5_typeref` | `0xf4` | `0x10f` | **`+0x1b`** |
| `__TEXT.__swift5_builtin` | `—` | `0x14` | **`+0x14`** |
| `__DATA.__data` | `0x1e0` | `0x1f0` | **`+0x10`** |
| `__TEXT.__objc_methtype` | `0xd4` | `0xdd` | **`+0x9`** |
| `__TEXT.__swift5_reflstr` | `—` | `0x9` | **`+0x9`** |
| `__DATA.__objc_selrefs` | `0xf8` | `0x100` | **`+0x8`** |
| `__DATA_CONST.__auth_ptr` | `0x40` | `0x48` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x24` | `0x2c` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x18` | `0x20` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x4` | `0x8` | **`+0x4`** |
| `__TEXT.__swift_as_cont` | `0x3c` | `0x40` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_entry`

### Other Changes

```diff

-134.0.7.0.1
+134.0.15.0.0

-  Functions: 113
-  Symbols:   182
-  CStrings:  73
+  Functions: 132
+  Symbols:   195
+  CStrings:  75
Symbols:
+ _$s11SwiftCRLite15BGTaskCompleterC11setOnExpireyyyxYaYbcSgF
+ _$s11SwiftCRLite15BGTaskCompleterC16handleExpirationyyxYaF
+ _$s11SwiftCRLite15BGTaskCompleterC16handleExpirationyyxYaFTu
+ _$s11SwiftCRLite15BGTaskCompleterC5label11onCompletedACyxGSS_yyYbctcfc
+ _$s11SwiftCRLite15BGTaskCompleterC8completeyyF
+ _$s11SwiftCRLite15BGTaskCompleterCMn
+ _$s11SwiftCRLite15ValidDaemonCoreC15onBGTaskExpired10reasonMaskySo028BGSystemTaskExpirationReasonJ0V_tYaFTjTu
+ _$sBi64_WV
+ _$sSS11utf8CStrings15ContiguousArrayVys4Int8VGvg
+ _objc_retain_x26
+ _swift_bridgeObjectRetain
+ _swift_getForeignTypeMetadata
+ _swift_release_x22
+ _swift_release_x28
- _objc_retain_x22
CStrings:
+ "setExpirationHandlerWithReasonMask:"
+ "v16@?0Q8"
```
