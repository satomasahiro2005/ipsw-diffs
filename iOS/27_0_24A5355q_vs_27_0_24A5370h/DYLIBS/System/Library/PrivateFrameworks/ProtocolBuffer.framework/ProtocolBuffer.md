## ProtocolBuffer

> `/System/Library/PrivateFrameworks/ProtocolBuffer.framework/ProtocolBuffer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x13358` | `0x13348` | **`-0x10`** |

### Other Changes

```diff

-323.30.4.30.1
+325.30.6.4.1

-  Symbols:   803
+  Symbols:   805
Symbols:
+ __ZNSt12length_errorC1B9fqe220106EPKc
+ __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__118basic_stringstreamIcNS_11char_traitsIcEENS_9allocatorIcEEEC1B9fqe220106Ev
+ __ZNSt3__120__throw_length_errorB9fqe220106EPKc
+ __ZNSt3__124__put_character_sequenceB9fqe220106IcNS_11char_traitsIcEEEERNS_13basic_ostreamIT_T0_EES7_PKS4_m
+ __ZNSt3__16vectorIhNS_9allocatorIhEEE20__throw_length_errorB9fqe220106Ev
+ _objc_retain_x25
+ _objc_retain_x28
- __ZNSt12length_errorC1B9fqe220100EPKc
- __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE20__throw_length_errorB9fqe220100Ev
- __ZNSt3__118basic_stringstreamIcNS_11char_traitsIcEENS_9allocatorIcEEEC1B9fqe220100Ev
- __ZNSt3__120__throw_length_errorB9fqe220100EPKc
- __ZNSt3__124__put_character_sequenceB9fqe220100IcNS_11char_traitsIcEEEERNS_13basic_ostreamIT_T0_EES7_PKS4_m
- __ZNSt3__16vectorIhNS_9allocatorIhEEE20__throw_length_errorB9fqe220100Ev
Functions:
~ _PBUnknownFieldAdd : 1812 -> 1816
~ _PBHashBytes : 264 -> 280
~ ____textFormatData_block_invoke : 500 -> 504
~ __textFormatDictionary : 536 -> 532
~ __textFormat : 768 -> 764
~ _PBRepeatedUInt32NSArray : 168 -> 164
~ -[PBTextWriter _printLine:format:] : 436 -> 432
~ -[PBTextWriter _writeResult:forProperty:bracePrefix:] : 812 -> 808
~ -[PBTextWriter _write:] : 4348 -> 4308
~ _PBReaderReadVarIntBuf : 108 -> 120
~ -[NSString(VariableSupport) _pb_fixCase:] : 304 -> 308
~ -[PBTextReader _readObject:] : 2888 -> 2880
~ +[PBStreamWriter writeProtoBuffers:toFile:] : 568 -> 564
~ -[PBMessageStreamReader nextMessage] : 428 -> 432
~ _PBRepeatedDoubleNSArray : 168 -> 164
~ _PBRepeatedFloatNSArray : 168 -> 164
~ _PBRepeatedInt32NSArray : 168 -> 164
~ _PBRepeatedInt64NSArray : 168 -> 164
~ _PBRepeatedUInt64NSArray : 168 -> 164
~ _PBRepeatedBOOLNSArray : 168 -> 164
~ -[_PBProperty _parseStructDefinition:] : 1108 -> 1104
~ +[_PBProperty getValidPropertiesForType:withCache:] : 3352 -> 3440
~ __ZN2PB6Reader9placeMarkERNS_10ReaderMarkE : 304 -> 300
~ __ZN2PB6Reader4readERNSt3__112basic_stringIcNS1_11char_traitsIcEENS1_9allocatorIcEEEE : 372 -> 368
~ __ZN2PB6Reader4readERNSt3__16vectorIhNS1_9allocatorIhEEEE : 568 -> 560
~ __ZN2PB6Reader4readERNS_4DataE : 360 -> 356
~ __ZN2PB6Reader4skipEjhi : 876 -> 864
~ -[PBSessionRequester _serializePayload:] : 1100 -> 1092
~ ___28-[PBSessionRequester _start]_block_invoke : 1256 -> 1252
~ -[PBSessionRequester _newSessionWithDelegate:delegateQueue:connectionProperties:] : 508 -> 504
```
