## QuickLook

> `/System/Library/Frameworks/QuickLook.framework/QuickLook`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x5354` | `0x54ba` | **`+0x166`** |
| `__TEXT.__delay_helper` | `0x948` | `0xa24` | **`+0xdc`** |
| `__TEXT.__eh_frame` | `0x49ac` | `0x48ec` | **`-0xc0`** |
| `__TEXT.__oslogstring` | `0x57d7` | `0x5887` | **`+0xb0`** |
| `__TEXT.__text` | `0xddf58` | `0xddecc` | **`-0x8c`** |
| `__DATA_CONST.__objc_selrefs` | `0x74b8` | `0x74f8` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0xb894` | `0xb8d4` | **`+0x40`** |
| `__TEXT.__const` | `0x3b94` | `0x3b64` | **`-0x30`** |
| `__TEXT.__unwind_info` | `0x4738` | `0x4720` | **`-0x18`** |
| `__AUTH.__data` | `0x1670` | `0x1680` | **`+0x10`** |
| `__DATA.__bss` | `0x34a8` | `0x3498` | **`-0x10`** |
| `__TEXT.__swift5_capture` | `0x1008` | `0xff8` | **`-0x10`** |
| `__AUTH_CONST.__objc_const` | `0x11bb0` | `0x11bb8` | **`+0x8`** |
| `__DATA_CONST.__got` | `0xfe8` | `0xff0` | **`+0x8`** |
| `__TEXT.__constg_swiftt` | `0x1854` | `0x185c` | **`+0x8`** |
| `__DATA.__data` | `0x3480` | `0x3484` | **`+0x4`** |
| `__TEXT.__gcc_except_tab` | `0x175c` | `0x1760` | **`+0x4`** |
| `__TEXT.__swift_as_cont` | `0x4ec` | `0x4f0` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0x1e4` | `0x1e0` | **`-0x4`** |

### Other Changes

```diff

-1034.1.3.0.0
+1034.1.4.0.0

+  - /System/Library/PrivateFrameworks/ManagedConfiguration.framework/ManagedConfiguration

-  Functions: 5745
-  Symbols:   7548
-  CStrings:  906
+  Functions: 5748
+  Symbols:   7556
+  CStrings:  913
Symbols:
+ -[QLPreviewCollection _currentItemCanEnterFullScreen]
+ -[QLPreviewCollection _itemViewControllerCanEnterFullScreen:]
+ -[QLPreviewController itemStore:canEnterFullScreenForItem:]
+ -[QLPreviewController mayMoveContentToUnmanagedDestination]
+ GCC_except_table123
+ GCC_except_table124
+ GCC_except_table159
+ GCC_except_table181
+ GCC_except_table182
+ GCC_except_table185
+ GCC_except_table203
+ GCC_except_table207
+ GCC_except_table92
+ GCC_except_table93
+ _OBJC_CLASS_$_MCProfileConnection
+ _OBJC_CLASS_$_MCProfileConnection$loadHelper_x8
+ ___swift_closure_destructor.105Tm
+ ___swift_closure_destructor.195Tm
+ ___swift_closure_destructor.89Tm
+ ___swift_closure_destructor.93Tm
+ _dlopenHelper$ManagedConfiguration
+ _dlopenHelperFlag$ManagedConfiguration
- GCC_except_table120
- GCC_except_table121
- GCC_except_table158
- GCC_except_table178
- GCC_except_table179
- GCC_except_table183
- GCC_except_table202
- GCC_except_table206
- GCC_except_table90
- GCC_except_table91
- ___swift_closure_destructor.102Tm
- ___swift_closure_destructor.192Tm
- ___swift_closure_destructor.86Tm
- ___swift_closure_destructor.90Tm
CStrings:
+ "/System/Library/PrivateFrameworks/ManagedConfiguration.framework/ManagedConfiguration"
+ "MDM : Managed content may not be moved to an unmanaged destination #PreviewController"
+ "Service side: ignoring %s, the preview collection is already gone"
+ "getPreviewCollectionUUIDWithCompletionHandler(completionHandler:)"
+ "preparePreviewCollectionForInvalidationWithCompletionHandler(completionHandler:)"
+ "setAllowInteractiveTransitions(_:)"
+ "setHostApplicationBundleIdentifier(_:)"
```
