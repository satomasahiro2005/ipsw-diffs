## H16ISP.mediacapture

> `/System/Library/MediaCapture/H16ISP.mediacapture`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1d8594` | `0x1d86c4` | **`+0x130`** |
| `__AUTH.__objc_data` | `0xa0` | `—` | **`-0xa0`** |
| `__DATA_DIRTY.__objc_data` | `0x50` | `0xf0` | **`+0xa0`** |
| `__DATA_CONST.__const` | `0xc148` | `0xc158` | **`+0x10`** |
| `__TEXT.__const` | `0x2f298` | `0x2f2a2` | **`+0xa`** |
| `__TEXT.__unwind_info` | `0x4038` | `0x4040` | **`+0x8`** |
| `__DATA.__common` | `0x30` | `0x2c` | **`-0x4`** |
| `__DATA_DIRTY.__common` | `—` | `0x4` | **`+0x4`** |

### Other Changes

```diff

-6.21.0.0.0
+6.103.0.0.0

-  Functions: 6000
-  Symbols:   8296
+  Functions: 6001
+  Symbols:   8299
Symbols:
+ __ZN6H16ISP12H16ISPDevice35InvokeDeviceMessageNotificationProcEjPv
+ __ZN6H16ISP12SystemStatus26CopyBuiltInCameraDeviceUIDEv
+ __oidAppleExtendedKeyUsageSWUpdateSigning
+ _oidAppleExtendedKeyUsageSWUpdateSigning
- __ZN6H16ISP12SystemStatus17CopyCMIODeviceUIDEv
Functions:
~ __ZN6H16ISPL35H16ISPDeviceServiceInterestCallbackEPvjjS0_ : 32 -> 12
~ __ZN6H16ISP12H16ISPDevice37RegisterDeviceMessageNotificationProcEPFiPS0_jPvS2_ES2_ : 8 -> 88
~ __ZN6H16ISP19H16ISPFrameReceiverC2EPNS_12H16ISPDeviceEjP21H16ISPTNRConfigStruct29H16ISPRationalFrameRateStructS5_ : 1512 -> 1516
~ __ZL32H16ISPCaptureStreamStartInternalP22OpaqueFigCaptureStream : 28136 -> 28144
~ __ZN6H16ISP12H16ISPDeviceC2EPNS_22H16ISPDeviceControllerEj : 1284 -> 1304
~ __ZN6H16ISP12H16ISPDevice16H16ISPDeviceOpenEPFiPS0_jPvS2_ES2_ : 332 -> 356
~ __ZN6H16ISP12H16ISPDevice17H16ISPDeviceCloseEv : 128 -> 160
~ __ZN6H16ISP19H16ISPFrameReceiver29removeIODispatcherFromRunLoopEv : 220 -> 216
+ __ZN6H16ISP12H16ISPDevice35InvokeDeviceMessageNotificationProcEjPv
```
