## swtransparencyd

> `/usr/libexec/swtransparencyd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xfdee4` | `0xff2d0` | **`+0x13ec`** |
| `__TEXT.__cstring` | `0x4da9` | `0x4ea9` | **`+0x100`** |
| `__TEXT.__oslogstring` | `0x36bd` | `0x37bd` | **`+0x100`** |
| `__TEXT.__eh_frame` | `0x69dc` | `0x6a54` | **`+0x78`** |
| `__DATA_CONST.__const` | `0x5fc8` | `0x6038` | **`+0x70`** |
| `__DATA_CONST.__cfstring` | `0x3060` | `0x30c0` | **`+0x60`** |
| `__TEXT.__unwind_info` | `0x4800` | `0x4840` | **`+0x40`** |
| `__TEXT.__auth_stubs` | `0x27e0` | `0x2810` | **`+0x30`** |
| `__TEXT.__const` | `0x5ed0` | `0x5ef0` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0x1400` | `0x1418` | **`+0x18`** |
| `__TEXT.__constg_swiftt` | `0x1ad4` | `0x1ae4` | **`+0x10`** |
| `__DATA.__common` | `0x2a8` | `0x2b0` | **`+0x8`** |
| `__DATA_CONST.__auth_ptr` | `0x508` | `0x510` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__got`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-1766.0.60.0.0
+1766.40.47.0.0

-  Functions: 6031
-  Symbols:   957
-  CStrings:  2894
+  Functions: 6052
+  Symbols:   960
+  CStrings:  2901
Symbols:
+ _$s10Foundation4DateV17timeIntervalSinceySdACF
+ _$s12Transparency0A13SWSysdiagnoseV12StateMachineV5state5flags12pendingFlags12publicKeybag13containerPath12reachability18lastMilestoneFetchAESSSg_SaySSGSgAoC06PublicJ0VSgAmC12ReachabilityVSg10Foundation4DateVSgtcfC
+ _$s12Transparency0A13SWSysdiagnoseV25milestoneRefreshFreshnessSdvgZ
+ _ccvrf_proof_to_hash
+ _ccvrf_sizeof_hash
- _$s12Transparency0A13SWSysdiagnoseV12StateMachineV5state5flags12pendingFlags12publicKeybag13containerPath12reachabilityAESSSg_SaySSGSgAnC06PublicJ0VSgAlC12ReachabilityVSgtcfC
- _objc_retain_x6
CStrings:
+ "Failed to read most recent milestone receiptTime: %@"
+ "Milestone younger than refresh threshold, skipping milestone-refresh work"
+ "SELECT receiptTime\nFROM SignedLogHeads\nWHERE application=? AND logType=? AND consistencyVerified=? AND milestone=1\nORDER BY receiptTime DESC\nLIMIT 1"
+ "VRF witness output does not match proof_to_hash(proof)"
+ "VRF witness output not bound to proof"
+ "no directory to delete %@ from"
+ "no directory to write %@ to"
```
