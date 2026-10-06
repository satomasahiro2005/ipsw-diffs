## diskimagesiod

> `/usr/libexec/diskimagesiod`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1f0a40` | `0x1f0718` | **`-0x328`** |
| `__DATA_CONST.__const` | `0x396d8` | `0x394b8` | **`-0x220`** |
| `__TEXT.__cstring` | `0x173e5` | `0x1759c` | **`+0x1b7`** |
| `__TEXT.__const` | `0x17647` | `0x175e7` | **`-0x60`** |
| `__TEXT.__oslogstring` | `0x2dab` | `0x2e04` | **`+0x59`** |
| `__TEXT.__unwind_info` | `0xe1c0` | `0xe170` | **`-0x50`** |
| `__TEXT.__gcc_except_tab` | `0x1be68` | `0x1bea0` | **`+0x38`** |
| `__DATA_CONST.__cfstring` | `0x4c40` | `0x4c60` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x6860` | `0x6840` | **`-0x20`** |
| `__TEXT.__objc_methname` | `0x78e1` | `0x78d4` | **`-0xd`** |
| `__DATA.__objc_selrefs` | `0x1f08` | `0x1f00` | **`-0x8`** |
| `__TEXT.__objc_methlist` | `0x3a1c` | `0x3a14` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_typeref`

### Other Changes

```diff

-598.40.3.0.0
+598.40.4.0.0

-  Functions: 11554
+  Functions: 11537

-  CStrings:  4041
+  CStrings:  4052
CStrings:
+ " bytes does not fit before the "
+ " bytes image"
+ " bytes is smaller than its trailer"
+ " exceeds the maximum of "
+ " for "
+ "%.*s: Failed to dup stderr: %d"
+ "%.*s: Failed to open /dev/tty: %d, falling back to stderr"
+ "%.*s: SLA resource has no text form, prompting with a warning instead"
+ "%.*s: SLA: unusable LPic resource"
+ "+[DISLAFrontend(Private) redirectStdoutForDisplay]"
+ "Cannot display SLA: no terminal or stderr to write to"
+ "Malformed SLA LPic resource"
+ "UDIF XML at "
+ "UDIF XML length "
+ "UDIF image of "
+ "WARNING: this disk image contains a software license agreement that cannot be displayed as text. To read it, open the disk image in the Finder. Continuing accepts the license agreement without reading it."
+ "bool DIIOManager::checkForPendingSLA(io_connect_t)"
+ "redirectStdoutForDisplay"
+ "std::expected<CFAutoRelease<CFStringRef>, std::errc> udif::sla::extract_sla_text(const DiskImageUDIF &)"
+ "trailer of a "
- "%.*s: Failed to open /dev/tty: %d"
- "%.*s: SLA resource size (%lld bytes) exceeds maximum (%lld), skipping"
- "+[DISLAFrontend(Private) redirectStdoutToTTY]"
- "/dev/null"
- "CFAutoRelease<CFStringRef> udif::sla::extract_sla_text(const DiskImageUDIF &)"
- "Cannot display SLA: not running in a terminal"
- "SLA resource found but text extraction failed"
- "isStdoutQuietMode"
- "redirectStdoutToTTY"
```
