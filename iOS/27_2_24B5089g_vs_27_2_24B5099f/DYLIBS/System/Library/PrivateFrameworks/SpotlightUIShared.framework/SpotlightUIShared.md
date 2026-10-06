## SpotlightUIShared

> `/System/Library/PrivateFrameworks/SpotlightUIShared.framework/SpotlightUIShared`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xe4e74` | `0xe6200` | **`+0x138c`** |
| `__TEXT.__oslogstring` | `0x13e2` | `0x1602` | **`+0x220`** |
| `__DATA_CONST.__objc_selrefs` | `0x1620` | `0x1710` | **`+0xf0`** |
| `__TEXT.__objc_methlist` | `0xf00` | `0xfd8` | **`+0xd8`** |
| `__AUTH_CONST.__cfstring` | `0x820` | `0x8e0` | **`+0xc0`** |
| `__TEXT.__cstring` | `0x3468` | `0x34f8` | **`+0x90`** |
| `__DATA_CONST.__got` | `0x1018` | `0x1098` | **`+0x80`** |
| `__TEXT.__unwind_info` | `0x4308` | `0x4350` | **`+0x48`** |
| `__AUTH_CONST.__auth_got` | `0x1d38` | `0x1d68` | **`+0x30`** |
| `__AUTH_CONST.__objc_const` | `0x3ab8` | `0x3ae8` | **`+0x30`** |
| `__TEXT.__eh_frame` | `0x9334` | `0x9364` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x690` | `0x6b8` | **`+0x28`** |
| `__TEXT.__gcc_except_tab` | `0x18` | `0x28` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x80` | `0x84` | **`+0x4`** |

### Other Changes

```diff

-250.1.4.1.0
+250.1.9.0.0

+  - /System/Library/Frameworks/Security.framework/Security

