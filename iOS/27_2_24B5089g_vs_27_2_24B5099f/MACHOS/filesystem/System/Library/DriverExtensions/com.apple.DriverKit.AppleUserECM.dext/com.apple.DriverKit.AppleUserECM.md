## com.apple.DriverKit.AppleUserECM

> `/System/Library/DriverExtensions/com.apple.DriverKit.AppleUserECM.dext/com.apple.DriverKit.AppleUserECM`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x617c` | `0x6334` | **`+0x1b8`** |
| `__DATA_CONST.__const` | `0xe00` | `0xe50` | **`+0x50`** |
| `__TEXT.__cstring` | `0x695` | `0x6c5` | **`+0x30`** |
| `__TEXT.__auth_stubs` | `0x4e0` | `0x4f0` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x270` | `0x278` | **`+0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__got`
- `__DATA_CONST.__osclassinfo`

### Other Changes

```diff

-73.40.5.0.0
+73.40.6.0.0

-  Functions: 145
-  Symbols:   286
-  CStrings:  114
+  Functions: 147
+  Symbols:   287
+  CStrings:  115
Symbols:
+ __ZN16IODispatchSource9SetEnableEbPFiP15OSMetaClassBase5IORPCE
CStrings:
+ "AppleUserECMInterruptDispatchQueue"
+ "deactivate_block_invoke"
- "deactivate"
```
