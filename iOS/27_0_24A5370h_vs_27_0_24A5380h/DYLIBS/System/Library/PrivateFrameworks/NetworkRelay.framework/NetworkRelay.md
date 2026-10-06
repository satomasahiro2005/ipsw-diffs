## NetworkRelay

> `/System/Library/PrivateFrameworks/NetworkRelay.framework/NetworkRelay`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x78998` | `0x78c1c` | **`+0x284`** |
| `__TEXT.__cstring` | `0xfec4` | `0xffbd` | **`+0xf9`** |
| `__AUTH_CONST.__cfstring` | `0x5080` | `0x5120` | **`+0xa0`** |
| `__AUTH_CONST.__objc_const` | `0x50f0` | `0x5150` | **`+0x60`** |
| `__AUTH.__objc_data` | `0x50` | `—` | **`-0x50`** |
| `__DATA_DIRTY.__objc_data` | `0xb90` | `0xbe0` | **`+0x50`** |
| `__TEXT.__objc_methlist` | `0x1f1c` | `0x1f4c` | **`+0x30`** |
| `__DATA_CONST.__const` | `0xce8` | `0xd10` | **`+0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0x1088` | `0x10a8` | **`+0x20`** |
| `__DATA.__bss` | `0x280` | `0x268` | **`-0x18`** |
| `__DATA_DIRTY.__bss` | `0xe0` | `0xf8` | **`+0x18`** |
| `__DATA.__data` | `0x208` | `0x1f8` | **`-0x10`** |
| `__DATA_DIRTY.__data` | `0x10` | `0x20` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x548` | `0x550` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x278` | `0x280` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x9e8` | `0x9f0` | **`+0x8`** |

### Other Changes

```diff

-914.0.1.0.4
+914.0.14.502.2

-  Functions: 1041
-  Symbols:   2253
-  CStrings:  1956
+  Functions: 1046
+  Symbols:   2261
+  CStrings:  1964
Symbols:
+ -[NRDeviceMeshParticipantInfo isCurrentRouteThroughPrimaryAssistDevice]
+ -[NRDeviceMeshParticipantInfo setIsCurrentRouteThroughPrimaryAssistDevice:]
+ -[NRDevicePreferences quickRelayPresence]
+ -[NRDevicePreferences setQuickRelayPresence:]
+ GCC_except_table128
+ GCC_except_table138
+ GCC_except_table140
+ GCC_except_table277
+ GCC_except_table332
+ GCC_except_table357
+ GCC_except_table450
+ GCC_except_table461
+ GCC_except_table697
+ GCC_except_table710
+ GCC_except_table714
+ GCC_except_table718
+ GCC_except_table724
+ GCC_except_table728
+ GCC_except_table732
+ GCC_except_table736
+ GCC_except_table759
+ GCC_except_table762
+ GCC_except_table771
+ GCC_except_table773
+ GCC_except_table775
+ GCC_except_table782
+ GCC_except_table784
+ GCC_except_table835
+ GCC_except_table837
+ GCC_except_table852
+ _OBJC_IVAR_$_NRDeviceMeshParticipantInfo._isCurrentRouteThroughPrimaryAssistDevice
+ _OBJC_IVAR_$_NRDevicePreferences._internalQuickRelayPresence
+ _createStringFromNRQuickRelayPresence
+ _nrXPCKeyDevicePreferencesQuickRelayPresence
- GCC_except_table122
- GCC_except_table135
- GCC_except_table137
- GCC_except_table274
- GCC_except_table329
- GCC_except_table354
- GCC_except_table445
- GCC_except_table456
- GCC_except_table692
- GCC_except_table700
- GCC_except_table709
- GCC_except_table713
- GCC_except_table719
- GCC_except_table723
- GCC_except_table727
- GCC_except_table731
- GCC_except_table754
- GCC_except_table757
- GCC_except_table761
- GCC_except_table768
- GCC_except_table770
- GCC_except_table772
- GCC_except_table774
- GCC_except_table830
- GCC_except_table832
- GCC_except_table847
CStrings:
+ "%s%.30s:%-4d %@ setting quick relay presence from %@ to %@"
+ "-[NRDevicePreferences setQuickRelayPresence:]"
+ "DevicePreferencesQuickRelayPresence"
+ "NRMeshParticipantInfo[appID=%@ primaryAssistCapable=%@ selectedAsPrimaryAssist=%@ currentRouteThroughPrimaryAssist=%@]"
+ "invalid"
+ "isCurrentRouteThroughPrimaryAssistDevice"
+ "offline"
+ "online"
+ "unknown"
- "NRMeshParticipantInfo[appID=%@ primaryAssistCapable=%@ selectedAsPrimaryAssist=%@]"
```
