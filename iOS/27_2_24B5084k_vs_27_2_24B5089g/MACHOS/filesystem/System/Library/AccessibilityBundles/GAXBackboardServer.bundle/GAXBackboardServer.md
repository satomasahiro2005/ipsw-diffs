## GAXBackboardServer

> `/System/Library/AccessibilityBundles/GAXBackboardServer.bundle/GAXBackboardServer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2b9dc` | `0x2bbe8` | **`+0x20c`** |
| `__TEXT.__objc_methname` | `0x8df7` | `0x8e80` | **`+0x89`** |
| `__TEXT.__objc_stubs` | `0x69c0` | `0x6a20` | **`+0x60`** |
| `__DATA.__objc_const` | `0x2a38` | `0x2a68` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x28cc` | `0x28ec` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0x1ee8` | `0x1f00` | **`+0x18`** |
| `__DATA_CONST.__const` | `0x16c8` | `0x16b0` | **`-0x18`** |
| `__TEXT.__oslogstring` | `0x42ca` | `0x42db` | **`+0x11`** |
| `__TEXT.__unwind_info` | `0xaa0` | `0xaa8` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x1a8` | `0x1ac` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`

### Other Changes

```diff

-1067.3.0.0.0
+1067.3.1.0.0

-  Functions: 970
+  Functions: 974

-  CStrings:  2268
+  CStrings:  2273
CStrings:
+ "App layout has %d app elements of %d total, from same app %i: %{public}@"
+ "TB,N,V_cachedIsLostModeActive"
+ "TB,N,V_didReadLostModeState"
+ "_cachedIsLostModeActive"
+ "_didReadLostModeState"
+ "cachedIsLostModeActive"
+ "didReadLostModeState"
+ "setCachedIsLostModeActive:"
+ "setDidReadLostModeState:"
- "App layout has %d elements from same app %i: %{public}@"
- "TB,N,V_isLostModeActive"
- "_isLostModeActive"
- "setIsLostModeActive:"
```
