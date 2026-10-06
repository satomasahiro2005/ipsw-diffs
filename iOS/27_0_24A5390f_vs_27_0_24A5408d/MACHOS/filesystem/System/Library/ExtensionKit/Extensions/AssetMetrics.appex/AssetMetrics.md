## AssetMetrics

> `/System/Library/ExtensionKit/Extensions/AssetMetrics.appex/AssetMetrics`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x48ec` | `0x3c7c` | **`-0xc70`** |
| `__DATA.__bss` | `0x780` | `0x500` | **`-0x280`** |
| `__TEXT.__auth_stubs` | `0x6f0` | `0x590` | **`-0x160`** |
| `__TEXT.__const` | `0x4fa` | `0x3ca` | **`-0x130`** |
| `__TEXT.__oslogstring` | `0x1b5` | `0xea` | **`-0xcb`** |
| `__DATA_CONST.__const` | `0x320` | `0x258` | **`-0xc8`** |
| `__DATA_CONST.__auth_got` | `0x378` | `0x2c8` | **`-0xb0`** |
| `__TEXT.__eh_frame` | `0x340` | `0x290` | **`-0xb0`** |
| `__TEXT.__unwind_info` | `0x268` | `0x1f8` | **`-0x70`** |
| `__DATA_CONST.__auth_ptr` | `0x1e8` | `0x190` | **`-0x58`** |
| `__TEXT.__swift5_typeref` | `0x172` | `0x142` | **`-0x30`** |
| `__TEXT.__swift5_reflstr` | `0x96` | `0x68` | **`-0x2e`** |
| `__TEXT.__cstring` | `0xcd` | `0xa2` | **`-0x2b`** |
| `__DATA.__data` | `0x200` | `0x1d8` | **`-0x28`** |
| `__TEXT.__constg_swiftt` | `0xec` | `0xd0` | **`-0x1c`** |
| `__TEXT.__swift5_fieldmd` | `0xcc` | `0xb0` | **`-0x1c`** |
| `__DATA_CONST.__got` | `0x88` | `0x70` | **`-0x18`** |
| `__TEXT.__swift5_assocty` | `0x30` | `0x18` | **`-0x18`** |
| `__TEXT.__swift5_proto` | `0x40` | `0x2c` | **`-0x14`** |
| `__TEXT.__swift_as_cont` | `0x20` | `0x18` | **`-0x8`** |
| `__TEXT.__swift5_types` | `0x14` | `0x10` | **`-0x4`** |
| `__TEXT.__swift_as_ret` | `0x20` | `0x1c` | **`-0x4`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift_as_entry`

### Other Changes

```diff

-3600.5.1.0.0
+3600.6.1.0.0

-  - /System/Library/PrivateFrameworks/AssistantServices.framework/AssistantServices

-  Functions: 168
-  Symbols:   93
-  CStrings:  17
+  Functions: 126
+  Symbols:   89
+  CStrings:  13
Symbols:
+ _objc_release_x26
- _AFIsHorseman
- __swift_stdlib_bridgeErrorToNSError
- _objc_release_x23
- _swift_allocBox
- _swift_release_x19
CStrings:
+ "AssetMetrics are disabled"
- "AssetMetrics AND Assistant/dictation are enabled. Continuing."
- "Hourly task running on HomePod. Not continuing for resource reasons."
- "Siri Assistant or Dictation disabled. Not continuing."
- "dependenciesUnavailableError"
- "unexpected error throws: %@"
```
