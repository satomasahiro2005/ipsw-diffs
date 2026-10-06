## mediaanalysisd-generation

> `/System/Library/PrivateFrameworks/MediaAnalysisGeneration.framework/XPCServices/mediaanalysisd-generation.xpc/mediaanalysisd-generation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7354` | `0x771c` | **`+0x3c8`** |
| `__TEXT.__auth_stubs` | `0xad0` | `0xb60` | **`+0x90`** |
| `__DATA_CONST.__const` | `0x2e0` | `0x360` | **`+0x80`** |
| `__DATA_CONST.__auth_got` | `0x590` | `0x5d8` | **`+0x48`** |
| `__TEXT.__objc_stubs` | `0x660` | `0x6a0` | **`+0x40`** |
| `__DATA.__bss` | `0x1b0` | `0x1e0` | **`+0x30`** |
| `__TEXT.__cstring` | `0x2cd` | `0x2fd` | **`+0x30`** |
| `__TEXT.__oslogstring` | `0x493` | `0x4c3` | **`+0x30`** |
| `__TEXT.__objc_methname` | `0x66b` | `0x692` | **`+0x27`** |
| `__TEXT.__objc_methlist` | `0x234` | `0x254` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0x46c` | `0x488` | **`+0x1c`** |
| `__DATA.__objc_selrefs` | `0x258` | `0x268` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x2b0` | `0x2c0` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x200` | `0x208` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-435.60.2.11.2
+435.65.2.0.0

-  Functions: 127
-  Symbols:   191
-  CStrings:  168
+  Functions: 135
+  Symbols:   201
+  CStrings:  172
Symbols:
+ __dispatch_source_type_timer
+ _dispatch_resume
+ _dispatch_source_cancel
+ _dispatch_source_create
+ _dispatch_source_set_event_handler
+ _dispatch_source_set_timer
+ _dispatch_time
+ _exit
+ _objc_release_x1
+ _os_transaction_create
CStrings:
+ "[MADGenerationXPCService] Idle timer fired – exiting"
+ "cancelIdleExitTimer"
+ "com.apple.mediaanalysisd-generation.idle-exit"
+ "startIdleExitTimer"
```
