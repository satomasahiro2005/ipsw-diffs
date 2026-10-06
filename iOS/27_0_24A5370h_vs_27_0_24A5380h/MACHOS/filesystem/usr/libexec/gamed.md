## gamed

> `/usr/libexec/gamed`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x298d54` | `0x29984c` | **`+0xaf8`** |
| `__TEXT.__objc_methname` | `0x23627` | `0x23907` | **`+0x2e0`** |
| `__TEXT.__objc_stubs` | `0x1b7e0` | `0x1ba40` | **`+0x260`** |
| `__DATA_CONST.__got` | `0x1ff8` | `0x2208` | **`+0x210`** |
| `__TEXT.__objc_methlist` | `0xe06c` | `0xe19c` | **`+0x130`** |
| `__DATA_CONST.__cfstring` | `0xc3a0` | `0xc2a0` | **`-0x100`** |
| `__DATA.__objc_data` | `0x7120` | `0x71e8` | **`+0xc8`** |
| `__DATA.__objc_const` | `0x20ee0` | `0x20f88` | **`+0xa8`** |
| `__DATA.__objc_selrefs` | `0x8170` | `0x8208` | **`+0x98`** |
| `__TEXT.__cstring` | `0x19501` | `0x19591` | **`+0x90`** |
| `__TEXT.__unwind_info` | `0x8db0` | `0x8e10` | **`+0x60`** |
| `__TEXT.__auth_stubs` | `0x48e0` | `0x4920` | **`+0x40`** |
| `__TEXT.__constg_swiftt` | `0x1bf0` | `0x1c2c` | **`+0x3c`** |
| `__DATA.__data` | `0x4d20` | `0x4d50` | **`+0x30`** |
| `__TEXT.__swift5_fieldmd` | `0x1770` | `0x1798` | **`+0x28`** |
| `__DATA_CONST.__auth_got` | `0x2488` | `0x24a8` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x14408` | `0x14428` | **`+0x20`** |
| `__TEXT.__const` | `0x133e0` | `0x13400` | **`+0x20`** |
| `__TEXT.__objc_classname` | `0x2a07` | `0x2a27` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0x1269` | `0x1289` | **`+0x20`** |
| `__DATA.__common` | `0xb20` | `0xb28` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x968` | `0x970` | **`+0x8`** |
| `__TEXT.__eh_frame` | `0xbb20` | `0xbb28` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x1e8` | `0x1ec` | **`+0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methtype`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-821.0.16.0.0
+821.0.18.0.0

-  Functions: 12194
-  Symbols:   2529
-  CStrings:  10543
+  Functions: 12255
+  Symbols:   2532
+  CStrings:  10566
Symbols:
+ _$s12GameServices0A7FiltersV18recentlyPlayedOnlySbvs
+ _$s12GameServices0A7FiltersV7defaultACvgZ
+ _$s12GameServices0A7FiltersVMa
+ _$s12GameServices16ListGamesRequestV7filtersAA0A7FiltersVvs
- _swift_runtimeSupportsNoncopyableTypes
CStrings:
+ "GKLastContactsIntegrationConsentVersionDisplayedForHashedPlayerID_"
+ "GKLastFriendSuggestionsVersionDisplayedForHashedPlayerID_"
+ "GKLastGamesCrossUseConsentNoticeVersionDisplayedForHashedPlayerID_"
+ "GKLastGamesPrivacyNoticeVersionDisplayedForHashedPlayerID_"
+ "GKLastPersonalizationVersionDisplayedForHashedPlayerID_"
+ "GKLastPrivacyNoticeVersionDisplayedForHashedPlayerID_"
+ "GKLastProfilePrivacyVersionDisplayedForHashedPlayerID_"
+ "GKLastWelcomeWhatsNewCopyVersionDisplayedForHashedPlayerID_"
+ "GKOnboardingNoticeConfiguration"
+ "GKOnboardingNoticeMigrationVersion"
+ "GameDaemonCore.GKOnboardingNoticeConfiguration"
+ "T@\"GKOnboardingNoticeConfiguration\",N,R"
+ "_gkAsHexString"
+ "_gkSHA256HashData"
+ "contactsIntegrationConsentVersionWithPlayerID:"
+ "friendSuggestionsVersionWithPlayerID:"
+ "gamesCrossUseConsentNoticeVersionWithPlayerID:"
+ "gamesPrivacyNoticeVersionWithPlayerID:"
+ "migrateLegacyKeysIfNeeded"
+ "onboardingNoticeConfiguration"
+ "personalizationVersionWithPlayerID:"
+ "privacyNoticeVersionWithPlayerID:"
+ "profilePrivacyVersionWithPlayerID:"
+ "setContactsIntegrationConsentVersion:playerID:"
+ "setFriendSuggestionsVersion:playerID:"
+ "setGamesCrossUseConsentNoticeVersion:playerID:"
+ "setGamesPrivacyNoticeVersion:playerID:"
+ "setPersonalizationVersion:playerID:"
+ "setPrivacyNoticeVersion:playerID:"
+ "setProfilePrivacyVersion:playerID:"
+ "setWelcomeWhatsNewCopyVersion:playerID:"
+ "welcomeWhatsNewCopyVersionWithPlayerID:"
- "GKLastContactsIntegrationConsentVersionDisplayedForHashedPlayerID_%@"
- "GKLastFriendSuggestionsVersionDisplayedForHashedPlayerID_%@"
- "GKLastGamesCrossUseConsentNoticeVersionDisplayedForHashedPlayerID_%@"
- "GKLastGamesPrivacyNoticeVersionDisplayedForHashedPlayerID_%@"
- "GKLastPersonalizationVersionDisplayedForHashedPlayerID_%@"
- "GKLastPrivacyNoticeVersionDisplayedForHashedPlayerID_%@"
- "GKLastProfilePrivacyVersionDisplayedForHashedPlayerID_%@"
- "GKLastWelcomeWhatsNewCopyVersionDisplayedForHashedPlayerID_%@"
- "setLastNoticeVersionForSignedInPlayerWithName:lastVersion:"
```
