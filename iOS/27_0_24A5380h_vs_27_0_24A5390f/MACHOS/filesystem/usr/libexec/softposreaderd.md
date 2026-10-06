## softposreaderd

> `/usr/libexec/softposreaderd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4236c4` | `0x4239a8` | **`+0x2e4`** |
| `__DATA_CONST.__const` | `0x18280` | `0x182d0` | **`+0x50`** |
| `__TEXT.__oslogstring` | `0xce1e` | `0xce4e` | **`+0x30`** |
| `__TEXT.__eh_frame` | `0xcab4` | `0xca8c` | **`-0x28`** |
| `__TEXT.__const` | `0x88320` | `0x88340` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x20a0` | `0x2080` | **`-0x20`** |
| `__TEXT.__auth_stubs` | `0x4280` | `0x4290` | **`+0x10`** |
| `__TEXT.__constg_swiftt` | `0x794c` | `0x795c` | **`+0x10`** |
| `__TEXT.__cstring` | `0x119bb` | `0x119ab` | **`-0x10`** |
| `__TEXT.__objc_methname` | `0x42dd` | `0x42cd` | **`-0x10`** |
| `__TEXT.__objc_methtype` | `0x1535` | `0x1525` | **`-0x10`** |
| `__DATA.__objc_selrefs` | `0xb18` | `0xb10` | **`-0x8`** |
| `__DATA_CONST.__auth_got` | `0x2148` | `0x2150` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x4e48` | `0x4e40` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-50.31.1.0.0
+50.32.1.0.0

+  - /System/Library/PrivateFrameworks/SetupAssistant.framework/SetupAssistant

-  Functions: 6165
+  Functions: 6163

-  CStrings:  3581
+  CStrings:  3582
Symbols:
+ _BYSetupAssistantNeedsToRun
- _OBJC_CLASS_$_NFSession
CStrings:
+ "Failed to refresh UniversalSecureChannel: %@"
+ "dynamicSEUISheet.present failed: %@"
+ "isBuddyFlow"
- "setSessionTimeLimit:"
- "waiting for NFSecureElementManagerSession..."
```
