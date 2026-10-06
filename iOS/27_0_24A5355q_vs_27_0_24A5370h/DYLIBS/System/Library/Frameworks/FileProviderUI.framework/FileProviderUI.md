## FileProviderUI

> `/System/Library/Frameworks/FileProviderUI.framework/FileProviderUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc418` | `0xc3e8` | **`-0x30`** |

### Other Changes

```text
Functions:
~ +[FPUIManager actionsForProviderDomain:] : 1872 -> 1860
~ +[FPUIManager isAction:eligibleForItems:] : 584 -> 580
~ +[FPUIManager getExtensionRecordsForUseCase:uiExtensionRecord:nonUIExtensionRecord:forProviderDomain:] : 740 -> 736
~ +[FPUIManager extensionMatchingDictionaryForItems:fpProviderDomain:] : 424 -> 420
~ -[FPUIActionViewController viewDidLoad] : 760 -> 756
~ -[FPUIAuthenticationVolumeMountViewController setupTableViewSections] : 784 -> 780
~ -[FPUIAuthenticationLandingViewController _showRecentServersSectionWithRecentServers:rowAnimation:] : 696 -> 692
~ -[FPUIAuthenticationLandingViewController removeServerWithRepresentation:] : 436 -> 432
~ ___85-[FPUIAuthenticationCredentialsViewController _rowDescriptorForCredentialDescriptor:]_block_invoke_2 : 528 -> 524
~ -[FPUIAuthenticationCredentialsViewController setupTableViewSections] : 1360 -> 1356
```
