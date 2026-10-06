## SiriAudioSupport

> `/System/Library/PrivateFrameworks/SiriAudioSupport.framework/SiriAudioSupport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x231f50` | `0x233314` | **`+0x13c4`** |
| `__TEXT.__oslogstring` | `0x230fe` | `0x231ee` | **`+0xf0`** |
| `__TEXT.__unwind_info` | `0x4920` | `0x4938` | **`+0x18`** |
| `__DATA.__data` | `0x2228` | `0x2238` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x1360` | `0x1370` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `0x457b` | `0x4587` | **`+0xc`** |
| `__AUTH_CONST.__auth_got` | `0x20a0` | `0x2098` | **`-0x8`** |
| `__DATA.__common` | `0x148` | `0x150` | **`+0x8`** |

### Other Changes

```diff

-3600.33.17.0.0
+3605.20.1.0.0

-  Functions: 8541
-  Symbols:   2417
-  CStrings:  2698
+  Functions: 8546
+  Symbols:   2418
+  CStrings:  2701
Symbols:
+ _symbolic _____Sg 12MediaIntents11AudioSearchV10ItemSourceO
+ _symbolic _____Sg_ABt 12MediaIntents11AudioSearchV10ItemSourceO
- _symbolic _____Sg 18AppIntentsServices0bC0O14InterfaceIdiomO
CStrings:
+ "InstalledAppProvider#installedApps filtered %ld user-excluded app(s)"
+ "SiriAudioAppPredictor#resetExcludedAppBundleIds clearing excluded apps"
+ "SiriAudioAppPredictor#setExcludedAppBundleIds setting %ld excluded app(s)"
```
