## IMDaemonCore

> `/System/Library/PrivateFrameworks/IMDaemonCore.framework/IMDaemonCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3c2f0c` | `0x3c7ad0` | **`+0x4bc4`** |
| `__TEXT.__oslogstring` | `0x558b2` | `0x55c62` | **`+0x3b0`** |
| `__TEXT.__eh_frame` | `0xa6f0` | `0xaa5c` | **`+0x36c`** |
| `__TEXT.__cstring` | `0x14476` | `0x14756` | **`+0x2e0`** |
| `__TEXT.__const` | `0x8918` | `0x8b28` | **`+0x210`** |
| `__AUTH_CONST.__const` | `0xa578` | `0xa738` | **`+0x1c0`** |
| `__TEXT.__unwind_info` | `0xe400` | `0xe510` | **`+0x110`** |
| `__TEXT.__objc_methlist` | `0x1d824` | `0x1d92c` | **`+0x108`** |
| `__DATA.__data` | `0x6dbc` | `0x6e9c` | **`+0xe0`** |
| `__DATA_DIRTY.__data` | `0x3918` | `0x3858` | **`-0xc0`** |
| `__TEXT.__swift5_typeref` | `0x3f50` | `0x400c` | **`+0xbc`** |
| `__TEXT.__gcc_except_tab` | `0x1fa78` | `0x1fb14` | **`+0x9c`** |
| `__DATA.__bss` | `0x55e0` | `0x5670` | **`+0x90`** |
| `__TEXT.__swift5_capture` | `0x1cc8` | `0x1d3c` | **`+0x74`** |
| `__TEXT.__swift5_fieldmd` | `0x1d50` | `0x1dc4` | **`+0x74`** |
| `__TEXT.__swift5_reflstr` | `0x19fb` | `0x199b` | **`-0x60`** |
| `__DATA_CONST.__const` | `0x6e70` | `0x6ec0` | **`+0x50`** |
| `__DATA_CONST.__objc_selrefs` | `0x11390` | `0x113d8` | **`+0x48`** |
| `__TEXT.__swift_as_cont` | `0x968` | `0x9a4` | **`+0x3c`** |
| `__AUTH_CONST.__auth_got` | `0x2fc8` | `0x2ff8` | **`+0x30`** |
| `__DATA_CONST.__objc_protolist` | `0xa00` | `0xa20` | **`+0x20`** |
| `__TEXT.__swift_as_ret` | `0x4e4` | `0x504` | **`+0x20`** |
| `__TEXT.__constg_swiftt` | `0x2d6c` | `0x2d50` | **`-0x1c`** |
| `__AUTH_CONST.__objc_const` | `0x27aa0` | `0x27ab8` | **`+0x18`** |
| `__TEXT.__swift_as_entry` | `0x414` | `0x428` | **`+0x14`** |
| `__DATA_CONST.__got` | `0x3908` | `0x3918` | **`+0x10`** |
| `__DATA_CONST.__objc_protorefs` | `0x378` | `0x388` | **`+0x10`** |
| `__TEXT.__swift5_proto` | `0x410` | `0x41c` | **`+0xc`** |
| `__TEXT.__swift5_types` | `0x294` | `0x2a0` | **`+0xc`** |
| `__DATA_CONST.__objc_classlist` | `0xaf8` | `0xaf0` | **`-0x8`** |
| `__TEXT.__swift5_protos` | `0x54` | `0x5c` | **`+0x8`** |

### Other Changes

```diff

-1491.200.73.0.0
+1491.200.95.0.0

-  Functions: 15200
-  Symbols:   3300
-  CStrings:  8549
+  Functions: 15252
+  Symbols:   3303
+  CStrings:  8576
Symbols:
+ _IMPreviewGenerationSucceededNotificationPreviewWasForceRegeneratedUserInfoKey
+ _swift_getExistentialTypeMetadata
+ _swift_release_x11
CStrings:
+ "\nTasks in batch: "
+ " *** Not accepting transfer -- file is already on disk, nothing to download %@"
+ " activity was left running for "
+ " batch in the critical lane did not finish within "
+ " critical batch exceeded "
+ " seconds, which could indicate a battery drain bug. Tap this notification to file a radar."
+ "%s No broadcaster for messages with GUIDs %s"
+ "Background Processing Timeout"
+ "Failed to notify the user of AskTo request dropped. Error: %@"
+ "Failed to resolve MMCS-backed balloon plugin payload for dropped message %@"
+ "Finished calling AskTo for posting drop user notification"
+ "Generating preview OOP with tmpURL %@ finalURL %@ previewURL %@ maxWidth %f scale %f forceRegeneration %{BOOL}d"
+ "Not generating assistant action suggestions for message in group chat"
+ "Not resolving balloon plugin attachment payload, blastdoor not supported in %{public}@ yet"
+ "PersistentTaskBatchTimeoutSecondsOverride"
+ "PersistentTaskInducedBatchHangSeconds"
+ "This is an internal-only notification."
+ "Transfer %@ PreviewGenState in Success/Fail %ld, saved attributionInfo %@"
+ "Transfer %@ PreviewGenState in Unknown/RecovFailure %ld, saved attributionInfo %@"
+ "Transfer %@ PreviewGenState in default %ld, saved attributionInfo %@"
+ "UPI token message cannot be relayed: failing message"
+ "We have no peer devices %{BOOL}d, or this message had emergency number(s) %lu, or a UPI message v1: %{BOOL}d or v2: %{BOOL}d, or this was a critical message (%{BOOL}d), and we are not the default app (%{BOOL}d): not relaying message"
+ "[%{public}s] failed to wind down with error %@"
+ "[%{public}s] interrupting run"
+ "com.apple.MobileSMS.PersistentTaskBatchTimeout"
+ "errorCodeV2"
+ "s and was abandoned. The critical lane holds a preventsDeviceSleep assertion, so a batch that never returns keeps the device awake.\n\nActivity: "
+ "suspended due to critical execution budget exhaustion"
+ "v16@?0@\"NSData\"8"
+ "v20@?0@\"NSData\"8B16"
- "Generating preview OOP with tmpURL %@ finalURL %@ previewURL %@ maxWidth %f scale %f"
- "We have no peer devices %@, or this message had emergency number(s) %lu, or this was a critical message (%@) and we are not the default app (%@): not relaying message"
- "errorCode"
```
