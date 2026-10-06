## AppleNeuralEngine

> `/System/Library/PrivateFrameworks/AppleNeuralEngine.framework/AppleNeuralEngine`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x57ec0` | `0x59574` | **`+0x16b4`** |
| `__TEXT.__ustring` | `—` | `0xb76` | **`+0xb76`** |
| `__AUTH_CONST.__cfstring` | `0x4a80` | `0x4fe0` | **`+0x560`** |
| `__TEXT.__gcc_except_tab` | `0x67d0` | `0x6b7c` | **`+0x3ac`** |
| `__TEXT.__unwind_info` | `0x1418` | `0x1620` | **`+0x208`** |
| `__TEXT.__oslogstring` | `0xb883` | `0xba7b` | **`+0x1f8`** |
| `__TEXT.__cstring` | `0x3893` | `0x3a6d` | **`+0x1da`** |
| `__DATA_CONST.__const` | `0x978` | `0xad0` | **`+0x158`** |
| `__AUTH_CONST.__objc_const` | `0x3cd0` | `0x3d88` | **`+0xb8`** |
| `__TEXT.__objc_methlist` | `0x2b94` | `0x2c3c` | **`+0xa8`** |
| `__DATA_CONST.__objc_selrefs` | `0x1a28` | `0x1a88` | **`+0x60`** |
| `__AUTH.__objc_data` | `0x4b0` | `0x500` | **`+0x50`** |
| `__AUTH_CONST.__const` | `0x4d0` | `0x4f0` | **`+0x20`** |
| `__AUTH_CONST.__objc_arrayobj` | `0x60` | `0x78` | **`+0x18`** |
| `__DATA.__bss` | `0x180` | `0x190` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x680` | `0x688` | **`+0x8`** |
| `__DATA.__data` | `0x718` | `0x720` | **`+0x8`** |
| `__DATA_CONST.__objc_arraydata` | `0x120` | `0x128` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x130` | `0x138` | **`+0x8`** |

### Other Changes

```diff

-382.12.0.0.0
+382.15.1.0.0

