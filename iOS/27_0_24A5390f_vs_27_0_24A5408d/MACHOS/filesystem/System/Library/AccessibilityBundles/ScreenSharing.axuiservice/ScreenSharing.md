## ScreenSharing

> `/System/Library/AccessibilityBundles/ScreenSharing.axuiservice/ScreenSharing`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6614` | `0x6ed0` | **`+0x8bc`** |
| `__TEXT.__objc_methname` | `0x1d9d` | `0x205c` | **`+0x2bf`** |
| `__TEXT.__objc_stubs` | `0x1b20` | `0x1ca0` | **`+0x180`** |
| `__TEXT.__objc_methtype` | `0x74c` | `0x885` | **`+0x139`** |
| `__DATA.__objc_const` | `0x1d18` | `0x1de0` | **`+0xc8`** |
| `__TEXT.__oslogstring` | `0x400` | `0x496` | **`+0x96`** |
| `__TEXT.__objc_methlist` | `0xa94` | `0xb24` | **`+0x90`** |
| `__DATA.__objc_selrefs` | `0x8e0` | `0x948` | **`+0x68`** |
| `__DATA.__data` | `0x180` | `0x1e0` | **`+0x60`** |
| `__TEXT.__auth_stubs` | `0x590` | `0x5f0` | **`+0x60`** |
| `__DATA_CONST.__cfstring` | `0x360` | `0x3a0` | **`+0x40`** |
| `__TEXT.__cstring` | `0x18e` | `0x1c0` | **`+0x32`** |
| `__DATA_CONST.__auth_got` | `0x2d8` | `0x308` | **`+0x30`** |
| `__TEXT.__objc_classname` | `0xb5` | `0xe3` | **`+0x2e`** |
| `__TEXT.__unwind_info` | `0x258` | `0x280` | **`+0x28`** |
| `__DATA.__objc_ivar` | `0xc8` | `0xd8` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x100` | `0x108` | **`+0x8`** |
| `__DATA_CONST.__objc_protolist` | `0x20` | `0x28` | **`+0x8`** |
| `__TEXT.__const` | `0x88` | `0x90` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_superrefs`

### Other Changes

```diff

-166.11.0.0.0
+166.13.0.0.0

-  Functions: 187
-  Symbols:   149
-  CStrings:  530
+  Functions: 197
+  Symbols:   156
+  CStrings:  562
Symbols:
+ _CGRectIsEmpty
+ _CGRectIsNull
+ _CGRectNull
+ _OBJC_CLASS_$_AXUIClientMessenger
+ _objc_destroyWeak
+ _objc_loadWeakRetained
+ _objc_setProperty_nonatomic_copy
+ _objc_storeWeak
- _OBJC_CLASS_$_UIScreen
CStrings:
+ "@\"<SSUICursorViewControllerDisplayBoundsDelegate>\""
+ "@\"NSString\""
+ "SSUICursorSceneClientIdentifier"
+ "SSUICursorViewControllerDisplayBoundsDelegate"
+ "T@\"<SSUICursorViewControllerDisplayBoundsDelegate>\",W,N,V_displayBoundsDelegate"
+ "T@\"NSString\",C,N,V_cursorClientIdentifier"
+ "_convertRectToSceneReferenceSpace:"
+ "_cursorClientIdentifier"
+ "_displayBoundsDelegate"
+ "_lastNotifiedDisplayBounds"
+ "_notifyDisplayBoundsDelegateIfNeeded"
+ "addContentViewController:withUserInteractionEnabled:forService:forSceneClientIdentifier:"
+ "clientMessengerWithIdentifier:"
+ "currentDisplayBoundsInSceneReferenceSpace"
+ "cursorClientIdentifier"
+ "cursorViewController:didUpdateDisplayBounds:"
+ "displayBounds"
+ "displayBounds changed, notifying delegate: %s"
+ "displayBoundsDelegate"
+ "mBaseSize"
+ "pushing displayBounds %s to client"
+ "releaseBitmapContexts"
+ "resizeFrameForDisplay:screenBounds:"
+ "resizeToFit:"
+ "sendAsynchronousMessage:withIdentifier:targetAccessQueue:completion:"
+ "setActiveSceneTrackingEnabled:forSceneClientIdentifier:"
+ "setCursorClientIdentifier:"
+ "setDisplayBoundsDelegate:"
+ "slate base size changed from (%f, %f) to (%f, %f), rebuilding bitmap"
+ "v56@0:8@\"SSUICursorViewController\"16{CGRect={CGPoint=dd}{CGSize=dd}}24"
+ "v56@0:8@16{CGRect={CGPoint=dd}{CGSize=dd}}24"
+ "viewDidLayoutSubviews"
+ "{CGRect={CGPoint=dd}{CGSize=dd}}80@0:8{CGRect={CGPoint=dd}{CGSize=dd}}16{CGRect={CGPoint=dd}{CGSize=dd}}48"
+ "{CGSize=\"width\"d\"height\"d}"
+ "\xb4"
+ "\xd1"
- "addContentViewController:withUserInteractionEnabled:forService:"
- "mainScreen"
- "resizeFrameForDisplay:"
- "\x94"
```
