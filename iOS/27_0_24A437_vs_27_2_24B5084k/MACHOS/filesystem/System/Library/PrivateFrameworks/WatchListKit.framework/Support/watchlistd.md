## watchlistd

> `/System/Library/PrivateFrameworks/WatchListKit.framework/Support/watchlistd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x290ec` | `0x29244` | **`+0x158`** |
| `__TEXT.__objc_stubs` | `0x53c0` | `0x5460` | **`+0xa0`** |
| `__TEXT.__cstring` | `0x47a8` | `0x4815` | **`+0x6d`** |
| `__TEXT.__objc_methname` | `0x60d7` | `0x6132` | **`+0x5b`** |
| `__TEXT.__oslogstring` | `0x2970` | `0x29b4` | **`+0x44`** |
| `__DATA.__objc_selrefs` | `0x1c68` | `0x1c90` | **`+0x28`** |
| `__DATA_CONST.__cfstring` | `0x3c40` | `0x3c60` | **`+0x20`** |
| `__DATA_CONST.__objc_arrayobj` | `—` | `0x18` | **`+0x18`** |
| `__DATA_CONST.__objc_intobj` | `0x60` | `0x78` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x5a8` | `0x5b0` | **`+0x8`** |
| `__DATA_CONST.__objc_arraydata` | `—` | `0x8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-952.0.1.0.0
+952.10.6.0.0

-  Symbols:   2577
-  CStrings:  1983
+  Symbols:   2584
+  CStrings:  1992
Symbols:
+ _OBJC_CLASS_$_IntentProgressReporterObjC
+ _OBJC_CLASS_$_NSConstantArray
+ _OBJC_CLASS_$_TVASCapabilityRegistryObjC
+ _objc_msgSend$defaultBagV3
+ _objc_msgSend$isChildAccount
+ _objc_msgSend$isSimpleProfile
+ _objc_msgSend$prewarmBagV3
+ _objc_msgSend$registerWithCapabilities:
+ _objc_msgSend$responseStatusCode
- _OBJC_CLASS_$_IntentPlayEventReporterObjC
- _objc_msgSend$statusCode
Functions:
~ +[AMSBag(WLKAdditions) wlk_defaultBag] : 264 -> 328
~ -[WLDClientConnection prewarm] : 92 -> 128
~ -[WLDServer _init] : 148 -> 192
~ __54+[WLDPlaybackReporter _decorateVODSummary:completion:]_block_invoke.36 : 680 -> 664
~ +[WLDPlaybackReporter _donateIntentWithPlaybackSummary:andMetadata:] : 1152 -> 1280
~ -[WLDPlaybackManager _shouldPromptForBundleID:outAccessStatus:] : 564 -> 652
CStrings:
+ "WLDPlaybackManager: should not prompt becuase it is currently disabled on U13 accounts."
+ "WLDPlaybackReporter - Skipping donation for Simple Profile account."
+ "defaultBagV3"
+ "isChildAccount"
+ "isSimpleProfile"
+ "prewarmBagV3"
+ "registerWithCapabilities:"
+ "responseStatusCode"
+ "sp_personal"
+ "tricycle"
- "statusCode"
```
