## libAppPatch.dylib

> `/usr/lib/libAppPatch.dylib`

### Other Changes

```diff

-1655.0.0.0.0
+1660.0.0.0.0
Functions:
~ _hardlink_copy_hierarchy : 5512 -> 5508
~ _realpath_parent_no_symlink : 436 -> 432
~ _read_string_to_terminator : 116 -> 124
~ _patchFile : 1604 -> 1600
~ _MICreateSHA256Digest : 1648 -> 1656
~ _MIApplyAppPatch : 3524 -> 3636
~ __FindBundles : 856 -> 852
~ __PushPathBuf : 108 -> 104
~ __PopPathBuf : 56 -> 52
~ _TraverseDirectoryWithPostTraversal : 2928 -> 2844
~ -[NSString(MobileInstallationAdditions) containsDotDotPathComponents] : 280 -> 276
~ _MIArrayContainsOnlyClass : 272 -> 268
~ _MIArrayFilteredToContainOnlyClass : 352 -> 348
~ ___124-[MIFileManager _stageURLByCopying:toItemName:inStagingDir:stagingMode:settingUID:gid:dataProtectionClass:hasSymlink:error:]_block_invoke : 2136 -> 2128
~ ___124-[MIFileManager _stageURLByCopying:toItemName:inStagingDir:stagingMode:settingUID:gid:dataProtectionClass:hasSymlink:error:]_block_invoke_2 : 68 -> 64
~ -[MIFileManager destinationOfSymbolicLinkAtURL:error:] : 360 -> 356
~ -[MIFileManager enumerateExternalVolumesWithBlock:] : 600 -> 620
~ -[MIFileManager captureStoreDataFromDirectory:toDirectory:doCopy:failureIsFatal:includeiTunesMetadata:withError:] : 860 -> 856
~ -[MIFileManager _validateSymlink:withStartingDepth:andEndingDepth:] : 452 -> 448
~ __CheckRealpathHasBasePrefix : 572 -> 568
~ -[MIFileManager debugDescriptionForItemAtURL:] : 1604 -> 1600
~ -[MIFileManager logAccessPermissionsForURL:] : 832 -> 828
~ _create_reordered_hidden_disk_header : 272 -> 280
```
