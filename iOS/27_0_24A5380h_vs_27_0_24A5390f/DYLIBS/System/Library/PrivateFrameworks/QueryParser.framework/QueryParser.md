## QueryParser

> `/System/Library/PrivateFrameworks/QueryParser.framework/QueryParser`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x115bb8` | `0x115de8` | **`+0x230`** |
| `__AUTH.__objc_data` | `0xa28` | `0x8e8` | **`-0x140`** |
| `__DATA_DIRTY.__objc_data` | `0x5f8` | `0x738` | **`+0x140`** |
| `__TEXT.__oslogstring` | `0x793e` | `0x79ae` | **`+0x70`** |
| `__DATA.__bss` | `0x1570` | `0x1550` | **`-0x20`** |
| `__DATA_DIRTY.__bss` | `0x428` | `0x448` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x299c` | `0x29b4` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x20e0` | `0x20f0` | **`+0x10`** |
| `__TEXT.__cstring` | `0xd2d5` | `0xd2e5` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0x13548` | `0x13558` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x15d8` | `0x15e0` | **`+0x8`** |
| `__DATA.__data` | `0x11b0` | `0x11b8` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x5208` | `0x5210` | **`+0x8`** |

### Other Changes

```diff

-3600.31.13.0.0
+3600.31.18.0.0

-  Functions: 4271
-  Symbols:   5928
-  CStrings:  3391
+  Functions: 4276
+  Symbols:   5934
+  CStrings:  3394
Symbols:
+ +[QPAssetManager(Testing) _test_scopedAssertionInvalidateDelayNsec]
+ +[QPAssetManager(Testing) _test_setScopedAssertionInvalidateDelayNsec:]
+ GCC_except_table158
+ GCC_except_table167
+ __OBJC_$_CLASS_METHODS_QPAssetManager(Testing)
+ __ZL37sQPScopedAssertionInvalidateDelayNsec
+ __ZNSt3__113basic_ostreamIcNS_11char_traitsIcEEE5tellpEv
+ _dispatch_after
- GCC_except_table140
- __OBJC_$_CLASS_METHODS_QPAssetManager
CStrings:
+ "(nil)"
+ "[Conversation Entity]"
+ "[QPNLU][qid=%ld] PHOTOSENSITIVE query token detected for Home, disabling text embeddings"
+ "[UAF] Failed to acquire scoped RBS assertion; skipping OTA retrieval this call: %s"
- "[UAF] Failed to acquire scoped RBS assertion: %s"
```
