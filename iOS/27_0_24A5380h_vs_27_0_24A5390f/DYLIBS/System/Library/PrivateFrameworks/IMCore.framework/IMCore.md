## IMCore

> `/System/Library/PrivateFrameworks/IMCore.framework/IMCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2fe854` | `0x2fcdc0` | **`-0x1a94`** |
| `__TEXT.__gcc_except_tab` | `0x12088` | `0x1193c` | **`-0x74c`** |
| `__TEXT.__oslogstring` | `0x240eb` | `0x23b3b` | **`-0x5b0`** |
| `__TEXT.__cstring` | `0x13515` | `0x13405` | **`-0x110`** |
| `__TEXT.__unwind_info` | `0xc478` | `0xc390` | **`-0xe8`** |
| `__AUTH_CONST.__objc_const` | `0x22198` | `0x221d0` | **`+0x38`** |
| `__TEXT.__objc_methlist` | `0x18d1c` | `0x18d4c` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x5878` | `0x58a0` | **`+0x28`** |
| `__AUTH_CONST.__cfstring` | `0xba80` | `0xbaa0` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0xea90` | `0xeaa8` | **`+0x18`** |
| `__AUTH_CONST.__auth_got` | `0x21a8` | `0x21a0` | **`-0x8`** |
| `__DATA_CONST.__got` | `0x2880` | `0x2878` | **`-0x8`** |
| `__DATA.__objc_ivar` | `0x12b8` | `0x12bc` | **`+0x4`** |

### Other Changes

```diff

-1486.100.5.2.1
+1487.100.6.2.2

-  Functions: 15208
-  Symbols:   2691
-  CStrings:  5052
+  Functions: 15211
+  Symbols:   2689
+  CStrings:  5023
Symbols:
- _IMRegisterForSiriSuggestionsInAppSettingChanges
- _IMSiriSuggestionsInAppSettingChangedNotification
CStrings:
+ "-[IMChatRegistry(IMChatRegistry_DaemonIncoming) historyQuery:chatID:services:finishedWithResult:limit:hasMessagesBefore:hasMessagesAfter:]"
+ "IMPLUGIN_SKIPCOLLABORATIONINITIATION_KEY"
- "%s Adding %lu identifiers to coalesced fetch"
- "%s: %ld identifiers need save state fetch"
- "-[IMChatRegistry(IMChatRegistry_DaemonIncoming) historyQuery:chatID:services:finishedWithResult:limit:]"
- "-[IMPhotoLibraryPersistenceManager cachedCountOfSyndicationIdentifiersSavedToSystemPhotoLibrary:shouldFetchAndNotifyAsNeeded:didStartFetch:]"
- "-[IMPhotoLibraryPersistenceManager fetchInfoForSyndicationIdentifiersSavedToSystemPhotoLibrary:completion:]"
- "-[IMSWHighlightCenterController initWithAppIdentifier:]"
- "Broadcasting changes to %lu listeners"
- "CoreAutomation"
- "Fetching %lu identifiers that weren't cached"
- "Finished fetching identifiers that weren't cached. Notifying listeners. identifiersNeedingFetch count: %lu"
- "IMHandle+Utilities: equivalentToRecipients - self or recipient array has duplicate values! self: %@; recipients: %@"
- "IMPhotoLibraryPersistenceManager -- syndicationIdentifiersPendingFetch cleared before fetch could begin, this is an invalid state"
- "IMSWHighlightCenterController"
- "Invalidating cache"
- "No more active sessions, unregistering all listeners and clearing caches"
- "Not allowing IMPhotoLibraryPersistenceManager to be created."
- "Not flushing save state cache as there were no deletions"
- "Not unregistering listener because it's already not listening %p"
- "Photo library changed, will invalidate %d"
- "Received photoLibraryDidChange: notification"
- "Registering IMPhotoLibraryPersistenceManager as a system photo library change observer"
- "Registering active session with GUID %@"
- "Registering as photo library persistence change listener %p"
- "Unregistering all persistence manager listeners"
- "Unregistering as photo library persistence change listener %p"
- "Unregistering listener %p"
- "Unregistering session with GUID %@ remaining sessions active %lu"
- "_handleSiriSuggestionsInAppSettingChanged"
- "groupParticipantsWithGroupID incoming ID %@ "
- "groupParticipantsWithGroupID resulting chat %@ "
- "groupParticipantsWithGroupID resulting participants %@ "
```
