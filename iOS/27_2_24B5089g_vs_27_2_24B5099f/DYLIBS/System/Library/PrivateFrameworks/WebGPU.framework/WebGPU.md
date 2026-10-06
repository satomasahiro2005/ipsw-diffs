## WebGPU

> `/System/Library/PrivateFrameworks/WebGPU.framework/WebGPU`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x244778` | `0x24573c` | **`+0xfc4`** |
| `__TEXT.__cstring` | `0x3e1fc` | `0x3e44c` | **`+0x250`** |
| `__TEXT.__gcc_except_tab` | `0xa918` | `0xa9b8` | **`+0xa0`** |
| `__TEXT.__unwind_info` | `0x43e0` | `0x4420` | **`+0x40`** |
| `__AUTH_CONST.__const` | `0x4ce0` | `0x4d18` | **`+0x38`** |
| `__AUTH_CONST.__cfstring` | `0x3a40` | `0x3a60` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0xa08` | `0xa20` | **`+0x18`** |

### Other Changes

```diff

-625.2.5.10.1
+625.2.7.1.0

-  Functions: 3640
-  Symbols:   4095
-  CStrings:  2752
+  Functions: 3649
+  Symbols:   4108
+  CStrings:  2757
Symbols:
+ GCC_except_table46
+ __ZN3WTF3BoxINSt3__16atomicIbEEED1Ev
+ __ZN3WTF6Detail15CallableWrapperIZN6WebGPU6Buffer26restoreSnapshotAfterCommitERNS2_13CommandBufferERNS2_5QueueEPU19objcproto9MTLBuffer11objc_objectmE3$_0vJU8__strongPU27objcproto16MTLCommandBuffer11objc_objectEE4callESC_
+ __ZN3WTF6Detail15CallableWrapperIZN6WebGPU6Buffer26restoreSnapshotAfterCommitERNS2_13CommandBufferERNS2_5QueueEPU19objcproto9MTLBuffer11objc_objectmE3$_0vJU8__strongPU27objcproto16MTLCommandBuffer11objc_objectEED0Ev
+ __ZN3WTF6Detail15CallableWrapperIZN6WebGPU6Buffer26restoreSnapshotAfterCommitERNS2_13CommandBufferERNS2_5QueueEPU19objcproto9MTLBuffer11objc_objectmE3$_0vJU8__strongPU27objcproto16MTLCommandBuffer11objc_objectEED1Ev
+ __ZN6WebGPU15crashGPUProcessILj10EEEvRKN3WTF6RefPtrINS_6DeviceENS1_12RawPtrTraitsIS3_EENS1_21DefaultRefDerefTraitsIS3_EEEEP7NSErrorSC_
+ __ZN6WebGPU15crashGPUProcessILj11EEEvRKN3WTF6RefPtrINS_6DeviceENS1_12RawPtrTraitsIS3_EENS1_21DefaultRefDerefTraitsIS3_EEEEP7NSErrorSC_
+ __ZN6WebGPU15crashGPUProcessILj16EEEvRKN3WTF6RefPtrINS_6DeviceENS1_12RawPtrTraitsIS3_EENS1_21DefaultRefDerefTraitsIS3_EEEEP7NSErrorSC_
+ __ZN6WebGPU15crashGPUProcessILj17EEEvRKN3WTF6RefPtrINS_6DeviceENS1_12RawPtrTraitsIS3_EENS1_21DefaultRefDerefTraitsIS3_EEEEP7NSErrorSC_
+ __ZN6WebGPU15crashGPUProcessILj8EEEvRKN3WTF6RefPtrINS_6DeviceENS1_12RawPtrTraitsIS3_EENS1_21DefaultRefDerefTraitsIS3_EEEEP7NSErrorSC_
+ __ZN6WebGPU15crashGPUProcessILj9EEEvRKN3WTF6RefPtrINS_6DeviceENS1_12RawPtrTraitsIS3_EENS1_21DefaultRefDerefTraitsIS3_EEEEP7NSErrorSC_
+ __ZN6WebGPU5Queue10copyBufferEPU19objcproto9MTLBuffer11objc_objectyS2_yy
+ __ZN6WebGPU6Buffer24snapshotRangeBeforeClearERNS_5QueueEmm
+ __ZN6WebGPU6Buffer26invalidateDrawIndexedCacheEPNS_14CommandEncoderE
+ __ZN6WebGPU6Buffer26restoreSnapshotAfterCommitERNS_13CommandBufferERNS_5QueueEPU19objcproto9MTLBuffer11objc_objectm
+ __ZN6WebGPUL15crashGPUProcessERKN3WTF6RefPtrINS_6DeviceENS0_12RawPtrTraitsIS2_EENS0_21DefaultRefDerefTraitsIS2_EEEEP8NSString
+ __ZNK3WTF29ThreadSafeWeakPtrControlBlock29makeStrongReferenceIfPossibleIN6WebGPU6DeviceEEENS_6RefPtrIT_NS_12RawPtrTraitsIS5_EENS_21DefaultRefDerefTraitsIS5_EEEEPKS5_
+ __ZTVN3WTF6Detail15CallableWrapperIZN6WebGPU6Buffer26restoreSnapshotAfterCommitERNS2_13CommandBufferERNS2_5QueueEPU19objcproto9MTLBuffer11objc_objectmE3$_0vJU8__strongPU27objcproto16MTLCommandBuffer11objc_objectEEE
+ __ZZN6WebGPU6Buffer26restoreSnapshotAfterCommitERNS_13CommandBufferERNS_5QueueEPU19objcproto9MTLBuffer11objc_objectmEN3$_0D1Ev
+ ___block_descriptor_48_ea8_32c94_ZTSKZN6WebGPU5Queue22commitMTLCommandBufferEPU27objcproto16MTLCommandBuffer11objc_objectE3$_1_e28_v16?0"<MTLCommandBuffer>"8l
+ ___block_descriptor_64_ea8_32s40c34_ZTSN3WTF3BoxINSt3__16atomicIbEEEE48c73_ZTSN3WTF17ThreadSafeWeakPtrIN6WebGPU6DeviceENS_15NoTaggingTraitsIS2_EEEE_e5_v8?0l
+ ___copy_helper_block_ea8_40c34_ZTSN3WTF3BoxINSt3__16atomicIbEEEE48c73_ZTSN3WTF17ThreadSafeWeakPtrIN6WebGPU6DeviceENS_15NoTaggingTraitsIS2_EEEE
+ ___destroy_helper_block_ea8_40c34_ZTSN3WTF3BoxINSt3__16atomicIbEEEE48c73_ZTSN3WTF17ThreadSafeWeakPtrIN6WebGPU6DeviceENS_15NoTaggingTraitsIS2_EEEE
+ _dispatch_after
+ _dispatch_get_global_queue
+ _dispatch_time
- __ZN3WTF6Detail15CallableWrapperIZN6WebGPU6Buffer32clearIndexBufferForCommandBufferERNS2_13CommandBufferEE3$_0vJU8__strongPU27objcproto16MTLCommandBuffer11objc_objectEE4callES8_
- __ZN3WTF6Detail15CallableWrapperIZN6WebGPU6Buffer32clearIndexBufferForCommandBufferERNS2_13CommandBufferEE3$_0vJU8__strongPU27objcproto16MTLCommandBuffer11objc_objectEED0Ev
- __ZN3WTF6Detail15CallableWrapperIZN6WebGPU6Buffer32clearIndexBufferForCommandBufferERNS2_13CommandBufferEE3$_0vJU8__strongPU27objcproto16MTLCommandBuffer11objc_objectEED1Ev
- __ZN6WebGPU15crashGPUProcessILj10EEEvP7NSErrorS2_
- __ZN6WebGPU15crashGPUProcessILj11EEEvP7NSErrorS2_
- __ZN6WebGPU15crashGPUProcessILj16EEEvP7NSErrorS2_
- __ZN6WebGPU15crashGPUProcessILj17EEEvP7NSErrorS2_
- __ZN6WebGPU15crashGPUProcessILj8EEEvP7NSErrorS2_
- __ZN6WebGPU15crashGPUProcessILj9EEEvP7NSErrorS2_
- __ZN6WebGPU5Queue11writeBufferERNS_6BufferEyNSt3__14spanIhLm18446744073709551615EEE
- __ZTVN3WTF6Detail15CallableWrapperIZN6WebGPU6Buffer32clearIndexBufferForCommandBufferERNS2_13CommandBufferEE3$_0vJU8__strongPU27objcproto16MTLCommandBuffer11objc_objectEEE
- __ZZN6WebGPU6Buffer32clearIndexBufferForCommandBufferERNS_13CommandBufferEEN3$_0D1Ev
- ___block_descriptor_40_ea8_32c94_ZTSKZN6WebGPU5Queue22commitMTLCommandBufferEPU27objcproto16MTLCommandBuffer11objc_objectE3$_1_e28_v16?0"<MTLCommandBuffer>"8l
CStrings:
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/usr/local/include/wtf/Box.h"
+ "21.0.0 (clang-2100.4.1.1) [+internal-os]"
+ "Encountered fatal GPU error %@"
+ "T *WTF::Box<std::atomic<bool>>::operator->() const [T = std::atomic<bool>]"
+ "WebGPU: command buffer %@ did not complete within 3s timeout"
+ "void WebGPU::crashGPUProcess(const RefPtr<Device> &, NSError *__strong, NSError *__strong) [errorCode = 10U]"
+ "void WebGPU::crashGPUProcess(const RefPtr<Device> &, NSError *__strong, NSError *__strong) [errorCode = 11U]"
+ "void WebGPU::crashGPUProcess(const RefPtr<Device> &, NSError *__strong, NSError *__strong) [errorCode = 16U]"
+ "void WebGPU::crashGPUProcess(const RefPtr<Device> &, NSError *__strong, NSError *__strong) [errorCode = 17U]"
+ "void WebGPU::crashGPUProcess(const RefPtr<Device> &, NSError *__strong, NSError *__strong) [errorCode = 8U]"
+ "void WebGPU::crashGPUProcess(const RefPtr<Device> &, NSError *__strong, NSError *__strong) [errorCode = 9U]"
+ "void WebGPU::crashGPUProcess(const RefPtr<Device> &, NSString *__strong)"
- "21.0.0 (clang-2100.3.34.1) [+internal-os]"
- "void WebGPU::crashGPUProcess(NSError *__strong, NSError *__strong) [errorCode = 10U]"
- "void WebGPU::crashGPUProcess(NSError *__strong, NSError *__strong) [errorCode = 11U]"
- "void WebGPU::crashGPUProcess(NSError *__strong, NSError *__strong) [errorCode = 16U]"
- "void WebGPU::crashGPUProcess(NSError *__strong, NSError *__strong) [errorCode = 17U]"
- "void WebGPU::crashGPUProcess(NSError *__strong, NSError *__strong) [errorCode = 8U]"
- "void WebGPU::crashGPUProcess(NSError *__strong, NSError *__strong) [errorCode = 9U]"
```
