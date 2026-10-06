## com.apple.DriverKit.AppleUserECM

> `/System/Library/DriverExtensions/com.apple.DriverKit.AppleUserECM.dext/com.apple.DriverKit.AppleUserECM`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_CONST.__const` | `0xe00` | `0xe40` | **`+0x40`** |
| `__TEXT.__text` | `0x60e8` | `0x60fc` | **`+0x14`** |

### Same-size Content Changes

- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__got`
- `__DATA_CONST.__osclassinfo`

### Other Changes

```diff

-73.0.1.0.0
+73.0.2.0.0

-  Functions: 145
-  Symbols:   284
+  Functions: 146
+  Symbols:   285
Symbols:
+ __NSConcreteGlobalBlock
Functions:
~ __ZN12AppleUserECM9Stop_ImplEP9IOService : 908 -> 928
+ sub_100001d48
~ __ZN12AppleUserECM8activateEv : 1192 -> 1188
```
