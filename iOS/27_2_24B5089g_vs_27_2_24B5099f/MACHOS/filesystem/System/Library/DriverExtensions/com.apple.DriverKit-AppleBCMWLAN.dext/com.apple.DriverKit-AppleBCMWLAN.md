## com.apple.DriverKit-AppleBCMWLAN

> `/System/Library/DriverExtensions/com.apple.DriverKit-AppleBCMWLAN.dext/com.apple.DriverKit-AppleBCMWLAN`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x291f78` | `0x291d04` | **`-0x274`** |
| `__TEXT.__cstring` | `0x83602` | `0x834c7` | **`-0x13b`** |
| `__DATA_CONST.__const` | `0x211a8` | `0x211c0` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x5ff8` | `0x5ff0` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__osclassinfo`
- `__TEXT.__const`
- `__TEXT.__eh_frame`
- `__TEXT.__init_offsets`

### Other Changes

```diff

-1582.5.0.0.0
+1582.8.0.0.0

-  Symbols:   12070
-  CStrings:  13147
+  Symbols:   12073
+  CStrings:  13143
Symbols:
+ __ZN30AppleBCMWLANProximityInterface18setAGGRESSIVE_EDCAEP26apple80211_aggressive_edca
+ __ZThn112_N30AppleBCMWLANProximityInterface18setAGGRESSIVE_EDCAEP26apple80211_aggressive_edca
+ __ZThn128_N30AppleBCMWLANProximityInterface18setAGGRESSIVE_EDCAEP26apple80211_aggressive_edca
CStrings:
+ "\"AppleBCMWLANV3_driverkit-1582.8\""
+ "AppleBCMWLANV3_driverkit-1582.8"
+ "Sep 26 2026 03:37:36"
- "\"AppleBCMWLANV3_driverkit-1582.5\""
- "AppleBCMWLANV3_driverkit-1582.5"
- "Sep 14 2026 21:06:04"
- "[dk] %s@%d:ERROR: NAN attribute header runs past the end of the attribute list\n"
- "[dk] %s@%d:ERROR: NAN attribute length %u exceeds the remaining attribute list\n"
- "[dk] %s@%d:ERROR: NAN shared key descriptor body %u too short, minimum %u\n"
- "[dk] %s@%d:ERROR: NAN shared key descriptor key data length %u exceeds body %u\n"
```
