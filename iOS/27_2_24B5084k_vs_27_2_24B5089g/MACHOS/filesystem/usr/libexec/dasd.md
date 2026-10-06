## dasd

> `/usr/libexec/dasd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x17b1fc` | `0x17c52c` | **`+0x1330`** |
| `__DATA.__objc_const` | `0x33fc8` | `0x34420` | **`+0x458`** |
| `__TEXT.__objc_methname` | `0x2ebb5` | `0x2ed55` | **`+0x1a0`** |
| `__TEXT.__objc_stubs` | `0x1b380` | `0x1b520` | **`+0x1a0`** |
| `__DATA_CONST.__cfstring` | `0x11ae0` | `0x11c20` | **`+0x140`** |
| `__TEXT.__oslogstring` | `0x171a9` | `0x172e9` | **`+0x140`** |
| `__TEXT.__cstring` | `0x10706` | `0x10806` | **`+0x100`** |
| `__TEXT.__objc_methlist` | `0x1334c` | `0x1343c` | **`+0xf0`** |
| `__TEXT.__objc_methtype` | `0x4231` | `0x42e1` | **`+0xb0`** |
| `__DATA_CONST.__const` | `0x4fa8` | `0x5038` | **`+0x90`** |
| `__TEXT.__unwind_info` | `0x5130` | `0x51a8` | **`+0x78`** |
| `__DATA.__objc_selrefs` | `0x9e20` | `0x9e88` | **`+0x68`** |
| `__DATA.__data` | `0x21a0` | `0x2200` | **`+0x60`** |
| `__DATA_CONST.__objc_arraydata` | `0x4a0` | `0x4f8` | **`+0x58`** |
| `__DATA.__objc_data` | `0x4908` | `0x4958` | **`+0x50`** |
| `__DATA.__bss` | `0x1250` | `0x1280` | **`+0x30`** |
| `__TEXT.__objc_classname` | `0x1ca8` | `0x1cd8` | **`+0x30`** |
| `__DATA_CONST.__objc_arrayobj` | `0x1c8` | `0x1e0` | **`+0x18`** |
| `__TEXT.__gcc_except_tab` | `0x502c` | `0x5044` | **`+0x18`** |
| `__TEXT.__auth_stubs` | `0x2240` | `0x2250` | **`+0x10`** |
| `__TEXT.__const` | `0x1578` | `0x1588` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x1644` | `0x1650` | **`+0xc`** |
| `__DATA_CONST.__auth_got` | `0x1130` | `0x1138` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x708` | `0x710` | **`+0x8`** |
| `__DATA_CONST.__objc_protolist` | `0x218` | `0x220` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x5c0` | `0x5c8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_builtin`
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

-2467.40.37.0.0
+2467.40.41.0.0

-  Functions: 8411
-  Symbols:   1019
-  CStrings:  12534
+  Functions: 8441
+  Symbols:   1020
+  CStrings:  12573
Symbols:
+ _MGIsDeviceOneOfType
CStrings:
+ "AppLifecycleRecorder"
+ "B36@0:8@16B24@28"
+ "B48@0:8Q16@24@32^@40"
+ "Backfilled %lu app lifecycle checkpoints"
+ "Backfilling app lifecycle checkpoints for %{public}@ - %{public}@"
+ "Donated checkpoint %lu for %{public}@ at %{public}@"
+ "Failed to read App.InFocus: %{public}@"
+ "Failed to record checkpoint %lu for %{public}@: %{public}@"
+ "Nothing to backfill; resume point is not before the window end"
+ "_DASAppLifecycleRecorder"
+ "_DASProcessLifecycleDelegate"
+ "_liveDonationStartDate"
+ "absoluteTimestamp"
+ "appLifecycle"
+ "backfillCheckpointsUpToDate:"
+ "backfillHistoryPrecedingLiveWindow"
+ "com.apple.DocumentsApp"
+ "com.apple.MobileSMS"
+ "com.apple.Notes"
+ "com.apple.dasd.appLifecycleBackfill"
+ "com.apple.dasd.appLifecycleRecorder"
+ "com.apple.iCal"
+ "com.apple.mail"
+ "com.apple.mobilecal"
+ "com.apple.mobilenotes"
+ "com.apple.reminders"
+ "donateTransitionForApp:foregrounded:atDate:"
+ "inLongInactivityWindow"
+ "initInternal"
+ "isThermallyConstrainedHardware"
+ "notifyDelegatesOfTransitionForApp:foregrounded:atDate:"
+ "processLifecycleMonitor:observedTransitionForApp:foregrounded:atDate:"
+ "reportCustomCheckpoint:forTask:atDate:error:"
+ "resumeDateBefore:"
+ "sharedRecorder"
+ "startDonating"
+ "v32@0:8@\"_DASProcessLifecycleMonitor\"16@\"NSSet\"24"
+ "v44@0:8@\"_DASProcessLifecycleMonitor\"16@\"NSString\"24B32@\"NSDate\"36"
+ "v44@0:8@16@24B32@36"
```
