## askpermissiond

> `/System/Library/PrivateFrameworks/AskPermission.framework/Support/askpermissiond`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4e214` | `0x514dc` | **`+0x32c8`** |
| `__DATA.__objc_const` | `0x5378` | `0x5608` | **`+0x290`** |
| `__TEXT.__objc_methname` | `0x6af6` | `0x6d26` | **`+0x230`** |
| `__TEXT.__objc_stubs` | `0x5680` | `0x5860` | **`+0x1e0`** |
| `__TEXT.__oslogstring` | `0x560b` | `0x57b8` | **`+0x1ad`** |
| `__TEXT.__cstring` | `0x30ec` | `0x3254` | **`+0x168`** |
| `__TEXT.__auth_stubs` | `0x1220` | `0x1360` | **`+0x140`** |
| `__TEXT.__objc_methlist` | `0x283c` | `0x2944` | **`+0x108`** |
| `__DATA_CONST.__cfstring` | `0x2fc0` | `0x3080` | **`+0xc0`** |
| `__DATA.__objc_data` | `0x13e8` | `0x1490` | **`+0xa8`** |
| `__DATA_CONST.__auth_got` | `0x920` | `0x9c0` | **`+0xa0`** |
| `__TEXT.__objc_methtype` | `0x166d` | `0x16f9` | **`+0x8c`** |
| `__DATA.__objc_selrefs` | `0x1960` | `0x19e8` | **`+0x88`** |
| `__DATA.__data` | `0x608` | `0x680` | **`+0x78`** |
| `__TEXT.__objc_classname` | `0x5e0` | `0x61b` | **`+0x3b`** |
| `__TEXT.__const` | `0x618` | `0x650` | **`+0x38`** |
| `__DATA.__bss` | `0x3e0` | `0x410` | **`+0x30`** |
| `__DATA_CONST.__got` | `0x558` | `0x588` | **`+0x30`** |
| `__DATA_CONST.__objc_intobj` | `0xa8` | `0xd8` | **`+0x30`** |
| `__TEXT.__gcc_except_tab` | `0x350` | `0x380` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0xc10` | `0xc40` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x18d0` | `0x18f8` | **`+0x28`** |
| `__TEXT.__swift5_typeref` | `0x2a2` | `0x2c7` | **`+0x25`** |
| `__DATA_CONST.__auth_ptr` | `0x138` | `0x150` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x34c` | `0x360` | **`+0x14`** |
| `__DATA_CONST.__objc_classlist` | `0x1b0` | `0x1c0` | **`+0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0xd8` | `0xe8` | **`+0x10`** |
| `__TEXT.__swift5_capture` | `0x354` | `0x360` | **`+0xc`** |
| `__DATA_CONST.__objc_protolist` | `0x50` | `0x58` | **`+0x8`** |
| `__TEXT.__constg_swiftt` | `0x2a0` | `0x2a8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_reflstr`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-130.0.23.0.0
+130.0.25.0.0

+  - /System/Library/Frameworks/CoreGraphics.framework/CoreGraphics

+  - /System/Library/Frameworks/ImageIO.framework/ImageIO

+  - /System/Library/Frameworks/QuartzCore.framework/QuartzCore

-  - /System/Library/PrivateFrameworks/ScreenTimeUI.framework/ScreenTimeUI

