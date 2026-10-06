## OSAnalytics

> `/System/Library/PrivateFrameworks/OSAnalytics.framework/OSAnalytics`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0x3d8` | `0x810` | **`+0x438`** |
| `__DATA_DIRTY.__objc_data` | `0x708` | `0x2d0` | **`-0x438`** |
| `__DATA_CONST.__got` | `0x450` | `0x440` | **`-0x10`** |
| `__TEXT.__objc_methlist` | `0x1ca8` | `0x1cb8` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0xe80` | `0xe78` | **`-0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x16b0` | `0x16b8` | **`+0x8`** |
| `__TEXT.__text` | `0x4b01c` | `0x4b024` | **`+0x8`** |

### Other Changes

```diff

-1056.0.3.0.0
+1056.0.12.0.0

-  Functions: 1252
+  Functions: 1253
Symbols:
+ +[OSAReport getSyslogAtCaptureTime:forPids:andOptionalSenders:additionalPredicates:]
+ GCC_except_table31
+ GCC_except_table35
+ GCC_except_table37
+ ___84+[OSAReport getSyslogAtCaptureTime:forPids:andOptionalSenders:additionalPredicates:]_block_invoke
+ ___84+[OSAReport getSyslogAtCaptureTime:forPids:andOptionalSenders:additionalPredicates:]_block_invoke_2
+ _getSyslogAtCaptureTime:forPids:andOptionalSenders:additionalPredicates:.OSLogEventStoreObj
+ _getSyslogAtCaptureTime:forPids:andOptionalSenders:additionalPredicates:.OSLogEventStreamObj
+ _getSyslogAtCaptureTime:forPids:andOptionalSenders:additionalPredicates:.log_semaphore
+ _getSyslogAtCaptureTime:forPids:andOptionalSenders:additionalPredicates:.loggingSupport_dylib
+ _getSyslogAtCaptureTime:forPids:andOptionalSenders:additionalPredicates:.onceToken
- GCC_except_table30
- GCC_except_table33
- GCC_except_table36
- ___70-[OSAReport getSyslogForPids:andOptionalSenders:additionalPredicates:]_block_invoke
- ___70-[OSAReport getSyslogForPids:andOptionalSenders:additionalPredicates:]_block_invoke_2
- _getSyslogForPids:andOptionalSenders:additionalPredicates:.OSLogEventStoreObj
- _getSyslogForPids:andOptionalSenders:additionalPredicates:.OSLogEventStreamObj
- _getSyslogForPids:andOptionalSenders:additionalPredicates:.log_semaphore
- _getSyslogForPids:andOptionalSenders:additionalPredicates:.loggingSupport_dylib
- _getSyslogForPids:andOptionalSenders:additionalPredicates:.onceToken
- _swift_willThrowTypedImpl
```
