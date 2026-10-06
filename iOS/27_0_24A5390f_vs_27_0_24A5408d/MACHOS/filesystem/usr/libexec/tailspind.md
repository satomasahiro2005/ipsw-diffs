## tailspind

> `/usr/libexec/tailspind`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xe888` | `0xef98` | **`+0x710`** |
| `__TEXT.__oslogstring` | `0x2ab7` | `0x2bdd` | **`+0x126`** |
| `__TEXT.__gcc_except_tab` | `0x288` | `0x318` | **`+0x90`** |
| `__TEXT.__objc_stubs` | `0xba0` | `0xc20` | **`+0x80`** |
| `__DATA_CONST.__const` | `0x448` | `0x4c0` | **`+0x78`** |
| `__TEXT.__dlopen_cstrs` | `—` | `0x5c` | **`+0x5c`** |
| `__TEXT.__auth_stubs` | `0xc60` | `0xcb0` | **`+0x50`** |
| `__DATA_CONST.__cfstring` | `0x840` | `0x880` | **`+0x40`** |
| `__TEXT.__objc_methname` | `0xee2` | `0xf20` | **`+0x3e`** |
| `__TEXT.__cstring` | `0x135f` | `0x139c` | **`+0x3d`** |
| `__DATA_CONST.__auth_got` | `0x640` | `0x668` | **`+0x28`** |
| `__DATA.__objc_selrefs` | `0x388` | `0x3a8` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x440` | `0x460` | **`+0x20`** |
| `__DATA.__bss` | `0x5c8` | `0x5d8` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x178` | `0x188` | **`+0x10`** |
| `__TEXT.__const` | `0x134` | `0x140` | **`+0xc`** |
| `__DATA.__data` | `0x2164` | `0x2168` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-267.0.0.0.0
+268.0.0.0.0

-  Functions: 286
-  Symbols:   255
-  CStrings:  513
+  Functions: 294
+  Symbols:   262
+  CStrings:  528
Symbols:
+ _OBJC_CLASS_$_NSUserDefaults
+ _TSPCPUTraceOptions_PidFilters
+ _objc_getClass
+ _objc_retain_x9
+ _tailspin_config_apply_sync
+ _tailspin_config_create_with_current_state
+ _tailspin_cputrace_enabled_set_with_options
CStrings:
+ "B12@?0i8"
+ "CPUTrace pid selection enablement: %d"
+ "CPUTrace pid selection: Failed to apply tailspin config"
+ "CPUTrace pid selection: Failed to get tailspin config"
+ "CPUTrace pid selection: Got pid %d"
+ "CPUTrace pid selection: libhwtrace not present"
+ "CPUTracePIDSelectorObjC"
+ "CPUTracePIDSelectorObjC not present"
+ "CPUTracePidSelectionEnabled"
+ "CoreDiagnostics not present"
+ "boolValue"
+ "initWithSuiteName:"
+ "objectForKey:"
+ "softlink:o:path:/System/Library/PrivateFrameworks/CoreDiagnostics.framework/CoreDiagnostics"
+ "startWithCallback:"
```
