## manageddeviced

> `/usr/libexec/manageddeviced`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_CONST.__got` | `0x908` | `0x930` | **`+0x28`** |
| `__TEXT.__objc_methname` | `0x9ce5` | `0x9ce6` | **`+0x1`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-22.0.0.0.0
+24.0.0.0.0

+  - /System/Library/PrivateFrameworks/AppStoreFoundation.framework/AppStoreFoundation
Symbols:
+ _OBJC_CLASS_$_ASFReceipt
- _OBJC_CLASS_$_SSPurchaseReceipt
CStrings:
+ "vppStateFlagsWithRecord:"
- "vppStateFlagsWithProxy:"
```
