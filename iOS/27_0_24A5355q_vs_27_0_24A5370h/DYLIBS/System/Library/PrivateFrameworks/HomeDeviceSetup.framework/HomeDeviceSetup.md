## HomeDeviceSetup

> `/System/Library/PrivateFrameworks/HomeDeviceSetup.framework/HomeDeviceSetup`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x1acc4` | `0x1ad54` | **`+0x90`** |
| `__DATA.__data` | `0xb00` | `0xb70` | **`+0x70`** |
| `__TEXT.__text` | `0x7314c` | `0x73114` | **`-0x38`** |
| `__DATA_CONST.__const` | `0x1960` | `0x1980` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x1868` | `0x1870` | **`+0x8`** |

### Other Changes

```diff

-405.0.0.0.0
+405.0.1.0.0

-  Functions: 3089
-  Symbols:   3346
-  CStrings:  3137
+  Functions: 3092
+  Symbols:   3347
+  CStrings:  3140
Symbols:
+ _gLogCategory_HDSDefaults
CStrings:
+ "+[HDSDefaults sysDropBuildMode]"
+ "HDSDefaults"
+ "internal"
+ "production"
+ "sysDropBuildMode: Seed path + profile -> %s\n"
+ "sysDropBuildMode: override from defaults: %ld -> %s\n"
- "sysdrop"
- "sysdrop_carry"
- "sysdrop_rp"
```
