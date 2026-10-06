## BackgroundShortcutRunner

> `/System/Library/PrivateFrameworks/WorkflowKit.framework/XPCServices/BackgroundShortcutRunner.xpc/BackgroundShortcutRunner`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x876dc` | `0x8887c` | **`+0x11a0`** |
| `__TEXT.__auth_stubs` | `0x32b0` | `0x33b0` | **`+0x100`** |
| `__TEXT.__oslogstring` | `0x114e` | `0x11fe` | **`+0xb0`** |
| `__DATA_CONST.__auth_got` | `0x1968` | `0x19e8` | **`+0x80`** |
| `__TEXT.__unwind_info` | `0x1470` | `0x14d8` | **`+0x68`** |
| `__TEXT.__eh_frame` | `0x46e8` | `0x4740` | **`+0x58`** |
| `__DATA_CONST.__got` | `0xe38` | `0xe78` | **`+0x40`** |
| `__TEXT.__objc_stubs` | `0x2060` | `0x2080` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0x4bc` | `0x4dc` | **`+0x20`** |
| `__DATA.__data` | `0x12f8` | `0x1308` | **`+0x10`** |
| `__TEXT.__objc_methname` | `0x26cf` | `0x26df` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x4e0` | `0x4ec` | **`+0xc`** |
| `__TEXT.__swift5_typeref` | `0xf36` | `0xf42` | **`+0xc`** |
| `__DATA.__objc_selrefs` | `0xa60` | `0xa68` | **`+0x8`** |
| `__TEXT.__swift5_capture` | `0x9e4` | `0x9ec` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0x308` | `0x30c` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0x178` | `0x17c` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_entry`

### Other Changes

```diff

-5034.0.12.100.0
+5037.103.100.0.0

-  Functions: 2658
+  Functions: 2659

-  CStrings:  694
+  CStrings:  697
CStrings:
+ "supportedModes"
+ "transformAction: failed to decode INIntent from intentData"
+ "transformAction: failed to serialize parameters for intent %s"
+ "transformAction: no bundle identifier on INAppIntent %s"
+ "transformAction: no replacement action for donated intent %s, launchId=%s"
- "Could not create filled action %s"
- "Could not find bundle identifier on intent"
```
