## AdPlatformsCommon

> `/System/Library/PrivateFrameworks/AdPlatformsCommon.framework/AdPlatformsCommon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xf88e4` | `0xfd01c` | **`+0x4738`** |
| `__DATA.__bss` | `0x16950` | `0x16e50` | **`+0x500`** |
| `__AUTH_CONST.__const` | `0xaef0` | `0xb3b8` | **`+0x4c8`** |
| `__TEXT.__const` | `0x14598` | `0x14828` | **`+0x290`** |
| `__TEXT.__cstring` | `0x611f` | `0x62bf` | **`+0x1a0`** |
| `__TEXT.__unwind_info` | `0x4cf0` | `0x4da8` | **`+0xb8`** |
| `__TEXT.__eh_frame` | `0x4534` | `0x45dc` | **`+0xa8`** |
| `__TEXT.__swift5_fieldmd` | `0x5a50` | `0x5af0` | **`+0xa0`** |
| `__TEXT.__oslogstring` | `0x29fb` | `0x2a8b` | **`+0x90`** |
| `__TEXT.__swift5_typeref` | `0x4427` | `0x44ab` | **`+0x84`** |
| `__AUTH_CONST.__objc_const` | `0xbc40` | `0xbcb8` | **`+0x78`** |
| `__DATA.__data` | `0x24b0` | `0x2520` | **`+0x70`** |
| `__TEXT.__swift5_capture` | `0x474` | `0x4d8` | **`+0x64`** |
| `__TEXT.__constg_swiftt` | `0x65c4` | `0x6624` | **`+0x60`** |
| `__TEXT.__objc_methlist` | `0x2cb4` | `0x2d04` | **`+0x50`** |
| `__DATA_DIRTY.__data` | `0x7f28` | `0x7ef8` | **`-0x30`** |
| `__TEXT.__swift5_assocty` | `0xa40` | `0xa70` | **`+0x30`** |
| `__TEXT.__swift5_reflstr` | `0x4218` | `0x4248` | **`+0x30`** |
| `__DATA_CONST.__objc_selrefs` | `0x1660` | `0x1688` | **`+0x28`** |
| `__TEXT.__swift5_proto` | `0x1014` | `0x103c` | **`+0x28`** |
| `__AUTH_CONST.__cfstring` | `0x1fe0` | `0x2000` | **`+0x20`** |
| `__TEXT.__swift5_types` | `0x6ac` | `0x6bc` | **`+0x10`** |
| `__DATA.__common` | `0x60` | `0x68` | **`+0x8`** |
| `__DATA_DIRTY.__objc_data` | `0x19d0` | `0x19d8` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x388` | `0x38c` | **`+0x4`** |

### Other Changes

```diff

-557.1.33.0.0
+557.2.8.0.0

-  Functions: 8043
+  Functions: 8121

-  CStrings:  909
+  CStrings:  924
CStrings:
+ "%{public}s: delivering event for purpose %ld"
+ "Failed to purge expired capping events"
+ "Failed to record ad interacted event: %@"
+ "Failed to record log discard event: %@"
+ "Failed to record place action event: %@"
+ "SLPIncrementalityFlagCheck"
+ "[ClientIdentifierProvider] Prewarm finished."
+ "[ClientIdentifierProvider] Prewarming %{public}@."
+ "[ClientIdentifierProvider] Returning %{public}@ from cache."
+ "[IdentifierBuilder] No configuration for type: %{public}@ source: %{public}d, caching the absence."
+ "availability"
+ "clientSessionId"
+ "com.apple.ap.admetrics"
+ "com.apple.ap.cappingdatabasepurge"
+ "com.apple.ap.identifierPrewarm"
+ "flagEnabledAtRequest"
+ "processId"
+ "source"
- "%{public}s: delivering event %{public}s"
- "[AccountInformation] Failed to load IDAccountsRecord from Keychain."
- "[ClientIdentifierProvider] Returning identifiers from cache."
```
