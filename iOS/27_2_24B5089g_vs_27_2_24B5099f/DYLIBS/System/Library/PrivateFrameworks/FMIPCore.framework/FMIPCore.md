## FMIPCore

> `/System/Library/PrivateFrameworks/FMIPCore.framework/FMIPCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1d269c` | `0x1d2ebc` | **`+0x820`** |
| `__DATA.__bss` | `0x12680` | `0x12780` | **`+0x100`** |
| `__AUTH_CONST.__objc_const` | `0xf1e8` | `0xf270` | **`+0x88`** |
| `__TEXT.__const` | `0x135bc` | `0x13614` | **`+0x58`** |
| `__TEXT.__eh_frame` | `0x46c0` | `0x4718` | **`+0x58`** |
| `__AUTH.__objc_data` | `0x1208` | `0x11b8` | **`-0x50`** |
| `__TEXT.__swift5_reflstr` | `0x5481` | `0x54d1` | **`+0x50`** |
| `__AUTH.__data` | `0x5340` | `0x5378` | **`+0x38`** |
| `__TEXT.__constg_swiftt` | `0x68d0` | `0x6904` | **`+0x34`** |
| `__TEXT.__swift5_typeref` | `0x42ed` | `0x4317` | **`+0x2a`** |
| `__AUTH_CONST.__const` | `0x129a1` | `0x129c9` | **`+0x28`** |
| `__DATA_DIRTY.__data` | `0x59c8` | `0x59e8` | **`+0x20`** |
| `__TEXT.__cstring` | `0x54cc` | `0x54ec` | **`+0x20`** |
| `__TEXT.__oslogstring` | `0xab30` | `0xab10` | **`-0x20`** |
| `__TEXT.__swift5_fieldmd` | `0x5e44` | `0x5e5c` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x4dc8` | `0x4dd8` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x1610` | `0x1618` | **`+0x8`** |
| `__DATA.__common` | `0x388` | `0x380` | **`-0x8`** |
| `__TEXT.__swift5_proto` | `0xe2c` | `0xe34` | **`+0x8`** |

### Other Changes

```diff

-470.31.6.16.30
+470.31.6.16.39

-  Functions: 8828
+  Functions: 8840

-  CStrings:  1416
+  CStrings:  1417
CStrings:
+ "FMIPDemoDataInjector: Unable to find `host` device."
+ "FMIPDemoInteractionController: Received %s for demo device, which is unsupported in demo mode."
+ "deprecationWarning"
- "FMIPDemoDataInjector: Unable to find `host` device, returning ONLY fake data."
- "FMIPDemoInteractionController: Received %s for non-host device, which is unsupported in demo mode."
```
