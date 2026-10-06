## Spotlight

> `/System/Library/PrivateFrameworks/Spotlight.framework/Spotlight`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0xe8` | `0x468` | **`+0x380`** |
| `__DATA_DIRTY.__objc_data` | `0xe50` | `0xad0` | **`-0x380`** |
| `__DATA.__bss` | `0x910` | `0x9f0` | **`+0xe0`** |
| `__DATA_DIRTY.__bss` | `0x6b0` | `0x5d0` | **`-0xe0`** |
| `__TEXT.__text` | `0x9f968` | `0x9fa3c` | **`+0xd4`** |
| `__DATA.__data` | `0x768` | `0x6d8` | **`-0x90`** |
| `__DATA_DIRTY.__data` | `0x2f8` | `0x360` | **`+0x68`** |
| `__TEXT.__gcc_except_tab` | `0x5598` | `0x55ec` | **`+0x54`** |
| `__AUTH.__data` | `0x28` | `0x50` | **`+0x28`** |
| `__AUTH_CONST.__cfstring` | `0x2fe0` | `0x3000` | **`+0x20`** |
| `__TEXT.__cstring` | `0x355c` | `0x357c` | **`+0x20`** |
| `__TEXT.__oslogstring` | `0x5822` | `0x5842` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x2e50` | `0x2e58` | **`+0x8`** |

### Other Changes

```diff

-2465.1.2.0.0
+2465.1.3.0.0

-  CStrings:  937
+  CStrings:  939
CStrings:
+ "[App Exclusions] notification filtered, source %@ disabled"
+ "[App Exclusions] notification group missing creator"
+ "[App Exclusions] notification missing creator, filtered"
+ "[qid=%lu][SearchToolFederation] CoreSpotlight federationDisabledBundles: %@"
+ "com.apple.usernotifications.groups"
- "Skipping shortcut %@ for restricted app %@"
- "[ProtectedApps][personal answers] event from federation-disabled source %@ allowed through"
- "[qid=%lu][SearchToolFederation] CoreSpotlight disabledBundles: %@"
```
