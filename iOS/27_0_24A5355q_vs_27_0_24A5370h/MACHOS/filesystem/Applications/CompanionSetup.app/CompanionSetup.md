## CompanionSetup

> `/Applications/CompanionSetup.app/CompanionSetup`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8fc30` | `0x9ff3c` | **`+0x1030c`** |
| `__DATA_CONST.__const` | `0x6518` | `0x8428` | **`+0x1f10`** |
| `__TEXT.__swift5_capture` | `0x2674` | `0x3118` | **`+0xaa4`** |
| `__TEXT.__swift5_typeref` | `0x15ca` | `0x18d6` | **`+0x30c`** |
| `__TEXT.__eh_frame` | `0x42a0` | `0x4570` | **`+0x2d0`** |
| `__DATA.__bss` | `0x2380` | `0x2500` | **`+0x180`** |
| `__DATA.__objc_data` | `0x2100` | `0x1fe8` | **`-0x118`** |
| `__TEXT.__const` | `0x3584` | `0x3694` | **`+0x110`** |
| `__TEXT.__unwind_info` | `0x1e88` | `0x1f78` | **`+0xf0`** |
| `__TEXT.__auth_stubs` | `0x26c0` | `0x27a0` | **`+0xe0`** |
| `__TEXT.__objc_methname` | `0x4b3d` | `0x4c0d` | **`+0xd0`** |
| `__TEXT.__swift5_reflstr` | `0x15b4` | `0x1654` | **`+0xa0`** |
| `__DATA_CONST.__auth_got` | `0x1368` | `0x13d8` | **`+0x70`** |
| `__TEXT.__cstring` | `0x3b2a` | `0x3b9a` | **`+0x70`** |
| `__TEXT.__oslogstring` | `0x14f3` | `0x1553` | **`+0x60`** |
| `__TEXT.__objc_classname` | `0x6ee` | `0x6ae` | **`-0x40`** |
| `__TEXT.__constg_swiftt` | `0x178c` | `0x17c8` | **`+0x3c`** |
| `__DATA.__data` | `0x2130` | `0x2160` | **`+0x30`** |
| `__DATA.__objc_const` | `0x1d18` | `0x1ce8` | **`-0x30`** |
| `__TEXT.__objc_methlist` | `0x127c` | `0x124c` | **`-0x30`** |
| `__DATA_CONST.__got` | `0xd40` | `0xd68` | **`+0x28`** |
| `__TEXT.__swift_as_cont` | `0x43c` | `0x464` | **`+0x28`** |
| `__TEXT.__objc_stubs` | `0x2900` | `0x2920` | **`+0x20`** |
| `__TEXT.__swift5_assocty` | `0x258` | `0x270` | **`+0x18`** |
| `__DATA_CONST.__auth_ptr` | `0x740` | `0x750` | **`+0x10`** |
| `__TEXT.__objc_methtype` | `0x1bfb` | `0x1c0b` | **`+0x10`** |
| `__TEXT.__swift5_proto` | `0x194` | `0x1a0` | **`+0xc`** |
| `__TEXT.__swift_as_entry` | `0x180` | `0x18c` | **`+0xc`** |
| `__DATA.__objc_selrefs` | `0x1200` | `0x1208` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0xb0` | `0xa8` | **`-0x8`** |
| `__TEXT.__swift_as_ret` | `0x188` | `0x190` | **`+0x8`** |
| `__TEXT.__swift5_fieldmd` | `0x12cc` | `0x12c8` | **`-0x4`** |
| `__TEXT.__swift5_types` | `0x100` | `0x104` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_stublist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`

### Other Changes

```diff

-520.0.0.0.0
+524.0.16.0.0

