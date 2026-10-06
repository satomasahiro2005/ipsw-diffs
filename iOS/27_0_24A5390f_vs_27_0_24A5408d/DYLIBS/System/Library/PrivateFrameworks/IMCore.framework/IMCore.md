## IMCore

> `/System/Library/PrivateFrameworks/IMCore.framework/IMCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2fcdc0` | `0x2fd190` | **`+0x3d0`** |
| `__AUTH_CONST.__objc_const` | `0x221d0` | `0x22418` | **`+0x248`** |
| `__TEXT.__oslogstring` | `0x23b3b` | `0x23d1b` | **`+0x1e0`** |
| `__TEXT.__objc_methlist` | `0x18d4c` | `0x18e4c` | **`+0x100`** |
| `__TEXT.__cstring` | `0x13405` | `0x13355` | **`-0xb0`** |
| `__AUTH.__objc_data` | `0x4020` | `0x40c0` | **`+0xa0`** |
| `__TEXT.__gcc_except_tab` | `0x1193c` | `0x119c4` | **`+0x88`** |
| `__DATA_CONST.__objc_selrefs` | `0xeaa8` | `0xeb20` | **`+0x78`** |
| `__DATA.__data` | `0x64f8` | `0x6558` | **`+0x60`** |
| `__TEXT.__unwind_info` | `0xc390` | `0xc3c0` | **`+0x30`** |
| `__AUTH_CONST.__cfstring` | `0xbaa0` | `0xbac0` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x2878` | `0x2890` | **`+0x18`** |
| `__DATA_CONST.__objc_classlist` | `0x908` | `0x918` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x21a0` | `0x21a8` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x12bc` | `0x12c4` | **`+0x8`** |
| `__DATA_CONST.__const` | `0x58a0` | `0x58a8` | **`+0x8`** |
| `__DATA_CONST.__objc_protolist` | `0x578` | `0x580` | **`+0x8`** |

### Other Changes

```diff

-1487.100.6.2.2
+1491.100.1.2.11

-  Functions: 15211
-  Symbols:   2689
-  CStrings:  5023
+  Functions: 15223
+  Symbols:   2696
+  CStrings:  5025
Symbols:
+ _IMChatItemsUpdateReasonServiceChanged
+ _IMChatPropertyLastUPIVisibilityCheckDate
+ _IMIsRunningInMessagesNotificationExtension
+ _OBJC_CLASS_$_IMNewComposeRichCardMessagePartChatItem
+ _OBJC_CLASS_$_IMNewComposeTextMessagePartChatItem
+ _OBJC_METACLASS_$_IMNewComposeRichCardMessagePartChatItem
+ _OBJC_METACLASS_$_IMNewComposeTextMessagePartChatItem
CStrings:
+ "(IMChat) Welcome messages changed"
+ "Attempted to update security scoped url for transferGUID: %@ but no message exists for transfer"
+ "ServiceChanged"
+ "Struggling message awaiting satellite decision, don't downgrade: %@"
+ "UPI check triggered: %@ at %@ - oldNeedsHide: %@ newNeedsHide: %@ oldUPIDate: %@ newUPIDate: %@ oldestUPIDate: %@ -> UPIVisibilityChanged: %{bool}d UPIDateChanged: %{bool}d"
+ "UPI visibility changed, updating chat items for chat: %@ - UPIVisibilitySame: %{bool}d UPICheckDateChanged: %{bool}d lastUPIVisibilityCheckDate: %@"
+ "Welcome messages changed, updating chat items for chat: %@"
+ "set sortID %@ guid %@ itemIsUnsentAndFromMe %@"
+ "stage welcome prefilled text for chat: %@"
+ "stage welcome rich card in transcript for chat: %@"
- " doesn't match participants count: "
- "(IMChat) Service for sending changed"
- "At least one participant is required"
- "Chat record for rowID: %lld: guid: %s has no participants. Continuing export without this chat"
- "Conversation type "
- "Participant list is empty for chat: "
- "UPI visibility changed, updating chat items for chat: %@"
- "set sortID %@ guid %@ unsentIsFromMeItemOrThreadOriginator %@"
```
