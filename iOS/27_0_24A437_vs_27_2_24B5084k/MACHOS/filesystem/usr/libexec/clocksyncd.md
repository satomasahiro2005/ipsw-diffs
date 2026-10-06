## clocksyncd

> `/usr/libexec/clocksyncd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3b498` | `0x3bd88` | **`+0x8f0`** |
| `__TEXT.__cstring` | `0x2866` | `0x2a3d` | **`+0x1d7`** |
| `__TEXT.__oslogstring` | `0x5945` | `0x5b02` | **`+0x1bd`** |
| `__TEXT.__objc_stubs` | `0x5a40` | `0x5a80` | **`+0x40`** |
| `__TEXT.__auth_stubs` | `0xd40` | `0xd70` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0xe80` | `0xea8` | **`+0x28`** |
| `__TEXT.__objc_methname` | `0x91d0` | `0x91f3` | **`+0x23`** |
| `__DATA_CONST.__cfstring` | `0x1f60` | `0x1f80` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0x6b8` | `0x6d0` | **`+0x18`** |
| `__DATA.__objc_selrefs` | `0x1db0` | `0x1dc0` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-1501.6.0.0.0
+1510.7.0.0.0

-  Functions: 1534
-  Symbols:   284
-  CStrings:  2466
+  Functions: 1544
+  Symbols:   287
+  CStrings:  2484
Symbols:
+ _objc_retain_x26
+ _objc_retain_x27
+ _strcmp
CStrings:
+ "%@: %s: Refusing a nil UUID\n"
+ "%@: %s: Refusing preferred UUID %@, already registered to %@\n"
+ "%@: Refusing to serialize a malformed trigger timing\n"
+ "%s: Caller pid %d lacks %s, denying mock sync entity request\n"
+ "%s: Failed to deinitialize default MSG device handle. Error: 0x%x\n"
+ "%s: No active XPC connection, denying mock sync entity request\n"
+ "%s: Refusing %lu trigger timings, limit is %lu\n"
+ "%s: Refusing trigger timing encoded as '%s', require '%s'\n"
+ "-[TSDMSGService init]"
+ "-[TSDSyncEntityManager createMockSSAMEntityWithTriggerTiming:machTime:persist:preferredUUID:reply:]"
+ "-[TSDSyncEntityManager createMockSSAMEntityWithTriggerTiming:machTime:persist:preferredUUID:reply:]_block_invoke"
+ "-[TSDSyncEntityManager getSyncEntityForUUID:withReply:]"
+ "-[TSDSyncEntityManager removeAllMockSSAMEntriesWithReply:]"
+ "-[TSDSyncEntityManager removeMockSSAMEntityWithUUID:reply:]"
+ "1510.7"
+ "TSFixed64_64FromValue"
+ "com.apple.private.timesync.mock-entity"
+ "getValue:size:"
+ "objCType"
+ "valueForEntitlement:"
- "1501.6"
- "getValue:"
```
