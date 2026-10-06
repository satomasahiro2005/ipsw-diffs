## GAXBackboardServer

> `/System/Library/AccessibilityBundles/GAXBackboardServer.bundle/GAXBackboardServer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA.__objc_const` | `0x2ae0` | `0x29c0` | **`-0x120`** |
| `__TEXT.__oslogstring` | `0x3e49` | `0x3ef4` | **`+0xab`** |
| `__DATA.__objc_data` | `0x640` | `0x5a0` | **`-0xa0`** |
| `__TEXT.__cstring` | `0x467a` | `0x460b` | **`-0x6f`** |
| `__DATA_CONST.__cfstring` | `0x3660` | `0x3600` | **`-0x60`** |
| `__TEXT.__objc_classname` | `0x33f` | `0x2ed` | **`-0x52`** |
| `__TEXT.__objc_methlist` | `0x2874` | `0x2834` | **`-0x40`** |
| `__DATA_CONST.__const` | `0x1678` | `0x16a0` | **`+0x28`** |
| `__TEXT.__objc_stubs` | `0x6860` | `0x6880` | **`+0x20`** |
| `__TEXT.__text` | `0x2acbc` | `0x2acd8` | **`+0x1c`** |
| `__DATA_CONST.__objc_classlist` | `0xa0` | `0x90` | **`-0x10`** |
| `__TEXT.__objc_methtype` | `0x185a` | `0x1868` | **`+0xe`** |
| `__DATA_CONST.__objc_superrefs` | `0x70` | `0x68` | **`-0x8`** |
| `__TEXT.__const` | `0x178` | `0x180` | **`+0x8`** |
| `__TEXT.__objc_methname` | `0x8b77` | `0x8b7f` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0xa68` | `0xa60` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`

### Other Changes

```diff

-1059.0.0.0.0
+1061.0.0.0.0

-  Functions: 958
-  Symbols:   584
-  CStrings:  2232
+  Functions: 955
+  Symbols:   580
+  CStrings:  2231
Symbols:
- _OBJC_CLASS_$_GAXBKOrientationManagerAccessibility
- _OBJC_CLASS_$___GAXBKOrientationManagerAccessibility_super
- _OBJC_METACLASS_$_GAXBKOrientationManagerAccessibility
- _OBJC_METACLASS_$___GAXBKOrientationManagerAccessibility_super
CStrings:
+ "Still waiting for GAX SpringBoard Server to load. Will try again in %{public}.2f"
+ "Still waiting to connect to SB. Will try again in %{public}.2f"
+ "Verifier reported a nil session app while still initializing after reboot. Preserving persisted activeAppID (%{public}@) so boot restore can relaunch."
+ "_prepareGuidedAccessAfterConnectingToSpringboard:retryDelay:"
+ "v28@0:8B16d20"
- "BKOrientationManager"
- "GAXBKOrientationManagerAccessibility"
- "Still waiting for GAX SpringBoard Server to load. Will try again in .1"
- "Still waiting to connect to SB. Will try again in .5"
- "__GAXBKOrientationManagerAccessibility_super"
- "_queue_postUpdatedRawAccelerometerDeviceOrientation:"
```
