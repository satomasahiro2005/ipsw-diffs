## NANDTaskScheduler

> `/usr/libexec/NANDTaskScheduler`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xe0fc` | `0xf290` | **`+0x1194`** |
| `__TEXT.__oslogstring` | `0x2b63` | `0x2e6b` | **`+0x308`** |
| `__TEXT.__cstring` | `0x10c9` | `0x1235` | **`+0x16c`** |
| `__TEXT.__objc_methname` | `0x1522` | `0x15fe` | **`+0xdc`** |
| `__TEXT.__objc_stubs` | `0x1540` | `0x1600` | **`+0xc0`** |
| `__TEXT.__auth_stubs` | `0x780` | `0x810` | **`+0x90`** |
| `__DATA_CONST.__auth_got` | `0x3d0` | `0x418` | **`+0x48`** |
| `__DATA_CONST.__const` | `0x650` | `0x690` | **`+0x40`** |
| `__TEXT.__gcc_except_tab` | `0x258` | `0x294` | **`+0x3c`** |
| `__DATA.__objc_selrefs` | `0x6a8` | `0x6d8` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x2e8` | `0x318` | **`+0x30`** |
| `__TEXT.__objc_methtype` | `0x32c` | `0x352` | **`+0x26`** |
| `__DATA_CONST.__cfstring` | `0xa00` | `0xa20` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x4ac` | `0x4c4` | **`+0x18`** |
| `__DATA.__bss` | `0x49` | `0x59` | **`+0x10`** |
| `__TEXT.__const` | `0x1a0` | `0x1b0` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x1b8` | `0x1c0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`

### Other Changes

```diff

-835.0.0.0.0
+843.0.0.0.0

-  Functions: 241
-  Symbols:   189
-  CStrings:  701
+  Functions: 251
+  Symbols:   199
+  CStrings:  741
Symbols:
+ _NSURLIsRegularFileKey
+ _fclose
+ _fopen
+ _fputc
+ _localtime_r
+ _objc_release_x20
+ _os_parse_boot_arg_int
+ _strftime
+ _time
+ _vfprintf
CStrings:
+ "  graft[%u]: enrolled %lu file(s) from %s"
+ "  graft[%u]: enumerating %s"
+ "  graft[%u]: enumeration error at %s: %s"
+ "  graft[%u]: failed to create enumerator"
+ "  graft[%u]: failed to unenroll DMG inode %llu: %s"
+ "  graft[%u]: fsgetpath for graft dir inode %llu failed: %s"
+ "  graft[%u]: register failed for %s: %s"
+ "%Y-%m-%d %H:%M:%S"
+ "/private/var/db/NANDTaskScheduler/nts_persistent_1.log"
+ "/private/var/db/NANDTaskScheduler/nts_persistent_2.log"
+ "ALIGNED: No DMG enrollments to expand, skipping expansion."
+ "B40@0:8Q16@24Q32"
+ "Failed to check inode registration: %{public}@"
+ "File size (%lld bytes) is below minimum threshold (%luMB): %@"
+ "IS went idle with saved prio %d during deferral; skipping to BDR."
+ "ISTK postBoot defer."
+ "ISTK postBoot exit."
+ "ISTK postBoot stage %u"
+ "ISTK prio %u , stage %u"
+ "ISTK prio %u - defer."
+ "ISTK prio %u - exit."
+ "Q48@0:8@16Q24Q32^@40"
+ "QUERY prio %u , result 0x%x, new run."
+ "QUERY prio %u , result 0x%x, resume %d."
+ "Registering file for alignment: %{public}@ (type: %lu, minSizeMB: %lu)"
+ "[%s] "
+ "a"
+ "caseInsensitiveCompare:"
+ "dmg"
+ "expand_aligned_DMGs: APFSIOC_GET_GRAFT_INFO failed: %s"
+ "expand_aligned_DMGs: calloc failed"
+ "expand_aligned_DMGs: checking %u graft(s) for aligned enrollments"
+ "expand_aligned_DMGs: no grafts on volume"
+ "expand_aligned_DMGs: statfs failed: %s"
+ "fileURLWithFileSystemRepresentation:isDirectory:relativeToURL:"
+ "getResourceValue:forKey:error:"
+ "graft[%u/%u]] not enrolled."
+ "isInodeRegistered:mountPoint:alignmentType:"
+ "iter# %u - IDSTK status? %u, gcDest tpt? %u"
+ "nts-prst-log"
+ "pathExtension"
+ "registerFile:alignmentType:minSizeMB:error:"
+ "w"
- "File size (%lld bytes) is below minimum threshold (100MB): %@"
- "IS went idle with saved prio %d, do not proceed."
- "iter# %u - IDSTK status? %u"
```
