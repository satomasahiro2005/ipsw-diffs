## TrialProto

> `/System/Library/PrivateFrameworks/TrialProto.framework/TrialProto`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5a6d8` | `0x5a548` | **`-0x190`** |
| `__TEXT.__unwind_info` | `0x1fc0` | `0x1fc8` | **`+0x8`** |

### Other Changes

```diff

-501.0.0.0.0
+505.0.0.0.0
Functions:
~ -[TRIPBEnumDescriptor textFormatNameForValue:] : 900 -> 896
~ _ReadRawVarint32FromData : 232 -> 244
~ -[TRIPBMessage internalClear:] : 912 -> 904
~ +[TRIPBDescriptor allocDescriptorForClass:rootClass:file:fields:fieldCount:storageSize:flags:] : 276 -> 284
~ -[TRIPBMessage mergeFromCodedInputStream:extensionRegistry:] : 1388 -> 1384
~ +[TRIPBMessage resolveInstanceMethod:] : 1348 -> 1332
~ _TRIPBClassHasSel : 136 -> 132
~ -[TRIPBMessage copyFieldsInto:zone:descriptor:] : 1092 -> 1088
~ _CloneExtensionMap : 672 -> 668
~ _TRIPBDictionaryReadEntry : 588 -> 584
~ -[TRIPBMessage isInitialized] : 928 -> 924
~ -[TRIPBOneofDescriptor initWithName:fields:] : 356 -> 352
~ -[TRIPBEnumDescriptor getValue:forEnumTextFormatName:] : 180 -> 176
~ _TRIPBTextFormatForUnknownFieldSet : 1020 -> 1012
~ _TRIPBWriteExtensionValueToOutputStream : 1136 -> 1120
~ _TRIPBComputeExtensionSerializedSizeIncludingTag : 676 -> 664
~ -[TRILogTreatment dictionaryRepresentation] : 648 -> 644
~ -[TRILogTreatment writeTo:] : 624 -> 612
~ -[TRILogTreatment copyWithZone:] : 660 -> 652
~ -[TRILogTreatment mergeFrom:] : 608 -> 600
~ _TRIPBMessageDropUnknownFieldsRecursively : 1388 -> 1380
~ ___AppendTextFormatForMapMessageField_block_invoke : 408 -> 404
~ ___AppendTextFormatForMapMessageField_block_invoke_2 : 548 -> 544
~ _TRIPBAutocreatedArrayModified : 444 -> 440
~ _TRIPBAutocreatedDictionaryModified : 464 -> 460
~ ___29-[TRIPBMessage isInitialized]_block_invoke : 320 -> 316
~ -[TRIPBMessage writeField:toCodedOutputStream:] : 3960 -> 3904
~ -[TRIPBMessage writeExtensionsToCodedOutputStream:range:] : 324 -> 320
~ -[TRIPBMessage mergeFrom:] : 1780 -> 1772
~ -[TRIPBMessage isEqual:] : 816 -> 784
~ -[TRIPBMessage hash] : 516 -> 496
~ -[TRIPBMessage serializedSize] : 4052 -> 4032
~ -[TRIPBUnknownFieldSet sortedFields] : 464 -> 460
~ -[TRIPBUnknownFieldSet getTags:] : 208 -> 216
~ -[TRIPBDescriptor setupOneofs:count:firstHasIndex:] : 580 -> 576
~ -[TRIPBDescriptor setupExtraTextInfo:] : 296 -> 292
~ -[TRIPBDescriptor fieldWithNumber:] : 248 -> 244
~ -[TRIPBDescriptor fieldWithName:] : 268 -> 264
~ -[TRIPBDescriptor oneofWithName:] : 268 -> 264
~ -[TRIPBOneofDescriptor fieldWithNumber:] : 248 -> 244
~ -[TRIPBOneofDescriptor fieldWithName:] : 268 -> 264
~ _TRIPBFieldTag : 60 -> 56
~ _TRIPBFieldAlternateTag : 156 -> 152
~ -[TRIPBEnumDescriptor calcValueNameOffsets] : 200 -> 196
~ -[TRIPBExtensionDescriptor wireType] : 44 -> 40
~ -[TRIPBExtensionDescriptor alternateWireType] : 136 -> 132
~ +[TRIFactorLevel(NamespaceHashing) hashForFactorLevels:] : 484 -> 480
~ -[TRIPBUnknownField copyWithZone:] : 420 -> 416
~ -[TRIPBUnknownField serializedSize] : 832 -> 824
~ -[TRIPBUnknownField writeAsMessageSetExtensionToOutput:] : 256 -> 252
~ -[TRIPBUnknownField serializedSizeAsMessageSetExtension] : 268 -> 264
~ -[TRIPBUnknownField description] : 720 -> 712
~ -[TRIPBUnknownField mergeFromField:] : 540 -> 536
~ _ExtensionForName : 408 -> 416
~ -[TRIPBInt32Array description] : 204 -> 200
~ -[TRIPBInt32Array enumerateValuesWithOptions:usingBlock:] : 204 -> 200
~ -[TRIPBInt32Array insertValue:atIndex:] : 244 -> 252
~ -[TRIPBInt32Array removeValueAtIndex:] : 204 -> 212
~ -[TRIPBUInt32Array description] : 204 -> 200
~ -[TRIPBUInt32Array enumerateValuesWithOptions:usingBlock:] : 204 -> 200
~ -[TRIPBUInt32Array insertValue:atIndex:] : 244 -> 252
~ -[TRIPBUInt32Array removeValueAtIndex:] : 204 -> 212
~ -[TRIPBInt64Array description] : 204 -> 200
~ -[TRIPBInt64Array enumerateValuesWithOptions:usingBlock:] : 204 -> 200
~ -[TRIPBInt64Array insertValue:atIndex:] : 244 -> 252
~ -[TRIPBInt64Array removeValueAtIndex:] : 204 -> 212
~ -[TRIPBUInt64Array description] : 204 -> 200
~ -[TRIPBUInt64Array enumerateValuesWithOptions:usingBlock:] : 204 -> 200
~ -[TRIPBUInt64Array insertValue:atIndex:] : 244 -> 252
~ -[TRIPBUInt64Array removeValueAtIndex:] : 204 -> 212
~ -[TRIPBFloatArray description] : 188 -> 184
~ -[TRIPBFloatArray enumerateValuesWithOptions:usingBlock:] : 204 -> 200
~ -[TRIPBFloatArray insertValue:atIndex:] : 244 -> 252
~ -[TRIPBFloatArray removeValueAtIndex:] : 204 -> 212
~ -[TRIPBDoubleArray description] : 204 -> 200
~ -[TRIPBDoubleArray enumerateValuesWithOptions:usingBlock:] : 204 -> 200
~ -[TRIPBDoubleArray insertValue:atIndex:] : 244 -> 252
~ -[TRIPBDoubleArray removeValueAtIndex:] : 204 -> 212
~ -[TRIPBBoolArray description] : 184 -> 180
~ -[TRIPBBoolArray enumerateValuesWithOptions:usingBlock:] : 204 -> 200
~ -[TRIPBBoolArray insertValue:atIndex:] : 240 -> 244
~ -[TRIPBBoolArray removeValueAtIndex:] : 200 -> 204
~ -[TRIPBEnumArray description] : 204 -> 200
~ -[TRIPBEnumArray enumerateRawValuesWithOptions:usingBlock:] : 204 -> 200
~ -[TRIPBEnumArray enumerateValuesWithOptions:usingBlock:] : 280 -> 300
~ -[TRIPBEnumArray insertRawValue:atIndex:] : 244 -> 252
~ -[TRIPBEnumArray removeValueAtIndex:] : 204 -> 212
~ -[TRIPBEnumArray insertValue:atIndex:] : 304 -> 312
~ -[TRIPBUInt32UInt32Dictionary initWithUInt32s:forKeys:count:] : 200 -> 208
~ -[TRIPBUInt32Int32Dictionary initWithInt32s:forKeys:count:] : 200 -> 208
~ -[TRIPBUInt32UInt64Dictionary initWithUInt64s:forKeys:count:] : 200 -> 208
~ -[TRIPBUInt32Int64Dictionary initWithInt64s:forKeys:count:] : 200 -> 208
~ -[TRIPBUInt32BoolDictionary initWithBools:forKeys:count:] : 200 -> 208
~ -[TRIPBUInt32FloatDictionary initWithFloats:forKeys:count:] : 200 -> 208
~ -[TRIPBUInt32DoubleDictionary initWithDoubles:forKeys:count:] : 200 -> 208
~ -[TRIPBUInt32EnumDictionary initWithValidationFunction:rawValues:forKeys:count:] : 224 -> 232
~ -[TRIPBUInt32ObjectDictionary initWithObjects:forKeys:count:] : 248 -> 252
~ -[TRIPBUInt32ObjectDictionary isInitialized] : 244 -> 240
~ -[TRIPBInt32UInt32Dictionary initWithUInt32s:forKeys:count:] : 200 -> 208
~ -[TRIPBInt32Int32Dictionary initWithInt32s:forKeys:count:] : 200 -> 208
~ -[TRIPBInt32UInt64Dictionary initWithUInt64s:forKeys:count:] : 200 -> 208
~ -[TRIPBInt32Int64Dictionary initWithInt64s:forKeys:count:] : 200 -> 208
~ -[TRIPBInt32BoolDictionary initWithBools:forKeys:count:] : 200 -> 208
~ -[TRIPBInt32FloatDictionary initWithFloats:forKeys:count:] : 200 -> 208
~ -[TRIPBInt32DoubleDictionary initWithDoubles:forKeys:count:] : 200 -> 208
~ -[TRIPBInt32EnumDictionary initWithValidationFunction:rawValues:forKeys:count:] : 224 -> 232
~ -[TRIPBInt32ObjectDictionary initWithObjects:forKeys:count:] : 248 -> 252
~ -[TRIPBInt32ObjectDictionary isInitialized] : 244 -> 240
~ -[TRIPBUInt64UInt32Dictionary initWithUInt32s:forKeys:count:] : 200 -> 208
~ -[TRIPBUInt64Int32Dictionary initWithInt32s:forKeys:count:] : 200 -> 208
~ -[TRIPBUInt64UInt64Dictionary initWithUInt64s:forKeys:count:] : 200 -> 208
~ -[TRIPBUInt64Int64Dictionary initWithInt64s:forKeys:count:] : 200 -> 208
~ -[TRIPBUInt64BoolDictionary initWithBools:forKeys:count:] : 200 -> 208
~ -[TRIPBUInt64FloatDictionary initWithFloats:forKeys:count:] : 200 -> 208
~ -[TRIPBUInt64DoubleDictionary initWithDoubles:forKeys:count:] : 200 -> 208
~ -[TRIPBUInt64EnumDictionary initWithValidationFunction:rawValues:forKeys:count:] : 224 -> 232
~ -[TRIPBUInt64ObjectDictionary initWithObjects:forKeys:count:] : 248 -> 252
~ -[TRIPBUInt64ObjectDictionary isInitialized] : 244 -> 240
~ -[TRIPBInt64UInt32Dictionary initWithUInt32s:forKeys:count:] : 200 -> 208
~ -[TRIPBInt64Int32Dictionary initWithInt32s:forKeys:count:] : 200 -> 208
~ -[TRIPBInt64UInt64Dictionary initWithUInt64s:forKeys:count:] : 200 -> 208
~ -[TRIPBInt64Int64Dictionary initWithInt64s:forKeys:count:] : 200 -> 208
~ -[TRIPBInt64BoolDictionary initWithBools:forKeys:count:] : 200 -> 208
~ -[TRIPBInt64FloatDictionary initWithFloats:forKeys:count:] : 200 -> 208
~ -[TRIPBInt64DoubleDictionary initWithDoubles:forKeys:count:] : 200 -> 208
~ -[TRIPBInt64EnumDictionary initWithValidationFunction:rawValues:forKeys:count:] : 224 -> 232
~ -[TRIPBInt64ObjectDictionary initWithObjects:forKeys:count:] : 248 -> 252
~ -[TRIPBInt64ObjectDictionary isInitialized] : 244 -> 240
~ -[TRIPBStringUInt32Dictionary initWithUInt32s:forKeys:count:] : 240 -> 248
~ -[TRIPBStringInt32Dictionary initWithInt32s:forKeys:count:] : 240 -> 248
~ -[TRIPBStringUInt64Dictionary initWithUInt64s:forKeys:count:] : 240 -> 248
~ -[TRIPBStringInt64Dictionary initWithInt64s:forKeys:count:] : 240 -> 248
~ -[TRIPBStringBoolDictionary initWithBools:forKeys:count:] : 240 -> 248
~ -[TRIPBStringFloatDictionary initWithFloats:forKeys:count:] : 240 -> 248
~ -[TRIPBStringDoubleDictionary initWithDoubles:forKeys:count:] : 240 -> 248
~ -[TRIPBStringEnumDictionary initWithValidationFunction:rawValues:forKeys:count:] : 264 -> 272
~ -[TRIPBBoolUInt32Dictionary initWithUInt32s:forKeys:count:] : 136 -> 140
~ -[TRIPBBoolUInt32Dictionary initWithDictionary:] : 140 -> 124
~ -[TRIPBBoolUInt32Dictionary getUInt32:forKey:] : 40 -> 36
~ -[TRIPBBoolUInt32Dictionary computeSerializedSizeAsField:] : 220 -> 212
~ -[TRIPBBoolUInt32Dictionary writeToCodedOutputStream:asField:] : 212 -> 204
~ -[TRIPBBoolUInt32Dictionary addEntriesFromDictionary:] : 108 -> 92
~ -[TRIPBBoolInt32Dictionary initWithInt32s:forKeys:count:] : 136 -> 140
~ -[TRIPBBoolInt32Dictionary initWithDictionary:] : 140 -> 124
~ -[TRIPBBoolInt32Dictionary getInt32:forKey:] : 40 -> 36
~ -[TRIPBBoolInt32Dictionary computeSerializedSizeAsField:] : 220 -> 212
~ -[TRIPBBoolInt32Dictionary writeToCodedOutputStream:asField:] : 212 -> 204
~ -[TRIPBBoolInt32Dictionary addEntriesFromDictionary:] : 108 -> 92
~ -[TRIPBBoolUInt64Dictionary initWithUInt64s:forKeys:count:] : 136 -> 140
~ -[TRIPBBoolUInt64Dictionary initWithDictionary:] : 140 -> 124
~ -[TRIPBBoolUInt64Dictionary getUInt64:forKey:] : 40 -> 36
~ -[TRIPBBoolUInt64Dictionary computeSerializedSizeAsField:] : 216 -> 208
~ -[TRIPBBoolUInt64Dictionary writeToCodedOutputStream:asField:] : 208 -> 200
~ -[TRIPBBoolUInt64Dictionary addEntriesFromDictionary:] : 108 -> 92
~ -[TRIPBBoolInt64Dictionary initWithInt64s:forKeys:count:] : 136 -> 140
~ -[TRIPBBoolInt64Dictionary initWithDictionary:] : 140 -> 124
~ -[TRIPBBoolInt64Dictionary getInt64:forKey:] : 40 -> 36
~ -[TRIPBBoolInt64Dictionary computeSerializedSizeAsField:] : 220 -> 212
~ -[TRIPBBoolInt64Dictionary writeToCodedOutputStream:asField:] : 212 -> 204
~ -[TRIPBBoolInt64Dictionary addEntriesFromDictionary:] : 108 -> 92
~ -[TRIPBBoolBoolDictionary initWithBools:forKeys:count:] : 136 -> 144
~ -[TRIPBBoolBoolDictionary initWithDictionary:] : 140 -> 124
~ -[TRIPBBoolBoolDictionary getBool:forKey:] : 40 -> 36
~ -[TRIPBBoolBoolDictionary computeSerializedSizeAsField:] : 196 -> 192
~ -[TRIPBBoolBoolDictionary writeToCodedOutputStream:asField:] : 204 -> 196
~ -[TRIPBBoolBoolDictionary addEntriesFromDictionary:] : 108 -> 92
~ -[TRIPBBoolFloatDictionary initWithFloats:forKeys:count:] : 136 -> 140
~ -[TRIPBBoolFloatDictionary initWithDictionary:] : 140 -> 124
~ -[TRIPBBoolFloatDictionary computeSerializedSizeAsField:] : 196 -> 192
~ -[TRIPBBoolFloatDictionary writeToCodedOutputStream:asField:] : 200 -> 192
~ -[TRIPBBoolFloatDictionary addEntriesFromDictionary:] : 108 -> 92
~ -[TRIPBBoolDoubleDictionary initWithDoubles:forKeys:count:] : 136 -> 140
~ -[TRIPBBoolDoubleDictionary initWithDictionary:] : 140 -> 124
~ -[TRIPBBoolDoubleDictionary getDouble:forKey:] : 40 -> 36
~ -[TRIPBBoolDoubleDictionary computeSerializedSizeAsField:] : 196 -> 192
~ -[TRIPBBoolDoubleDictionary writeToCodedOutputStream:asField:] : 200 -> 192
~ -[TRIPBBoolDoubleDictionary addEntriesFromDictionary:] : 108 -> 92
~ -[TRIPBBoolObjectDictionary initWithObjects:forKeys:count:] : 212 -> 216
~ -[TRIPBBoolObjectDictionary setTRIPBGenericValue:forTRIPBGenericValueKey:] : 60 -> 68
~ -[TRIPBBoolObjectDictionary deepCopyWithZone:] : 132 -> 124
~ -[TRIPBBoolObjectDictionary computeSerializedSizeAsField:] : 264 -> 260
~ -[TRIPBBoolObjectDictionary writeToCodedOutputStream:asField:] : 192 -> 188
~ -[TRIPBBoolObjectDictionary addEntriesFromDictionary:] : 168 -> 160
~ -[TRIPBBoolObjectDictionary removeObjectForKey:] : 44 -> 48
~ -[TRIPBBoolEnumDictionary initWithValidationFunction:rawValues:forKeys:count:] : 164 -> 168
~ -[TRIPBBoolEnumDictionary initWithDictionary:] : 160 -> 144
~ -[TRIPBBoolEnumDictionary getEnum:forKey:] : 104 -> 100
~ -[TRIPBBoolEnumDictionary getRawValue:forKey:] : 40 -> 36
~ -[TRIPBBoolEnumDictionary computeSerializedSizeAsField:] : 220 -> 212
~ -[TRIPBBoolEnumDictionary writeToCodedOutputStream:asField:] : 212 -> 204
~ -[TRIPBBoolEnumDictionary addRawEntriesFromDictionary:] : 108 -> 92
~ -[TRIDenormalizedEvent dictionaryRepresentation] : 1140 -> 1128
~ -[TRIDenormalizedEvent writeTo:] : 740 -> 728
~ -[TRIDenormalizedEvent copyWithZone:] : 844 -> 832
~ -[TRIDenormalizedEvent mergeFrom:] : 808 -> 796
~ -[TRISystemDimensions writeTo:] : 832 -> 828
~ -[TRISystemDimensions copyWithZone:] : 1000 -> 996
~ -[TRISystemDimensions mergeFrom:] : 836 -> 832
~ -[TRIPBCodedOutputStream writeStringArray:values:] : 256 -> 252
~ -[TRIPBCodedOutputStream writeMessageArray:values:] : 256 -> 252
~ -[TRIPBCodedOutputStream writeBytesArray:values:] : 256 -> 252
~ -[TRIPBCodedOutputStream writeGroupArray:values:] : 256 -> 252
~ -[TRIPBCodedOutputStream writeUnknownGroupArray:values:] : 256 -> 252
```