-  Functions: 2215
-  Symbols:   1236
-  CStrings:  1390
+  Functions: 2446
+  Symbols:   1258
+  CStrings:  1402
Symbols:
+ _$s14AppleIDSetupUI15ProxCardContentV5title5image11productTypeACSS_So7UIImageCSSSgtcfC
+ _$s14AppleIDSetupUI15ProxCardContentVMa
+ _$s14AppleIDSetupUI15ProxCardContentVMn
+ _$s14AppleIDSetupUI19SetupViewControllerC21dontSuggestUserAction04skipJ017shouldAutoDismiss22isPreEstablishedClient15proxCardContent14contextBuilder13reportHandlerACSo8UIActionCSg_AMS2bAA04ProxtU0VSg0aB00D7ContextV0W0VAUncys6ResultOyAQ0D6ReportVs5Error_pGctcfc
+ _$s17CompanionSetupKit011CSKStepHomeC14ChooseRoomInfoV19homeWasAutoselectedSbvg
+ _$s17CompanionSetupKit011CSKStepHomecB6ClientC5EventO12chooseRoomExyAESayAA0decI0VG_AHSgS2btcAEmFWC
+ _$s17CompanionSetupKit21CSKSetupAppleTVClientC13ConfigurationV19skipPreConnectStepsSbvs
+ _$s17CompanionSetupKit21CSKSetupAppleTVClientC17flowRestartNeededSbvg
+ _$s17CompanionSetupKit21CSKSetupAppleTVClientC7CommandO8osUpdateyAeA21CSKStepOSUpdateClientCADOcAEmFWC
+ _$s17CompanionSetupKit21CSKSetupAppleTVClientC7UIStateC5PhaseO11osUpdateAskyAgA15CSKOSUpdateInfoVcAGmFWC
+ _$s17CompanionSetupKit21CSKSetupAppleTVClientC7UIStateC5PhaseO8osUpdateyAgA19CSKOSUpdateProgressVcAGmFWC
+ _$s17CompanionSetupKit21CSKSetupAppleTVClientCScAAAMc
+ _$s22UniformTypeIdentifiers15UTHardwareColorOMa
+ _$s22UniformTypeIdentifiers15UTHardwareColorOMn
+ _$s22UniformTypeIdentifiers6UTTypeV10identifierSSvg
+ _$s22UniformTypeIdentifiers6UTTypeV16_deviceModelCode14enclosureColorACSgSS_AA010UTHardwareI0OSgtcfC
+ _$s22UniformTypeIdentifiers6UTTypeVMa
+ _$s22UniformTypeIdentifiers6UTTypeVMn
+ _$s5UIKit15UIMutableTraitsPy5ValueQyd__qd__mcAA17UITraitDefinitionRd__SYAERQSiAD_03RawD0RTd__luigTj
+ _$sSS9hasPrefixySbSSF
+ _$ss10_HashTableV12previousHole6beforeAB6BucketVAF_tF
+ _MobileGestalt_copy_productType_obj
+ _OBJC_CLASS_$_ISSymbol
+ _objc_retain_x10
+ _swift_bridgeObjectRetain_n
+ _swift_unknownObjectWeakAssign
- _$s14AppleIDSetupUI19SetupViewControllerC21dontSuggestUserAction04skipJ017shouldAutoDismiss22isPreEstablishedClient14contextBuilder13reportHandlerACSo8UIActionCSg_ALS2b0aB00D7ContextV0T0VAQncys6ResultOyAM0D6ReportVs5Error_pGctcfc
- _$s17CompanionSetupKit9CSKClientC7CommandO13speakPasscodeyA2EmFWC
- _$ss12_ArrayBufferV20_consumeAndCreateNew14bufferIsUnique15minimumCapacity13growForAppendAByxGSb_SiSbtFyXl_Ts5
- _swift_isUniquelyReferenced_nonNull_bridgeObject
CStrings:
+ "ERROR_ADD_USER_SUBTITLE_ICLOUD_ACCOUNT_MISMATCH"
+ "ERROR_PRIMARY_ACTION_TITLE_GO_TO_SETTINGS"
+ "ERROR_PRIMARY_ACTION_TITLE_UPDATE"
+ "ERROR_PRIMARY_ACTION_TITLE_WIFI_SETTINGS"
+ "ERROR_TITLE_ICLOUD_ACCOUNT_MISMATCH"
+ "Error: iCloud Account Mismatch"
+ "ICLOUD_FOR_HOME_BUTTON"
+ "ICLOUD_FOR_SIRI_BUTTON"
+ "Restarting setup flow"
+ "SOFTWARE_UPDATE_STARTED_DETAIL_APPLE_TV"
+ "backHandler"
+ "bodyLabel"
+ "erroriCloudAccountMismatch"
+ "getCGImageForImageDescriptor:completion:"
+ "iCloud Account Mismatch"
+ "imageStackView"
+ "initWithCGImage:scale:orientation:"
+ "invalidate()"
+ "name"
+ "person.crop.circle.badge.exclamationmark"
+ "resolvedDisclaimerAction"
+ "setDisplayDeviceType:"
+ "showRoomPicker rooms=%s, showsBackButton = %{bool}d, homeWasAutoselected = %{bool}d"
+ "startFlow: restart=%{bool}d"
+ "symbolForTypeIdentifier:withResolutionStrategy:variantOptions:error:"
+ "systemYellowColor"
+ "v16@?0^{CGImage=}8"
- "CGImage"
- "CompanionSetup.DisclaimerContentViewController"
- "CompanionSetup/DisclaimerContentViewController.swift"
- "ERROR_PRIMARY_ACTION_TITLE_MORE_INFO"
- "ERROR_PRIMARY_ACTION_TITLE_NO_ICLOUD_HSA2"
- "ERROR_PRIMARY_ACTION_TITLE_NO_ICLOUD_KEYCHAIN"
- "ERROR_PRIMARY_ACTION_TITLE_NO_PASSCODE"
- "ERROR_PRIMARY_ACTION_TITLE_NO_WIFI"
- "_TtC14CompanionSetup31DisclaimerContentViewController"
- "imageForDescriptor:"
- "initWithCGImage:"
- "lock.icloud.fill"
- "placeholder"
- "prepareImageForDescriptor:"
- "showRoomPicker rooms=%s, showsBackButton = %{bool}d"
```
