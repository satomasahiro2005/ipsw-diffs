## BiomeStreams

> `/System/Library/PrivateFrameworks/BiomeStreams.framework/BiomeStreams`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3fc270` | `0x3f8cc8` | **`-0x35a8`** |
| `__AUTH_CONST.__objc_const` | `0x4deb0` | `0x4d450` | **`-0xa60`** |
| `__TEXT.__objc_methlist` | `0x1512c` | `0x14edc` | **`-0x250`** |
| `__AUTH.__objc_data` | `0x6a88` | `0x6998` | **`-0xf0`** |
| `__TEXT.__unwind_info` | `0xc430` | `0xc360` | **`-0xd0`** |
| `__TEXT.__oslogstring` | `0xbee0` | `0xbe40` | **`-0xa0`** |
| `__AUTH_CONST.__cfstring` | `0x9480` | `0x9400` | **`-0x80`** |
| `__TEXT.__cstring` | `0x31183` | `0x31123` | **`-0x60`** |
| `__DATA_CONST.__objc_selrefs` | `0x60b0` | `0x6078` | **`-0x38`** |
| `__DATA.__objc_ivar` | `0x1874` | `0x184c` | **`-0x28`** |
| `__DATA_CONST.__objc_classlist` | `0xea0` | `0xe88` | **`-0x18`** |
| `__DATA_CONST.__objc_superrefs` | `0x990` | `0x978` | **`-0x18`** |
| `__DATA_CONST.__got` | `0x1098` | `0x1088` | **`-0x10`** |

### Other Changes

```diff

-236.0.2.0.0
+239.0.2.0.0

