## LiveFS

> `/System/Library/PrivateFrameworks/LiveFS.framework/LiveFS`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__gcc_except_tab` | `0xd5c` | `0xd60` | **`+0x4`** |
| `__TEXT.__text` | `0x19f9c` | `0x19f98` | **`-0x4`** |

### Other Changes

```diff

-971.0.0.0.5
+974.0.1.0.2
Functions:
~ -[LiveFSXattrCache insertEntryForData:forName:] : 716 -> 712
~ +[FSKitDiskArbHelper DAMountFSKitVolume:deviceName:mountPoint:volumeName:auditToken:mountOptions:] : 1984 -> 2012
~ +[FSKitDiskArbHelper DAMountUserFSVolume:deviceName:mountPoint:volumeName:auditToken:mountOptions:] : 1872 -> 1880
~ -[LiveFSVolumeClient updatesDoneFor:] : 464 -> 460
~ -[LiveFSAppleDoubleManager scrubDirectoryNamed:inDirectory:] : 1264 -> 1260
~ -[LiveFSAppleDoubleManager clearCache] : 336 -> 332
~ -[LiveFSAppleDouble swapFileHeader:] : 96 -> 112
~ -[LiveFSAppleDouble loadAttrHeader] : 436 -> 440
~ -[LiveFSAppleDouble loadADHeader] : 2644 -> 2640
~ ___33-[LiveFSAppleDouble loadADHeader]_block_invoke.115 : 244 -> 252
~ -[LiveFSAppleDouble valueForXattrNamed:posixError:] : 876 -> 880
~ -[LiveFSAppleDouble setValue:forXattrNamed:how:] : 3256 -> 3196
~ -[LiveFSAppleDouble _removeXattrNamed:allowADFileRemoval:] : 3244 -> 3248
~ -[LiveFSAppleDouble allXattrNamesAndPosixError:] : 492 -> 496
```
