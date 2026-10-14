## manageddeviced

> `/usr/libexec/manageddeviced`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__objc_methname` | `0xa4a7` | `0xa4f0` | **`+0x49`** |
| `__TEXT.__objc_stubs` | `0x92e0` | `0x9320` | **`+0x40`** |
| `__TEXT.__text` | `0x43dec` | `0x43e28` | **`+0x3c`** |
| `__DATA.__objc_selrefs` | `0x2a40` | `0x2a50` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x41ec` | `0x41fc` | **`+0x10`** |
| `__TEXT.__const` | `0x118` | `0x120` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1298` | `0x12a0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`

### Other Changes

```diff

-31.0.0.0.0
+31.42.1.0.0

-  Functions: 1756
+  Functions: 1757

-  CStrings:  2779
+  CStrings:  2781
CStrings:
+ "_handoffCurrentReplyToQueue:block:"
+ "_performOnStateQueueForWaitingCaller:"
```
