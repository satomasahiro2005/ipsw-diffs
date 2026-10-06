## NearbyInteraction

> `/System/Library/Frameworks/NearbyInteraction.framework/NearbyInteraction`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x36158` | `0x36640` | **`+0x4e8`** |
| `__AUTH.__objc_data` | `0x410` | `—` | **`-0x410`** |
| `__DATA_DIRTY.__objc_data` | `0xd20` | `0x1130` | **`+0x410`** |
| `__AUTH_CONST.__cfstring` | `0x5a20` | `0x5ac0` | **`+0xa0`** |
| `__TEXT.__gcc_except_tab` | `0x5938` | `0x59bc` | **`+0x84`** |
| `__TEXT.__cstring` | `0x512f` | `0x51a7` | **`+0x78`** |
| `__AUTH_CONST.__objc_const` | `0x7928` | `0x7988` | **`+0x60`** |
| `__TEXT.__objc_methlist` | `0x4328` | `0x4378` | **`+0x50`** |
| `__DATA_CONST.__objc_selrefs` | `0x1f90` | `0x1fc8` | **`+0x38`** |
| `__AUTH_CONST.__const` | `0x438` | `0x458` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x2b0` | `0x2d0` | **`+0x20`** |
| `__TEXT.__const` | `0x500` | `0x520` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x2180` | `0x21a0` | **`+0x20`** |
| `__DATA.__bss` | `0x5a0` | `0x590` | **`-0x10`** |
| `__DATA.__objc_ivar` | `0x500` | `0x508` | **`+0x8`** |
| `__DATA_CONST.__const` | `0xd30` | `0xd38` | **`+0x8`** |
| `__DATA_DIRTY.__bss` | `0x98` | `0xa0` | **`+0x8`** |

### Other Changes

```diff

-557.0.0.0.0
+560.0.0.0.0

-  Functions: 1560
-  Symbols:   2925
-  CStrings:  936
+  Functions: 1568
+  Symbols:   2939
+  CStrings:  941
Symbols:
+ -[NIDLTDOAMeasurement initWithAnchorAddress:clusterInitiatorAddress:measurementType:coordinatesType:transmitTime:rawTransmitTime:receiveTime:rawReceiveTime:signalStrength:carrierFrequencyOffset:responderClockFrequencyOffset:coordinates:floorElevation:]
+ -[NIDLTDOAMeasurement rawReceiveTime]
+ -[NIDLTDOAMeasurement rawTransmitTime]
+ -[NIDLTDOAMeasurement setRawReceiveTime:]
+ -[NIDLTDOAMeasurement setRawTransmitTime:]
+ -[NISystemEventNotifier _setSMBClkCfg:]
+ GCC_except_table25
+ GCC_except_table363
+ GCC_except_table364
+ GCC_except_table368
+ GCC_except_table372
+ _OBJC_IVAR_$_NIDLTDOAMeasurement._rawReceiveTime
+ _OBJC_IVAR_$_NIDLTDOAMeasurement._rawTransmitTime
+ __NISystemEventDictKey_SMBClkCfgValue
+ ___39-[NISystemEventNotifier _setSMBClkCfg:]_block_invoke
+ ___39-[NISystemEventNotifier _setSMBClkCfg:]_block_invoke_2
- GCC_except_table365
- GCC_except_table369
CStrings:
+ "Raw Receive Time: [%llu], "
+ "Raw Transmit Time: [%llu], "
+ "RawReceiveTime"
+ "RawTransmitTime"
+ "SystemEventDictKey_SMBClkCfgValue"
+ "\xa2"
- "\x82"
```
