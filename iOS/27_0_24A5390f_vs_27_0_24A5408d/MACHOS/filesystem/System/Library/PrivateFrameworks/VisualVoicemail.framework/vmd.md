## vmd

> `/System/Library/PrivateFrameworks/VisualVoicemail.framework/vmd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__gcc_except_tab` | `0x10d1c` | `0x12e7c` | **`+0x2160`** |
| `__TEXT.__text` | `0xc0fa4` | `0xc2a08` | **`+0x1a64`** |
| `__TEXT.__unwind_info` | `0x49a0` | `0x4e40` | **`+0x4a0`** |
| `__DATA.__objc_const` | `0x12cf0` | `0x12ec0` | **`+0x1d0`** |
| `__TEXT.__oslogstring` | `0x16337` | `0x161b7` | **`-0x180`** |
| `__TEXT.__objc_methname` | `0x12d7f` | `0x12ed1` | **`+0x152`** |
| `__DATA_CONST.__const` | `0x34e0` | `0x33a8` | **`-0x138`** |
| `__DATA.__objc_data` | `0x1e10` | `0x1eb0` | **`+0xa0`** |
| `__TEXT.__objc_methtype` | `0x35da` | `0x3669` | **`+0x8f`** |
| `__DATA_CONST.__cfstring` | `0x5640` | `0x55c0` | **`-0x80`** |
| `__DATA.__bss` | `0x640` | `0x5e0` | **`-0x60`** |
| `__TEXT.__auth_stubs` | `0x18a0` | `0x1900` | **`+0x60`** |
| `__TEXT.__cstring` | `0x491a` | `0x48ba` | **`-0x60`** |
| `__TEXT.__objc_methlist` | `0x7e74` | `0x7ed4` | **`+0x60`** |
| `__DATA_CONST.__auth_got` | `0xc68` | `0xc98` | **`+0x30`** |
| `__TEXT.__objc_classname` | `0xe4a` | `0xe7a` | **`+0x30`** |
| `__TEXT.__objc_stubs` | `0xe2a0` | `0xe280` | **`-0x20`** |
| `__DATA.__objc_ivar` | `0x7d0` | `0x7e8` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x828` | `0x838` | **`+0x10`** |
| `__DATA_CONST.__objc_catlist` | `0x58` | `0x48` | **`-0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x2f8` | `0x308` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0x4820` | `0x4828` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x2c0` | `0x2c8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__init_offsets`
- `__TEXT.__swift5_typeref`

### Other Changes

```diff

-956.0.0.0.0
+958.0.0.0.0

