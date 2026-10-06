## sysdiagnose_helper

> `/usr/libexec/sysdiagnose_helper`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x24bec` | `0x2523c` | **`+0x650`** |
| `__TEXT.__oslogstring` | `0x2671` | `0x2781` | **`+0x110`** |
| `__TEXT.__cstring` | `0x972f` | `0x97dd` | **`+0xae`** |
| `__DATA_CONST.__cfstring` | `0x1d40` | `0x1da0` | **`+0x60`** |
| `__DATA_CONST.__const` | `0x848` | `0x898` | **`+0x50`** |
| `__TEXT.__objc_methname` | `0x16fb` | `0x1744` | **`+0x49`** |
| `__TEXT.__objc_stubs` | `0x17a0` | `0x17e0` | **`+0x40`** |
| `__TEXT.__auth_stubs` | `0xfc0` | `0xfe0` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x630` | `0x650` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0x7a8` | `0x7c4` | **`+0x1c`** |
| `__DATA.__objc_selrefs` | `0x650` | `0x660` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x7f0` | `0x800` | **`+0x10`** |
| `__TEXT.__const` | `0x488` | `0x490` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x5dc` | `0x5e4` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-1598.0.0.0.0
+1598.0.4.0.0

-  Functions: 359
-  Symbols:   355
-  CStrings:  2176
+  Functions: 365
+  Symbols:   357
+  CStrings:  2190
Symbols:
+ _container_debug_dump_state
+ _container_error_copy_unlocalized_description
CStrings:
+ "Container Manager SPI error. Finished: %d, serviced by pid %d, return success: %d"
+ "Container Manager: failed to dump debug state; error = %{public}s"
+ "Container Manager: failed to open [%{public}s] for writing; error = (%d) %{public}s"
+ "Skipping error stats collection"
+ "TASK_TYPE_CONTAINER_MANAGER"
+ "containerManagerTaskWithDir:withTimeout:"
+ "idleStackFlowVCurveCDPEnd"
+ "idleStackFlowVCurveCDPStart"
+ "idleStackPurgeableValidityCurveAtSlowGC"
+ "json"
+ "squarePurgeable"
+ "state"
+ "stringByAppendingPathExtension:"
+ "v16@?0^{container_error_extended_s=}8"
```
