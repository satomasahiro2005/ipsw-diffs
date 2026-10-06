## IMDebug

> `/private/var/staged_system_apps/Podcasts.app/Frameworks/IMDebug.framework/IMDebug`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x787c` | `0x7864` | **`-0x18`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-4027.100.59.0.0
+4027.100.70.0.0
Functions:
~ -[UIViewController(RecursiveDescription) addDescriptionToString:indentLevel:] : 448 -> 444
~ +[IMDebugDataManager writeDebugDataWithProgress:] : 1828 -> 1816
~ ___55-[IMDebugViewControllerHierarchyDataProvider debugData]_block_invoke : 384 -> 380
~ ___45-[IMDebugViewHierarchyDataProvider debugData]_block_invoke : 468 -> 464
~ _do_extract_currentfile : 936 -> 944
~ _main : 660 -> 656
~ _unzOpen2 : 964 -> 960
~ _unzOpenCurrentFile3 : 1448 -> 1444
~ _unzReadCurrentFile : 844 -> 828
~ _zipOpen2 : 1420 -> 1416
~ _add_data_in_datablock : 324 -> 332
~ _zipOpenNewFileInZip4 : 2484 -> 2500
~ _zipWriteInFileInZip : 340 -> 332
~ _zipFlushWriteBuffer : 220 -> 228
```
