## callverificationd

> `/usr/libexec/callverificationd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x145e4` | `0x12d54` | **`-0x1890`** |
| `__TEXT.__eh_frame` | `0xc38` | `0x998` | **`-0x2a0`** |
| `__DATA.__bss` | `0x2300` | `0x2180` | **`-0x180`** |
| `__TEXT.__objc_methtype` | `0x41b` | `0x4f8` | **`+0xdd`** |
| `__DATA.__data` | `0x700` | `0x7d0` | **`+0xd0`** |
| `__TEXT.__unwind_info` | `0x800` | `0x758` | **`-0xa8`** |
| `__TEXT.__const` | `0x1328` | `0x128c` | **`-0x9c`** |
| `__TEXT.__objc_methname` | `0x825` | `0x899` | **`+0x74`** |
| `__DATA_CONST.__const` | `0x1320` | `0x12c0` | **`-0x60`** |
| `__TEXT.__objc_stubs` | `0x4e0` | `0x540` | **`+0x60`** |
| `__TEXT.__oslogstring` | `0x57a` | `0x52a` | **`-0x50`** |
| `__TEXT.__swift5_typeref` | `0x468` | `0x4b3` | **`+0x4b`** |
| `__DATA.__objc_const` | `0x4a8` | `0x4f0` | **`+0x48`** |
| `__TEXT.__swift5_fieldmd` | `0x4ec` | `0x4ac` | **`-0x40`** |
| `__TEXT.__objc_methlist` | `0x28c` | `0x2c4` | **`+0x38`** |
| `__TEXT.__objc_classname` | `0xd4` | `0x103` | **`+0x2f`** |
| `__DATA.__objc_selrefs` | `0x280` | `0x2a8` | **`+0x28`** |
| `__TEXT.__constg_swiftt` | `0x414` | `0x3f0` | **`-0x24`** |
| `__DATA_CONST.__objc_protolist` | `0x20` | `0x40` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0x254` | `0x274` | **`+0x20`** |
| `__TEXT.__swift_as_cont` | `0x68` | `0x4c` | **`-0x1c`** |
| `__DATA_CONST.__got` | `0x1a8` | `0x190` | **`-0x18`** |
| `__DATA_CONST.__objc_protorefs` | `0x10` | `0x20` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0xe40` | `0xe50` | **`+0x10`** |
| `__TEXT.__cstring` | `0x335` | `0x325` | **`-0x10`** |
| `__TEXT.__swift5_proto` | `0x118` | `0x10c` | **`-0xc`** |
| `__TEXT.__swift_as_ret` | `0x34` | `0x28` | **`-0xc`** |
| `__DATA_CONST.__auth_got` | `0x728` | `0x730` | **`+0x8`** |
| `__DATA_CONST.__auth_ptr` | `0x1a0` | `0x198` | **`-0x8`** |
| `__TEXT.__swift5_types` | `0x6c` | `0x68` | **`-0x4`** |
| `__TEXT.__swift_as_entry` | `0x24` | `0x20` | **`-0x4`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`

### Other Changes

```diff

-7.0.0.0.0
+9.0.0.0.0

-  Functions: 750
-  Symbols:   365
-  CStrings:  209
+  Functions: 697
+  Symbols:   362
+  CStrings:  215
Symbols:
+ _$ss11AnyHashableV13_rawHashValue4seedS2i_tF
+ _$ss11AnyHashableV2eeoiySbAB_ABtFZ
+ _$ss11AnyHashableVyABxcSHRzlufC
+ _OBJC_CLASS_$_AKGlobalConfig
- _$sBbWV
- _$sSSSesWP
- _$sSayxGSesSeRzlMc
- _$sSiN
- _$sSiSzsMc
- _$sSzsE11descriptionSSvg
- _$ss22KeyedDecodingContainerV6decode_6forKeyS2im_xtKF
CStrings:
+ "@24@0:8@\"NSCoder\"16"
+ "NSCoding"
+ "NSSecureCoding"
+ "POST request to %{public}s completed with status code 200; txnid: %{public}s"
+ "POST request to %{public}s failed with status code %{public}ld; txnid: %{public}s"
+ "TB,R"
+ "allHeaderFields"
+ "encodeWithCoder:"
+ "fetchGlobalConfigUsingCachePolicy:completion:"
+ "sharedInstance"
+ "supportPhoneNumbers"
+ "supportsSecureCoding"
+ "v24@0:8@\"NSCoder\"16"
+ "v24@?0@\"NSDictionary\"8@\"NSError\"16"
- "Callback request failed with status code: %{public}ld"
- "Config request failed with status code: %ld"
- "GET request to %{public}s completed with status %{public}s"
- "Making GET request to endpoint: %{public}s"
- "Response data: %{public}s"
- "cmd"
- "configUrlKey"
- "supportNumberList"
```
