## MobileMail

> `/private/var/staged_system_apps/MobileMail.app/MobileMail`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x62750c` | `0x6275a4` | **`+0x98`** |
| `__TEXT.__objc_stubs` | `0x46900` | `0x46880` | **`-0x80`** |
| `__TEXT.__gcc_except_tab` | `0x56180` | `0x561e0` | **`+0x60`** |
| `__TEXT.__objc_methname` | `0x699c7` | `0x69a27` | **`+0x60`** |
| `__DATA_CONST.__const` | `0x267c8` | `0x26788` | **`-0x40`** |
| `__DATA_CONST.__got` | `0x4278` | `0x4238` | **`-0x40`** |
| `__TEXT.__cstring` | `0x197c4` | `0x19784` | **`-0x40`** |
| `__TEXT.__oslogstring` | `0x1ac92` | `0x1ac62` | **`-0x30`** |
| `__DATA.__objc_const` | `0x37968` | `0x37988` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0x15b20` | `0x15b00` | **`-0x20`** |
| `__TEXT.__objc_methlist` | `0x26c2c` | `0x26c0c` | **`-0x20`** |
| `__DATA.__bss` | `0x16c38` | `0x16c28` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x1ab60` | `0x1ab70` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x1fdc` | `0x1fe8` | **`+0xc`** |
| `__DATA_CONST.__objc_catlist` | `0xf0` | `0xe8` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
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
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-3901.200.34.0.0
+3901.200.41.0.0

-  Symbols:   5046
-  CStrings:  22359
+  Symbols:   5038
+  CStrings:  22357
Symbols:
- _MFMessageCcContainsAccountAddress
- _MFMessageConversationIsMuted
- _MFMessageConversationIsVIP
- _MFMessageHasAttachments
- _MFMessageSenderIsVIP
- _MFMessageToContainsAccountAddress
- _MFMessageToOrCcContainsAccountAddress
- _MessageIsJournaled
CStrings:
+ "<%@: %p> Deferring load more messages - mailbox object ids not resolved yet"
+ "<%@: %p> Updated resolved mailbox object ids: %{public}@, complete: %i, mailboxes: %{public}@"
+ "Deferring selectDefaultMailbox until maild returns the mailbox list"
+ "TB,N,V_resolvedMailboxObjectIDsAreComplete"
+ "_cachedAccountDisplayName"
+ "_didRetryMailboxObjectIDsAfterLoadFailure"
+ "_pendingMailboxCacheWarmRefresh"
+ "_resolvedMailboxObjectIDsAreComplete"
+ "_selectDefaultMailboxWhenMailboxesAreAvailable"
+ "_updateResolvedMailboxObjectIDsRetryingWhenCacheWarms:"
+ "accountIfAvailable"
+ "accountWithURL:"
+ "availableMailboxTypeResolver"
+ "isMailboxCacheWarm"
+ "mailboxesFuture"
+ "resolvedMailboxObjectIDsAreComplete"
+ "setBucketBarPeekingEnabled:"
+ "setResolvedMailboxObjectIDsAreComplete:"
+ "v16@?0@\"NSOrderedSet\"8"
- "#Warning Unsupported criterion during server-side searchability determination (failing transformation) : %@"
- "#Warning unexpected criterion during server-side searchability determination (assuming YES) : %@"
- "<%@: %p> Updated resolved mailbox object ids: %{public}@, mailboxes: %{public}@"
- "@\"MFMessageCriterion\"16@?0@\"MFMessageCriterion\"8"
- "@\"MFMessageCriterion\"16@?0@\"NSString\"8"
- "TB,N,V_wasWindowSceneWide"
- "_wasWindowSceneWide"
- "allVIPEmailAddressesCriterion"
- "components:fromDate:"
- "criteria"
- "criterionByApplyingTransform:"
- "expression"
- "initWithType:qualifier:expression:"
- "mailServerSideCriterion"
- "mf_shouldUseDesktopClassNavigationBarForTraitCollection:windowScene:"
- "mui_isWide"
- "myEmailAddressesCriterionWithType:"
- "notCriterionWithCriterion:"
- "orCompoundCriterionWithCriteria:"
- "setWasWindowSceneWide:"
- "wasWindowSceneWide"
```
