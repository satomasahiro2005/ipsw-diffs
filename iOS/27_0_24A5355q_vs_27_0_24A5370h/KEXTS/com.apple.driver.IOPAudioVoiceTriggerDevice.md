## com.apple.driver.IOPAudioVoiceTriggerDevice

> `com.apple.driver.IOPAudioVoiceTriggerDevice`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__auth_stubs` | `0x0` | `0x5f0` | **`+0x5f0`** |
| `__TEXT_EXEC.__text` | `0xcef0` | `0xcf14` | **`+0x24`** |
| `__TEXT.__cstring` | `0x2e02` | `0x2e0b` | **`+0x9`** |

### Other Changes

```diff

-600.4.0.0.0
+600.6.0.0.0

-  CStrings:  214
+  CStrings:  215
Functions:
~ __ZN26IOPAudioVoiceTriggerDevice16_enableListeningEb : 584 -> 580
~ sub_fffffff00a19faf8 -> sub_fffffff00a2281a4 : 268 -> 276
~ sub_fffffff00a19fc04 -> sub_fffffff00a2282b8 : 376 -> 384
~ _u8__v_visit : 476 -> 472
~ _voicetriggerdebug_voicetriggerdebug_debuggetsecuredata : 1004 -> 1008
~ sub_fffffff00a1a1840 -> sub_fffffff00a229efc : 848 -> 856
~ sub_fffffff00a1a3e78 -> sub_fffffff00a22c53c : 244 -> 252
~ sub_fffffff00a1a3f6c -> sub_fffffff00a22c638 : 344 -> 352
CStrings:
+ "19:52:50"
+ "19:52:51"
+ "Jun 18 2026"
- "02:44:01"
- "Jun  5 2026"
```
