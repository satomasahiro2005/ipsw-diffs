## assessmentagent

> `/usr/libexec/assessmentagent`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x92328` | `0x94118` | **`+0x1df0`** |
| `__TEXT.__eh_frame` | `0x3a9c` | `0x3bec` | **`+0x150`** |
| `__TEXT.__const` | `0x7c40` | `0x7d60` | **`+0x120`** |
| `__DATA.__objc_const` | `0x53a8` | `0x5480` | **`+0xd8`** |
| `__DATA.__data` | `0x6a58` | `0x6b28` | **`+0xd0`** |
| `__DATA_CONST.__const` | `0x77d8` | `0x78a8` | **`+0xd0`** |
| `__TEXT.__constg_swiftt` | `0x44cc` | `0x4574` | **`+0xa8`** |
| `__TEXT.__swift5_typeref` | `0x383a` | `0x38d8` | **`+0x9e`** |
| `__TEXT.__swift5_fieldmd` | `0x3148` | `0x31dc` | **`+0x94`** |
| `__TEXT.__swift5_reflstr` | `0x366d` | `0x36fd` | **`+0x90`** |
| `__TEXT.__auth_stubs` | `0x2040` | `0x2090` | **`+0x50`** |
| `__TEXT.__oslogstring` | `0x1c24` | `0x1c74` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x21e0` | `0x2228` | **`+0x48`** |
| `__DATA_CONST.__cfstring` | `0x1c0` | `0x200` | **`+0x40`** |
| `__TEXT.__cstring` | `0x1b68` | `0x1b98` | **`+0x30`** |
| `__TEXT.__objc_classname` | `0x182b` | `0x185b` | **`+0x30`** |
| `__DATA_CONST.__auth_got` | `0x1030` | `0x1058` | **`+0x28`** |
| `__DATA_CONST.__got` | `0x840` | `0x860` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x23e0` | `0x2400` | **`+0x20`** |
| `__TEXT.__swift_as_cont` | `0x290` | `0x2a8` | **`+0x18`** |
| `__TEXT.__swift5_capture` | `0xe10` | `0xe24` | **`+0x14`** |
| `__DATA_CONST.__auth_ptr` | `0x9b0` | `0x9c0` | **`+0x10`** |
| `__TEXT.__objc_methname` | `0x3689` | `0x3699` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0xa78` | `0xa80` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x260` | `0x268` | **`+0x8`** |
| `__TEXT.__swift5_protos` | `0xc4` | `0xcc` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x314` | `0x31c` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x1a8` | `0x1b0` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x150` | `0x158` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x42c` | `0x430` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`

### Other Changes

```diff

-50.0.0.0.0
+53.0.0.0.0

-  Functions: 2845
-  Symbols:   931
-  CStrings:  1067
+  Functions: 2864
+  Symbols:   940
+  CStrings:  1074
Symbols:
+ _$s13AsyncIteratorSciTl
+ _$sScEMa
+ _$sScI4next9isolation7ElementQzSgScA_pSgYi_tYa7FailureQzYKFTj
+ _$sScI4next9isolation7ElementQzSgScA_pSgYi_tYa7FailureQzYKFTjTu
+ _$sScT6cancelyyF
+ _$sScTss5NeverORszABRs_rlE17checkCancellationyyKFZ
+ _$sSci13AsyncIteratorSci_ScITn
+ _$sSci17makeAsyncIterator0bC0QzyFTj
+ _$sSciTL
CStrings:
+ "/usr/libexec/mdmclient"
+ "/usr/libexec/opendirectoryd"
+ "User session gate screenLocked: %{bool,public}d → ready: %{bool,public}d"
+ "_TtC15assessmentagent18AEAUserSessionGate"
+ "allowGracefulTermination"
+ "systemMonitor"
+ "transitionState"
+ "userSessionGate"
- "isTransitioning"
```
