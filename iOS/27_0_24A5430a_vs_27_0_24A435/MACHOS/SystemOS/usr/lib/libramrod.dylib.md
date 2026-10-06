## libramrod.dylib

> `/usr/lib/libramrod.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xeedb4` | `0xf0a70` | **`+0x1cbc`** |
| `__TEXT.__cstring` | `0x2bbc5` | `0x2be81` | **`+0x2bc`** |
| `__TEXT.__oslogstring` | `0xac8` | `0xb92` | **`+0xca`** |
| `__AUTH_CONST.__cfstring` | `0xc3c0` | `0xc480` | **`+0xc0`** |
| `__DATA.__bss` | `0x8a0` | `0x948` | **`+0xa8`** |
| `__AUTH_CONST.__const` | `0x2068` | `0x20b8` | **`+0x50`** |
| `__TEXT.__auth_stubs` | `0x2af0` | `0x2b40` | **`+0x50`** |
| `__TEXT.__gcc_except_tab` | `0xb2c` | `0xb6c` | **`+0x40`** |
| `__AUTH_CONST.__auth_got` | `0x1580` | `0x15a8` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x1e88` | `0x1eb0` | **`+0x28`** |
| `__TEXT.__objc_stubs` | `0x2900` | `0x2920` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0x29f1` | `0x29fe` | **`+0xd`** |
| `__DATA_CONST.__objc_selrefs` | `0xcd0` | `0xcd8` | **`+0x8`** |
| `__TEXT.__eh_frame` | `0x378` | `0x380` | **`+0x8`** |

### Same-size Content Changes

- `__AUTH.__data`
- `__AUTH.__objc_data`
- `__AUTH_CONST.__objc_const`
- `__AUTH_CONST.__objc_intobj`
- `__DATA.__data`
- `__DATA.__objc_classrefs`
- `__DATA.__objc_superrefs`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__TEXT.__const`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-  Functions: 2862
-  Symbols:   1886
-  CStrings:  6360
+  Functions: 2871
+  Symbols:   1892
+  CStrings:  6386
Symbols:
+ __ramrod_device_supports_provisional_nonce_rollback
+ _notify_cancel
+ _notify_get_state
+ _notify_post
+ _notify_register_check
+ _notify_register_dispatch
CStrings:
+ "%@/bic_sec"
+ "%@/genx_history"
+ "%@/history_sec"
+ "--set-provisional"
+ "--slot"
+ "ApplePearlExclaveSEPDriver"
+ "Generating reference frames info record...\n"
+ "IODeviceTree:/product/display%d"
+ "Reference frames info record written to %s\n"
+ "ReferenceFramesSetInfo, index: %zu, type: %d, count: %d, size: %d\n"
+ "Verifying new reference frames info record...\n"
+ "com.apple.pearld.check_secure_streaming"
+ "com.apple.pearld.ready"
+ "ctx[%d]: display \"%s\" (display index %d)\n"
+ "display%d: display-boot-rotation = %u\n"
+ "display%d: display-rotation = %u\n"
+ "display-boot-rotation"
+ "display-rotation"
+ "mutableBytes"
+ "notifyResult == 0"
+ "outDataSize <= signedRefFramesInfoRecordData.length"
+ "pearldReady"
+ "reference-info-record.DAT"
+ "requestData"
+ "sema"
+ "signedRefFramesInfoRecordData"
```
