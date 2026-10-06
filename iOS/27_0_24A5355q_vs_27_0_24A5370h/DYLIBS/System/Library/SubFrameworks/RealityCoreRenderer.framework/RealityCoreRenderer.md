## RealityCoreRenderer

> `/System/Library/SubFrameworks/RealityCoreRenderer.framework/RealityCoreRenderer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xeb214` | `0xedab8` | **`+0x28a4`** |
| `__TEXT.__eh_frame` | `0x6c10` | `0x6db0` | **`+0x1a0`** |
| `__DATA.__bss` | `0x5980` | `0x5a80` | **`+0x100`** |
| `__TEXT.__cstring` | `0x1dc2` | `0x1e82` | **`+0xc0`** |
| `__AUTH_CONST.__const` | `0x2fa78` | `0x2f9d0` | **`-0xa8`** |
| `__AUTH_CONST.__auth_got` | `0xf30` | `0xfa8` | **`+0x78`** |
| `__TEXT.__unwind_info` | `0x3118` | `0x3180` | **`+0x68`** |
| `__TEXT.__const` | `0xaf94` | `0xafe4` | **`+0x50`** |
| `__DATA.__common` | `0x80` | `0xa0` | **`+0x20`** |
| `__TEXT.__constg_swiftt` | `0x40b4` | `0x4094` | **`-0x20`** |
| `__DATA.__data` | `0x1a48` | `0x1a60` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x560` | `0x578` | **`+0x18`** |
| `__TEXT.__swift5_assocty` | `0x540` | `0x558` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x438` | `0x424` | **`-0x14`** |
| `__DATA_CONST.__const` | `0xfb8` | `0xfc8` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x1220` | `0x1230` | **`+0x10`** |
| `__TEXT.__swift5_reflstr` | `0x36ec` | `0x36fc` | **`+0x10`** |
| `__TEXT.__swift5_proto` | `0x328` | `0x330` | **`+0x8`** |
| `__TEXT.__swift5_typeref` | `0x2342` | `0x233c` | **`-0x6`** |
| `__TEXT.__swift5_fieldmd` | `0x4614` | `0x4610` | **`-0x4`** |
| `__TEXT.__swift5_types` | `0x59c` | `0x598` | **`-0x4`** |
| `__TEXT.__swift_as_cont` | `0x2610` | `0x2614` | **`+0x4`** |
| `__TEXT.__oslogstring` | `—` | `0x3` | **`+0x3`** |

### Other Changes

```diff

-24.0.0.0.1
+24.0.2.0.0

+  - /System/Library/Frameworks/Security.framework/Security

