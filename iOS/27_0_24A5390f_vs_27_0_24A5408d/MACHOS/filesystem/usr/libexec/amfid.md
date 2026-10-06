## amfid

> `/usr/libexec/amfid`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x211bc` | `0x17cbc` | **`-0x9500`** |
| `__TEXT.__cstring` | `0x2090` | `0x1687` | **`-0xa09`** |
| `__TEXT.__objc_methname` | `0x1596` | `0xd49` | **`-0x84d`** |
| `__DATA_CONST.__cfstring` | `0xdc0` | `0x600` | **`-0x7c0`** |
| `__TEXT.__objc_stubs` | `0x14e0` | `0xd80` | **`-0x760`** |
| `__DATA.__objc_const` | `0x9c0` | `0x5e0` | **`-0x3e0`** |
| `__TEXT.__objc_methlist` | `0x5f4` | `0x344` | **`-0x2b0`** |
| `__DATA.__objc_selrefs` | `0x670` | `0x478` | **`-0x1f8`** |
| `__TEXT.__objc_methtype` | `0x432` | `0x31d` | **`-0x115`** |
| `__DATA.__objc_data` | `0x310` | `0x220` | **`-0xf0`** |
| `__TEXT.__unwind_info` | `0x710` | `0x638` | **`-0xd8`** |
| `__DATA_CONST.__const` | `0xb60` | `0xa90` | **`-0xd0`** |
| `__TEXT.__const` | `0xb2c` | `0xa84` | **`-0xa8`** |
| `__TEXT.__auth_stubs` | `0x15f0` | `0x1560` | **`-0x90`** |
| `__TEXT.__objc_classname` | `0xeb` | `0x9e` | **`-0x4d`** |
| `__DATA_CONST.__auth_got` | `0xb10` | `0xac8` | **`-0x48`** |
| `__TEXT.__oslogstring` | `0x15f5` | `0x1632` | **`+0x3d`** |
| `__DATA.__objc_ivar` | `0x34` | `0x8` | **`-0x2c`** |
| `__DATA_CONST.__got` | `0x3b0` | `0x398` | **`-0x18`** |
| `__DATA_CONST.__objc_classlist` | `0x40` | `0x28` | **`-0x18`** |
| `__DATA_CONST.__objc_intobj` | `0x30` | `0x48` | **`+0x18`** |
| `__DATA_CONST.__objc_superrefs` | `0x18` | `0x8` | **`-0x10`** |
| `__DATA_CONST.__auth_ptr` | `0x1e8` | `0x1f0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__init_offsets`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-1171.0.3.0.0
+1171.0.12.0.0

+  - /usr/lib/libDetachedCertificates.dylib
+  - /usr/lib/libDetachedCertificatesLookup.dylib

-  Functions: 482
-  Symbols:   561
-  CStrings:  715
+  Functions: 384
+  Symbols:   545
+  CStrings:  547
Symbols:
+ _OBJC_CLASS_$_DetachedCertificatesLookup
+ _os_lockdown_mode_enabled
+ _os_variant_has_factory_content
- _NSLocalizedDescriptionKey
- _OBJC_CLASS_$_NSArray
- _OBJC_CLASS_$_NSMutableArray
- _ccder_blob_decode_bitstring
- _ccder_blob_decode_tag
- _ccder_blob_decode_tl
- _ccder_blob_decode_uint64
- _ccder_encode_constructed_tl
- _ccder_encode_raw_octet_string
- _ccder_encode_uint64
- _ccder_sizeof
- _ccder_sizeof_raw_octet_string
- _ccder_sizeof_uint64
- _ccsha1_di
- _ccsha224_di
- _ccsha256_di
- _ccsha384_di
- _ccsha512_di
- _objc_autorelease
CStrings:
+ "%s: lockdown interface not supported (non-UI && no lockdown)"
+ "com.apple.amfi.developer_mode_state"
+ "developer_app_executions"
+ "developer_mode_state"
+ "lockdown_mode_state"
+ "numberWithBool:"
- "&"
- "*40@0:8@16*24*32"
- "/System/Library/Security/DetachedCertificates.der"
- "/System/Library/Security/PQCCertificates.der"
- "@\"NSData\""
- "@\"NSMutableArray\""
- "@\"NSMutableDictionary\""
- "@24@0:8^@16"
- "@32@0:8@16@24"
- "@32@0:8@16^@24"
- "@40@0:8@16@24@32"
- "@40@0:8@16@24^@32"
- "B32@0:8@16^@24"
- "B40@0:8@16@24^@32"
- "B40@0:8^{?=*Q}16^@24^@32"
- "B40@0:8^{?=Q{?=*Q}}16^@24^@32"
- "B48@0:8@16@24@32^@40"
- "CTGetAKIDFromCertificate failed for %@: %d"
- "CTGetSKIDFromCertificate failed for %@: %d"
- "Compatibility version mismatch: self=%llu, other=%llu"
- "DetachedCertificateEntry"
- "DetachedCertificates.der"
- "DetachedCertificatesFile"
- "DetachedCertificatesLookup"
- "DetachedCertificatesLookupErrorDomain"
- "Error draining certificate entry fields"
- "Error iterating sequence: %d"
- "Expected INTEGER for compatibility_version, tag=0x%llx"
- "Expected INTEGER for version, tag=0x%llx"
- "Expected OCTET STRING for certificate"
- "Expected OCTET STRING for skid"
- "Expected SEQUENCE for certificate entry, got 0x%llx"
- "Expected SEQUENCE for certificate list"
- "Expected [0] EXPLICIT tag, got 0x%llx"
- "Expected [1] EXPLICIT tag, got 0x%llx"
- "Failed to allocate encoding buffer"
- "Failed to decode akid"
- "Failed to decode certificate"
- "Failed to decode certificate sequence: %d"
- "Failed to decode root DER: %d"
- "Failed to decode skid"
- "Failed to encode [0] EXPLICIT tag"
- "Failed to encode [1] EXPLICIT tag"
- "Failed to encode [2] EXPLICIT tag"
- "Failed to encode compatibility_version"
- "Failed to encode intermediate certificate entry"
- "Failed to encode intermediate certificates SEQUENCE"
- "Failed to encode leaf certificate entry"
- "Failed to encode leaf certificates SEQUENCE"
- "Failed to encode root SEQUENCE"
- "Failed to encode root certificate entry"
- "Failed to encode root certificates SEQUENCE"
- "Failed to encode version"
- "Failed to extract SKID from CMS blob: %d"
- "Failed to get compatibility_version element"
- "Failed to get intermediate certificates element"
- "Failed to get leaf certificates element"
- "Failed to get version element"
- "Failed to parse compatibility_version integer"
- "Failed to parse version integer"
- "Failed to write to path: %@"
- "File does not exist at path: %@"
- "Intermediate AKID does not match root SKID for leaf at index %lu"
- "Intermediate certificate's AKID does not match root certificate's SKID"
- "Invalid parameters: executablePath and cmsData are required"
- "Invalid parameters: executablePath and skid are required"
- "Leaf AKID does not match intermediate SKID for leaf at index %lu"
- "Leaf certificate does not have an AKID"
- "Leaf certificate's AKID does not match intermediate certificate's SKID"
- "No detached certificates found for executable: %@"
- "No intermediate certificate found for leaf at index %lu"
- "No intermediate certificate found matching leaf's AKID"
- "No leaf certificate found with the specified SKID"
- "Q"
- "Q24@0:8@16"
- "Root element is not a SEQUENCE, tag=0x%llx"
- "System/Library/Security/DetachedCertificates.der"
- "T@\"NSData\",R,N,V_akid"
- "T@\"NSData\",R,N,V_certificate"
- "T@\"NSData\",R,N,V_skid"
- "T@\"NSMutableArray\",&,N,V_intermediateCertificates"
- "T@\"NSMutableArray\",&,N,V_leafCertificates"
- "T@\"NSMutableArray\",&,N,V_rootCertificates"
- "T@\"NSMutableDictionary\",&,N,V_intermediateSKIDMap"
- "T@\"NSMutableDictionary\",&,N,V_leafSKIDMap"
- "T@\"NSMutableDictionary\",&,N,V_rootSKIDMap"
- "TQ,N,V_compatibilityVersion"
- "TQ,N,V_version"
- "Unsupported compatibility_version: %llu (max supported: 1)"
- "_akid"
- "_certificate"
- "_compatibilityVersion"
- "_intermediateCertificates"
- "_intermediateSKIDMap"
- "_leafCertificates"
- "_leafSKIDMap"
- "_rootCertificates"
- "_rootSKIDMap"
- "_skid"
- "_version"
- "addCertificateChainWithLeaf:intermediate:error:"
- "addCertificateChainWithLeaf:intermediate:root:error:"
- "addCertificateChainsWithLeaves:parents:error:"
- "addObject:"
- "addObjectsFromArray:"
- "akid"
- "array"
- "arrayWithCapacity:"
- "arrayWithObjects:count:"
- "certificate"
- "com.apple.security.DetachedCertificates"
- "compatibilityVersion"
- "copy"
- "dataWithContentsOfFile:options:error:"
- "derEncodedSize"
- "dictionary"
- "dictionaryWithCapacity:"
- "encodeCertificateEntry:der:der_end:"
- "errorWithDomain:code:userInfo:"
- "extractAKIDFromCertificate:certificateName:error:"
- "extractSKIDFromCMSData:error:"
- "extractSKIDFromCertificate:certificateName:error:"
- "initWithSKID:certificate:akid:"
- "intermediate"
- "intermediate of leaf at index %lu"
- "intermediateCertificates"
- "intermediateSKIDMap"
- "isEqualToArray:"
- "isEqualToData:"
- "leaf"
- "leaf at index %lu"
- "leafCertificates"
- "leafSKIDMap"
- "loadCertificatesFileMatching:skid:"
- "loadFromPath:error:"
- "lookupCertificateChainForSKID:error:"
- "lookupCertificatesForExecutable:skid:error:"
- "lookupDetachedCertificatesFileForExecutable:cmsData:error:"
- "lookupDetachedCertificatesFileForExecutable:skid:error:"
- "mergeWithFile:error:"
- "objectAtIndexedSubscript:"
- "parent"
- "parseCertificateEntry:certificate:error:"
- "parseCertificateSequence:certificates:error:"
- "parseFromData:error:"
- "q24@?0@\"DetachedCertificateEntry\"8@\"DetachedCertificateEntry\"16"
- "rebuildSKIDMaps"
- "removeAllObjects"
- "removeRootCertificates"
- "root"
- "root of leaf at index %lu"
- "rootCertificates"
- "rootSKIDMap"
- "searchInsideOutForFile:skid:"
- "setCompatibilityVersion:"
- "setIntermediateCertificates:"
- "setIntermediateSKIDMap:"
- "setLeafCertificates:"
- "setLeafSKIDMap:"
- "setRootCertificates:"
- "setRootSKIDMap:"
- "setVersion:"
- "sizeOfCertificateEntry:"
- "skid"
- "sortCertificateArrays"
- "sortUsingComparator:"
- "stringByAppendingPathComponent:"
- "stringByDeletingLastPathComponent"
- "stringByResolvingSymlinksInPath"
- "v24@0:8Q16"
- "version"
- "writeToData:"
- "writeToFile:options:error:"
- "writeToPath:error:"
```
