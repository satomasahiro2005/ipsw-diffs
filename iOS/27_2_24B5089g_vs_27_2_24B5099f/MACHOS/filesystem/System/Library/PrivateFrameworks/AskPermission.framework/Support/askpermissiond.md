## askpermissiond

> `/System/Library/PrivateFrameworks/AskPermission.framework/Support/askpermissiond`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x52e30` | `0x54490` | **`+0x1660`** |
| `__TEXT.__oslogstring` | `0x5b04` | `0x5e04` | **`+0x300`** |
| `__TEXT.__objc_methname` | `0x6f06` | `0x7156` | **`+0x250`** |
| `__TEXT.__objc_stubs` | `0x5a00` | `0x5bc0` | **`+0x1c0`** |
| `__DATA.__objc_const` | `0x5620` | `0x57c8` | **`+0x1a8`** |
| `__DATA_CONST.__cfstring` | `0x3240` | `0x3340` | **`+0x100`** |
| `__TEXT.__objc_methlist` | `0x29dc` | `0x2a8c` | **`+0xb0`** |
| `__TEXT.__cstring` | `0x3394` | `0x3434` | **`+0xa0`** |
| `__DATA.__objc_selrefs` | `0x1a50` | `0x1ac0` | **`+0x70`** |
| `__TEXT.__objc_methtype` | `0x1749` | `0x17a9` | **`+0x60`** |
| `__TEXT.__unwind_info` | `0xc60` | `0xc90` | **`+0x30`** |
| `__DATA.__objc_ivar` | `0x364` | `0x384` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x1968` | `0x1988` | **`+0x20`** |
| `__DATA.__bss` | `0x420` | `0x430` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x5a8` | `0x5b8` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
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
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-130.1.4.0.0
+130.1.6.0.0

-  Functions: 1167
-  Symbols:   555
-  CStrings:  2171
+  Functions: 1185
+  Symbols:   557
+  CStrings:  2214
Symbols:
+ _AMSAccountMediaTypeAppStoreSandbox
+ _OBJC_CLASS_$_NSISO8601DateFormatter
CStrings:
+ "%{public}@: Failed to handle Sandbox remote notification. Error: %{public}@"
+ "%{public}@: Getting SANDBOX Store Accounts"
+ "%{public}@: Getting Sandbox user. Action: %{public}ld"
+ "%{public}@: Handled Sandbox remote notification succesfully"
+ "%{public}@: Handling Sandbox request in Pending state"
+ "%{public}@: Handling Sandbox request in Unknown state"
+ "%{public}@: Ignoring pending request."
+ "%{public}@: Missing server result - %{public}@"
+ "%{public}@: No active Sandbox account"
+ "%{public}@: No sandbox store accounts"
+ "%{public}@: No store OR sandbox accounts - will not progress any further"
+ "%{public}@: Payload missing request DSID - will not progress any further"
+ "%{public}@: Payload request DSID doesn't match any active store or sandbox DSIDs - will not progress any further"
+ "%{public}@: Starting requester remote notification task (Sandbox: %d). Payload: %{public}@"
+ "%{public}@: Unable to decode server result - %{public}@"
+ "01:08:32"
+ "@240@0:8@16@24@32@40@48@56@64@72@80@88B96B100@104@112@120@128@136@144@152@160@168B176@180@188@196q204B212@216@224@232"
+ "@28@0:8^@16B24"
+ "@36@0:8@16B24^@28"
+ "@36@0:8q16B24^@28"
+ "@40@0:8@16@24B32B36"
+ "@76@0:8@16@24@32B40@44@52@60q68"
+ "ISO8601DateFormatter"
+ "No active Sandbox account"
+ "Sep 28 2026"
+ "Server Response Error"
+ "T@\"NSNumber\",R,N,V_requesterDSID"
+ "TB,N,V_isSandbox"
+ "TB,R,N,V_isSandbox"
+ "Unable to decode server result"
+ "_activeSandboxStoreDSIDs"
+ "_handleRequesterNotification:withRequesterDSID:andSuppressDialog:"
+ "_handleSandboxNotification:withRequesterDSID:"
+ "_handleSandboxRequest"
+ "_isSandbox"
+ "_requestInfoForIndentifier:isSandbox:withError:"
+ "_serverRequestWithError:isSandbox:"
+ "_serverRequestWithUser:isSandbox:error:"
+ "ams_iTunesSandboxAccounts"
+ "approvalRequestWithRequestIdentifier:isSandbox:"
+ "bagForProfile:profileVersion:processInfo:"
+ "createdDateISO8601"
+ "dateFormatter"
+ "initWithDate:requestIdentifier:uniqueIdentifier:isSandbox:itemIdentifier:localizations:offerName:status:"
+ "initWithItemIdentifier:requestIdentifier:uniqueIdentifier:ageRating:ageRatingValue:approverDSID:requesterDSID:requesterAltDSID:createdDate:modifiedDate:isException:isSandbox:itemBundleID:itemDesc:itemTitle:localizedPrice:previewURL:productType:productTypeName:productURL:offerName:originatedOnThisDevice:requestString:requestSummary:priceSummary:status:suppressClientResume:starRating:thumbnailURLString:uuid:"
+ "initWithPayload:requesterDSID:isSandbox:andSuppressDialog:"
+ "is-sandbox"
+ "isSandbox"
+ "isSandboxRequest"
+ "modifiedDateISO8601"
+ "primaryiCloudUserWithAction:isSandbox:keychainError:"
+ "sandboxBag"
+ "setFormatOptions:"
+ "setIsSandbox:"
+ "v36@0:8@16@24B32"
- "%{public}@: Payload request DSID doesn't match store DSIDs: %@"
- "%{public}@: Starting requester remote notification task. Payload: %{public}@"
- "10:28:12"
- "@236@0:8@16@24@32@40@48@56@64@72@80@88B96@100@108@116@124@132@140@148@156@164B172@176@184@192q200B208@212@220@228"
- "@72@0:8@16@24@32@40@48@56q64"
- "Sep 12 2026"
- "_handleRequesterNotification:andSuppressDialog:"
- "_serverRequestWithUser:error:"
- "initWithDate:requestIdentifier:uniqueIdentifier:itemIdentifier:localizations:offerName:status:"
- "initWithItemIdentifier:requestIdentifier:uniqueIdentifier:ageRating:ageRatingValue:approverDSID:requesterDSID:requesterAltDSID:createdDate:modifiedDate:isException:itemBundleID:itemDesc:itemTitle:localizedPrice:previewURL:productType:productTypeName:productURL:offerName:originatedOnThisDevice:requestString:requestSummary:priceSummary:status:suppressClientResume:starRating:thumbnailURLString:uuid:"
- "initWithPayload:andSuppressDialog:"
- "primaryiCloudUserWithAction:keychainError:"
```
