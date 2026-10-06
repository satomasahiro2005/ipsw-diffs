## mscamerad-xpc

> `/System/Library/Frameworks/ImageCaptureCore.framework/XPCServices/mscamerad-xpc.xpc/mscamerad-xpc`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x15964` | `0x15a8c` | **`+0x128`** |
| `__TEXT.__cstring` | `0x1136` | `0x1185` | **`+0x4f`** |
| `__DATA_CONST.__cfstring` | `0x1dc0` | `0x1de0` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0x31e9` | `0x31f2` | **`+0x9`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-2113.0.0.0.0
+2114.0.0.0.0

-  CStrings:  990
+  CStrings:  991
Symbols:
+ -[MSCameraFile createBufferCacheAtOffset:]
+ _objc_msgSend$createBufferCacheAtOffset:
- -[MSCameraFile createBufferCache]
- _objc_msgSend$createBufferCache
Functions:
~ ___37-[ICBufferCache resetBufferAtOffset:]_block_invoke : 496 -> 500
~ -[ICBufferCache consumeBufferAtOffset:sized:] : 332 -> 344
~ ___45-[ICBufferCache consumeBufferAtOffset:sized:]_block_invoke : 272 -> 280
~ -[MSCameraFile createBufferCache] -> -[MSCameraFile createBufferCacheAtOffset:] : 124 -> 140
~ -[MSCameraFile readDataWithOptions:reply:] : 1616 -> 1872
CStrings:
+ "Buffer cache miss at offset: %lld, reading %lld bytes directly"
+ "ICReadBufferStreamOpen: %llu at offset: %lld"
+ "createBufferCacheAtOffset:"
- "ICReadBufferStreamOpen: %llu"
- "createBufferCache"
```
