## ShareSheet

> `/System/Library/PrivateFrameworks/ShareSheet.framework/ShareSheet`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc7544` | `0xc7c80` | **`+0x73c`** |
| `__TEXT.__ustring` | `0x104` | `0x1f4` | **`+0xf0`** |
| `__TEXT.__cstring` | `0x7128` | `0x720c` | **`+0xe4`** |
| `__TEXT.__dlopen_cstrs` | `0xaaf` | `0xb4f` | **`+0xa0`** |
| `__TEXT.__oslogstring` | `0x7195` | `0x7217` | **`+0x82`** |
| `__TEXT.__gcc_except_tab` | `0x202c` | `0x207c` | **`+0x50`** |
| `__AUTH_CONST.__cfstring` | `0x59e0` | `0x5a20` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x3530` | `0x3570` | **`+0x40`** |
| `__AUTH_CONST.__objc_const` | `0x2a350` | `0x2a388` | **`+0x38`** |
| `__DATA_CONST.__const` | `0x28a8` | `0x28d8` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x11314` | `0x11344` | **`+0x30`** |
| `__DATA.__bss` | `0xab8` | `0xad8` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x8c30` | `0x8c48` | **`+0x18`** |

### Other Changes

```diff

-2126.10.4.0.0
+2131.10.1.2.7

-  Functions: 5897
-  Symbols:   10258
-  CStrings:  1613
+  Functions: 5906
+  Symbols:   10264
+  CStrings:  1618
Symbols:
+ -[SFShareSheetSlotManager fetchExistingShareForFileOrFolderURL:completionHandler:]
+ -[SHSheetInteractor fetchExistingShareForFileOrFolderURL:completionHandler:]
+ -[SHSheetServiceManager fetchExistingShareForFileOrFolderURL:completionHandler:]
+ -[UICollaborationInviteWithLinkActivity _systemImageName]
+ GCC_except_table65
+ ___87-[UICollaborationInviteWithLinkActivity canPerformWithCollaborationItem:activityItems:]_block_invoke
+ ___getSFUIActivityViewControllerConfiguratorClass_block_invoke
+ _getSFUIActivityViewControllerConfiguratorClass.softClass
- -[UICollaborationInviteWithLinkActivity _activityImage]
- -[UICollaborationInviteWithLinkActivity _activitySettingsImage]
CStrings:
+ "Add Access"
+ "If you share this with a group, you have to approve access for each member. Or you can allow anyone with the link for instant access."
+ "SFUIActivityViewControllerConfigurator"
+ "SHARE_LINK_ACCESS_REQUESTS_ALREADY_ON_MESSAGE"
+ "SHARE_LINK_ACCESS_REQUESTS_UNSUPPORTED_MESSAGE"
+ "Sharing/SFShareSheetSlotManager/fetchExistingShareForFileOrFolderURL"
+ "Timed out waiting for addItemAllowed, returning default YES."
+ "To add access for people, enter their email addresses or choose from your Contacts list.\n\nAdding access doesn’t share a link. After adding, let these participants know they have access."
+ "person.badge.plus"
- "CopyLinkActivity"
- "Create Link"
- "Create a link by adding people who you‘d like to collaborate with"
- "SHARE_LINK_ACCESS_REQUESTS_ON_MESSAGE"
```
