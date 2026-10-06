## diskimagesiod

> `/usr/libexec/diskimagesiod`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1dc2cc` | `0x1e242c` | **`+0x6160`** |
| `__TEXT.__gcc_except_tab` | `0x1ae88` | `0x1b744` | **`+0x8bc`** |
| `__TEXT.__cstring` | `0x15aa1` | `0x162ae` | **`+0x80d`** |
| `__DATA_CONST.__const` | `0x37ee0` | `0x38448` | **`+0x568`** |
| `__TEXT.__oslogstring` | `0x2a8c` | `0x2dab` | **`+0x31f`** |
| `__TEXT.__objc_methname` | `0x764a` | `0x793a` | **`+0x2f0`** |
| `__TEXT.__objc_stubs` | `0x6620` | `0x68a0` | **`+0x280`** |
| `__DATA_CONST.__cfstring` | `0x4a20` | `0x4c40` | **`+0x220`** |
| `__TEXT.__unwind_info` | `0xdae0` | `0xdcb0` | **`+0x1d0`** |
| `__DATA.__objc_const` | `0x58e0` | `0x5a18` | **`+0x138`** |
| `__TEXT.__objc_methlist` | `0x3904` | `0x3a34` | **`+0x130`** |
| `__TEXT.__const` | `0x14067` | `0x14137` | **`+0xd0`** |
| `__DATA.__objc_selrefs` | `0x1e58` | `0x1f18` | **`+0xc0`** |
| `__TEXT.__auth_stubs` | `0x22c0` | `0x2350` | **`+0x90`** |
| `__TEXT.__objc_methtype` | `0x2783` | `0x2811` | **`+0x8e`** |
| `__DATA.__objc_data` | `0x1700` | `0x1750` | **`+0x50`** |
| `__DATA_CONST.__auth_got` | `0x1178` | `0x11c0` | **`+0x48`** |
| `__TEXT.__objc_classname` | `0x651` | `0x667` | **`+0x16`** |
| `__DATA.__bss` | `0x250` | `0x260` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x30c` | `0x318` | **`+0xc`** |
| `__DATA_CONST.__objc_classlist` | `0x240` | `0x248` | **`+0x8`** |

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

