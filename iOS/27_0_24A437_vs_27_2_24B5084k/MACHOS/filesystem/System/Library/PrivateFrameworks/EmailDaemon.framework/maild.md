## maild

> `/System/Library/PrivateFrameworks/EmailDaemon.framework/maild`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x152ce4` | `0x1528f8` | **`-0x3ec`** |
| `__DATA.__objc_const` | `0x13080` | `0x12de0` | **`-0x2a0`** |
| `__TEXT.__objc_methlist` | `0xaffc` | `0xae34` | **`-0x1c8`** |
| `__TEXT.__objc_methname` | `0x1cf85` | `0x1ce75` | **`-0x110`** |
| `__DATA.__data` | `0x2e30` | `0x2d40` | **`-0xf0`** |
| `__TEXT.__gcc_except_tab` | `0x19738` | `0x196a4` | **`-0x94`** |
| `__TEXT.__objc_methtype` | `0x4199` | `0x4119` | **`-0x80`** |
| `__TEXT.__objc_stubs` | `0x16520` | `0x164c0` | **`-0x60`** |
| `__DATA.__objc_selrefs` | `0x7050` | `0x7000` | **`-0x50`** |
| `__TEXT.__unwind_info` | `0x6f90` | `0x6f50` | **`-0x40`** |
| `__TEXT.__objc_classname` | `0x1aff` | `0x1acf` | **`-0x30`** |
| `__TEXT.__oslogstring` | `0xb02e` | `0xaffe` | **`-0x30`** |
| `__DATA_CONST.__const` | `0xe620` | `0xe5f8` | **`-0x28`** |
| `__TEXT.__auth_stubs` | `0x2800` | `0x2820` | **`+0x20`** |
| `__DATA_CONST.__objc_protolist` | `0x348` | `0x330` | **`-0x18`** |
| `__TEXT.__cstring` | `0x8de6` | `0x8df8` | **`+0x12`** |
| `__DATA_CONST.__auth_got` | `0x1410` | `0x1420` | **`+0x10`** |
| `__DATA_CONST.__auth_ptr` | `0x420` | `0x410` | **`-0x10`** |
| `__TEXT.__const` | `0x15fc` | `0x15ec` | **`-0x10`** |
| `__TEXT.__swift5_reflstr` | `0x33c` | `0x32c` | **`-0x10`** |
| `__DATA_CONST.__got` | `0x1838` | `0x1840` | **`+0x8`** |
| `__DATA_CONST.__objc_catlist` | `0x78` | `0x70` | **`-0x8`** |
| `__DATA_CONST.__objc_protorefs` | `0xb0` | `0xa8` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA.__objc_ivar`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__dlopen_cstrs`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-3901.100.1.2.14
+3901.200.34.0.0

+  - /System/Library/PrivateFrameworks/HybridSearchResultRanker.framework/HybridSearchResultRanker

-  Functions: 5881
-  Symbols:   1546
-  CStrings:  7536
+  Functions: 5875
+  Symbols:   1549
+  CStrings:  7514
Symbols:
+ _CacheDeleteRequestCacheableSpaceGuidance
+ _EFProcessDidBecomeIdleNotification
+ _MFErrorPageMarkupFormat
+ _MFMailDirectoryURL
+ _OBJC_CLASS_$_EDListUnsubscribeDetector
- _MFMIMEErrorDomain
- _OBJC_CLASS_$_EMListUnsubscribeDetector
CStrings:
+ "CACHE_DELETE_GUIDANCE"
+ "CACHE_DELETE_GUIDANCE_CAN_EXPAND_CACHE"
+ "CACHE_DELETE_GUIDANCE_DO_NOT_EXPAND_CACHE"
+ "CACHE_DELETE_GUIDANCE_WILL_EVICT_LOWER_PRIORITY"
+ "MFDeviceStorage"
+ "MFMailDeviceStorage"
+ "_processDidBecomeIdle:"
+ "flushAllMessageStoreCaches"
+ "freeSpaceGuidanceForSpaceIncrease:urgency:"
+ "q32@0:8q16q24"
- "<html dir=auto><body><i><font color=#888>%@</font></i></body></html>"
- "@\"<ECMailbox>\"24@0:8q16"
- "@\"<EDDeliveryAccount>\"16@0:8"
- "@\"ACAccount\"16@0:8"
- "@16@?0@\"<EDAccount>\"8"
- "@24@0:8@\"NSString\"16"
- "B24@0:8@\"NSURL\"16"
- "ECAccountPropertyProviding"
- "ECMailAccount"
- "EDAccount"
- "EDReceivingAccount"
- "Failed to find a message for error: %{public}@"
- "MCSNotJunk"
- "MESSAGE_CAUSED_PROBLEM"
- "MESSAGE_UNAVAILABLE"
- "MessageContentView"
- "OPERATION_NOT_JUNK_DESC"
- "T@\"ACAccount\",R,N"
- "accountURL"
- "altDSID"
- "canAuthenticateWithCurrentCredentials"
- "containsMailboxWithURL:"
- "ef_match"
- "initWithSpecialDestination:"
- "isLocalAccount"
- "mf_isSMIMEError"
- "primaryiCloudAccount"
- "setDeliveryAccount:"
- "smtpIdentifier"
- "sourceIsManaged"
- "systemAccount"
- "v24@0:8@\"<EDDeliveryAccount>\"16"
```
