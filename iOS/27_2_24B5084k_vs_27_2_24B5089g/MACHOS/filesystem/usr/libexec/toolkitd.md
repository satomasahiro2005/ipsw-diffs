## toolkitd

> `/usr/libexec/toolkitd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa32e8` | `0xa3524` | **`+0x23c`** |
| `__TEXT.__eh_frame` | `0x5f00` | `0x5f30` | **`+0x30`** |
| `__TEXT.__auth_stubs` | `0x2e10` | `0x2e20` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x1ee8` | `0x1ef8` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x1710` | `0x1718` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-5110.0.8.0.0
+5111.0.2.0.0

-  Functions: 2966
-  Symbols:   1275
+  Functions: 2971
+  Symbols:   1276
Symbols:
+ _$s7ToolKit0A8DatabaseC8AccessorC12addParameter6toolId3key12typeInstance9sortOrder13relationships5flags12requirementsys5Int64V_SSAA04TypeK0OSiSayAA0F22RelationshipDefinitionVGAA0fT0V0F5FlagsVSayAA18RuntimeRequirementOGtKF
+ _$s7ToolKit0A8DatabaseC8AccessorC12addParameter6toolId3key12typeInstance9sortOrder13relationships5flags12requirementsys5Int64V_SSAA04TypeK0OSiSayAA0F22RelationshipDefinitionVGAA0fT0V0F5FlagsVSayAA18RuntimeRequirementOGtKFfA5_
+ _$s7ToolKit19ParameterDefinitionV3key4name11description5flags9valueType13relationships06parentA8Metadata27overriddenSampleInvocations07booleanM012requirementsACSS_S2SSgAC0C5FlagsVAA0J8InstanceOSayAA0c12RelationshipD0VGAC0aM0VSgSayAA0o10InvocationD0VGSgAC07BooleanM0VSgSayAA18RuntimeRequirementOGtcfC
- _$s7ToolKit0A8DatabaseC8AccessorC12addParameter6toolId3key12typeInstance9sortOrder13relationships5flagsys5Int64V_SSAA04TypeK0OSiSayAA0F22RelationshipDefinitionVGAA0fS0V0F5FlagsVtKF
- _$s7ToolKit19ParameterDefinitionV3key4name11description5flags9valueType13relationships06parentA8Metadata27overriddenSampleInvocations07booleanM0ACSS_S2SSgAC0C5FlagsVAA0J8InstanceOSayAA0c12RelationshipD0VGAC0aM0VSgSayAA0o10InvocationD0VGSgAC07BooleanM0VSgtcfC
```
