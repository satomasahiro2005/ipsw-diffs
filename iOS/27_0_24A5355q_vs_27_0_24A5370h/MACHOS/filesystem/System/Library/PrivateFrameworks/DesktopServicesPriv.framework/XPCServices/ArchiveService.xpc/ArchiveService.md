## ArchiveService

> `/System/Library/PrivateFrameworks/DesktopServicesPriv.framework/XPCServices/ArchiveService.xpc/ArchiveService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x316d0` | `0x2d6cc` | **`-0x4004`** |
| `__TEXT.__gcc_except_tab` | `0x47c4` | `0x3ef0` | **`-0x8d4`** |
| `__TEXT.__objc_methname` | `0x2bbc` | `0x23d7` | **`-0x7e5`** |
| `__DATA.__objc_const` | `0xcc8` | `0x7b8` | **`-0x510`** |
| `__TEXT.__objc_methtype` | `0x101f` | `0xb8f` | **`-0x490`** |
| `__TEXT.__objc_stubs` | `0x21c0` | `0x1d80` | **`-0x440`** |
| `__TEXT.__objc_methlist` | `0x9e4` | `0x6c4` | **`-0x320`** |
| `__TEXT.__oslogstring` | `0x15d1` | `0x1313` | **`-0x2be`** |
| `__TEXT.__cstring` | `0x1d52` | `0x1b22` | **`-0x230`** |
| `__DATA_CONST.__cfstring` | `0x1300` | `0x10e0` | **`-0x220`** |
| `__TEXT.__unwind_info` | `0x1348` | `0x11c0` | **`-0x188`** |
| `__DATA_CONST.__const` | `0x1538` | `0x13c0` | **`-0x178`** |
| `__DATA.__objc_selrefs` | `0x9f8` | `0x890` | **`-0x168`** |
| `__DATA.__objc_data` | `0x310` | `0x1d0` | **`-0x140`** |
| `__DATA.__data` | `0x470` | `0x360` | **`-0x110`** |
| `__TEXT.__objc_classname` | `0x172` | `0xd2` | **`-0xa0`** |
| `__DATA_CONST.__got` | `0x4c8` | `0x488` | **`-0x40`** |
| `__DATA.__objc_ivar` | `0x50` | `0x30` | **`-0x20`** |
| `__DATA_CONST.__objc_classlist` | `0x40` | `0x20` | **`-0x20`** |
| `__DATA_CONST.__objc_protolist` | `0x40` | `0x20` | **`-0x20`** |
| `__TEXT.__const` | `0x8fa` | `0x8da` | **`-0x20`** |
| `__DATA_CONST.__objc_protorefs` | `0x18` | `0x8` | **`-0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x20` | `0x10` | **`-0x10`** |
| `__DATA.__common` | `0xc` | `0x18` | **`+0xc`** |
| `__DATA_CONST.__auth_ptr` | `0xf8` | `0xf0` | **`-0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`

### Other Changes

