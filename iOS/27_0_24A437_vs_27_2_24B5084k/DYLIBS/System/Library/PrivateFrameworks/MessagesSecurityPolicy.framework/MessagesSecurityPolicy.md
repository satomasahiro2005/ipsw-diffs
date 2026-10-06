## MessagesSecurityPolicy

> `/System/Library/PrivateFrameworks/MessagesSecurityPolicy.framework/MessagesSecurityPolicy`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1ad68` | `0x1ce80` | **`+0x2118`** |
| `__TEXT.__const` | `0x157e` | `0x18ce` | **`+0x350`** |
| `__TEXT.__oslogstring` | `0xf27` | `0x11e7` | **`+0x2c0`** |
| `__AUTH_CONST.__const` | `0x1418` | `0x16b0` | **`+0x298`** |
| `__TEXT.__constg_swiftt` | `0xc8c` | `0xdfc` | **`+0x170`** |
| `__TEXT.__eh_frame` | `0x588` | `0x6b0` | **`+0x128`** |
| `__TEXT.__swift5_typeref` | `0xb8c` | `0xc8c` | **`+0x100`** |
| `__AUTH.__data` | `0x4c8` | `0x598` | **`+0xd0`** |
| `__TEXT.__swift5_fieldmd` | `0x840` | `0x90c` | **`+0xcc`** |
| `__TEXT.__swift5_assocty` | `0x2a8` | `0x348` | **`+0xa0`** |
| `__TEXT.__swift5_reflstr` | `0x737` | `0x7d7` | **`+0xa0`** |
| `__TEXT.__unwind_info` | `0x5b8` | `0x640` | **`+0x88`** |
| `__DATA.__data` | `0x388` | `0x3e0` | **`+0x58`** |
| `__TEXT.__cstring` | `0x7e5` | `0x815` | **`+0x30`** |
| `__TEXT.__swift5_proto` | `0xec` | `0x118` | **`+0x2c`** |
| `__AUTH_CONST.__auth_got` | `0x730` | `0x758` | **`+0x28`** |
| `__AUTH_CONST.__objc_const` | `0xdc8` | `0xde8` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x2a8` | `0x2c8` | **`+0x20`** |
| `__DATA_DIRTY.__data` | `0x738` | `0x758` | **`+0x20`** |
| `__TEXT.__swift5_capture` | `0x8c4` | `0x8e4` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x1c8` | `0x1e0` | **`+0x18`** |
| `__TEXT.__swift5_types` | `0xa8` | `0xc0` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x354` | `0x364` | **`+0x10`** |
| `__TEXT.__swift5_protos` | `0x74` | `0x80` | **`+0xc`** |

### Other Changes

```diff

-1491.100.1.2.25
+1491.200.63.2.1

-  Functions: 547
-  Symbols:   487
-  CStrings:  118
+  Functions: 585
+  Symbols:   507
+  CStrings:  130
Symbols:
+ _BlastDoorInstanceTypeLockDownMode
+ _OBJC_CLASS_$_IMSyndicationUtilities
+ _swift_arrayInitWithTakeBackToFront
+ _swift_arrayInitWithTakeFrontToBack
+ _symbolic $s22MessagesSecurityPolicy20SyndicationUtilitiesP
+ _symbolic $s22MessagesSecurityPolicy21CloudKitShareURLRulesP
+ _symbolic $s22MessagesSecurityPolicy22CloudKitShareURLActionP
+ _symbolic Say_____G 10Foundation3URLV
+ _symbolic So18NSAttributedStringCSg
+ _symbolic _____ 22MessagesSecurityPolicy21CloudKitShareURLInputV
+ _symbolic _____ 22MessagesSecurityPolicy24CheckIfExistsAssetActionV
+ _symbolic _____ 22MessagesSecurityPolicy25SkipCloudKitShareURLRulesV
+ _symbolic _____ 22MessagesSecurityPolicy26SkipCloudKitShareURLActionV
+ _symbolic _____ 22MessagesSecurityPolicy28ScanForCloudKitShareURLRulesV
+ _symbolic _____ 22MessagesSecurityPolicy30ScanForCloudKitShareURLsActionV
+ _symbolic ______p 22MessagesSecurityPolicy20SyndicationUtilitiesP
+ _symbolic ______p 22MessagesSecurityPolicy22CloudKitShareURLActionP
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 10Foundation3URLV
+ _type_layout_string 22MessagesSecurityPolicy21CloudKitShareURLInputV
+ _type_layout_string 22MessagesSecurityPolicy30ScanForCloudKitShareURLsActionV
CStrings:
+ "CloudKitShareURLPolicyAction"
+ "CloudKitShareURLRulesSelector"
+ "Collecting CloudKit share URLs to register for %s, context: %ld"
+ "Executing CheckIfExistsAssetAction"
+ "Failed to check if attachment exists at URL: %s, with error: %@"
+ "Failed to collect CloudKit share URLs: %@"
+ "Selected BlastDoor interface for lock down mode"
+ "[CloudKitShareURLProcessing] Did not scan message for CloudKit share URLs"
+ "[CloudKitShareURLProcessing] Not scanning for CloudKit share URLs for %s sender"
+ "[CloudKitShareURLProcessing] Scanned message body and payload for CloudKit share URLs; found %{public}ld"
+ "[CloudKitShareURLProcessing] Scanning for CloudKit share URLs for %s sender"
+ "[CloudKitShareURLProcessing] Scanning for CloudKit share URLs for a junk report"
```