-  Functions: 5263
-  Symbols:   2278
-  CStrings:  438
+  Functions: 5292
+  Symbols:   2324
+  CStrings:  452
Symbols:
+ +[SUISPasteboardExtractor createIdentifierKey]
+ +[SUISPasteboardExtractor finalizeUniqueIdentifierForAttributeSet:]
+ +[SUISPasteboardExtractor hashStringFromData:]
+ +[SUISPasteboardExtractor hashStringFromRawHash:]
+ +[SUISPasteboardExtractor hashStringFromString:key:]
+ +[SUISPasteboardExtractor identifierKeyQuery]
+ +[SUISPasteboardExtractor identifierKey]
+ +[SUISPasteboardExtractor loadIdentifierKey]
+ +[SUISPasteboardExtractor readIdentifierKeyWithStatus:]
+ +[SUISPasteboardManager carryOverHistoryAttributesTo:from:]
+ +[SUISPasteboardManager indexActionForAttributeSet:generationCount:lastIndexedAttributeSet:lastIndexedGeneration:hasNewlyCachedFiles:]
+ +[SUISPasteboardManager pasteboardIndexingQueue]
+ -[SUISPasteboardManager clearPasteboardHistoryIfWipeRequested]
+ -[SUISPasteboardManager deleteCachedFiles:]
+ -[SUISPasteboardManager deleteStalePasteboardItem:]
+ -[SUISPasteboardManager forgetLastIndexedAttributeSet:]
+ -[SUISPasteboardManager historyItemCopiedGeneration]
+ -[SUISPasteboardManager indexCoreSpotlightItemWithAttributeSet:replacing:newlyCachedFiles:]
+ -[SUISPasteboardManager indexOrUpdateIfExistsCorespotlightItemAttributeSet:generationCount:newlyCachedFiles:]
+ -[SUISPasteboardManager lastIndexedAttributeSet]
+ -[SUISPasteboardManager lastIndexedGeneration]
+ -[SUISPasteboardManager setHistoryItemCopiedGeneration:]
+ -[SUISPasteboardManager setLastIndexedAttributeSet:]
+ -[SUISPasteboardManager setLastIndexedGeneration:]
+ GCC_except_table4
+ _CCHmac
+ _CC_SHA256
+ _OBJC_CLASS_$_NSDictionary
+ _OBJC_CLASS_$_NSMutableData
+ _OBJC_IVAR_$_SUISPasteboardManager._historyItemCopiedGeneration
+ _OBJC_IVAR_$_SUISPasteboardManager._lastIndexedAttributeSet
+ _OBJC_IVAR_$_SUISPasteboardManager._lastIndexedGeneration
+ _OUTLINED_FUNCTION_1
+ _SecItemAdd
+ _SecItemCopyMatching
+ _SecRandomCopyBytes
+ __OBJC_$_CLASS_METHODS_SUISPasteboardExtractor
+ ___109-[SUISPasteboardManager indexOrUpdateIfExistsCorespotlightItemAttributeSet:generationCount:newlyCachedFiles:]_block_invoke
+ ___48+[SUISPasteboardManager pasteboardIndexingQueue]_block_invoke
+ ___55-[SUISPasteboardManager forgetLastIndexedAttributeSet:]_block_invoke
+ ___91-[SUISPasteboardManager indexCoreSpotlightItemWithAttributeSet:replacing:newlyCachedFiles:]_block_invoke
+ ___block_descriptor_48_e8_32s40s_e5_v8?0ls32l8s40l8
+ ___block_descriptor_64_e8_32s40s48s56s_e17_v16?0"NSError"8ls32l8s40l8s48l8s56l8
+ ___block_descriptor_72_e8_32s40s48s56s64s_e17_v16?0"NSArray"8ls32l8s40l8s48l8s56l8s64l8
+ ___kCFBooleanFalse
+ ___kCFBooleanTrue
+ _kSecAttrAccessGroup
+ _kSecAttrAccessible
+ _kSecAttrAccessibleAfterFirstUnlockThisDeviceOnly
+ _kSecAttrAccount
+ _kSecAttrService
+ _kSecAttrSynchronizable
+ _kSecClass
+ _kSecClassGenericPassword
+ _kSecRandomDefault
+ _kSecReturnData
+ _kSecUseDataProtectionKeychain
+ _kSecValueData
+ _objc_retain_x4
+ _pasteboardIndexingQueue.onceToken
+ _pasteboardIndexingQueue.queue
+ _sIdentifierKey
- +[SUISPasteboardManager pasteboardExpirationManagerQueue]
- -[SUISPasteboardManager changeCount]
- -[SUISPasteboardManager indexCoreSpotlightItemWithAttributeSet:]
- -[SUISPasteboardManager indexOrUpdateIfExistsCorespotlightItemAttributeSet:]
- -[SUISPasteboardManager pasteboardHistoryItemWasCopied]
- -[SUISPasteboardManager setChangeCount:]
- -[SUISPasteboardManager setPasteboardHistoryItemWasCopied:]
- _OBJC_IVAR_$_SUISPasteboardManager._changeCount
- _OBJC_IVAR_$_SUISPasteboardManager._pasteboardHistoryItemWasCopied
- ___57+[SUISPasteboardManager pasteboardExpirationManagerQueue]_block_invoke
- ___64-[SUISPasteboardManager indexCoreSpotlightItemWithAttributeSet:]_block_invoke
- ___76-[SUISPasteboardManager indexOrUpdateIfExistsCorespotlightItemAttributeSet:]_block_invoke
- ___block_descriptor_48_e8_32s40s_e17_v16?0"NSError"8ls32l8s40l8
- ___block_descriptor_56_e8_32s40s48s_e17_v16?0"NSArray"8ls32l8s40l8s48l8
- _pasteboardExpirationManagerQueue.onceToken
- _pasteboardExpirationManagerQueue.queue
CStrings:
+ "%02x"
+ "already indexed this content for generation count %ld, skipping hash:%@"
+ "better extraction for generation count %ld, replacing hash:%@ with hash:%@"
+ "cached attachment for generation count %ld was gone, re-indexing hash:%@"
+ "com.apple.Spotlight.pasteboardHistory"
+ "com.apple.spotlight.delete.pasteboard.unindexed"
+ "com.apple.spotlight.pasteboardIndexingQueue"
+ "com.apple.spotlight.replace.pasteboard.superseded"
+ "deleting stale pasteboard item hash:%@ files:%lu"
+ "failed to generate pasteboard identifier key"
+ "failed to read pasteboard identifier key: %d"
+ "failed to store pasteboard identifier key: %d"
+ "generated a new pasteboard identifier key"
+ "identifierKey"
+ "no identifier key available, not indexing this pasteboard item"
+ "not indexing pasteboard item, identifier length:%lu lastUsedDate:%@"
+ "pasteboard identifier key already exists, re-reading"
+ "wiping pasteboard history for the new identifier scheme"
- "com.apple.spotlight.pasteboardExpirationManagerQueue"
- "identifier for CSSItem has no length"
- "updating changeCount from:%ld to %ld"
- "we're missing the lastuseddate when indexing. Skip indexing."
```
