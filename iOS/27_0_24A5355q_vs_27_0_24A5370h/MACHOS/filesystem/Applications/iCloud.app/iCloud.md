## iCloud

> `/Applications/iCloud.app/iCloud`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x16568` | `0x16c78` | **`+0x710`** |
| `__DATA_CONST.__cfstring` | `0x2020` | `0x2340` | **`+0x320`** |
| `__TEXT.__cstring` | `0x2a0c` | `0x2cba` | **`+0x2ae`** |
| `__TEXT.__ustring` | `0xc` | `0x2a0` | **`+0x294`** |
| `__TEXT.__objc_stubs` | `0x3220` | `0x3320` | **`+0x100`** |
| `__TEXT.__objc_methname` | `0x44fa` | `0x459b` | **`+0xa1`** |
| `__DATA.__objc_selrefs` | `0x1018` | `0x1058` | **`+0x40`** |
| `__DATA_CONST.__const` | `0x720` | `0x748` | **`+0x28`** |
| `__DATA_CONST.__got` | `0x3d8` | `0x3f0` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x1098` | `0x10b0` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x420` | `0x438` | **`+0x18`** |
| `__TEXT.__objc_methtype` | `0x1057` | `0x1069` | **`+0x12`** |
| `__TEXT.__const` | `0xd8` | `0xd0` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`

### Other Changes

```diff

-2710.108.20.0.0
+2710.112.0.0.0

-  Functions: 294
-  Symbols:   227
-  CStrings:  1186
+  Functions: 298
+  Symbols:   230
+  CStrings:  1220
Symbols:
+ _OBJC_CLASS_$_NSDate
+ _OBJC_CLASS_$_NSDateFormatter
+ _OBJC_CLASS_$_NSURLQueryItem
CStrings:
+ "\n\n[INTERNAL ONLY]\nYour logs and the share owner's logs are both required to investigate this issue — this radar is unactionable without them.\n\nAfter filing, share this radar with the owner via iMessage:\n1. Tap + in iMessage\n2. Select Tap to Radar\n3. Select your newly filed radar\n\nAsk the share owner to attach their sysdiagnose."
+ "%@ (%ld)"
+ "1"
+ "552485"
+ "A CloudKit share was unavailable when the participant attempted to open it.\n\n## Environment\nShare URL: %@\nError: %@\n\n## Steps to Reproduce\n1. Receive a share invitation link from a document owner.\n2. Tap the share URL on this device.\n3. Observe \"Item Unavailable\" error.\n\n## Expected Result\nThe shared document opens successfully.\n\n## Actual Result\nCloudKit returns the above error and the shared document cannot be opened."
+ "All"
+ "Always"
+ "Classification"
+ "CloudKit"
+ "ComponentID"
+ "ComponentName"
+ "ComponentVersion"
+ "Description"
+ "File a Radar"
+ "Other Bug"
+ "Reproducibility"
+ "Share Unavailable [%@]: %@"
+ "Title"
+ "date"
+ "isUserInitiated"
+ "new"
+ "no-error"
+ "queryItemWithName:value:"
+ "setDateFormat:"
+ "setHost:"
+ "setQueryItems:"
+ "shareUnavailableTTRURL:error:"
+ "showFailureAlert:isSourceICS:fileRadarAction:"
+ "stringFromDate:"
+ "tap-to-radar"
+ "timeOfIssue"
+ "unknown"
+ "v36@0:8@16B24@?28"
+ "yyyy.MM.dd_HH-mm-ss"
```
