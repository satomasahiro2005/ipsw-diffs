## WorkflowEditor

> `/System/Library/PrivateFrameworks/WorkflowEditor.framework/WorkflowEditor`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x28796c` | `0x2a05d0` | **`+0x18c64`** |
| `__AUTH_CONST.__const` | `0x166b0` | `0x178f8` | **`+0x1248`** |
| `__AUTH.__objc_data` | `0xbc48` | `0xc940` | **`+0xcf8`** |
| `__TEXT.__const` | `0x1db70` | `0x1e820` | **`+0xcb0`** |
| `__AUTH_CONST.__objc_const` | `0x17070` | `0x17b20` | **`+0xab0`** |
| `__TEXT.__constg_swiftt` | `0xd538` | `0xdef4` | **`+0x9bc`** |
| `__DATA.__bss` | `0x15770` | `0x15fe0` | **`+0x870`** |
| `__AUTH.__data` | `0x6f10` | `0x7770` | **`+0x860`** |
| `__TEXT.__swift5_reflstr` | `0x7bec` | `0x838c` | **`+0x7a0`** |
| `__TEXT.__swift5_typeref` | `0x1cbc6` | `0x1d32c` | **`+0x766`** |
| `__DATA.__data` | `0xd4d8` | `0xdb28` | **`+0x650`** |
| `__TEXT.__unwind_info` | `0xa770` | `0xad50` | **`+0x5e0`** |
| `__TEXT.__swift5_fieldmd` | `0x7f70` | `0x84fc` | **`+0x58c`** |
| `__TEXT.__swift5_capture` | `0x53ac` | `0x58f4` | **`+0x548`** |
| `__TEXT.__cstring` | `0x7562` | `0x79cc` | **`+0x46a`** |
| `__TEXT.__eh_frame` | `0x6f9c` | `0x7374` | **`+0x3d8`** |
| `__TEXT.__objc_methlist` | `0xb274` | `0xb44c` | **`+0x1d8`** |
| `__AUTH_CONST.__auth_got` | `0x3d80` | `0x3f30` | **`+0x1b0`** |
| `__DATA_CONST.__got` | `0x2888` | `0x2a08` | **`+0x180`** |
| `__DATA_CONST.__objc_selrefs` | `0x7210` | `0x7368` | **`+0x158`** |
| `__DATA_CONST.__const` | `0x1578` | `0x1690` | **`+0x118`** |
| `__TEXT.__oslogstring` | `0x1d24` | `0x1e02` | **`+0xde`** |
| `__TEXT.__swift5_assocty` | `0x19e8` | `0x1a60` | **`+0x78`** |
| `__TEXT.__ustring` | `0xfe` | `0x15e` | **`+0x60`** |
| `__DATA.__common` | `0x350` | `0x3a8` | **`+0x58`** |
| `__TEXT.__swift5_types` | `0x884` | `0x8d0` | **`+0x4c`** |
| `__DATA_CONST.__objc_classlist` | `0x788` | `0x7d0` | **`+0x48`** |
| `__AUTH_CONST.__cfstring` | `0x1620` | `0x1660` | **`+0x40`** |
| `__TEXT.__swift5_proto` | `0xb24` | `0xb60` | **`+0x3c`** |
| `__TEXT.__swift_as_cont` | `0x45c` | `0x488` | **`+0x2c`** |
| `__TEXT.__swift5_builtin` | `0x3c0` | `0x3d4` | **`+0x14`** |
| `__TEXT.__swift5_mpenum` | `0x70` | `0x80` | **`+0x10`** |
| `__TEXT.__swift_as_entry` | `0x1c8` | `0x1d0` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x1d8` | `0x1e0` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x548` | `0x54c` | **`+0x4`** |

### Other Changes

```diff

-5028.0.21.0.0
+5032.5.0.0.0
+  - /System/Library/Frameworks/AVFoundation.framework/AVFoundation