-  Functions: 21961
-  Symbols:   44753
-  CStrings:  9180
+  Functions: 21920
+  Symbols:   44669
+  CStrings:  9174
Symbols:
+ -[BMDatabasesAccessDaemonDelegate prepareResource:withMode:inContainer:error:]
- +[BMMicroLocationTruthTagEvent eventWithData:dataVersion:]
- -[BMDatabasesAccessDaemonDelegate prepareResource:withMode:inContainer:]
- -[BMMicroLocationTruthTagEvent .cxx_destruct]
- -[BMMicroLocationTruthTagEvent absoluteTimestamp]
- -[BMMicroLocationTruthTagEvent clientBundleIdentifier]
- -[BMMicroLocationTruthTagEvent dataVersion]
- -[BMMicroLocationTruthTagEvent encodeAsProto]
- -[BMMicroLocationTruthTagEvent hash]
- -[BMMicroLocationTruthTagEvent initWithAbsoluteTimestamp:clientBundleIdentifier:truthTagIdentifier:recordingRequestIdentifier:]
- -[BMMicroLocationTruthTagEvent initWithProto:]
- -[BMMicroLocationTruthTagEvent initWithProtoData:]
- -[BMMicroLocationTruthTagEvent isEqual:]
- -[BMMicroLocationTruthTagEvent proto]
- -[BMMicroLocationTruthTagEvent recordingRequestIdentifier]
- -[BMMicroLocationTruthTagEvent serialize]
- -[BMMicroLocationTruthTagEvent truthTagIdentifier]
- -[BMMicroLocationTruthTagStream .cxx_destruct]
- -[BMMicroLocationTruthTagStream identifier]
- -[BMMicroLocationTruthTagStream init]
- -[BMMicroLocationTruthTagStream publisherFromStartTime:]
- -[BMMicroLocationTruthTagStream publisherWithStartTime:endTime:maxEvents:lastN:reversed:]
- -[BMMicroLocationTruthTagStream publisherWithStartTime:endTime:maxEvents:reversed:]
- -[BMMicroLocationTruthTagStream publisher]
- -[BMMicroLocationTruthTagStream source]
- -[BMPBMicroLocationTruthTagEvent .cxx_destruct]
- -[BMPBMicroLocationTruthTagEvent absoluteTimestamp]
- -[BMPBMicroLocationTruthTagEvent clientBundleId]
- -[BMPBMicroLocationTruthTagEvent copyTo:]
- -[BMPBMicroLocationTruthTagEvent copyWithZone:]
- -[BMPBMicroLocationTruthTagEvent description]
- -[BMPBMicroLocationTruthTagEvent dictionaryRepresentation]
- -[BMPBMicroLocationTruthTagEvent hasAbsoluteTimestamp]
- -[BMPBMicroLocationTruthTagEvent hasClientBundleId]
- -[BMPBMicroLocationTruthTagEvent hasRecordingRequestIdentifier]
- -[BMPBMicroLocationTruthTagEvent hasTruthTagIdentifier]
- -[BMPBMicroLocationTruthTagEvent hash]
- -[BMPBMicroLocationTruthTagEvent isEqual:]
- -[BMPBMicroLocationTruthTagEvent mergeFrom:]
- -[BMPBMicroLocationTruthTagEvent readFrom:]
- -[BMPBMicroLocationTruthTagEvent recordingRequestIdentifier]
- -[BMPBMicroLocationTruthTagEvent setAbsoluteTimestamp:]
- -[BMPBMicroLocationTruthTagEvent setClientBundleId:]
- -[BMPBMicroLocationTruthTagEvent setHasAbsoluteTimestamp:]
- -[BMPBMicroLocationTruthTagEvent setRecordingRequestIdentifier:]
- -[BMPBMicroLocationTruthTagEvent setTruthTagIdentifier:]
- -[BMPBMicroLocationTruthTagEvent truthTagIdentifier]
- -[BMPBMicroLocationTruthTagEvent writeTo:]
- OBJC_IVAR_$_BMPBMicroLocationTruthTagEvent._absoluteTimestamp
- OBJC_IVAR_$_BMPBMicroLocationTruthTagEvent._clientBundleId
- OBJC_IVAR_$_BMPBMicroLocationTruthTagEvent._has
- OBJC_IVAR_$_BMPBMicroLocationTruthTagEvent._recordingRequestIdentifier
- OBJC_IVAR_$_BMPBMicroLocationTruthTagEvent._truthTagIdentifier
- _$sSS3key_SaySSG5valuetSgWOe
- _BMPBMicroLocationTruthTagEventReadFrom
- _OBJC_CLASS_$_BMMicroLocationTruthTagEvent
- _OBJC_CLASS_$_BMMicroLocationTruthTagStream
- _OBJC_CLASS_$_BMPBMicroLocationTruthTagEvent
- _OBJC_IVAR_$_BMMicroLocationTruthTagEvent._absoluteTimestamp
- _OBJC_IVAR_$_BMMicroLocationTruthTagEvent._clientBundleIdentifier
- _OBJC_IVAR_$_BMMicroLocationTruthTagEvent._recordingRequestIdentifier
- _OBJC_IVAR_$_BMMicroLocationTruthTagEvent._truthTagIdentifier
- _OBJC_IVAR_$_BMMicroLocationTruthTagStream._stream
- _OBJC_METACLASS_$_BMMicroLocationTruthTagEvent
- _OBJC_METACLASS_$_BMMicroLocationTruthTagStream
- _OBJC_METACLASS_$_BMPBMicroLocationTruthTagEvent
- __OBJC_$_CLASS_METHODS_BMMicroLocationTruthTagEvent
- __OBJC_$_CLASS_PROP_LIST_BMMicroLocationTruthTagEvent
- __OBJC_$_INSTANCE_METHODS_BMMicroLocationTruthTagEvent
- __OBJC_$_INSTANCE_METHODS_BMMicroLocationTruthTagStream
- __OBJC_$_INSTANCE_METHODS_BMPBMicroLocationTruthTagEvent
- __OBJC_$_INSTANCE_VARIABLES_BMMicroLocationTruthTagEvent
- __OBJC_$_INSTANCE_VARIABLES_BMMicroLocationTruthTagStream
- __OBJC_$_INSTANCE_VARIABLES_BMPBMicroLocationTruthTagEvent
- __OBJC_$_PROP_LIST_BMMicroLocationTruthTagEvent
- __OBJC_$_PROP_LIST_BMMicroLocationTruthTagStream
- __OBJC_$_PROP_LIST_BMPBMicroLocationTruthTagEvent
- __OBJC_CLASS_PROTOCOLS_$_BMMicroLocationTruthTagEvent
- __OBJC_CLASS_PROTOCOLS_$_BMMicroLocationTruthTagStream
- __OBJC_CLASS_PROTOCOLS_$_BMPBMicroLocationTruthTagEvent
- __OBJC_CLASS_RO_$_BMMicroLocationTruthTagEvent
- __OBJC_CLASS_RO_$_BMMicroLocationTruthTagStream
- __OBJC_CLASS_RO_$_BMPBMicroLocationTruthTagEvent
- __OBJC_METACLASS_RO_$_BMMicroLocationTruthTagEvent
- __OBJC_METACLASS_RO_$_BMMicroLocationTruthTagStream
- __OBJC_METACLASS_RO_$_BMPBMicroLocationTruthTagEvent
CStrings:
- "%@: tried to initialize with a non-BMPBMicroLocationTruthTagEvent proto"
- "BMMicroLocationTruthTagEvent"
- "BMMicroLocationTruthTagEvent: Mismatched data version (%u != %u) cannot deserialize"
- "MicroLocationTruthTag"
- "recordingRequestIdentifier"
- "truthTagIdentifier"
```
