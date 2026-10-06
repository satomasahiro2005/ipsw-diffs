## HomeSettings

> `/System/Library/PreferenceBundles/HomeSettings.bundle/HomeSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_CONST.__cfstring` | `0x1220` | `0x1480` | **`+0x260`** |
| `__TEXT.__cstring` | `0x1010` | `0x1225` | **`+0x215`** |
| `__DATA_CONST.__objc_intobj` | `0x18` | `0x180` | **`+0x168`** |
| `__DATA_CONST.__objc_arraydata` | `0x28` | `0x128` | **`+0x100`** |
| `__TEXT.__text` | `0x5aa8` | `0x5b94` | **`+0xec`** |
| `__TEXT.__objc_methname` | `0x2b38` | `0x2bc0` | **`+0x88`** |
| `__DATA_CONST.__objc_arrayobj` | `0x18` | `0x78` | **`+0x60`** |
| `__TEXT.__ustring` | `0x220` | `0x25e` | **`+0x3e`** |
| `__TEXT.__objc_stubs` | `0x18a0` | `0x18c0` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x448` | `0x460` | **`+0x18`** |
| `__DATA.__objc_selrefs` | `0xc30` | `0xc40` | **`+0x10`** |
| `__DATA.__objc_const` | `0xa18` | `0xa20` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0xc1c` | `0xc24` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA.__objc_ivar`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_classname`
- `__TEXT.__objc_methtype`
- `__TEXT.__oslogstring`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1241.1.7.1.3
+1263.1.0.1.2

-  Symbols:   216
-  CStrings:  663
+  Symbols:   219
+  CStrings:  684
Symbols:
+ _HFPreferencesSimulateMatterCommandErrorKey
+ _HFPreferencesSimulateMatterCommandErrorStatusKey
+ _HFPreferencesSimulateMatterCommandErrorTypeKey
CStrings:
+ "  ↳ Error Type"
+ "  ↳ Status Code"
+ "Busy (0x9C)"
+ "Command Response"
+ "CommandInvalidInState / InvalidInMode / InvalidSet (0x03)"
+ "Interaction Status"
+ "InvalidInState (0xCB)"
+ "RVC BatteryLow (0x48)"
+ "RVC DustBinFull (0x43)"
+ "RVC DustBinMissing (0x42)"
+ "RVC FailedToFindChargingDock / CleaningInProgress (0x40)"
+ "RVC MopCleaningPadMissing (0x47)"
+ "RVC Stuck (0x41)"
+ "RVC WaterTankEmpty (0x44)"
+ "RVC WaterTankLidOpen (0x46)"
+ "RVC WaterTankMissing (0x45)"
+ "Simulate Matter Command Error"
+ "UnableToCompleteOperation / GenericFailure (0x02)"
+ "UnableToStartOrResume / UnsupportedMode / UnsupportedArea (0x01)"
+ "ho_globalListChooserSpecifierWithName:key:values:titles:defaultValue:"
+ "homeManager:didRemoveCurrentAccessoryWithRegulatoryEraseRequired:"
```
