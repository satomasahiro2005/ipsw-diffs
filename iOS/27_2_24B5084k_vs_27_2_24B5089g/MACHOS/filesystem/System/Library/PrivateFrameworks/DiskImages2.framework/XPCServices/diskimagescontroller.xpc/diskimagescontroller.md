## diskimagescontroller

> `/System/Library/PrivateFrameworks/DiskImages2.framework/XPCServices/diskimagescontroller.xpc/diskimagescontroller`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1f49b0` | `0x1f4e2c` | **`+0x47c`** |
| `__TEXT.__cstring` | `0x18608` | `0x186b8` | **`+0xb0`** |
| `__TEXT.__gcc_except_tab` | `0x1c0dc` | `0x1c138` | **`+0x5c`** |
| `__TEXT.__oslogstring` | `0x1aac` | `0x1ae3` | **`+0x37`** |
| `__TEXT.__objc_stubs` | `0x5c00` | `0x5be0` | **`-0x20`** |
| `__TEXT.__objc_methname` | `0x6803` | `0x67f6` | **`-0xd`** |
| `__DATA.__objc_selrefs` | `0x1b70` | `0x1b68` | **`-0x8`** |
| `__TEXT.__objc_methlist` | `0x3494` | `0x348c` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_typeref`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-598.40.3.0.0
+598.40.4.0.0

-  CStrings:  3665
+  CStrings:  3673
CStrings:
+ " bytes does not fit before the "
+ " bytes image"
+ " bytes is smaller than its trailer"
+ " exceeds the maximum of "
+ " for "
+ "%.*s: Failed to dup stderr: %d"
+ "%.*s: Failed to open /dev/tty: %d, falling back to stderr"
+ "+[DISLAFrontend(Private) redirectStdoutForDisplay]"
+ "598.40.4"
+ "Cannot display SLA: no terminal or stderr to write to"
+ "UDIF XML at "
+ "UDIF XML length "
+ "UDIF image of "
+ "redirectStdoutForDisplay"
+ "trailer of a "
- "%.*s: Failed to open /dev/tty: %d"
- "+[DISLAFrontend(Private) redirectStdoutToTTY]"
- "/dev/null"
- "598.40.3"
- "Cannot display SLA: not running in a terminal"
- "isStdoutQuietMode"
- "redirectStdoutToTTY"
```
