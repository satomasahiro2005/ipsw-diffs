## JetCore

> `/System/Library/PrivateFrameworks/JetCore.framework/JetCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x268538` | `0x26f958` | **`+0x7420`** |
| `__TEXT.__unwind_info` | `0x9aa8` | `0xa050` | **`+0x5a8`** |
| `__TEXT.__cstring` | `0xa551` | `0xaa01` | **`+0x4b0`** |
| `__TEXT.__eh_frame` | `0x151e0` | `0x15510` | **`+0x330`** |
| `__AUTH_CONST.__const` | `0x1a7d0` | `0x1aa98` | **`+0x2c8`** |
| `__DATA.__bss` | `0x23a10` | `0x23c90` | **`+0x280`** |
| `__TEXT.__const` | `0x1eef4` | `0x1f0f4` | **`+0x200`** |
| `__DATA.__data` | `0x64e0` | `0x66a0` | **`+0x1c0`** |
| `__AUTH_CONST.__objc_const` | `0x2c58` | `0x2d50` | **`+0xf8`** |
| `__TEXT.__swift5_fieldmd` | `0x6ac0` | `0x6bb4` | **`+0xf4`** |
| `__AUTH.__data` | `0x2790` | `0x2848` | **`+0xb8`** |
| `__TEXT.__constg_swiftt` | `0x7c70` | `0x7d24` | **`+0xb4`** |
| `__TEXT.__swift5_reflstr` | `0x3b52` | `0x3bd0` | **`+0x7e`** |
| `__TEXT.__swift5_typeref` | `0x8477` | `0x84d7` | **`+0x60`** |
| `__TEXT.__swift5_capture` | `0x3808` | `0x3828` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0x1f48` | `0x1f60` | **`+0x18`** |
| `__DATA_CONST.__const` | `0x580` | `0x598` | **`+0x18`** |
| `__TEXT.__swift5_assocty` | `0x10a0` | `0x10b8` | **`+0x18`** |
| `__TEXT.__swift5_proto` | `0x1768` | `0x1780` | **`+0x18`** |
| `__DATA_CONST.__got` | `0xa08` | `0xa18` | **`+0x10`** |
| `__DATA_DIRTY.__data` | `0x3738` | `0x3748` | **`+0x10`** |
| `__TEXT.__swift_as_cont` | `0xa6c` | `0xa7c` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0x9b0` | `0x9bc` | **`+0xc`** |
| `__DATA_CONST.__objc_classlist` | `0x150` | `0x158` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x840` | `0x848` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x5ac` | `0x5b4` | **`+0x8`** |
| `__TEXT.__swift5_protos` | `0x1a4` | `0x1a8` | **`+0x4`** |

### Other Changes

```diff

-10.0.47.0.0
+10.1.8.0.0

-  Functions: 12810
-  Symbols:   3816
-  CStrings:  974
+  Functions: 12911
+  Symbols:   3826
+  CStrings:  1000
Symbols:
+ __DATA__TtC7JetCore14JetAssetClient
+ __IVARS__TtC7JetCore14JetAssetClient
+ __METACLASS_DATA__TtC7JetCore14JetAssetClient
+ ___swift_closure_destructor.31Tm
+ _associated conformance 7JetCore18AssetPendingOriginOSHAASQ
+ _symbolic $s7JetCore27URLSessionAsyncDataFetchingP
+ _symbolic _____ 7JetCore0A11AssetClientC
+ _symbolic _____ 7JetCore18AssetPendingOriginO
+ _symbolic _____ 7JetCore19MetricsCommonFieldsV
+ _symbolic ______p 7JetCore27URLSessionAsyncDataFetchingP
+ _symbolic _____y_____G 7JetCore14DaemonResponseO AA0c2NoD0V
+ _type_layout_string 7JetCore19MetricsCommonFieldsV
- ___swift_closure_destructor.37Tm
- ___swift_memcpy168_8
CStrings:
+ " = 'push' THEN pending_origin ELSE "
+ " END,\n    modified_at = "
+ ",\n    pending_origin = "
+ ",\n    pending_origin = CASE WHEN pending = 1 AND pending_origin IN ('checkpoint', 'apsReconnect') AND "
+ ",\n    schedule_to = "
+ "ALTER TABLE push_subscription ADD COLUMN pending_origin TEXT"
+ "AssetPushSubscriptionSQLiteStore DB migration to v7..."
+ "Cannot retrieve asset via daemon: "
+ "Daemon prewarm failed: "
+ "DaemonSession.sendSync"
+ "Direct fetch failed: "
+ "Error occurred when sending synchronous request to daemon: "
+ "Falling back to direct network fetch"
+ "JetAssetClient.prewarm"
+ "MetricsCommonFields: use the typed property for '"
+ "Received an XPC error sending synchronous request: "
+ "Sending synchronous prewarm request to daemon"
+ "Sending synchronous request to daemon: "
+ "UPDATE push_subscription SET\n    pending = 1,\n    download_attempts = 0,\n    schedule_from = "
+ "UPDATE push_subscription SET pending = 0, download_attempts = NULL, schedule_from = NULL, schedule_to = NULL, priority = NULL, server_timestamp = NULL, pending_origin = NULL, modified_at = "
+ "XPC session (sendSync) cancelled: "
+ "apsReconnect"
+ "checkpoint"
+ "pendingOriginRaw"
+ "push"
+ "push304Retry"
+ "sendSync complete"
+ "✅ AssetPushSubscriptionSQLiteStore DB migration to v7 complete"
- "Sending one-way prewarm request to daemon"
- "UPDATE push_subscription SET pending = 0, download_attempts = NULL, schedule_from = NULL, schedule_to = NULL, priority = NULL, server_timestamp = NULL, modified_at = "
```
