## DeviceManagementTools

> `/System/Library/PrivateFrameworks/DeviceManagementTools.framework/DeviceManagementTools`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x165f4` | `0x165bc` | **`-0x38`** |

### Other Changes

```diff

-83.0.0.0.0
+85.0.0.0.0
Functions:
~ -[DMTDisallowedPayloadTypesValidator validateProfile:error:] : 480 -> 476
~ -[DMTAllowedPayloadTypesValidator validateProfile:error:] : 648 -> 644
~ ___61+[DMTConfigurationPayloadBase payloadSubclassesByPayloadType]_block_invoke : 756 -> 752
~ -[DMTWiFiAutoJoinValidator validateProfile:error:] : 348 -> 344
~ -[DMTWiFiCertificateReferencesValidator validateProfile:error:] : 636 -> 632
~ -[DMTWiFiPayload initWithDictionary:error:] : 968 -> 960
~ __DMTErrorDescriptionsForKey : 364 -> 360
~ -[DMTConfigurationProfile payloadsByType] : 468 -> 464
~ -[DMTConfigurationProfile payloadsByUUID] : 404 -> 400
~ -[DMTConfigurationProfile payloadsOfType:] : 356 -> 352
~ -[DMTConfigurationProfile payloadsOfTypes:] : 360 -> 356
~ -[DMTConfigurationProfile validateWithValidators:error:] : 288 -> 284
~ -[DMTConfigurationProfile initWithDictionary:error:] : 760 -> 756
```
