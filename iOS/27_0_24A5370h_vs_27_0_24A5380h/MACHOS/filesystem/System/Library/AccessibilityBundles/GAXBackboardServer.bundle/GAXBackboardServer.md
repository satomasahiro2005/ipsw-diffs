## GAXBackboardServer

> `/System/Library/AccessibilityBundles/GAXBackboardServer.bundle/GAXBackboardServer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2ab74` | `0x2acbc` | **`+0x148`** |
| `__TEXT.__objc_methname` | `0x8bdc` | `0x8b77` | **`-0x65`** |
| `__TEXT.__cstring` | `0x4644` | `0x467a` | **`+0x36`** |
| `__TEXT.__oslogstring` | `0x3e13` | `0x3e49` | **`+0x36`** |
| `__DATA.__objc_const` | `0x2b10` | `0x2ae0` | **`-0x30`** |
| `__TEXT.__objc_stubs` | `0x6880` | `0x6860` | **`-0x20`** |
| `__TEXT.__objc_methlist` | `0x288c` | `0x2874` | **`-0x18`** |
| `__TEXT.__gcc_except_tab` | `0x7d4` | `0x7e8` | **`+0x14`** |
| `__DATA.__objc_selrefs` | `0x1ea8` | `0x1e98` | **`-0x10`** |
| `__TEXT.__auth_stubs` | `0xc30` | `0xc40` | **`+0x10`** |
| `__DATA.__bss` | `0xa0` | `0xa8` | **`+0x8`** |
| `__DATA_CONST.__auth_got` | `0x628` | `0x630` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x348` | `0x350` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0xa60` | `0xa68` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x1a8` | `0x1a4` | **`-0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`

### Other Changes

```diff

-1057.0.0.0.0
+1059.0.0.0.0

-  Functions: 959
-  Symbols:   583
-  CStrings:  2234
+  Functions: 958
+  Symbols:   584
+  CStrings:  2232
Symbols:
+ _notify_register_check
CStrings:
+ "Failed to initialize AAC restriction notification: %u"
+ "_reconcileDisableSystemGesturesAssertion"
+ "com.apple.accessibility.guidedaccess.restrictedForAAC"
- "T@\"NSArray\",&,N,V_ignoredTouchRegions"
- "_ignoredTouchRegions"
- "_updateDisablingSystemGesturesForMode:"
- "ignoredTouchRegions"
- "setIgnoredTouchRegions:"
```
