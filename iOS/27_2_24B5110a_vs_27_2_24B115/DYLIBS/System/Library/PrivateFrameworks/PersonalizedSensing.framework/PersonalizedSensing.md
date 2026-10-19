## PersonalizedSensing

> `/System/Library/PrivateFrameworks/PersonalizedSensing.framework/PersonalizedSensing`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x10464` | `0x101b4` | **`-0x2b0`** |
| `__TEXT.__cstring` | `0x15c2` | `0x14f0` | **`-0xd2`** |
| `__AUTH_CONST.__cfstring` | `0x1bc0` | `0x1b40` | **`-0x80`** |
| `__DATA_CONST.__objc_selrefs` | `0xde0` | `0xdd0` | **`-0x10`** |
| `__TEXT.__gcc_except_tab` | `0x31c` | `0x310` | **`-0xc`** |
| `__DATA_CONST.__got` | `0x1f8` | `0x1f0` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x608` | `0x600` | **`-0x8`** |

### Other Changes

```diff

-  Symbols:   994
-  CStrings:  355
+  Symbols:   993
+  CStrings:  356
Symbols:
- _OBJC_CLASS_$_NSAssertionHandler
Functions:
~ -[MODefaultsManager objectForKey:] : 332 -> 248
~ -[MODefaultsManager objectForKeyWithoutLog:] : 260 -> 164
~ -[MODefaultsManager deleteObjectForKey:] : 312 -> 236
~ -[MODefaultsManager setObject:forKey:] : 348 -> 264
~ -[MODefaultsManager setObjectWithoutLog:forKey:] : 216 -> 100
~ -[MOConnectionManager _getActiveConnection] : 784 -> 700
~ -[MOConnectionManager withProxyProvider:proxyHandler:onError:] : 488 -> 412
~ +[MODictionaryEncoder encodeDictionary:] : 408 -> 320
~ +[MODictionaryEncoder decodeToDictionary:] : 408 -> 320
~ +[MOPlatformInfo isSeedBuild] : 8 -> 112
CStrings:
+ "PlatformInfoOverrideIsSeedBuild"
```