-  Functions: 7106
-  Symbols:   14243
-  CStrings:  179
+  Functions: 7132
+  Symbols:   14296
+  CStrings:  186
Symbols:
+ _$s19RealityCoreRenderer12MeshInstanceC8meshPart8pipeline17geometryArguments07surfaceJ008lightingJ09transform12sortCategory16triangleFillMode2idAcA0dG0C_AA19RenderPipelineStateCAA13ArgumentTableCSgA2SSo13simd_float4x4aAC04SortO0OSo011MTLTriangleqR0V10Foundation4UUIDVSgtAA0T12ContextErrorOYKcfCTq
+ _$s19RealityCoreRenderer12MeshInstanceC8meshPart8pipeline17geometryArguments07surfaceJ008lightingJ09transform12sortCategory16triangleFillMode2idAcA0dG0C_AA19RenderPipelineStateCAA13ArgumentTableCSgA2SSo13simd_float4x4aAC04SortO0OSo011MTLTriangleqR0V10Foundation4UUIDVSgtAA0T12ContextErrorOYKcfc
+ _$s19RealityCoreRenderer14_Proto_Pose_v1VwstTm
+ _$s19RealityCoreRenderer16MaterialCompilerC9ResourcesV6deviceAESo9MTLDevice_p_tYaKcfCTY2248_
+ _$s19RealityCoreRenderer17BoundingSphereBoxVwstTm
+ _$s19RealityCoreRenderer20LowLevelMeshInstanceC16triangleFillModeSo011MTLTriangleiJ0VvM
+ _$s19RealityCoreRenderer20LowLevelMeshInstanceC16triangleFillModeSo011MTLTriangleiJ0VvM.resume
+ _$s19RealityCoreRenderer20LowLevelMeshInstanceC16triangleFillModeSo011MTLTriangleiJ0Vvg
+ _$s19RealityCoreRenderer20LowLevelMeshInstanceC16triangleFillModeSo011MTLTriangleiJ0VvpMV
+ _$s19RealityCoreRenderer20LowLevelMeshInstanceC16triangleFillModeSo011MTLTriangleiJ0Vvs
+ _$s19RealityCoreRenderer23StandaloneRenderContextC13ConfigurationV21shouldUseResidencySetSbvg
+ _$s19RealityCoreRenderer23StandaloneRenderContextC13ConfigurationV26residencySetDefaultEnabled33_C5DA9C4746BA93686999737EE2989783LLSbSgvpZ
+ _$s19RealityCoreRenderer23StandaloneRenderContextC13ConfigurationV26residencySetDefaultEnabled33_C5DA9C4746BA93686999737EE2989783LLSbSgvpZfiAHyXEfU_
+ _$s19RealityCoreRenderer23StandaloneRenderContextC13ConfigurationV26residencySetDefaultEnabled33_C5DA9C4746BA93686999737EE2989783LL_WZ
+ _$s19RealityCoreRenderer23StandaloneRenderContextC13ConfigurationV26residencySetDefaultEnabled33_C5DA9C4746BA93686999737EE2989783LL_Wz
+ _$s19RealityCoreRenderer23StandaloneRenderContextC13ConfigurationV35indirectCommandBufferDefaultEnabled33_C5DA9C4746BA93686999737EE2989783LLSbSgvpZ
+ _$s19RealityCoreRenderer23StandaloneRenderContextC13ConfigurationV35indirectCommandBufferDefaultEnabled33_C5DA9C4746BA93686999737EE2989783LLSbSgvpZfiAHyXEfU_
+ _$s19RealityCoreRenderer23StandaloneRenderContextC13ConfigurationV35indirectCommandBufferDefaultEnabled33_C5DA9C4746BA93686999737EE2989783LL_WZ
+ _$s19RealityCoreRenderer23StandaloneRenderContextC13ConfigurationV35indirectCommandBufferDefaultEnabled33_C5DA9C4746BA93686999737EE2989783LL_Wz
+ _$s19RealityCoreRenderer25InstanceTransformResourceC4readyxxs4SpanVySo13simd_float4x4aGnq_YKXEq_YKs5ErrorR_Ri_zr0_lFxs03RawH0Vq_YKXEfU_TATm
+ _$s19RealityCoreRenderer25InstanceTransformResourceC4readyxxs4SpanVySo13simd_float4x4aGnq_YKXEq_YKs5ErrorR_Ri_zr0_lFxs03RawH0Vq_YKXEfU_xAIq_YKXEfU_
+ _$s19RealityCoreRenderer25InstanceTransformResourceC4readyxxs4SpanVySo13simd_float4x4aGnq_YKXEq_YKs5ErrorR_Ri_zr0_lFxs03RawH0Vq_YKXEfU_xAIq_YKXEfU_TA
+ _$s19RealityCoreRenderer26getBoolValueForEntitlementySbSSF
+ _$s19RealityCoreRenderer27_Proto_BoundingSphereBox_v1VwstTm
+ _$s19RealityCoreRenderer3LogV6logger2os6LoggerVvpZ
+ _$s19RealityCoreRenderer3LogV6logger_WZ
+ _$s19RealityCoreRenderer3LogV6logger_Wz
+ _$s2os32getNullTerminatedUTF8PointerImpl_21storingStringOwnersInSVSS_SpyypGSgztF
+ _$s2os6LoggerV9logObjectSo03OS_a1_C0Cvg
+ _$s2os6LoggerV9subsystem8categoryACSS_SStcfC
+ _$s2os6LoggerVMa
+ _$sSS8UTF8ViewV13_foreignCountSiyF
+ _$sSa6append10contentsOfyqd__n_t7ElementQyd__RszSTRd__lFs5UInt8V_SayAFGTgq5
+ _$sSbN
+ _$sSo13MTLClearColorawstTm
+ _$sSo13os_log_type_ta0A0E4infoABvgZ
+ _$sSo19MTLTriangleFillModeVSQSCMc
+ _$sSo19MTLTriangleFillModeVSQSCMcMK
+ _$sSo19MTLTriangleFillModeVSQSCSQ2eeoiySbx_xtFZTW
+ _$sSo19MTLTriangleFillModeVSYSCMA
+ _$sSo19MTLTriangleFillModeVSYSCMc
+ _$sSo19MTLTriangleFillModeVSYSCMcMK
+ _$sSo19MTLTriangleFillModeVSYSCSY8rawValue03RawE0QzvgTW
+ _$sSo19MTLTriangleFillModeVSYSCSY8rawValuexSg03RawE0Qz_tcfCTW
+ _$sSo9MTLDeviceP19RealityCoreRendererE32supportsIndirectTriangleFillModeSbvg
+ _$ss11_StringGutsV16_deconstructUTF87scratchyXlSg5owner_xSi6lengthSb11usesScratchSb15allocatedMemorytSwSg_ts8_PointerRzlFSV_Tgq5
+ _$ss11_StringGutsV16_foreignCopyUTF84intoSiSgSrys5UInt8VG_tF
+ _$ss11_StringGutsV23_allocateForDeconstructyXl5owner_SVSi6lengthtyF
+ _$ss11_StringGutsV23_allocateForDeconstructyXl5owner_SVSi6lengthtyFTv_r
+ _$ss11_StringGutsVN
+ _$ss12_ArrayBufferV20_consumeAndCreateNew14bufferIsUnique15minimumCapacity13growForAppendAByxGSb_SiSbtFs5UInt8V_Tgq5
+ _$ss13_StringObjectV10sharedUTF8SRys5UInt8VGvg
+ _$ss14MutableRawSpanV19RealityCoreRendererE19withMemoryReboundToyq0_xm_q0_s0aC0VyxGzq_YKXEtq_YKs15BitwiseCopyableRzs5ErrorR_Ri_0_r1_lFq0_Swq_YKXEfU_Tm
+ _$ss22_ContiguousArrayBufferV19_uninitializedCount15minimumCapacityAByxGSi_SitcfCs5UInt8V_Tt1gq5
+ _$ss23_ContiguousArrayStorageCys5UInt8VGMR
+ _$ss23_ContiguousArrayStorageCys5UInt8VGMd
+ _$ss32_copyCollectionToContiguousArrayys0dE0Vy7ElementQzGxSlRzlFSS8UTF8ViewV_Tgq5
+ _$ss7RawSpanV19RealityCoreRendererE19withMemoryReboundToyq0_xm_q0_s0B0VyxGq_YKXEtq_YKs15BitwiseCopyableRzs5ErrorR_Ri_0_r1_lF
+ _$ss7RawSpanV19RealityCoreRendererE19withMemoryReboundToyq0_xm_q0_s0B0VyxGq_YKXEtq_YKs15BitwiseCopyableRzs5ErrorR_Ri_0_r1_lFq0_SWq_YKXEfU_q0_SRyxGq_YKXEfU_
+ _$syXlN
+ _MTLGPUDebugEnabled
+ _OBJC_CLASS_$_NSUserDefaults
+ _SecTaskCopyValueForEntitlement
+ _SecTaskCreateFromSelf
+ ___swift_allocate_value_buffer
+ ___swift_memcpy304_8
+ ___swift_project_value_buffer
+ __os_log_impl
+ _os_log_type_enabled
+ _swift_slowAlloc
+ _swift_slowDealloc
+ _symbolic _____y_____G s23_ContiguousArrayStorageC s5UInt8V
+ _sysctlbyname
- _$s15Synchronization5_CellVySo16os_unfair_lock_sVGMR
- _$s15Synchronization5_CellVySo16os_unfair_lock_sVGMd
- _$s19RealityCoreRenderer12MeshInstanceC8meshPart8pipeline17geometryArguments07surfaceJ008lightingJ09transform12sortCategory2idAcA0dG0C_AA19RenderPipelineStateCAA13ArgumentTableCSgA2RSo13simd_float4x4aAC04SortO0O10Foundation4UUIDVSgtAA0Q12ContextErrorOYKcfCTq
- _$s19RealityCoreRenderer12MeshInstanceC8meshPart8pipeline17geometryArguments07surfaceJ008lightingJ09transform12sortCategory2idAcA0dG0C_AA19RenderPipelineStateCAA13ArgumentTableCSgA2RSo13simd_float4x4aAC04SortO0O10Foundation4UUIDVSgtAA0Q12ContextErrorOYKcfc
- _$sSo16os_unfair_lock_sVMB
- _$sSo16os_unfair_lock_sVMF
- _$sSo16os_unfair_lock_sVML
- _$sSo16os_unfair_lock_sVMa
- _$sSo16os_unfair_lock_sVMf
- _$sSo16os_unfair_lock_sVMn
- _$sSo16os_unfair_lock_sVWV
- _$sSo16os_unfair_lock_sVwet
- _$sSo16os_unfair_lock_sVwst
- _$ss14MutableRawSpanV19RealityCoreRendererE19withMemoryReboundToyq0_xm_q0_s0aC0VyxGzq_YKXEtq_YKs15BitwiseCopyableRzs5ErrorR_Ri_0_r1_lFq0_Swq_YKXEfU_
- ___swift_memcpy129_16
- ___swift_memcpy296_8
- _kCGColorSpaceDisplayP3
- _symbolic _____ So16os_unfair_lock_sV
- _symbolic _____y_____G 15Synchronization5_CellVAARi_zrlE So16os_unfair_lock_sV
- _type_layout_string So16os_unfair_lock_sV
CStrings:
+ "%s"
+ "Indirect command buffer rendering disabled"
+ "Indirect command buffer rendering enabled"
+ "RealityCoreRenderer"
+ "Residency sets disabled"
+ "Residency sets enabled"
+ "com.apple.RealityKit"
+ "com.apple.developer.gpu-restricted"
+ "com.apple.private.gpu-restricted"
+ "com.apple.re.indirectCommandBuffer"
+ "com.apple.re.residencySet"
+ "kern.hv_vmm_present"
+ "realitykit::post_lighting_private::api::post_lighting_color"
+ "realitykit::post_lighting_private::api::set_post_lighting_color"
+ "realitykit::post_lighting_private::api::surface_data"
- "realitykit::post_lighting::api::post_lighting_color"
- "realitykit::post_lighting::api::set_post_lighting_color"
- "realitykit::post_lighting::api::surface_data"
- "realitykit::surface::api::set_bent_normal"
- "realitykit::surface::api::set_subsurface_color"
- "realitykit::surface::api::set_subsurface_radius"
- "realitykit::surface::api::set_subsurface_radius_scale"
- "realitykit::surface::api::set_subsurface_weight"
```
