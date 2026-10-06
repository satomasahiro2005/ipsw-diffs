## iCloudQuota

> `/System/Library/PrivateFrameworks/iCloudQuota.framework/iCloudQuota`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__objc_const` | `0xb600` | `0xba10` | **`+0x410`** |
| `__TEXT.__text` | `0x7c994` | `0x7ccdc` | **`+0x348`** |
| `__TEXT.__dlopen_cstrs` | `0x3b5` | `0x417` | **`+0x62`** |
| `__DATA.__data` | `0x5a8` | `0x608` | **`+0x60`** |
| `__AUTH.__objc_data` | `0x1678` | `0x16c8` | **`+0x50`** |
| `__TEXT.__objc_methlist` | `0x5a3c` | `0x5a74` | **`+0x38`** |
| `__TEXT.__unwind_info` | `0x1ed8` | `0x1ef8` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x1e68` | `0x1e80` | **`+0x18`** |
| `__TEXT.__gcc_except_tab` | `0x5a8` | `0x5c0` | **`+0x18`** |
| `__DATA_DIRTY.__bss` | `0x268` | `0x278` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x3b8` | `0x3c0` | **`+0x8`** |
| `__DATA_CONST.__objc_protolist` | `0x50` | `0x58` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x290` | `0x298` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x6bc` | `0x6c0` | **`+0x4`** |

### Same-size Content Changes

- `__TEXT.__oslogstring`

### Other Changes

```diff

-301.24.1.3.0
+301.24.1.4.0

-  Functions: 3048
-  Symbols:   4349
+  Functions: 3053
+  Symbols:   4365
Symbols:
+ -[ICQNotifyDeleteReporter .cxx_destruct]
+ -[ICQNotifyDeleteReporter initWithAccount:]
+ -[ICQNotifyDeleteReporter reportDeleteWithSuccess:bundleId:completion:]
+ _OBJC_CLASS_$_ICQNotifyDeleteReporter
+ _OBJC_IVAR_$_ICQNotifyDeleteReporter._account
+ _OBJC_METACLASS_$_ICQNotifyDeleteReporter
+ __OBJC_$_INSTANCE_METHODS_ICQNotifyDeleteReporter
+ __OBJC_$_INSTANCE_VARIABLES_ICQNotifyDeleteReporter
+ __OBJC_$_PROP_LIST_ICQNotifyDeleteReporter
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_ICQNotifyDeleteReporting
+ __OBJC_$_PROTOCOL_METHOD_TYPES_ICQNotifyDeleteReporting
+ __OBJC_$_PROTOCOL_REFS_ICQNotifyDeleteReporting
+ __OBJC_CLASS_PROTOCOLS_$_ICQNotifyDeleteReporter
+ __OBJC_CLASS_RO_$_ICQNotifyDeleteReporter
+ __OBJC_LABEL_PROTOCOL_$_ICQNotifyDeleteReporting
+ __OBJC_METACLASS_RO_$_ICQNotifyDeleteReporter
+ __OBJC_PROTOCOL_$_ICQNotifyDeleteReporting
+ ___71-[ICQNotifyDeleteReporter reportDeleteWithSuccess:bundleId:completion:]_block_invoke
- -[ICQCloudStorageDataController reportDeleteWithSuccess:bundleId:completion:]
- ___77-[ICQCloudStorageDataController reportDeleteWithSuccess:bundleId:completion:]_block_invoke
CStrings:
+ "XPC error connecting to ind daemon."
+ "reportDeleteWithSuccess:bundleId:completion: called by %{public}@ with success: %d."
- "Reaching out to daemon to report Manage Storage delete for %{public}@."
- "XPC Error while reaching out to daemon to report delete."
```
