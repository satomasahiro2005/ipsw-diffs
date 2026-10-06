## AEBookPlugins

> `/private/var/staged_system_apps/Books.app/Frameworks/AEBookPlugins.framework/AEBookPlugins`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x13349c` | `0x13359c` | **`+0x100`** |
| `__DATA_CONST.__got` | `0x15d0` | `0x16c0` | **`+0xf0`** |
| `__TEXT.__objc_methname` | `0x37fe9` | `0x37fb9` | **`-0x30`** |
| `__DATA_CONST.__const` | `0x4340` | `0x4368` | **`+0x28`** |
| `__TEXT.__objc_stubs` | `0x29560` | `0x29540` | **`-0x20`** |
| `__TEXT.__objc_methlist` | `0x182cc` | `0x182e4` | **`+0x18`** |
| `__DATA.__objc_selrefs` | `0xd6e0` | `0xd6d8` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x53b0` | `0x53b8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_ivar`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__cstring`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methtype`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-6636.0.0.0.0
+6643.0.0.0.0

-  Functions: 8419
-  Symbols:   2309
-  CStrings:  12177
+  Functions: 8421
+  Symbols:   2311
+  CStrings:  12176
Symbols:
+ __UIWindowSceneDidBeginLiveResizeNotification
+ __UIWindowSceneDidEndLiveResizeNotification
CStrings:
+ "B24@0:8@\"UIZoomTransitionInteractionContext\"16"
+ "TB,N,V_inWindowSceneLiveResize"
+ "_bk_windowSceneDidBeginLiveResize:"
+ "_bk_windowSceneDidEndLiveResize:"
+ "_inWindowSceneLiveResize"
+ "inWindowSceneLiveResize"
+ "setInWindowSceneLiveResize:"
+ "willBegin"
- "B24@0:8@\"_UIViewControllerTransitionInteractionContext\"16"
- "T@\"NSLayoutConstraint\",&,N,V_topBarTopConstraint"
- "_setOverrideBackgroundExtension:"
- "_topBarTopConstraint"
- "_updateToolbarPositionAndBackgroundExtension"
- "defaultStatusBarHeightInOrientation:"
- "proposedBeginState"
- "setTopBarTopConstraint:"
- "topBarTopConstraint"
```