```diff

-1848.0.0.0.0
+1850.0.0.0.0

+  - /System/Library/PrivateFrameworks/DesktopServicesPriv.framework/DesktopServicesPriv

-  Functions: 753
-  Symbols:   757
-  CStrings:  943
+  Functions: 690
+  Symbols:   741
+  CStrings:  817
Symbols:
+ _CFDictionaryContainsKey
+ _CFDictionaryCreateMutableCopy
+ _CFDictionaryGetCount
+ _CFDictionaryRemoveValue
+ __ZN15TFileDescriptor10sCloseLockE
+ __ZN15TFileDescriptor15sCloseConditionE
+ __ZN15TFileDescriptor16sCloseGenerationE
+ __ZN15TFileDescriptor4OpenERKNSt3__112basic_stringIcNS0_11char_traitsIcEENS0_9allocatorIcEEEE9OpenFlags8SymlinksP16__CFFileSecuritybbb
+ __ZNSt3__118condition_variable10notify_allEv
- _APP_SANDBOX_READ
- _APP_SANDBOX_READ_WRITE
- _NSLocalizedRecoverySuggestionErrorKey
- _OBJC_CLASS_$_DSArchiveService
- _OBJC_CLASS_$_DSSandboxingURLWrapper
- _OBJC_CLASS_$_NSSet
- _OBJC_CLASS_$_NSXPCInterface
- _OBJC_CLASS_$_RBSAssertion
- _OBJC_CLASS_$_RBSDomainAttribute
- _OBJC_CLASS_$_RBSTarget
- _OBJC_METACLASS_$_DSArchiveService
- _OBJC_METACLASS_$_DSArchivedItemDescriptor
- _OBJC_METACLASS_$_DSQuarantine
- _OBJC_METACLASS_$_DSSandboxingURLWrapper
- _SANDBOX_EXTENSION_CANONICAL
- _SANDBOX_EXTENSION_NOFOLLOW
- _SANDBOX_EXTENSION_NO_REPORT
- __CFURLAttachSecurityScopeToFileURL
- __CFURLPromiseCopyPhysicalURL
- __CFURLPromiseSetPhysicalURL
- __ZN15TFileDescriptor4OpenEPKc9OpenFlags8SymlinksP16__CFFileSecuritybbb
- _objc_opt_respondsToSelector
- _objc_retainBlock
- _objc_setProperty_nonatomic_copy
- _sandbox_extension_issue_file
CStrings:
+ "SetResourcePropertiesForKeys successful after removing %{public}@"
- "<%@: %p url: %@ promiseURL: %@>"
- "@\"<DSArchiveServiceUnarchivingDelegate>\""
- "@\"NSData\""
- "@\"NSNumber\""
- "@\"NSProgress\"48@0:8@\"NSArray\"16Q24@\"NSURL\"32@?<v@?@\"NSURL\"@\"NSString\"@\"NSError\">40"
- "@\"NSProgress\"48@0:8@\"NSURL\"16@\"NSArray\"24@\"NSURL\"32@?<v@?@\"NSURL\"@\"NSError\">40"
- "@\"NSProgress\"48@0:8@\"NSURL\"16@\"NSString\"24@\"NSURL\"32@?<v@?@\"NSURL\"@\"NSError\">40"
- "@\"NSProgress\"56@0:8@\"NSURL\"16@\"NSArray\"24@\"NSURL\"32Q40@?<v@?@\"NSURL\"@\"NSError\">48"
- "@\"NSProgress\"60@0:8@\"NSArray\"16@\"NSString\"24B32Q36@\"NSURL\"44@?<v@?@\"NSURL\"@\"NSString\"@\"NSError\">52"
- "@\"NSProgress\"60@0:8@\"NSURL\"16@\"NSArray\"24B32@\"NSURL\"36Q44@?<v@?@\"NSURL\"@\"NSError\">52"
- "@\"NSProgress\"64@0:8@\"NSArray\"16@\"NSURL\"24Q32Q40@\"NSString\"48@?<v@?@\"NSURL\"@\"NSError\">56"
- "@\"NSProgress\"64@0:8@\"NSURL\"16@\"NSURL\"24Q32Q40@\"NSArray\"48@?<v@?@\"NSURL\"@\"NSError\">56"
- "@24@0:8@\"NSCoder\"16"
- "@36@0:8@16B24^@28"
- "@40@0:8@16r*24^@32"
- "@44@0:8@16r*24B32^@36"
- "@48@0:8@16@24@32@?40"
- "@48@0:8@16Q24@32@?40"
- "@56@0:8@16@24@32Q40@?48"
- "@60@0:8@16@24B32@36Q44@?52"
- "@60@0:8@16@24B32Q36@44@?52"
- "Archive Service archive assertion invalidated with error: %@"
- "Archive Service connection interrupted"
- "Archive Service unarchive assertion invalidated with error: %@"
- "ArchiveEnterPassword"
- "ArchiveServices archive operation"
- "ArchiveServices unarchive operation"
- "B32@0:8@16^@24"
- "BackgroundArchive"
- "Could not issue %s sandbox extension (%@)."
- "DSArchiveService"
- "DSArchiveServiceProtocol"
- "DSArchiveServiceStreamingInternal"
- "DSArchivedItemDescriptor"
- "DSQuarantine"
- "DSSandboxingURLWrapper"
- "NSCoding"
- "NSPromise"
- "NSPromiseScope"
- "NSSecureCoding"
- "NSURL"
- "NSURLScope"
- "T@\"<DSArchiveServiceUnarchivingDelegate>\",W,N,V_unarchivingDelegate"
- "T@\"NSData\",&,N,V_promiseScope"
- "T@\"NSData\",&,N,V_scope"
- "T@\"NSNumber\",C,N,V_fileSize"
- "T@\"NSString\",C,N,V_filePath"
- "T@\"NSString\",C,N,V_typeIdentifier"
- "T@\"NSURL\",&,N,V_promiseURL"
- "T@\"NSURL\",C,N,V_url"
- "TB,R"
- "_filePath"
- "_fileSize"
- "_promiseScope"
- "_promiseURL"
- "_scope"
- "_typeIdentifier"
- "_unarchivingDelegate"
- "_url"
- "acquireWithInvalidationHandler:"
- "applyDefaultQuarantineToURL:error:"
- "applyQuarantine:toURL:error:"
- "archiveItemsAtURLs: Couldn't get url wrapper for destination: %@"
- "archiveItemsAtURLs: destination doesn't exist or isn't a directory: %@"
- "archiveItemsAtURLs:toURL:options:compressionFormat:passphrase:completionHandler:"
- "archiveItemsWithURLs: Couldn't get url wrapper: %@"
- "archiveItemsWithURLs: destination is nil"
- "archiveItemsWithURLs: no urls"
- "archiveItemsWithURLs:compressionFormat:destinationFolderURL:completionHandler:"
- "archiveItemsWithURLs:passphrase:addToKeychain:compressionFormat:destinationFolderURL:completionHandler:"
- "attributeWithDomain:name:"
- "com.apple.ArchiveService"
- "couldn't issue sandbox extension %s for '%@': %s"
- "couldn't issue sandbox extension %s for '%@'; failed to get realpath for parent: %s"
- "couldn't issue sandbox extension %s for '%@'; failed to get realpath: %s"
- "currentProcess"
- "decodeObjectOfClass:forKey:"
- "dictionaryWithDictionary:"
- "encodeObject:forKey:"
- "encodeWithCoder:"
- "fileSize"
- "initWithCoder:"
- "initWithExplanation:target:attributes:"
- "initWithServiceName:"
- "initWithURL:extensionClass:report:error:"
- "interfaceWithProtocol:"
- "invalidate"
- "itemDescriptorsForItemAtURL: url is nil"
- "itemDescriptorsForItemAtURL:passphrase:completionHandler:"
- "itemDescriptorsForItemAtURL:passphrases:completionHandler:"
- "promiseScope"
- "promiseURL"
- "scope"
- "service:didReceiveArchivedItemsDescriptors:"
- "service:didReceiveArchivedItemsDescriptors:placeholderName:placeholderTypeIdentifier:"
- "setClasses:forSelector:argumentIndex:ofReply:"
- "setInterruptionHandler:"
- "setPromiseScope:"
- "setPromiseURL:"
- "setScope:"
- "setUnarchivingDelegate:"
- "setUrl:"
- "setWithArray:"
- "stringByDeletingLastPathComponent"
- "supportsSecureCoding"
- "unarchiveItemAtURL: Couldn't get url wrapper for destination: %@"
- "unarchiveItemAtURL: Couldn't get url wrapper for item: %@"
- "unarchiveItemAtURL: destination doesn't exist or isn't a directory: %@"
- "unarchiveItemAtURL: destination is nil"
- "unarchiveItemAtURL: url is nil"
- "unarchiveItemAtURL:passphrase:destinationFolderURL:completionHandler:"
- "unarchiveItemAtURL:passphrases:addToKeychain:destinationFolderURL:acceptedFormats:completionHandler:"
- "unarchiveItemAtURL:passphrases:destinationFolderURL:acceptedFormats:completionHandler:"
- "unarchiveItemAtURL:passphrases:destinationFolderURL:completionHandler:"
- "unarchiveItemAtURL:toURL:options:acceptedFormats:passphrases:completionHandler:"
- "unarchivingDelegate"
- "v24@0:8@\"NSCoder\"16"
- "v24@?0@\"NSArray\"8@\"NSError\"16"
- "v24@?0@\"RBSAssertion\"8@\"NSError\"16"
- "v32@?0@\"NSURL\"8@\"NSString\"16@\"NSError\"24"
- "v40@0:8@\"NSArray\"16@\"NSString\"24@\"NSString\"32"
- "v40@0:8@\"NSURL\"16@\"NSArray\"24@?<v@?@\"NSArray\"@\"NSError\">32"
- "v40@0:8@\"NSURL\"16@\"NSString\"24@?<v@?@\"NSArray\"@\"NSError\">32"
- "v40@0:8@16@24@32"
- "wrapperWithURL:extensionClass:error:"
- "wrapperWithURL:extensionClass:report:error:"
- "wrapperWithURL:readonly:error:"
```