-  Functions: 1129
-  Symbols:   517
-  CStrings:  2085
+  Functions: 1150
+  Symbols:   545
+  CStrings:  2129
Symbols:
+ _$s10Foundation3URLV19_bridgeToObjectiveCSo5NSURLCyF
+ _$s10Foundation4DateV36_unconditionallyBridgeFromObjectiveCyACSo6NSDateCSgFZ
+ _$s10Foundation4DateVMa
+ _$s10Foundation4DateVMn
+ _$s5AskTo10ATQuestionC0aB4CoreE17AssociatedContentV16bundleIdentifierSSSgvs
+ _$s5AskTo10ATQuestionC0aB4CoreE20VisualRepresentationO5imageyAFSo10CGImageRefacAFmFWC
+ _$s5AskTo10ATQuestionC0aB4CoreE20VisualRepresentationOMa
+ _$s5AskTo10ATQuestionC0aB4CoreE20VisualRepresentationOMn
+ _$s5AskTo10ATQuestionC14expirationDate10Foundation0E0VSgvs
+ _$s5AskTo10ATQuestionC16notificationTextSSSgvs
+ _$s5AskTo10ATQuestionC17associatedContentAC0aB4CoreE010AssociatedE0VvM
+ _$s5AskTo10ATQuestionC20visualRepresentationAC0aB4CoreE06VisualE0OSgvs
+ _$s5AskTo10ATQuestionC9badgeIcon0aB4Core10ATIconTypeOSgvs
+ _$s9AskToCore10ATIconTypeO7appIconyAcA13ATApplicationV_tcACmFWC
+ _$s9AskToCore10ATIconTypeOMa
+ _$s9AskToCore10ATIconTypeOMn
+ _$s9AskToCore13ATApplicationV8bundleIDACSS_tcfC
+ _CGBitmapContextCreate
+ _CGBitmapContextCreateImage
+ _CGColorSpaceCreateDeviceRGB
+ _CGImageGetHeight
+ _CGImageGetWidth
+ _CGImageSourceCreateImageAtIndex
+ _CGImageSourceCreateWithURL
+ _OBJC_CLASS_$_CALayer
+ __dispatch_source_type_timer
+ _dispatch_source_cancel
+ _dispatch_source_set_timer
+ _kCACornerCurveContinuous
- _$s5AskTo10ATQuestionC33associatedContentBundleIdentifierSSSgvs
CStrings:
+ "%@: "
+ "%@: [%@] "
+ "%{public}@: Authentication timed out after %{public}.0f seconds"
+ "%{public}@: Purchase did *NOT* originate on this device - Will not replay purchase."
+ "%{public}@: Reloading ApprovalRequest failed for UniqueIdentifier: %@ - defaulting originatedOnThisDevice flag to YES to avoid no-purchase on any device"
+ "%{public}@: Remote alert handle deallocated without ever completing authentication"
+ "%{public}@: Remote alert handle invalidated. Error: %{public}@"
+ "%{public}@Failed to find AdamID for BundleID via AppStore Daemon Library. %{public}@"
+ "%{public}@Found AdamIDs for BundleID via AppStore Daemon Library: %{public}@"
+ "%{public}@Not a SAD app - falling back to record's storeItemIdentifier"
+ "05:38:49"
+ "@"
+ "@236@0:8@16@24@32@40@48@56@64@72@80@88B96@100@108@116@124@132@140@148@156@164B172@176@184@192q200B208@212@220@228"
+ "@24@0:8@?16"
+ "@?"
+ "APUserProviderAuthObserver"
+ "Adding visualRepresentation requestedAppIconURL: "
+ "AltDistro App Exception - No PIN Set - Local Auth skipped, Exception Approved"
+ "Authentication Success for Local Approval of App Exception"
+ "Authentication timed out"
+ "DeallocGuard"
+ "Error creating rounded image"
+ "Error loading image"
+ "Jul 11 2026"
+ "Remote alert handle deallocated without completing"
+ "Remote alert handle invalidated"
+ "SBSRemoteAlertHandleObserver"
+ "TB,N,V_originatedOnThisDevice"
+ "TB,R,N,V_originatedOnThisDevice"
+ "_block"
+ "_completePendingAuthenticationForToken:user:error:"
+ "_createAndStoreExceptionRequestWithAccount:"
+ "_originatedOnThisDevice"
+ "_token"
+ "addServerExpiration"
+ "askForExceptionWithUuid:type:title:message:bundleIdentifier:preApprove:postApprove:preDecline:postDecline:expirationDate:responseBundleIdentifier:metadata:fallbackURL:delegateCallback:completionHandler:"
+ "askToBuyWithUuid:title:message:bundleIdentifier:preApprove:postApprove:preDecline:postDecline:expirationDate:responseBundleIdentifier:metadata:fallbackURL:delegateCallback:completionHandler:"
+ "askWithTopic:uuid:title:message:bundleIdentifier:preApprove:postApprove:preDecline:postDecline:expirationDate:responseBundleIdentifier:metadata:fallbackURL:delegateCallback:completionHandler:"
+ "initWithDeallocGuardBlock:"
+ "initWithItemIdentifier:requestIdentifier:uniqueIdentifier:ageRating:ageRatingValue:approverDSID:requesterDSID:requesterAltDSID:createdDate:modifiedDate:isException:itemBundleID:itemDesc:itemTitle:localizedPrice:previewURL:productType:productTypeName:productURL:offerName:originatedOnThisDevice:requestString:requestSummary:priceSummary:status:suppressClientResume:starRating:thumbnailURLString:uuid:"
+ "initWithToken:"
+ "isCacheDateExpired:"
+ "originatedOnThisDevice"
+ "registerObserver:"
+ "remoteAlertHandle:didInvalidateWithError:"
+ "remoteAlertHandleDidActivate:"
+ "remoteAlertHandleDidDeactivate:"
+ "renderInContext:"
+ "setContents:"
+ "setCornerCurve:"
+ "setCornerRadius:"
+ "setFrame:"
+ "setMasksToBounds:"
+ "setOriginatedOnThisDevice:"
+ "v128@0:8@\"NSUUID\"16@\"NSString\"24@\"NSString\"32@\"NSString\"40@\"NSString\"48@\"NSString\"56@\"NSString\"64@\"NSString\"72@\"NSDate\"80@\"NSString\"88@\"APAskToAgeRestrictionMetadata\"96@\"NSURL\"104@?<v@?B@\"NSError\">112@?<v@?B@\"NSError\">120"
+ "v136@0:8@\"ATQuestionTopic\"16@\"NSUUID\"24@\"NSString\"32@\"NSString\"40@\"NSString\"48@\"NSString\"56@\"NSString\"64@\"NSString\"72@\"NSString\"80@\"NSDate\"88@\"NSString\"96@\"APAskToAgeRestrictionMetadata\"104@\"NSURL\"112@?<v@?B@\"NSError\">120@?<v@?B@\"NSError\">128"
+ "v136@0:8@\"NSUUID\"16q24@\"NSString\"32@\"NSString\"40@\"NSString\"48@\"NSString\"56@\"NSString\"64@\"NSString\"72@\"NSString\"80@\"NSDate\"88@\"NSString\"96@\"APAskToAgeRestrictionMetadata\"104@\"NSURL\"112@?<v@?B@\"NSError\">120@?<v@?B@\"NSError\">128"
+ "v24@0:8@\"SBSRemoteAlertHandle\"16"
+ "v32@0:8@\"SBSRemoteAlertHandle\"16@\"NSError\"24"
- "%{public}@: Failed to find AdamID for BundleID via AppStore Daemon Library. %{public}@"
- "%{public}@: Found AdamIDs for BundleID via AppStore Daemon Library: %{public}@"
- "%{public}@: User unable to use iMessage - Creating new Request with UUID: %{public}@"
- "04:11:43"
- "@232@0:8@16@24@32@40@48@56@64@72@80@88B96@100@108@116@124@132@140@148@156@164@172@180@188q196B204@208@216@224"
- "Authentication Succiess for Local Approval of App Exception"
- "Jun 27 2026"
- "askForExceptionWithUuid:type:title:message:bundleIdentifier:preApprove:postApprove:preDecline:postDecline:responseBundleIdentifier:metadata:fallbackURL:delegateCallback:completionHandler:"
- "askToBuyWithUuid:title:message:bundleIdentifier:preApprove:postApprove:preDecline:postDecline:responseBundleIdentifier:metadata:fallbackURL:delegateCallback:completionHandler:"
- "askWithTopic:uuid:title:message:bundleIdentifier:preApprove:postApprove:preDecline:postDecline:responseBundleIdentifier:metadata:fallbackURL:delegateCallback:completionHandler:"
- "initWithItemIdentifier:requestIdentifier:uniqueIdentifier:ageRating:ageRatingValue:approverDSID:requesterDSID:requesterAltDSID:createdDate:modifiedDate:isException:itemBundleID:itemDesc:itemTitle:localizedPrice:previewURL:productType:productTypeName:productURL:offerName:requestString:requestSummary:priceSummary:status:suppressClientResume:starRating:thumbnailURLString:uuid:"
- "isDateExpired:"
- "v120@0:8@\"NSUUID\"16@\"NSString\"24@\"NSString\"32@\"NSString\"40@\"NSString\"48@\"NSString\"56@\"NSString\"64@\"NSString\"72@\"NSString\"80@\"APAskToAgeRestrictionMetadata\"88@\"NSURL\"96@?<v@?B@\"NSError\">104@?<v@?B@\"NSError\">112"
- "v128@0:8@\"ATQuestionTopic\"16@\"NSUUID\"24@\"NSString\"32@\"NSString\"40@\"NSString\"48@\"NSString\"56@\"NSString\"64@\"NSString\"72@\"NSString\"80@\"NSString\"88@\"APAskToAgeRestrictionMetadata\"96@\"NSURL\"104@?<v@?B@\"NSError\">112@?<v@?B@\"NSError\">120"
- "v128@0:8@\"NSUUID\"16q24@\"NSString\"32@\"NSString\"40@\"NSString\"48@\"NSString\"56@\"NSString\"64@\"NSString\"72@\"NSString\"80@\"NSString\"88@\"APAskToAgeRestrictionMetadata\"96@\"NSURL\"104@?<v@?B@\"NSError\">112@?<v@?B@\"NSError\">120"
```
