## diskimagescontroller

> `/System/Library/PrivateFrameworks/DiskImages2.framework/XPCServices/diskimagescontroller.xpc/diskimagescontroller`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1e23f0` | `0x1e503c` | **`+0x2c4c`** |
| `__TEXT.__cstring` | `0x16ee8` | `0x174c8` | **`+0x5e0`** |
| `__TEXT.__gcc_except_tab` | `0x1b4ec` | `0x1b908` | **`+0x41c`** |
| `__TEXT.__objc_stubs` | `0x59e0` | `0x5c40` | **`+0x260`** |
| `__TEXT.__oslogstring` | `0x1894` | `0x1aac` | **`+0x218`** |
| `__TEXT.__objc_methname` | `0x666c` | `0x685c` | **`+0x1f0`** |
| `__DATA_CONST.__cfstring` | `0x43e0` | `0x4560` | **`+0x180`** |
| `__DATA_CONST.__const` | `0x39b70` | `0x39cd0` | **`+0x160`** |
| `__DATA.__objc_const` | `0x52e8` | `0x53c0` | **`+0xd8`** |
| `__TEXT.__objc_methlist` | `0x33d4` | `0x34ac` | **`+0xd8`** |
| `__TEXT.__unwind_info` | `0xdff8` | `0xe0b8` | **`+0xc0`** |
| `__DATA.__objc_selrefs` | `0x1ae8` | `0x1b80` | **`+0x98`** |
| `__TEXT.__auth_stubs` | `0x2090` | `0x2120` | **`+0x90`** |
| `__TEXT.__objc_methtype` | `0x22f5` | `0x2365` | **`+0x70`** |
| `__DATA.__objc_data` | `0x1700` | `0x1750` | **`+0x50`** |
| `__DATA_CONST.__auth_got` | `0x1060` | `0x10a8` | **`+0x48`** |
| `__DATA.__bss` | `0x240` | `0x250` | **`+0x10`** |
| `__TEXT.__const` | `0x1483a` | `0x1482a` | **`-0x10`** |
| `__TEXT.__objc_classname` | `0x669` | `0x679` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x240` | `0x248` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x28c` | `0x290` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_typeref`

### Other Changes

