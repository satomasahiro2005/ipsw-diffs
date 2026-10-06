## ControlCenterUIKit

> `/System/Library/PrivateFrameworks/ControlCenterUIKit.framework/ControlCenterUIKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x49e2c` | `0x4b6d0` | **`+0x18a4`** |
| `__TEXT.__oslogstring` | `0x6c3` | `0x983` | **`+0x2c0`** |
| `__TEXT.__cstring` | `0x16e1` | `0x1801` | **`+0x120`** |
| `__AUTH_CONST.__const` | `0x1728` | `0x17f0` | **`+0xc8`** |
| `__AUTH_CONST.__auth_got` | `0x9e8` | `0xa60` | **`+0x78`** |
| `__DATA_CONST.__objc_selrefs` | `0x2e70` | `0x2eb8` | **`+0x48`** |
| `__TEXT.__objc_methlist` | `0x57d8` | `0x5820` | **`+0x48`** |
| `__TEXT.__swift5_capture` | `0x3fc` | `0x43c` | **`+0x40`** |
| `__AUTH_CONST.__objc_const` | `0x93f0` | `0x9428` | **`+0x38`** |
| `__TEXT.__const` | `0x1e28` | `0x1df8` | **`-0x30`** |
| `__DATA_CONST.__got` | `0x6d0` | `0x6f8` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x1838` | `0x1860` | **`+0x28`** |
| `__DATA.__data` | `0x15a0` | `0x15c0` | **`+0x20`** |
| `__TEXT.__swift5_typeref` | `0x779` | `0x787` | **`+0xe`** |
| `__DATA.__objc_ivar` | `0x4ac` | `0x4b0` | **`+0x4`** |

### Other Changes

```diff

-704.0.2.0.0
+704.2.2.0.0

-  Functions: 2533
-  Symbols:   2974
-  CStrings:  227
+  Functions: 2558
+  Symbols:   2984
+  CStrings:  235
Symbols:
+ -[CCUIButtonModuleView _updateVisualStylingProviderIfNeeded]
+ -[CCUIRoundButton _accessibilityDelayBeforeUpdatingOnActivation]
+ -[CCUIRoundButton accessibilityDelayBeforeUpdatingOnActivation]
+ -[CCUIRoundButton setAccessibilityDelayBeforeUpdatingOnActivation:]
+ -[UIView(CCUIAdditions_Private) _controlCenterApplyPrimaryContentShadowWithOpacityScale:]
+ _OBJC_CLASS_$_UITouch
+ _OBJC_IVAR_$_CCUIRoundButton._accessibilityDelayBeforeUpdatingOnActivation
+ ___swift_closure_destructor.124Tm
+ ___swift_closure_destructor.181Tm
+ ___swift_closure_destructor.231Tm
+ __swiftImmortalRefCount
+ _memcpy
+ _symbolic _____y_____G s23_ContiguousArrayStorageC s5UInt8V
- ___swift_closure_destructor.115Tm
- ___swift_closure_destructor.172Tm
- ___swift_closure_destructor.222Tm
CStrings:
+ "[Control Template View] (%{public}s) Declining a context menu, the custom glyph view was hit"
+ "[Control Template View] (%{public}s) Declining a context menu, the delegate provided no menu"
+ "[Control Template View] (%{public}s) Declining a context menu, there is no context menu delegate"
+ "[Control Template View] (%{public}s) Presenting the context menu, UIControl's touch-down gesture did not recognize"
+ "[Control Template View] (%{public}s) Tap did not show a context menu, %{public}s [ showsMenuAsPrimaryAction: %{bool,public}d showsMenuAffordance: %{bool,public}d contextMenuInteractionEnabled: %{bool,public}d hasDelegate: %{bool,public}d gridSizeClass: %{public}ld ]"
+ "no delegate asked for the default action"
+ "showsMenuAsPrimaryAction is not set and there is no menu module delegate"
+ "the context menu interaction is not installed"
+ "the menu module delegate does not show its menu as the primary action"
+ "the menu would be anchored inside the custom glyph view"
- "Calistoga"
- "SwiftUI"
```
