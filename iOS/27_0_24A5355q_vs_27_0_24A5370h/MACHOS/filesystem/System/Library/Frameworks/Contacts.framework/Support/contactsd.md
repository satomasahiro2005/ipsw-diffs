## contactsd

> `/System/Library/Frameworks/Contacts.framework/Support/contactsd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2e5fc` | `0x2fd90` | **`+0x1794`** |
| `__TEXT.__objc_stubs` | `0x3fa0` | `0x42c0` | **`+0x320`** |
| `__TEXT.__oslogstring` | `0x2459` | `0x2709` | **`+0x2b0`** |
| `__TEXT.__objc_methname` | `0x581d` | `0x5aad` | **`+0x290`** |
| `__DATA_CONST.__const` | `0x13f0` | `0x1528` | **`+0x138`** |
| `__TEXT.__cstring` | `0x1502` | `0x15e2` | **`+0xe0`** |
| `__DATA.__objc_selrefs` | `0x1530` | `0x15f8` | **`+0xc8`** |
| `__TEXT.__gcc_except_tab` | `0x1a4` | `0x250` | **`+0xac`** |
| `__DATA_CONST.__cfstring` | `0x8c0` | `0x960` | **`+0xa0`** |
| `__TEXT.__unwind_info` | `0xb38` | `0xb88` | **`+0x50`** |
| `__DATA.__objc_const` | `0x30e8` | `0x3130` | **`+0x48`** |
| `__TEXT.__objc_methlist` | `0x1c34` | `0x1c6c` | **`+0x38`** |
| `__TEXT.__auth_stubs` | `0x1640` | `0x1670` | **`+0x30`** |
| `__TEXT.__const` | `0x8e8` | `0x918` | **`+0x30`** |
| `__TEXT.__objc_methtype` | `0x12c7` | `0x12e7` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0xb30` | `0xb48` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x538` | `0x550` | **`+0x18`** |
| `__DATA.__bss` | `0x720` | `0x730` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x130` | `0x134` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-3833.100.7.2.1
+3835.100.6.0.0

-  Functions: 1002
-  Symbols:   585
-  CStrings:  1333
+  Functions: 1016
+  Symbols:   591
+  CStrings:  1386
Symbols:
+ _NSStringFromClass
+ _NSStringFromSelector
+ _OBJC_CLASS_$_CNBlockCountingSchedulerDecorator
+ _OBJC_CLASS_$_CNTimeIntervalFormatter
+ _OBJC_CLASS_$_CNTimeProvider
+ _objc_opt_isKindOfClass
CStrings:
+ "%04llx BEGIN Save"
+ "%04llx Change history details: startingToken=%{public}d, unifyResults=%{public}d, includeGroupChanges=%{public}d, additionalKeysCount=%{public}lu"
+ "%04llx EXECUTING (queued: %{public}@)"
+ "%04llx FINISH (%{public}@)"
+ "%04llx FINISH FAILED (%{public}@): %{public}@"
+ "%04llx Predicate: %{private}@"
+ "%04llx QUEUED queue=%{public}@ depth=%ld client=%{public}@"
+ "%04llx RECEIVED %{public}@ (change history) client=%{public}@"
+ "%04llx RECEIVED %{public}@ client=%{public}@"
+ "%04llx RECEIVED executeSaveRequest:withReply: client=%{public}@"
+ "%04llx REPLIED (%{public}@)"
+ "%04llx REPLIED FAILED (%{public}@): %{public}@"
+ "%04llx Request details: unifyResults=%{public}d, sortOrder=%{public}ld, keysCount=%{public}lu"
+ "%@ (pid %d)"
+ "(nil)"
+ "@\"NSString\""
+ "T@\"<CNScheduler>\",R,N,V_expressWorkQueue"
+ "T@\"NSString\",R,C,N,V_clientIdentifierForLogging"
+ "Using express work queue: client is entitled"
+ "Using normal work queue: client is not entitled for the express lane"
+ "_clientIdentifierForLogging"
+ "_expressWorkQueue"
+ "_performServicingRequestOnQueue:triageSerial:work:"
+ "activeBlockCount"
+ "additionalContactKeyDescriptors"
+ "api-triage"
+ "auditToken:allowsExpressWithError:"
+ "bundleIdentifierForAuditToken:"
+ "clientIdentifierForLogging"
+ "clientIdentifierForLoggingWithAuditToken:"
+ "cn_triageWithLog:serialNumber:"
+ "com.apple.contactsd.api.default-"
+ "com.apple.contactsd.api.express-"
+ "default"
+ "express"
+ "expressWorkQueue"
+ "includeGroupChanges"
+ "initWithDataMapper:dataMapperConfiguration:workQueue:expressWorkQueue:connection:accessAuthorization:"
+ "initWithScheduler:"
+ "initWithServiceProvider:scheduler:expressScheduler:tccServices:"
+ "initWithWorkQueue:expressWorkQueue:connection:"
+ "keysToFetch"
+ "logTriageStatsToLog:"
+ "makeExpressScheduler"
+ "pendingBlockCount"
+ "performServicingRequestForSaveRequest:work:"
+ "pid %d"
+ "predicate"
+ "processIdentifierForAuditToken:"
+ "processNameForAuditToken:"
+ "serialNumber"
+ "shortDebugDescription"
+ "shouldUnifyResults"
+ "sortOrder"
+ "startingToken"
+ "stringForTimeInterval:"
+ "triageLog"
+ "unifyResults"
+ "v24@?0@\"CNChangeHistoryResult\"8@\"NSError\"16"
+ "v24@?0@\"NSNumber\"8@\"NSError\"16"
+ "v32@?0@\"NSArray\"8@\"NSDictionary\"16@\"NSError\"24"
+ "v40@0:8@16Q24@?32"
+ "v44@?0@\"NSData\"8@\"NSDictionary\"16@\"<CNEncodedFetchCursor>\"24B32@\"NSError\"36"
- "Using high-priority work queue: client is entitled"
- "Using normal work queue: client is not entitled for high priority"
- "auditToken:allowsHighPriorityWithError:"
- "com.apple.contactsd.api.default-priority-"
- "com.apple.contactsd.api.high-priority-"
- "initWithDataMapper:dataMapperConfiguration:workQueue:highPriorityWorkQueue:connection:accessAuthorization:"
- "initWithServiceProvider:scheduler:highPriorityScheduler:tccServices:"
- "initWithWorkQueue:highPriorityWorkQueue:connection:"
- "makeHighPriorityScheduler"
- "v16@?0@\"CNContactStore\"8"
```
