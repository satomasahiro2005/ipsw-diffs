## AskPermissionAskToResponseExtension

> `/System/Library/ExtensionKit/Extensions/AskPermissionAskToResponseExtension.appex/AskPermissionAskToResponseExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x11990` | `0x14b48` | **`+0x31b8`** |
| `__TEXT.__auth_stubs` | `0xdb0` | `0x1020` | **`+0x270`** |
| `__TEXT.__cstring` | `0xeee` | `0x114d` | **`+0x25f`** |
| `__TEXT.__eh_frame` | `0x3bc` | `0x54c` | **`+0x190`** |
| `__DATA_CONST.__auth_got` | `0x6e8` | `0x820` | **`+0x138`** |
| `__DATA_CONST.__const` | `0x690` | `0x578` | **`-0x118`** |
| `__TEXT.__objc_stubs` | `0x1c80` | `0x1d40` | **`+0xc0`** |
| `__TEXT.__unwind_info` | `0x3d8` | `0x480` | **`+0xa8`** |
| `__TEXT.__swift5_capture` | `0x114` | `0x70` | **`-0xa4`** |
| `__TEXT.__objc_methname` | `0x282d` | `0x28a5` | **`+0x78`** |
| `__TEXT.__objc_methtype` | `0xa4d` | `0xaba` | **`+0x6d`** |
| `__TEXT.__swift5_typeref` | `0x2df` | `0x342` | **`+0x63`** |
| `__DATA_CONST.__got` | `0x258` | `0x2b0` | **`+0x58`** |
| `__DATA.__data` | `0x4e0` | `0x520` | **`+0x40`** |
| `__DATA.__objc_selrefs` | `0xa00` | `0xa30` | **`+0x30`** |
| `__TEXT.__swift5_reflstr` | `0xc1` | `0xe4` | **`+0x23`** |
| `__DATA.__objc_const` | `0x13c8` | `0x13e8` | **`+0x20`** |
| `__DATA.__objc_data` | `0x380` | `0x3a0` | **`+0x20`** |
| `__TEXT.__swift_as_cont` | `0x1c` | `0x3c` | **`+0x20`** |
| `__TEXT.__constg_swiftt` | `0x290` | `0x2a8` | **`+0x18`** |
| `__TEXT.__swift_as_ret` | `0xc` | `0x1c` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0xb8` | `0xc4` | **`+0xc`** |
| `__DATA_CONST.__auth_ptr` | `0x1c8` | `0x1d0` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x10` | `0x18` | **`+0x8`** |
| `__TEXT.__const` | `0x4de` | `0x4e2` | **`+0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-130.0.20.0.0
+130.0.23.0.0

-  Functions: 310
-  Symbols:   229
-  CStrings:  742
+  Functions: 349
+  Symbols:   241
+  CStrings:  760
Symbols:
+ _AMSError
+ _OBJC_CLASS_$_AMSURLSession
+ __Block_copy
+ __Block_release
+ __swiftEmptyArrayStorage
+ _malloc_size
+ _swift_allocError
+ _swift_bridgeObjectRelease_n
+ _swift_continuation_await
+ _swift_continuation_init
+ _swift_continuation_throwingResume
+ _swift_continuation_throwingResumeWithError
+ _swift_coroFrameAlloc
+ _swift_errorRetain
+ _swift_isaMask
+ _swift_retain_x2
+ _swift_retain_x20
+ _swift_willThrow
- _objc_release_x10
- _swift_release_n
- _swift_retain_x22
- _swift_unknownObjectWeakDestroy
- _swift_unknownObjectWeakInit
- _swift_unknownObjectWeakLoadStrong
CStrings:
+ ",\nBundle Identifier: "
+ ",\nDisplay Name: "
+ ",\nExtension Bundle Identifier: "
+ ". Time allowance flow will not be shown."
+ "ActionDelegate: Failed to terminate extension: "
+ "ActionDelegate: Missing Host. Unable to terminate extension."
+ "Approve In Person View auth completed with results: "
+ "Approve In Person View completed with choice: "
+ "Approve In Person View for Screen Time Allowance failed: "
+ "ApproveInPersonView(model:authCompletion:flowCompletion:) called flowCompletion with neither an answerChoice nor an error"
+ "AskToMetadata found"
+ "Couldn't make a URL from the request.thumbnailURLString"
+ "Creating Screen Time Settings for altDSID: "
+ "Error Decoding Request Data - "
+ "Failed to create ScreenTimeSettings: "
+ "Failed to load thumbnail data: "
+ "Loading Approve In Person View"
+ "Loading Basic Remote Product View"
+ "Missing question or askToTopicMetadata"
+ "No request. Time allowance flow will not be shown."
+ "Presenting Approve In Person View"
+ "Requester AltDSID missing - unable to check Screen Time Settings for migration; Time allowance flow will not be shown."
+ "Requester DSID missing - unable to provide to Screen Time. Time allowance flow will not be shown."
+ "Requester has migrated to Screen Time."
+ "Requester has not migrated to Screen Time. Time allowance flow will not be shown."
+ "Screen Time management is disabled for requester. Time allowance flow will not be shown."
+ "Screen Time management is enabled for requester."
+ "addErrorBlock:"
+ "ak_redactedCopy"
+ "data"
+ "dataTaskPromiseWithRequest:"
+ "iconDataPromise"
+ "makeUIViewController: BasicRemoteProductViewControllerWrapper called"
+ "minimalSession"
+ "presentAskInPersonView(for:)"
+ "promiseWithError:"
+ "updateUIViewController: BasicRemoteProductViewControllerWrapper called"
+ "v24@?0@\"AMSURLResult\"8@\"NSError\"16"
- "### ActionDelegate: Failed to terminate extension: "
- "### ActionDelegate: Missing Host. Unable to terminate extension."
- "### Approve In Person View for Screen Time Allowance failed: "
- "### AskToMetadata found"
- "### Creating Screen Time Settings for altDSID: "
- "### Error Decoding Request Data - "
- "### Failed to create ScreenTimeSettings: "
- "### Identifier: "
- "### Loading Approve In Person View"
- "### Loading Basic Remote Product View"
- "### Missing question or askToTopicMetadata"
- "### Requester AltDSID missing - unable to check Screen Time Settings for migration; Time allowance flow will not be shown."
- "### Requester has not migrated to Screen Time. Time allowance flow will not be shown."
- "### Screen Time user is migrated - Time allowance flow will be shown."
- "### Time allowance flow was shown."
- "### makeUIViewController: BasicRemoteProductViewControllerWrapper called"
- "### updateUIViewController: BasicRemoteProductViewControllerWrapper called"
- ", \n Bundle Identifier: "
- ", \n Display Name: "
- ", \n Extension Bundle Identifier: "
```
