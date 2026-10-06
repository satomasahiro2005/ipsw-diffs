## com.apple.DriverKit.AppleUserECM

> `/System/Library/DriverExtensions/com.apple.DriverKit.AppleUserECM.dext/com.apple.DriverKit.AppleUserECM`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6100` | `0x617c` | **`+0x7c`** |
| `__DATA_CONST.__const` | `0xe40` | `0xe00` | **`-0x40`** |
| `__TEXT.__oslogstring` | `0xcf7` | `0xd2b` | **`+0x34`** |
| `__TEXT.__auth_stubs` | `0x4c0` | `0x4e0` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0x260` | `0x270` | **`+0x10`** |
| `__TEXT.__cstring` | `0x68a` | `0x695` | **`+0xb`** |

### Same-size Content Changes

- `__DATA_CONST.__got`
- `__DATA_CONST.__osclassinfo`

### Other Changes

```diff

-73.0.2.0.0
+73.40.5.0.0

-  Functions: 146
-  Symbols:   285
-  CStrings:  112
+  Functions: 145
+  Symbols:   286
+  CStrings:  114
Symbols:
+ __ZN15IODispatchQueue17WakeupWithOptionsEPvy
+ __ZN15IODispatchQueue5SleepEPvy
- __NSConcreteGlobalBlock
CStrings:
+ "%s::%s: timed out waiting for interruptCancelEvent\n"
+ "deactivate"
```
