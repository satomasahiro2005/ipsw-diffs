## ANELargeModelCompilerService

> `/System/Library/PrivateFrameworks/AppleNeuralEngine.framework/XPCServices/ANELargeModelCompilerService.xpc/ANELargeModelCompilerService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1819c` | `0x18b64` | **`+0x9c8`** |
| `__TEXT.__oslogstring` | `0x20e8` | `0x224c` | **`+0x164`** |
| `__TEXT.__objc_methname` | `0x246d` | `0x24e1` | **`+0x74`** |
| `__TEXT.__objc_stubs` | `0x2160` | `0x21c0` | **`+0x60`** |
| `__DATA_CONST.__cfstring` | `0x1880` | `0x18c0` | **`+0x40`** |
| `__TEXT.__gcc_except_tab` | `0x1210` | `0x1248` | **`+0x38`** |
| `__TEXT.__cstring` | `0x1255` | `0x1277` | **`+0x22`** |
| `__TEXT.__auth_stubs` | `0x7d0` | `0x7f0` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0xa40` | `0xa58` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x954` | `0x96c` | **`+0x18`** |
| `__TEXT.__objc_methtype` | `0x601` | `0x615` | **`+0x14`** |
| `__DATA_CONST.__auth_got` | `0x400` | `0x410` | **`+0x10`** |
| `__TEXT.__const` | `0x108` | `0x118` | **`+0x10`** |
| `__DATA.__data` | `0x3f0` | `0x3f8` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x428` | `0x430` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`

### Other Changes

```diff

-382.11.0.0.0
+382.12.0.0.0

-  Functions: 291
-  Symbols:   933
-  CStrings:  842
+  Functions: 295
+  Symbols:   940
+  CStrings:  853
Symbols:
+ +[_ANEStorageHelper isPath:safelyWithinDirectory:]
+ -[_ANEModelCacheManager scanAllPartitionsForModel:csIdentity:expunge:allowProcessModelShare:]
+ ___93-[_ANEModelCacheManager scanAllPartitionsForModel:csIdentity:expunge:allowProcessModelShare:]_block_invoke
+ ___block_descriptor_156_e8_32s40s48s56s64s72s80s88s96s104bs112r_e5_v8?0ls32l8s40l8s48l8s56l8s104l8s64l8r112l8s72l8s80l8s88l8s96l8
+ __os_log_fault_impl
+ _kANEDCompilerQoSHintKey
+ _objc_msgSend$isPath:safelyWithinDirectory:
+ _objc_msgSend$scanAllPartitionsForModel:csIdentity:expunge:allowProcessModelShare:
+ _objc_msgSend$unsignedIntValue
+ _qos_class_self
- GCC_except_table9
- ___70-[_ANEModelCacheManager scanAllPartitionsForModel:csIdentity:expunge:]_block_invoke
- ___block_descriptor_136_e8_32s40s48s56s64s72s80s88s96bs104r_e5_v8?0ls32l8s96l8s40l8s48l8r104l8s56l8s64l8s72l8s80l8s88l8
CStrings:
+ "%@: refusing expunge with allowProcessModelShare — would purge shared-bucket models on behalf of an unrelated csIdentity"
+ "%u qos:%u model.string_id:%llu csIdentity:%{public}@"
+ "<private>"
+ "ANECompilerService QoS: model.string_id=%llu clientQos=%u threadQos=%u"
+ "B40@0:8@16@24B32B36"
+ "_ANEC_ESPRESSO_TRANSLATE"
+ "_ANEC_QUEUE_WAIT"
+ "csIdentity:%{public}@ status:%u durationMs:%f"
+ "isPath:safelyWithinDirectory:"
+ "kANEDCompilerQoSHintKey"
+ "qos:%u model.string_id:%llu name:%{public}@ csIdentity:%{public}@"
+ "scanAllPartitionsForModel:csIdentity:expunge:allowProcessModelShare:"
+ "unsignedIntValue"
- "%u model.string_id:%llu"
- "model.string_id:%llu"
```
