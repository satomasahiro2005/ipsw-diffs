## HealthAppHealthDaemon

> `/System/Library/PrivateFrameworks/HealthAppHealthDaemon.framework/HealthAppHealthDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x492f8` | `0x4972c` | **`+0x434`** |
| `__AUTH.__objc_data` | `0x368` | `0x4d8` | **`+0x170`** |
| `__TEXT.__cstring` | `0x17b5` | `0x1855` | **`+0xa0`** |
| `__AUTH_CONST.__objc_const` | `0x3190` | `0x3220` | **`+0x90`** |
| `__TEXT.__constg_swiftt` | `0x934` | `0x9bc` | **`+0x88`** |
| `__TEXT.__const` | `0x21d0` | `0x2250` | **`+0x80`** |
| `__AUTH.__data` | `0xc0` | `0x118` | **`+0x58`** |
| `__TEXT.__objc_methlist` | `0x1ea0` | `0x1ee0` | **`+0x40`** |
| `__AUTH_CONST.__const` | `0x15c8` | `0x1598` | **`-0x30`** |
| `__AUTH_CONST.__auth_got` | `0x10c8` | `0x10f0` | **`+0x28`** |
| `__TEXT.__eh_frame` | `0x20c8` | `0x20f0` | **`+0x28`** |
| `__DATA.__data` | `0x1120` | `0x1100` | **`-0x20`** |
| `__DATA_DIRTY.__data` | `0xa48` | `0xa28` | **`-0x20`** |
| `__TEXT.__swift5_fieldmd` | `0x698` | `0x6b8` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x1478` | `0x1498` | **`+0x20`** |
| `__DATA_CONST.__objc_classlist` | `0x120` | `0x130` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x1480` | `0x1490` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `0x8ac` | `0x8b8` | **`+0xc`** |
| `__DATA_DIRTY.__objc_data` | `0xc90` | `0xc98` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0xc0` | `0xc8` | **`+0x8`** |

### Same-size Content Changes

- `__TEXT.__oslogstring`

### Other Changes

```diff

-7027.1.45.2.4
+7027.1.54.2.3

-  Functions: 1670
-  Symbols:   1511
-  CStrings:  316
+  Functions: 1681
+  Symbols:   1530
+  CStrings:  319
Symbols:
+ -[HDHealthAppProfileExtension _makeNotificationSyncClientWithIdentifier:queueTag:registrationGroup:]
+ -[HDHealthAppProfileExtension initWithProfile:registrationCompleteHandler:]
+ GCC_except_table7
+ _OBJC_CLASS_$_HAHDLoggingPinnedContentStateSyncEntity
+ _OBJC_CLASS_$__TtC21HealthAppHealthDaemon32PinnedContentStateSyncEntityBase
+ _OBJC_METACLASS_$_HAHDLoggingPinnedContentStateSyncEntity
+ _OBJC_METACLASS_$__TtC21HealthAppHealthDaemon32PinnedContentStateSyncEntityBase
+ __CLASS_METHODS__TtC21HealthAppHealthDaemon32PinnedContentStateSyncEntityBase
+ __CLASS_PROPERTIES__TtC21HealthAppHealthDaemon32PinnedContentStateSyncEntityBase
+ __DATA_HAHDLoggingPinnedContentStateSyncEntity
+ __DATA__TtC21HealthAppHealthDaemon32PinnedContentStateSyncEntityBase
+ __INSTANCE_METHODS_HAHDLoggingPinnedContentStateSyncEntity
+ __INSTANCE_METHODS__TtC21HealthAppHealthDaemon32PinnedContentStateSyncEntityBase
+ __METACLASS_DATA_HAHDLoggingPinnedContentStateSyncEntity
+ __METACLASS_DATA__TtC21HealthAppHealthDaemon32PinnedContentStateSyncEntityBase
+ __PROTOCOLS__TtC21HealthAppHealthDaemon32PinnedContentStateSyncEntityBase
+ ___100-[HDHealthAppProfileExtension _makeNotificationSyncClientWithIdentifier:queueTag:registrationGroup:]_block_invoke
+ ___75-[HDHealthAppProfileExtension initWithProfile:registrationCompleteHandler:]_block_invoke
+ _dispatch_get_global_queue
+ _dispatch_group_create
+ _dispatch_group_enter
+ _dispatch_group_leave
+ _dispatch_group_notify
+ _symbolic _____ 09HealthAppA6Daemon32PinnedContentStateSyncEntityBaseC
+ _symbolic _____ 09HealthAppA6Daemon35LoggingPinnedContentStateSyncEntityC
+ _symbolic _____ So27HDCodablePinnedContentStateC09HealthAppE6DaemonE17SyncSchemaVersionO
- GCC_except_table4
- __CLASS_METHODS_HAHDSummaryPinnedContentStateSyncEntity
- __CLASS_PROPERTIES_HAHDSummaryPinnedContentStateSyncEntity
- __PROTOCOLS_HAHDSummaryPinnedContentStateSyncEntity
- ___47-[HDHealthAppProfileExtension initWithProfile:]_block_invoke
- ___swift_destroy_boxed_opaque_existential_0Tm
- _symbolic _____ 09HealthAppA6Daemon35SummaryPinnedContentStateSyncEntityC0H13SchemaVersionO
CStrings:
+ " must override pinnedContentDomain"
+ "HealthAppHealthDaemon/PinnedContentStateSyncEntityBase.swift"
+ "PinnedContentSyncEntityDomainLogging"
+ "[%{public}s]_%@: Sync complete!"
+ "[%{public}s]_%@: Unable to sync"
+ "[%{public}s]_%@: Unknown sync result: %s"
- "[%s]_%@: Sync complete!"
- "[%s]_%@: Unable to sync"
- "[%s]_%@: Unknown sync result: %s"
```
