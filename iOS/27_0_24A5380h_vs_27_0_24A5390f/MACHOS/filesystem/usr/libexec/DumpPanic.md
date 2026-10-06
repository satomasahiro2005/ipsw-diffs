## DumpPanic

> `/usr/libexec/DumpPanic`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2aee4` | `0x2b194` | **`+0x2b0`** |
| `__DATA.__objc_const` | `0xfb0` | `0x10e0` | **`+0x130`** |
| `__TEXT.__objc_stubs` | `0x25a0` | `0x2640` | **`+0xa0`** |
| `__TEXT.__objc_methname` | `0x1f55` | `0x1fc4` | **`+0x6f`** |
| `__TEXT.__objc_methlist` | `0x85c` | `0x8bc` | **`+0x60`** |
| `__DATA.__objc_data` | `0x4d8` | `0x528` | **`+0x50`** |
| `__TEXT.__gcc_except_tab` | `0xb78` | `0xbb8` | **`+0x40`** |
| `__DATA.__objc_selrefs` | `0xac8` | `0xb00` | **`+0x38`** |
| `__TEXT.__objc_methtype` | `0x531` | `0x546` | **`+0x15`** |
| `__TEXT.__cstring` | `0x2b9b` | `0x2b8b` | **`-0x10`** |
| `__TEXT.__objc_classname` | `0x11c` | `0x12c` | **`+0x10`** |
| `__TEXT.__oslogstring` | `0x48e8` | `0x48d8` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x8c0` | `0x8d0` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x94` | `0xa0` | **`+0xc`** |
| `__DATA_CONST.__objc_classlist` | `0x68` | `0x70` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_typeref`

### Other Changes

```diff

-34.0.0.0.0
+37.0.0.0.0

-  Functions: 853
+  Functions: 863

-  CStrings:  1317
+  CStrings:  1334
CStrings:
+ "  -e, --plane FILE\n              use plane panic test input JSON file with multiple nodes\n\n"
+ "C"
+ "C16@0:8"
+ "Failed to allocate %zu bytes for report %d"
+ "Failed to create SOCD handle: %d"
+ "Failed to get SOCD v2 container agent ID: %d, num_agents: %zu"
+ "Failed to load SOCD container: %d"
+ "Failed to open report %d: %d"
+ "Failed to read report data for report %d: %d"
+ "SOCDReportInfo"
+ "T@\"NSData\",&,N,V_data"
+ "T@\"NSURL\",&,V_plane_json"
+ "TC,N,V_agentId"
+ "TC,N,V_type"
+ "Warning: Failed to set AWL platform data from platformSocdBuffer in plane metadata"
+ "_agentId"
+ "_data"
+ "_plane_json"
+ "_type"
+ "agentId"
+ "firstObject"
+ "plane"
+ "plane_json"
+ "plane_node"
+ "setAgentId:"
+ "setData:"
+ "setPlaneMetadata:"
+ "setPlane_json:"
+ "setType:"
+ "v20@0:8C16"
- "  -e, --ensemble FILE\n              use ensemble panic test input JSON file with multiple nodes\n\n"
- "Failed to allocate memory for report data, size: %zu"
- "Failed to get SOCD container size, report record ID: %d, error: %d"
- "Failed to open SOCD container size, report record ID: %d, error: %d"
- "Failed to read SOCD container report data, report record ID: %d, error: %d"
- "T@\"NSURL\",&,V_ensemble_json"
- "Warning: Failed to set AWL platform data from platformSocdBuffer in ensemble metadata"
- "_ensemble_json"
- "ensemble"
- "ensemble_json"
- "ensemble_node"
- "setEnsembleMetadata:"
- "setEnsemble_json:"
```
