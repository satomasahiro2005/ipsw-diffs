## ToolKit

> `/System/Library/PrivateFrameworks/ToolKit.framework/ToolKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x509f38` | `0x50d030` | **`+0x30f8`** |
| `__TEXT.__eh_frame` | `0x34f58` | `0x35288` | **`+0x330`** |
| `__AUTH_CONST.__const` | `0x2df58` | `0x2e278` | **`+0x320`** |
| `__TEXT.__const` | `0x7bef8` | `0x7c138` | **`+0x240`** |
| `__DATA_DIRTY.__bss` | `0x47900` | `0x47a80` | **`+0x180`** |
| `__TEXT.__unwind_info` | `0x1bdf0` | `0x1bee0` | **`+0xf0`** |
| `__TEXT.__swift5_capture` | `0x3fa4` | `0x4068` | **`+0xc4`** |
| `__TEXT.__swift5_fieldmd` | `0x14314` | `0x143d4` | **`+0xc0`** |
| `__TEXT.__swift5_reflstr` | `0x99d7` | `0x9a67` | **`+0x90`** |
| `__TEXT.__swift5_typeref` | `0x14ad6` | `0x14b56` | **`+0x80`** |
| `__TEXT.__constg_swiftt` | `0xf220` | `0xf28c` | **`+0x6c`** |
| `__DATA.__data` | `0xfd90` | `0xfdc0` | **`+0x30`** |
| `__TEXT.__swift_as_entry` | `0x634` | `0x650` | **`+0x1c`** |
| `__TEXT.__swift_as_cont` | `0xca8` | `0xcc0` | **`+0x18`** |
| `__TEXT.__swift_as_ret` | `0x7e4` | `0x7fc` | **`+0x18`** |
| `__DATA_CONST.__const` | `0x338` | `0x348` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0xdc0` | `0xdd0` | **`+0x10`** |
| `__DATA_DIRTY.__data` | `0x12fd8` | `0x12fe8` | **`+0x10`** |
| `__TEXT.__cstring` | `0x98e4` | `0x98f4` | **`+0x10`** |
| `__TEXT.__oslogstring` | `0x502c` | `0x503c` | **`+0x10`** |
| `__TEXT.__swift5_proto` | `0x6f7c` | `0x6f8c` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0x18c4` | `0x18d0` | **`+0xc`** |
| `__AUTH_CONST.__auth_got` | `0x2848` | `0x2850` | **`+0x8`** |

### Other Changes

```diff

-5113.0.1.1.1
+5114.0.8.3.0

-  Functions: 46138
-  Symbols:   10406
-  CStrings:  1796
+  Functions: 46240
+  Symbols:   10420
+  CStrings:  1797
Symbols:
+ _VCIsShortcutsActionsBundleIdentifier
+ ___swift__destructor.193Tm
+ ___swift_closure_destructor.297Tm
+ _associated conformance 7ToolKit0A17InvocationOptionsV14InterfaceIdiomO23HomeAccessoryCodingKeys33_D88535082CE74DB276E107568E2E9C0ALLOs0I3KeyAAs23CustomStringConvertible
+ _associated conformance 7ToolKit0A17InvocationOptionsV14InterfaceIdiomO23HomeAccessoryCodingKeys33_D88535082CE74DB276E107568E2E9C0ALLOs0I3KeyAAs28CustomDebugStringConvertible
+ _get_enum_tag_for_layout_string 7ToolKit14TypeIdentifierOAA19ContainerDefinitionV6DeviceOAA0cF0Os5Error_pIeghHnnrzo_Sg
+ _symbolic _____ 7ToolKit0A17InvocationOptionsV14InterfaceIdiomO23HomeAccessoryCodingKeys33_D88535082CE74DB276E107568E2E9C0ALLO
+ _symbolic _____ 7ToolKit27TypedValueConversionOptionsV
+ _symbolic _____ 7ToolKit29ClosureTypeDefinitionProvider33_74B2D7A44B435BF81634B257E0794C78LLV
+ _symbolic ________________tYaYbKc 7ToolKit14TypeDefinitionO AA0C10IdentifierO AA09ContainerD0V6DeviceO
+ _symbolic ________________tYaYbKcSg 7ToolKit14TypeDefinitionO AA0C10IdentifierO AA09ContainerD0V6DeviceO
+ _symbolic _____ySSSgG s23_ContiguousArrayStorageC
+ _symbolic _____y_____G s22KeyedDecodingContainerV 7ToolKit0D17InvocationOptionsV14InterfaceIdiomO23HomeAccessoryCodingKeys33_D88535082CE74DB276E107568E2E9C0ALLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 7ToolKit0D17InvocationOptionsV14InterfaceIdiomO23HomeAccessoryCodingKeys33_D88535082CE74DB276E107568E2E9C0ALLO
+ _type_layout_string 7ToolKit27TypedValueConversionOptionsV
+ _type_layout_string 7ToolKit29ClosureTypeDefinitionProvider33_74B2D7A44B435BF81634B257E0794C78LLV
- ___swift__destructor.189Tm
- ___swift_closure_destructor.293Tm
CStrings:
+ "Prewarming bundle: %s (%{public}s)"
+ "prewarmBundle(bundleIdentifier:options:)"
+ "rendersNoParameters"
- "Prewarming bundle: %s"
- "prewarmBundle(bundleIdentifier:)"
```
