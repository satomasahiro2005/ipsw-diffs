## ContactsPersistence

> `/System/Library/PrivateFrameworks/ContactsPersistence.framework/ContactsPersistence`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4c368` | `0x4a9bc` | **`-0x19ac`** |
| `__TEXT.__objc_methlist` | `0x5474` | `0x522c` | **`-0x248`** |
| `__AUTH_CONST.__const` | `0x1320` | `0x11a0` | **`-0x180`** |
| `__TEXT.__oslogstring` | `0x341a` | `0x32ca` | **`-0x150`** |
| `__AUTH_CONST.__cfstring` | `0x4160` | `0x4020` | **`-0x140`** |
| `__TEXT.__cstring` | `0x318f` | `0x306f` | **`-0x120`** |
| `__TEXT.__unwind_info` | `0x16a0` | `0x15e8` | **`-0xb8`** |
| `__DATA.__bss` | `0x11e0` | `0x1130` | **`-0xb0`** |
| `__DATA_CONST.__objc_selrefs` | `0x3260` | `0x31f0` | **`-0x70`** |
| `__DATA_CONST.__const` | `0x1c50` | `0x1c08` | **`-0x48`** |
| `__DATA_CONST.__got` | `0x820` | `0x828` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x218` | `0x210` | **`-0x8`** |

### Other Changes

