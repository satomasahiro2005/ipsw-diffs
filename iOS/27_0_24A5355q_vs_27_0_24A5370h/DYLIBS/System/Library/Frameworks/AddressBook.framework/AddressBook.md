## AddressBook

> `/System/Library/Frameworks/AddressBook.framework/AddressBook`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1a738` | `0x1a698` | **`-0xa0`** |
| `__TEXT.__cstring` | `0x1f62` | `0x1ef5` | **`-0x6d`** |
| `__TEXT.__oslogstring` | `0x36e` | `0x3db` | **`+0x6d`** |
| `__AUTH_CONST.__cfstring` | `0xfe0` | `0xfc0` | **`-0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x10d8` | `0x10d0` | **`-0x8`** |
| `__TEXT.__const` | `0xcc` | `0xd4` | **`+0x8`** |

### Other Changes

```diff

-12678.100.1.0.0
+12679.100.1.0.0
Functions:
~ +[ABSPerson vCardRepresentationForPeople:] : 548 -> 544
~ -[ABSConstantsMapping invertedMapping] : 384 -> 380
~ -[NSArray(ABSExtensions) abs_arrayByMappingTransform:] : 384 -> 380
~ -[ABSBulkFaultHandler batchOfPeopleInStorageMissingKeysIncluding:] : 860 -> 852
~ ___141-[CNMultiValuePropertyDescription(ABSExtentions) dictionaryBasedMultiValueTransformWithLabelMapping:inputKeys:destinationClass:valueMapping:]_block_invoke : 388 -> 384
~ -[ABSAddressBookContextStorage commitPendingChanges] : 544 -> 536
~ -[ABSAddressBook save:] : 3428 -> 3384
~ -[ABSAddressBook allPeople] : 836 -> 832
~ -[ABSAddressBook peopleWithCNIdentifiers:] : 1360 -> 1348
~ -[ABSAddressBook updatePeople:refetchingProperties:] : 744 -> 736
~ -[ABSAddressBook _resultRecordsFromFetchedCNImpls:mergedWithStorage:creationBlock:] : 648 -> 644
~ -[ABSAddressBook updateFetchingAllPropertiesForSources:] : 476 -> 472
~ -[ABSAddressBook allGroups] : 672 -> 668
~ -[ABSAddressBook updateFetchingAllPropertiesForGroups:] : 668 -> 660
~ -[ABSGroup updateAllValuesWithValuesFromGroup:] : 392 -> 388
~ _ABSCreateThumbnailDataAndCropRectFromImageData : 580 -> 548
~ _socialProfileFromURL : 1000 -> 996
CStrings:
+ "Thumbnail crop rect {{%f, %f}, {%f, %f}} origin y forced to 0 because it was negative (availableHeight = %d)"
- "Thumbnail crop rect {{%@, %@}, {%@, %@}} origin y forced to 0 because it was negative (availableHeight = %@)"
```
