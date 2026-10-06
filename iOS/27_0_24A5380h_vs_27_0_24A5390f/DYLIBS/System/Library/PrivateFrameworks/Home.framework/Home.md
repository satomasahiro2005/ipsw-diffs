## Home

> `/System/Library/PrivateFrameworks/Home.framework/Home`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3c268c` | `0x3c4508` | **`+0x1e7c`** |
| `__AUTH_CONST.__objc_const` | `0x4c458` | `0x4c5b0` | **`+0x158`** |
| `__TEXT.__swift5_reflstr` | `0xd50` | `0xe90` | **`+0x140`** |
| `__AUTH.__objc_data` | `0xa4c0` | `0xa5e8` | **`+0x128`** |
| `__TEXT.__eh_frame` | `0x74d8` | `0x75a8` | **`+0xd0`** |
| `__TEXT.__constg_swiftt` | `0x2164` | `0x222c` | **`+0xc8`** |
| `__AUTH.__data` | `0x13c0` | `0x1480` | **`+0xc0`** |
| `__DATA.__data` | `0x76c8` | `0x7778` | **`+0xb0`** |
| `__TEXT.__const` | `0x58c0` | `0x5970` | **`+0xb0`** |
| `__TEXT.__swift5_fieldmd` | `0x112c` | `0x11c4` | **`+0x98`** |
| `__TEXT.__cstring` | `0x34be3` | `0x34c7a` | **`+0x97`** |
| `__TEXT.__unwind_info` | `0xeac0` | `0xeb40` | **`+0x80`** |
| `__TEXT.__objc_methlist` | `0x2c9d4` | `0x2ca1c` | **`+0x48`** |
| `__AUTH_CONST.__cfstring` | `0x273e0` | `0x27420` | **`+0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0x13030` | `0x13070` | **`+0x40`** |
| `__TEXT.__oslogstring` | `0x1d855` | `0x1d895` | **`+0x40`** |
| `__TEXT.__swift5_typeref` | `0x2c53` | `0x2c8d` | **`+0x3a`** |
| `__DATA_DIRTY.__data` | `0xef0` | `0xf10` | **`+0x20`** |
| `__DATA.__common` | `0x160` | `0x178` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x3248` | `0x3258` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x1880` | `0x1888` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x18c` | `0x194` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0x538` | `0x540` | **`+0x8`** |

### Other Changes

```diff

-1232.3.0.0.0
+1238.0.0.0.0

-  Functions: 21250
-  Symbols:   30296
-  CStrings:  8539
+  Functions: 21285
+  Symbols:   30308
+  CStrings:  8542
Symbols:
+ -[HFAccessorySettingItem _shouldHideAppleIntelligenceReportSettingForNonOwner]
+ _OBJC_CLASS_$__TtCE4HomeCSo20HFPredictionsManager10ScoreCache
+ _OBJC_METACLASS_$__TtCE4HomeCSo20HFPredictionsManager10ScoreCache
+ __DATA__TtCE4HomeCSo20HFPredictionsManager10ScoreCache
+ __INSTANCE_METHODS__TtCE4HomeCSo20HFPredictionsManager10ScoreCache
+ __IVARS__TtCE4HomeCSo20HFPredictionsManager10ScoreCache
+ __METACLASS_DATA__TtCE4HomeCSo20HFPredictionsManager10ScoreCache
+ _symbolic SDy__________GSg 10Foundation4UUIDV 13HomeDataModel0C18AnalyticsUtilitiesO010PredictionF13ScoringValuesV
+ _symbolic _____ 4Home28MatterAccessoryRepresentableC14ProtectedState33_87938DBE0F8705385ED1AB739C091D54LLV
+ _symbolic _____ So20HFPredictionsManagerC4HomeE10ScoreCacheC
+ _symbolic _____y_____G 15Synchronization5MutexVAARi_zrlE 4Home28MatterAccessoryRepresentableC14ProtectedState33_87938DBE0F8705385ED1AB739C091D54LLV
+ _symbolic _____y_____G 15Synchronization5_CellVAARi_zrlE 4Home28MatterAccessoryRepresentableC14ProtectedState33_87938DBE0F8705385ED1AB739C091D54LLV
CStrings:
+ "Apple Intelligence Report setting is only available to the home owner."
+ "Failed to fetch today's events"
+ "HFPredictionsManager froze %{public}ld prediction scores for module display"
+ "These settings should be hidden since they are not supported for this accessory"
- "Failed to determine today event count"
```
