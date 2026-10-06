## SessionCore

> `/System/Library/PrivateFrameworks/SessionCore.framework/SessionCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x14a53c` | `0x14d628` | **`+0x30ec`** |
| `__TEXT.__oslogstring` | `0x76d4` | `0x7914` | **`+0x240`** |
| `__TEXT.__swift5_typeref` | `0x2dab` | `0x2dcf` | **`+0x24`** |
| `__TEXT.__unwind_info` | `0x2648` | `0x2650` | **`+0x8`** |

### Other Changes

```diff

-310.0.0.0.0
+311.0.0.0.0

-  Functions: 3551
-  Symbols:   1749
-  CStrings:  832
+  Functions: 3557
+  Symbols:   1751
+  CStrings:  839
Symbols:
+ _symbolic SS3key______5valuet 11SessionCore24ActivityParticipantEventV
+ _symbolic _____ySS_____G s18_DictionaryStorageC 11SessionCore24ActivityParticipantEventV
CStrings:
+ "Activity request blocked by alert scene target without user consent: %{private}s"
+ "Activity request blocked by content source without user consent: %{private}s"
+ "Activity request blocked by scene target without user consent: %{private}s"
+ "Alert scene target does not have user consent to request activities %{public}s"
+ "Alert scene target does not include NSSupportsLiveActivities key in its Info.plist %{public}s"
+ "Alert scene target has too many activities"
+ "Alert scene target is restricted: %{private}s"
+ "Ending activity %{public}s because authorization was revoked for %{public}s"
+ "Scene target does not have user consent to request activities %{public}s"
+ "Scene target does not include NSSupportsLiveActivities key in its Info.plist %{public}s"
+ "Scene target has too many activities"
- "Ending activity because authorization was revoked: %{public}s"
- "No scene target has user consent to request activities"
- "Target does not have user consent to request activities %{public}s"
- "User consent granted by scene target %{public}s"
```
