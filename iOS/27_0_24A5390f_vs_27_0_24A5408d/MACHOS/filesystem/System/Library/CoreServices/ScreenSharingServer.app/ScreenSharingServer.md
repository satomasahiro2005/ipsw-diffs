## ScreenSharingServer

> `/System/Library/CoreServices/ScreenSharingServer.app/ScreenSharingServer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3f8a8` | `0x40064` | **`+0x7bc`** |
| `__TEXT.__cstring` | `0xb69e` | `0xb87e` | **`+0x1e0`** |
| `__TEXT.__oslogstring` | `0x7539` | `0x760f` | **`+0xd6`** |
| `__DATA_CONST.__cfstring` | `0x1d60` | `0x1e20` | **`+0xc0`** |
| `__TEXT.__objc_methtype` | `0x322c` | `0x32b5` | **`+0x89`** |
| `__DATA_CONST.__const` | `0x610` | `0x590` | **`-0x80`** |
| `__TEXT.__objc_stubs` | `0x4760` | `0x46e0` | **`-0x80`** |
| `__TEXT.__auth_stubs` | `0xe40` | `0xe80` | **`+0x40`** |
| `__TEXT.__objc_methname` | `0x6160` | `0x6198` | **`+0x38`** |
| `__DATA.__objc_selrefs` | `0x1718` | `0x16f0` | **`-0x28`** |
| `__DATA_CONST.__auth_got` | `0x730` | `0x750` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x560` | `0x580` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x1d94` | `0x1d9c` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__gcc_except_tab`

### Other Changes

```diff

-166.11.0.0.0
+166.13.0.0.0

-  Functions: 619
-  Symbols:   369
-  CStrings:  3330
+  Functions: 624
+  Symbols:   373
+  CStrings:  3344
Symbols:
+ _CGPointZero
+ _CGRectFromString
+ _CGRectIsNull
+ _CGRectNull
+ _MGGetFloat32Answer
+ _NSStringFromClass
- _OBJC_CLASS_$_UIScreen
- _UIScreenModeDidChangeNotification
CStrings:
+ "%@/%@"
+ "%@[%lu]"
+ "-[SSAnnotationRenderer convertScaledCoordinates:]"
+ "MGGetSInt32Answer(kMGQMainScreenHeight) returned 0"
+ "MGGetSInt32Answer(kMGQMainScreenWidth) returned 0"
+ "StripNonSerializableValues"
+ "StripNonSerializableValues_block_invoke"
+ "T{CGRect={CGPoint=dd}{CGSize=dd}},N,V_currentDisplayBounds"
+ "[%s:%d] MGGetSInt32Answer(kMGQMainScreenHeight) returned 0"
+ "[%s:%d] MGGetSInt32Answer(kMGQMainScreenWidth) returned 0"
+ "[%s:%d] convertScaledCoordinates called before currentDisplayBounds was known"
+ "[%s:%d] sendServiceMessage dict: %s  destination %s  service %p"
+ "[%s:%d] stripping non-serializable value <%s> at %s"
+ "[%s:%d] stripping non-string key <%s> under %s"
+ "_currentDisplayBounds"
+ "_updateDisplayBoundsFromReply:"
+ "convertScaledCoordinates called before currentDisplayBounds was known"
+ "currentDisplayBounds"
+ "currentDisplayBounds updated: %s"
+ "displayBounds"
+ "enumerateKeysAndObjectsUsingBlock:"
+ "main screen point width: %f height: %f orientation %ld landscape: %d"
+ "main-screen-height"
+ "main-screen-scale"
+ "main-screen-width"
+ "sendServiceMessage dict: %s  destination %s  service %p"
+ "setCurrentDisplayBounds:"
+ "stripping non-serializable value <%s> at %s"
+ "stripping non-string key <%s> under %s"
+ "v32@?0@8@16^B24"
+ "v48@0:8{CGRect={CGPoint=dd}{CGSize=dd}}16"
+ "{CGRect=\"origin\"{CGPoint=\"x\"d\"y\"d}\"size\"{CGSize=\"width\"d\"height\"d}}"
+ "{CGRect={CGPoint=dd}{CGSize=dd}}16@0:8"
- "@\"UIScreen\""
- "T@\"UIScreen\",&,V_mainScreen"
- "[%s:%d] sendServiceMessage dict = %s  destination %s  sercice %p"
- "_mainScreen"
- "bounds"
- "currentMode"
- "main screen point width: %f height: %f  scaling: %f orientation %ld landscape: %d"
- "mainScreen"
- "mainScreen init"
- "mainScreen init main"
- "mainThread"
- "nativeBounds"
- "scale"
- "screenDidChange"
- "screenDidChange:"
- "screenRect: %s, scale: %f, modesize: (%f, %f)"
- "sendServiceMessage dict = %s  destination %s  sercice %p"
- "setMainScreen:"
- "size"
```
