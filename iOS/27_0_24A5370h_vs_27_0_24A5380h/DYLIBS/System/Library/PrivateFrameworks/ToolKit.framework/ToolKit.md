## ToolKit

> `/System/Library/PrivateFrameworks/ToolKit.framework/ToolKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA.__bss` | `0x998c0` | `0x93640` | **`-0x6280`** |
| `__DATA_DIRTY.__bss` | `0x41100` | `0x47380` | **`+0x6280`** |
| `__DATA_DIRTY.__data` | `0x10c68` | `0x12c68` | **`+0x2000`** |
| `__DATA.__data` | `0x10ff0` | `0xfb90` | **`-0x1460`** |
| `__AUTH.__data` | `0x3428` | `0x28b8` | **`-0xb70`** |
| `__TEXT.__text` | `0x4cd7d8` | `0x4cdab0` | **`+0x2d8`** |
| `__TEXT.__const` | `0x7ac68` | `0x7acd8` | **`+0x70`** |
| `__DATA.__common` | `0x988` | `0x920` | **`-0x68`** |
| `__DATA_DIRTY.__common` | `0x9e0` | `0xa48` | **`+0x68`** |
| `__AUTH.__objc_data` | `0x98` | `0x48` | **`-0x50`** |
| `__DATA_DIRTY.__objc_data` | `0x360` | `0x3b0` | **`+0x50`** |
| `__TEXT.__cstring` | `0x9254` | `0x9224` | **`-0x30`** |
| `__TEXT.__swift5_reflstr` | `0x9377` | `0x93a7` | **`+0x30`** |
| `__TEXT.__swift5_typeref` | `0x1467e` | `0x146a8` | **`+0x2a`** |
| `__TEXT.__swift5_fieldmd` | `0x13d14` | `0x13d2c` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x5a0` | `0x5b4` | **`+0x14`** |
| `__TEXT.__eh_frame` | `0x32848` | `0x32838` | **`-0x10`** |
| `__TEXT.__swift5_mpenum` | `0x328` | `0x330` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0xa78` | `0xa80` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1aaf0` | `0x1aaf8` | **`+0x8`** |

### Other Changes

```diff

-5028.0.21.0.0
+5032.5.0.0.0

-  Functions: 44656
-  Symbols:   10287
-  CStrings:  1711
+  Functions: 44650
+  Symbols:   10286
+  CStrings:  1710
Symbols:
+ _get_enum_tag_for_layout_string 7ToolKit0A15InvocationErrorO
+ _symbolic SS16bundleIdentifier_SS06actionB0t
- _get_type_metadata 15Synchronization5MutexVy7ToolKit0C8DatabaseC0cE6WriterC14HeartbeatState33_9B7CB6459158BF139B64DFA69282C2EFLLVG noncopyable
- _swift_runtimeSupportsNoncopyableTypes
- _swift_willThrowTypedImpl
CStrings:
- "ToolKit/ToolInvocation+LinkServices.swift"
```
