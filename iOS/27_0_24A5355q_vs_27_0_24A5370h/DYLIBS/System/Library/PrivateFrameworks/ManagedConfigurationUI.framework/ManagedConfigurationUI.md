## ManagedConfigurationUI

> `/System/Library/PrivateFrameworks/ManagedConfigurationUI.framework/ManagedConfigurationUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x18b40` | `0x18b1c` | **`-0x24`** |

### Other Changes

```diff

-105.0.0.0.0
+107.0.0.0.0
Functions:
~ __CreateHexStringForBytes : 220 -> 240
~ -[MCCertificatePickerController setRowToSelect] : 524 -> 520
~ -[MCInstallProfileViewController dealloc] : 340 -> 336
~ -[MCUIAppSigner _updateUntrustedAppCountsForBundleIDs:] : 412 -> 408
~ -[MCUIAppSigner isTrusted] : 352 -> 348
~ +[MCUIAppSigner enterpriseAppSignersWithOutDeveloperAppSigners:] : 1644 -> 1640
~ +[MCUIAppSignerUninstallerUtilities _provisioningProfileUUIDsForAppSigner:] : 368 -> 364
~ ___38-[MCUIAppSignerViewController _verify]_block_invoke : 496 -> 492
~ -[MCUIListController _showAccountDetailsPaneWithUsername:completion:] : 452 -> 448
~ -[MCUIMCSpecifierProvider specifiers] : 1460 -> 1448
~ +[MCUISettingsWatchManager hasAnyYorktownEnrolledWatches] : 376 -> 372
~ -[MCUISpecifierProvider _specifiersForProfiles:singularHeader:pluralHeaader:profilesInstalled:] : 484 -> 480
~ -[MCURLListenerListController _pushProfileDetailsForProfileWithID:withCompletion:] : 644 -> 640
```
