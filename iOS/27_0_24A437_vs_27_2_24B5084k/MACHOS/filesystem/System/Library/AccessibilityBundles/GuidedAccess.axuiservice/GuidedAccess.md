## GuidedAccess

> `/System/Library/AccessibilityBundles/GuidedAccess.axuiservice/GuidedAccess`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2f818` | `0x31bbc` | **`+0x23a4`** |
| `__TEXT.__auth_stubs` | `0xc70` | `0xfa0` | **`+0x330`** |
| `__TEXT.__objc_methname` | `0xc5f6` | `0xc88a` | **`+0x294`** |
| `__TEXT.__cstring` | `0x3ec6` | `0x4144` | **`+0x27e`** |
| `__DATA_CONST.__auth_got` | `0x648` | `0x7e0` | **`+0x198`** |
| `__TEXT.__objc_methtype` | `0x2530` | `0x26b4` | **`+0x184`** |
| `__TEXT.__objc_stubs` | `0x8ee0` | `0x9060` | **`+0x180`** |
| `__DATA.__objc_data` | `0xc80` | `0xdf8` | **`+0x178`** |
| `__DATA.__objc_const` | `0x47b8` | `0x48c8` | **`+0x110`** |
| `__TEXT.__const` | `0x1b0` | `0x280` | **`+0xd0`** |
| `__TEXT.__swift5_typeref` | `0x6` | `0xc0` | **`+0xba`** |
| `__DATA.__data` | `0xa08` | `0xab8` | **`+0xb0`** |
| `__TEXT.__objc_methlist` | `0x36cc` | `0x377c` | **`+0xb0`** |
| `__DATA_CONST.__cfstring` | `0x2a80` | `0x2b20` | **`+0xa0`** |
| `__TEXT.__oslogstring` | `0x1244` | `0x12e2` | **`+0x9e`** |
| `__TEXT.__objc_classname` | `0x75f` | `0x7cf` | **`+0x70`** |
| `__TEXT.__unwind_info` | `0xd50` | `0xdc0` | **`+0x70`** |
| `__TEXT.__constg_swiftt` | `0x50` | `0xb8` | **`+0x68`** |
| `__DATA.__objc_selrefs` | `0x2a98` | `0x2af8` | **`+0x60`** |
| `__DATA_CONST.__objc_dictobj` | `0x28` | `0x78` | **`+0x50`** |
| `__DATA_CONST.__got` | `0x520` | `0x558` | **`+0x38`** |
| `__TEXT.__swift5_fieldmd` | `0x10` | `0x48` | **`+0x38`** |
| `__DATA_CONST.__auth_ptr` | `—` | `0x30` | **`+0x30`** |
| `__TEXT.__swift5_reflstr` | `—` | `0x29` | **`+0x29`** |
| `__DATA_CONST.__objc_arraydata` | `0x10` | `0x30` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x1b48` | `0x1b38` | **`-0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x148` | `0x158` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0x974` | `0x968` | **`-0xc`** |
| `__TEXT.__swift5_types` | `0x4` | `0xc` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x264` | `0x268` | **`+0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`

### Other Changes

