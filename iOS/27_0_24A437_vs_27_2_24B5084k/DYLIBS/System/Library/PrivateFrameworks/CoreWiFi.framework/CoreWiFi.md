## CoreWiFi

> `/System/Library/PrivateFrameworks/CoreWiFi.framework/CoreWiFi`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1ff0f4` | `0x200cb0` | **`+0x1bbc`** |
| `__TEXT.__oslogstring` | `0x2115b` | `0x21496` | **`+0x33b`** |
| `__AUTH_CONST.__objc_const` | `0x182b0` | `0x185a0` | **`+0x2f0`** |
| `__TEXT.__cstring` | `0x258be` | `0x259e6` | **`+0x128`** |
| `__TEXT.__objc_methlist` | `0x12674` | `0x12794` | **`+0x120`** |
| `__AUTH.__objc_data` | `0x1448` | `0x1538` | **`+0xf0`** |
| `__DATA_CONST.__objc_selrefs` | `0x9358` | `0x93b8` | **`+0x60`** |
| `__TEXT.__unwind_info` | `0x6dc8` | `0x6e28` | **`+0x60`** |
| `__AUTH_CONST.__const` | `0x50d8` | `0x5118` | **`+0x40`** |
| `__TEXT.__gcc_except_tab` | `0x7694` | `0x76d0` | **`+0x3c`** |
| `__DATA_CONST.__const` | `0x5cc8` | `0x5cf0` | **`+0x28`** |
| `__AUTH_CONST.__cfstring` | `0x1d1e0` | `0x1d200` | **`+0x20`** |
| `__AUTH_CONST.__objc_intobj` | `0x3e28` | `0x3e40` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x1500` | `0x1518` | **`+0x18`** |
| `__DATA_CONST.__objc_classlist` | `0x400` | `0x418` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x9c0` | `0x9d0` | **`+0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x390` | `0x3a0` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x1078` | `0x1070` | **`-0x8`** |
| `__DATA_DIRTY.__bss` | `0x2e0` | `0x2e8` | **`+0x8`** |

### Other Changes

```diff

-1030.84.4.1.0
+1032.5.0.0.0

-  Functions: 9449
-  Symbols:   1185
-  CStrings:  6362
+  Functions: 9481
+  Symbols:   1187
+  CStrings:  6380
Symbols:
+ _OBJC_CLASS_$_CWFColocatedConsentResult
+ _OBJC_METACLASS_$_CWFColocatedConsentResult
CStrings:
+ "<%@: status=%ld, networks=%@>"
+ "@?<v@?@\"CWFColocatedConsentResult\"@\"NSError\">8@?0"
+ "DisallowCarrierProfileNetworksInLockdownMode"
+ "[corewifi] %{public}s (%{public}s:%u) Colocated consent evaluation timed out"
+ "[corewifi] %{public}s (%{public}s:%u) Colocated consent for %@: %@"
+ "[corewifi] %{public}s (%{public}s:%u) Colocated consent scan failed, reporting no candidate (%@)"
+ "[corewifi] %{public}s (%{public}s:%u) Colocated consent scanned %lu channel(s) in %llums, %lu result(s): %@"
+ "[corewifi] %{public}s (%{public}s:%u) No 5GHz channel to scan for %@, nothing colocated can qualify"
+ "[corewifi] %{public}s (%{public}s:%u) Split-SSID candidate %@ has no same-LAN history, consent required"
+ "[corewifi] %{public}s (%{public}s:%u) interface was NULL"
+ "[corewifi] AUTO-JOIN: Card capabilities not configured"
+ "[corewifi] AUTO-JOIN: Skipping known network that is not allowed in lockdown mode (network=%{public}@, addReason=%{public}@)"
+ "[corewifi] AUTO-JOIN: Will NOT use low power scan core (LPSC)"
+ "[corewifi] Network warning flags changed, current=%lu interfaceName=%@, posting XPC event"
+ "[corewifi] Network warning flags did not change, skipping event, current=%lu interfaceName=%@"
+ "__CWFClassifyColocated"
+ "__CWFColocatedScanParameters"
+ "__CWFPerformColocatedNetworkScan"
+ "__CWFPerformColocatedNetworkScanForInterface"
+ "__CWFPerformColocatedNetworkScanForInterface_block_invoke_2"
- "[corewifi] Network warning flags changed previous=%lu current=%lu interfaceName=%@, posting XPC event"
- "[corewifi] Network warning flags did not change, skipping event, previous=%lu current=%lu interfaceName=%@"
```
