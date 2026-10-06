## AXSoundDetectionUI

> `/System/Library/PrivateFrameworks/AXSoundDetectionUI.framework/AXSoundDetectionUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x56288` | `0x56f1c` | **`+0xc94`** |
| `__TEXT.__oslogstring` | `0x623e` | `0x65b6` | **`+0x378`** |
| `__AUTH_CONST.__objc_const` | `0x3500` | `0x3678` | **`+0x178`** |
| `__TEXT.__objc_methlist` | `0x22bc` | `0x2344` | **`+0x88`** |
| `__DATA_CONST.__objc_selrefs` | `0x1540` | `0x15b8` | **`+0x78`** |
| `__AUTH.__objc_data` | `0x1538` | `0x1588` | **`+0x50`** |
| `__TEXT.__cstring` | `0xff4` | `0x1029` | **`+0x35`** |
| `__TEXT.__unwind_info` | `0x1048` | `0x1078` | **`+0x30`** |
| `__AUTH_CONST.__cfstring` | `0xf40` | `0xf60` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0x324` | `0x344` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x678` | `0x690` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x1ac` | `0x1b8` | **`+0xc`** |
| `__AUTH_CONST.__auth_got` | `0xa08` | `0xa10` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0xf8` | `0x100` | **`+0x8`** |

### Other Changes

```diff

-534.0.0.0.0
+536.0.0.0.0

-  Functions: 1447
-  Symbols:   1641
-  CStrings:  622
+  Functions: 1460
+  Symbols:   1669
+  CStrings:  636
Symbols:
+ -[AXSDCustomDetectionController _customPipedInFileUpdated]
+ -[AXSDCustomDetectionController _processCustomPipedFile]
+ -[AXSDKShotModelManager analyzeFileAtURL:forDetectors:]
+ -[_AXSDKShotFileObserver .cxx_destruct]
+ -[_AXSDKShotFileObserver detectorIdentifier]
+ -[_AXSDKShotFileObserver hasNotified]
+ -[_AXSDKShotFileObserver request:didFailWithError:]
+ -[_AXSDKShotFileObserver request:didProduceResult:]
+ -[_AXSDKShotFileObserver requestDidComplete:]
+ -[_AXSDKShotFileObserver setDetectorIdentifier:]
+ -[_AXSDKShotFileObserver setHasNotified:]
+ GCC_except_table563
+ _OBJC_CLASS_$_NSProcessInfo
+ _OBJC_CLASS_$_SNClassificationResult
+ _OBJC_CLASS_$__AXSDKShotFileObserver
+ _OBJC_IVAR_$_AXSDCustomDetectionController._customPipeQueue
+ _OBJC_IVAR_$__AXSDKShotFileObserver._detectorIdentifier
+ _OBJC_IVAR_$__AXSDKShotFileObserver._hasNotified
+ _OBJC_METACLASS_$__AXSDKShotFileObserver
+ __OBJC_$_INSTANCE_METHODS__AXSDKShotFileObserver
+ __OBJC_$_INSTANCE_VARIABLES__AXSDKShotFileObserver
+ __OBJC_$_PROP_LIST__AXSDKShotFileObserver
+ __OBJC_CLASS_PROTOCOLS_$__AXSDKShotFileObserver
+ __OBJC_CLASS_RO_$__AXSDKShotFileObserver
+ __OBJC_METACLASS_RO_$__AXSDKShotFileObserver
+ ___37-[AXSDCustomDetectionController init]_block_invoke
+ ___58-[AXSDCustomDetectionController _customPipedInFileUpdated]_block_invoke
+ _objc_setProperty_nonatomic_copy
CStrings:
+ ".claimed-%@"
+ "Custom Detection Controller (file): analyzing %@ against %lu detector(s)"
+ "Custom Detection Controller (file): doorbell rang but no enabled custom detectors; discarding %@"
+ "Custom Detection Controller (file): doorbell rang but no file at %@; ignoring"
+ "Custom Detection Controller (file): finished analyzing %@"
+ "Custom Detection Controller (file): no enabled custom detectors to analyze against %@"
+ "Custom Detection Controller (file): no requests added for %@; aborting analysis"
+ "Custom Detection Controller (file): request complete"
+ "Custom Detection Controller (file): request failed: %@"
+ "Custom Detection Controller (file): result — top class id=%@ confidence=%f (%lu classes)"
+ "Custom Detection Controller (file): unable to add request for %@: %@"
+ "Custom Detection Controller (file): unable to build request for %@ %@"
+ "Custom Detection Controller (file): unable to create file analyzer for %@: %@"
+ "com.apple.accessibility.kshot.custompipe"
```
