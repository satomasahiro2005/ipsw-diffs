## com.apple.DriverKit-AppleBCMWLAN

> `/System/Library/DriverExtensions/com.apple.DriverKit-AppleBCMWLAN.dext/com.apple.DriverKit-AppleBCMWLAN`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2913ac` | `0x2914f4` | **`+0x148`** |
| `__TEXT.__cstring` | `0x830d4` | `0x831be` | **`+0xea`** |
| `__DATA_CONST.__const` | `0x21120` | `0x21148` | **`+0x28`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__got`
- `__DATA_CONST.__osclassinfo`
- `__TEXT.__const`
- `__TEXT.__eh_frame`
- `__TEXT.__init_offsets`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1580.68.0.0.0
+1580.73.0.0.0

-  Functions: 14174
-  Symbols:   12057
-  CStrings:  13130
+  Functions: 14186
+  Symbols:   12064
+  CStrings:  13133
Symbols:
+ _ZNK28AppleBCMWLANBusInterfacePCIe22checkPCIeMMIOReadinessEv
+ __ZN11AppleOLYHAL32reportInitFailureWithChipResetDKEP8OSStringb
+ __ZN17IO80211Controller34reportsPerInterfacePeerCacheLimitsEv
+ __ZN24AppleBCMWLANNANInterface26getPEER_CACHE_MAXIMUM_SIZEEP34apple80211_peer_cache_maximum_size
+ __ZNK28AppleBCMWLANBusInterfacePCIe22checkPCIeMMIOReadinessEv
+ __ZThn112_N24AppleBCMWLANNANInterface26getPEER_CACHE_MAXIMUM_SIZEEP34apple80211_peer_cache_maximum_size
+ __ZThn128_N24AppleBCMWLANNANInterface26getPEER_CACHE_MAXIMUM_SIZEEP34apple80211_peer_cache_maximum_size
+ __ZThn48_N17IO80211Controller34reportsPerInterfacePeerCacheLimitsEv
- __ZN11AppleOLYHAL19reportInitFailureDKEP8OSString
CStrings:
+ "\"AppleBCMWLANV3_driverkit-1580.73\""
+ "AppleBCMWLANV3_driverkit-1580.73"
+ "Aug  3 2026 21:23:43"
+ "[dk] %s@%d:APB CB not accessible before readOTP\n"
+ "[dk] %s@%d:Dext PCIe config not ready for MMIO.\n"
+ "[dk] %s@%d:Failed to read or parse OTP data. Failing start\n"
+ "[dk] %s@%d:PCI config not MMIO-ready before readOTP (cmd=0x%04x bar0=0x%08x)\n"
+ "[dk] %s@%d:Pre-OTP PCI cfg cmd=0x%04x bar0=0x%08x\n"
+ "[dk] %s@%d:Pre-OTP read checks failed! Failing start\n"
+ "[dk] %s@%d:PreOTP PCI config read failed"
+ "[dk] %s@%d:dext APB gate ENTER (checking APB before readOTP)\n"
+ "checkPCIeMMIOReadiness"
- "\"AppleBCMWLANV3_driverkit-1580.68\""
- "AppleBCMWLANV3_driverkit-1580.68"
- "Jul 10 2026 21:53:28"
- "[dk] %s@%d:APB CB error-log registers before readOTP:\n"
- "[dk] %s@%d:CB0[0x%x] = 0x%08x\n"
- "[dk] %s@%d:CB0[0x%x] read failed: 0x%x\n"
- "[dk] %s@%d:CB1[0x%x] = 0x%08x\n"
- "[dk] %s@%d:CB1[0x%x] read failed: 0x%x\n"
- "[dk] %s@%d:Failed to read OTP data\n"
```
