## amsengagementd

> `/System/Library/PrivateFrameworks/AppleMediaServicesUI.framework/amsengagementd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1db040` | `0x1dcb50` | **`+0x1b10`** |
| `__TEXT.__cstring` | `0xd316` | `0xd4f6` | **`+0x1e0`** |
| `__DATA_CONST.__const` | `0x11a90` | `0x11bf8` | **`+0x168`** |
| `__TEXT.__const` | `0xef68` | `0xf078` | **`+0x110`** |
| `__TEXT.__unwind_info` | `0x74e8` | `0x7580` | **`+0x98`** |
| `__DATA.__bss` | `0x144b0` | `0x14530` | **`+0x80`** |
| `__TEXT.__auth_stubs` | `0x4160` | `0x41d0` | **`+0x70`** |
| `__TEXT.__objc_methname` | `0x8dc8` | `0x8d68` | **`-0x60`** |
| `__TEXT.__constg_swiftt` | `0x6028` | `0x6080` | **`+0x58`** |
| `__TEXT.__swift5_capture` | `0x463c` | `0x4684` | **`+0x48`** |
| `__DATA.__objc_const` | `0xae50` | `0xae10` | **`-0x40`** |
| `__TEXT.__eh_frame` | `0xd448` | `0xd488` | **`+0x40`** |
| `__TEXT.__swift5_typeref` | `0x6dd7` | `0x6d97` | **`-0x40`** |
| `__DATA_CONST.__auth_got` | `0x20c0` | `0x20f8` | **`+0x38`** |
| `__TEXT.__swift5_fieldmd` | `0x4a50` | `0x4a88` | **`+0x38`** |
| `__TEXT.__objc_classname` | `0x2a22` | `0x2a52` | **`+0x30`** |
| `__TEXT.__swift5_reflstr` | `0x2f79` | `0x2fa9` | **`+0x30`** |
| `__DATA.__data` | `0xa668` | `0xa688` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x6260` | `0x6280` | **`+0x20`** |
| `__DATA_CONST.__auth_ptr` | `0x1180` | `0x1190` | **`+0x10`** |
| `__DATA.__objc_data` | `0x3f00` | `0x3ef8` | **`-0x8`** |
| `__DATA.__objc_selrefs` | `0x21c8` | `0x21d0` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x5f8` | `0x600` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0xaf8` | `0xafc` | **`+0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__objc_methtype`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-8.1.20.0.0
+8.1.23.2.1

-  Functions: 11869
-  Symbols:   1788
-  CStrings:  3397
+  Functions: 11882
+  Symbols:   1796
+  CStrings:  3403
Symbols:
+ _$s8Dispatch0A8WorkItemC5flags5blockAcA0abC5FlagsV_yyXBtcfc
+ _$s8Dispatch0A8WorkItemC6cancelyyFTj
+ _$s8Dispatch0A8WorkItemCMa
+ _$s8Dispatch0A8WorkItemCMn
+ _$sSb10FoundationE34_conditionallyBridgeFromObjectiveC_6resultSbSo8NSNumberC_SbSgztFZ
+ _$sSd10FoundationE34_conditionallyBridgeFromObjectiveC_6resultSbSo8NSNumberC_SdSgztFZ
+ _$sSo17OS_dispatch_queueC8DispatchE10asyncAfter8deadline7executeyAC0D4TimeV_AC0D8WorkItemCtF
+ _$sSo7JSValueC9JetEngineE10isFunctionSbvg
CStrings:
+ "Enqueue exceeded "
+ "Enqueue exceeded recommended time ("
+ "ExecutionTimeWarning"
+ "Shed idle memory (cleared reconstructable caches)"
+ "[ExecutionTimeWarning] Attempt to notify JS app of long-running task failed. \nThis means that either JS context is invalid or the JS app has not registered as a listener of __amsDispatchEvent."
+ "[ExecutionTimeWarning] Notifying JS app of long-running task through __amsDispatchEvent."
+ "_TtCC14amsengagementd13EnqueueRunnerP33_8FA124567D00B9D238CC3B03C4C0F3FC12DeadlineGate"
+ "__amsDispatchEvent"
+ "claimed"
+ "engagement-enqueue-timeout-enabled"
+ "engagement-enqueue-timeout-seconds"
+ "execution-timeout"
+ "globalObject"
+ "s recommended time"
- " shared JSVirtualMachine(s)"
- " shared JSVirtualMachine(s), cleared reconstructable caches)"
- "Created shared JSVirtualMachine for app: "
- "JSVirtualMachineStore releasing "
- "Shed idle memory (released "
- "_TtC14amsengagementd21JSVirtualMachineStore"
- "virtualMachineStore"
- "virtualMachines"
```
