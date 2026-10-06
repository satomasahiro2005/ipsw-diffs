## demod

> `/usr/libexec/demod`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xf9cfc` | `0xfab14` | **`+0xe18`** |
| `__TEXT.__oslogstring` | `0x1d6bc` | `0x1d95c` | **`+0x2a0`** |
| `__TEXT.__cstring` | `0x115b2` | `0x11792` | **`+0x1e0`** |
| `__TEXT.__objc_stubs` | `0x1bb80` | `0x1bd00` | **`+0x180`** |
| `__TEXT.__objc_methname` | `0x2174e` | `0x2187d` | **`+0x12f`** |
| `__TEXT.__gcc_except_tab` | `0x47f8` | `0x48e4` | **`+0xec`** |
| `__DATA_CONST.__cfstring` | `0xef60` | `0xf040` | **`+0xe0`** |
| `__DATA.__objc_const` | `0x19a60` | `0x19af0` | **`+0x90`** |
| `__DATA_CONST.__const` | `0x32a0` | `0x3310` | **`+0x70`** |
| `__DATA.__objc_selrefs` | `0x8348` | `0x83a8` | **`+0x60`** |
| `__TEXT.__objc_methlist` | `0xdc8c` | `0xdce4` | **`+0x58`** |
| `__DATA.__objc_data` | `0x48f0` | `0x4940` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x3b58` | `0x3b88` | **`+0x30`** |
| `__TEXT.__objc_classname` | `0x18ea` | `0x18fa` | **`+0x10`** |
| `__DATA_CONST.__got` | `0xf58` | `0xf60` | **`+0x8`** |
| `__DATA_CONST.__objc_arraydata` | `0x940` | `0x948` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x738` | `0x740` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_ivar`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methtype`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-1871.40.52.0.0
+1871.40.61.0.0

+  - /System/Library/Frameworks/CoreSpotlight.framework/CoreSpotlight

-  Functions: 6148
-  Symbols:   1066
-  CStrings:  11064
+  Functions: 6162
+  Symbols:   1067
+  CStrings:  11098
Symbols:
+ _OBJC_CLASS_$_CSSearchableIndex
CStrings:
+ "%s - Failed to issue CoreSpotlight command %{public}@ - %{public}@"
+ "%s - Successfully issued CoreSpotlight command %{public}@"
+ "%s - alwaysRecognized: %d"
+ "%s - begin-turbo command failed, disabling turbo to be safe"
+ "%s - issuing CoreSpotlight command %{public}@"
+ "+[MSDSpotlightIndexHelper _runCoreSpotlightCommand:withTimeout:]_block_invoke"
+ "+[MSDSpotlightIndexHelper _startNewIndexingForMessages]"
+ "+[MSDSpotlightIndexHelper endTurbo]"
+ "+[MSDSpotlightIndexHelper startTurbo]"
+ "/var/mobile/Library/Preferences/com.apple.tvremoted.plist"
+ "AlwaysRecognized"
+ "Cannot refresh file download credential: no manifest info for the current content update"
+ "DisableAppleIntelligenceAssetsDownload"
+ "DisableAppleIntelligenceAssetsDownload is set, faking successful asset download"
+ "DisableAppleIntelligenceAssetsDownload is set, returning GM availability as YES"
+ "DisableAppleIntelligenceAssetsDownload is set, skipping purge of existing GreyMatter assets"
+ "MSDSpotlightIndexHelper"
+ "No manifest info available to identify the content update."
+ "Timed out while waiting for CoreSpotlight command %{public}@ to complete."
+ "_issueCommand:completionHandler:"
+ "_runCoreSpotlightCommand:withTimeout:"
+ "_startNewIndexingForMessages"
+ "begin-turbo"
+ "boolForKey:"
+ "defaultSearchableIndex"
+ "end-turbo"
+ "endTurbo"
+ "isAlwaysRecognized"
+ "job:com.apple.MobileSMS:NSFileProtectionCompleteUntilFirstUserAuthentication:2:0"
+ "manifestInfoForCredentialRefresh"
+ "refreshIndexingForMessagesWithCompletion:"
+ "setDemoModeRecognizeMyVoice:"
+ "setDemoModeSetupPresets:"
+ "startTurbo"
```