-  Functions: 19152
-  Symbols:   9714
-  CStrings:  1050
+  Functions: 20006
+  Symbols:   10046
+  CStrings:  1088
Symbols:
+ -[AddContactRecipientButtonHandler contactPicker:didSelectContact:]
+ -[WFParameterValuePickerViewController collectionByExcludingSiblingStates:]
+ -[WFParameterValuePickerViewController excludedStates]
+ -[WFParameterValuePickerViewController setExcludedStates:]
+ GCC_except_table1109
+ GCC_except_table1117
+ GCC_except_table1126
+ GCC_except_table1131
+ GCC_except_table1211
+ GCC_except_table1569
+ GCC_except_table1573
+ GCC_except_table1576
+ GCC_except_table1621
+ GCC_except_table1630
+ GCC_except_table860
+ GCC_except_table871
+ GCC_except_table884
+ _AVLayerVideoGravityResizeAspectFill
+ _OBJC_CLASS_$_AVPlayerItem
+ _OBJC_CLASS_$_AVPlayerLayer
+ _OBJC_CLASS_$_AVPlayerLooper
+ _OBJC_CLASS_$_AVQueuePlayer
+ _OBJC_CLASS_$_WFAppleIntelligenceAvailabilityProvider
+ _OBJC_CLASS_$_WFParameterRelationResource
+ _OBJC_CLASS_$_WFResourceWithActiveDependents
+ _OBJC_CLASS_$_WFSlotConjunctionFormatter
+ _OBJC_IVAR_$_WFParameterValuePickerViewController._excludedStates
+ _OBJC_METACLASS_$_WFSlotConjunctionFormatter
+ _OBJC_METACLASS_$__TtC14WorkflowEditorP33_614F1DFEBF3DEBC915070CB296BEEF1915WFEditorTipCell
+ _OBJC_METACLASS_$__TtC14WorkflowEditorP33_614F1DFEBF3DEBC915070CB296BEEF1916LoopingVideoView
+ _OBJC_METACLASS_$__TtC14WorkflowEditorP33_614F1DFEBF3DEBC915070CB296BEEF1925NonSelectableLinkTextView
+ _OBJC_METACLASS_$__TtC14WorkflowEditorP33_614F1DFEBF3DEBC915070CB296BEEF1928WFEditorTriggerSeparatorCell
+ _OBJC_METACLASS_$__TtC14WorkflowEditorP33_614F1DFEBF3DEBC915070CB296BEEF1932WFEditorTriggerBottomSpacingCell
+ _OUTLINED_FUNCTION_237
+ _OUTLINED_FUNCTION_238
+ _OUTLINED_FUNCTION_239
+ _OUTLINED_FUNCTION_240
+ _OUTLINED_FUNCTION_241
+ _OUTLINED_FUNCTION_242
+ _OUTLINED_FUNCTION_243
+ _OUTLINED_FUNCTION_244
+ _OUTLINED_FUNCTION_245
+ _OUTLINED_FUNCTION_246
+ _OUTLINED_FUNCTION_247
+ _OUTLINED_FUNCTION_248
+ _OUTLINED_FUNCTION_249
+ _OUTLINED_FUNCTION_250
+ _OUTLINED_FUNCTION_251
+ _OUTLINED_FUNCTION_252
+ _OUTLINED_FUNCTION_253
+ _OUTLINED_FUNCTION_254
+ _OUTLINED_FUNCTION_255
+ _OUTLINED_FUNCTION_256
+ _OUTLINED_FUNCTION_257
+ _OUTLINED_FUNCTION_258
+ _OUTLINED_FUNCTION_259
+ _OUTLINED_FUNCTION_260
+ _OUTLINED_FUNCTION_261
+ _OUTLINED_FUNCTION_262
+ _OUTLINED_FUNCTION_263
+ _OUTLINED_FUNCTION_264
+ _OUTLINED_FUNCTION_265
+ _OUTLINED_FUNCTION_266
+ _OUTLINED_FUNCTION_267
+ _OUTLINED_FUNCTION_268
+ _OUTLINED_FUNCTION_269
+ _OUTLINED_FUNCTION_270
+ _OUTLINED_FUNCTION_271
+ _OUTLINED_FUNCTION_272
+ _OUTLINED_FUNCTION_273
+ _OUTLINED_FUNCTION_274
+ _OUTLINED_FUNCTION_275
+ _OUTLINED_FUNCTION_276
+ _OUTLINED_FUNCTION_277
+ _OUTLINED_FUNCTION_278
+ _OUTLINED_FUNCTION_279
+ _OUTLINED_FUNCTION_280
+ _OUTLINED_FUNCTION_281
+ _OUTLINED_FUNCTION_282
+ _OUTLINED_FUNCTION_283
+ _OUTLINED_FUNCTION_284
+ _OUTLINED_FUNCTION_285
+ _OUTLINED_FUNCTION_286
+ _OUTLINED_FUNCTION_287
+ _OUTLINED_FUNCTION_288
+ _OUTLINED_FUNCTION_289
+ _OUTLINED_FUNCTION_290
+ _OUTLINED_FUNCTION_291
+ _OUTLINED_FUNCTION_292
+ _OUTLINED_FUNCTION_293
+ _OUTLINED_FUNCTION_294
+ _OUTLINED_FUNCTION_295
+ _OUTLINED_FUNCTION_296
+ _OUTLINED_FUNCTION_297
+ _OUTLINED_FUNCTION_298
+ _OUTLINED_FUNCTION_299
+ _OUTLINED_FUNCTION_300
+ _OUTLINED_FUNCTION_301
+ _OUTLINED_FUNCTION_302
+ _OUTLINED_FUNCTION_303
+ _OUTLINED_FUNCTION_304
+ _OUTLINED_FUNCTION_305
+ _OUTLINED_FUNCTION_306
+ _OUTLINED_FUNCTION_307
+ _OUTLINED_FUNCTION_308
+ _OUTLINED_FUNCTION_309
+ _OUTLINED_FUNCTION_310
+ _OUTLINED_FUNCTION_311
+ _OUTLINED_FUNCTION_312
+ _OUTLINED_FUNCTION_313
+ _OUTLINED_FUNCTION_314
+ _OUTLINED_FUNCTION_315
+ _OUTLINED_FUNCTION_316
+ _OUTLINED_FUNCTION_317
+ _OUTLINED_FUNCTION_318
+ _OUTLINED_FUNCTION_319
+ _OUTLINED_FUNCTION_320
+ _OUTLINED_FUNCTION_321
+ _OUTLINED_FUNCTION_322
+ _OUTLINED_FUNCTION_323
+ _OUTLINED_FUNCTION_324
+ _OUTLINED_FUNCTION_325
+ _OUTLINED_FUNCTION_326
+ _OUTLINED_FUNCTION_327
+ _OUTLINED_FUNCTION_328
+ _OUTLINED_FUNCTION_329
+ _OUTLINED_FUNCTION_330
+ _OUTLINED_FUNCTION_331
+ _OUTLINED_FUNCTION_332
+ _OUTLINED_FUNCTION_333
+ _OUTLINED_FUNCTION_334
+ _OUTLINED_FUNCTION_335
+ _OUTLINED_FUNCTION_336
+ _OUTLINED_FUNCTION_337
+ _OUTLINED_FUNCTION_338
+ _OUTLINED_FUNCTION_339
+ _OUTLINED_FUNCTION_340
+ _OUTLINED_FUNCTION_341
+ _OUTLINED_FUNCTION_342
+ _OUTLINED_FUNCTION_343
+ _OUTLINED_FUNCTION_344
+ _OUTLINED_FUNCTION_345
+ _OUTLINED_FUNCTION_346
+ _OUTLINED_FUNCTION_347
+ _OUTLINED_FUNCTION_348
+ _OUTLINED_FUNCTION_349
+ _OUTLINED_FUNCTION_350
+ _OUTLINED_FUNCTION_351
+ _OUTLINED_FUNCTION_352
+ _OUTLINED_FUNCTION_353
+ _OUTLINED_FUNCTION_354
+ _OUTLINED_FUNCTION_355
+ _OUTLINED_FUNCTION_356
+ _OUTLINED_FUNCTION_357
+ _OUTLINED_FUNCTION_358
+ _OUTLINED_FUNCTION_359
+ _OUTLINED_FUNCTION_360
+ _OUTLINED_FUNCTION_361
+ _OUTLINED_FUNCTION_362
+ _OUTLINED_FUNCTION_363
+ _OUTLINED_FUNCTION_364
+ _OUTLINED_FUNCTION_365
+ _OUTLINED_FUNCTION_366
+ _OUTLINED_FUNCTION_367
+ _OUTLINED_FUNCTION_368
+ _OUTLINED_FUNCTION_369
+ _OUTLINED_FUNCTION_370
+ _OUTLINED_FUNCTION_371
+ _OUTLINED_FUNCTION_372
+ _OUTLINED_FUNCTION_373
+ _OUTLINED_FUNCTION_374
+ _OUTLINED_FUNCTION_375
+ _OUTLINED_FUNCTION_376
+ _OUTLINED_FUNCTION_377
+ _OUTLINED_FUNCTION_378
+ _OUTLINED_FUNCTION_379
+ _OUTLINED_FUNCTION_380
+ _OUTLINED_FUNCTION_381
+ _OUTLINED_FUNCTION_382
+ _OUTLINED_FUNCTION_383
+ _OUTLINED_FUNCTION_384
+ _OUTLINED_FUNCTION_385
+ _OUTLINED_FUNCTION_386
+ _OUTLINED_FUNCTION_387
+ _OUTLINED_FUNCTION_388
+ _OUTLINED_FUNCTION_389
+ _OUTLINED_FUNCTION_390
+ _OUTLINED_FUNCTION_391
+ _OUTLINED_FUNCTION_392
+ _OUTLINED_FUNCTION_393
+ _OUTLINED_FUNCTION_394
+ _OUTLINED_FUNCTION_395
+ _OUTLINED_FUNCTION_396
+ _OUTLINED_FUNCTION_397
+ _OUTLINED_FUNCTION_398
+ _OUTLINED_FUNCTION_399
+ _OUTLINED_FUNCTION_400
+ _OUTLINED_FUNCTION_401
+ _UIFontWeightRegular
+ _WFShortcutSourceDescribeAShortcut
+ _WFShortcutsEditorTipDismissedKey
+ __CLASS_METHODS_WFSlotConjunctionFormatter
+ __CLASS_METHODS__TtC14WorkflowEditorP33_614F1DFEBF3DEBC915070CB296BEEF1916LoopingVideoView
+ __CLASS_PROPERTIES__TtC14WorkflowEditorP33_614F1DFEBF3DEBC915070CB296BEEF1916LoopingVideoView
+ __DATA_WFSlotConjunctionFormatter
+ __DATA__TtC14WorkflowEditorP33_614F1DFEBF3DEBC915070CB296BEEF1915WFEditorTipCell
+ __DATA__TtC14WorkflowEditorP33_614F1DFEBF3DEBC915070CB296BEEF1915WFEditorTipItem
+ __DATA__TtC14WorkflowEditorP33_614F1DFEBF3DEBC915070CB296BEEF1916LoopingVideoView
+ __DATA__TtC14WorkflowEditorP33_614F1DFEBF3DEBC915070CB296BEEF1925NonSelectableLinkTextView
+ __DATA__TtC14WorkflowEditorP33_614F1DFEBF3DEBC915070CB296BEEF1928WFEditorTriggerSeparatorCell
+ __DATA__TtC14WorkflowEditorP33_614F1DFEBF3DEBC915070CB296BEEF1928WFEditorTriggerSeparatorItem
+ __DATA__TtC14WorkflowEditorP33_614F1DFEBF3DEBC915070CB296BEEF1932WFEditorTriggerBottomSpacingCell
+ __DATA__TtC14WorkflowEditorP33_614F1DFEBF3DEBC915070CB296BEEF1932WFEditorTriggerBottomSpacingItem
+ __INSTANCE_METHODS_WFSlotConjunctionFormatter
+ __INSTANCE_METHODS__TtC14WorkflowEditorP33_614F1DFEBF3DEBC915070CB296BEEF1916LoopingVideoView
+ __INSTANCE_METHODS__TtC14WorkflowEditorP33_614F1DFEBF3DEBC915070CB296BEEF1925NonSelectableLinkTextView
+ __INSTANCE_METHODS__TtC14WorkflowEditorP33_614F1DFEBF3DEBC915070CB296BEEF1928WFEditorTriggerSeparatorCell
+ __INSTANCE_METHODS__TtC14WorkflowEditorP33_614F1DFEBF3DEBC915070CB296BEEF1932WFEditorTriggerBottomSpacingCell
+ __IVARS__TtC14WorkflowEditorP33_614F1DFEBF3DEBC915070CB296BEEF1915WFEditorTipCell
+ __IVARS__TtC14WorkflowEditorP33_614F1DFEBF3DEBC915070CB296BEEF1916LoopingVideoView
+ __IVARS__TtC14WorkflowEditorP33_614F1DFEBF3DEBC915070CB296BEEF1928WFEditorTriggerSeparatorCell
+ __METACLASS_DATA_WFSlotConjunctionFormatter
+ __METACLASS_DATA__TtC14WorkflowEditorP33_614F1DFEBF3DEBC915070CB296BEEF1915WFEditorTipCell
+ __METACLASS_DATA__TtC14WorkflowEditorP33_614F1DFEBF3DEBC915070CB296BEEF1915WFEditorTipItem
+ __METACLASS_DATA__TtC14WorkflowEditorP33_614F1DFEBF3DEBC915070CB296BEEF1916LoopingVideoView
+ __METACLASS_DATA__TtC14WorkflowEditorP33_614F1DFEBF3DEBC915070CB296BEEF1925NonSelectableLinkTextView
+ __METACLASS_DATA__TtC14WorkflowEditorP33_614F1DFEBF3DEBC915070CB296BEEF1928WFEditorTriggerSeparatorCell
+ __METACLASS_DATA__TtC14WorkflowEditorP33_614F1DFEBF3DEBC915070CB296BEEF1928WFEditorTriggerSeparatorItem
+ __METACLASS_DATA__TtC14WorkflowEditorP33_614F1DFEBF3DEBC915070CB296BEEF1932WFEditorTriggerBottomSpacingCell
+ __METACLASS_DATA__TtC14WorkflowEditorP33_614F1DFEBF3DEBC915070CB296BEEF1932WFEditorTriggerBottomSpacingItem
+ __OBJC_$_INSTANCE_METHODS__TtC14WorkflowEditorP33_614F1DFEBF3DEBC915070CB296BEEF1915WFEditorTipCell(WorkflowEditor)
+ __OBJC_CLASS_PROTOCOLS_$__TtC14WorkflowEditorP33_614F1DFEBF3DEBC915070CB296BEEF1915WFEditorTipCell(WorkflowEditor)
+ __PROPERTIES__TtC14WorkflowEditor19GenerativeOneUpView
+ __PROPERTIES__TtC14WorkflowEditorP33_614F1DFEBF3DEBC915070CB296BEEF1925NonSelectableLinkTextView
+ ___209+[WFEnumerationValuePicker presentWithParameter:state:slotIdentifier:initialCollection:variableProvider:variableUIDelegate:allowsPickingVariables:processing:presentationAnchor:cancelHandler:completionHandler:]_block_invoke
+ ___75-[WFParameterValuePickerViewController collectionByExcludingSiblingStates:]_block_invoke
+ ___block_descriptor_48_e8_32s_e35_v32?0"<WFParameterState>"8Q16^B24ls32l8
+ ___swift_closure_destructor.125Tm
+ ___swift_closure_destructor.137Tm
+ ___swift_closure_destructor.146Tm
+ ___swift_closure_destructor.263Tm
+ ___swift_closure_destructor.490Tm
+ ___swift_closure_destructor.582Tm
+ ___swift_closure_destructor.62Tm
+ ___swift_closure_destructor.71Tm
+ ___swift_closure_destructor.85Tm
+ ___swift_closure_destructor.88Tm
+ ___swift_closure_destructor.97Tm
+ ___swift_memcpy152_8
+ _associated conformance 14WorkflowEditor13PCCUpsellViewV5StateOSHAASQ
+ _associated conformance 14WorkflowEditor13PCCUpsellViewV7SwiftUI0D0AA4BodyAdEP_AdE
+ _associated conformance 14WorkflowEditor20ShortcutCreationTypeOSHAASQ
+ _associated conformance 14WorkflowEditor25ActionParameterIdentifier022_C2A3C381B62D57F59A208G9A47950B27LLVSHAASQ
+ _associated conformance 14WorkflowEditor25SummarizationShimmerLabelV7SwiftUI4ViewAA4BodyAdEP_AdE
+ _associated conformance 14WorkflowEditor26ShortcutCreationEntryPointOSHAASQ
+ _associated conformance 14WorkflowEditor29DescribeModelCallResponseType022_C2A3C381B62D57F59A208I9A47950B27LLOSHAASQ
+ _get_witness_table 7SwiftUI15ModifiedContentVyACyACyAA4TextVAA16_FlexFrameLayoutVGAA16_OverlayModifierVyACyAhA20_MaskAlignmentEffectVyACyACyACyAA14LinearGradientVAA01_gH0VGAA07_OffsetM0VGAGGGGGGAA017_AppearanceActionJ0VGAA4ViewHPAyAA1_HPAhAA1_HPAeAA1_HPyHC_AgA0sJ0HPyHCHC_AxAA2_HPyHCHC_A_AAA2_HPyHCHC
+ _get_witness_table 7SwiftUI15ModifiedContentVyACyACyACyACyACyAA6HStackVyAA05TupleD0VyAA5ImageVSg_AA4TextVAA6SpacerVQPGGAA30_EnvironmentKeyWritingModifierVyAA5ColorVSgGGAA14_PaddingLayoutVGAYGAA026_InsettableBackgroundShapeM0VyAtA7CapsuleVGGAYGAYGAA4ViewHPA6_AAA8_HPA5_AAA8_HPA_AAA8_HPAzAA8_HPAwAA8_HPApAA8_HPyHC_AvA0uM0HPyHCHC_AyAA9_HPyHCHC_AyAA9_HPyHCHC_A4_AAA9_HPyHCHC_AyAA9_HPyHCHC_AyAA9_HPyHCHC
+ _get_witness_table 7SwiftUI4ViewRzlAA15ModifiedContentVyxAA30_EnvironmentKeyWritingModifierVySSSgGGAaBHPxAaBHD1__AhA0cI0HPyHCHC
+ _get_witness_table qd__7SwiftUI4ViewHD2_AaBPAAE12onTapGesture5count7performQrSi_yyctFQOyAA15ModifiedContentVyAHyAHyAHyAA6HStackVyAA05TupleJ0VyAA5ImageV_AHyAHyAA4TextVAA16_FlexFrameLayoutVGAA08_PaddingQ0VGQPGGAA30_EnvironmentKeyWritingModifierVyAA5ColorVSgGGAUGAUGAA016_BackgroundStyleV0VyA0_GG_Qo_HO
+ _kCALineCapRound
+ _swift_dynamicCastObjCClassUnconditional
+ _symbolic SDySS_____GIegr_ 14ShortcutsAgent0B7ToolboxV6ResultV10ToolRenderV
+ _symbolic SDy_____SiG 14WorkflowEditor25ActionParameterIdentifier022_C2A3C381B62D57F59A208G9A47950B27LLV
+ _symbolic Say_____G 11WorkflowKit12WFNewTriggerC
+ _symbolic Say_____G 14WorkflowEditor28WFEditorTriggerSeparatorItem33_614F1DFEBF3DEBC915070CB296BEEF19LLC
+ _symbolic Say______pG So37WFEnumerationSupportingParameterStateP
+ _symbolic ScSy_____y______GG 14ShortcutsAgent0B7SessionC5EventO AA017DescribeAShortcutB0V
+ _symbolic ShySJG
+ _symbolic Shy_____G 14ShortcutsAgent12DaSErrorCodeO
+ _symbolic SiIegd_
+ _symbolic SiIegr_
+ _symbolic So10UITextViewCSg
+ _symbolic So12CAShapeLayerCSg
+ _symbolic So13AVQueuePlayerCSg
+ _symbolic So14AVPlayerLooperCSg
+ _symbolic _____ 14ShortcutsAgent017DescribeAShortcutB5EventO17GeneratedShortcutV
+ _symbolic _____ 14ShortcutsAgent0B7ToolboxV6ResultV
+ _symbolic _____ 14ShortcutsAgent10PickOutputO
+ _symbolic _____ 14ShortcutsAgent11PickRequestV
+ _symbolic _____ 14ShortcutsAgent16FindEntitiesToolV6OutputV
+ _symbolic _____ 14ShortcutsAgent16FindEntitiesToolV9ArgumentsV
+ _symbolic _____ 14ShortcutsAgent25DescribeAShortcutResponseV
+ _symbolic _____ 14WorkflowEditor0A8Snapshot022_C2A3C381B62D57F59A208E9A47950B27LLV
+ _symbolic _____ 14WorkflowEditor13PCCUpsellViewV
+ _symbolic _____ 14WorkflowEditor13PCCUpsellViewV5StateO
+ _symbolic _____ 14WorkflowEditor15WFEditorTipCell33_614F1DFEBF3DEBC915070CB296BEEF19LLC
+ _symbolic _____ 14WorkflowEditor15WFEditorTipItem33_614F1DFEBF3DEBC915070CB296BEEF19LLC
+ _symbolic _____ 14WorkflowEditor16LoopingVideoView33_614F1DFEBF3DEBC915070CB296BEEF19LLC
+ _symbolic _____ 14WorkflowEditor16SampleCellActionV
+ _symbolic _____ 14WorkflowEditor20ShortcutCreationTypeO
+ _symbolic _____ 14WorkflowEditor25ActionParameterIdentifier022_C2A3C381B62D57F59A208G9A47950B27LLV
+ _symbolic _____ 14WorkflowEditor25NonSelectableLinkTextView33_614F1DFEBF3DEBC915070CB296BEEF19LLC
+ _symbolic _____ 14WorkflowEditor25SummarizationShimmerLabelV
+ _symbolic _____ 14WorkflowEditor26ShortcutCreationEntryPointO
+ _symbolic _____ 14WorkflowEditor26WFSlotConjunctionFormatterC
+ _symbolic _____ 14WorkflowEditor28WFEditorTriggerSeparatorCell33_614F1DFEBF3DEBC915070CB296BEEF19LLC
+ _symbolic _____ 14WorkflowEditor28WFEditorTriggerSeparatorItem33_614F1DFEBF3DEBC915070CB296BEEF19LLC
+ _symbolic _____ 14WorkflowEditor29DescribeModelCallResponseType022_C2A3C381B62D57F59A208I9A47950B27LLO
+ _symbolic _____ 14WorkflowEditor31GenerativeExperienceCoordinatorC23CreationMetricsSnapshotV
+ _symbolic _____ 14WorkflowEditor32WFEditorTriggerBottomSpacingCell33_614F1DFEBF3DEBC915070CB296BEEF19LLC
+ _symbolic _____ 14WorkflowEditor32WFEditorTriggerBottomSpacingItem33_614F1DFEBF3DEBC915070CB296BEEF19LLC
+ _symbolic _____ 7SwiftUI17EnvironmentValuesV14WorkflowEditorE25ParameterLabelOverrideKey33_BEF3AF68E39DC04FCF61A9D593FD2516LLV
+ _symbolic _____Iegr_ 14ShortcutsAgent25DescribeAShortcutResponseV
+ _symbolic _____Sg 14ShortcutsAgent12DaSErrorCodeO
+ _symbolic _____Sg 14ShortcutsAgent16ModelCallMetricsV
+ _symbolic _____Sg 14WorkflowEditor0A8Snapshot022_C2A3C381B62D57F59A208E9A47950B27LLV
+ _symbolic _____Sg 7SwiftUI4FontV6DesignO
+ _symbolic _____SgSg 14WorkflowEditor15WFEditorTipItem33_614F1DFEBF3DEBC915070CB296BEEF19LLC
+ _symbolic _____SgXw 14WorkflowEditor15WFEditorTipCell33_614F1DFEBF3DEBC915070CB296BEEF19LLC
+ _symbolic _____SgXwz_Xx 14WorkflowEditor15ActionViewModelC
+ _symbolic _____Sg_ABt 10Foundation3URLV
+ _symbolic _____XDXMT 14WorkflowEditor15WFEditorTipCell33_614F1DFEBF3DEBC915070CB296BEEF19LLC
+ _symbolic _____Xoz_Xx 14WorkflowEditor41GenerativeExperienceOverlayViewControllerC
+ _symbolic ______p 11WorkflowKit24WFPCCQuotaCheckingActionP
+ _symbolic _____yAAyAAyAAyAAyAAy_____y_____y_____Sg___________QPGG_____y_____SgGG_____GAOG_____yAK_____GGAOGAOG 7SwiftUI15ModifiedContentV AA6HStackV AA05TupleD0V AA5ImageV AA4TextV AA6SpacerV AA30_EnvironmentKeyWritingModifierV AA5ColorV AA14_PaddingLayoutV AA026_InsettableBackgroundShapeM0V AA7CapsuleV
+ _symbolic _____yAAyAAyAAyAAy__________GACG_____y_____SgGGAFy_____SgGGAFy______pSgGG 7SwiftUI15ModifiedContentV 14WorkflowEditor23ActionResourceErrorViewV AA14_PaddingLayoutV AA30_EnvironmentKeyWritingModifierV AD0eF7OptionsC AD0eF7ResultsC So19WFUserInterfaceHostP
+ _symbolic _____yAAyAAyAAyAAy_____y_____y_____Sg___________QPGG_____y_____SgGG_____GAOG_____yAK_____GGAOG 7SwiftUI15ModifiedContentV AA6HStackV AA05TupleD0V AA5ImageV AA4TextV AA6SpacerV AA30_EnvironmentKeyWritingModifierV AA5ColorV AA14_PaddingLayoutV AA026_InsettableBackgroundShapeM0V AA7CapsuleV
+ _symbolic _____yAAyAAyAAy__________GACG_____y_____SgGGAFy_____SgGG 7SwiftUI15ModifiedContentV 14WorkflowEditor23ActionResourceErrorViewV AA14_PaddingLayoutV AA30_EnvironmentKeyWritingModifierV AD0eF7OptionsC AD0eF7ResultsC
+ _symbolic _____yAAyAAyAAy_____y_____y_____Sg___________QPGG_____y_____SgGG_____GAOG_____yAK_____GG 7SwiftUI15ModifiedContentV AA6HStackV AA05TupleD0V AA5ImageV AA4TextV AA6SpacerV AA30_EnvironmentKeyWritingModifierV AA5ColorV AA14_PaddingLayoutV AA026_InsettableBackgroundShapeM0V AA7CapsuleV
+ _symbolic _____yAAyAAyAAy_____y_____y______AAyAAy__________G_____GQPGG_____y_____SgGGAHGAHG_____yAMGG 7SwiftUI15ModifiedContentV AA6HStackV AA05TupleD0V AA5ImageV AA4TextV AA16_FlexFrameLayoutV AA08_PaddingK0V AA30_EnvironmentKeyWritingModifierV AA5ColorV AA016_BackgroundStyleP0V
+ _symbolic _____yAAyAAy__________GACG_____y_____SgGG 7SwiftUI15ModifiedContentV 14WorkflowEditor23ActionResourceErrorViewV AA14_PaddingLayoutV AA30_EnvironmentKeyWritingModifierV AD0eF7OptionsC
+ _symbolic _____yAAyAAy__________G_____yAAyAD_____yAAyAAyAAy__________G_____GACGGGGG_____G 7SwiftUI15ModifiedContentV AA4TextV AA16_FlexFrameLayoutV AA16_OverlayModifierV AA20_MaskAlignmentEffectV AA14LinearGradientV AA01_gH0V AA07_OffsetM0V AA017_AppearanceActionJ0V
+ _symbolic _____yAAyAAy__________ySSSgGGACy______pSgGGACy_____GG 7SwiftUI15ModifiedContentV 14WorkflowEditor16ParameterRowViewV AA30_EnvironmentKeyWritingModifierV So19WFUserInterfaceHostP AD0f12PresentationJ0O
+ _symbolic _____yAAyAAy_____y_____y_____Sg___________QPGG_____y_____SgGG_____GAOG 7SwiftUI15ModifiedContentV AA6HStackV AA05TupleD0V AA5ImageV AA4TextV AA6SpacerV AA30_EnvironmentKeyWritingModifierV AA5ColorV AA14_PaddingLayoutV
+ _symbolic _____yAAyAAy_____y_____y______AAyAAy__________G_____GQPGG_____y_____SgGGAHGAHG 7SwiftUI15ModifiedContentV AA6HStackV AA05TupleD0V AA5ImageV AA4TextV AA16_FlexFrameLayoutV AA08_PaddingK0V AA30_EnvironmentKeyWritingModifierV AA5ColorV
+ _symbolic _____yAAy__________G_____G 7SwiftUI15ModifiedContentV AA14LinearGradientV AA12_FrameLayoutV AA13_OffsetEffectV
+ _symbolic _____yAAy__________G_____yAAyAD_____yAAyAAyAAy__________G_____GACGGGGG 7SwiftUI15ModifiedContentV AA4TextV AA16_FlexFrameLayoutV AA16_OverlayModifierV AA20_MaskAlignmentEffectV AA14LinearGradientV AA01_gH0V AA07_OffsetM0V
+ _symbolic _____yAAy__________ySSSgGGACy______pSgGG 7SwiftUI15ModifiedContentV 14WorkflowEditor16ParameterRowViewV AA30_EnvironmentKeyWritingModifierV So19WFUserInterfaceHostP
+ _symbolic _____yAAy_____y_____y_____Sg___________QPGG_____y_____SgGG_____G 7SwiftUI15ModifiedContentV AA6HStackV AA05TupleD0V AA5ImageV AA4TextV AA6SpacerV AA30_EnvironmentKeyWritingModifierV AA5ColorV AA14_PaddingLayoutV
+ _symbolic _____yAAy_____y_____y______AAyAAy__________G_____GQPGG_____y_____SgGGAHG 7SwiftUI15ModifiedContentV AA6HStackV AA05TupleD0V AA5ImageV AA4TextV AA16_FlexFrameLayoutV AA08_PaddingK0V AA30_EnvironmentKeyWritingModifierV AA5ColorV
+ _symbolic _____ySJG s11_SetStorageC
+ _symbolic _____ySJG s23_ContiguousArrayStorageC
+ _symbolic _____ySOG s11_SetStorageC
+ _symbolic _____ySSSgG 7SwiftUI11EnvironmentV
+ _symbolic _____ySSSgG 7SwiftUI30_EnvironmentKeyWritingModifierV
+ _symbolic _____ySo16WFAccessResourceCG s11_SetStorageC
+ _symbolic _____y_So10WFWorkflowCSSSgG So8NSObjectC10FoundationE26KeyValueObservingPublisherV
+ _symbolic _____y_____G 7SwiftUI14_UIHostingViewC 14WorkflowEditor25SummarizationShimmerLabelV
+ _symbolic _____y_____G 7SwiftUI9LazyStateV 12CoreGraphics7CGFloatV
+ _symbolic _____y_____G s11_SetStorageC 14ShortcutsAgent12DaSErrorCodeO
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 14ShortcutsAgent12DaSErrorCodeO
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 14WorkflowEditor16SampleCellActionV
+ _symbolic _____y_____GSg 7SwiftUI14_UIHostingViewC 14WorkflowEditor25SummarizationShimmerLabelV
+ _symbolic _____y_____SaySSGG 10Foundation15ListFormatStyleV AA06StringD0V
+ _symbolic _____y_____SaySSG_G 10Foundation15ListFormatStyleV0B4TypeO AA06StringD0V
+ _symbolic _____y_____SaySSG_G 10Foundation15ListFormatStyleV5WidthO AA06StringD0V
+ _symbolic _____y_____SiG s17_NativeDictionaryV 14WorkflowEditor25ActionParameterIdentifier022_C2A3C381B62D57F59A208I9A47950B27LLV
+ _symbolic _____y______G 14ShortcutsAgent0B7SessionC5EventO AA017DescribeAShortcutB0V
+ _symbolic _____y______G 7SwiftUI9LazyStateV7StorageO 12CoreGraphics7CGFloatV
+ _symbolic _____y______GSg 14ShortcutsAgent0B7SessionC5EventO AA017DescribeAShortcutB0V
+ _symbolic _____y__________G 7SwiftUI15ModifiedContentV AA14LinearGradientV AA12_FrameLayoutV
+ _symbolic _____y__________ySSSgGG 7SwiftUI15ModifiedContentV 14WorkflowEditor16ParameterRowViewV AA30_EnvironmentKeyWritingModifierV
+ _symbolic _____y______y_So10WFWorkflowCSSSgGG 7Combine10PublishersO4DropV So8NSObjectC10FoundationE26KeyValueObservingPublisherV
+ _symbolic _____y______y_So10WFWorkflowCSo0A4IconCGG 7Combine10PublishersO4DropV So8NSObjectC10FoundationE26KeyValueObservingPublisherV
+ _symbolic _____y______y______y_So10WFWorkflowCSSSgGGSo17OS_dispatch_queueCG 7Combine10PublishersO9ReceiveOnV AC4DropV So8NSObjectC10FoundationE26KeyValueObservingPublisherV
+ _symbolic _____y______y______y_So10WFWorkflowCSo0A4IconCGGSo17OS_dispatch_queueCG 7Combine10PublishersO9ReceiveOnV AC4DropV So8NSObjectC10FoundationE26KeyValueObservingPublisherV
+ _symbolic _____y_____yAAyAAyAAy_____y_____y______AAyAAy__________G_____GQPGG_____y_____SgGGAHGAHG_____yAMGG_Qo_ 7SwiftUI4ViewPAAE12onTapGesture5count7performQrSi_yyctFQO AA15ModifiedContentV AA6HStackV AA05TupleJ0V AA5ImageV AA4TextV AA16_FlexFrameLayoutV AA08_PaddingQ0V AA30_EnvironmentKeyWritingModifierV AA5ColorV AA016_BackgroundStyleV0V
+ _symbolic _____y_____yAByABy__________G_____G_____GG 7SwiftUI20_MaskAlignmentEffectV AA15ModifiedContentV AA14LinearGradientV AA12_FrameLayoutV AA07_OffsetE0V AA05_FlexjK0V
+ _symbolic _____y_____yABy__________G_____yAByAByABy__________G_____GADGGGG 7SwiftUI16_OverlayModifierV AA15ModifiedContentV AA4TextV AA16_FlexFrameLayoutV AA20_MaskAlignmentEffectV AA14LinearGradientV AA01_iJ0V AA07_OffsetM0V
+ _symbolic _____y_____y_____Sg___________QPGG 7SwiftUI6HStackV AA12TupleContentV AA5ImageV AA4TextV AA6SpacerV
+ _symbolic _____y_____y______G_G ScS8IteratorV 14ShortcutsAgent0C7SessionC5EventO AC017DescribeAShortcutC0V
+ _symbolic _____y_____y___________yADy__________G_____GQPGG 7SwiftUI6HStackV AA12TupleContentV AA5ImageV AA08ModifiedE0V AA4TextV AA16_FlexFrameLayoutV AA08_PaddingK0V
+ _symbolic _____y_____y_____y_____Sg___________QPGG_____y_____SgGG 7SwiftUI15ModifiedContentV AA6HStackV AA05TupleD0V AA5ImageV AA4TextV AA6SpacerV AA30_EnvironmentKeyWritingModifierV AA5ColorV
+ _symbolic _____y_____y_____y______AAyAAy__________G_____GQPGG_____y_____SgGG 7SwiftUI15ModifiedContentV AA6HStackV AA05TupleD0V AA5ImageV AA4TextV AA16_FlexFrameLayoutV AA08_PaddingK0V AA30_EnvironmentKeyWritingModifierV AA5ColorV
+ _symbolic _____yx_____ySSSgGG 7SwiftUI15ModifiedContentV AA30_EnvironmentKeyWritingModifierV
+ _symbolic y_____c 14WorkflowEditor31GenerativeExperienceCoordinatorC
+ _type_layout_string 14WorkflowEditor0A8Snapshot022_C2A3C381B62D57F59A208E9A47950B27LLV
+ _type_layout_string 14WorkflowEditor13PCCUpsellViewV
+ _type_layout_string 14WorkflowEditor16SampleCellActionV
+ _type_layout_string 14WorkflowEditor25ActionParameterIdentifier022_C2A3C381B62D57F59A208G9A47950B27LLV
+ _type_layout_string 14WorkflowEditor31GenerativeExperienceCoordinatorC23CreationMetricsSnapshotV
- GCC_except_table1105
- GCC_except_table1113
- GCC_except_table1122
- GCC_except_table1127
- GCC_except_table1207
- GCC_except_table1563
- GCC_except_table1567
- GCC_except_table1570
- GCC_except_table1615
- GCC_except_table1624
- GCC_except_table858
- GCC_except_table867
- GCC_except_table880
- _OBJC_CLASS_$_WFLinkEntityProvidingParameter
- __CATEGORY_CLASS_PROPERTIES_WFContactFieldParameter_$_WorkflowEditor
- ___swift_closure_destructor.121Tm
- ___swift_closure_destructor.132Tm
- ___swift_closure_destructor.141Tm
- ___swift_closure_destructor.23Tm
- ___swift_closure_destructor.34Tm
- ___swift_closure_destructor.374Tm
- ___swift_closure_destructor.58Tm
- ___swift_closure_destructor.73Tm
- ___swift_closure_destructor.84Tm
- _associated conformance 14WorkflowEditor26ICloudPlusUpsellBannerViewV7SwiftUI0G0AA4BodyAdEP_AdE
- _get_witness_table 7SwiftUI15ModifiedContentVyACyACyACyAA6HStackVyAA05TupleD0VyAA5ImageV_AA4TextVAA6SpacerVACyAA4ViewPAAE11buttonStyleyQrqd__AA015PrimitiveButtonL0Rd__lFQOyACyAA0N0VyACyACyACyAkA16_FixedSizeLayoutVGAA30_EnvironmentKeyWritingModifierVyAA4FontVSgGGAXyAA5ColorVSgGGGAXyAA08AnyShapeL0VSgGG_AA017BorderedProminentnL0VQo_AXyAA0n6BorderY0VGGQPGGA5_GAA08_PaddingQ0VGA24_GAA011_BackgroundlU0VyA3_GGAaNHPA26_AaNHPA25_AaNHPA22_AaNHPA21_AaNHPyHC_A5_AA0jU0HPyHCHC_A24_AAA31_HPyHCHC_A24_AAA31_HPyHCHC_A29_AAA31_HPyHCHC
- _get_witness_table 7SwiftUI15ModifiedContentVyACyACyACyACyACyAA6HStackVyAA05TupleD0VyAA5ImageV_AA4TextVAA6SpacerVQPGGAA30_EnvironmentKeyWritingModifierVyAA5ColorVSgGGAA14_PaddingLayoutVGAXGAA026_InsettableBackgroundShapeM0VyAsA7CapsuleVGGAXGAXGAA4ViewHPA5_AAA7_HPA4_AAA7_HPAzAA7_HPAyAA7_HPAvAA7_HPAoAA7_HPyHC_AuA0uM0HPyHCHC_AxAA8_HPyHCHC_AxAA8_HPyHCHC_A3_AAA8_HPyHCHC_AxAA8_HPyHCHC_AxAA8_HPyHCHC
- _swift_willThrowTypedImpl
- _symbolic _____ 14WorkflowEditor26ICloudPlusUpsellBannerViewV
- _symbolic _____yAAyAAyAAyAAyAAy_____y_____y________________QPGG_____y_____SgGG_____GANG_____yAJ_____GGANGANG 7SwiftUI15ModifiedContentV AA6HStackV AA05TupleD0V AA5ImageV AA4TextV AA6SpacerV AA30_EnvironmentKeyWritingModifierV AA5ColorV AA14_PaddingLayoutV AA026_InsettableBackgroundShapeM0V AA7CapsuleV
- _symbolic _____yAAyAAyAAyAAy_____y_____y________________QPGG_____y_____SgGG_____GANG_____yAJ_____GGANG 7SwiftUI15ModifiedContentV AA6HStackV AA05TupleD0V AA5ImageV AA4TextV AA6SpacerV AA30_EnvironmentKeyWritingModifierV AA5ColorV AA14_PaddingLayoutV AA026_InsettableBackgroundShapeM0V AA7CapsuleV
- _symbolic _____yAAyAAyAAy_____y_____y________________AAy_____yAAy_____yAAyAAyAAyAE_____G_____y_____SgGGAJy_____SgGGGAJy_____SgGG______Qo_AJy_____GGQPGGAQG_____GA4_G_____yAOGG 7SwiftUI15ModifiedContentV AA6HStackV AA05TupleD0V AA5ImageV AA4TextV AA6SpacerV AA4ViewPAAE11buttonStyleyQrqd__AA015PrimitiveButtonL0Rd__lFQO AA0N0V AA16_FixedSizeLayoutV AA30_EnvironmentKeyWritingModifierV AA4FontV AA5ColorV AA08AnyShapeL0V AA017BorderedProminentnL0V AA0n6BorderY0V AA08_PaddingQ0V AA011_BackgroundlU0V
- _symbolic _____yAAyAAyAAy_____y_____y________________QPGG_____y_____SgGG_____GANG_____yAJ_____GG 7SwiftUI15ModifiedContentV AA6HStackV AA05TupleD0V AA5ImageV AA4TextV AA6SpacerV AA30_EnvironmentKeyWritingModifierV AA5ColorV AA14_PaddingLayoutV AA026_InsettableBackgroundShapeM0V AA7CapsuleV
- _symbolic _____yAAyAAy_____y_____y________________QPGG_____y_____SgGG_____GANG 7SwiftUI15ModifiedContentV AA6HStackV AA05TupleD0V AA5ImageV AA4TextV AA6SpacerV AA30_EnvironmentKeyWritingModifierV AA5ColorV AA14_PaddingLayoutV
- _symbolic _____yAAy__________y______pSgGGACy_____GG 7SwiftUI15ModifiedContentV 14WorkflowEditor16ParameterRowViewV AA30_EnvironmentKeyWritingModifierV So19WFUserInterfaceHostP AD0f12PresentationJ0O
- _symbolic _____yAAy_____y_____y________________QPGG_____y_____SgGG_____G 7SwiftUI15ModifiedContentV AA6HStackV AA05TupleD0V AA5ImageV AA4TextV AA6SpacerV AA30_EnvironmentKeyWritingModifierV AA5ColorV AA14_PaddingLayoutV
- _symbolic _____y__________y______pSgGG 7SwiftUI15ModifiedContentV 14WorkflowEditor16ParameterRowViewV AA30_EnvironmentKeyWritingModifierV So19WFUserInterfaceHostP
- _symbolic _____y______y_So10WFWorkflowCSo0A4IconCGSo17OS_dispatch_queueCG 7Combine10PublishersO9ReceiveOnV So8NSObjectC10FoundationE26KeyValueObservingPublisherV
- _symbolic _____y_____y________________QPGG 7SwiftUI6HStackV AA12TupleContentV AA5ImageV AA4TextV AA6SpacerV
- _symbolic _____y_____y_____y________________QPGG_____y_____SgGG 7SwiftUI15ModifiedContentV AA6HStackV AA05TupleD0V AA5ImageV AA4TextV AA6SpacerV AA30_EnvironmentKeyWritingModifierV AA5ColorV
CStrings:
+ "%s Unable to create CNComposeRecipient in AddContactRecipientButtonHandler %@"
+ ", suggestedQuery: "
+ "-[AddContactRecipientButtonHandler contactPicker:didSelectContact:]"
+ "Browse actions and edit your shortcut. To choose your default view, open %@."
+ "Configure %@ to enable this automation."
+ "Configure this automation."
+ "Disambiguation: Entity"
+ "Disambiguation: Multi-Select"
+ "Disambiguation: System Picker"
+ "Disambiguation: Text"
+ "EditorAnimation-Dark-Pad"
+ "EditorAnimation-Dark-Phone"
+ "EditorAnimation-Light-Pad"
+ "EditorAnimation-Light-Phone"
+ "Finding “%@”…"
+ "Initial State"
+ "Not requesting summarization, since it is not eligible or already populated."
+ "Optional<String>"
+ "Other"
+ "Presenting usage limits KB article from action view"
+ "Settings"
+ "Shortcut Summary"
+ "Shortcut Summary with Steps"
+ "Shortcuts Editor"
+ "Shortcuts doesn’t have access to your contacts."
+ "Show Example Cell"
+ "Show Example Session"
+ "Summarizing shortcut…"
+ "Text Response"
+ "Thinking State"
+ "TriggerBottomSpacingCell"
+ "TriggerSeparatorCell"
+ "User Request"
+ "WorkflowEditor.WFEditorTipItem"
+ "WorkflowEditor.WFEditorTriggerBottomSpacingItem"
+ "WorkflowEditor.WFEditorTriggerSeparatorItem"
+ "You’re approaching your daily Apple Intelligence limit for Shortcuts."
+ "You’ve reached your daily limit for requests to the Cloud Pro model. Using the Cloud Pro model in Shortcuts will be limited for up to 24 hours."
+ "You’ve reached your daily limit for requests to the cloud model. Sign in to iCloud to get more requests."
+ "You’ve reached your daily limit for requests to the cloud model. Upgrade to iCloud+ to get more requests."
+ "You’ve reached your daily limit for requests to the cloud model. Using the cloud model in Shortcuts will be limited for up to 24 hours."
+ "key IN %@"
+ "or"
+ "phoneNumbers.@count + emailAddresses.@count == 1"
+ "rectangle.on.rectangle"
+ "shortcuts-editor-tip://settings"
- "Automation is invalid"
- "Finding “%@“…"
- "Shortcuts doesn't have access to your contacts."
- "Upgrade"
- "You've reached your daily limit for requests to the Cloud Pro model. Using the Cloud Pro model in Shortcuts will be limited for up to 24 hours."
- "You've reached your daily limit for requests to the cloud model. Sign in to iCloud to get more requests."
- "You've reached your daily limit for requests to the cloud model. Upgrade to iCloud+ to get more requests."
- "You've reached your daily limit for requests to the cloud model. Using the cloud model in Shortcuts will be limited for up to 24 hours."
```
