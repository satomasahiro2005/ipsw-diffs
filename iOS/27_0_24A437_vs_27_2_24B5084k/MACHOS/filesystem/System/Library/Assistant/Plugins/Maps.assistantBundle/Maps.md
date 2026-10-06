## Maps

> `/System/Library/Assistant/Plugins/Maps.assistantBundle/Maps`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_CONST.__const` | `0x180d0` | `0x18a28` | **`+0x958`** |
| `__DATA_CONST.__cfstring` | `0x8420` | `0x87c0` | **`+0x3a0`** |
| `__TEXT.__cstring` | `0x9efc` | `0xa28f` | **`+0x393`** |
| `__TEXT.__text` | `0x14524` | `0x14684` | **`+0x160`** |
| `__DATA_CONST.__objc_arraydata` | `0x98` | `0xc8` | **`+0x30`** |
| `__DATA_CONST.__objc_intobj` | `0x828` | `0x7f8` | **`-0x30`** |
| `__DATA_CONST.__objc_dictobj` | `—` | `0x28` | **`+0x28`** |
| `__DATA_CONST.__objc_doubleobj` | `0x3b0` | `0x3c0` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x540` | `0x548` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arrayobj`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-2972.30.6.12.58
+2972.31.6.17.21

-  Functions: 1338
-  Symbols:   1295
-  CStrings:  1975
+  Functions: 1361
+  Symbols:   1319
+  CStrings:  2004
Symbols:
+ _MapsConfig_ChromeContextCoordinationStuckQueueRecoveryTimeout
+ _MapsConfig_DisplayedVisitedPlacesMinimumDisplayDuration
+ _MapsConfig_EnrichmentOnboardingSheetSuppressed
+ _MapsConfig_JetEnabled
+ _MapsConfig_JetForceFallbackJetPack
+ _MapsConfig_JetHighlightRenderedUI
+ _MapsConfig_JetIgnoreJetPackCache
+ _MapsConfig_JetIgnoreJetPackSigning
+ _MapsConfig_JetInspectable
+ _MapsConfig_JetPackProduct
+ _MapsConfig_JetPackProductURLs
+ _MapsConfig_JetPackURLOverride
+ _MapsConfig_JetUseProductionBundledPack
+ _MapsConfig_MapModePickerZoomTransitionEnabled
+ _MapsConfig_MapsHomeMaxRecentsMac
+ _MapsConfig_MapsHomeRecentsRowsPerColumn
+ _MapsConfig_MapsHomeRecentsRowsPerColumnMac
+ _MapsConfig_PreferencesScreenUseJetRendering
+ _MapsConfig_SearchHomeRecentMaxColumns
+ _MapsConfig_SearchHomeRecentMaxColumnsMac
+ _MapsConfig_SearchHomeRecentRowsPerColumn
+ _MapsConfig_SearchHomeRecentRowsPerColumnEnriched
+ _MapsConfig_SearchHomeRecentRowsPerColumnMac
+ _MapsConfig_SidebarSheetWidthMultiplierMac
+ _OBJC_CLASS_$_NSConstantDictionary
- _MapsConfig_FlyoverMaxSearchNotification
CStrings:
+ "Carry"
+ "ChromeContextCoordinationStuckQueueRecoveryTimeout"
+ "DisplayedVisitedPlacesMinimumDisplayDuration"
+ "EnrichmentOnboardingSheetSuppressed"
+ "JetEnabled"
+ "JetForceFallbackJetPack"
+ "JetHighlightRenderedUI"
+ "JetIgnoreJetPackCache"
+ "JetIgnoreJetPackSigning"
+ "JetInspectable"
+ "JetPackProduct"
+ "JetPackProductURLs"
+ "JetPackURLOverride"
+ "JetUseProductionBundledPack"
+ "MapModePickerZoomTransitionEnabled"
+ "MapsHomeMaxRecentsMac"
+ "MapsHomeRecentsRowsPerColumn"
+ "MapsHomeRecentsRowsPerColumnMac"
+ "PreferencesScreenUseJetRendering"
+ "Presubmission"
+ "SearchHomeRecentMaxColumns"
+ "SearchHomeRecentMaxColumnsMac"
+ "SearchHomeRecentRowsPerColumn"
+ "SearchHomeRecentRowsPerColumnEnriched"
+ "SearchHomeRecentRowsPerColumnMac"
+ "SidebarSheetWidthMultiplierMac"
+ "https://apps.mzstatic.com/content/3e22681091624b6eaf72730309a89491/maps.jetpack"
+ "https://apps.mzstatic.com/content/cdcbf37fc6874dbf9112a58d7d53ce28/maps.jetpack"
+ "https://apps.mzstatic.com/content/e2206ce7479244289fdbee6d39042dd9/maps.jetpack"
+ "iOS Production"
- "FlyoverMaxSearchNotificationKey"
```