```diff

-3835.100.6.0.0
+3837.100.1.0.0

-  Functions: 2341
-  Symbols:   4235
-  CStrings:  861
+  Functions: 2265
+  Symbols:   4164
+  CStrings:  843
Symbols:
+ +[CNCDContact os_log]
+ _ABCDCompareByOrderingIndexWithPrimaryFirst_block_invoke_6.cn_once_object_10
+ _ABCDCompareByOrderingIndexWithPrimaryFirst_block_invoke_6.cn_once_token_10
+ ___21+[CNCDContact os_log]_block_invoke
+ _preferredNameSortDescriptors.onceToken
+ _preferredNameSortDescriptors.sPreferredNameSortDescriptors
+ _preferredPhotoSortDescriptors.onceToken
+ _preferredPhotoSortDescriptors.sPreferredPhotoSortDescriptors
- +[ABCDContactDate isLimitedLabeledValue]
- +[ABCDContactDate limitedPropertyName]
- +[ABCDContactDate limitedStringPropertyKeys]
- +[ABCDGroup limitedClassName]
- +[ABCDGroup limitedStringPropertyKeys]
- +[ABCDRelatedName isLimitedLabeledValue]
- +[ABCDRelatedName limitedPropertyName]
- +[ABCDRelatedName limitedStringPropertyKeys]
- +[ABCDSocialProfile isLimitedLabeledValue]
- +[ABCDSocialProfile limitedPropertyName]
- +[ABCDSocialProfile limitedStringPropertyKeys]
- +[CNCDContact limitedClassName]
- +[CNCDContact limitedLabelValuePropertyKeys]
- +[CNCDContact limitedStringPropertyKeys]
- +[CNCDEmailAddress isLimitedLabeledValue]
- +[CNCDEmailAddress limitedPropertyName]
- +[CNCDEmailAddress limitedStringPropertyKeys]
- +[CNCDMessagingAddress isLimitedLabeledValue]
- +[CNCDMessagingAddress limitedPropertyName]
- +[CNCDMessagingAddress limitedStringPropertyKeys]
- +[CNCDOwnedObject isLimitedLabeledValue]
- +[CNCDOwnedObject limitedPropertyName]
- +[CNCDOwnedObject limitedStringPropertyKeys]
- +[CNCDOwnedObject os_log]
- +[CNCDPhoneNumber isLimitedLabeledValue]
- +[CNCDPhoneNumber limitedPropertyName]
- +[CNCDPhoneNumber limitedStringPropertyKeys]
- +[CNCDPostalAddress isLimitedLabeledValue]
- +[CNCDPostalAddress limitedPropertyName]
- +[CNCDPostalAddress limitedStringPropertyKeys]
- +[CNCDRecord limitedClassName]
- +[CNCDRecord limitedLabelValuePropertyKeys]
- +[CNCDRecord limitedStringPropertyKeys]
- +[CNCDURLAddress isLimitedLabeledValue]
- +[CNCDURLAddress limitedPropertyName]
- +[CNCDURLAddress limitedStringPropertyKeys]
- -[CNCDMessagingAddress prepareForDeletion]
- -[CNCDMessagingAddress validateValue:forKey:error:]
- -[CNCDOwnedObject limitStringValue:forKey:]
- -[CNCDOwnedObject validateForInsert:]
- -[CNCDOwnedObject validateForUpdate:]
- -[CNCDOwnedObject validateValue:forKey:error:]
- -[CNCDRecord limitLabeledValues:forKey:]
- -[CNCDRecord limitString:forKey:]
- -[CNCDRecord validateValue:forKey:error:]
- _ABCDCompareByOrderingIndexWithPrimaryFirst_block_invoke_6.cn_once_object_14
- _ABCDCompareByOrderingIndexWithPrimaryFirst_block_invoke_6.cn_once_token_14
- __OBJC_$_CLASS_METHODS_ABCDContactDate
- __OBJC_$_CLASS_METHODS_ABCDRelatedName
- __OBJC_$_CLASS_METHODS_CNCDEmailAddress
- __OBJC_$_CLASS_METHODS_CNCDPhoneNumber
- __OBJC_$_CLASS_METHODS_CNCDPostalAddress
- __OBJC_$_CLASS_METHODS_CNCDURLAddress
- ___25+[CNCDOwnedObject os_log]_block_invoke
- ___38+[ABCDGroup limitedStringPropertyKeys]_block_invoke
- ___40+[CNCDContact limitedStringPropertyKeys]_block_invoke
- ___40-[CNCDRecord limitLabeledValues:forKey:]_block_invoke
- ___40-[CNCDRecord limitLabeledValues:forKey:]_block_invoke_2
- ___43+[CNCDURLAddress limitedStringPropertyKeys]_block_invoke
- ___44+[ABCDContactDate limitedStringPropertyKeys]_block_invoke
- ___44+[ABCDRelatedName limitedStringPropertyKeys]_block_invoke
- ___44+[CNCDContact limitedLabelValuePropertyKeys]_block_invoke
- ___44+[CNCDPhoneNumber limitedStringPropertyKeys]_block_invoke
- ___45+[CNCDEmailAddress limitedStringPropertyKeys]_block_invoke
- ___46+[ABCDSocialProfile limitedStringPropertyKeys]_block_invoke
- ___46+[CNCDPostalAddress limitedStringPropertyKeys]_block_invoke
- ___49+[CNCDMessagingAddress limitedStringPropertyKeys]_block_invoke
- ___block_descriptor_32_e25_B16?0"ABCDOwnedObject"8l
- ___block_descriptor_40_e8_32s_e25_v16?0"ABCDOwnedObject"8ls32l8
- _limitedLabelValuePropertyKeys.cn_once_object_3
- _limitedLabelValuePropertyKeys.cn_once_token_3
- _limitedStringPropertyKeys.cn_once_object_0
- _limitedStringPropertyKeys.cn_once_object_2
- _limitedStringPropertyKeys.cn_once_token_0
- _limitedStringPropertyKeys.cn_once_token_2
- _preferredNameSortDescriptors.cn_once_object_0
- _preferredNameSortDescriptors.cn_once_token_0
- _preferredPhotoSortDescriptors.cn_once_object_1
- _preferredPhotoSortDescriptors.cn_once_token_1
CStrings:
- "B16@?0@\"ABCDOwnedObject\"8"
- "CNCDOwnedObject"
- "CNCDRecord"
- "CNContact"
- "CNContact.URLAddresses"
- "CNContact.contactRelations"
- "CNContact.dates"
- "CNContact.emailAddresses"
- "CNContact.instantMessageAddresses"
- "CNContact.phoneNumbers"
- "CNContact.postalAddresses"
- "CNContact.socialProfiles"
- "CNGroup"
- "In some %{public}@, expected to limit the %{public}@ string length, but this property was not a string."
- "In some %{public}@, expected to limit the number of %{public}@ labeled values, but this property was not a set."
- "In some %{public}@, limited the %{public}@ string length"
- "In some %{public}@, limited the number of %{public}@ labeled values"
- "v16@?0@\"ABCDOwnedObject\"8"
```
