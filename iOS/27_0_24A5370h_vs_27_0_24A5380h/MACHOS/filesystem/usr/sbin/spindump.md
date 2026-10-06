## spindump

> `/usr/sbin/spindump`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb76d0` | `0xb8e10` | **`+0x1740`** |
| `__TEXT.__oslogstring` | `0x2697f` | `0x26ded` | **`+0x46e`** |
| `__TEXT.__cstring` | `0x15117` | `0x1532b` | **`+0x214`** |
| `__DATA_CONST.__cfstring` | `0x9be0` | `0x9d60` | **`+0x180`** |
| `__TEXT.__gcc_except_tab` | `0x2f24` | `0x3094` | **`+0x170`** |
| `__TEXT.__auth_stubs` | `0x12e0` | `0x1370` | **`+0x90`** |
| `__DATA_CONST.__auth_got` | `0x980` | `0x9c8` | **`+0x48`** |
| `__TEXT.__const` | `0x240` | `0x270` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x1520` | `0x1540` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x4180` | `0x41a0` | **`+0x20`** |
| `__DATA.__bss` | `0x808` | `0x818` | **`+0x10`** |
| `__TEXT.__objc_methname` | `0x4257` | `0x4265` | **`+0xe`** |
| `__DATA.__objc_selrefs` | `0x11b8` | `0x11c0` | **`+0x8`** |
| `__DATA_CONST.__auth_ptr` | `0x18` | `0x20` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x218` | `0x220` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0xcc8` | `0xcd0` | **`+0x8`** |

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

-  Functions: 1808
-  Symbols:   380
-  CStrings:  3856
+  Functions: 1818
+  Symbols:   389
+  CStrings:  3878
Symbols:
+ _SANanosecondsFromMachTimeUsingTimebase
+ _ktrace_file_close
+ _ktrace_file_earliest_continuous_time
+ _ktrace_file_latest_continuous_time
+ _ktrace_file_open
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
