## RemotePaymentPassActionsMessagesExtension

> `/Applications/RemotePaymentPassActionsService.app/PlugIns/RemotePaymentPassActionsMessagesExtension.appex/RemotePaymentPassActionsMessagesExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8be4` | `0x9540` | **`+0x95c`** |
| `__TEXT.__oslogstring` | `0x10a9` | `0x1315` | **`+0x26c`** |
| `__TEXT.__objc_stubs` | `0x2140` | `0x22e0` | **`+0x1a0`** |
| `__TEXT.__objc_methname` | `0x2903` | `0x2a32` | **`+0x12f`** |
| `__DATA_CONST.__const` | `0x390` | `0x480` | **`+0xf0`** |
| `__DATA.__objc_selrefs` | `0xaa8` | `0xb10` | **`+0x68`** |
| `__TEXT.__cstring` | `0x7bd` | `0x815` | **`+0x58`** |
| `__TEXT.__auth_stubs` | `0x4d0` | `0x500` | **`+0x30`** |
| `__DATA_CONST.__auth_got` | `0x278` | `0x290` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x200` | `0x218` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x8d8` | `0x8f0` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x248` | `0x260` | **`+0x18`** |
| `__TEXT.__const` | `0x58` | `0x60` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`

### Other Changes

```diff

-1353.0.0.0.0
+1354.0.0.0.0

+  - /System/Library/PrivateFrameworks/FamilyCircle.framework/FamilyCircle

-  Functions: 148
-  Symbols:   166
-  CStrings:  593
+  Functions: 156
+  Symbols:   172
+  CStrings:  614
Symbols:
+ _NPKPreferencesGetValue
+ _NPKRemotePassActionSkipFamilyCircleVerification
+ _OBJC_CLASS_$_FAFetchFamilyCircleRequest
+ _PKOSVariantSubsystem
+ _dispatch_get_global_queue
+ _os_variant_has_internal_ui
CStrings:
+ "B16@?0@\"FAFamilyMember\"8"
+ "B32@?0@\"NSString\"8Q16^B24"
+ "Error: NPKRemotePassActionCompanionConversationManager: Failed to fetch family circle to verify sender: %@"
+ "Error: NPKRemotePassActionCompanionConversationManager: Unable to resolve a handle for the conversation; refusing to treat sender as a family member."
+ "Error: Refusing to present a payment sheet: sender is not a verified member of the family circle!"
+ "Notice: NPKRemotePassActionCompanionConversationManager: Skipping Family Circle verification due to internal-only debug override."
+ "Notice: NPKRemotePassActionCompanionConversationManager: Verified family circle membership for handle: %{private}@, isFamilyMember: %d"
+ "_shouldSkipFamilyCircleVerification"
+ "appleID"
+ "appleIDAliases"
+ "boolValue"
+ "caseInsensitiveCompare:"
+ "indexOfObjectPassingTest:"
+ "memberForPhoneNumber:"
+ "members"
+ "npkIsPhoneNumber"
+ "pk_containsObjectPassingTest:"
+ "setCachePolicy:"
+ "startRequestWithCompletionHandler:"
+ "v24@?0@\"FAFamilyCircle\"8@\"NSError\"16"
+ "verifyFamilyCircleMembershipForConversation:completion:"
```
