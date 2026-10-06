## AuthKitUIService

> `/Applications/AuthKitUIService.app/AuthKitUIService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1934c` | `0x199fc` | **`+0x6b0`** |
| `__DATA.__objc_const` | `0x1f40` | `0x2330` | **`+0x3f0`** |
| `__TEXT.__objc_stubs` | `0x16a0` | `0x18e0` | **`+0x240`** |
| `__TEXT.__objc_methname` | `0x2891` | `0x2ac9` | **`+0x238`** |
| `__DATA.__data` | `0x5d0` | `0x690` | **`+0xc0`** |
| `__DATA.__objc_data` | `0x318` | `0x3d8` | **`+0xc0`** |
| `__DATA.__objc_selrefs` | `0x9a8` | `0xa60` | **`+0xb8`** |
| `__TEXT.__eh_frame` | `0x338` | `0x298` | **`-0xa0`** |
| `__TEXT.__oslogstring` | `0xa98` | `0xa08` | **`-0x90`** |
| `__DATA_CONST.__const` | `0xd50` | `0xce0` | **`-0x70`** |
| `__TEXT.__objc_classname` | `0x260` | `0x2d0` | **`+0x70`** |
| `__TEXT.__objc_methlist` | `0xb40` | `0xbb0` | **`+0x70`** |
| `__TEXT.__swift5_reflstr` | `0xac` | `0x112` | **`+0x66`** |
| `__TEXT.__swift5_typeref` | `0x34e` | `0x3a2` | **`+0x54`** |
| `__TEXT.__auth_stubs` | `0xb70` | `0xb30` | **`-0x40`** |
| `__TEXT.__const` | `0x494` | `0x4c4` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x560` | `0x530` | **`-0x30`** |
| `__TEXT.__constg_swiftt` | `0xf8` | `0x124` | **`+0x2c`** |
| `__TEXT.__swift5_fieldmd` | `0x90` | `0xb8` | **`+0x28`** |
| `__DATA_CONST.__auth_got` | `0x5c8` | `0x5a8` | **`-0x20`** |
| `__TEXT.__swift5_capture` | `0x2c8` | `0x2b0` | **`-0x18`** |
| `__TEXT.__objc_methtype` | `0x109a` | `0x10ab` | **`+0x11`** |
| `__DATA_CONST.__objc_protolist` | `0x60` | `0x70` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x48` | `0x50` | **`+0x8`** |
| `__DATA_CONST.__objc_protorefs` | `0x18` | `0x20` | **`+0x8`** |
| `__TEXT.__cstring` | `0xc4a` | `0xc45` | **`-0x5`** |
| `__TEXT.__swift5_types` | `0x14` | `0x18` | **`+0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-559.0.0.0.0
+560.125.4.1.0

+  - /System/Library/PrivateFrameworks/ProxCardKit.framework/ProxCardKit

+  - /usr/lib/swift/libswiftIntents.dylib

-  Functions: 502
-  Symbols:   339
-  CStrings:  640
+  Functions: 523
+  Symbols:   337
+  CStrings:  664
Symbols:
+ _$s10ObjectiveC22_convertBoolToObjCBoolyAA0eF0VSbF
+ _$sSo8NSObjectC10ObjectiveCE2eeoiySbAB_ABtFZ
+ _OBJC_CLASS_$_AKAppleIDServerUIContextController
+ _OBJC_CLASS_$_AKApprovalFlowContext
+ _OBJC_CLASS_$_PRXAction
+ _OBJC_CLASS_$_PRXCardContentViewController
+ _OBJC_METACLASS_$_PRXCardContentViewController
+ __swift_FORCE_LOAD_$_swiftIntents
+ _kAKApprovalFlowContextKey
- _$s10Foundation4DataV19_bridgeToObjectiveCSo6NSDataCyF
- _$s10Foundation4DataVMn
- _$s10Foundation4DataVSlAAMc
- _$sSS10FoundationE4data8encodingSSSgAA4DataVh_SSAAE8EncodingVtcfC
- _$sSS10FoundationE8EncodingV4utf8ACvgZ
- _$sSS10FoundationE8EncodingVMa
- _$sSlsE6prefixy11SubSequenceQzSiF
- _$sSlsE7isEmptySbvg
- _kAKApprovalFlowBaseURLStringKey
- _kAKApprovalFlowInitialXMLKey
- _kAKApprovalFlowServerRequestConfigurationKey
CStrings:
+ "$__lazy_storage_$_exitHandler"
+ "AuthKitUIService1"
+ "CONTINUE"
+ "Missing or malformed approval flow context in userInfo"
+ "Missing or unparseable RUI URL on approval flow context"
+ "No server UI context controller available; refusing to start a RemoteUI load the coordinator would deny"
+ "PRXFlowDelegate"
+ "_TtC16AuthKitUIService37ApprovalFlowCardContentViewController"
+ "_canShowWhileLocked"
+ "_isSecureForRemoteViewService"
+ "actionWithTitle:style:handler:"
+ "addAction:"
+ "approvalFlowContext"
+ "cardCopy"
+ "cardViewController"
+ "didLaunchRemoteUI"
+ "initWithContentView:"
+ "loadURL:postBody:"
+ "presentProxCardFlowWithDelegate:initialViewController:"
+ "primaryActionTitle"
+ "proxCardFlowDidDismiss"
+ "proxCardFlowWillPresent"
+ "pushInfo"
+ "ruiURLString"
+ "serverRequestConfiguration"
+ "serverUIContextController"
+ "setDismissalType:"
+ "setPushInfo:"
+ "setSubtitle:"
+ "setTelemetryFlowID:"
+ "setTitle:"
+ "showActivityIndicatorWithStatus:"
+ "subtitle"
+ "telemetryFlowID"
+ "title"
+ "v16@?0@\"PRXAction\"8"
- "<non-UTF8>"
- "Base URL is invalid or missing"
- "Missing baseURLString in userInfo"
- "Missing initial XML in userInfo"
- "No AKServerRequestConfiguration data in userInfo, delegate callbacks will not be signed"
- "No XML available for approval flow"
- "No userInfo in configuration context"
- "XML preview (first 200 bytes): %s"
- "baseURLString"
- "initial XML is empty"
- "initialXML"
- "loadData:baseURL:"
```
