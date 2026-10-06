## spindump_fileparser

> `/usr/libexec/spindump_fileparser`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc092c` | `0xc20c8` | **`+0x179c`** |
| `__TEXT.__oslogstring` | `0x284db` | `0x28949` | **`+0x46e`** |
| `__TEXT.__cstring` | `0x15cbf` | `0x15ed3` | **`+0x214`** |
| `__DATA_CONST.__cfstring` | `0xa200` | `0xa380` | **`+0x180`** |
| `__TEXT.__gcc_except_tab` | `0x3044` | `0x31b4` | **`+0x170`** |
| `__TEXT.__auth_stubs` | `0x1340` | `0x13b0` | **`+0x70`** |
| `__DATA_CONST.__auth_got` | `0x9b0` | `0x9e8` | **`+0x38`** |
| `__TEXT.__const` | `0x250` | `0x280` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x1570` | `0x1590` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x4420` | `0x4440` | **`+0x20`** |
| `__DATA.__bss` | `0x808` | `0x818` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x220` | `0x230` | **`+0x10`** |
| `__TEXT.__objc_methname` | `0x4370` | `0x437e` | **`+0xe`** |
| `__DATA.__objc_selrefs` | `0x1220` | `0x1228` | **`+0x8`** |
| `__DATA_CONST.__auth_ptr` | `0x20` | `0x28` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0xce0` | `0xce8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-440.0.0.0.0
+443.0.0.0.0

-  Functions: 1820
-  Symbols:   387
-  CStrings:  3959
+  Functions: 1831
+  Symbols:   394
+  CStrings:  3981
Symbols:
+ _SANanosecondsFromMachTimeUsingTimebase
+ _ktrace_file_earliest_continuous_time
+ _ktrace_file_latest_continuous_time
+ _ktrace_file_supports_continuous_time
+ _ktrace_file_timebase
+ _mach_timebase_info
+ _statfs
CStrings:
+ "No mach continuous time in WR tailspin %s"
+ "No overlap in WR tailspin %s"
+ "PowerExceptions"
+ "Unable to format: No mach continuous time in WR tailspin %s"
+ "Unable to format: No overlap in WR tailspin %s"
+ "Unable to format: Unable to get earliest ktrace machcont timestamp in WR tailspin %s: %d (%s)"
+ "Unable to format: Unable to get ktrace mach timebase, assuming native timebase in WR tailspin %s: %d (%s)"
+ "Unable to format: Unable to get latest ktrace machcont timestamp in WR tailspin %s: %d (%s)"
+ "Unable to format: Unable to open WR tailspin %s: %d (%s)"
+ "Unable to format: Unable to statfs %s: %d (%s)"
+ "Unable to format: ktrace mach timebase %d/%d, assuming native timebase in WR tailspin %s"
+ "Unable to format: ktrace unavailable for WR tailspin %s"
+ "Unable to get earliest ktrace machcont timestamp in WR tailspin %s: %d (%s)"
+ "Unable to get ktrace mach timebase, assuming native timebase in WR tailspin %s: %d (%s)"
+ "Unable to get latest ktrace machcont timestamp in WR tailspin %s: %d (%s)"
+ "Unable to open WR tailspin %s: %d (%s)"
+ "Unable to statfs %s: %d (%s)"
+ "bug_subtype"
+ "codesigningID"
+ "ktrace mach timebase %d/%d, assuming native timebase in WR tailspin %s"
+ "ktrace unavailable for WR tailspin %s"
+ "overlapdurationms"
```