```diff

-1064.0.0.0.0
+1067.3.0.0.0

+  - /System/Library/PrivateFrameworks/DeviceConfiguration.framework/DeviceConfiguration

-  Functions: 1178
-  Symbols:   672
-  CStrings:  2573
+  Functions: 1214
+  Symbols:   709
+  CStrings:  2612
Symbols:
+ _CACornerRadiiEqualToRadii
+ _GAXCornerRadiiFromRectCornerRadii
+ _GAXDisplayCornerRadiiForWindow
+ _GAXFixedSpaceCornerRadiiFromInterfaceCornerRadii
+ _GAXIPCPayloadKeyHostedApplicationCornerRadii
+ _GAXRectCornerRadiiFromCornerRadii
+ _GAXUIMessageKeyHostedApplicationCornerRadii
+ _NSStringFromUIRectCornerRadii
+ __UITraitCollectionDisplayCornerRadiusUnspecified
+ ___chkstk_darwin
+ __swiftEmptyArrayStorage
+ __swift_stdlib_reportUnimplementedInitializer
+ _deserializeGAXBackboardState
+ _kCACornerCurveContinuous
+ _malloc_size
+ _memmove
+ _objc_allocWithZone
+ _objc_retainAutoreleasedReturnValue
+ _objc_retain_x27
+ _swift_allocObject
+ _swift_arrayInitWithCopy
+ _swift_arrayInitWithTakeBackToFront
+ _swift_arrayInitWithTakeFrontToBack
+ _swift_bridgeObjectRelease
+ _swift_bridgeObjectRetain
+ _swift_errorRelease
+ _swift_errorRetain
+ _swift_getObjectType
+ _swift_getTypeByMangledNameInContext2
+ _swift_getWitnessTable
+ _swift_release
+ _swift_release_x19
+ _swift_release_x22
+ _swift_release_x23
+ _swift_release_x24
+ _swift_release_x25
+ _swift_unknownObjectRelease
CStrings:
+ "-[AXSpringBoardServer(GAXAdditions) gaxUpdateStateOfHostedApplicationWithIdentifier:scaleFactorNumber:centerStringRepresentation:cornerRadiiStringRepresentation:animationDurationNumber:]"
+ "?"
+ "GAX Accessibility Intelligence Store"
+ "GAX DeviceConfiguration: FAILED to commit store(s) %@ — %@"
+ "GAX DeviceConfiguration: FAILED to delete store(s) %@ — %@"
+ "GAX DeviceConfiguration: committed store(s) %@"
+ "GAX DeviceConfiguration: committing store(s) %@ via provider %@ -> %@"
+ "GAX DeviceConfiguration: deleted store(s) %@"
+ "GAX DeviceConfiguration: deleting store(s) %@"
+ "GAXIPCPayloadKeyHostedApplicationCornerRadii"
+ "GuidedAccess.GAXDeviceConfigurationStore"
+ "T@\"NSString\",N,R"
+ "T{CACornerRadii={CGSize=dd}{CGSize=dd}{CGSize=dd}{CGSize=dd}},N"
+ "T{CACornerRadii={CGSize=dd}{CGSize=dd}{CGSize=dd}{CGSize=dd}},N,V_lastSentHostedApplicationCornerRadii"
+ "Unmanaged ASAM: publishing %lu DeviceConfiguration restriction store(s) for style %ld"
+ "Unmanaged ASAM: retracting %lu DeviceConfiguration restriction store(s)"
+ "_TtC12GuidedAccess27GAXDeviceConfigurationStore"
+ "_TtC12GuidedAccess30GAXDeviceConfigurationProvider"
+ "_allUnmanagedASAMDeviceConfigurationStores"
+ "_lastSentHostedApplicationCornerRadii"
+ "_unmanagedASAMDeviceConfigurationStoreNames"
+ "_unmanagedASAMDeviceConfigurationStoresForStyle:"
+ "_updateHostedApplicationCornerRadiiIfNeeded"
+ "allowAccessibilityAsk"
+ "com.apple.Accessibility"
+ "com.apple.accessibility.GuidedAccess"
+ "commitStores:"
+ "contentsCornerRadii"
+ "cornerRadii"
+ "deleteStoreNames:"
+ "effectiveRadiusForCorner:"
+ "gaxUpdateStateOfHostedApplicationWithIdentifier:scaleFactorNumber:centerStringRepresentation:cornerRadiiStringRepresentation:animationDurationNumber:"
+ "hosted application corner radii"
+ "init()"
+ "initWithName:valuesForConfigurationID:"
+ "lastSentHostedApplicationCornerRadii"
+ "name"
+ "setContentsCornerRadii:"
+ "setCornerCurve:"
+ "setCornerRadii:"
+ "setLastSentHostedApplicationCornerRadii:"
+ "updateHostedApplicationStateWithScaleFactor:center:cornerRadii:animationDuration:"
+ "v112@0:8d16{CGPoint=dd}24{CACornerRadii={CGSize=dd}{CGSize=dd}{CGSize=dd}{CGSize=dd}}40d104"
+ "v56@0:8@16@24@32@40@48"
+ "v80@0:8{CACornerRadii={CGSize=dd}{CGSize=dd}{CGSize=dd}{CGSize=dd}}16"
+ "valuesForConfigurationID"
+ "{CACornerRadii=\"minXMaxY\"{CGSize=\"width\"d\"height\"d}\"maxXMaxY\"{CGSize=\"width\"d\"height\"d}\"maxXMinY\"{CGSize=\"width\"d\"height\"d}\"minXMinY\"{CGSize=\"width\"d\"height\"d}}"
+ "{CACornerRadii={CGSize=dd}{CGSize=dd}{CGSize=dd}{CGSize=dd}}16@0:8"
- "-[AXSpringBoardServer(GAXAdditions) gaxUpdateStateOfHostedApplicationWithIdentifier:scaleFactorNumber:centerStringRepresentation:animationDurationNumber:]"
- "Td,N"
- "applicationViewRoundedCornerRadius"
- "contentsCornerRadius"
- "cornerRadius"
- "gaxUpdateStateOfHostedApplicationWithIdentifier:scaleFactorNumber:centerStringRepresentation:animationDurationNumber:"
- "setContentsCornerRadius:"
- "updateHostedApplicationStateWithScaleFactor:center:animationDuration:"
- "v48@0:8d16{CGPoint=dd}24d40"
```
