## deleted_helper

> `/System/Library/PrivateFrameworks/CacheDelete.framework/deleted_helper`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x9324` | `0x9754` | **`+0x430`** |
| `__TEXT.__oslogstring` | `0x1cc2` | `0x1dd2` | **`+0x110`** |
| `__TEXT.__cstring` | `0x874` | `0x8bf` | **`+0x4b`** |
| `__TEXT.__auth_stubs` | `0x7c0` | `0x800` | **`+0x40`** |
| `__DATA_CONST.__const` | `0x4e0` | `0x508` | **`+0x28`** |
| `__DATA_CONST.__auth_got` | `0x3f0` | `0x410` | **`+0x20`** |
| `__DATA_CONST.__cfstring` | `0x600` | `0x620` | **`+0x20`** |
| `__DATA.__bss` | `0x68` | `0x70` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x98` | `0xa0` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x188` | `0x190` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-901.0.0.0.1
+904.0.0.0.0

-  Functions: 80
-  Symbols:   367
-  CStrings:  326
+  Functions: 82
+  Symbols:   375
+  CStrings:  331
Symbols:
+ GCC_except_table34
+ GCC_except_table37
+ GCC_except_table46
+ GCC_except_table51
+ __RegisterCacheDeleteOrphanDirHandlerService_block_invoke_2
+ __RegisterCacheDeleteOrphanDirHandlerService_block_invoke_3
+ ___block_descriptor_40_e8_32s_e5_v8?0ls32l8
+ __dispatch_source_type_timer
+ _dispatch_source_cancel
+ _dispatch_source_set_timer
+ _dispatch_time
+ _objc_retain_x25
+ _tokenStringForToken
- GCC_except_table35
- GCC_except_table38
- GCC_except_table44
- GCC_except_table49
- _objc_retain_x24
CStrings:
+ "%@ performSingleVolumePurge: Starting purge on %@ for %llu bytes"
+ "%@ performSingleVolumePurge: Volume %@ total purged %llu bytes"
+ "%@ performSingleVolumePurge: escalation range %d -> %d (requested urgency: %d)"
+ "%@ performSingleVolumePurge: fsctl failed on %@ with error: %s"
+ "%@ performSingleVolumePurge: fsctl purged %llu bytes (all services) at urgency %d"
+ "%@ performSingleVolumePurge: fsctl purged %llu bytes from service %@ at urgency %d"
+ "%@ performSingleVolumePurge: requesting %llu bytes (all services) at urgency %d"
+ "%@ performSingleVolumePurge: requesting %llu bytes from service %@ at urgency %d"
+ "CACHE_DELETE_FSPURGE_SKIP_ESCALATION"
+ "OSASubmission already in flight, skipping for this purge."
+ "OSASubmission timed out after 20s, proceeding with purge."
+ "com.apple.cache_delete.osa_submission"
- "performSingleVolumePurge: Starting purge on %@ for %llu bytes"
- "performSingleVolumePurge: Volume %@ total purged %llu bytes"
- "performSingleVolumePurge: fsctl failed on %@ with error: %s"
- "performSingleVolumePurge: fsctl purged %llu bytes (all services)"
- "performSingleVolumePurge: fsctl purged %llu bytes from service %@"
- "performSingleVolumePurge: requesting %llu bytes (all services)"
- "performSingleVolumePurge: requesting %llu bytes from service %@"
```
