## PersonalizedSensing

> `/System/Library/PrivateFrameworks/PersonalizedSensing.framework/PersonalizedSensing`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x101b4` | `0x10464` | **`+0x2b0`** |
| `__TEXT.__cstring` | `0x14f0` | `0x15c2` | **`+0xd2`** |
| `__AUTH_CONST.__cfstring` | `0x1b40` | `0x1bc0` | **`+0x80`** |
| `__DATA_CONST.__objc_selrefs` | `0xdd0` | `0xde0` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0x310` | `0x31c` | **`+0xc`** |
| `__DATA_CONST.__got` | `0x1f0` | `0x1f8` | **`+0x8`** |
| `__TEXT.__const` | `0x138` | `0x140` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x600` | `0x608` | **`+0x8`** |

### Other Changes

```diff

-417.0.0.0.0
+502.0.5.0.0

-  Symbols:   993
-  CStrings:  356
+  Symbols:   994
+  CStrings:  355
Symbols:
+ _OBJC_CLASS_$_NSAssertionHandler
Functions:
~ -[MODefaultsManager objectForKey:] : 248 -> 332
~ -[MODefaultsManager objectForKeyWithoutLog:] : 164 -> 260
~ -[MODefaultsManager deleteObjectForKey:] : 236 -> 312
~ -[MODefaultsManager setObject:forKey:] : 264 -> 348
~ -[MODefaultsManager setObjectWithoutLog:forKey:] : 100 -> 216
~ -[MOConnectionManager _getActiveConnection] : 700 -> 784
~ -[MOConnectionManager withProxyProvider:proxyHandler:onError:] : 412 -> 488
~ +[MODictionaryEncoder encodeDictionary:] : 320 -> 408
~ +[MODictionaryEncoder decodeToDictionary:] : 320 -> 408
~ +[MOPlatformInfo isSeedBuild] : 112 -> 8
CStrings:
- "PlatformInfoOverrideIsSeedBuild"
```
