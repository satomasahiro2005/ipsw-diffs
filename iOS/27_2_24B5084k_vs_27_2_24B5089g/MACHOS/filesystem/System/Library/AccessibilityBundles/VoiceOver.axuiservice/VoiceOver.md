## VoiceOver

> `/System/Library/AccessibilityBundles/VoiceOver.axuiservice/VoiceOver`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x255d8` | `0x25958` | **`+0x380`** |
| `__TEXT.__objc_methname` | `0x6f76` | `0x70c0` | **`+0x14a`** |
| `__TEXT.__objc_stubs` | `0x4c40` | `0x4d20` | **`+0xe0`** |
| `__TEXT.__objc_methlist` | `0x1e44` | `0x1e84` | **`+0x40`** |
| `__DATA.__objc_selrefs` | `0x1a68` | `0x1aa0` | **`+0x38`** |
| `__DATA.__objc_const` | `0x38c0` | `0x38f0` | **`+0x30`** |
| `__TEXT.__objc_methtype` | `0x1de8` | `0x1df6` | **`+0xe`** |
| `__DATA_CONST.__got` | `0x4b0` | `0x4b8` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x9e8` | `0x9f0` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x200` | `0x204` | **`+0x4`** |
| `__TEXT.__cstring` | `0x1389` | `0x138a` | **`+0x1`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA.__objc_stublist`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-2482.13.0.0.0
+2482.13.1.0.0

-  Functions: 837
-  Symbols:   415
-  CStrings:  1510
+  Functions: 842
+  Symbols:   416
+  CStrings:  1520
Symbols:
+ _OBJC_CLASS_$_NSMapTable
CStrings:
+ "@\"NSMapTable\""
+ "T@\"NSMapTable\",&,N,V_owningScenesByContentViewController"
+ "_contentViewController:isOwnedByScene:"
+ "_forgetOwningSceneForContentViewController:"
+ "_owningScenesByContentViewController"
+ "_setOwningScene:forContentViewController:"
+ "isEqualToNumber:"
+ "owningScenesByContentViewController"
+ "setOwningScenesByContentViewController:"
+ "weakToWeakObjectsMapTable"
```