-  Functions: 1726
-  Symbols:   2250
-  CStrings:  1433
+  Functions: 1751
+  Symbols:   2289
+  CStrings:  1483
Symbols:
+ +[_ANECompileFlavorPolicy nonBondedCsIdentities]
+ +[_ANECompileFlavorPolicy shouldDisableBondedForCsIdentity:]
+ +[_ANEErrors errorForCode:method:]
+ +[_ANEErrors errorForCode:method:underlyingCode:]
+ +[_ANEErrors errorForCode:method:underlyingCode:additionalUserInfo:]
+ +[_ANEErrors inferenceErrorForStatus:method:]
+ +[_ANEErrors stringForCode:]
+ +[_ANEModelToken appGroupIdentifiersFor:processIdentifier:]
+ +[_ANEStrings modelSourceContainerName]
+ -[_ANEClient compiledModelExistsInCacheFor:limitToCurrentProcess:]
+ -[_ANEClient updateCachedModelLocationForModelTrackedByHash:toAppGroup:error:]
+ -[_ANEDaemonConnection compiledModelExistsInCacheFor:limitToCurrentProcess:withReply:]
+ -[_ANEDaemonConnection updateCachedModelLocationForModelTrackedByHash:toAppGroup:withReply:]
+ GCC_except_table0
+ GCC_except_table20
+ GCC_except_table21
+ GCC_except_table22
+ GCC_except_table23
+ GCC_except_table24
+ GCC_except_table27
+ GCC_except_table40
+ GCC_except_table41
+ GCC_except_table52
+ GCC_except_table68
+ GCC_except_table71
+ _CFArrayGetTypeID
+ _OBJC_CLASS_$__ANECompileFlavorPolicy
+ _OBJC_METACLASS_$__ANECompileFlavorPolicy
+ __OBJC_$_CLASS_METHODS__ANECompileFlavorPolicy
+ __OBJC_CLASS_RO_$__ANECompileFlavorPolicy
+ __OBJC_METACLASS_RO_$__ANECompileFlavorPolicy
+ ___48+[_ANECompileFlavorPolicy nonBondedCsIdentities]_block_invoke
+ ___66-[_ANEClient compiledModelExistsInCacheFor:limitToCurrentProcess:]_block_invoke
+ ___66-[_ANEClient compiledModelExistsInCacheFor:limitToCurrentProcess:]_block_invoke_2
+ ___78-[_ANEClient updateCachedModelLocationForModelTrackedByHash:toAppGroup:error:]_block_invoke
+ ___78-[_ANEClient updateCachedModelLocationForModelTrackedByHash:toAppGroup:error:]_block_invoke_2
+ ___86-[_ANEDaemonConnection compiledModelExistsInCacheFor:limitToCurrentProcess:withReply:]_block_invoke
+ ___92-[_ANEDaemonConnection updateCachedModelLocationForModelTrackedByHash:toAppGroup:withReply:]_block_invoke
+ ___block_descriptor_65_e8_32s40s48r_e5_v8?0ls32l8s40l8r48l8
+ ___block_descriptor_72_e8_32s40s48r56r_e20_v20?0B8"NSError"12lr48l8s32l8s40l8r56l8
+ ___block_descriptor_80_e8_32s40s48s56r64r_e5_v8?0ls32l8s40l8s48l8r56l8r64l8
+ ___block_descriptor_88_e8_32s40s48s56r64r_e5_v8?0ls32l8s40l8s48l8r56l8r64l8
+ _kANEErrorLoadStageKey
+ _kANEErrorUnderlyingStatusKey
+ _kANEFDisableBondedNetworksKey
+ _nonBondedCsIdentities.list
+ _nonBondedCsIdentities.once
- -[_ANEDaemonConnection compiledModelExistsInCacheFor:withReply:]
- GCC_except_table64
- GCC_except_table67
- ___44-[_ANEClient compiledModelExistsInCacheFor:]_block_invoke
- ___44-[_ANEClient compiledModelExistsInCacheFor:]_block_invoke_2
- ___64-[_ANEDaemonConnection compiledModelExistsInCacheFor:withReply:]_block_invoke
- ___block_descriptor_64_e8_32s40s48r_e5_v8?0ls32l8s40l8r48l8
- ___block_descriptor_96_e8_32s40s48s56r64r_e5_v8?0lr56l8s32l8s40l8s48l8r64l8
CStrings:
+ "%@: %@"
+ "%@: %@ (underlying=0x%lX)"
+ "%@: ANE error (code=%lu)"
+ "%@: ANE error (code=%lu, underlying=0x%lX)"
+ "%@: SecTaskCopyValueForEntitlement() returned app-groups:=\"%@\""
+ "%@: appGroupIdentifiersFor ignoring inelligible app-group (found %@)"
+ "%@: client(%d) : does not belong to an app-group"
+ "../"
+ "Error: %@ encountered during updateCachedModelLocationForModelTrackedByHash:%@ toAppGroup:%@"
+ "Inference failed — ANE firmware failure"
+ "Inference failed — ANE hardware failure"
+ "Inference failed — IOSurface smaller than the model expects (re-check inputBufferSize/outputBufferSize from the load reply)"
+ "Inference failed — ISO too old (transient; retry)"
+ "Inference failed — bad program image (model may be corrupt or incompatible)"
+ "Inference failed — device not ready (transient; retry)"
+ "Inference failed — device power-on failed (transient; retry)"
+ "Inference failed — device still open (lifecycle issue)"
+ "Inference failed — exclusive-access contention with another client"
+ "Inference failed — generic ANE error"
+ "Inference failed — invalid argument or state"
+ "Inference failed — no ANE resources (transient; retry)"
+ "Inference failed — no memory (transient; retry under lower memory pressure)"
+ "Inference failed — operation not permitted (check entitlements)"
+ "Inference failed — referenced resource not found"
+ "Inference failed — request aborted"
+ "Inference failed — shared intermediate buffer alloc/lock failure"
+ "Inference preempted by higher-priority request (transient; retry)"
+ "Mutable weights map failed"
+ "Mutable weights unmap failed"
+ "Program IOSurfaces map failed"
+ "Program IOSurfaces unmap failed"
+ "Program load failed — ANE firmware failure"
+ "Program load failed — ANE hardware failure"
+ "Program load failed — bad program image (model may be corrupt or incompatible)"
+ "Program load failed — device power-on failed (transient; retry)"
+ "Program load failed — generic ANE error"
+ "Program load failed — no ANE resources (transient; retry)"
+ "Program load failed — no memory (transient; retry under lower memory pressure)"
+ "Program load failed — operation not permitted (check entitlements)"
+ "Session hint request failed"
+ "[proxy updateCachedModelLocationForModelTrackedByHash:%@ toAppGroup:%@...] returned success = %d with error = %@"
+ "_"
+ "_ANEErrorLoadStage"
+ "_ANEErrorUnderlyingStatus"
+ "com.apple.security.application-groups"
+ "com.topazlabs.TopazPhotoAI"
+ "kANEFDisableBondedNetworksKey"
+ "model.src_cont"
+ "updateCachedModelLocationForModelTrackedByHash:%@ toAppGroup:%@"
+ "updateLocationForModelTrackedByHash:%@ toAppGroup:%@"
```
