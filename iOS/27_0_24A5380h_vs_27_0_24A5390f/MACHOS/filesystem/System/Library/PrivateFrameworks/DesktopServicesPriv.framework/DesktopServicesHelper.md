## DesktopServicesHelper

> `/System/Library/PrivateFrameworks/DesktopServicesPriv.framework/DesktopServicesHelper`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x81aac` | `0x82978` | **`+0xecc`** |
| `__TEXT.__gcc_except_tab` | `0xa4dc` | `0xa708` | **`+0x22c`** |
| `__TEXT.__oslogstring` | `0x37af` | `0x38f7` | **`+0x148`** |
| `__TEXT.__unwind_info` | `0x3938` | `0x3998` | **`+0x60`** |
| `__TEXT.__objc_stubs` | `0x1ec0` | `0x1e80` | **`-0x40`** |
| `__DATA.__bss` | `0x910` | `0x948` | **`+0x38`** |
| `__TEXT.__cstring` | `0x2784` | `0x27bc` | **`+0x38`** |
| `__DATA.__data` | `0x541` | `0x519` | **`-0x28`** |
| `__DATA_CONST.__cfstring` | `0x1420` | `0x1440` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0x1e0a` | `0x1e01` | **`-0x9`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__init_offsets`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-1852.0.0.0.0
+1854.0.0.0.0

-  Functions: 2222
+  Functions: 2224

-  CStrings:  1221
+  CStrings:  1229
CStrings:
+ "About to rename\n\t old: `%{public}@`\n\t new: `%{public}@`"
+ "Clone-link copy fallback failed. status=%d"
+ "Preserved clone link denied (status=%d); falling back to a copy for %{public}s"
+ "StartTime_CalcTimeRemaining"
+ "copyfile failed cross volume copy: %{errno}d\n\t src: `%{public}@`\n\t dst: `%{public}@`"
+ "doubleValue"
+ "rename failed: %{errno}d\n\t old: `%{public}@`\n\t new: `%{public}@`"
+ "sourceName"
+ "sourceParentPath"
- "timeIntervalSinceNow"
```
