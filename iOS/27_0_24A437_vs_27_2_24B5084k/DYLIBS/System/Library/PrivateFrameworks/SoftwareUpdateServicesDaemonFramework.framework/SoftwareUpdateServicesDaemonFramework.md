## SoftwareUpdateServicesDaemonFramework

> `/System/Library/PrivateFrameworks/SoftwareUpdateServicesDaemonFramework.framework/SoftwareUpdateServicesDaemonFramework`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x62df4` | `0x632d0` | **`+0x4dc`** |
| `__TEXT.__cstring` | `0x110f8` | `0x111d1` | **`+0xd9`** |
| `__AUTH_CONST.__cfstring` | `0x8c80` | `0x8d40` | **`+0xc0`** |
| `__TEXT.__objc_methlist` | `0x51a4` | `0x51e4` | **`+0x40`** |
| `__AUTH_CONST.__objc_const` | `0x83d0` | `0x8400` | **`+0x30`** |
| `__DATA_CONST.__objc_selrefs` | `0x3e38` | `0x3e68` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x1a60` | `0x1a70` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0x7a8` | `0x79c` | **`-0xc`** |
| `__DATA.__objc_ivar` | `0x354` | `0x358` | **`+0x4`** |

### Other Changes

```diff

-1112.0.3.0.0
+1114.40.9.0.0

-  Functions: 2142
-  Symbols:   3435
-  CStrings:  1507
+  Functions: 2149
+  Symbols:   3443
+  CStrings:  1514
Symbols:
+ -[SUAutoInstallManager _queue_scheduleAutoUpdateBannerIfNeededForReason:]
+ -[SUPolicyFactory _resolvedPersonalizationServerURL]
+ -[SUPolicyFactory personalizationServerURL]
+ -[SUPolicyFactory setPersonalizationServerURL:]
+ -[SUScanner _shouldRescanForScanOptions:previousScanError:hasDoneSplatScan:reason:]
+ GCC_except_table90
+ _OBJC_IVAR_$_SUPolicyFactory._personalizationServerURL
+ ___43-[SUPolicyFactory personalizationServerURL]_block_invoke
+ ___47-[SUPolicyFactory setPersonalizationServerURL:]_block_invoke
- GCC_except_table89
CStrings:
+ "\t"
+ "%@: install tonight is scheduled and download is done. Displaying banner"
+ "%@: no passcode set. Displaying banner"
+ "%s - will rescan for updates, reason = '%@', with options %@"
+ "%s: T&Cs already accepted"
+ "Auto update consented"
+ "Not performing space check for updatesDownloadable since there is an in-progress/finished download"
+ "Operation auto-consented"
+ "Overriding Tatsu personalization server URL for this update: %@"
+ "Will not rescan for Splat -- disabled by Preferences"
+ "Will not rescan for updates"
+ "Will rescan for Splat updates"
+ "[DDM] Fall back to a scan for Splat updates"
+ "[DDM] Fall back to a scan for regular updates"
- "%s - [DDM] Fall back to a scan for Splat updates"
- "%s - [DDM] Fall back to a scan for regular updates"
- "%s - will not rescan for Splat -- disabled by default"
- "%s - will rescan for updates with options %@"
- "Auto update consented and no passcode set. Displaying banner"
- "Install tonight is scheduled and download is done. Displaying banner"
- "Not performing space check since there is an in-progress download"
```
