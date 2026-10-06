## SwiftTLS

> `/System/Library/PrivateFrameworks/SwiftTLS.framework/SwiftTLS`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xe1ef8` | `0xe06cc` | **`-0x182c`** |
| `__TEXT.__oslogstring` | `0x393e` | `0x39de` | **`+0xa0`** |
| `__TEXT.__eh_frame` | `0x3260` | `0x31f8` | **`-0x68`** |
| `__TEXT.__cstring` | `0x11b1` | `0x1161` | **`-0x50`** |
| `__AUTH_CONST.__auth_got` | `0x8c8` | `0x898` | **`-0x30`** |
| `__AUTH_CONST.__const` | `0x2f08` | `0x2f30` | **`+0x28`** |
| `__TEXT.__swift5_fieldmd` | `0x2d0c` | `0x2d34` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x1960` | `0x1988` | **`+0x28`** |
| `__TEXT.__constg_swiftt` | `0x1834` | `0x1854` | **`+0x20`** |
| `__DATA.__data` | `0xb48` | `0xb30` | **`-0x18`** |
| `__TEXT.__const` | `0x7294` | `0x7284` | **`-0x10`** |
| `__TEXT.__swift5_capture` | `0x70` | `0x80` | **`+0x10`** |
| `__TEXT.__swift5_reflstr` | `0x27b3` | `0x27c3` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `0xe3e` | `0xe3a` | **`-0x4`** |

### Other Changes

```diff

-171.0.8.0.0
+171.0.14.0.0

-  Functions: 2302
-  Symbols:   710
-  CStrings:  385
+  Functions: 2315
+  Symbols:   706
+  CStrings:  386
Symbols:
+ ___swift_get_extra_inhabitant_index.66Tm
+ ___swift_store_extra_inhabitant_index.67Tm
+ _symbolic _____ 8SwiftTLS11InputBufferV
+ _symbolic _____ s7RawSpanV
- ___swift_get_extra_inhabitant_index.57Tm
- ___swift_store_extra_inhabitant_index.58Tm
- _swift_release_x28
- _swift_retain_x28
- _swift_retain_x8
- _swift_unexpectedError
- _symbolic SnySiG
- _symbolic ______p s19_HasContiguousBytesP
CStrings:
+ "could not generate ephemeral key for negotiated group: %hu"
+ "handshake processing (%ld bytes)"
+ "saving unprocessed network data (%ld bytes)"
- "SwiftTLS/Extensions+KeyShare.swift"
- "SwiftTLS/KeyExchange.swift"
```
