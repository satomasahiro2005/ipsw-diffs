## spaceattributiond

> `/System/Library/PrivateFrameworks/SpaceAttribution.framework/spaceattributiond`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__gcc_except_tab` | `0x1800` | `0x15e0` | **`-0x220`** |
| `__TEXT.__text` | `0x3fd88` | `0x3fe80` | **`+0xf8`** |
| `__TEXT.__cstring` | `0x3636` | `0x36c0` | **`+0x8a`** |
| `__DATA_CONST.__const` | `0x17e0` | `0x1808` | **`+0x28`** |
| `__DATA_CONST.__objc_intobj` | `0x588` | `0x570` | **`-0x18`** |
| `__TEXT.__objc_methname` | `0x8a6b` | `0x8a6c` | **`+0x1`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-499.40.4.0.0
+499.40.4.0.1

-  Functions: 1474
+  Functions: 1476

-  CStrings:  2789
+  CStrings:  2792
CStrings:
+ "-[SAHelper registerPaths:reply:]_block_invoke"
+ "-[SAHelper unregisterPaths:reply:]_block_invoke"
+ "com.apple.SAHelper.dynamicRegistrationQueue"
+ "dynamicRegistrationQueue"
- "dynamicRegistrationLock"
```
