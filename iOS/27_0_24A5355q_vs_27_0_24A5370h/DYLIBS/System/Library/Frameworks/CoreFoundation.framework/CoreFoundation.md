## CoreFoundation

> `/System/Library/Frameworks/CoreFoundation.framework/CoreFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1d0b0c` | `0x1d1fac` | **`+0x14a0`** |
| `__TEXT.__oslogstring` | `0x5622` | `0x59c8` | **`+0x3a6`** |
| `__TEXT.__cstring` | `0x14b1bb` | `0x14b234` | **`+0x79`** |
| `__TEXT.__gcc_except_tab` | `0x5e54` | `0x5e2c` | **`-0x28`** |
| `__AUTH_CONST.__auth_got` | `0x18e8` | `0x1908` | **`+0x20`** |
| `__AUTH_CONST.__cfstring` | `0x140ce0` | `0x140d00` | **`+0x20`** |
| `__DATA.__bss` | `0x874` | `0x894` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x6558` | `0x6538` | **`-0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x2b08` | `0x2b20` | **`+0x18`** |
| `__TEXT.__const` | `0x1a7d18` | `0x1a7d30` | **`+0x18`** |
| `__DATA_CONST.__const` | `0x3c89c0` | `0x3c89b0` | **`-0x10`** |
| `__TEXT.__objc_methlist` | `0x7b0c` | `0x7b1c` | **`+0x10`** |
| `__DATA.__common` | `0x90` | `0x98` | **`+0x8`** |

### Other Changes

```diff

-5027.0.51.2.101
+5027.0.55.1.0

-  Functions: 8585
-  Symbols:   11455
-  CStrings:  44271
+  Functions: 8595
+  Symbols:   11458
+  CStrings:  44291
Symbols:
+ -[NSNull hash]
+ GCC_except_table108
+ GCC_except_table97
+ __CFCacheTestingFlags
+ __CFPrefsLongLivedLog
+ __CFPrefsSignpostsLogForDuration
+ __CFUserNotificationCreateWithReplyPort
+ ___block_descriptor_60_e8_32o40o_e33_v16?0"NSObject<OS_xpc_object>"8ls32l8s40l8
+ __os_signpost_emit_with_name_impl
+ _longLivedLogHandle
+ _mach_continuous_time
+ _os_signpost_enabled
+ _os_signpost_id_make_with_pointer
+ _signpostDetailedHandle
+ _signpostHandle
+ _signpostHandleMinimumThreshold
- GCC_except_table70
- GCC_except_table99
- _OUTLINED_FUNCTION_48
- _OUTLINED_FUNCTION_49
- _OUTLINED_FUNCTION_50
- _OUTLINED_FUNCTION_51
- _OUTLINED_FUNCTION_52
- ___103-[CFPrefsSearchListSource synchronouslySendSystemMessage:andUserMessage:andDirectMessage:replyHandler:]_block_invoke_5
- ___103-[CFPrefsSearchListSource synchronouslySendSystemMessage:andUserMessage:andDirectMessage:replyHandler:]_block_invoke_6
- ___103-[CFPrefsSearchListSource synchronouslySendSystemMessage:andUserMessage:andDirectMessage:replyHandler:]_block_invoke_7
- ___39-[CFPrefsDaemon initWithRole:testMode:]_block_invoke_4
- ___39-[CFPrefsDaemon initWithRole:testMode:]_block_invoke_5
- ___block_descriptor_48_e8_32o40o_e33_v16?0"NSObject<OS_xpc_object>"8ls32l8s40l8
CStrings:
+ "%s/%s"
+ "%{public, signpost.description:begin_time}llu %{public, signpost.description:end_time}llu"
+ "Domain: %{public}@ %{public, signpost.description:begin_time}llu %{public, signpost.description:end_time}llu"
+ "Domain: %{public}@, User: %{private}@, ByHost: %i, Managed: %i %{public, signpost.description:begin_time}llu %{public, signpost.description:end_time}llu"
+ "Domain: %{public}@, User: %{public}@, ByHost: %i, Managed: %i %{public, signpost.description:begin_time}llu %{public, signpost.description:end_time}llu"
+ "Identifier: %{public}@ User: %{private}@ %{public, signpost.description:begin_time}llu %{public, signpost.description:end_time}llu"
+ "Unexpected character `%c` while parsing unicode character escape sequence on line %d"
+ "acceptMessage"
+ "audit"
+ "client-%i %{public, signpost.description:begin_time}llu %{public, signpost.description:end_time}llu"
+ "createDiskWrite"
+ "diskWriteIO"
+ "flushCachesForAppIdentifier"
+ "flushManagedSources"
+ "handleRequest"
+ "respondToFileWrittenToBehindOurBack"
+ "sendSystemAndUserMessage"
+ "sendSystemMessage"
+ "sendUserMessage"
+ "signposts"
+ "signpostsDetailed"
- "cwd"
```
