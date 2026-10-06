## ModuleACM

> `/System/Library/Frameworks/LocalAuthentication.framework/Support/ModulePlugins/ModuleACM.bundle/ModuleACM`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x20dc8` | `0x21090` | **`+0x2c8`** |
| `__TEXT.__oslogstring` | `0xb60` | `0xcc8` | **`+0x168`** |
| `__TEXT.__gcc_except_tab` | `0x3e0` | `0x410` | **`+0x30`** |
| `__TEXT.__const` | `0x2b8` | `0x2d8` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x26c0` | `0x26e0` | **`+0x20`** |
| `__TEXT.__auth_stubs` | `0x770` | `0x780` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0xa80` | `0xa88` | **`+0x8`** |
| `__DATA_CONST.__auth_got` | `0x3c8` | `0x3d0` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x298` | `0x2a0` | **`+0x8`** |
| `__TEXT.__objc_methname` | `0x280d` | `0x2815` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-2319.0.63.0.0
+2319.40.29.0.0

-  Symbols:   448
-  CStrings:  924
+  Symbols:   450
+  CStrings:  928
Symbols:
+ _LACPolicyOptionSkipDoublePress
+ __os_log_debug_impl
CStrings:
+ "Building submechanisms for KofN requirement type:%lu (k:%ld) with subrequirement types:%{public}@"
+ "KofN requirement type:%lu is already satisfied; dropping its submechanisms (subrequirement types:%{public}@)"
+ "KofN requirement type:%lu resolved (k:%ld, submechanisms:%lu)"
+ "KofN subrequirement type:%lu state:%d hasMechanism:%d (remaining k:%ld, submechanisms:%lu)"
```