-  Functions: 11190
-  Symbols:   773
-  CStrings:  3872
+  Functions: 11270
+  Symbols:   782
+  CStrings:  3975
Symbols:
+ _CFStringGetIntValue
+ _SecTaskCopyValueForEntitlement
+ _SecTaskCreateFromSelf
+ _dup2
+ _fputs
+ _pclose
+ _popen
+ _read
+ _write
CStrings:
+ "%.*s: Client cancelled SLA: %{public}@"
+ "%.*s: Client confirmed SLA acceptance"
+ "%.*s: Failed to connect to IO daemon for SLA handling"
+ "%.*s: Failed to dup stdout: %d"
+ "%.*s: Failed to dup2 to stdout: %d"
+ "%.*s: Failed to open /dev/tty: %d"
+ "%.*s: Failed to open pager, writing directly to stdout"
+ "%.*s: IO was not fully started, quitting immediately"
+ "%.*s: No usable SLA text found in UDIF resources"
+ "%.*s: Pager command failed with status %d, output may be incomplete"
+ "%.*s: SLA detected, connecting to IO daemon for user acceptance"
+ "%.*s: SLA resource size (%lld bytes) exceeds maximum (%lld), skipping"
+ "%.*s: SLA: failed to decode %s resource ID %d with encoding 0x%x"
+ "%.*s: SLA: non-numeric resource ID string, skipping"
+ "%.*s: XPC connection disconnected during SLA wait, cancelling attach"
+ "%.*s: XPC connection lost: %{public}@"
+ "%.*s: cancelSLA wait returned error: %{public}@"
+ "+[DISLAFrontend(Private) displaySLAText:error:]"
+ "+[DISLAFrontend(Private) redirectStdoutToTTY]"
+ "-[DIBaseXPCHandler installConnectionLostHandlers]_block_invoke"
+ "-[DIClient2IODaemonXPCHandler cancelSLAWithReason:]"
+ "-[DIIOClientDelegate cancelSLAWithReason:reply:]"
+ "-[DIIOClientDelegate confirmSLAAcceptedWithReply:]"
+ "-[DIIODaemonDelegate resumeAttachAfterSLA:completionReply:confirmReply:]"
+ "/dev/null"
+ "0"
+ ": flush in destructor failed ("
+ "@\"DIAttachParams\""
+ "@?"
+ "@?16@0:8"
+ "ASIF header changed while unlocked"
+ "Agree Y/N? "
+ "Barrier failed after defrag table move, error "
+ "Barrier failed before dir flush"
+ "CFAutoRelease<CFStringRef> udif::sla::extract_sla_text(const DiskImageUDIF &)"
+ "CFAutoRelease<CFStringRef> udif::sla::extract_text_from_resource_array(CFArrayRef, std::optional<std::span<const UInt8>>, std::optional<int32_t>, CFStringEncoding)"
+ "Can't write initial table data"
+ "Cannot display SLA: not running in a terminal"
+ "DISLAFrontend"
+ "Daemon no longer available"
+ "Disconnected during SLA prompt"
+ "Diskimageuio: Failed to create disk image: "
+ "Diskimageuio: Invalid pstack element: "
+ "Encountered an irrecoverable I/O error, all future I/Os will be invalidated"
+ "Failed to convert SLA text to C string"
+ "Failed to create disk image"
+ "Failed to start IO after SLA acceptance"
+ "Failed to write SLA text to stdout"
+ "GUI SLA handling required"
+ "No pending SLA to confirm"
+ "Private"
+ "Raw header changed while unlocked"
+ "SLA prompt cancelled"
+ "SLA resource found but text extraction failed"
+ "SLA text is empty"
+ "Single element in pstack that isn't an image"
+ "T@\"DIAttachParams\",&,V_pendingSLAAttachParams"
+ "T@\"DIDiskMountTracker\",W,V_diskTracker"
+ "T@\"NSString\",&,N,V_slaText"
+ "T@?,C,V_slaCompletionReply"
+ "TEXT"
+ "UDIF header changed while unlocked"
+ "UTF8"
+ "Unexpected materialized_diskimage in create_diskimage_from_hdr"
+ "User declined SLA"
+ "XPC connection interrupted"
+ "XPC connection invalidated"
+ "_pendingSLAAttachParams"
+ "_slaCompletionReply"
+ "_slaText"
+ "can't get Diskimage attribute, unknown header format"
+ "cancelSLAWithReason:"
+ "cancelSLAWithReason:reply:"
+ "clearConnectionLostHandlers"
+ "com.apple.diskimages.sla-prompt"
+ "confirmSLAAcceptedWithError:"
+ "confirmSLAAcceptedWithReply:"
+ "displaySLAText:error:"
+ "finalizePostStartIO:waitForDevice:error:"
+ "h"
+ "installConnectionLostHandlers"
+ "int di_asif::details::dir::defrag_table(ContextASIF &, dir_idx_t)"
+ "io_result_t details::for_each_sg_in_vec_internal(Fn &&, sg_vec_ref::iterator, sg_vec::iterator, size_t, bool) [Fn = (lambda at /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/DiskImages2/app/disk_images/formats/asif.cpp:2035:32)]"
+ "io_result_t details::for_each_sg_in_vec_internal(Fn &&, sg_vec_ref::iterator, sg_vec::iterator, size_t, bool) [Fn = (lambda at /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/DiskImages2/app/disk_images/formats/asif.cpp:2069:32)]"
+ "isStdoutQuietMode"
+ "pendingSLAAttachParams"
+ "promptForAcceptance:"
+ "promptUserForSLAAcceptance:error:"
+ "redirectStdoutToTTY"
+ "restoreStdout:"
+ "resumeAttachAfterSLA:completionReply:confirmReply:"
+ "setClasses:forSelector:argumentIndex:ofReply:"
+ "setPendingSLAAttachParams:"
+ "setSlaCompletionReply:"
+ "setSlaText:"
+ "setWithObject:"
+ "slaCompletionReply"
+ "slaText"
+ "startIO called more than once"
+ "startIO called without a pending DiskImage"
+ "static expected<diskimage, diskimage_err> diskimage_uio::diskimage::create(std::vector<diskimage_open_params_pair> &&, uint32_t)"
+ "std::unique_ptr<DiskImage> diskimage_uio::details::diskimage_open_params_impl::transfer_disk_image_ownership()"
+ "tr '\\r' '\\n' | fmt | ${PAGER:-more}"
+ "userInfo"
+ "v16@?0@\"NSString\"8"
+ "v24@0:8@?<v@?@\"DIDeviceHandle\"@\"NSError\">16"
+ "v24@?0@\"DIDeviceHandle\"8@\"NSError\"16"
+ "v32@0:8@\"DIAttachParams\"16@?<v@?@\"DIDeviceHandle\"@\"NSString\"@\"NSError\">24"
+ "v32@0:8@\"NSString\"16@?<v@?@\"NSError\">24"
+ "v40@0:8@16@?24@?32"
+ "void DiskImage::do_terminate()"
+ "w"
+ "waitForSLACompletionWithReply:"
- "%.*s: _ioManager was not initialized yet, quitting immediately"
- "4"
- "Diskimageuio: Invalid pstack element"
- "Encountered an inrecoverable I/O error, all future I/Os will be invalidated"
- "T@\"DIDiskMountTracker\",&,V_diskTracker"
- "Unsupported UDIF with SLA found"
- "io_result_t details::for_each_sg_in_vec_internal(Fn &&, sg_vec_ref::iterator, sg_vec::iterator, size_t, bool) [Fn = (lambda at /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/DiskImages2/app/disk_images/formats/asif.cpp:2032:32)]"
- "io_result_t details::for_each_sg_in_vec_internal(Fn &&, sg_vec_ref::iterator, sg_vec::iterator, size_t, bool) [Fn = (lambda at /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/DiskImages2/app/disk_images/formats/asif.cpp:2066:32)]"
- "v32@0:8@\"DIAttachParams\"16@?<v@?@\"DIDeviceHandle\"@\"NSError\">24"
- "void DiskImage::terminate()"
```
