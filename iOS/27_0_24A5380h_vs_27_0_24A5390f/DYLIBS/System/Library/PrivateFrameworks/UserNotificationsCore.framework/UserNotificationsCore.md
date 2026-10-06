## UserNotificationsCore

> `/System/Library/PrivateFrameworks/UserNotificationsCore.framework/UserNotificationsCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x231938` | `0x236050` | **`+0x4718`** |
| `__TEXT.__eh_frame` | `0x82d4` | `0x85d4` | **`+0x300`** |
| `__TEXT.__oslogstring` | `0x1160a` | `0x118aa` | **`+0x2a0`** |
| `__TEXT.__cstring` | `0x90d1` | `0x9191` | **`+0xc0`** |
| `__TEXT.__swift5_reflstr` | `0x474a` | `0x47ea` | **`+0xa0`** |
| `__TEXT.__unwind_info` | `0x64c0` | `0x6550` | **`+0x90`** |
| `__DATA_CONST.__objc_selrefs` | `0x3e10` | `0x3e70` | **`+0x60`** |
| `__DATA_DIRTY.__data` | `0x72f0` | `0x7340` | **`+0x50`** |
| `__TEXT.__swift5_fieldmd` | `0x5164` | `0x5194` | **`+0x30`** |
| `__TEXT.__swift_as_cont` | `0x3e4` | `0x408` | **`+0x24`** |
| `__TEXT.__const` | `0x1363c` | `0x1365c` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x1720` | `0x1738` | **`+0x18`** |
| `__TEXT.__swift_as_ret` | `0x238` | `0x24c` | **`+0x14`** |
| `__AUTH_CONST.__auth_got` | `0x2310` | `0x2320` | **`+0x10`** |
| `__DATA.__data` | `0x4098` | `0x40a8` | **`+0x10`** |
| `__TEXT.__swift_as_entry` | `0x214` | `0x220` | **`+0xc`** |

### Other Changes

```diff

-713.0.0.0.0
+717.0.0.0.0

+  - /System/Library/Frameworks/Contacts.framework/Contacts

-  Functions: 9466
-  Symbols:   6439
-  CStrings:  2194
+  Functions: 9489
+  Symbols:   6440
+  CStrings:  2208
Symbols:
+ _CNContactEmailAddressesKey
+ _CNContactPhoneNumbersKey
- _UNCCatchMe
CStrings:
+ "%{public}s Error while indexing without inference %@"
+ "%{public}s Indexing without inference, reason=%s"
+ "%{public}s Not publishing delivery event; notification was not indexed to Spotlight"
+ "CSPerson handles array is empty. %@"
+ "EntityQuery from Spotlight returned %ld results, mapped into %ld entities."
+ "EntityQuery using Spotlight for %{public}ld identifiers"
+ "Failed to query Spotlight fallback: %@"
+ "Falling back to Spotlight for %{public}ld identifiers not hydrated from the repository"
+ "Indexing: %{public}s suppressInference=%{bool,public}d"
+ "UniqueIdentifier workaround is only valid for notification queries."
+ "_kMDItemAppEntityInstanceIdentifier"
+ "indexedNoWaitCMAS"
+ "indexedNoWaitCritical"
+ "indexedNoWaitIgnoreDoNotDisturb"
+ "indexedNoWaitPlatformEligibility"
- "Indexing: %{public}s"
```
