## hangtracerd

> `/usr/libexec/hangtracerd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x35cf8` | `0x36f50` | **`+0x1258`** |
| `__DATA_CONST.__const` | `0x2108` | `0x2238` | **`+0x130`** |
| `__DATA.__objc_const` | `0x59f8` | `0x5af0` | **`+0xf8`** |
| `__TEXT.__objc_methname` | `0x9b7d` | `0x9c5b` | **`+0xde`** |
| `__TEXT.__oslogstring` | `0x66ea` | `0x6779` | **`+0x8f`** |
| `__TEXT.__objc_stubs` | `0x5c20` | `0x5ca0` | **`+0x80`** |
| `__TEXT.__objc_methlist` | `0x282c` | `0x289c` | **`+0x70`** |
| `__TEXT.__unwind_info` | `0xb78` | `0xbe0` | **`+0x68`** |
| `__TEXT.__gcc_except_tab` | `0x3d0` | `0x430` | **`+0x60`** |
| `__TEXT.__objc_methtype` | `0x130b` | `0x1355` | **`+0x4a`** |
| `__DATA.__objc_selrefs` | `0x1ed0` | `0x1ef8` | **`+0x28`** |
| `__DATA.__bss` | `0x560` | `0x548` | **`-0x18`** |
| `__TEXT.__const` | `0x3e8` | `0x400` | **`+0x18`** |
| `__TEXT.__cstring` | `0x4d89` | `0x4da0` | **`+0x17`** |
| `__DATA.__objc_ivar` | `0x518` | `0x52c` | **`+0x14`** |
| `__TEXT.__auth_stubs` | `0xf90` | `0xfa0` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x7d8` | `0x7e0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`

### Other Changes

```diff

-424.0.0.0.0
+426.0.0.0.0

-  Functions: 1363
-  Symbols:   401
-  CStrings:  3144
+  Functions: 1386
+  Symbols:   402
+  CStrings:  3160
Symbols:
+ _CFRunLoopRun
CStrings:
+ "@\"CADisplay\""
+ "@\"HUDAnimator\""
+ "@40@0:8@16@24d32"
+ "@48@0:8@16@24@32@40"
+ "@56@0:8@16@24d32@40@48"
+ "@64@0:8@16@24@32d40@48@56"
+ "@64@0:8@16@24@32d40d48@56"
+ "A"
+ "B40@0:8@16d24d32"
+ "Invalidating current HUD Context (displayId=%u). Debug description: %@"
+ "T@\"CADisplay\",&,N,V_display"
+ "T@\"CADisplay\",R,N,V_display"
+ "T@\"HUDAnimator\",W,N,V_animator"
+ "TextAnimation: updateAnimation returned NO — token stale, re-registering"
+ "[displayId=%u] A new HUD line is created for %@ with HANG start timestamp of %llu in mach absolute time. contentId:%@"
+ "[displayId=%u] Clearing %lu HUD lines @ %s"
+ "[displayId=%u] Passed 0 HUD content, removing the HUD from screen"
+ "[displayId=%u] Removed hudLines item %@"
+ "_animator"
+ "_display"
+ "animator"
+ "d16@?0@\"CADisplay\"8"
+ "display"
+ "displayLinkWithDisplay:target:selector:"
+ "initWithDisplay:"
+ "initWithDisplay:queue:"
+ "initWithLineState:theme:fontSize:animator:lineDelegate:"
+ "initWithNamespaceLayer:codeLayer:spacing:"
+ "initWithProcExitRecord:theme:display:lineDelegate:"
+ "initWithQueue:processName:theme:fontSize:animator:lineDelegate:"
+ "initWithRenderContext:display:queue:"
+ "initWithTitle:label:theme:fontSize:contentScale:display:"
+ "initWithValueText:unit:theme:display:"
+ "pointScale"
+ "setAnimator:"
+ "setDisplay:"
+ "topMargin for displayId=%u set to %f, displayScale=%f, orientation=%@"
- "@48@0:8@16@24d32@40"
- "@56@0:8@16@24@32d40@48"
- "@56@0:8@16@24@32d40d48"
- "A new HUD line is created for %@ with HANG start timestamp of %llu in mach absolute time. contentId:%@"
- "Clearing %lu HUD lines @ %s"
- "Invalidating current HUD Context. Debug description: %@"
- "Passed 0 HUD content, removing the HUD from screen"
- "Removed hudLines item %@"
- "_displayLinkInvalidated"
- "cachedTopMargin is set to %f where DisplayScale is %f. The orientation is %@"
- "displayLinkWithTarget:selector:"
- "initWithLineState:theme:fontSize:lineDelegate:"
- "initWithNamespaceLayer:codeLayer:"
- "initWithProcExitRecord:theme:lineDelegate:"
- "initWithQueue:processName:theme:fontSize:lineDelegate:"
- "initWithRenderContext:queue:"
- "initWithTitle:label:theme:fontSize:contentScale:"
- "initWithValueText:unit:theme:"
- "run"
- "sharedAnimator"
- "v40@0:8@16d24d32"
```
