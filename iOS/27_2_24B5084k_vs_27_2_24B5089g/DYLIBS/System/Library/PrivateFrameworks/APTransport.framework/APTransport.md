## APTransport

> `/System/Library/PrivateFrameworks/APTransport.framework/APTransport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb6550` | `0xb714c` | **`+0xbfc`** |
| `__TEXT.__cstring` | `0x3095b` | `0x30ebc` | **`+0x561`** |
| `__DATA.__data` | `0x14a0` | `0x1430` | **`-0x70`** |
| `__DATA_DIRTY.__data` | `0xc40` | `0xcb0` | **`+0x70`** |
| `__AUTH_CONST.__cfstring` | `0x6640` | `0x6660` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x2d30` | `0x2d50` | **`+0x20`** |
| `__DATA.__bss` | `0x130` | `0x120` | **`-0x10`** |
| `__DATA_DIRTY.__bss` | `0x2b8` | `0x2c8` | **`+0x10`** |

### Other Changes

```diff

-1005.7.1.0.0
+1005.8.1.0.0

-  Functions: 5349
-  Symbols:   4412
-  CStrings:  4565
+  Functions: 5364
+  Symbols:   4422
+  CStrings:  4587
Symbols:
+ GCC_except_table36
+ GCC_except_table45
+ GCC_except_table63
+ GCC_except_table69
+ GCC_except_table70
+ _APAdvertiserInfoCopyNameWithoutMDNSLabelSuffix
+ _APBrowserSetAirPlayInfo
+ _APTransportDeviceForwardAirPlayInfoToBrowser
+ _FigCFSetContainsValue
+ _FigCFSetGetCount
+ _OUTLINED_FUNCTION_61
+ _OUTLINED_FUNCTION_62
+ _OUTLINED_FUNCTION_63
+ _OUTLINED_FUNCTION_64
+ _OUTLINED_FUNCTION_65
+ _OUTLINED_FUNCTION_66
+ ___APBrowserSetAirPlayInfo_block_invoke
+ ___strlcpy_chk
- GCC_except_table26
- GCC_except_table31
- GCC_except_table34
- GCC_except_table61
- GCC_except_table62
- GCC_except_table67
- GCC_except_table68
- __APAdvertiserInfoCopyAndRemoveMDNSLabelSuffix
CStrings:
+ "%s external AirPlay info for device with id: %@ name: %'@ from source: [%{ptr}]"
+ "1005.8.1"
+ "APAdvertiserInfoCopyNameWithoutMDNSLabelSuffix"
+ "APBrowserSetAirPlayInfo"
+ "APTransportDeviceForwardAirPlayInfoToBrowser"
+ "Add external source [%{ptr}] for device with id: %@. %ld registered sources"
+ "Dropping external AirPlay info for device with id: %@. Last source withdrew"
+ "Dropping external AirPlay info for device with id: %@: deviceInfo caught up"
+ "External AirPlay info for device with id: %@ is held until Discovery finds it"
+ "ExternalInfoSources"
+ "Failed to create advertiser info for %@."
+ "OSStatus browser_addOrUpdateExternalAirPlayInfo(APBrowserRef, CFNumberRef, CFNumberRef, CFStringRef, CFDataRef)"
+ "OSStatus browser_createAdvertiserInfoForDevice(APBrowserRef, CFNumberRef, CFDictionaryRef, APAdvertiserInfoRef *)"
+ "OSStatus browser_removeExternalAirPlayInfo(APBrowserRef, CFNumberRef, CFNumberRef)"
+ "Remove external source [%{ptr}] for device with id: %@. %ld registered sources"
+ "Update"
+ "[%{ptr}] Deleted old capture file (%s; freed %lu bytes, %lu bytes / %lu file(s) remain): %s\n"
+ "[%{ptr}] Enforcing storage limits: %lu evictable capture file(s), %lu bytes across all captures (limits: %d file(s), %d bytes)\n"
+ "[%{ptr}] Most recent capture (%lu bytes) alone exceeds the %d-byte budget; keeping it instead of deleting the just-completed snoop\n"
+ "browser_addOrUpdateExternalAirPlayInfo"
+ "browser_copyEffectiveAirPlayInfo"
+ "browser_removeExternalAirPlayInfo"
+ "browser_setAirPlayInfo"
+ "over file-count limit"
+ "over size budget"
+ "void browser_dropExternalAirPlayInfoIfDeviceInfoCaughtUp(APBrowserRef, CFNumberRef, CFDictionaryRef)"
- "1005.7.1"
- "OSStatus browser_createAdvertiserInfoForDevice(CFAllocatorRef, CFDictionaryRef, LogCategory *, APAdvertiserInfoRef *)"
- "[%{ptr}] Deleted old capture file: %s\n"
- "_APAdvertiserInfoCopyAndRemoveMDNSLabelSuffix"
```
