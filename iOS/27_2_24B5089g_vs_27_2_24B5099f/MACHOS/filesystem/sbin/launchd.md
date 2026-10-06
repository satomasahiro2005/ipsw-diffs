## launchd

> `/sbin/launchd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5b8d0` | `0x5bb5c` | **`+0x28c`** |
| `__TEXT.__cstring` | `0x168c6` | `0x169a6` | **`+0xe0`** |
| `__TEXT.__auth_stubs` | `0x2710` | `0x2720` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x1390` | `0x1398` | **`+0x8`** |
| `__DATA_CONST.__const` | `0x59e0` | `0x59e8` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1140` | `0x1138` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA.__os_assumes_log`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__got`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__dof_launchd`
- `__TEXT.__eh_frame`
- `__TEXT.__init_offsets`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`

### Other Changes

```diff

-3298.40.20.0.0
+3298.40.28.0.0

-  Symbols:   711
-  CStrings:  2830
+  Symbols:   712
+  CStrings:  2836
Symbols:
+ _fstatfs
+ _objc_retain_x23
- _objc_retain_x22
CStrings:
+ "@(#)VERSION:Darwin Bootstrapper Version 7.0.0: Sat Sep 26 06:06:59 PDT 2026; root:libxpc_executables-3298.40.28~39/launchd/RELEASE_ARM64E"
+ "Darwin Bootstrapper Version 7.0.0: Sat Sep 26 06:06:59 PDT 2026; root:libxpc_executables-3298.40.28~39/launchd/RELEASE_ARM64E"
+ "Failed to resolve BundlePath: error=%s: %d, caller=%s"
+ "_BundlePath"
+ "bundle path = %s"
+ "com.apple.private.xpc.launchd.allow-set-bundle-path"
+ "fstatfs failed, treating ownership as untrusted: %d: %s"
+ "v20@?0^{_launch_io_s={_launch_object_s=^vB}{?={_xpc_token_s=IIIIIiii}Q}{?=C*^{dispatch_data_s}^{_xpc_bundle_s}^v{stat=iSSQIIi{timespec=qq}{timespec=qq}{timespec=qq}{timespec=qq}qqiIIi[2q]}i^{dispatch_queue_s}@?b1b1b1b1b1b1}}8i16"
+ "v28@?0^{_launch_domain_io_s={_launch_object_s=^vB}{?=*{_xpc_token_s=IIIIIiii}Q^{dispatch_queue_s}@?@?^{_launch_array_s}ICb1}}8^{_launch_io_s={_launch_object_s=^vB}{?={_xpc_token_s=IIIIIiii}Q}{?=C*^{dispatch_data_s}^{_xpc_bundle_s}^v{stat=iSSQIIi{timespec=qq}{timespec=qq}{timespec=qq}{timespec=qq}qqiIIi[2q]}i^{dispatch_queue_s}@?b1b1b1b1b1b1}}16i24"
+ "vproc not allowed by caller %s"
- "@(#)VERSION:Darwin Bootstrapper Version 7.0.0: Sun Sep 13 20:53:38 PDT 2026; root:libxpc_executables-3298.40.20~223/launchd/RELEASE_ARM64E"
- "Darwin Bootstrapper Version 7.0.0: Sun Sep 13 20:53:38 PDT 2026; root:libxpc_executables-3298.40.20~223/launchd/RELEASE_ARM64E"
- "v20@?0^{_launch_io_s={_launch_object_s=^vB}{?={_xpc_token_s=IIIIIiii}Q}{?=C*^{dispatch_data_s}^{_xpc_bundle_s}^v{stat=iSSQIIi{timespec=qq}{timespec=qq}{timespec=qq}{timespec=qq}qqiIIi[2q]}i^{dispatch_queue_s}@?b1b1b1b1b1}}8i16"
- "v28@?0^{_launch_domain_io_s={_launch_object_s=^vB}{?=*{_xpc_token_s=IIIIIiii}Q^{dispatch_queue_s}@?@?^{_launch_array_s}ICb1}}8^{_launch_io_s={_launch_object_s=^vB}{?={_xpc_token_s=IIIIIiii}Q}{?=C*^{dispatch_data_s}^{_xpc_bundle_s}^v{stat=iSSQIIi{timespec=qq}{timespec=qq}{timespec=qq}{timespec=qq}qqiIIi[2q]}i^{dispatch_queue_s}@?b1b1b1b1b1}}16i24"
```
