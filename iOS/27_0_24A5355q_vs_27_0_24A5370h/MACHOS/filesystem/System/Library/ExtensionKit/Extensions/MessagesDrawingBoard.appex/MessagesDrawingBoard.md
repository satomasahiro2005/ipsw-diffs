## MessagesDrawingBoard

> `/System/Library/ExtensionKit/Extensions/MessagesDrawingBoard.appex/MessagesDrawingBoard`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x80a4` | `0xa7f4` | **`+0x2750`** |
| `__DATA.__bss` | `0x380` | `0x780` | **`+0x400`** |
| `__DATA_CONST.__const` | `0x280` | `0x538` | **`+0x2b8`** |
| `__TEXT.__eh_frame` | `0x3e0` | `0x650` | **`+0x270`** |
| `__TEXT.__const` | `0x454` | `0x6b4` | **`+0x260`** |
| `__TEXT.__auth_stubs` | `0xb10` | `0xd10` | **`+0x200`** |
| `__DATA_CONST.__auth_got` | `0x590` | `0x690` | **`+0x100`** |
| `__TEXT.__oslogstring` | `0xe9` | `0x1d2` | **`+0xe9`** |
| `__TEXT.__unwind_info` | `0x278` | `0x360` | **`+0xe8`** |
| `__DATA_CONST.__auth_ptr` | `0x178` | `0x230` | **`+0xb8`** |
| `__TEXT.__swift5_fieldmd` | `0xcc` | `0x174` | **`+0xa8`** |
| `__DATA.__data` | `0x328` | `0x3b8` | **`+0x90`** |
| `__TEXT.__swift5_typeref` | `0x20c` | `0x29c` | **`+0x90`** |
| `__DATA_CONST.__got` | `0xe0` | `0x158` | **`+0x78`** |
| `__TEXT.__constg_swiftt` | `0x2a8` | `0x310` | **`+0x68`** |
| `__TEXT.__swift5_capture` | `0xb4` | `0x108` | **`+0x54`** |
| `__TEXT.__swift5_reflstr` | `0x130` | `0x17a` | **`+0x4a`** |
| `__TEXT.__cstring` | `0xa3` | `0xe3` | **`+0x40`** |
| `__TEXT.__objc_stubs` | `0x960` | `0x920` | **`-0x40`** |
| `__DATA.__objc_const` | `0x370` | `0x390` | **`+0x20`** |
| `__TEXT.__swift5_proto` | `0x1c` | `0x3c` | **`+0x20`** |
| `__DATA.__objc_data` | `0x2f8` | `0x310` | **`+0x18`** |
| `__TEXT.__swift5_assocty` | `0x30` | `0x48` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x14` | `0x28` | **`+0x14`** |
| `__TEXT.__swift_as_cont` | `0x28` | `0x3c` | **`+0x14`** |
| `__DATA.__objc_selrefs` | `0x3b0` | `0x3a0` | **`-0x10`** |
| `__TEXT.__objc_methname` | `0xace` | `0xabe` | **`-0x10`** |
| `__TEXT.__swift5_types` | `0xc` | `0x18` | **`+0xc`** |
| `__TEXT.__objc_methtype` | `0x15d` | `0x153` | **`-0xa`** |
| `__TEXT.__swift_as_entry` | `0x1c` | `0x24` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x14` | `0x1c` | **`+0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-371.4.100.0.0
+373.1.0.0.0

-  Functions: 138
-  Symbols:   152
-  CStrings:  172
+  Functions: 212
+  Symbols:   167
+  CStrings:  179
Symbols:
+ __swiftImmortalRefCount
+ _malloc_size
+ _memmove
+ _swift_arrayInitWithCopy
+ _swift_arrayInitWithTakeBackToFront
+ _swift_arrayInitWithTakeFrontToBack
+ _swift_bridgeObjectRetain
+ _swift_cvw_assignWithCopy
+ _swift_cvw_assignWithTake
+ _swift_cvw_destroy
+ _swift_cvw_initWithCopy
+ _swift_cvw_initializeBufferWithCopyOfBuffer
+ _swift_isUniquelyReferenced_nonNull_native
+ _swift_release_x9
+ _swift_retain_x21
+ _swift_task_isCancelledWithFlags
- _objc_retain_x24
CStrings:
+ "Cancel tapped — cancelling any in-flight export"
+ "Export cancelled before render started"
+ "Export cancelled during render — discarding result, not inserting"
+ "Export cancelled — skipping finish"
+ "animateWithDuration:animations:"
+ "contentTypeIdentifiers"
+ "exportTask"
+ "isSaving"
+ "itemCount"
+ "locationX"
+ "locationY"
+ "setAlpha:"
+ "setCustomView:"
+ "whiteColor"
- "$__lazy_storage_$_exportSpinner"
- "centerXAnchor"
- "centerYAnchor"
- "removeFromSuperview"
- "setHidesWhenStopped:"
- "stopAnimating"
- "superview"
```
