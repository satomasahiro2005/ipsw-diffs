## SampleAnalysis

> `/System/Library/PrivateFrameworks/SampleAnalysis.framework/SampleAnalysis`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x105ecc` | `0x105f14` | **`+0x48`** |
| `__TEXT.__gcc_except_tab` | `0x20600` | `0x20604` | **`+0x4`** |

### Other Changes

```text
Functions:
~ _print_io_histograms : 968 -> 976
~ -[SASampleStore _parseKCDataTaskContainer:timestampOfSample:sampleIndex:sharedCaches:frameIterator:primaryDataIsKPerf:addStaticInfoOnly:kperfState:ktraceDataUnavailable:taskUniquePidsInThisSample:taskPidsInThisSample:importanceDonations:rPidForJetsamCoalitionId:port_label_info_array:vmrls:exclaveInfo:] : 18152 -> 18200
~ -[SAModel(Serialization) addSelfToBuffer:bufferLength:withCompletedSerializationDictionary:] : 1492 -> 1496
~ -[SATask(Serialization) populateReferencesUsingBuffer:bufferLength:andDeserializationDictionary:andDataBufferDictionary:] : 5104 -> 5116
```
