## IconServices

> `/System/Library/PrivateFrameworks/IconServices.framework/IconServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x67b10` | `0x676b0` | **`-0x460`** |
| `__AUTH_CONST.__objc_const` | `0x14048` | `0x143a8` | **`+0x360`** |
| `__TEXT.__unwind_info` | `0x1968` | `0x19d8` | **`+0x70`** |
| `__DATA.__data` | `0x1cec` | `0x1d4c` | **`+0x60`** |
| `__TEXT.__objc_methlist` | `0x697c` | `0x69bc` | **`+0x40`** |
| `__TEXT.__oslogstring` | `0x40d4` | `0x40fc` | **`+0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0x3190` | `0x31b0` | **`+0x20`** |
| `__DATA_CONST.__objc_protolist` | `0x110` | `0x118` | **`+0x8`** |
| `__TEXT.__eh_frame` | `0x88` | `0x80` | **`-0x8`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-775.0.3.0.0
+779.0.0.0.0

-  Functions: 2608
-  Symbols:   4964
-  CStrings:  1084
+  Functions: 2609
+  Symbols:   4971
+  CStrings:  1085
Symbols:
+ -[ISStaticResources cache:willEvictObject:]
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_NSCacheDelegate
+ __OBJC_$_PROTOCOL_METHOD_TYPES_NSCacheDelegate
+ __OBJC_$_PROTOCOL_REFS_NSCacheDelegate
+ __OBJC_CLASS_PROTOCOLS_$_ISStaticResources
+ __OBJC_LABEL_PROTOCOL_$_NSCacheDelegate
+ __OBJC_PROTOCOL_$_NSCacheDelegate
CStrings:
+ "00:30:55"
+ "VL:: Evicting static resource/image: %@"
- "20:50:40"
```
