## Contacts

> `/private/var/staged_system_apps/Contacts.app/Contacts`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xfd60` | `0x10368` | **`+0x608`** |
| `__TEXT.__objc_methname` | `0x5fb6` | `0x6149` | **`+0x193`** |
| `__TEXT.__objc_stubs` | `0x3f00` | `0x4020` | **`+0x120`** |
| `__TEXT.__objc_methtype` | `0x1ae8` | `0x1bd8` | **`+0xf0`** |
| `__DATA.__objc_const` | `0x2f50` | `0x3020` | **`+0xd0`** |
| `__TEXT.__objc_methlist` | `0x1e20` | `0x1ee8` | **`+0xc8`** |
| `__DATA.__objc_selrefs` | `0x1630` | `0x1698` | **`+0x68`** |
| `__DATA.__objc_data` | `0x7d0` | `0x820` | **`+0x50`** |
| `__TEXT.__auth_stubs` | `0x4d0` | `0x520` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x598` | `0x5e0` | **`+0x48`** |
| `__TEXT.__oslogstring` | `0x3c0` | `0x3ef` | **`+0x2f`** |
| `__TEXT.__cstring` | `0x530` | `0x559` | **`+0x29`** |
| `__TEXT.__objc_classname` | `0x486` | `0x4af` | **`+0x29`** |
| `__DATA_CONST.__auth_got` | `0x278` | `0x2a0` | **`+0x28`** |
| `__DATA_CONST.__const` | `0x458` | `0x478` | **`+0x20`** |
| `__DATA.__bss` | `0x78` | `0x88` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x238` | `0x240` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0xc8` | `0xd0` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0xb0` | `0xb8` | **`+0x8`** |
| `__TEXT.__const` | `0x40` | `0x48` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x170` | `0x174` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_protolist`

### Other Changes

```diff

-1463.200.51.0.0
+1463.200.82.0.0

-  Functions: 522
-  Symbols:   165
-  CStrings:  1165
+  Functions: 539
+  Symbols:   171
+  CStrings:  1188
Symbols:
+ _CGRectGetHeight
+ _CGRectGetMidX
+ _CGRectGetMinX
+ _CGRectGetMinY
+ _CGRectIsNull
+ _CGRectNull
CStrings:
+ "@\"UISplitViewController\""
+ "B32@0:8{CGSize=dd}16"
+ "CNContactsSplitViewControllerCoordinator"
+ "T@\"UISplitViewController\",W,N,V_splitViewController"
+ "alignmentRegionFrame"
+ "d48@0:8{UIEdgeInsets=dddd}16"
+ "initWithSplitViewController:"
+ "isPortrait:"
+ "midVerticalDivisionRegion:"
+ "os_log"
+ "preferredDisplayModeForExpandingToProposedDisplayMode:"
+ "q24@0:8q16"
+ "setSplitViewController:"
+ "setupProperties"
+ "shouldShowOneBesideSecondaryWithSize:"
+ "symmetricHorizontalSafeAreaInsetFromSafeAreaInsets:"
+ "updateSplitViewController"
+ "using coordinator for split view controller %p"
+ "verticalDivisionRegionForView:"
+ "viewIfLoaded"
+ "{CGRect={CGPoint=dd}{CGSize=dd}}16@0:8"
+ "{CGRect={CGPoint=dd}{CGSize=dd}}24@0:8@16"
+ "{CGRect={CGPoint=dd}{CGSize=dd}}48@0:8{CGRect={CGPoint=dd}{CGSize=dd}}16"
```
