## AppleMediaServicesKitInternal

> `/System/Library/PrivateFrameworks/AppleMediaServicesKitInternal.framework/AppleMediaServicesKitInternal`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x60ab60` | `0x613df0` | **`+0x9290`** |
| `__TEXT.__const` | `0x538a8` | `0x54188` | **`+0x8e0`** |
| `__TEXT.__gcc_except_tab` | `0x2d4c0` | `0x2dbf4` | **`+0x734`** |
| `__AUTH_CONST.__const` | `0x26ff0` | `0x275f0` | **`+0x600`** |
| `__TEXT.__cstring` | `0xdb24` | `0xdee5` | **`+0x3c1`** |
| `__TEXT.__unwind_info` | `0xd7e0` | `0xda08` | **`+0x228`** |
| `__AUTH.__data` | `0x4d0` | `0x358` | **`-0x178`** |
| `__DATA_DIRTY.__data` | `0x4a0` | `0x610` | **`+0x170`** |
| `__DATA_DIRTY.__objc_data` | `0x4d0` | `0x620` | **`+0x150`** |
| `__AUTH.__objc_data` | `0xc00` | `0xac0` | **`-0x140`** |
| `__DATA_CONST.__const` | `0x1c78` | `0x1d28` | **`+0xb0`** |
| `__AUTH_CONST.__objc_const` | `0x3608` | `0x36a8` | **`+0xa0`** |
| `__TEXT.__oslogstring` | `0xc9c` | `0xd2c` | **`+0x90`** |
| `__TEXT.__eh_frame` | `0x4454` | `0x44dc` | **`+0x88`** |
| `__DATA.__bss` | `0x8468` | `0x84e8` | **`+0x80`** |
| `__TEXT.__swift5_capture` | `0x1e4` | `0x258` | **`+0x74`** |
| `__TEXT.__swift5_typeref` | `0x1ba8` | `0x1c12` | **`+0x6a`** |
| `__TEXT.__swift5_reflstr` | `0xb63` | `0xbb3` | **`+0x50`** |
| `__AUTH_CONST.__auth_got` | `0x1450` | `0x1488` | **`+0x38`** |
| `__TEXT.__swift5_fieldmd` | `0x1070` | `0x1098` | **`+0x28`** |
| `__DATA.__data` | `0x1b40` | `0x1b60` | **`+0x20`** |
| `__TEXT.__constg_swiftt` | `0x129c` | `0x12b8` | **`+0x1c`** |
| `__DATA_CONST.__objc_selrefs` | `0xa38` | `0xa50` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x190` | `0x19c` | **`+0xc`** |
| `__DATA_CONST.__got` | `0x660` | `0x668` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0x468` | `0x460` | **`-0x8`** |
| `__TEXT.__swift5_proto` | `0x488` | `0x48c` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0x1c0` | `0x1c4` | **`+0x4`** |

### Other Changes

```diff

-2.0.21.0.0
+2.0.23.0.0

+  - /usr/lib/swift/libswiftSynchronization.dylib

-  Functions: 10612
-  Symbols:   661
-  CStrings:  2085
+  Functions: 10750
+  Symbols:   666
+  CStrings:  2118
Symbols:
+ _OBJC_CLASS_$_NSHashTable
+ __os_feature_enabled_impl
+ _swift_bridgeObjectRetain_n
+ _swift_release_x1
+ _swift_unknownObjectWeakDestroy
CStrings:
+ " | Age = "
+ " | Cache-Control = "
+ " | Expires = "
+ " | computed expiration = "
+ " | incoming = "
+ "%@-%@"
+ "2.0.23"
+ "Added external app integrity headers."
+ "Bag invalidated for matching originKey = "
+ "Bag invalidated."
+ "Bag invalidation skipped, originKey mismatch. stored = "
+ "Bag invalidation skipped, source not loaded. originKey = "
+ "Bag response Date = "
+ "Bag service invalidated."
+ "Cache evicted for cacheKey %s. Forwarding eviction for originKey %s."
+ "Failed to get external app integrity data."
+ "Finished invalidating cached bag data source for originKey = "
+ "GameOverlay"
+ "Games"
+ "ImmutableBag forcibly expired. Original expiration = "
+ "Mutable bags force-expired after data source invalidation."
+ "MutableBag forcibly expired."
+ "MutableBag invalidating data source for originKey = "
+ "MutableBag snapshot replaced. expiration = "
+ "No IExternalAppIntegrityProvider configured, skipping request."
+ "Recorded cache mapping for cacheKey %s, originKey %s, URL %s."
+ "X-Apple-I-88CC-99DE-EE63-2736"
+ "app-context"
+ "com.apple.GameOverlayUI"
+ "com.apple.games"
+ "externalAppIntegrity/paths"
+ "gameoverlayui_push_bag"
+ "games_push_bag"
+ "gseui"
+ "hardwareBrand"
+ "x-apple-client-app-verification"
- "%@-%s"
- "2.0.21"
- "\xd3"
```
