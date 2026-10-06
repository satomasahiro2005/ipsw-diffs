## AppleAccountSettings

> `/System/Library/PreferenceBundles/AccountSettings/AppleAccountSettings.bundle/AppleAccountSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x421a0` | `0x42c84` | **`+0xae4`** |
| `__TEXT.__objc_methname` | `0xae74` | `0xb0e6` | **`+0x272`** |
| `__TEXT.__objc_stubs` | `0x7f60` | `0x80a0` | **`+0x140`** |
| `__TEXT.__objc_methlist` | `0x2b40` | `0x2c48` | **`+0x108`** |
| `__DATA.__objc_const` | `0x64c8` | `0x6598` | **`+0xd0`** |
| `__TEXT.__objc_methtype` | `0x2b1d` | `0x2b9d` | **`+0x80`** |
| `__DATA.__objc_selrefs` | `0x2b20` | `0x2b98` | **`+0x78`** |
| `__DATA.__data` | `0x1098` | `0x10f8` | **`+0x60`** |
| `__DATA_CONST.__got` | `0x9f0` | `0xa40` | **`+0x50`** |
| `__DATA_CONST.__cfstring` | `0x1a20` | `0x1a60` | **`+0x40`** |
| `__TEXT.__auth_stubs` | `0x1490` | `0x14b0` | **`+0x20`** |
| `__TEXT.__cstring` | `0x1fe7` | `0x2007` | **`+0x20`** |
| `__TEXT.__objc_classname` | `0x824` | `0x844` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x1168` | `0x1188` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0xa58` | `0xa68` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0x594` | `0x5a4` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x324` | `0x330` | **`+0xc`** |
| `__DATA_CONST.__objc_protolist` | `0x108` | `0x110` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-588.0.0.0.0
+589.125.4.0.0

-  Functions: 1505
-  Symbols:   648
-  CStrings:  2710
+  Functions: 1521
+  Symbols:   657
+  CStrings:  2736
Symbols:
+ _NSURLErrorDomain
+ _OBJC_CLASS_$_AKFeatureManager
+ _OBJC_CLASS_$_NSThread
+ _kAKAnalyticsEventActivateElement
+ _kAKAnalyticsEventLoadURL
+ _kAKAnalyticsEventLoadURLComplete
+ _kAKAnalyticsEventProcessHook
+ _kAKAnalyticsEventRenderUI
+ _kAKAnalyticsEventReportError
+ _kAKProcessHook
+ _objc_getProperty
+ _objc_setProperty_atomic_copy
- OBJC_IVAR_$_AAUIFMIPHeaderDeviceInfoPageSurrogate._appleAccount
- OBJC_IVAR_$_AAUIFMIPHeaderDeviceInfoPageSurrogate._device
- OBJC_IVAR_$_AAUIFMIPHeaderDeviceInfoPageSurrogate._remoteUIPage
CStrings:
+ "@72@0:8@16@24@32@40@48@?56@?64"
+ "RemoteUITelemetryDelegate"
+ "T@\"NSString\",C,V_altDSID"
+ "T@\"NSString\",C,V_remoteUITelemetryFlowID"
+ "_aatAccountActivitySpecifierProvider"
+ "_altDSID"
+ "_applyTelemetryFlowIDToContext:"
+ "_configureRemoteController:"
+ "_configureRemoteController:mintFlowID:"
+ "_mintRemoteUITelemetryFlowIDIfNeeded:"
+ "_remoteUITelemetryFlowID"
+ "aaui_analyticsEventWithRUITelemetryElement:eventName:altDSID:flowID:error:"
+ "aaui_encodedElementNameWithDomainPrefix:element:activeElements:"
+ "com.apple.remoteui"
+ "didLoadURL:error:"
+ "escapeOffer"
+ "hooksFor:accountManager:telemetryFlowID:"
+ "isFeatureEnabled:"
+ "isMainThread"
+ "loadDataRequest:identifier:data:serverUILoadDelegate:telemetryFlowID:preparation:completion:"
+ "loadRemoteRequest:identifier:serverUILoadDelegate:telemetryFlowID:preparation:completion:"
+ "processedElementWithError:forElement:"
+ "remoteUITelemetryFlowID"
+ "setRemoteUITelemetryFlowID:"
+ "setTelemetryDelegate:"
+ "v24@0:8@\"RUITelemetryElement\"16"
+ "v32@0:8@\"NSError\"16@\"RUITelemetryElement\"24"
+ "v32@0:8@\"RUITelemetryElement\"16@\"NSError\"24"
+ "willActivateElement:"
+ "willDisplayUI:"
+ "willLoadURL:"
+ "willProcessHook:"
+ "\xf0\xa2"
- "@56@0:8@16@24@32@?40@?48"
- "hooksFor:accountManager:"
- "loadDataRequest:identifier:data:serverUILoadDelegate:preparation:completion:"
- "loadRemoteRequest:identifier:serverUILoadDelegate:preparation:completion:"
- "setInsetsLayoutMarginsFromSafeArea:"
- "setPreservesSuperviewLayoutMargins:"
- "\xf0\x92"
```
