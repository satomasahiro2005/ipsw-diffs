## WirelessProximity

> `/System/Library/PrivateFrameworks/WirelessProximity.framework/WirelessProximity`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x32cd0` | `0x32e1c` | **`+0x14c`** |
| `__AUTH_CONST.__cfstring` | `0x2f00` | `0x2f80` | **`+0x80`** |
| `__TEXT.__cstring` | `0x3b52` | `0x3bae` | **`+0x5c`** |
| `__AUTH_CONST.__objc_const` | `0x3168` | `0x3198` | **`+0x30`** |
| `__TEXT.__gcc_except_tab` | `0x668` | `0x698` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x2bf4` | `0x2c0c` | **`+0x18`** |
| `__DATA_CONST.__const` | `0x798` | `0x7a8` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x1710` | `0x1720` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x21c` | `0x220` | **`+0x4`** |

### Other Changes

```diff

-2700.37.0.0.0
+2700.41.1.1.0

+  - /System/Library/PrivateFrameworks/Rapport.framework/Rapport

-  Functions: 1967
-  Symbols:   1865
-  CStrings:  953
+  Functions: 1969
+  Symbols:   1870
+  CStrings:  957
Symbols:
+ -[WPAdvertisingRequest needsIdentity]
+ -[WPAdvertisingRequest setNeedsIdentity:]
+ _OBJC_IVAR_$_WPAdvertisingRequest._needsIdentity
+ _WPHeySiriNeedsIdentity
+ _WPHeySiriRPIdentity
+ __ZNSt3__110unique_ptrIN2BT12TimeAndTimer5Timer9TimerImplENS_14default_deleteIS4_EEE5resetB9fqe220106EPS4_
+ __ZNSt3__110unique_ptrIN2BT12TimeAndTimer5TimerENS_14default_deleteIS3_EEE5resetB9fqe220106EPS3_
+ __ZNSt3__119__shared_weak_count16__release_sharedB9fqe220106Ev
- __ZNSt3__110unique_ptrIN2BT12TimeAndTimer5Timer9TimerImplENS_14default_deleteIS4_EEE5resetB9fqe220100EPS4_
- __ZNSt3__110unique_ptrIN2BT12TimeAndTimer5TimerENS_14default_deleteIS3_EEE5resetB9fqe220100EPS3_
- __ZNSt3__119__shared_weak_count16__release_sharedB9fqe220100Ev
CStrings:
+ "LECAHap"
+ "LECAHapLow"
+ "LECATmap"
+ "LECATmapLow"
+ "WPHeySiriNeedsIdentity"
+ "WPHeySiriRPIdentity"
+ "kDeviceRPIdentity"
+ "kNeedsIdentity"
- "LECA1"
- "LECA2"
- "LECA3"
- "LECA4"
```
