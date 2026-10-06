## scrod

> `/System/Library/CoreServices/VoiceOverTouch.app/scrod`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xbd0c` | `0xbb48` | **`-0x1c4`** |
| `__TEXT.__objc_stubs` | `0x1aa0` | `0x1a00` | **`-0xa0`** |
| `__TEXT.__objc_methname` | `0x1c43` | `0x1bbb` | **`-0x88`** |
| `__TEXT.__oslogstring` | `0x1325` | `0x12f2` | **`-0x33`** |
| `__DATA.__objc_selrefs` | `0x8d8` | `0x8b0` | **`-0x28`** |
| `__DATA.__objc_const` | `0xac8` | `0xaa8` | **`-0x20`** |
| `__TEXT.__cstring` | `0x392` | `0x386` | **`-0xc`** |
| `__DATA_CONST.__got` | `0x318` | `0x310` | **`-0x8`** |
| `__DATA.__objc_ivar` | `0x7c` | `0x78` | **`-0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-329.0.0.0.0
+330.1.0.0.0

-  Symbols:   225
-  CStrings:  526
+  Symbols:   224
+  CStrings:  518
Symbols:
- _OBJC_CLASS_$_SCROBrailleHandler
Functions:
~ sub_100001a90 : 280 -> 244
~ sub_100001cb4 -> sub_100001c90 : 920 -> 636
~ sub_10000204c -> sub_100001f0c : 368 -> 284
~ sub_1000021bc -> sub_100002028 : 256 -> 208
CStrings:
+ "MSCRODMain using Swift BrailleServer"
- "Braille_XPC"
- "MSCRODMain using Mach transport"
- "MSCRODMain using XPC transport with Swift BrailleServer"
- "_usesXPCTransport"
- "detachNewThreadSelector:toTarget:withObject:"
- "initWithObjectsAndKeys:"
- "registerWithMach"
- "serverSource"
- "unregisterWithMach"
```
