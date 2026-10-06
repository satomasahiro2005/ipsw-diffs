## PerfPowerServicesEventListenerPlugin

> `/System/Library/UserEventPlugins/PerfPowerServicesEventListenerPlugin.plugin/PerfPowerServicesEventListenerPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8708` | `0x8bf4` | **`+0x4ec`** |
| `__TEXT.__objc_stubs` | `0x12a0` | `0x1300` | **`+0x60`** |
| `__TEXT.__auth_stubs` | `0x550` | `0x5a0` | **`+0x50`** |
| `__DATA.__cfstring` | `0x1b60` | `0x1ba0` | **`+0x40`** |
| `__TEXT.__objc_methname` | `0x159d` | `0x15ce` | **`+0x31`** |
| `__DATA.__auth_got` | `0x2b8` | `0x2e0` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x1f8` | `0x218` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0x708` | `0x720` | **`+0x18`** |
| `__TEXT.__cstring` | `0x1338` | `0x134c` | **`+0x14`** |
| `__TEXT.__objc_methlist` | `0x89c` | `0x8ac` | **`+0x10`** |
| `__DATA.__auth_ptr` | `—` | `0x8` | **`+0x8`** |
| `__DATA.__got` | `0xa8` | `0xb0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__const`
- `__DATA.__data`
- `__DATA.__objc_arraydata`
- `__DATA.__objc_classlist`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_dictobj`
- `__DATA.__objc_intobj`
- `__DATA.__objc_protolist`
- `__DATA.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__gcc_except_tab`

### Other Changes

```diff

-3468.0.0.502.1
+3486.0.21.502.1

-  Functions: 233
-  Symbols:   172
-  CStrings:  578
+  Functions: 234
+  Symbols:   178
+  CStrings:  584
Symbols:
+ _IOIteratorNext
+ _IOObjectGetClass
+ _IORegistryEntryGetChildIterator
+ _OBJC_CLASS_$_NSArray
+ _objc_opt_class
+ _objc_opt_isKindOfClass
CStrings:
+ "BankID"
+ "ID"
+ "IOService"
+ "_modularBatteryData"
+ "mutableCopy"
+ "unsignedIntValue"
```
