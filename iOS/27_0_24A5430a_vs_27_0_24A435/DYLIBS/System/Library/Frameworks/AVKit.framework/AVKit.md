## AVKit

> `/System/Library/Frameworks/AVKit.framework/AVKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x268b10` | `0x269ccc` | **`+0x11bc`** |
| `__AUTH_CONST.__objc_const` | `0x382a0` | `0x38578` | **`+0x2d8`** |
| `__TEXT.__objc_methlist` | `0x1ed44` | `0x1ee14` | **`+0xd0`** |
| `__AUTH.__objc_data` | `0x6838` | `0x68d8` | **`+0xa0`** |
| `__TEXT.__cstring` | `0x1329a` | `0x13322` | **`+0x88`** |
| `__AUTH_CONST.__cfstring` | `0x99a0` | `0x9a00` | **`+0x60`** |
| `__DATA_CONST.__got` | `0x1848` | `0x18a8` | **`+0x60`** |
| `__DATA_CONST.__objc_selrefs` | `0xd430` | `0xd488` | **`+0x58`** |
| `__TEXT.__oslogstring` | `0xc11d` | `0xc15b` | **`+0x3e`** |
| `__TEXT.__unwind_info` | `0xa368` | `0xa3a0` | **`+0x38`** |
| `__DATA.__objc_ivar` | `0x3024` | `0x3054` | **`+0x30`** |
| `__DATA_CONST.__objc_classlist` | `0xae8` | `0xaf8` | **`+0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x7f8` | `0x808` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x1fa0` | `0x1fa8` | **`+0x8`** |

### Other Changes

```diff

