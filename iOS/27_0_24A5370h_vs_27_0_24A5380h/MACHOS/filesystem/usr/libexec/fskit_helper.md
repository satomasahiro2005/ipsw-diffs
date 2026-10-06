## fskit_helper

> `/usr/libexec/fskit_helper`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x13b0` | `0x14ec` | **`+0x13c`** |
| `__TEXT.__objc_stubs` | `0x300` | `0x340` | **`+0x40`** |
| `__TEXT.__oslogstring` | `0x364` | `0x3a1` | **`+0x3d`** |
| `__TEXT.__objc_methname` | `0x365` | `0x397` | **`+0x32`** |
| `__TEXT.__cstring` | `0x161` | `0x180` | **`+0x1f`** |
| `__TEXT.__objc_methtype` | `0x1b1` | `0x1c3` | **`+0x12`** |
| `__DATA.__objc_selrefs` | `0x180` | `0x190` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x48` | `0x50` | **`+0x8`** |
| `__TEXT.__const` | `0x50` | `0x58` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x1ac` | `0x1b4` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-974.0.1.0.2
+974.0.7.0.0

-  Functions: 27
-  Symbols:   63
-  CStrings:  109
+  Functions: 28
+  Symbols:   64
+  CStrings:  115
Symbols:
+ _SANDBOX_CHECK_CANONICAL
+ _sandbox_check_by_audit_token
- _objc_release_x24
CStrings:
+ "FSKitHelper: sandbox denied %{public}s on %{public}s (rv=%d)"
+ "audit_token"
+ "file-read-data"
+ "file-write-data"
+ "i36@0:8@16r*24B32"
+ "sandboxCheckAuditToken:path:writable:"
```
