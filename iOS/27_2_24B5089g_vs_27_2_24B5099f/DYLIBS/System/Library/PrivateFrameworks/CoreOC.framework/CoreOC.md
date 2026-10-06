## CoreOC

> `/System/Library/PrivateFrameworks/CoreOC.framework/CoreOC`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_DIRTY.__data` | `0x3da8` | `0x4978` | **`+0xbd0`** |
| `__AUTH.__data` | `0x7a8` | `—` | **`-0x7a8`** |
| `__TEXT.__text` | `0x10048c` | `0x1008bc` | **`+0x430`** |
| `__DATA.__data` | `0x1250` | `0xe30` | **`-0x420`** |
| `__AUTH.__objc_data` | `0x120` | `—` | **`-0x120`** |
| `__DATA_CONST.__const` | `0x370` | `0x478` | **`+0x108`** |
| `__DATA_DIRTY.__objc_data` | `0x1440` | `0x1540` | **`+0x100`** |
| `__TEXT.__cstring` | `0x3f8c` | `0x407c` | **`+0xf0`** |
| `__TEXT.__unwind_info` | `0x1f48` | `0x1f10` | **`-0x38`** |
| `__AUTH_CONST.__auth_got` | `0x1788` | `0x17b0` | **`+0x28`** |
| `__TEXT.__eh_frame` | `0x17b8` | `0x17e0` | **`+0x28`** |
| `__AUTH_CONST.__objc_const` | `0x7760` | `0x7740` | **`-0x20`** |
| `__DATA_DIRTY.__bss` | `0x9b0` | `0x9d0` | **`+0x20`** |
| `__TEXT.__const` | `0x5978` | `0x5958` | **`-0x20`** |
| `__TEXT.__constg_swiftt` | `0x4620` | `0x4608` | **`-0x18`** |
| `__TEXT.__swift5_reflstr` | `0x452c` | `0x451c` | **`-0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x35e0` | `0x35d4` | **`-0xc`** |
| `__DATA.__bss` | `0x3980` | `0x3988` | **`+0x8`** |

### Other Changes

```diff

-11.3.6.0.0
+11.3.7.0.0

-  Functions: 3561
-  Symbols:   616
-  CStrings:  1094
+  Functions: 3571
+  Symbols:   615
+  CStrings:  1106
Symbols:
+ _OBJC_CLASS_$_OS_os_log
- _kdebug_trace
- _kdebug_trace_string
CStrings:
+ "boundingbox"
+ "explicit_feedback"
+ "frameIndex=%{public}llu"
+ "frame_boundary"
+ "freeform_mesh_refinement"
+ "oc_detect_stage"
+ "oc_preview_stage"
+ "oc_scan_stage"
+ "pnp_measurement_interval"
+ "take_shot"
+ "update_shot"
+ "write_shot"
```
