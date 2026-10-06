## iconservicesagent

> `/System/Library/CoreServices/iconservicesagent`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5764` | `0x7988` | **`+0x2224`** |
| `__TEXT.__objc_stubs` | `0x14c0` | `0x19e0` | **`+0x520`** |
| `__TEXT.__objc_methname` | `0x1379` | `0x1856` | **`+0x4dd`** |
| `__DATA_CONST.__cfstring` | `0x660` | `0xa80` | **`+0x420`** |
| `__TEXT.__cstring` | `0x41d` | `0x7ce` | **`+0x3b1`** |
| `__DATA.__objc_const` | `0x8a8` | `0xa90` | **`+0x1e8`** |
| `__DATA.__objc_selrefs` | `0x688` | `0x7f0` | **`+0x168`** |
| `__TEXT.__oslogstring` | `0xb82` | `0xcb9` | **`+0x137`** |
| `__TEXT.__objc_methlist` | `0x434` | `0x54c` | **`+0x118`** |
| `__DATA.__data` | `0x120` | `0x1e0` | **`+0xc0`** |
| `__TEXT.__objc_methtype` | `0x3ae` | `0x449` | **`+0x9b`** |
| `__DATA_CONST.__const` | `0x268` | `0x300` | **`+0x98`** |
| `__TEXT.__auth_stubs` | `0x5d0` | `0x650` | **`+0x80`** |
| `__TEXT.__gcc_except_tab` | `0x158` | `0x1c8` | **`+0x70`** |
| `__DATA.__objc_data` | `0x190` | `0x1e0` | **`+0x50`** |
| `__DATA_CONST.__got` | `0x190` | `0x1d8` | **`+0x48`** |
| `__DATA_CONST.__auth_got` | `0x2f8` | `0x338` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x1b8` | `0x1f8` | **`+0x40`** |
| `__TEXT.__objc_classname` | `0xac` | `0xd8` | **`+0x2c`** |
| `__DATA.__bss` | `—` | `0x10` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x54` | `0x64` | **`+0x10`** |
| `__DATA_CONST.__objc_protolist` | `0x18` | `0x28` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x28` | `0x30` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x20` | `0x28` | **`+0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__const`

### Other Changes

```diff

-775.0.3.0.0
+779.0.0.0.0

+  - /System/Library/PrivateFrameworks/DiagnosticExtensions.framework/DiagnosticExtensions

