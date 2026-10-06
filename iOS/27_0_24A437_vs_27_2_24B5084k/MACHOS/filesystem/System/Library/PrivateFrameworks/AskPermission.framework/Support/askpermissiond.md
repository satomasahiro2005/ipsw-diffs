## askpermissiond

> `/System/Library/PrivateFrameworks/AskPermission.framework/Support/askpermissiond`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x51958` | `0x52e30` | **`+0x14d8`** |
| `__TEXT.__oslogstring` | `0x5880` | `0x5b04` | **`+0x284`** |
| `__TEXT.__objc_methname` | `0x6d66` | `0x6f06` | **`+0x1a0`** |
| `__DATA_CONST.__cfstring` | `0x30e0` | `0x3240` | **`+0x160`** |
| `__TEXT.__objc_stubs` | `0x58a0` | `0x5a00` | **`+0x160`** |
| `__TEXT.__cstring` | `0x3274` | `0x3394` | **`+0x120`** |
| `__TEXT.__objc_methlist` | `0x295c` | `0x29dc` | **`+0x80`** |
| `__DATA.__objc_selrefs` | `0x19f8` | `0x1a50` | **`+0x58`** |
| `__TEXT.__swift5_typeref` | `0x2c7` | `0x319` | **`+0x52`** |
| `__TEXT.__objc_methtype` | `0x16f9` | `0x1749` | **`+0x50`** |
| `__TEXT.__auth_stubs` | `0x1380` | `0x13b0` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x1948` | `0x1968` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x588` | `0x5a8` | **`+0x20`** |
| `__DATA.__objc_const` | `0x5608` | `0x5620` | **`+0x18`** |
| `__DATA_CONST.__auth_got` | `0x9d0` | `0x9e8` | **`+0x18`** |
| `__DATA.__bss` | `0x410` | `0x420` | **`+0x10`** |
| `__DATA.__data` | `0x680` | `0x690` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0xc50` | `0xc60` | **`+0x10`** |
| `__TEXT.__swift5_capture` | `0x360` | `0x36c` | **`+0xc`** |
| `__DATA_CONST.__auth_ptr` | `0x150` | `0x158` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x360` | `0x364` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-130.0.29.0.0
+130.1.4.0.0

-  Functions: 1154
-  Symbols:   547
-  CStrings:  2137
+  Functions: 1167
+  Symbols:   555
+  CStrings:  2171
Symbols:
+ _$s5AskTo16ATDispatchCenterC23stageQuestionInMessages_14recipientGroupyAA10ATQuestionC_AA011ATRecipientJ0OtYaKF
+ _$s5AskTo16ATDispatchCenterC23stageQuestionInMessages_14recipientGroupyAA10ATQuestionC_AA011ATRecipientJ0OtYaKFTu
+ _$s9AskToCore10ATIconTypeO13graphicSymbolyACSS_AA7ATColorVSgSayAFGtcACmFWC
+ _$s9AskToCore7ATColorV3red5green4blue7opacityACSf_S3ftcfC
+ _$s9AskToCore7ATColorVMa
+ _$s9AskToCore7ATColorVMn
+ _NSCalendarIdentifierGregorian
+ _OBJC_CLASS_$_NSCalendar
+ _OBJC_CLASS_$_NSTimeZone
+ _objc_retain_x5
- _$s5AskTo16ATDispatchCenterC4send_2toyAA10ATQuestionC_AA16ATRecipientGroupOtYaKF
- _$s5AskTo16ATDispatchCenterC4send_2toyAA10ATQuestionC_AA16ATRecipientGroupOtYaKFTu
CStrings:
+ "%{public}@: Could not fetch FamilyCircle to find a single approver. Error: %{public}@"
+ "%{public}@: Could not look up a single approver to pre-fill. Error: %{public}@"
+ "%{public}@: Could not resolve a single approver with a username to pre-fill. Approver count: %{public}lu"
+ "%{public}@: Family has multiple approvers; not pre-filling. Approver count: %{public}lu"
+ "%{public}@: Fetching FamilyCircle to find a single approver"
+ "%{public}@: Found a single approver to pre-fill"
+ "%{public}@: No single approver to pre-fill; prompting for the full Apple ID"
+ "%{public}@: Unable to send via AskTo - request has no UUID - Checking if we can send via PeopleClient"
+ "21:44:02"
+ "Could not fetch FamilyCircle"
+ "Family error"
+ "Family has multiple approvers"
+ "Family has no approver with a username to pre-fill"
+ "No approver to pre-fill"
+ "No single approver"
+ "Sep  4 2026"
+ "T@\"NSString\",C,N"
+ "T@\"NSString\",C,N,Vusername"
+ "UTC"
+ "VIEW_SERVICE_CONNECTION_LOST_ERROR_BODY"
+ "_isApprover:"
+ "_presentErrorAlertWithTitle:body:errorCode:correlationId:responseBody:requesterDSID:"
+ "_singleApproverUsernameWithFamilyRequest:"
+ "askForExceptionWithUuid:type:title:message:bundleIdentifier:preApprove:postApprove:preDecline:postDecline:expirationDate:responseBundleIdentifier:badgeIconBundleIdentifier:metadata:fallbackURL:delegateCallback:completionHandler:"
+ "askToBadgeIconBundleIdentifier"
+ "askToBuyWithUuid:title:message:bundleIdentifier:preApprove:postApprove:preDecline:postDecline:expirationDate:responseBundleIdentifier:badgeIconBundleIdentifier:metadata:fallbackURL:delegateCallback:completionHandler:"
+ "askWithTopic:uuid:title:message:bundleIdentifier:preApprove:postApprove:preDecline:postDecline:expirationDate:responseBundleIdentifier:badgeIconBundleIdentifier:metadata:fallbackURL:delegateCallback:completionHandler:"
+ "calendarWithIdentifier:"
+ "com.apple.Music"
+ "com.apple.iBooks"
+ "domain"
+ "members"
+ "plus.arrow.trianglehead.clockwise"
+ "presentDialogWithTitle:body:buttons:showIcon:completion:"
+ "setCalendar:"
+ "setTimeZone:"
+ "singleApproverUsername"
+ "subscription"
+ "timeZoneWithAbbreviation:"
+ "v136@0:8@\"NSUUID\"16@\"NSString\"24@\"NSString\"32@\"NSString\"40@\"NSString\"48@\"NSString\"56@\"NSString\"64@\"NSString\"72@\"NSDate\"80@\"NSString\"88@\"NSString\"96@\"APAskToAgeRestrictionMetadata\"104@\"NSURL\"112@?<v@?B@\"NSError\">120@?<v@?B@\"NSError\">128"
+ "v144@0:8@\"ATQuestionTopic\"16@\"NSUUID\"24@\"NSString\"32@\"NSString\"40@\"NSString\"48@\"NSString\"56@\"NSString\"64@\"NSString\"72@\"NSString\"80@\"NSDate\"88@\"NSString\"96@\"NSString\"104@\"APAskToAgeRestrictionMetadata\"112@\"NSURL\"120@?<v@?B@\"NSError\">128@?<v@?B@\"NSError\">136"
+ "v144@0:8@\"NSUUID\"16q24@\"NSString\"32@\"NSString\"40@\"NSString\"48@\"NSString\"56@\"NSString\"64@\"NSString\"72@\"NSString\"80@\"NSDate\"88@\"NSString\"96@\"NSString\"104@\"APAskToAgeRestrictionMetadata\"112@\"NSURL\"120@?<v@?B@\"NSError\">128@?<v@?B@\"NSError\">136"
+ "v24@0:8@\"NSString\"16"
+ "v52@0:8@16@24@32B40@?44"
+ "v64@0:8@16@24q32@40@48@56"
+ "yyyy-MM-dd'T'HH:mm:ss.SZZZ"
- "20:19:25"
- "@\"NSUUID\"16@0:8"
- "Aug  8 2026"
- "T@\"NSUUID\",R,N"
- "YYYY-MM-dd'T'HH:mm:ss.SZZZ"
- "askForExceptionWithUuid:type:title:message:bundleIdentifier:preApprove:postApprove:preDecline:postDecline:expirationDate:responseBundleIdentifier:metadata:fallbackURL:delegateCallback:completionHandler:"
- "askToBuyWithUuid:title:message:bundleIdentifier:preApprove:postApprove:preDecline:postDecline:expirationDate:responseBundleIdentifier:metadata:fallbackURL:delegateCallback:completionHandler:"
- "askWithTopic:uuid:title:message:bundleIdentifier:preApprove:postApprove:preDecline:postDecline:expirationDate:responseBundleIdentifier:metadata:fallbackURL:delegateCallback:completionHandler:"
- "presentDialogWithTitle:body:buttons:completion:"
- "v128@0:8@\"NSUUID\"16@\"NSString\"24@\"NSString\"32@\"NSString\"40@\"NSString\"48@\"NSString\"56@\"NSString\"64@\"NSString\"72@\"NSDate\"80@\"NSString\"88@\"APAskToAgeRestrictionMetadata\"96@\"NSURL\"104@?<v@?B@\"NSError\">112@?<v@?B@\"NSError\">120"
- "v136@0:8@\"ATQuestionTopic\"16@\"NSUUID\"24@\"NSString\"32@\"NSString\"40@\"NSString\"48@\"NSString\"56@\"NSString\"64@\"NSString\"72@\"NSString\"80@\"NSDate\"88@\"NSString\"96@\"APAskToAgeRestrictionMetadata\"104@\"NSURL\"112@?<v@?B@\"NSError\">120@?<v@?B@\"NSError\">128"
- "v136@0:8@\"NSUUID\"16q24@\"NSString\"32@\"NSString\"40@\"NSString\"48@\"NSString\"56@\"NSString\"64@\"NSString\"72@\"NSString\"80@\"NSDate\"88@\"NSString\"96@\"APAskToAgeRestrictionMetadata\"104@\"NSURL\"112@?<v@?B@\"NSError\">120@?<v@?B@\"NSError\">128"
```
