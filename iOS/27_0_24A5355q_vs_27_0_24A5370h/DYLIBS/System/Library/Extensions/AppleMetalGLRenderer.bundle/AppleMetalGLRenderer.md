## AppleMetalGLRenderer

> `/System/Library/Extensions/AppleMetalGLRenderer.bundle/AppleMetalGLRenderer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x182e0` | `0x183c4` | **`+0xe4`** |

### Other Changes

```diff
Symbols:
+ __ZNSt3__119__allocate_at_leastB9fqn220106INS_9allocatorIP17GLRBufferResourceEENS_16allocator_traitsIS4_EEEENS_19__allocation_resultINT0_7pointerENS8_9size_typeEEERT_m
+ __ZNSt3__119__allocate_at_leastB9fqn220106INS_9allocatorIjEENS_16allocator_traitsIS2_EEEENS_19__allocation_resultINT0_7pointerENS6_9size_typeEEERT_m
+ __ZNSt3__16vectorIP17GLRBufferResourceNS_9allocatorIS2_EEE20__throw_length_errorB9fqn220106Ev
+ __ZNSt3__16vectorIjNS_9allocatorIjEEE20__throw_length_errorB9fqn220106Ev
+ __ZSt28__throw_bad_array_new_lengthB9fqn220106v
- __ZNSt3__119__allocate_at_leastB9fqn220100INS_9allocatorIP17GLRBufferResourceEENS_16allocator_traitsIS4_EEEENS_19__allocation_resultINT0_7pointerENS8_9size_typeEEERT_m
- __ZNSt3__119__allocate_at_leastB9fqn220100INS_9allocatorIjEENS_16allocator_traitsIS2_EEEENS_19__allocation_resultINT0_7pointerENS6_9size_typeEEERT_m
- __ZNSt3__16vectorIP17GLRBufferResourceNS_9allocatorIS2_EEE20__throw_length_errorB9fqn220100Ev
- __ZNSt3__16vectorIjNS_9allocatorIjEEE20__throw_length_errorB9fqn220100Ev
- __ZSt28__throw_bad_array_new_lengthB9fqn220100v
Functions:
~ __ZN11GLDQueryRec7deallocEv : 128 -> 124
~ __ZN13GLDContextRec18loadCurrentQueriesEv : 216 -> 220
~ __ZN12GLDDeviceRec4initEv : 980 -> 992
~ __ZN17GLDFramebufferRec11updateStateEh : 516 -> 508
~ __ZN21GLDPipelineProgramRec19createMetalFunctionEP13GLDProgramRecjj : 596 -> 612
~ __ZN15GLRResourceList19releaseAllResourcesEv : 236 -> 232
~ __ZN15GLRResourceList17makeResourcesBusyEv : 176 -> 172
~ __ZN15GLRResourceList28makeResourcesNotBusyAndResetEv : 296 -> 292
~ __ZN16GLDShareGroupRec7deallocEv : 164 -> 180
~ __ZN16GLDShareGroupRec17createZeroTextureEbi : 852 -> 848
~ __ZN13GLDTextureRec7deallocEv : 316 -> 320
~ ____ZN13GLDTextureRec11restoreDataEii_block_invoke : 164 -> 172
~ __ZN13GLDTextureRec23readTextureDataInternalEiijjPv : 1372 -> 1416
~ __ZN13GLDTextureRec17updatePixelFormatEv : 208 -> 216
~ __ZN13GLDTextureRec18getMetalSwizzleKeyEv : 204 -> 188
~ __ZN13GLDTextureRec20getIOSurfaceResourceEv : 1000 -> 992
~ __ZN13GLDTextureRec17allocMetalTextureEv : 308 -> 312
~ __ZN13GLDTextureRec18loadPrivateTextureEjPt : 1368 -> 1428
~ __ZN13GLDTextureRec18updateSamplerStateEj : 216 -> 208
~ __ZN12GLDDeviceRec20telemetryEmitTextureEv : 148 -> 152
~ __ZN13GLDContextRec25buildRenderPassDescriptorEv : 920 -> 968
~ __ZN13GLDContextRec22addRenderPassResourcesEv : 140 -> 160
~ __ZN13GLDContextRec13endRenderPassEv : 1096 -> 1104
~ __ZN13GLDContextRec28buildPipelineStateDescriptorEv : 680 -> 676
~ __ZN13GLDContextRec36setRenderTexturesAndSamplersInternalEjRjP23SetSamplerStateIMPCacheP18SetTextureIMPCache : 776 -> 788
~ __ZN13GLDContextRec22setRenderVertexBuffersEv : 284 -> 292
~ __ZN13GLDContextRec23setRenderVertexCurrentsEv : 188 -> 196
~ __ZN13GLDContextRec26setRenderPrimitiveCurrentsEv : 188 -> 196
~ __ZN13GLDContextRec31setRenderUniformBuffersInternalEPP17GLRBufferResourcePmmP17SetBufferIMPCache : 148 -> 140
~ __ZN13GLDContextRec25updateRenderColorMaskModeEv : 200 -> 196
~ _gldClearFramebufferData : 752 -> 756
~ __ZN13GLDContextRec18initWithShareGroupEP16GLDShareGroupRecPK11GLDStateRecPK17GLDPluginStateRecPK14GLRPixelFormatP19GLDContextConfigRec : 720 -> 736
~ __ZN13GLDContextRec7deallocEv : 688 -> 724
~ _gldBlitFramebufferData : 4548 -> 4556
~ __ZN13GLDContextRec29updateUniformBindingsInternalEjRjPP17GLRBufferResourcePmm : 480 -> 460
~ __ZN20GLRDataBufferManager7deallocEv : 88 -> 76
~ __ZN20GLRDataBufferManager15allocDataBufferEmPm : 292 -> 280
~ __ZN13GLDContextRec14tfDirtyBuffersEv : 144 -> 152
~ __ZL20gldRenderVertexArrayP13GLDContextRecjjiijPKviS2_ : 1756 -> 1740
~ __ZN13GLDContextRec19loadCurrentSamplersEj : 380 -> 368
~ __ZNK20GLRRenderPipelineKey14copyDescriptorERK16GLRFunctionCache : 1096 -> 1088
~ __ZN16GLRFunctionCache19newFunctionWithGLIREPU23objcproto12MTLDeviceSPI11objc_objectPvPU27objcproto16OS_dispatch_data8NSObject15MTLFunctionType : 264 -> 260
~ __ZNK16GLRFunctionCache6getKeyEPU22objcproto11MTLFunction11objc_object : 164 -> 160
~ _gldUpdateDispatch : 980 -> 984
~ __ZN13GLDContextRec19loadCurrentTexturesEjPKy : 792 -> 760
~ _gldUnbindTexture : 104 -> 120
~ __ZN13GLDContextRec15bindVertexArrayEP17GLDVertexArrayRecyy : 620 -> 616
~ __ZN13GLDContextRec26buildVertexArrayDescriptorEP21GLDPipelineProgramRecP17GLDVertexArrayRec : 720 -> 740
~ __ZN13GLDContextRec41buildPrimitiveBufferVertexArrayDescriptorEv : 1624 -> 1636
~ __ZN13GLDContextRec26setTranformFeedbackBuffersEv : 124 -> 140
~ __ZN13GLDContextRec28updateTransfromFeedbackStateEv : 368 -> 364
```