-  Functions: 3605
-  Symbols:   709
-  CStrings:  5898
+  Functions: 3596
+  Symbols:   716
+  CStrings:  5903
Symbols:
+ _OBJC_CLASS_$_VMVoicemailData
+ _OBJC_CLASS_$_VMVoicemailDataContainer
+ _VVVerifierChangedNotification
+ __Z31VMVoicemailGetDataFileExtensionv
+ __Z32VMVoicemailDataPathForIdentifierP8NSStringm
+ __Z40VMVoicemailGetSummarizationFileExtensionv
+ __Z40VMVoicemailGetTranscriptionFileExtensionv
+ __Z41VMVoicemailSummarizationPathForIdentifierP8NSStringm
+ __Z41VMVoicemailTranscriptionPathForIdentifierP8NSStringm
- _OBJC_CLASS_$_VMMutableVoicemail
- _OBJC_CLASS_$_VMVoicemail
CStrings:
+ "\v"
+ "%s#E Failed to unarchive transcript for voicemail with identifier: %lu: %@"
+ "%s#I Queueing voicemail for retranscription: %lu"
+ "%s#I Transcription cancelled for voicemail with identifier: %lu."
+ "@\"VMSharedStore\""
+ "B24@0:8Q16"
+ "B24@?0@\"NSNumber\"8@\"NSDictionary\"16"
+ "T@\"NSString\",R,N,V_voicemailDirectoryPath"
+ "T@\"NSURL\",R,N,V_databaseFileURL"
+ "T@\"NSURL\",R,N,V_notificationDirectoryURL"
+ "T@\"NSURL\",R,N,V_voicemailDirectoryURL"
+ "T@\"VMSharedStore\",R,N,V_sharedStore"
+ "T@\"VMSharedStore\",W,N,V_voicemailStore"
+ "VMDCarrierAccountDataSource.mm"
+ "VMManager.mm"
+ "VMVoicemailDataFactory"
+ "VMVoicemailStorePaths"
+ "_databaseFileURL"
+ "_notificationDirectoryURL"
+ "_sharedStore"
+ "_voicemailDirectoryPath"
+ "_voicemailDirectoryURL"
+ "_voicemailStore"
+ "dataForRecord:forContexts:andIsoCodes:"
+ "dataWithContentsOfFile:"
+ "databaseFileURL"
+ "initWithVoicemails:"
+ "notificationDirectoryURL"
+ "prepareVoicemailsForMailboxType:read:limit:offset:completion:"
+ "processTranscriptForIdentifier:"
+ "q24@?0@\"VMVoicemailData\"8@\"VMVoicemailData\"16"
+ "setVoicemailStore:"
+ "sharedStore"
+ "sortUsingComparator:"
+ "unarchivedObjectOfClass:fromData:error:"
+ "v16@?0@\"VMVoicemailDataContainer\"8"
+ "v24@0:8@\"VMVoicemailDataContainer\"16"
+ "v24@0:8@?<v@?@\"VMVoicemailDataContainer\"@\"NSString\">16"
+ "v32@?0@\"NSNumber\"8Q16^B24"
+ "v48@0:8q16q24q32@?<v@?@\"VMVoicemailDataContainer\"@\"NSString\">40"
+ "v52@0:8q16B24q28q36@?<v@?@\"VMVoicemailDataContainer\"@\"NSString\">44"
+ "v56@0:8q16@24q32q40@?48"
+ "vmdb.shr"
+ "voicemailDirectoryPath"
+ "voicemailDirectoryURL"
+ "voicemailStore"
+ "voicemailsUpdated:basePath:"
- "\n"
- "%@\n"
- "%@%d.amr"
- "%@/"
- "%s#E Error unarchiving summarization metadata dictionary as file name empty."
- "%s#E Error unarchiving summarization metadata dictionary: %@"
- "%s#I Got previous attempts of: %@, will check to see if %lu is in it."
- "%s#I Noted in plist that we have attempted to transcribe voicemail with identifier: %lu."
- "%s#I Queueing voicemail for retranscription: %@"
- "%s#I Removing from plist that we have attempted to transcribe voicemail with identifier: %lu."
- "%s#I Returning NO since the task dictionary doesn't exist."
- "%s#I Transcription cancelled for voicemail: %@. Removing from attempted voicemails."
- ".amr"
- ".summary"
- ".transcript"
- "B24@?0@\"VMVoicemail\"8@\"NSDictionary\"16"
- "VMDCarrierAccountDataSource.m"
- "VMManager.m"
- "VMVoicemailTranscriptionPreviouslyAttemptedVoicemails"
- "alreadyAttemptedVoicemailTranscriptionForVoicemail:"
- "cancelAttemptedVoicemailTranscriptionForVoicemail:"
- "fullPath"
- "hasDirectoryPath"
- "messageForRecord:forContexts:andIsoCodes:"
- "orderedSet"
- "orderedSetWithCapacity:"
- "processTranscriptForVoicemail:"
- "q24@?0@\"VMVoicemail\"8@\"VMVoicemail\"16"
- "setAttemptedVoicemailTranscriptionForVoicemail:"
- "setSummarizationMetaDataURL:"
- "setTranscriptionURL:"
- "sortedArrayUsingComparator:"
- "summarizationMetaDataURL"
- "v16@?0@\"NSOrderedSet\"8"
- "v24@0:8@\"NSOrderedSet\"16"
- "v24@0:8@?<v@?@\"NSOrderedSet\">16"
- "v32@?0@\"VMVoicemail\"8Q16^B24"
- "v48@0:8q16q24q32@?<v@?@\"NSArray\">40"
- "v52@0:8q16B24q28q36@?<v@?@\"NSArray\">44"
- "vm.shared.store"
- "vmsg.cat"
- "voicemailsUpdated:"
```
