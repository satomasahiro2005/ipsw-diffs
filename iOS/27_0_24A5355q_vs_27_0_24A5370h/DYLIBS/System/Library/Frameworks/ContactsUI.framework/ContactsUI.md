## ContactsUI

> `/System/Library/Frameworks/ContactsUI.framework/ContactsUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x384280` | `0x385678` | **`+0x13f8`** |
| `__AUTH_CONST.__objc_const` | `0x592d0` | `0x594f8` | **`+0x228`** |
| `__TEXT.__objc_methlist` | `0x39324` | `0x394bc` | **`+0x198`** |
| `__DATA_CONST.__objc_selrefs` | `0x184b0` | `0x18558` | **`+0xa8`** |
| `__DATA.__data` | `0xac98` | `0xace8` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0xdc58` | `0xdca8` | **`+0x50`** |
| `__TEXT.__swift5_capture` | `0x1510` | `0x1550` | **`+0x40`** |
| `__TEXT.__constg_swiftt` | `0x55e0` | `0x55a8` | **`-0x38`** |
| `__AUTH.__objc_data` | `0xfc90` | `0xfc68` | **`-0x28`** |
| `__DATA.__objc_ivar` | `0x3c30` | `0x3c54` | **`+0x24`** |
| `__TEXT.__cstring` | `0x138c5` | `0x138e7` | **`+0x22`** |
| `__AUTH_CONST.__cfstring` | `0xba20` | `0xba40` | **`+0x20`** |
| `__TEXT.__const` | `0xc420` | `0xc440` | **`+0x20`** |
| `__TEXT.__swift5_fieldmd` | `0x3580` | `0x3598` | **`+0x18`** |
| `__TEXT.__swift5_reflstr` | `0x38c1` | `0x38d1` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `0xefb2` | `0xefc2` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x28f0` | `0x28f8` | **`+0x8`** |

### Other Changes

