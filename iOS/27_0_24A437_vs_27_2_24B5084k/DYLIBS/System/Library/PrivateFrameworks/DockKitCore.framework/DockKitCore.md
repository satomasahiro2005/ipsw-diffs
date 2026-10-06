## DockKitCore

> `/System/Library/PrivateFrameworks/DockKitCore.framework/DockKitCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x12e138` | `0x12ed48` | **`+0xc10`** |
| `__TEXT.__oslogstring` | `0x2c89` | `0x3259` | **`+0x5d0`** |
| `__AUTH.__objc_data` | `0x4cd8` | `0x5070` | **`+0x398`** |
| `__AUTH_CONST.__objc_const` | `0x7058` | `0x7288` | **`+0x230`** |
| `__TEXT.__objc_methlist` | `0x2974` | `0x2b34` | **`+0x1c0`** |
| `__TEXT.__constg_swiftt` | `0x475c` | `0x485c` | **`+0x100`** |
| `__TEXT.__const` | `0x9438` | `0x9518` | **`+0xe0`** |
| `__AUTH.__data` | `0x1a50` | `0x1b10` | **`+0xc0`** |
| `__TEXT.__swift5_fieldmd` | `0x35fc` | `0x3664` | **`+0x68`** |
| `__TEXT.__unwind_info` | `0x53d0` | `0x5410` | **`+0x40`** |
| `__DATA.__data` | `0x1c90` | `0x1cc0` | **`+0x30`** |
| `__TEXT.__cstring` | `0x1eea` | `0x1f1a` | **`+0x30`** |
| `__DATA_CONST.__objc_classlist` | `0x210` | `0x238` | **`+0x28`** |
| `__TEXT.__swift5_typeref` | `0x2854` | `0x2872` | **`+0x1e`** |
| `__TEXT.__swift5_types` | `0x298` | `0x2ac` | **`+0x14`** |
| `__TEXT.__swift5_reflstr` | `0x2991` | `0x29a1` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x1360` | `0x1368` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x1150` | `0x1158` | **`+0x8`** |

### Other Changes

```diff

-414.0.0.0.0
+431.0.0.0.0

-  Functions: 7575
-  Symbols:   1896
-  CStrings:  489
+  Functions: 7623
+  Symbols:   1932
+  CStrings:  514
Symbols:
+ _OBJC_CLASS_$_DockCoreCameraCaptureClientSink
+ _OBJC_CLASS_$_DockCoreCertClientSink
+ _OBJC_CLASS_$_DockCoreClientSink
+ _OBJC_CLASS_$_DockCoreDebugClientSink
+ _OBJC_CLASS_$_DockCoreWeakClientProxy
+ _OBJC_METACLASS_$_DockCoreCameraCaptureClientSink
+ _OBJC_METACLASS_$_DockCoreCertClientSink
+ _OBJC_METACLASS_$_DockCoreClientSink
+ _OBJC_METACLASS_$_DockCoreDebugClientSink
+ _OBJC_METACLASS_$_DockCoreWeakClientProxy
+ __DATA_DockCoreCameraCaptureClientSink
+ __DATA_DockCoreCertClientSink
+ __DATA_DockCoreClientSink
+ __DATA_DockCoreDebugClientSink
+ __DATA_DockCoreWeakClientProxy
+ __INSTANCE_METHODS_DockCoreCameraCaptureClientSink
+ __INSTANCE_METHODS_DockCoreCertClientSink
+ __INSTANCE_METHODS_DockCoreClientSink
+ __INSTANCE_METHODS_DockCoreDebugClientSink
+ __INSTANCE_METHODS_DockCoreWeakClientProxy
+ __IVARS_DockCoreWeakClientProxy
+ __METACLASS_DATA_DockCoreCameraCaptureClientSink
+ __METACLASS_DATA_DockCoreCertClientSink
+ __METACLASS_DATA_DockCoreClientSink
+ __METACLASS_DATA_DockCoreDebugClientSink
+ __METACLASS_DATA_DockCoreWeakClientProxy
+ __PROTOCOLS_DockCoreCameraCaptureClientSink
+ __PROTOCOLS_DockCoreCertClientSink
+ __PROTOCOLS_DockCoreClientSink
+ __PROTOCOLS_DockCoreDebugClientSink
+ ___swift_closure_destructor.126Tm
+ ___swift_closure_destructor.130Tm
+ ___swift_closure_destructor.1878Tm
+ ___swift_closure_destructor.269Tm
+ ___swift_closure_destructor.414Tm
+ ___swift_closure_destructor.541Tm
+ ___swift_closure_destructor.547Tm
+ ___swift_closure_destructor.645Tm
+ ___swift_closure_destructor.732Tm
+ ___swift_closure_destructor.834Tm
+ ___swift_closure_destructor.857Tm
+ ___swift_project_boxed_opaque_existential_0
+ _symbolic _____ 11DockKitCore0aC10ClientSinkC
+ _symbolic _____ 11DockKitCore0aC14CertClientSinkC
+ _symbolic _____ 11DockKitCore0aC15DebugClientSinkC
+ _symbolic _____ 11DockKitCore0aC15WeakClientProxyC
+ _symbolic _____ 11DockKitCore0aC23CameraCaptureClientSinkC
- ___swift_closure_destructor.101Tm
- ___swift_closure_destructor.1849Tm
- ___swift_closure_destructor.240Tm
- ___swift_closure_destructor.385Tm
- ___swift_closure_destructor.512Tm
- ___swift_closure_destructor.518Tm
- ___swift_closure_destructor.616Tm
- ___swift_closure_destructor.703Tm
- ___swift_closure_destructor.805Tm
- ___swift_closure_destructor.828Tm
- ___swift_closure_destructor.97Tm
CStrings:
+ "DockKitCore.DockCoreWeakClientProxy"
+ "accessoryDescriptionFeedback after manager released; dropped"
+ "diagnosticsFeedback after manager released; dropped"
+ "dumpTrackerDiagnostics after manager released; dropped"
+ "dumpTrackerState after manager released; dropped"
+ "fwUpdateFeedback after manager released; dropped"
+ "haltFeedback after manager released; dropped"
+ "rebootFeedback after manager released; dropped"
+ "returnToBase after manager released; dropped"
+ "search after manager released; dropped"
+ "selectSubjectAtEvent after manager released; dropped"
+ "selectSubjectsEvent after manager released; dropped"
+ "sendCommandEvent after manager released; dropped"
+ "setFramingModeEvent after manager released; dropped"
+ "setRectOfInterestEvent after manager released; dropped"
+ "stopReturnToBase after manager released; dropped"
+ "stopSearch after manager released; dropped"
+ "unexpected actuatorFeedback on manager connection; dropped"
+ "unexpected batteryStateData on manager connection; dropped"
+ "unexpected disconnected on manager connection; dropped"
+ "unexpected sensorData on manager connection; dropped"
+ "unexpected systemEventData on manager connection; dropped"
+ "unexpected trackingSummaryData on manager connection; dropped"
+ "unexpected trackingSummaryDataDebug on manager connection; dropped"
+ "unexpected trajectoryProgressFeedback on manager connection; dropped"
```
