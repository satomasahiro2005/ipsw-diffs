## FSKit

> `/System/Library/PrivateFrameworks/FSKit.framework/FSKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__objc_const` | `0xb148` | `0xb268` | **`+0x120`** |
| `__TEXT.__text` | `0x5394c` | `0x53888` | **`-0xc4`** |
| `__TEXT.__objc_methlist` | `0x6260` | `0x62a8` | **`+0x48`** |
| `__DATA_CONST.__objc_selrefs` | `0x2be0` | `0x2c10` | **`+0x30`** |
| `__TEXT.__oslogstring` | `0x3f36` | `0x3f66` | **`+0x30`** |
| `__TEXT.__gcc_except_tab` | `0xe40` | `0xe5c` | **`+0x1c`** |
| `__DATA.__objc_ivar` | `0x628` | `0x640` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x1828` | `0x1830` | **`+0x8`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-971.0.0.0.5
+974.0.1.0.2

-  Functions: 2694
-  Symbols:   4231
+  Functions: 2698
+  Symbols:   4244
Symbols:
+ -[FSModuleVolume supportsAccess]
+ -[FSModuleVolume supportsOpenClose]
+ -[FSModuleVolume supportsPreallocate]
+ -[FSModuleVolume supportsReadWrite]
+ -[FSModuleVolume supportsVolumeRename]
+ -[FSModuleVolume supportsXattr]
+ GCC_except_table127
+ GCC_except_table174
+ GCC_except_table232
+ GCC_except_table57
+ GCC_except_table58
+ GCC_except_table60
+ _OBJC_IVAR_$_FSModuleVolume._supportsAccess
+ _OBJC_IVAR_$_FSModuleVolume._supportsOpenClose
+ _OBJC_IVAR_$_FSModuleVolume._supportsPreallocate
+ _OBJC_IVAR_$_FSModuleVolume._supportsReadWrite
+ _OBJC_IVAR_$_FSModuleVolume._supportsVolumeRename
+ _OBJC_IVAR_$_FSModuleVolume._supportsXattr
+ _OUTLINED_FUNCTION_24
- GCC_except_table121
- GCC_except_table168
- GCC_except_table226
- GCC_except_table50
- GCC_except_table51
- GCC_except_table52
CStrings:
+ "%s: conforms to FSVolumeHandler = %d"
+ "%s: item %p was reclaimed, returning nil"
+ "-[FSModuleVolume(Project) getItemForFH:]"
- "%s: start"
- "%s: supportsV2 = %d"
- "+[FSVolumeHandlerResult initialize]"
```