```diff

-588.0.0.0.2
+593.0.0.0.1

-  Functions: 11377
-  Symbols:   802
-  CStrings:  3525
+  Functions: 11412
+  Symbols:   811
+  CStrings:  3598
Symbols:
+ _SecTaskCopyValueForEntitlement
+ _SecTaskCreateFromSelf
+ _fputs
+ _objc_sync_enter
+ _objc_sync_exit
+ _pclose
+ _popen
+ _read
+ _write
CStrings:
+ "%.*s: Failed to connect to IO daemon for SLA handling"
+ "%.*s: Failed to dup stdout: %d"
+ "%.*s: Failed to dup2 to stdout: %d"
+ "%.*s: Failed to open /dev/tty: %d"
+ "%.*s: Failed to open pager, writing directly to stdout"
+ "%.*s: Pager command failed with status %d, output may be incomplete"
+ "%.*s: SLA detected, connecting to IO daemon for user acceptance"
+ "%.*s: SLA detected, returning to client for acceptance"
+ "%.*s: XPC connection lost: %{public}@"
+ "%.*s: cancelSLA wait returned error: %{public}@"
+ "%.*s: waitForSLACompletion returned error: %{public}@"
+ "+[DIControllerServiceConnection tryAttachWithParams:clientConnection:slaXpcHandler:outError:]"
+ "+[DISLAFrontend(Private) displaySLAText:error:]"
+ "+[DISLAFrontend(Private) redirectStdoutToTTY]"
+ "-[DIBaseXPCHandler installConnectionLostHandlers]_block_invoke"
+ "-[DIClient2IODaemonXPCHandler cancelSLAWithReason:]"
+ "-[DIControllerServiceConnection attachWithParams:reply:]_block_invoke"
+ "/dev/null"
+ "593.0.0"
+ ": flush in destructor failed ("
+ "ASIF header changed while unlocked"
+ "Agree Y/N? "
+ "B48@0:8@16@24^@32^@40"
+ "Barrier failed after defrag table move, error "
+ "Barrier failed before dir flush"
+ "Can't write initial table data"
+ "Cannot display SLA: not running in a terminal"
+ "DISLAFrontend"
+ "Diskimageuio: Failed to create disk image: "
+ "Diskimageuio: Invalid pstack element: "
+ "Encountered an irrecoverable I/O error, all future I/Os will be invalidated"
+ "Failed to convert SLA text to C string"
+ "Failed to create disk image"
+ "Failed to write SLA text to stdout"
+ "GUI SLA handling required"
+ "Private"
+ "Raw header changed while unlocked"
+ "SLA prompt cancelled"
+ "SLA text is empty"
+ "Single element in pstack that isn't an image"
+ "T@\"NSString\",&,N,V_slaText"
+ "UDIF header changed while unlocked"
+ "Unexpected materialized_diskimage in create_diskimage_from_hdr"
+ "User declined SLA"
+ "XPC connection interrupted"
+ "XPC connection invalidated"
+ "_slaText"
+ "can't get Diskimage attribute, unknown header format"
+ "cancelSLAWithReason:"
+ "cancelSLAWithReason:reply:"
+ "clearConnectionLostHandlers"
+ "com.apple.diskimages.sla-prompt"
+ "confirmSLAAcceptedWithError:"
+ "confirmSLAAcceptedWithReply:"
+ "displaySLAText:error:"
+ "installConnectionLostHandlers"
+ "int di_asif::details::dir::defrag_table(ContextASIF &, dir_idx_t)"
+ "io_result_t details::for_each_sg_in_vec_internal(Fn &&, sg_vec_ref::iterator, sg_vec::iterator, size_t, bool) [Fn = (lambda at /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/DiskImages2/app/disk_images/formats/asif.cpp:2035:32)]"
+ "io_result_t details::for_each_sg_in_vec_internal(Fn &&, sg_vec_ref::iterator, sg_vec::iterator, size_t, bool) [Fn = (lambda at /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/DiskImages2/app/disk_images/formats/asif.cpp:2069:32)]"
+ "isStdoutQuietMode"
+ "promptForAcceptance:"
+ "promptUserForSLAAcceptance:error:"
+ "redirectStdoutToTTY"
+ "restoreStdout:"
+ "setClasses:forSelector:argumentIndex:ofReply:"
+ "setSlaText:"
+ "setWithObject:"
+ "slaText"
+ "static expected<diskimage, diskimage_err> diskimage_uio::diskimage::create(std::vector<diskimage_open_params_pair> &&, uint32_t)"
+ "std::unique_ptr<DiskImage> diskimage_uio::details::diskimage_open_params_impl::transfer_disk_image_ownership()"
+ "tr '\\r' '\\n' | fmt | ${PAGER:-more}"
+ "tryAttachWithParams:clientConnection:slaXpcHandler:outError:"
+ "userInfo"
+ "v16@?0@\"NSString\"8"
+ "v24@0:8@?<v@?@\"DIDeviceHandle\"@\"NSError\">16"
+ "v32@0:8@\"DIAttachParams\"16@?<v@?@\"DIDeviceHandle\"@\"NSString\"@\"NSError\">24"
+ "v32@0:8@\"NSString\"16@?<v@?@\"NSError\">24"
+ "v32@?0@\"DIDeviceHandle\"8@\"NSString\"16@\"NSError\"24"
+ "void DiskImage::do_terminate()"
+ "w"
+ "waitForSLACompletionWithError:"
+ "waitForSLACompletionWithReply:"
- "+[DIControllerServiceConnection tryAttachWithParams:clientConnection:outError:]"
- "588.0.0"
- "Diskimageuio: Invalid pstack element"
- "Encountered an inrecoverable I/O error, all future I/Os will be invalidated"
- "io_result_t details::for_each_sg_in_vec_internal(Fn &&, sg_vec_ref::iterator, sg_vec::iterator, size_t, bool) [Fn = (lambda at /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/DiskImages2/app/disk_images/formats/asif.cpp:2032:32)]"
- "io_result_t details::for_each_sg_in_vec_internal(Fn &&, sg_vec_ref::iterator, sg_vec::iterator, size_t, bool) [Fn = (lambda at /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/DiskImages2/app/disk_images/formats/asif.cpp:2066:32)]"
- "tryAttachWithParams:clientConnection:outError:"
- "v32@0:8@\"DIAttachParams\"16@?<v@?@\"DIDeviceHandle\"@\"NSError\">24"
- "void DiskImage::terminate()"
```
