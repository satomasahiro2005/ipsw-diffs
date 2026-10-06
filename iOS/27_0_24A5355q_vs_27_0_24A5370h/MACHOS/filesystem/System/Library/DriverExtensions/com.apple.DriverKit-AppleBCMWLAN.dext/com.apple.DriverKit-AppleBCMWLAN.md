## com.apple.DriverKit-AppleBCMWLAN

> `/System/Library/DriverExtensions/com.apple.DriverKit-AppleBCMWLAN.dext/com.apple.DriverKit-AppleBCMWLAN`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x28e9a4` | `0x290760` | **`+0x1dbc`** |
| `__TEXT.__cstring` | `0x82d5c` | `0x82e33` | **`+0xd7`** |
| `__TEXT.__unwind_info` | `0x5fa8` | `0x5fb8` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__osclassinfo`
- `__TEXT.__const`
- `__TEXT.__eh_frame`
- `__TEXT.__init_offsets`

### Other Changes

```diff

-1580.55.0.0.0
+1580.59.0.0.0

-  Functions: 14156
-  Symbols:   12042
-  CStrings:  13114
+  Functions: 14163
+  Symbols:   12051
+  CStrings:  13117
Symbols:
+ _OUTLINED_FUNCTION_232
+ _OUTLINED_FUNCTION_258
+ _OUTLINED_FUNCTION_307
+ _OUTLINED_FUNCTION_570
+ _OUTLINED_FUNCTION_640
+ _OUTLINED_FUNCTION_641
+ _OUTLINED_FUNCTION_642
+ _OUTLINED_FUNCTION_643
+ _OUTLINED_FUNCTION_644
+ _ZN16AppleBCMWLANCore8is4388C2Ev
+ __ZN16AppleBCMWLANCore14getBtCoexStateEv
+ __ZN16AppleBCMWLANCore8is4388C2Ev
+ __ZN33AppleBCMWLANIO80211APSTAInterface13isLphsAllowedEv
- _OUTLINED_FUNCTION_234
- _OUTLINED_FUNCTION_259
- _OUTLINED_FUNCTION_309
- _OUTLINED_FUNCTION_573
CStrings:
+ "\"AppleBCMWLANV3_driverkit-1580.59\""
+ "AppleBCMWLANV3_driverkit-1580.59"
+ "Jun 16 2026 21:46:18"
+ "[dk] %s@%d:%s arg is null\n"
+ "[dk] %s@%d:Report LQM to User Land %d, ivars->fAverageRSSI %d\n"
+ "[dk] %s@%d:WARNING: Could not delete existing attributes, issueSyncSetIOVAR failed with retVal [ %d ]. Continuing anyway...\n"
- "\"AppleBCMWLANV3_driverkit-1580.55\""
- "AppleBCMWLANV3_driverkit-1580.55"
- "May 29 2026 20:17:14"
```
