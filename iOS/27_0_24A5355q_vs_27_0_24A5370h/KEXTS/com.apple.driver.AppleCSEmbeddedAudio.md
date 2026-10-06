## com.apple.driver.AppleCSEmbeddedAudio

> `com.apple.driver.AppleCSEmbeddedAudio`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__auth_stubs` | `0x0` | `0x260` | **`+0x260`** |
| `__TEXT_EXEC.__text` | `0x9c8c` | `0x9c80` | **`-0xc`** |

### Other Changes

```diff

-1000.40.0.0.0
+1000.41.0.0.0
Functions:
~ __ZN29AppleEmbeddedButtonController16completeHPDetectEbP12OSDictionaryPK8OSSymbol : 2636 -> 2644
~ __ZN17AppleCSCodecMikey18processMikeyStatusEhhhh : 692 -> 680
~ sub_fffffff0089d7f8c -> sub_fffffff0089eef58 : 236 -> 228
```
