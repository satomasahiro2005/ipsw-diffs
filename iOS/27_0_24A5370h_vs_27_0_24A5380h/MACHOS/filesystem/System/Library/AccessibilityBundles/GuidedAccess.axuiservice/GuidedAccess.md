## GuidedAccess

> `/System/Library/AccessibilityBundles/GuidedAccess.axuiservice/GuidedAccess`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2ec80` | `0x2f1b0` | **`+0x530`** |
| `__TEXT.__oslogstring` | `0xdec` | `0xec3` | **`+0xd7`** |
| `__TEXT.__objc_methname` | `0xc439` | `0xc4fc` | **`+0xc3`** |
| `__TEXT.__objc_stubs` | `0x8da0` | `0x8e20` | **`+0x80`** |
| `__TEXT.__objc_methlist` | `0x367c` | `0x36bc` | **`+0x40`** |
| `__TEXT.__objc_methtype` | `0x24b7` | `0x24ee` | **`+0x37`** |
| `__DATA.__objc_selrefs` | `0x2a40` | `0x2a68` | **`+0x28`** |
| `__DATA_CONST.__const` | `0x1ae8` | `0x1b08` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0xd38` | `0xd50` | **`+0x18`** |
| `__DATA.__objc_const` | `0x47b0` | `0x47b8` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x4e8` | `0x4f0` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0xe0` | `0xe8` | **`+0x8`** |
| `__TEXT.__gcc_except_tab` | `0x970` | `0x974` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`

### Other Changes

```diff

-1057.0.0.0.0
+1059.0.0.0.0

-  Functions: 1171
-  Symbols:   663
-  CStrings:  2543
+  Functions: 1176
+  Symbols:   662
+  CStrings:  2553
Symbols:
- _OBJC_CLASS_$_UIWindow
CStrings:
+ "@\"UIViewController\"24@0:8@\"GAXFeatureViewController\"16"
+ "Overlay VC reused but scene not ready, re-requesting scene"
+ "_contentMargin"
+ "_dismissAnyPresentedModalInTreeOf:"
+ "_viewControllerForPresentingOptions"
+ "_viewControllerWithPresentedModalInTreeOf:"
+ "childViewControllers"
+ "transitionToMode: IPC failed with error: %{public}@"
+ "transitionToMode: _clientMessenger is nil, IPC will fail silently"
+ "transitionToMode: requesting mode %lu"
+ "viewControllerForPresentingOptionsForFeatureViewController:"
+ "workspaceNavigationBarMinimumTopPadding"
- "_applicationKeyWindow"
- "workspaceNavigationBarTopPadding"
```
