## PlugInKitDaemon

> `/System/Library/PrivateFrameworks/PlugInKitDaemon.framework/PlugInKitDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x17874` | `0x177ec` | **`-0x88`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```text
Functions:
~ -[PKDTransaction matchPlugIns] : 4848 -> 4836
~ -[PKDQuery _findPlugInsFromEnumerator:] : 544 -> 540
~ -[PKDQuery _findPlugInsWithExtensionPoint:platforms:] : 892 -> 884
~ -[PKDatabase findPlugInsForQuery:discoveryInstanceUUID:allVersions:] : 1404 -> 1400
~ -[PKDPlugIn augmentForm:host:] : 1424 -> 1420
~ -[PKDQuery _electionPatternAsArray] : 532 -> 528
~ -[PKDPlugIn issueResourceExtensions:auditToken:] : 800 -> 796
~ -[PKDPlugIn _subservicesFrom:] : 484 -> 480
~ __30-[PKDTransaction matchPlugIns]_block_invoke.151 : 3024 -> 3020
~ -[PKDServer holdOnPlugIn:] : 464 -> 460
~ -[PKDPlugIn match:discoveryInstanceUUID:server:withError:] : 476 -> 472
~ -[PKDPlugIn matchKey:pattern:discoveryInstanceUUID:server:withError:] : 1120 -> 1116
~ -[PKDPlugIn matchValue:patterns:] : 388 -> 384
~ __30-[PKDTransaction matchPlugIns]_block_invoke.157 : 840 -> 836
~ -[PKDatabase plugInsWithinApplication:] : 500 -> 496
~ -[PKDatabase plugInsWithExtensionPointName:platforms:] : 584 -> 580
~ -[PKDatabase pluginsDidInstall:] : 572 -> 568
~ -[PKDatabase pluginsWillUninstall:] : 868 -> 848
~ -[PKDPersonaCache _lock_personaUniqueStringsToPersonas:] : 512 -> 508
~ -[PKDPersonaCache _lock_resyncFromUserPersonaAttributes:] : 1700 -> 1692
~ +[PKDPlugIn sandboxOverrideForExtensionPoint:attributes:] : 608 -> 604
~ -[PKDPlugIn prunedInfoDictionaryFor:] : 376 -> 372
~ -[PKDPlugIn checkBusy] : 720 -> 716
~ -[PKDQuery _findPlugInsWithExtensionPoints:platforms:] : 396 -> 392
~ -[PKDServer terminatePlugIns:synchronously:reply:] : 940 -> 936
~ -[PKDServer unholdToken:silent:] : 500 -> 496
~ -[PKDServer stop] : 488 -> 484
~ -[PKDTransaction bulkAnnotatePlugIns] : 996 -> 1004
~ -[PKDTransaction lockDownPlugIns] : 1776 -> 1772
```
