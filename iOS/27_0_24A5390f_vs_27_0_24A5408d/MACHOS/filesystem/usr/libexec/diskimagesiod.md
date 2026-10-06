## diskimagesiod

> `/usr/libexec/diskimagesiod`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1ed170` | `0x1ef5cc` | **`+0x245c`** |
| `__DATA_CONST.__const` | `0x38988` | `0x391f8` | **`+0x870`** |
| `__TEXT.__gcc_except_tab` | `0x1bc70` | `0x1bdbc` | **`+0x14c`** |
| `__TEXT.__const` | `0x17457` | `0x17597` | **`+0x140`** |
| `__TEXT.__unwind_info` | `0xe000` | `0xe120` | **`+0x120`** |
| `__TEXT.__cstring` | `0x172ec` | `0x173e5` | **`+0xf9`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_typeref`

### Other Changes

```diff

-598.0.0.0.0
+598.0.1.0.0

-  Functions: 11457
+  Functions: 11520

-  CStrings:  4035
+  CStrings:  4041
CStrings:
+ ", allocated: "
+ "Allocated after defrag: "
+ "Diskimageuio: Failed to create resizer: "
+ "Nothing to defrag"
+ "Starting ASIF defrag, used size: "
+ "io_result_t details::for_each_sg_in_vec_internal(Fn &&, sg_vec_ref::iterator, sg_vec::iterator, size_t, bool) [Fn = (lambda at /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/DiskImages2/app/disk_images/formats/asif.cpp:2064:32)]"
+ "io_result_t details::for_each_sg_in_vec_internal(Fn &&, sg_vec_ref::iterator, sg_vec::iterator, size_t, bool) [Fn = (lambda at /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/DiskImages2/app/disk_images/formats/asif.cpp:2098:32)]"
+ "static expected<diskimage_resizer, diskimage_err> diskimage_uio::diskimage_resizer::create(diskimage_open_params &&)"
- "io_result_t details::for_each_sg_in_vec_internal(Fn &&, sg_vec_ref::iterator, sg_vec::iterator, size_t, bool) [Fn = (lambda at /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/DiskImages2/app/disk_images/formats/asif.cpp:2035:32)]"
- "io_result_t details::for_each_sg_in_vec_internal(Fn &&, sg_vec_ref::iterator, sg_vec::iterator, size_t, bool) [Fn = (lambda at /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/DiskImages2/app/disk_images/formats/asif.cpp:2069:32)]"
```
