## GAXBackboardServer

> `/System/Library/AccessibilityBundles/GAXBackboardServer.bundle/GAXBackboardServer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2a0c8` | `0x2ab74` | **`+0xaac`** |
| `__TEXT.__objc_methname` | `0x8a42` | `0x8bdc` | **`+0x19a`** |
| `__TEXT.__objc_stubs` | `0x67a0` | `0x6880` | **`+0xe0`** |
| `__DATA.__objc_const` | `0x2ab0` | `0x2b10` | **`+0x60`** |
| `__DATA_CONST.__const` | `0x1620` | `0x1678` | **`+0x58`** |
| `__TEXT.__oslogstring` | `0x3dbe` | `0x3e13` | **`+0x55`** |
| `__DATA.__objc_selrefs` | `0x1e68` | `0x1ea8` | **`+0x40`** |
| `__DATA_CONST.__cfstring` | `0x3620` | `0x3660` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0x284c` | `0x288c` | **`+0x40`** |
| `__TEXT.__objc_methtype` | `0x1839` | `0x185a` | **`+0x21`** |
| `__TEXT.__unwind_info` | `0xa48` | `0xa60` | **`+0x18`** |
| `__TEXT.__cstring` | `0x462e` | `0x4644` | **`+0x16`** |
| `__TEXT.__gcc_except_tab` | `0x7c0` | `0x7d4` | **`+0x14`** |
| `__DATA.__objc_ivar` | `0x1a0` | `0x1a8` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x340` | `0x348` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`

### Other Changes

```diff

-1054.0.0.0.0
+1057.0.0.0.0

-  Functions: 950
-  Symbols:   581
-  CStrings:  2218
+  Functions: 959
+  Symbols:   583
+  CStrings:  2234
Symbols:
+ _BKSHIDServicesCancelTouchesOnAllDisplays
+ _GAXUIMessageKeyDisplayIdentifier
+ ___NSArray0__struct
- _BKSHIDServicesCancelTouchesOnMainDisplay
CStrings:
+ "%u"
+ "@\"NSArray\"32@0:8@\"GAXEventProcessor\"16@\"NSString\"24"
+ "@28@0:8i16@20"
+ "No CADisplay found for hardware identifier: %{public}@, falling back to main display"
+ "T@\"NSDictionary\",&,N,V_ignoredTouchRegionsByDisplay"
+ "T@\"NSString\",C,N,V_activeDisplayIdentifier"
+ "_activeDisplayIdentifier"
+ "_ignoredTouchRegionsByDisplay"
+ "_stableDisplayIdentifierForHardwareIdentifier:"
+ "activeDisplayIdentifier"
+ "display identifier"
+ "displayHardwareIdentifier"
+ "displayId"
+ "ignoredTouchRegionsByDisplay"
+ "ignoredTouchRegionsForEventProcessor:displayIdentifier:"
+ "ignoredTouchRegionsForOrientation:displayIdentifier:"
+ "setActiveDisplayIdentifier:"
+ "setIgnoredTouchRegions:forOrientation:displayIdentifier:"
+ "setIgnoredTouchRegionsByDisplay:"
+ "uniqueId"
+ "v36@0:8@16i24@28"
- "@\"NSArray\"24@0:8@\"GAXEventProcessor\"16"
- "@20@0:8i16"
- "ignoredTouchRegionsForEventProcessor:"
- "ignoredTouchRegionsForOrientation:"
- "setIgnoredTouchRegions:forOrientation:"
```
