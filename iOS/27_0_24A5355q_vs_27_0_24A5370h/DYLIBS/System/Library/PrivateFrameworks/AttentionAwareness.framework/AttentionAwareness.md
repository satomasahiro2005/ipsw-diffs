## AttentionAwareness

> `/System/Library/PrivateFrameworks/AttentionAwareness.framework/AttentionAwareness`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__objc_const` | `0x52c0` | `0x5128` | **`-0x198`** |
| `__TEXT.__text` | `0x37478` | `0x373fc` | **`-0x7c`** |
| `__TEXT.__cstring` | `0x4129` | `0x40bb` | **`-0x6e`** |
| `__DATA.__data` | `0xae4` | `0xa84` | **`-0x60`** |
| `__TEXT.__objc_methlist` | `0x2824` | `0x27c4` | **`-0x60`** |
| `__DATA_DIRTY.__objc_data` | `0x870` | `0x820` | **`-0x50`** |
| `__TEXT.__oslogstring` | `0x5834` | `0x57ef` | **`-0x45`** |
| `__DATA_CONST.__const` | `0xe48` | `0xe20` | **`-0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0x1448` | `0x1420` | **`-0x28`** |
| `__DATA.__objc_ivar` | `0x554` | `0x538` | **`-0x1c`** |
| `__TEXT.__unwind_info` | `0xd50` | `0xd38` | **`-0x18`** |
| `__DATA_CONST.__got` | `0x208` | `0x1f8` | **`-0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x128` | `0x120` | **`-0x8`** |
| `__DATA_CONST.__objc_protolist` | `0xe8` | `0xe0` | **`-0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x110` | `0x108` | **`-0x8`** |
| `__TEXT.__gcc_except_tab` | `0x86c` | `0x864` | **`-0x8`** |

### Other Changes

```diff

-261.0.0.0.1
+264.0.0.0.0

-  Functions: 975
-  Symbols:   2134
-  CStrings:  854
+  Functions: 966
+  Symbols:   2105
+  CStrings:  849
Symbols:
+ GCC_except_table118
+ GCC_except_table119
+ GCC_except_table165
+ GCC_except_table166
+ GCC_except_table170
+ GCC_except_table184
+ GCC_except_table203
+ GCC_except_table205
+ GCC_except_table230
+ GCC_except_table266
+ GCC_except_table290
+ GCC_except_table344
+ GCC_except_table356
+ GCC_except_table375
+ GCC_except_table439
+ GCC_except_table440
+ GCC_except_table46
+ GCC_except_table510
+ GCC_except_table516
+ GCC_except_table521
+ GCC_except_table534
+ GCC_except_table609
+ GCC_except_table633
+ GCC_except_table705
+ GCC_except_table80
+ GCC_except_table848
+ GCC_except_table874
+ GCC_except_table878
+ GCC_except_table882
+ GCC_except_table885
+ GCC_except_table889
+ GCC_except_table890
+ GCC_except_table900
+ GCC_except_table902
+ GCC_except_table907
+ GCC_except_table913
+ GCC_except_table915
- -[AWAttentionAwareService MotionStateChanging:]
- -[AWScheduler isDeviceStationary]
- -[AWScheduler motionActivityChanging:]
- -[MotionActivityObserver .cxx_destruct]
- -[MotionActivityObserver initWithCallbackQueue:observer:]
- GCC_except_table120
- GCC_except_table121
- GCC_except_table167
- GCC_except_table168
- GCC_except_table172
- GCC_except_table188
- GCC_except_table207
- GCC_except_table213
- GCC_except_table238
- GCC_except_table270
- GCC_except_table294
- GCC_except_table348
- GCC_except_table360
- GCC_except_table379
- GCC_except_table443
- GCC_except_table444
- GCC_except_table514
- GCC_except_table520
- GCC_except_table533
- GCC_except_table546
- GCC_except_table56
- GCC_except_table613
- GCC_except_table637
- GCC_except_table714
- GCC_except_table82
- GCC_except_table857
- GCC_except_table883
- GCC_except_table891
- GCC_except_table894
- GCC_except_table896
- GCC_except_table898
- GCC_except_table899
- GCC_except_table909
- GCC_except_table911
- GCC_except_table916
- GCC_except_table922
- GCC_except_table924
- _OBJC_CLASS_$_CMMotionActivityManager
- _OBJC_CLASS_$_MotionActivityObserver
- _OBJC_CLASS_$_NSOperationQueue
- _OBJC_IVAR_$_AWAttentionAwareService._motionActivityObserver
- _OBJC_IVAR_$_AWScheduler._isDeviceStationary
- _OBJC_IVAR_$_MotionActivityObserver._callbackQueue
- _OBJC_IVAR_$_MotionActivityObserver._isDeviceStationary
- _OBJC_IVAR_$_MotionActivityObserver._motionActivityManager
- _OBJC_IVAR_$_MotionActivityObserver._observer
- _OBJC_IVAR_$_MotionActivityObserver._operationQueue
- _OBJC_METACLASS_$_MotionActivityObserver
- __OBJC_$_INSTANCE_METHODS_MotionActivityObserver
- __OBJC_$_INSTANCE_VARIABLES_MotionActivityObserver
- __OBJC_$_PROTOCOL_INSTANCE_METHODS_MotionActivityObserving
- __OBJC_$_PROTOCOL_METHOD_TYPES_MotionActivityObserving
- __OBJC_CLASS_RO_$_MotionActivityObserver
- __OBJC_LABEL_PROTOCOL_$_MotionActivityObserving
- __OBJC_METACLASS_RO_$_MotionActivityObserver
- __OBJC_PROTOCOL_$_MotionActivityObserving
- ___47-[AWAttentionAwareService MotionStateChanging:]_block_invoke
- ___57-[MotionActivityObserver initWithCallbackQueue:observer:]_block_invoke
- ___57-[MotionActivityObserver initWithCallbackQueue:observer:]_block_invoke_2
- ___57-[MotionActivityObserver initWithCallbackQueue:observer:]_block_invoke_3
- ___block_descriptor_40_e8_32s_e26_v16?0"CMMotionActivity"8ls32l8
CStrings:
- "%13.5f: Device %s stationary"
- "%30s:%-4d: %13.5f: Device %s stationary"
- "-[MotionActivityObserver initWithCallbackQueue:observer:]"
- "MotionActivityObserver.m"
- "v16@?0@\"CMMotionActivity\"8"
```
