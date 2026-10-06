## com.apple.iokit.IOBiometricFamily

> `com.apple.iokit.IOBiometricFamily`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__auth_stubs` | `0x0` | `0x400` | **`+0x400`** |
| `__TEXT_EXEC.__text` | `0xf540` | `0xf578` | **`+0x38`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-570.0.0.0.0
+573.0.0.0.0
Functions:
~ sub_fffffff009f0efb0 -> sub_fffffff009f8cce0 : 88 -> 96
~ __ZN26IOBioShareableMemoryObject18getShareableMemoryEv : 1544 -> 1592
CStrings:
+ "AssertMacros: %s (value = 0x%lx), version: BiometricKit-573~7915, %s file: %s, line: %d\n"
- "AssertMacros: %s (value = 0x%lx), version: BiometricKit-570~3842, %s file: %s, line: %d\n"
```
