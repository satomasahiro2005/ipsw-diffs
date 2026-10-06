## UnityPoster

> `/System/Library/PrivateFrameworks/UnityPoster.framework/UnityPoster`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4640` | `0x4828` | **`+0x1e8`** |
| `__TEXT.__oslogstring` | `—` | `0x85` | **`+0x85`** |
| `__TEXT.__cstring` | `0x9d` | `0xcc` | **`+0x2f`** |
| `__AUTH_CONST.__cfstring` | `0x80` | `0xa0` | **`+0x20`** |
| `__AUTH_CONST.__const` | `0x40` | `0x60` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x530` | `0x550` | **`+0x20`** |
| `__DATA.__bss` | `0x10` | `0x20` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x98` | `0xa0` | **`+0x8`** |
| `__TEXT.__const` | `0x3d0` | `0x3d8` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1b8` | `0x1c0` | **`+0x8`** |

### Other Changes

```diff

-50.4.1.0.0
+51.0.0.0.0

-  Functions: 171
-  Symbols:   375
-  CStrings:  11
+  Functions: 173
+  Symbols:   380
+  CStrings:  14
Symbols:
+ _OBJC_CLASS_$_NSFileManager
+ __os_log_error_impl
+ _os_log_create
+ _os_log_type_enabled
+ _setupLayerForIdentifier:.log
Functions:
~ ___42-[UPQuiltViewPad setupLayerForIdentifier:]_block_invoke : 72 -> 68
~ ___42-[UPQuiltViewPad setupLayerForIdentifier:]_block_invoke_2 : 116 -> 308
+ ___42-[UPQuiltViewPad setupLayerForIdentifier:]_block_invoke.10
~ _OUTLINED_FUNCTION_0 : 28 -> 20
~ _OUTLINED_FUNCTION_1 : 20 -> 28
~ _OUTLINED_FUNCTION_4 : 16 -> 12
~ _OUTLINED_FUNCTION_5 : 12 -> 16
~ -[UPQuiltViewPad setupLayerForIdentifier:] : 376 -> 484
+ ___42-[UPQuiltViewPad setupLayerForIdentifier:]_block_invoke_2.cold.1
CStrings:
+ "BSUIMappedImageCache unavailable (caches dir not writable: %{public}@); falling back to non-mapped UIImage decode for poster assets."
+ "MappedImageCache"
+ "com.apple.Posters.UnityPoster"
```
