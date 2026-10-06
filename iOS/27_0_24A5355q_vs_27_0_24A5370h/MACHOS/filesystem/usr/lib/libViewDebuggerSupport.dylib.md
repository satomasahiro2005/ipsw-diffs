## libViewDebuggerSupport.dylib

> `/usr/lib/libViewDebuggerSupport.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2a3a0` | `0x2a34c` | **`-0x54`** |
| `__TEXT.__unwind_info` | `0x3e0` | `0x3d8` | **`-0x8`** |

### Same-size Content Changes

- `__AUTH.__objc_data`
- `__AUTH_CONST.__cfstring`
- `__AUTH_CONST.__const`
- `__AUTH_CONST.__objc_const`
- `__AUTH_CONST.__objc_intobj`
- `__DATA.__data`
- `__DATA_CONST.__objc_selrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_typeref`

### Other Changes

```text
Functions:
~ +[NSIndexPath(DebugHierarchyAdditionsFallback) indexPathWithDebugHierarchyValue:] : 224 -> 220
~ _resetDyldInsertLibraries : 460 -> 436
~ +[DBGViewDebuggerSupport fetchViewHierarchy] : 1436 -> 1428
~ +[DBGViewDebuggerSupport _arrayEncodedIndexPath:] : 220 -> 248
~ +[DBGViewDebuggerSupport _layerShouldSupersedeSnapshot:] : 312 -> 308
~ +[DBGViewDebuggerSupport _populateConstraintInfosArray:forViewHierarchy:] : 1004 -> 988
~ -[UIView(DebugHierarchyHelpers) __dbg_constraintsAffectingLayoutForAxis:] : 456 -> 452
~ -[UIView(DebugHierarchyHelpers) __dbg_snapshotImage] : 688 -> 680
~ -[UIView(DebugHierarchyHelpers) __dbg_snapshotImageRenderedUsingDrawHierarchyInRect] : 1528 -> 1520
~ +[DBGViewDebuggerSupport_iOS primaryWindowFromWindows:] : 372 -> 368
~ +[DBGViewDebuggerSupport_iOS snapshotView:errorString:] : 924 -> 916
~ +[DBGViewDebuggerSupport_iOS _isEffectView:] : 320 -> 316
~ +[DBGViewDebuggerSupport_iOS _renderEffectViewUsingDrawHierarchyInRect:] : 1356 -> 1348
~ _arrayOfObjectPointers : 372 -> 368
~ _$ss17_NativeDictionaryV4copyyyFSS_Say22libViewDebuggerSupport38SpatialSceneDebugRepresentationWrapperCGTg5 : 368 -> 360
```
