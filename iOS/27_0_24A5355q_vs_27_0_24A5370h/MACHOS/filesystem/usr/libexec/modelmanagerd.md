## modelmanagerd

> `/usr/libexec/modelmanagerd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1aaf6c` | `0x1ac8b0` | **`+0x1944`** |
| `__TEXT.__unwind_info` | `0x6e58` | `0x6c70` | **`-0x1e8`** |
| `__DATA_CONST.__const` | `0x7ac8` | `0x7ca8` | **`+0x1e0`** |
| `__TEXT.__eh_frame` | `0x16714` | `0x1664c` | **`-0xc8`** |
| `__TEXT.__const` | `0x66d6` | `0x6786` | **`+0xb0`** |
| `__TEXT.__oslogstring` | `0x9ba9` | `0x9c49` | **`+0xa0`** |
| `__TEXT.__swift5_capture` | `0x2294` | `0x2304` | **`+0x70`** |
| `__TEXT.__swift5_reflstr` | `0x24b3` | `0x2513` | **`+0x60`** |
| `__TEXT.__swift5_fieldmd` | `0x2120` | `0x2178` | **`+0x58`** |
| `__DATA.__objc_const` | `0x43b0` | `0x43f0` | **`+0x40`** |
| `__TEXT.__auth_stubs` | `0x3d10` | `0x3d50` | **`+0x40`** |
| `__TEXT.__objc_methname` | `0x18f3` | `0x1933` | **`+0x40`** |
| `__DATA.__data` | `0x6310` | `0x6348` | **`+0x38`** |
| `__DATA_CONST.__auth_got` | `0x1e90` | `0x1eb0` | **`+0x20`** |
| `__TEXT.__constg_swiftt` | `0x2d20` | `0x2d3c` | **`+0x1c`** |
| `__DATA.__common` | `0x5e0` | `0x5f8` | **`+0x18`** |
| `__TEXT.__swift5_typeref` | `0x2849` | `0x2861` | **`+0x18`** |
| `__TEXT.__swift_as_cont` | `0x1208` | `0x1220` | **`+0x18`** |
| `__TEXT.__cstring` | `0x1ed0` | `0x1ee0` | **`+0x10`** |
| `__TEXT.__swift_as_ret` | `0xab8` | `0xac4` | **`+0xc`** |
| `__TEXT.__swift_as_entry` | `0x944` | `0x94c` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x1d0` | `0x1d4` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`

### Other Changes

```diff

-680.0.0.0.0
+698.0.0.502.1

-  Functions: 8854
-  Symbols:   1673
-  CStrings:  1200
+  Functions: 8915
+  Symbols:   1677
+  CStrings:  1204
Symbols:
+ _$s12ModelCatalog17InferenceProviderV022VisualGenerationServerC0ACvgZ
+ _$s12ModelCatalog17InferenceProviderV14PCCAgentClientACvgZ
+ _$s12ModelCatalog17InferenceProviderV15PrivateMLClientACvgZ
+ _MobileGestalt_copy_regionCode_obj
CStrings:
+ "Blocking PCC session for bundle %s: inference provider %s is not supported in this region"
+ "Session %s failed to set properties from resolved bundle: %@"
+ "addSession(metadata:auditToken:alreadyLockedInferenceProvider:isUnentitled:resolvedBundle:)"
+ "isSensitiveRegionCountryPolicy"
+ "regionCodeProvider"
- "addSession(metadata:auditToken:alreadyLockedInferenceProvider:isUnentitled:)"
```