-  Functions: 109
-  Symbols:   155
-  CStrings:  434
+  Functions: 132
+  Symbols:   172
+  CStrings:  533
Symbols:
+ _NSUnderlyingErrorKey
+ _OBJC_CLASS_$_DEArchiver
+ _OBJC_CLASS_$_IFImage
+ _OBJC_CLASS_$_ISStoreIndex
+ _OBJC_CLASS_$_NSData
+ _OBJC_CLASS_$_NSDate
+ _OBJC_CLASS_$_NSDateFormatter
+ _OBJC_CLASS_$_NSMutableString
+ _OBJC_CLASS_$_NSNull
+ _dispatch_get_global_queue
+ _dispatch_once
+ _objc_autoreleasePoolPop
+ _objc_retainAutoreleaseReturnValue
+ _objc_retain_x24
+ _objc_retain_x28
+ _objc_setProperty_nonatomic_copy
+ _os_variant_has_internal_content
CStrings:
+ "\t%s\n"
+ "\nIndex contents:\n"
+ "\nTotal file count: %d\nCache items count: %d\nMax item index: %d\n"
+ "/private/var/tmp/IconServicesDiagnostics"
+ "<%@: icon=%@, descriptor=%@>"
+ "@\"IFColor\""
+ "@\"NSData\""
+ "@24@0:8@\"NSCoder\"16"
+ "CGImage"
+ "CustomerBuild"
+ "DEArchiver failed to create .tgz"
+ "DiagnosticExtensions.framework is not available on this system"
+ "Diagnostics archive collection requires an internal build"
+ "Failed to archive color item. Error: %@. Reference icon: %@"
+ "Failed to archive persistentID item. Error: %@. Reference icon: %@"
+ "Failed to copy cache contents"
+ "Failed to create archive directory"
+ "Failed to create bundle directory"
+ "Failed to unarchive persistentID for unit %@. Error: %@"
+ "Failed to unarchive tint color for unit %@. Error: %@"
+ "Failed to write dump.txt"
+ "Failed to write image for UUID %@"
+ "ISStoreMetadataItem"
+ "Icon cache not found"
+ "IconServicesDebugArchive_%@"
+ "Image encoding had errors during diagnostics archive: %@"
+ "Image encoding had errors during minimal diagnostics archive: %@"
+ "Index"
+ "Minimal diagnostics archive collection requires an internal build"
+ "NSCoding"
+ "NSSecureCoding"
+ "Removing store unit: %@ for item %@"
+ "Removing store unit: %@ with color: %@ for item %@"
+ "Store"
+ "Store contents:\n"
+ "Store index path: %s\nStore path: %s\n"
+ "T@\"IFColor\",&,N,V_tintColor"
+ "T@\"NSData\",&,N,V_persistentID"
+ "T@\"NSString\",C,N,V_descriptorDescription"
+ "T@\"NSString\",C,N,V_iconDescription"
+ "TB,R"
+ "URLByAppendingPathComponent:"
+ "_descriptorDescription"
+ "_iconDescription"
+ "_persistentID"
+ "_tintColor"
+ "appendFormat:"
+ "appendString:"
+ "archiveDirectoryAt:deleteOriginal:progressHandler:"
+ "collectDiagnosticsArchiveCompressed:withReply:"
+ "collectMinimalDiagnosticsArchiveWithReply:"
+ "copyItemAtURL:toURL:error:"
+ "createDirectoryAtURL:withIntermediateDirectories:attributes:error:"
+ "dataWithContentsOfURL:"
+ "date"
+ "decodeObjectOfClass:forKey:"
+ "descriptionForItem:index:filenames:"
+ "descriptorDescription"
+ "diagnostics archive collection"
+ "dump.txt"
+ "en_US_POSIX"
+ "encodeObject:forKey:"
+ "encodeWithCoder:"
+ "enumerateValuesWithBock:"
+ "enumeratorAtPath:"
+ "fileExistsAtPath:"
+ "iconDescription"
+ "images"
+ "initWithCoder:"
+ "initWithData:uuid:"
+ "initWithStoreFileURL:"
+ "initWithUUIDString:"
+ "isInternalBuild"
+ "isdata"
+ "lastPathComponent"
+ "localeWithLocaleIdentifier:"
+ "minimal diagnostics archive collection"
+ "nil cache or destination"
+ "null"
+ "pathExtension"
+ "persistentID"
+ "png"
+ "registerPersistentIdentifiers:forUnit:icon:descriptor:"
+ "registerTintColor:forUnit:icon:descriptor:"
+ "setDateFormat:"
+ "setDescriptorDescription:"
+ "setIconDescription:"
+ "setLocale:"
+ "setPersistentID:"
+ "setTintColor:"
+ "string"
+ "stringByAppendingPathComponent:"
+ "stringByAppendingPathExtension:"
+ "stringByDeletingPathExtension"
+ "stringFromDate:"
+ "supportsSecureCoding"
+ "v24@0:8@\"NSCoder\"16"
+ "v24@0:8@?<v@?@\"NSURL\"@\"NSError\">16"
+ "v24@?0r^{?=[16C]{?=dd}dI[16C][16C]{?=[16C]Q[16C]}B[16C]}8^B16"
+ "v28@0:8B16@?20"
+ "v28@0:8B16@?<v@?@\"NSURL\"@\"NSError\">20"
+ "v48@0:8@16@24@32@40"
+ "writeToURL:"
+ "writeToURL:atomically:"
+ "writeToURL:atomically:encoding:error:"
+ "yyyy.MM.dd_HH-mm-ss-z"
- "Failed to archive color. Error: %@"
- "Failed to unarchive color. Error: %@"
- "Removing store unit: %@"
- "Removing store unit: %@ with color: %@"
- "registerRecordIdentifiers:asSourceForUnit:"
- "registerTintColor:forUnit:"
- "v32@0:8@16@24"
```