-  Functions: 14854
-  Symbols:   20102
-  CStrings:  2999
+  Functions: 14871
+  Symbols:   20158
+  CStrings:  3004
Symbols:
+ +[AVCaptureDeviceStates stateWithStateADeviceIDs:stateBDeviceIDs:]
+ -[AVCaptureDeviceStateCoordinator .cxx_destruct]
+ -[AVCaptureDeviceStateCoordinator _updateCurrentState:]
+ -[AVCaptureDeviceStateCoordinator dealloc]
+ -[AVCaptureDeviceStateCoordinator deviceState]
+ -[AVCaptureDeviceStateCoordinator initWithView:types:queue:handler:]
+ -[AVCaptureDeviceStateCoordinator observeValueForKeyPath:ofObject:change:context:]
+ -[AVCaptureDeviceStates .cxx_destruct]
+ -[AVCaptureDeviceStates _initWithStateADeviceIDs:stateBDeviceIDs:]
+ -[AVCaptureDeviceStates debugDescription]
+ -[AVCaptureDeviceStates description]
+ -[AVCaptureDeviceStates hash]
+ -[AVCaptureDeviceStates isEqual:]
+ -[AVCaptureDeviceStates stateADeviceIDs]
+ -[AVCaptureDeviceStates stateBDeviceIDs]
+ GCC_except_table10122
+ GCC_except_table10124
+ GCC_except_table10138
+ GCC_except_table10172
+ GCC_except_table10182
+ GCC_except_table10332
+ GCC_except_table10338
+ GCC_except_table10379
+ GCC_except_table10401
+ GCC_except_table10617
+ GCC_except_table10639
+ GCC_except_table8376
+ GCC_except_table8406
+ GCC_except_table8410
+ GCC_except_table8565
+ GCC_except_table8623
+ GCC_except_table8625
+ GCC_except_table8809
+ GCC_except_table8822
+ GCC_except_table8843
+ GCC_except_table8866
+ GCC_except_table8876
+ GCC_except_table8894
+ GCC_except_table8895
+ GCC_except_table8899
+ GCC_except_table8907
+ GCC_except_table8963
+ GCC_except_table9259
+ GCC_except_table9277
+ GCC_except_table9430
+ GCC_except_table9434
+ GCC_except_table9436
+ GCC_except_table9438
+ GCC_except_table9439
+ GCC_except_table9440
+ GCC_except_table9471
+ GCC_except_table9479
+ GCC_except_table9509
+ GCC_except_table9535
+ GCC_except_table9553
+ GCC_except_table9557
+ GCC_except_table9561
+ GCC_except_table9563
+ GCC_except_table9635
+ GCC_except_table9658
+ GCC_except_table9698
+ GCC_except_table9703
+ GCC_except_table9719
+ GCC_except_table9822
+ GCC_except_table9987
+ _AVCaptureDeviceStateCoordinatorChangedContext
+ _AVCaptureDeviceTypeBuiltInBostonUltraWideCamera
+ _AVCaptureDeviceTypeBuiltInDualCamera
+ _AVCaptureDeviceTypeBuiltInDualWideCamera
+ _AVCaptureDeviceTypeBuiltInLiDARDepthCamera
+ _AVCaptureDeviceTypeBuiltInRenoUltraWideCamera
+ _AVCaptureDeviceTypeBuiltInTelephotoCamera
+ _AVCaptureDeviceTypeBuiltInTripleCamera
+ _AVCaptureDeviceTypeBuiltInTrueDepthCamera
+ _AVCaptureDeviceTypeBuiltInUltraWideCamera
+ _AVCaptureDeviceTypeBuiltInWideAngleCamera
+ _OBJC_CLASS_$_AVCaptureDeviceDiscoverySession
+ _OBJC_CLASS_$_AVCaptureDeviceStateCoordinator
+ _OBJC_CLASS_$_AVCaptureDeviceStates
+ _OBJC_IVAR_$_AVCaptureDeviceStateCoordinator._bostonDevices
+ _OBJC_IVAR_$_AVCaptureDeviceStateCoordinator._currentState
+ _OBJC_IVAR_$_AVCaptureDeviceStateCoordinator._handler
+ _OBJC_IVAR_$_AVCaptureDeviceStateCoordinator._isRenoSuspended
+ _OBJC_IVAR_$_AVCaptureDeviceStateCoordinator._lock
+ _OBJC_IVAR_$_AVCaptureDeviceStateCoordinator._otherDevices
+ _OBJC_IVAR_$_AVCaptureDeviceStateCoordinator._queue
+ _OBJC_IVAR_$_AVCaptureDeviceStateCoordinator._renoCamera
+ _OBJC_IVAR_$_AVCaptureDeviceStateCoordinator._renoDevices
+ _OBJC_IVAR_$_AVCaptureDeviceStateCoordinator._types
+ _OBJC_IVAR_$_AVCaptureDeviceStates._stateADeviceIDs
+ _OBJC_IVAR_$_AVCaptureDeviceStates._stateBDeviceIDs
+ _OBJC_METACLASS_$_AVCaptureDeviceStateCoordinator
+ _OBJC_METACLASS_$_AVCaptureDeviceStates
+ __OBJC_$_CLASS_METHODS_AVCaptureDeviceStates
+ __OBJC_$_INSTANCE_METHODS_AVCaptureDeviceStateCoordinator
+ __OBJC_$_INSTANCE_METHODS_AVCaptureDeviceStates
+ __OBJC_$_INSTANCE_VARIABLES_AVCaptureDeviceStateCoordinator
+ __OBJC_$_INSTANCE_VARIABLES_AVCaptureDeviceStates
+ __OBJC_$_PROP_LIST_AVCaptureDeviceStates
+ __OBJC_CLASS_RO_$_AVCaptureDeviceStateCoordinator
+ __OBJC_CLASS_RO_$_AVCaptureDeviceStates
+ __OBJC_METACLASS_RO_$_AVCaptureDeviceStateCoordinator
+ __OBJC_METACLASS_RO_$_AVCaptureDeviceStates
+ ___68-[AVCaptureDeviceStateCoordinator initWithView:types:queue:handler:]_block_invoke
+ ___82-[AVCaptureDeviceStateCoordinator observeValueForKeyPath:ofObject:change:context:]_block_invoke
+ _dispatch_assert_queue$V2
- GCC_except_table10105
- GCC_except_table10107
- GCC_except_table10121
- GCC_except_table10155
- GCC_except_table10165
- GCC_except_table10315
- GCC_except_table10321
- GCC_except_table10362
- GCC_except_table10384
- GCC_except_table10600
- GCC_except_table10622
- GCC_except_table8359
- GCC_except_table8389
- GCC_except_table8393
- GCC_except_table8548
- GCC_except_table8606
- GCC_except_table8608
- GCC_except_table8792
- GCC_except_table8805
- GCC_except_table8826
- GCC_except_table8849
- GCC_except_table8859
- GCC_except_table8877
- GCC_except_table8878
- GCC_except_table8882
- GCC_except_table8890
- GCC_except_table8946
- GCC_except_table9242
- GCC_except_table9260
- GCC_except_table9413
- GCC_except_table9417
- GCC_except_table9419
- GCC_except_table9421
- GCC_except_table9422
- GCC_except_table9423
- GCC_except_table9454
- GCC_except_table9462
- GCC_except_table9492
- GCC_except_table9518
- GCC_except_table9536
- GCC_except_table9540
- GCC_except_table9544
- GCC_except_table9546
- GCC_except_table9618
- GCC_except_table9641
- GCC_except_table9669
- GCC_except_table9681
- GCC_except_table9702
- GCC_except_table9805
- GCC_except_table9970
CStrings:
+ "%s Initialized AVCaptureDeviceStateCoordinator for UIView: %@"
+ "-[AVCaptureDeviceStateCoordinator initWithView:types:queue:handler:]"
+ "<%@: %p %@>"
+ "stateADeviceIDs: %@, stateBDeviceIDs: %@"
+ "suspended"
```