```diff

-1450.100.6.0.0
+1452.100.5.0.0

-  Functions: 24319
-  Symbols:   34074
+  Functions: 24361
+  Symbols:   34117
Symbols:
+ -[CNContactContentContainerViewController setPreservesExternalNavigationItems:]
+ -[CNContactContentDisplayViewController preservesExternalNavigationItems]
+ -[CNContactContentDisplayViewController setPreservesExternalNavigationItems:]
+ -[CNContactContentEditViewController preservesExternalNavigationItems]
+ -[CNContactContentEditViewController setPreservesExternalNavigationItems:]
+ -[CNContactContentNavigationItemUpdater preservesExternalNavigationItems]
+ -[CNContactContentNavigationItemUpdater setPreservesExternalNavigationItems:]
+ -[CNContactContentUnitaryViewController appearanceFromAppearance:withOverrideStyle:]
+ -[CNContactContentUnitaryViewController setPreservesExternalNavigationItems:]
+ -[CNContactContentUnitaryViewController updateBarButtonItemsAppearanceForEditingState]
+ -[CNContactContentViewController preservesExternalNavigationItems]
+ -[CNContactContentViewController setPreservesExternalNavigationItems:]
+ -[CNContactInlineActionsViewController isInContactCard]
+ -[CNContactInlineActionsViewController setIsInContactCard:]
+ -[CNContactPhotoView initialThreeDTouchEnabled]
+ -[CNContactPhotoView setInitialThreeDTouchEnabled:]
+ -[CNContactViewController preservesExternalNavigationItems]
+ -[CNContactViewController setPreservesExternalNavigationItems:]
+ -[CNSharedLayout preservesExternalNavigationItems]
+ -[CNSharedLayout setPreservesExternalNavigationItems:]
+ -[CNStarkContactPropertyCell updateConfigurationUsingState:]
+ -[CNUINavigationListViewCell updateConfigurationUsingState:]
+ -[CNVisualIdentityItemEditorViewController avatarViewTopMargin]
+ -[CNVisualIdentityItemEditorViewController didTapBackground:]
+ -[CNVisualIdentityItemEditorViewController gestureRecognizer:shouldReceiveTouch:]
+ -[CNVisualIdentityItemEditorViewController isCompactHeightWithEnhancedLandscape]
+ -[CNVisualIdentityItemEditorViewController navBarTapGesture]
+ -[CNVisualIdentityItemEditorViewController setNavBarTapGesture:]
+ -[CNVisualIdentityItemEditorViewController traitCollectionDidChange:]
+ -[CNVisualIdentityItemEditorViewController updateAvatarConstraintsForCurrentTraits]
+ -[CNVisualIdentityItemEditorViewController viewWillDisappear:]
+ GCC_except_table10130
+ GCC_except_table10136
+ GCC_except_table10358
+ GCC_except_table10559
+ GCC_except_table10573
+ GCC_except_table10587
+ GCC_except_table10843
+ GCC_except_table10845
+ GCC_except_table10914
+ GCC_except_table10915
+ GCC_except_table10916
+ GCC_except_table10931
+ GCC_except_table11213
+ GCC_except_table11219
+ GCC_except_table11271
+ GCC_except_table11275
+ GCC_except_table1144
+ GCC_except_table1146
+ GCC_except_table11480
+ GCC_except_table11667
+ GCC_except_table11672
+ GCC_except_table11675
+ GCC_except_table11685
+ GCC_except_table11687
+ GCC_except_table11688
+ GCC_except_table11698
+ GCC_except_table11712
+ GCC_except_table11732
+ GCC_except_table11737
+ GCC_except_table11795
+ GCC_except_table11907
+ GCC_except_table1194
+ GCC_except_table12001
+ GCC_except_table12028
+ GCC_except_table1206
+ GCC_except_table12147
+ GCC_except_table12209
+ GCC_except_table12271
+ GCC_except_table12272
+ GCC_except_table12282
+ GCC_except_table12283
+ GCC_except_table1238
+ GCC_except_table12710
+ GCC_except_table12727
+ GCC_except_table12748
+ GCC_except_table13046
+ GCC_except_table13080
+ GCC_except_table13183
+ GCC_except_table13380
+ GCC_except_table13448
+ GCC_except_table13454
+ GCC_except_table13528
+ GCC_except_table13529
+ GCC_except_table13537
+ GCC_except_table13617
+ GCC_except_table13622
+ GCC_except_table13795
+ GCC_except_table13814
+ GCC_except_table13963
+ GCC_except_table13992
+ GCC_except_table13993
+ GCC_except_table14127
+ GCC_except_table14214
+ GCC_except_table14221
+ GCC_except_table14258
+ GCC_except_table14514
+ GCC_except_table14517
+ GCC_except_table14623
+ GCC_except_table14642
+ GCC_except_table14909
+ GCC_except_table14984
+ GCC_except_table15105
+ GCC_except_table15109
+ GCC_except_table15183
+ GCC_except_table15249
+ GCC_except_table15263
+ GCC_except_table15282
+ GCC_except_table15284
+ GCC_except_table15453
+ GCC_except_table15554
+ GCC_except_table15634
+ GCC_except_table15638
+ GCC_except_table1565
+ GCC_except_table15656
+ GCC_except_table15706
+ GCC_except_table15829
+ GCC_except_table16135
+ GCC_except_table16150
+ GCC_except_table16166
+ GCC_except_table16180
+ GCC_except_table16184
+ GCC_except_table16185
+ GCC_except_table16205
+ GCC_except_table16281
+ GCC_except_table1629
+ GCC_except_table1634
+ GCC_except_table1638
+ GCC_except_table16670
+ GCC_except_table16672
+ GCC_except_table16681
+ GCC_except_table16776
+ GCC_except_table16839
+ GCC_except_table16879
+ GCC_except_table17009
+ GCC_except_table17288
+ GCC_except_table17292
+ GCC_except_table17770
+ GCC_except_table17788
+ GCC_except_table17840
+ GCC_except_table17879
+ GCC_except_table17896
+ GCC_except_table17916
+ GCC_except_table17938
+ GCC_except_table17952
+ GCC_except_table17955
+ GCC_except_table17957
+ GCC_except_table17964
+ GCC_except_table17965
+ GCC_except_table17990
+ GCC_except_table18117
+ GCC_except_table18127
+ GCC_except_table18143
+ GCC_except_table18147
+ GCC_except_table18151
+ GCC_except_table18153
+ GCC_except_table18199
+ GCC_except_table1825
+ GCC_except_table18410
+ GCC_except_table18467
+ GCC_except_table18468
+ GCC_except_table18475
+ GCC_except_table18480
+ GCC_except_table18485
+ GCC_except_table18494
+ GCC_except_table18497
+ GCC_except_table18522
+ GCC_except_table18544
+ GCC_except_table18562
+ GCC_except_table18563
+ GCC_except_table18574
+ GCC_except_table18581
+ GCC_except_table18582
+ GCC_except_table18585
+ GCC_except_table18587
+ GCC_except_table18589
+ GCC_except_table18602
+ GCC_except_table18743
+ GCC_except_table1879
+ GCC_except_table2102
+ GCC_except_table2185
+ GCC_except_table2888
+ GCC_except_table2954
+ GCC_except_table3032
+ GCC_except_table3033
+ GCC_except_table3034
+ GCC_except_table3149
+ GCC_except_table3279
+ GCC_except_table3451
+ GCC_except_table3453
+ GCC_except_table3586
+ GCC_except_table3588
+ GCC_except_table3666
+ GCC_except_table3783
+ GCC_except_table4000
+ GCC_except_table4001
+ GCC_except_table4172
+ GCC_except_table4214
+ GCC_except_table4248
+ GCC_except_table4368
+ GCC_except_table4458
+ GCC_except_table4732
+ GCC_except_table4736
+ GCC_except_table4817
+ GCC_except_table4978
+ GCC_except_table5019
+ GCC_except_table5093
+ GCC_except_table5094
+ GCC_except_table5100
+ GCC_except_table5102
+ GCC_except_table5157
+ GCC_except_table5177
+ GCC_except_table5218
+ GCC_except_table5225
+ GCC_except_table5226
+ GCC_except_table5290
+ GCC_except_table5294
+ GCC_except_table5438
+ GCC_except_table5815
+ GCC_except_table5824
+ GCC_except_table5915
+ GCC_except_table5943
+ GCC_except_table5951
+ GCC_except_table6066
+ GCC_except_table6239
+ GCC_except_table6385
+ GCC_except_table6401
+ GCC_except_table6701
+ GCC_except_table6740
+ GCC_except_table6813
+ GCC_except_table6992
+ GCC_except_table6997
+ GCC_except_table7128
+ GCC_except_table7204
+ GCC_except_table7348
+ GCC_except_table7605
+ GCC_except_table7703
+ GCC_except_table8104
+ GCC_except_table8161
+ GCC_except_table8195
+ GCC_except_table8246
+ GCC_except_table8317
+ GCC_except_table8361
+ GCC_except_table8742
+ GCC_except_table8785
+ GCC_except_table8850
+ GCC_except_table8856
+ GCC_except_table9024
+ GCC_except_table9059
+ GCC_except_table9099
+ GCC_except_table9123
+ GCC_except_table9188
+ GCC_except_table9315
+ GCC_except_table9319
+ GCC_except_table9445
+ GCC_except_table9446
+ GCC_except_table9452
+ GCC_except_table9462
+ GCC_except_table9465
+ GCC_except_table9470
+ GCC_except_table9480
+ GCC_except_table9483
+ GCC_except_table9497
+ GCC_except_table9503
+ GCC_except_table9506
+ GCC_except_table9509
+ GCC_except_table9511
+ GCC_except_table9717
+ GCC_except_table9725
+ GCC_except_table9800
+ GCC_except_table9803
+ GCC_except_table9898
+ GCC_except_table9936
+ GCC_except_table9951
+ GCC_except_table9956
+ _OBJC_IVAR_$_CNContactContentDisplayViewController._preservesExternalNavigationItems
+ _OBJC_IVAR_$_CNContactContentEditViewController._preservesExternalNavigationItems
+ _OBJC_IVAR_$_CNContactContentNavigationItemUpdater._preservesExternalNavigationItems
+ _OBJC_IVAR_$_CNContactContentViewController._preservesExternalNavigationItems
+ _OBJC_IVAR_$_CNContactInlineActionsViewController._isInContactCard
+ _OBJC_IVAR_$_CNContactPhotoView._initialThreeDTouchEnabled
+ _OBJC_IVAR_$_CNContactViewController._preservesExternalNavigationItems
+ _OBJC_IVAR_$_CNSharedLayout._preservesExternalNavigationItems
+ _OBJC_IVAR_$_CNVisualIdentityItemEditorViewController._navBarTapGesture
+ _OBJC_METACLASS_$__TtC10ContactsUIP33_324309E58E9A0668A8E269CFEC6C38C233SharedProfileScrollRevealObserver
+ __DATA__TtC10ContactsUIP33_324309E58E9A0668A8E269CFEC6C38C233SharedProfileScrollRevealObserver
+ __INSTANCE_METHODS__TtC10ContactsUIP33_324309E58E9A0668A8E269CFEC6C38C233SharedProfileScrollRevealObserver
+ __IVARS__TtC10ContactsUIP33_324309E58E9A0668A8E269CFEC6C38C233SharedProfileScrollRevealObserver
+ __METACLASS_DATA__TtC10ContactsUIP33_324309E58E9A0668A8E269CFEC6C38C233SharedProfileScrollRevealObserver
+ __PROTOCOLS__TtC10ContactsUIP33_324309E58E9A0668A8E269CFEC6C38C233SharedProfileScrollRevealObserver
+ ___95-[CNVisualIdentityItemEditorViewController viewWillTransitionToSize:withTransitionCoordinator:]_block_invoke
+ ___unnamed_8
+ _symbolic Sbyc
+ _symbolic _____ 10ContactsUI33SharedProfileScrollRevealObserver33_324309E58E9A0668A8E269CFEC6C38C2LLC
+ _symbolic y_____cSg 12CoreGraphics7CGFloatV
- GCC_except_table10108
- GCC_except_table10114
- GCC_except_table10336
- GCC_except_table10537
- GCC_except_table10551
- GCC_except_table10565
- GCC_except_table10821
- GCC_except_table10823
- GCC_except_table10892
- GCC_except_table10893
- GCC_except_table10894
- GCC_except_table10909
- GCC_except_table11191
- GCC_except_table11197
- GCC_except_table11249
- GCC_except_table11253
- GCC_except_table1143
- GCC_except_table1145
- GCC_except_table11458
- GCC_except_table11645
- GCC_except_table11650
- GCC_except_table11653
- GCC_except_table11663
- GCC_except_table11665
- GCC_except_table11666
- GCC_except_table11676
- GCC_except_table11690
- GCC_except_table11710
- GCC_except_table11715
- GCC_except_table11773
- GCC_except_table11885
- GCC_except_table1193
- GCC_except_table11979
- GCC_except_table12006
- GCC_except_table1205
- GCC_except_table12125
- GCC_except_table12187
- GCC_except_table12249
- GCC_except_table12250
- GCC_except_table12260
- GCC_except_table12261
- GCC_except_table1237
- GCC_except_table12688
- GCC_except_table12705
- GCC_except_table12726
- GCC_except_table13024
- GCC_except_table13058
- GCC_except_table13161
- GCC_except_table13358
- GCC_except_table13426
- GCC_except_table13432
- GCC_except_table13506
- GCC_except_table13507
- GCC_except_table13515
- GCC_except_table13595
- GCC_except_table13600
- GCC_except_table13773
- GCC_except_table13792
- GCC_except_table13941
- GCC_except_table13970
- GCC_except_table13971
- GCC_except_table14105
- GCC_except_table14191
- GCC_except_table14198
- GCC_except_table14235
- GCC_except_table14491
- GCC_except_table14494
- GCC_except_table14600
- GCC_except_table14619
- GCC_except_table14885
- GCC_except_table14959
- GCC_except_table15080
- GCC_except_table15084
- GCC_except_table15158
- GCC_except_table15224
- GCC_except_table15232
- GCC_except_table15234
- GCC_except_table15238
- GCC_except_table15428
- GCC_except_table15529
- GCC_except_table15609
- GCC_except_table15613
- GCC_except_table15631
- GCC_except_table1564
- GCC_except_table15681
- GCC_except_table15804
- GCC_except_table16109
- GCC_except_table16124
- GCC_except_table16140
- GCC_except_table16153
- GCC_except_table16154
- GCC_except_table16158
- GCC_except_table16159
- GCC_except_table16255
- GCC_except_table1628
- GCC_except_table1633
- GCC_except_table1637
- GCC_except_table16643
- GCC_except_table16645
- GCC_except_table16654
- GCC_except_table16749
- GCC_except_table16812
- GCC_except_table16852
- GCC_except_table16982
- GCC_except_table17259
- GCC_except_table17263
- GCC_except_table17741
- GCC_except_table17759
- GCC_except_table17811
- GCC_except_table17821
- GCC_except_table17867
- GCC_except_table17887
- GCC_except_table17909
- GCC_except_table17923
- GCC_except_table17926
- GCC_except_table17928
- GCC_except_table17935
- GCC_except_table17936
- GCC_except_table17961
- GCC_except_table18088
- GCC_except_table18098
- GCC_except_table18114
- GCC_except_table18118
- GCC_except_table18122
- GCC_except_table18124
- GCC_except_table18170
- GCC_except_table1824
- GCC_except_table18378
- GCC_except_table18435
- GCC_except_table18436
- GCC_except_table18443
- GCC_except_table18448
- GCC_except_table18453
- GCC_except_table18462
- GCC_except_table18465
- GCC_except_table18490
- GCC_except_table18498
- GCC_except_table18512
- GCC_except_table18531
- GCC_except_table18542
- GCC_except_table18549
- GCC_except_table18550
- GCC_except_table18553
- GCC_except_table18555
- GCC_except_table18557
- GCC_except_table18570
- GCC_except_table18711
- GCC_except_table1878
- GCC_except_table2101
- GCC_except_table2184
- GCC_except_table2885
- GCC_except_table2951
- GCC_except_table3029
- GCC_except_table3030
- GCC_except_table3031
- GCC_except_table3146
- GCC_except_table3276
- GCC_except_table3448
- GCC_except_table3450
- GCC_except_table3583
- GCC_except_table3585
- GCC_except_table3663
- GCC_except_table3780
- GCC_except_table3995
- GCC_except_table3996
- GCC_except_table4167
- GCC_except_table4209
- GCC_except_table4243
- GCC_except_table4362
- GCC_except_table4452
- GCC_except_table4724
- GCC_except_table4728
- GCC_except_table4797
- GCC_except_table4968
- GCC_except_table5009
- GCC_except_table5083
- GCC_except_table5084
- GCC_except_table5090
- GCC_except_table5092
- GCC_except_table5147
- GCC_except_table5167
- GCC_except_table5208
- GCC_except_table5215
- GCC_except_table5216
- GCC_except_table5280
- GCC_except_table5284
- GCC_except_table5428
- GCC_except_table5795
- GCC_except_table5804
- GCC_except_table5895
- GCC_except_table5923
- GCC_except_table5931
- GCC_except_table6046
- GCC_except_table6219
- GCC_except_table6365
- GCC_except_table6381
- GCC_except_table6680
- GCC_except_table6719
- GCC_except_table6792
- GCC_except_table6970
- GCC_except_table6975
- GCC_except_table7106
- GCC_except_table7182
- GCC_except_table7326
- GCC_except_table7583
- GCC_except_table7681
- GCC_except_table8082
- GCC_except_table8139
- GCC_except_table8173
- GCC_except_table8224
- GCC_except_table8295
- GCC_except_table8339
- GCC_except_table8720
- GCC_except_table8763
- GCC_except_table8828
- GCC_except_table8834
- GCC_except_table9002
- GCC_except_table9037
- GCC_except_table9077
- GCC_except_table9101
- GCC_except_table9166
- GCC_except_table9293
- GCC_except_table9297
- GCC_except_table9423
- GCC_except_table9424
- GCC_except_table9430
- GCC_except_table9436
- GCC_except_table9440
- GCC_except_table9443
- GCC_except_table9448
- GCC_except_table9461
- GCC_except_table9475
- GCC_except_table9481
- GCC_except_table9484
- GCC_except_table9487
- GCC_except_table9489
- GCC_except_table9695
- GCC_except_table9703
- GCC_except_table9778
- GCC_except_table9781
- GCC_except_table9876
- GCC_except_table9914
- GCC_except_table9929
- GCC_except_table9934
- _OBJC_METACLASS_$__TtCE10ContactsUICSo37CNUISharedProfileNavigationBarPaletteP33_324309E58E9A0668A8E269CFEC6C38C214ScrollObserver
- __DATA__TtCE10ContactsUICSo37CNUISharedProfileNavigationBarPaletteP33_324309E58E9A0668A8E269CFEC6C38C214ScrollObserver
- __INSTANCE_METHODS__TtCE10ContactsUICSo37CNUISharedProfileNavigationBarPaletteP33_324309E58E9A0668A8E269CFEC6C38C214ScrollObserver
- __IVARS__TtCE10ContactsUICSo37CNUISharedProfileNavigationBarPaletteP33_324309E58E9A0668A8E269CFEC6C38C214ScrollObserver
- __METACLASS_DATA__TtCE10ContactsUICSo37CNUISharedProfileNavigationBarPaletteP33_324309E58E9A0668A8E269CFEC6C38C214ScrollObserver
- __PROTOCOLS__TtCE10ContactsUICSo37CNUISharedProfileNavigationBarPaletteP33_324309E58E9A0668A8E269CFEC6C38C214ScrollObserver
- ___unnamed_4
- _symbolic _____ So37CNUISharedProfileNavigationBarPaletteC10ContactsUIE14ScrollObserver33_324309E58E9A0668A8E269CFEC6C38C2LLC
CStrings:
+ "BlockedContactCell"
+ "ContactsUI.SharedProfileScrollRevealObserver"
+ "R\xb1"
- "+"
- "B\xb1"
- "ContactsUI.ScrollObserver"
```
