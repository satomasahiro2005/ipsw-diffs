## ACCNowPlayingFeature

> `/System/Library/PrivateFrameworks/CoreAccessoriesFeatures.framework/XPCServices/ACCNowPlayingFeature.xpc/ACCNowPlayingFeature`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x12a7c` | `0x12a28` | **`-0x54`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1176.0.26.502.1
+1196.0.0.502.1
Functions:
~ -[ACCNowPlayingFeature currentMediaItemAttributes] : 2808 -> 2804
~ -[ACCNowPlayingFeature currentPlaybackAttributes] : 3464 -> 3452
~ ___46-[ACCNowPlayingXPCService broadcastToClients:]_block_invoke : 300 -> 296
~ +[NSDictionary(Utilities) dictionaryOfChangesBetween:and:] : 432 -> 428
~ -[ACCMemUsageStat update] : 308 -> 304
~ ___init_logging_modules_block_invoke : 608 -> 588
~ -[MediaLibraryHelper applicationsDidInstall:] : 244 -> 240
~ -[MediaLibraryHelper applicationsWillUninstall:] : 244 -> 240
~ -[MediaLibraryHelper applicationsDidUninstall:] : 244 -> 240
~ _convertNSDataToNSString : 260 -> 256
~ _convertNSStringToNSData : 444 -> 440
~ _classImplementsMethodsInProtocol : 304 -> 300
~ _base64EncodeArray : 328 -> 324
~ _base64DecodeArray : 340 -> 336
~ _ascii_to_hex : 156 -> 160
~ _printBytes : 136 -> 156
~ ___init_logging_signpost_modules_block_invoke : 608 -> 588
~ _createHexString : 408 -> 400
```
