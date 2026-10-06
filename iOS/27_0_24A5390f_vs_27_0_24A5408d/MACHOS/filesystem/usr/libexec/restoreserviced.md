## restoreserviced

> `/usr/libexec/restoreserviced`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x142e8` | `0x13f24` | **`-0x3c4`** |
| `__TEXT.__cstring` | `0x7cf3` | `0x79c8` | **`-0x32b`** |
| `__DATA_CONST.__cfstring` | `0x3fe0` | `0x4000` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0x1865` | `0x1883` | **`+0x1e`** |
| `__TEXT.__unwind_info` | `0x530` | `0x520` | **`-0x10`** |
| `__DATA.__objc_selrefs` | `0x758` | `0x760` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0xcdc` | `0xce4` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_superrefs`

### Other Changes

```diff

-48.0.0.0.0
+48.0.1.0.0

-  Functions: 548
+  Functions: 537

-  CStrings:  1474
+  CStrings:  1454
CStrings:
+ "hasExclusiveUSBHostDeviceMode"
+ "usb-host-device-exclusive"
- "   ^^ Found requested tag."
- "0 bytes read, IMG4 image hit end of block device? - fail errno=%d.."
- "AMRestorePartitionFWCopyTagData"
- "Bytes read didn't match derLen."
- "Failed to allocate Img4Data"
- "Failed to read terminator bytes."
- "Invalid termination bytes: [0x%02x, 0x%02x]"
- "Item %02d, der.length=%8d, Bad Img4 inside valid DER sequence. (derstat=%d)"
- "Item %02d, offset=%8d, der.length=%8d, img4Tag=[%@]"
- "No DER segments found."
- "No more segments. (derstat=%d)"
- "Too Many DER segments!"
- "Unable to open inURL %@"
- "Unable to rewind to start of IMG4 segment lseek=%ll, errno=%d."
- "Unable to seek to terminator segment errno=%d."
- "Unable to set F_NOCACHE on firmware storage"
- "_AMRestorePartitionOpenFileWithURL"
- "failed to allocate DER chunk buffer"
- "failed to allocate IMG4buffer"
- "failed to convert url to file system representation"
- "inURL is NULL"
- "open() returned %d, %s"
```
