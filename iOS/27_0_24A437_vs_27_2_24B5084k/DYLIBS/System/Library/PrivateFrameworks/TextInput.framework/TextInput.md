## TextInput

> `/System/Library/PrivateFrameworks/TextInput.framework/TextInput`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x80964` | `0x80bf0` | **`+0x28c`** |
| `__TEXT.__oslogstring` | `0x974` | `0xb19` | **`+0x1a5`** |
| `__DATA_CONST.__objc_arraydata` | `0x101948` | `0x101a18` | **`+0xd0`** |
| `__TEXT.__cstring` | `0x49636` | `0x4959c` | **`-0x9a`** |
| `__AUTH_CONST.__objc_const` | `0x11bd0` | `0x11c60` | **`+0x90`** |
| `__AUTH.__objc_data` | `0x2620` | `0x2670` | **`+0x50`** |
| `__AUTH_CONST.__objc_dictobj` | `0xf190` | `0xf1b8` | **`+0x28`** |
| `__AUTH_CONST.__cfstring` | `0x255d20` | `0x255d40` | **`+0x20`** |
| `__AUTH_CONST.__const` | `0xd60` | `0xd80` | **`+0x20`** |
| `__TEXT.__const` | `0x4b0` | `0x4d0` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0xb660` | `0xb680` | **`+0x20`** |
| `__AUTH_CONST.__objc_arrayobj` | `0x5058` | `0x5070` | **`+0x18`** |
| `__AUTH_CONST.__objc_intobj` | `0xd38` | `0xd50` | **`+0x18`** |
| `__DATA.__bss` | `0x788` | `0x798` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x20b0` | `0x20c0` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x5b8` | `0x5c0` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x56c0` | `0x56c8` | **`+0x8`** |

### Other Changes

```diff

-3567.0.0.0.0
+3568.1.4.0.0

-  Functions: 4011
-  Symbols:   7655
-  CStrings:  76804
+  Functions: 4015
+  Symbols:   7666
+  CStrings:  76808
Symbols:
+ +[TIMecabraComposedCharacterCandidate supportsSecureCoding]
+ +[TIMecabraComposedCharacterCandidate type]
+ _OBJC_CLASS_$_TIMecabraComposedCharacterCandidate
+ _OBJC_METACLASS_$_TIMecabraComposedCharacterCandidate
+ _TIInputManagerClientOSLogFacility
+ _TIInputManagerClientOSLogFacility.logFacility
+ _TIInputManagerClientOSLogFacility.onceToken
+ __OBJC_$_CLASS_METHODS_TIMecabraComposedCharacterCandidate
+ __OBJC_CLASS_RO_$_TIMecabraComposedCharacterCandidate
+ __OBJC_METACLASS_RO_$_TIMecabraComposedCharacterCandidate
+ ___TIInputManagerClientOSLogFacility_block_invoke
CStrings:
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/usr/include/c++/v1/__vector/vector.h:1161: libc++ Hardening assertion __position != end() failed: vector::erase(iterator) called with a non-dereferenceable iterator\n"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/usr/include/c++/v1/__vector/vector.h:414: libc++ Hardening assertion __n < size() failed: vector[] index out of bounds\n"
+ "IM Client closed connection to kbd (Please check for kbd crash logs.) after failures sending %{public}@. Last error domain=%{public}@ code=%{public}ld: %{public}@"
+ "IM Client falling back to stub input manager to handle request: %{public}@"
+ "IM Client intentionally invalidating connection to kbd"
+ "IM Client will retry (attempt %{public}ld) sending %{public}@ to kbd after error domain=%{public}@ code=%{public}ld: %{public}@"
+ "KBDInputManagerClient"
+ "Kurdish-Sorani-QWERTY"
+ "TIMecabraComposedCharacterCandidate"
- "%s will retry sending %@ to keyboard daemon after receiving %@"
- "-[TIKeyboardInputManagerClient handleError:forRequest:]"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:1161: libc++ Hardening assertion __position != end() failed: vector::erase(iterator) called with a non-dereferenceable iterator\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:414: libc++ Hardening assertion __n < size() failed: vector[] index out of bounds\n"
- "Please check for kbd crash logs. %s closed connection to keyboard daemon after two consecutive failures sending %@"
```
