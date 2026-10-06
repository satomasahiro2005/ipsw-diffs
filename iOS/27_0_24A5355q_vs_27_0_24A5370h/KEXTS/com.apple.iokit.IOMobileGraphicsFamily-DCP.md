## com.apple.iokit.IOMobileGraphicsFamily-DCP

> `com.apple.iokit.IOMobileGraphicsFamily-DCP`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__auth_stubs` | `0x0` | `0xe60` | **`+0xe60`** |
| `__TEXT_EXEC.__text` | `0x293e4` | `0x2989c` | **`+0x4b8`** |

### Other Changes

```diff

-700.50.66.0.0
+700.50.72.0.0
Functions:
~ sub_fffffff00a0b62f4 -> sub_fffffff00a139994 : 212 -> 244
~ __ZN5IOMFB12ServiceRelay18service_record_getEj : 72 -> 96
~ sub_fffffff00a0b75e0 -> sub_fffffff00a13acb8 : 1888 -> 1884
~ _strcmp : 2696 -> 2692
~ __ZN21IOMobileFramebufferAP18start_client_stateEv : 324 -> 336
~ __ZN21IOMobileFramebufferAP4stopEP9IOService : 1128 -> 1188
~ sub_fffffff00a0ba0f4 -> sub_fffffff00a13d80c : 688 -> 712
~ sub_fffffff00a0ba764 -> sub_fffffff00a13de94 : 556 -> 548
~ __ZN21IOMobileFramebufferAP26allocate_lpr_buffers_gatedEb : 1968 -> 1936
~ __ZN21IOMobileFramebufferAP11surface_mapEP9IOSurfacePP12IODMACommandPybbb : 1264 -> 1272
~ __ZN21IOMobileFramebufferAP16add_notificationE22IOMFB_NotificationTypeP18IOMFBNotifyRequestP22IOMFBNotifyRequestArgs : 516 -> 548
~ sub_fffffff00a0bce80 -> sub_fffffff00a1405b0 : 316 -> 348
~ __ZN21IOMobileFramebufferAP22powerUpDART_impl_gatedEbP8IOMapper : 388 -> 384
~ __ZN21IOMobileFramebufferAP24DARTErrorHandlerCallbackEPvPK15IODARTErrorInfo : 708 -> 704
~ __ZN21IOMobileFramebufferAP32cancel_all_pending_shared_eventsEv : 1656 -> 1680
~ __ZN21IOMobileFramebufferAP17allocate_carveoutEP9IOSurfacejj : 592 -> 608
~ __ZN21IOMobileFramebufferAP19async_swap_validateEP12IOMFBSwapRecP18IOMFBSwapIORequest : 348 -> 340
~ sub_fffffff00a0c3114 -> sub_fffffff00a14687c : 1736 -> 1760
~ __ZN21IOMobileFramebufferAP17io_fence_callbackEPvS0_P9IOSurfacei : 1636 -> 1732
~ sub_fffffff00a0c4d24 -> sub_fffffff00a148504 : 592 -> 624
~ __ZN21IOMobileFramebufferAP17swap_apply_fencesEP12IOMFBSwapRecP18IOMFBSwapIORequestPd : 1200 -> 1204
~ __ZN21IOMobileFramebufferAP21swap_submit_with_tagsEP12IOMFBSwapRecP12IOUserClientjPj : 4512 -> 4572
~ __ZN21IOMobileFramebufferAP40updateDisplayedDataFromPendingSwap_gatedEP18IOMFBSwapIORequest : 772 -> 1012
~ sub_fffffff00a0c7d6c -> sub_fffffff00a14b69c : 692 -> 684
~ __ZN21IOMobileFramebufferAP32swap_complete_head_of_line_gatedEjbjb : 352 -> 404
~ __ZN21IOMobileFramebufferAP22swap_complete_ap_gatedEjbPK16SwapCompleteDataPK12SwapInfoBlobjb : 808 -> 844
~ sub_fffffff00a0c84a8 -> sub_fffffff00a14be28 : 128 -> 164
~ sub_fffffff00a0c88ec -> sub_fffffff00a14c290 : 512 -> 544
~ sub_fffffff00a0c8aec -> sub_fffffff00a14c4b0 : 284 -> 320
~ sub_fffffff00a0c8cb4 -> sub_fffffff00a14c69c : 516 -> 504
~ sub_fffffff00a0c9380 -> sub_fffffff00a14cd5c : 80 -> 76
~ sub_fffffff00a0c9574 -> sub_fffffff00a14cf4c : 628 -> 664
~ sub_fffffff00a0cb524 -> sub_fffffff00a14ef20 : 716 -> 748
~ sub_fffffff00a0cb7f0 -> sub_fffffff00a14f20c : 568 -> 588
~ sub_fffffff00a0cba28 -> sub_fffffff00a14f458 : 296 -> 316
~ __ZN21IOMobileFramebufferAP13set_block_dcpEP4taskjjPKyjPKhmyjb : 488 -> 504
~ __ZNK21IOMobileFramebufferAP13get_block_dcpEP4taskjjPKyjPhm : 452 -> 464
~ __ZN21IOMobileFramebufferAP17get_buf_block_dcpEP4taskjjPKyjPKhmyjb : 488 -> 504
~ __ZN21IOMobileFramebufferAP17set_parameter_dcpE18IOMFBParameterNamePKyj : 212 -> 220
~ __ZN19AppleDCPLinkService5startEP9IOService : 2752 -> 2764
~ sub_fffffff00a0d01f8 -> sub_fffffff00a153c7c : 472 -> 492
~ sub_fffffff00a0d081c -> sub_fffffff00a1542b4 : 196 -> 216
~ sub_fffffff00a0d0f6c -> sub_fffffff00a154a18 : 308 -> 324
~ sub_fffffff00a0d1bbc -> sub_fffffff00a155678 : 276 -> 336
~ __ZZN19AppleDCPLinkService13wait_for_idleEvEN3$_08__invokeEP8OSObjectPvS3_S3_S3_ : 404 -> 424
~ sub_fffffff00a0d1ec4 -> sub_fffffff00a1559d0 : 292 -> 304
~ sub_fffffff00a0d2018 -> sub_fffffff00a155b30 : 60 -> 76
~ sub_fffffff00a0d31a0 -> sub_fffffff00a156cc8 : 272 -> 276
~ sub_fffffff00a0d3400 -> sub_fffffff00a156f2c : 264 -> 268
~ sub_fffffff00a0d3658 -> sub_fffffff00a157188 : 264 -> 268
~ sub_fffffff00a0d3760 -> sub_fffffff00a157294 : 268 -> 272
~ sub_fffffff00a0d50e0 -> sub_fffffff00a158c18 : 328 -> 332
~ sub_fffffff00a0d5228 -> sub_fffffff00a158d64 : 96 -> 100
~ sub_fffffff00a0d5288 -> sub_fffffff00a158dc8 : 96 -> 100
~ sub_fffffff00a0d52e8 -> sub_fffffff00a158e2c : 228 -> 224
~ sub_fffffff00a0d60d0 -> sub_fffffff00a159c10 : 488 -> 520
~ sub_fffffff00a0dc3e8 -> sub_fffffff00a15ff48 : 276 -> 280
~ sub_fffffff00a0dc804 -> sub_fffffff00a160368 : 264 -> 268
~ __ZN31IOMobileFramebuffer_RemoteCalls15D583_callback__EPK12link_state_tP13link_stream_tPKvjPvj : 320 -> 316
~ sub_fffffff00a0dcdb4 -> sub_fffffff00a160918 : 252 -> 256
~ __ZN31IOMobileFramebuffer_RemoteCalls15D590_callback__EPK12link_state_tP13link_stream_tPKvjPvj : 256 -> 260
~ sub_fffffff00a0dd138 -> sub_fffffff00a160ca4 : 344 -> 340
~ sub_fffffff00a0dd32c -> sub_fffffff00a160e94 : 288 -> 284
~ __ZN31IOMobileFramebuffer_RemoteCalls15D596_callback__EPK12link_state_tP13link_stream_tPKvjPvj : 264 -> 268
~ sub_fffffff00a0dd8d4 -> sub_fffffff00a16143c : 320 -> 316
~ __ZN31IOMobileFramebuffer_RemoteCalls15D598_callback__EPK12link_state_tP13link_stream_tPKvjPvj : 296 -> 292
~ sub_fffffff00a0ddb3c -> sub_fffffff00a16169c : 296 -> 292
~ sub_fffffff00a0ddc64 -> sub_fffffff00a1617c0 : 296 -> 292
```
