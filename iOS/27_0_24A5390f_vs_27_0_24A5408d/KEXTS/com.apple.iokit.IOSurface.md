## com.apple.iokit.IOSurface

> `com.apple.iokit.IOSurface`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x332bc` | `0x33968` | **`+0x6ac`** |
| `__TEXT.__os_log` | `0x3501` | `0x3779` | **`+0x278`** |
| `__TEXT.__cstring` | `0x3355` | `0x33b7` | **`+0x62`** |
| `__TEXT_EXEC.__auth_stubs` | `0x900` | `0x940` | **`+0x40`** |
| `__DATA_CONST.__auth_got` | `0x480` | `0x4a0` | **`+0x20`** |
| `__TEXT.__const` | `0x40` | `0x60` | **`+0x20`** |

### Other Changes

```diff

-402.5.0.0.0
-  Functions: 1324
+402.8.0.0.0
+  Functions: 1330

-  CStrings:  638
+  CStrings:  649
CStrings:
+ "%s"
+ "%s%u"
+ "%s: Couldn't allocate range allocator for graphics memory\n"
+ "112"
+ "1211111212221212121122222212212111212211111112211112221111112111122111121222212222122221222212222122221222212222112111112221112211112112222222222112"
+ "Failed to install %s memory region; checking in anyway\n"
+ "IOSurface: /vram declares %u carveout(s) but %u resolved; positions are ambiguous, installing none\n"
+ "IOSurface: /vram declares %u carveout(s) but none resolved\n"
+ "IOSurface: couldn't count /vram's reg tuples; assuming a single carveout\n"
+ "IOSurface: discovered %u display carveout(s) in /vram\n"
+ "IOSurfaceDeviceMemoryRegion: Couldn't get device memory with index %u for service %s\n"
+ "IOSurfaceDeviceMemoryRegion: Couldn't map device memory\n"
+ "IOSurfaceDeviceMemoryRegion: zero-length device memory with index %u for service %s\n"
+ "reg"
+ "virtual bool IOSurfaceDeviceMemoryRegion::init(IOSurfaceRoot *, OSDictionary *, const char *, uint32_t, uint32_t)"
- "1112"
- "121111121222121212112222221221211121221111111211112221111112111122111121222212222122221222212222122221222212222112111112221112211112112222222222112"
- "PurpleGfxMem"
- "ScalableMemory"
```
