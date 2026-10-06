## CallsDialer

> `/System/Library/PrivateFrameworks/CallsDialer.framework/CallsDialer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x43780` | `0x43b70` | **`+0x3f0`** |
| `__DATA_DIRTY.__data` | `0x368` | `0x5f0` | **`+0x288`** |
| `__AUTH.__data` | `0x280` | `0x110` | **`-0x170`** |
| `__DATA_DIRTY.__objc_data` | `0x8c8` | `0xa20` | **`+0x158`** |
| `__AUTH.__objc_data` | `0x548` | `0x440` | **`-0x108`** |
| `__DATA.__data` | `0xca0` | `0xb98` | **`-0x108`** |
| `__TEXT.__oslogstring` | `0x278e` | `0x286e` | **`+0xe0`** |
| `__AUTH_CONST.__objc_const` | `0x5d40` | `0x5e18` | **`+0xd8`** |
| `__DATA.__common` | `0x68` | `0x20` | **`-0x48`** |
| `__DATA_DIRTY.__common` | `0x10` | `0x58` | **`+0x48`** |
| `__TEXT.__objc_methlist` | `0x3f44` | `0x3f84` | **`+0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0x3440` | `0x3470` | **`+0x30`** |
| `__DATA_DIRTY.__bss` | `0x1a8` | `0x1c0` | **`+0x18`** |
| `__DATA.__bss` | `0xbe0` | `0xbd0` | **`-0x10`** |
| `__DATA_CONST.__got` | `0x720` | `0x730` | **`+0x10`** |
| `__TEXT.__const` | `0x1794` | `0x1784` | **`-0x10`** |
| `__TEXT.__swift5_reflstr` | `0x5c1` | `0x5ca` | **`+0x9`** |
| `__DATA_CONST.__objc_classlist` | `0x100` | `0x108` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1258` | `0x1260` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x2a8` | `0x2ac` | **`+0x4`** |

### Other Changes

```diff

-143.100.11.2.1
+145.100.7.2.1

-  Functions: 1654
-  Symbols:   2263
-  CStrings:  358
+  Functions: 1658
+  Symbols:   2273
+  CStrings:  365
Symbols:
+ +[PHLCDViewTextFieldFormatter formatText:inputIndex:previousSuggestion:networkCountryCode:homeCountryCode:]
+ -[PHBottomBarButton currentCallState]
+ -[PHBottomBarButton setCurrentCallState:]
+ -[PHHandsetDialerView _navigationChromeTopInset]
+ _OBJC_CLASS_$_PHLCDViewTextFieldFormatter
+ _OBJC_IVAR_$_PHBottomBarButton._currentCallState
+ _OBJC_METACLASS_$_PHLCDViewTextFieldFormatter
+ __OBJC_$_CLASS_METHODS_PHLCDViewTextFieldFormatter
+ __OBJC_CLASS_RO_$_PHLCDViewTextFieldFormatter
+ __OBJC_METACLASS_RO_$_PHLCDViewTextFieldFormatter
CStrings:
+ "%@ empty suggestion"
+ "%@ formatText: %@, inputIndex: %lu, previousSuggestion: %@, networkCountryCode %@, homeCountryCode %@"
+ "%@ formatted: %@"
+ "%@ new input index: %lu"
+ "%@ no change"
+ "%@ no suggestion"
+ "%@ suggestion: %@"
```
