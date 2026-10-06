## GenericGamepadHIDServicePlugin

> `/System/Library/HIDPlugins/ServicePlugins/GenericGamepadHIDServicePlugin.plugin/GenericGamepadHIDServicePlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8a98` | `0x8800` | **`-0x298`** |
| `__TEXT.__auth_stubs` | `0x530` | `0x4c0` | **`-0x70`** |
| `__TEXT.__cstring` | `0xa2b` | `0x9ea` | **`-0x41`** |
| `__DATA_CONST.__cfstring` | `0x4e0` | `0x4a0` | **`-0x40`** |
| `__TEXT.__objc_stubs` | `0xf80` | `0xf40` | **`-0x40`** |
| `__DATA_CONST.__auth_got` | `0x2a8` | `0x270` | **`-0x38`** |
| `__TEXT.__oslogstring` | `0x47e` | `0x449` | **`-0x35`** |
| `__TEXT.__objc_methname` | `0xdeb` | `0xdd1` | **`-0x1a`** |
| `__DATA.__objc_selrefs` | `0x530` | `0x520` | **`-0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x10` | `0x8` | **`-0x8`** |
| `__TEXT.__const` | `0x98` | `0x90` | **`-0x8`** |
| `__TEXT.__objc_methlist` | `0x34c` | `0x344` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x210` | `0x208` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methtype`

### Other Changes

```diff

-14.0.17.0.0
+14.0.19.0.0

-  Functions: 136
-  Symbols:   129
-  CStrings:  330
+  Functions: 133
+  Symbols:   121
+  CStrings:  323
Symbols:
- _IOObjectConformsTo
- _IOObjectGetClass
- _IOObjectRelease
- _IOObjectRetain
- _IORegistryEntryCreateCFProperty
- _IORegistryEntryGetParentEntry
- _kCFAllocatorDefault
- _objc_opt_self
CStrings:
- "Could not get parent of service <%s>: %{mach.errno}d"
- "GCSyntheticDevice"
- "GamepadHIDServiceSupport"
- "IOHIDDevice"
- "IOService"
- "boolValue"
- "propertyForKey:"
```
