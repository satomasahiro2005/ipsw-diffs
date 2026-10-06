## MessagesCloudSync

> `/System/Library/PrivateFrameworks/MessagesCloudSync.framework/MessagesCloudSync`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xfc234` | `0x103aa0` | **`+0x786c`** |
| `__TEXT.__eh_frame` | `0x9cf4` | `0xa33c` | **`+0x648`** |
| `__TEXT.__oslogstring` | `0x5763` | `0x5a23` | **`+0x2c0`** |
| `__TEXT.__unwind_info` | `0x3720` | `0x38d8` | **`+0x1b8`** |
| `__AUTH_CONST.__const` | `0x8d59` | `0x8ea1` | **`+0x148`** |
| `__TEXT.__const` | `0x98b0` | `0x99b0` | **`+0x100`** |
| `__TEXT.__cstring` | `0x3e01` | `0x3ef1` | **`+0xf0`** |
| `__TEXT.__swift_as_cont` | `0x96c` | `0xa04` | **`+0x98`** |
| `__TEXT.__swift5_reflstr` | `0x2ffa` | `0x307a` | **`+0x80`** |
| `__AUTH_CONST.__auth_got` | `0x10e0` | `0x1158` | **`+0x78`** |
| `__TEXT.__swift5_fieldmd` | `0x3358` | `0x33bc` | **`+0x64`** |
| `__TEXT.__swift_as_ret` | `0x4cc` | `0x520` | **`+0x54`** |
| `__TEXT.__swift5_typeref` | `0x2826` | `0x2868` | **`+0x42`** |
| `__TEXT.__constg_swiftt` | `0x2c00` | `0x2c34` | **`+0x34`** |
| `__DATA_CONST.__objc_selrefs` | `0xff0` | `0x1020` | **`+0x30`** |
| `__TEXT.__swift_as_entry` | `0x430` | `0x458` | **`+0x28`** |
| `__DATA.__data` | `0xff0` | `0x1010` | **`+0x20`** |
| `__TEXT.__swift5_capture` | `0xfd8` | `0xfe8` | **`+0x10`** |
| `__TEXT.__swift5_proto` | `0x750` | `0x75c` | **`+0xc`** |
| `__TEXT.__swift5_types` | `0x2d8` | `0x2dc` | **`+0x4`** |

### Other Changes

```diff

-1491.100.1.2.25
+1491.200.63.2.1

-  Functions: 3817
+  Functions: 3901

-  CStrings:  856
+  CStrings:  870
CStrings:
+ "Attachment reconcile aborting after batch due to: %@"
+ "Attachment reconcile already finished, skipping (%s)"
+ "Attachment reconcile disabled by server bag, skipping (%s)"
+ "Attachment reconcile drained for %s, marking finished (%s)"
+ "Attachment reconcile error writing record in zone "
+ "Attachment reconcile probe: no server asset for %s: %@"
+ "Attachment reconcile: error handling save for %@: %@"
+ "Attachment reconcile: writing %ld records to %s, %ld metadata-only (%s)"
+ "CloudKitAttachmentReconcileVersion"
+ "Encountered error moving recoverable message for guid %s %@"
+ "Error encountered marking orphaned/stray recoverable record for cloud deletion for guid %s %@"
+ "Failed to rebuild record from system fields when stripping assets; falling back to new record for %@"
+ "Missing recordName or zoneName for recoverable record guid %s; cannot validate, skipping"
+ "attachmentDownloadTimeFrame"
+ "mdd-attachment-reconcile-enabled"
+ "resetRecoverableMessageChangeTokenVersion"
- "Encountered error moving recoverable message part for guid %s %@"
- "Error encountered moving recoverable message %@"
```
