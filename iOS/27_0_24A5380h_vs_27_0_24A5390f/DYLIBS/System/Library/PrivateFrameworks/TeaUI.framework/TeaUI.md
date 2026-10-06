## TeaUI

> `/System/Library/PrivateFrameworks/TeaUI.framework/TeaUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3607f0` | `0x3645b4` | **`+0x3dc4`** |
| `__AUTH_CONST.__const` | `0x2d720` | `0x2d428` | **`-0x2f8`** |
| `__DATA.__bss` | `0x19a70` | `0x19d00` | **`+0x290`** |
| `__TEXT.__const` | `0x28074` | `0x28264` | **`+0x1f0`** |
| `__TEXT.__oslogstring` | `0x3975` | `0x3ab5` | **`+0x140`** |
| `__TEXT.__eh_frame` | `0x9a50` | `0x9b68` | **`+0x118`** |
| `__TEXT.__swift5_typeref` | `0xd87c` | `0xd96a` | **`+0xee`** |
| `__TEXT.__swift5_capture` | `0x9110` | `0x9024` | **`-0xec`** |
| `__TEXT.__unwind_info` | `0x10f18` | `0x10f90` | **`+0x78`** |
| `__TEXT.__swift5_reflstr` | `0xcdaf` | `0xce1f` | **`+0x70`** |
| `__AUTH_CONST.__objc_const` | `0x1bc20` | `0x1bc80` | **`+0x60`** |
| `__DATA_DIRTY.__data` | `0x114e8` | `0x11548` | **`+0x60`** |
| `__TEXT.__swift5_assocty` | `0x15b8` | `0x1618` | **`+0x60`** |
| `__DATA.__data` | `0x5ef0` | `0x5f30` | **`+0x40`** |
| `__TEXT.__cstring` | `0x9c61` | `0x9ca1` | **`+0x40`** |
| `__TEXT.__swift5_fieldmd` | `0xf900` | `0xf930` | **`+0x30`** |
| `__DATA_CONST.__objc_selrefs` | `0x4690` | `0x46a8` | **`+0x18`** |
| `__TEXT.__swift5_proto` | `0x1654` | `0x1668` | **`+0x14`** |
| `__DATA_CONST.__const` | `0x25a0` | `0x25b0` | **`+0x10`** |
| `__TEXT.__constg_swiftt` | `0x13c30` | `0x13c40` | **`+0x10`** |
| `__TEXT.__swift_as_cont` | `0x2f4` | `0x300` | **`+0xc`** |
| `__AUTH_CONST.__auth_got` | `0x2e18` | `0x2e20` | **`+0x8`** |
| `__DATA.__common` | `0x90` | `0x98` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x1a50` | `0x1a58` | **`+0x8`** |
| `__DATA_DIRTY.__objc_data` | `0x5c98` | `0x5ca0` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x1b0` | `0x1b8` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x1d4` | `0x1d8` | **`+0x4`** |

### Other Changes

```diff

-1468.0.0.0.0
+1471.0.0.0.0

-  Functions: 31679
-  Symbols:   8230
-  CStrings:  1102
+  Functions: 31735
+  Symbols:   8249
+  CStrings:  1109
Symbols:
+ ___swift_closure_destructor.63Tm
+ _associated conformance So23UIPopoverArrowDirectionVs10SetAlgebraSCSQ
+ _associated conformance So23UIPopoverArrowDirectionVs10SetAlgebraSCs25ExpressibleByArrayLiteral
+ _associated conformance So23UIPopoverArrowDirectionVs9OptionSetSCSY
+ _associated conformance So23UIPopoverArrowDirectionVs9OptionSetSCs0E7Algebra
+ _get_witness_table SHRzr0_lSSSHHPyHC
+ _symbolic SDySS_____G 5TeaUI12TipPlacementC
+ _symbolic SaySSGIegr_
+ _symbolic Say_____G 5TeaUI12TipPlacementC
+ _symbolic Say_____GIegr_ 5TeaUI12TipPlacementC
+ _symbolic Say______Say_____GtG 5TeaUI12TipPlacementC AA0C6ConfigV
+ _symbolic Say______Say_____GtGz_Xx 5TeaUI12TipPlacementC AA0C6ConfigV
+ _symbolic ScTyyt_____GSg s5NeverO
+ _symbolic _____Sg 5TeaUI16TipSourceManagerC
+ _symbolic _____SgXw 5TeaUI15TipPresentationC
+ _symbolic _____SgXw 5TeaUI16PillViewRendererC
+ _symbolic _____SgXwz_Xx 5TeaUI10TipManagerC
+ _symbolic _____SgXwz_Xx 5TeaUI16PillViewRendererC
+ _symbolic _____SgXwz_Xx 5TeaUI8PillViewC
+ _symbolic _____ySS______G SD6ValuesV 5TeaUI12TipPlacementC
- _symbolic Say_____G 5TeaUI9TipConfigV
CStrings:
+ ", groupIdentifier:"
+ "All registered placements=%s"
+ "Attempted to register a tip placement but source view controller was nil"
+ "Deregistering placements=%s..."
+ "Invalid placement=%s for tip source=%{public}s: disallowed in compact layouts"
+ "Invalid placement=%s for tip source=%{public}s: disallowed in regular layouts"
+ "Invalid placement=%s for tip source=%{public}s: keyboard is present"
+ "Invalidating stale presentation for tip placement source=%{public}s, sourceIdentifier=%{public}s"
+ "No record for checking config group presentability found for config=%{public}s - isPresentable=%{bool}d"
+ "Registering configs..."
+ "Removing placement for sourceIdentifier=%s"
+ "Resolved config for tip placement=%s"
+ "TeaUI/PillViewRenderer.swift"
- "Checking config group presentability for config=%{public}s... failed. No record"
- "Invalid placement for tip source=%{public}s, disallowed in compact layouts"
- "Invalid placement for tip source=%{public}s, disallowed in regular layouts"
- "Invalid placement for tip source=%{public}s: keyboard is present"
- "No presentable config found for tip=%{public}s"
- "Registered tip config=%{public}s"
```
