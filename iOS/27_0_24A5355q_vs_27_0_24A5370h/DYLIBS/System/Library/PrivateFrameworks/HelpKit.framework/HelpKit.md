## HelpKit

> `/System/Library/PrivateFrameworks/HelpKit.framework/HelpKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2ab4c` | `0x2ab28` | **`-0x24`** |
| `__TEXT.__const` | `0x2f8` | `0x308` | **`+0x10`** |

### Other Changes

```text
Functions:
~ -[HLPHelpBookController processData:formattedData:] : 3068 -> 3064
~ -[HLPHelpBookController dynamicServerSectionsForIdentifiers:level:parent:tocMap:] : 892 -> 884
~ +[HLPHelpViewController helpViewControllerWithURL:] : 1032 -> 1028
~ -[HLPHelpViewController setup] : 1200 -> 1196
~ -[HLPHelpSearchIndexController spotlightSearchResults] : 424 -> 420
~ -[HLPDataCacheController setLanguageCode:] : 624 -> 620
~ -[HLPDataCacheController reloadDataCache] : 1912 -> 1904
~ -[HLPDataCacheController cancelAllOriginSessionItems] : 420 -> 416
~ ___62-[HLPHelpTopicViewController _loadWithInfo:allowErrorMessage:]_block_invoke_2 : 1240 -> 1236
~ -[HLPHelpTopicViewController handleSupportFlowURL:] : 612 -> 608
~ -[HLPURLSessionTask didCompleteWithError:] : 364 -> 360
~ sub_2640d03e0 -> sub_26552d3ac : 172 -> 180
~ ___swift_closure_destructor : 128 -> 136
```
