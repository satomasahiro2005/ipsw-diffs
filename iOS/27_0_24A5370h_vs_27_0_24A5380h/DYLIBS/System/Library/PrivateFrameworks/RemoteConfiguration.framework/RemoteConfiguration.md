## RemoteConfiguration

> `/System/Library/PrivateFrameworks/RemoteConfiguration.framework/RemoteConfiguration`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2bf84` | `0x2c030` | **`+0xac`** |
| `__DATA_CONST.__objc_selrefs` | `0x1b68` | `0x1b70` | **`+0x8`** |

### Other Changes

```diff

-422.0.0.0.0
+423.0.0.0.0
Functions:
~ -[RCConfigurationManager _isValidConfigurationResource:configurationSettings:allowedToReachEndpoint:cachePolicy:] : 1024 -> 1040
~ +[RCEndpointResponseProcessing parseEndpointResponseDict:parsingError:configurationSettings:maxAge:loggingPrefix:completion:] : 2168 -> 2256
~ ___183-[RCConfigurationManager _processConfigurationCompletionWithResources:configurationSettings:processedConfigurationDataByRequestKey:processedTreatmentIDs:processedSegmentSetIDs:error:]_block_invoke : 808 -> 876
```
