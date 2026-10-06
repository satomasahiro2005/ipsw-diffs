## AMPDSAPlugin

> `/System/Library/ExtensionKit/Extensions/AMPDSAPlugin.appex/AMPDSAPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x12748` | `0xb518` | **`-0x7230`** |
| `__TEXT.__eh_frame` | `0xad0` | `0x640` | **`-0x490`** |
| `__TEXT.__oslogstring` | `0x9c5` | `0x535` | **`-0x490`** |
| `__TEXT.__unwind_info` | `0x418` | `0x338` | **`-0xe0`** |
| `__TEXT.__swift5_typeref` | `0x2d6` | `0x238` | **`-0x9e`** |
| `__DATA.__data` | `0x308` | `0x278` | **`-0x90`** |
| `__TEXT.__cstring` | `0x2c1` | `0x231` | **`-0x90`** |
| `__TEXT.__const` | `0x9b8` | `0x932` | **`-0x86`** |
| `__TEXT.__objc_stubs` | `0xc0` | `0x40` | **`-0x80`** |
| `__DATA_CONST.__got` | `0x1b8` | `0x158` | **`-0x60`** |
| `__TEXT.__objc_methname` | `0x95` | `0x51` | **`-0x44`** |
| `__DATA_CONST.__const` | `0x5a0` | `0x5d8` | **`+0x38`** |
| `__TEXT.__swift_as_cont` | `0x74` | `0x40` | **`-0x34`** |
| `__TEXT.__swift_as_ret` | `0x58` | `0x34` | **`-0x24`** |
| `__DATA.__objc_selrefs` | `0x30` | `0x10` | **`-0x20`** |
| `__TEXT.__swift5_reflstr` | `0x240` | `0x220` | **`-0x20`** |
| `__TEXT.__swift5_fieldmd` | `0x1d0` | `0x1b8` | **`-0x18`** |
| `__TEXT.__objc_methtype` | `0x1` | `0x15` | **`+0x14`** |
| `__DATA_CONST.__auth_ptr` | `0x228` | `0x218` | **`-0x10`** |
| `__TEXT.__swift_as_entry` | `0x40` | `0x30` | **`-0x10`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-26.0.0.0.0
-  - /System/Library/Frameworks/Accounts.framework/Accounts
+31.0.0.0.0

-  - /System/Library/PrivateFrameworks/AppleMediaServices.framework/AppleMediaServices
+  - /System/Library/PrivateFrameworks/CoreAnalytics.framework/CoreAnalytics

-  - /System/Library/PrivateFrameworks/OnDeviceStorage.framework/OnDeviceStorage

+  - /System/Library/PrivateFrameworks/PriMLDataPolicy.framework/PriMLDataPolicy

-  Functions: 246
-  Symbols:   107
-  CStrings:  81
+  Functions: 216
+  Symbols:   114
+  CStrings:  52
Symbols:
+ _AnalyticsSendEventLazy
+ _OBJC_CLASS_$_NSObject
+ __Block_copy
+ __Block_release
+ __NSConcreteStackBlock
+ _objc_autoreleaseReturnValue
+ _objc_release_x21
+ _swift_beginAccess
+ _swift_release_x22
+ _swift_retain_x2
+ _swift_retain_x27
- _OBJC_CLASS_$_ACAccountStore
- _swift_release_x27
- _swift_retain_x24
- _swift_retain_x8
CStrings:
+ "@\"NSDictionary\"8@?0"
+ "Training metrics: %s"
+ "Weight vector count: %ld, first 5: %s"
- ",\n    dataRequirementsFunction: "
- "Blackbird query failed with code %ld: %@"
- "BlackbirdDataRequirements"
- "BlackbirdQueries"
- "Columns not in access credential - check your JWT permissions"
- "Data requirements function returned non-dict result"
- "Encountered error while using Blackbird connection: %@, closing connection"
- "Error opening Blackbird connection: %@"
- "Executing Blackbird query '%s'..."
- "Executing dynamic Blackbird query"
- "Failed to extract column %s: %@"
- "Failed to get user DSID for Blackbird connection"
- "Malformed query - check SQL syntax"
- "Missing 'query' for '%s'"
- "Missing 'schema' for '%s'"
- "No data retrieved from Blackbird across %ld queries"
- "No queries dict found in data requirements result"
- "Non-existent database"
- "Query '%s' returned %ld rows"
- "Query: %s"
- "Received %ld queries from data requirements function"
- "Retrieved %ld rows from Blackbird"
- "Table used in SELECT is not in FROM clause"
- "Tables not in access credential - check your JWT permissions"
- "Unknown Blackbird error code: %ld"
- "Unknown column type '%s' for column '%s', falling back to string"
- "ams_DSID"
- "ams_activeiTunesAccount"
- "ams_sharedAccountStore"
- "data_requirements_function"
- "data_requirements_function is set but blackbird_access_token is missing in recipe"
- "stringValue"
```
