## HomeUIService

> `/Applications/HomeUIService.app/HomeUIService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x80734` | `0x810bc` | **`+0x988`** |
| `__TEXT.__objc_methname` | `0x16f74` | `0x170e4` | **`+0x170`** |
| `__TEXT.__oslogstring` | `0x8b62` | `0x8c72` | **`+0x110`** |
| `__TEXT.__objc_stubs` | `0xfea0` | `0xffa0` | **`+0x100`** |
| `__TEXT.__cstring` | `0x97e1` | `0x98c1` | **`+0xe0`** |
| `__TEXT.__objc_methtype` | `0x4076` | `0x4106` | **`+0x90`** |
| `__TEXT.__gcc_except_tab` | `0xc20` | `0xc7c` | **`+0x5c`** |
| `__DATA_CONST.__const` | `0x3310` | `0x3360` | **`+0x50`** |
| `__DATA.__objc_selrefs` | `0x5460` | `0x54a8` | **`+0x48`** |
| `__TEXT.__objc_methlist` | `0x8044` | `0x808c` | **`+0x48`** |
| `__TEXT.__unwind_info` | `0x1f50` | `0x1f90` | **`+0x40`** |
| `__DATA_CONST.__cfstring` | `0x4840` | `0x4860` | **`+0x20`** |
| `__DATA.__objc_const` | `0xdf10` | `0xdf20` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-1265.0.0.1.1
+1269.2.3.0.1

-  Functions: 2979
+  Functions: 2990

-  CStrings:  5427
+  CStrings:  5446
CStrings:
+ "%@ NFC launch, not asking nfcd, result=NO"
+ "%@ readerSupported=%{BOOL}d accessorySupportsNFC=%{BOOL}d result=%{BOOL}d"
+ "%s: switching the setup flow to proximity pairing with userInfo: %@"
+ "-[HSProximityCardHostViewController _swapProxCardFlowToViewController:]"
+ "-[HSProximityCardHostViewController coordinator:presentProximitySetupWithUserInfo:]"
+ "@\"NSArray\"36@0:8@\"CRCameraReader\"16^{__CVBuffer=}24I32"
+ "@36@0:8@16^{__CVBuffer=}24I32"
+ "Handing NFC tap off to homed"
+ "Not swapping in a view controller that cannot be a prox card %s"
+ "_buildProxCardFlowWithUserInfo:firstViewController:"
+ "_handOffNFCTapToHomed:fallback:"
+ "_swapProxCardFlowToViewController:"
+ "_updateHomeKitDispatcherProxPairingLaunchFlag"
+ "cameraReader:auxiliaryIDCornerDetection:orientation:"
+ "coordinator:presentProximitySetupWithUserInfo:"
+ "handleNFCTapWithSetupURLStrings:completionHandler:"
+ "setIsProxPairingLaunch:"
+ "setViewControllers:animated:"
+ "v32@0:8@\"HSProxCardCoordinator\"16@\"NSDictionary\"24"
```
