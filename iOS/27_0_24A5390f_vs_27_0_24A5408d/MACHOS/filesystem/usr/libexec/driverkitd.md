## driverkitd

> `/usr/libexec/driverkitd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xe96bc` | `0xeba10` | **`+0x2354`** |
| `__TEXT.__cstring` | `0x8ce4` | `0x9084` | **`+0x3a0`** |
| `__TEXT.__eh_frame` | `0x31ec` | `0x3374` | **`+0x188`** |
| `__DATA.__objc_const` | `0x3710` | `0x3890` | **`+0x180`** |
| `__DATA.__data` | `0x6290` | `0x63c8` | **`+0x138`** |
| `__TEXT.__const` | `0xf3f5` | `0xf485` | **`+0x90`** |
| `__TEXT.__objc_classname` | `0xb2c` | `0xbac` | **`+0x80`** |
| `__TEXT.__constg_swiftt` | `0x40bc` | `0x4130` | **`+0x74`** |
| `__TEXT.__unwind_info` | `0x2740` | `0x27b0` | **`+0x70`** |
| `__TEXT.__objc_methname` | `0x1346` | `0x13a6` | **`+0x60`** |
| `__DATA_CONST.__const` | `0x8950` | `0x8998` | **`+0x48`** |
| `__TEXT.__swift5_typeref` | `0x35f4` | `0x363a` | **`+0x46`** |
| `__TEXT.__swift5_fieldmd` | `0x3520` | `0x3564` | **`+0x44`** |
| `__TEXT.__objc_stubs` | `0x860` | `0x8a0` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0x1f8` | `0x224` | **`+0x2c`** |
| `__TEXT.__swift5_reflstr` | `0x2036` | `0x2056` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0x2e8` | `0x300` | **`+0x18`** |
| `__TEXT.__swift5_assocty` | `0x468` | `0x480` | **`+0x18`** |
| `__TEXT.__auth_stubs` | `0x2480` | `0x2490` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x1248` | `0x1250` | **`+0x8`** |
| `__DATA_CONST.__auth_ptr` | `0x850` | `0x858` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x508` | `0x510` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x1c0` | `0x1c8` | **`+0x8`** |
| `__DATA_CONST.__objc_protolist` | `0x68` | `0x70` | **`+0x8`** |
| `__DATA_CONST.__objc_protorefs` | `0x38` | `0x40` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0xc50` | `0xc54` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0x3cc` | `0x3d0` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__TEXT.__objc_methtype`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`

### Other Changes

```diff

-514.0.0.0.0
+514.2.1.0.0

-  Functions: 3610
-  Symbols:   877
-  CStrings:  1205
+  Functions: 3636
+  Symbols:   879
+  CStrings:  1226
Symbols:
+ _OBJC_CLASS_$_LSBundleRecord
+ _swift_getObjCClassFromMetadata
CStrings:
+ "App connection from pid %d resolved to an application record with no install session identifier; failing closed"
+ "App server name: %{public}s"
+ "Attempt by unentitled pid %d to access app interface"
+ "Audit token did not resolve to an application record"
+ "Error while getting scoped approval state: %{public}s"
+ "Incoming app request for scoped approval state from pid %d"
+ "KMError while getting scoped approval state: %{public}s"
+ "KernelManagement_executables-514.2.1"
+ "Processing pending requests from the kernel, if any"
+ "Scoped %lu of %lu cached approval entries to install session %{private}s: [%{private}s]"
+ "Unexpected call to applicationRecord(fromAuditToken:)"
+ "_TtC10driverkitd36DriverKitDaemonAppXPCRequestDelegate"
+ "_TtP10driverkitd32DriverKitDaemonAppClientProtocol_"
+ "auditToken"
+ "bundleRecordForAuditToken:error:"
+ "com.apple.DriverKitAppServer"
+ "com.apple.developer.system-extension.install"
+ "com.apple.driverkitd.NSXPCAppRequestSource"
+ "getApprovalStateForCallingAppWithReplyBlock:"
+ "incoming app connection from pid %d"
+ "install session identifier for calling application"
+ "processPendingRequestsOnActivation"
- "KernelManagement_executables-514"
```
