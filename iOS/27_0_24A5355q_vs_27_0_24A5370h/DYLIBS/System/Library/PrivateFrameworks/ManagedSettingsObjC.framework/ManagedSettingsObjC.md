## ManagedSettingsObjC

> `/System/Library/PrivateFrameworks/ManagedSettingsObjC.framework/ManagedSettingsObjC`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__cfstring` | `0x25c0` | `0x25e0` | **`+0x20`** |
| `__AUTH_CONST.__objc_const` | `0x9620` | `0x9640` | **`+0x20`** |
| `__TEXT.__cstring` | `0x17cc` | `0x17ec` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x488c` | `0x48ac` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x1218` | `0x1238` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x1ca8` | `0x1cc0` | **`+0x18`** |
| `__DATA.__bss` | `0x8d0` | `0x8e0` | **`+0x10`** |

### Other Changes

```diff

-299.0.0.0.0
+300.0.0.0.0

-  Functions: 1616
-  Symbols:   3412
-  CStrings:  408
+  Functions: 1620
+  Symbols:   3418
+  CStrings:  409
Symbols:
+ +[MOSiriSettingsGroup forceSiriReduceSensitiveContentMetadata]
+ -[MOSiriSettingsGroup forceSiriReduceSensitiveContent]
+ -[MOSiriSettingsGroup setForceSiriReduceSensitiveContent:]
+ ___62+[MOSiriSettingsGroup forceSiriReduceSensitiveContentMetadata]_block_invoke
+ _forceSiriReduceSensitiveContentMetadata.metadata
+ _forceSiriReduceSensitiveContentMetadata.onceToken
CStrings:
+ "forceSiriReduceSensitiveContent"
```
