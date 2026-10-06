## MessageUI

> `/System/Library/Frameworks/MessageUI.framework/MessageUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0xa21b` | `0xa0d6` | **`-0x145`** |
| `__TEXT.__gcc_except_tab` | `0x25090` | `0x25148` | **`+0xb8`** |
| `__AUTH.__objc_data` | `0x34e8` | `0x3588` | **`+0xa0`** |
| `__DATA_DIRTY.__objc_data` | `0xc30` | `0xb90` | **`-0xa0`** |
| `__TEXT.__text` | `0x14f1ac` | `0x14f114` | **`-0x98`** |
| `__TEXT.__eh_frame` | `0x664` | `0x5e8` | **`-0x7c`** |
| `__AUTH_CONST.__auth_got` | `0x1968` | `0x18f8` | **`-0x70`** |
| `__AUTH_CONST.__objc_const` | `0x1a730` | `0x1a778` | **`+0x48`** |
| `__DATA_CONST.__objc_selrefs` | `0xc1c8` | `0xc200` | **`+0x38`** |
| `__DATA_CONST.__const` | `0x4950` | `0x4978` | **`+0x28`** |
| `__AUTH_CONST.__cfstring` | `0x8e60` | `0x8e40` | **`-0x20`** |
| `__DATA.__bss` | `0x1d68` | `0x1d50` | **`-0x18`** |
| `__TEXT.__objc_methlist` | `0x129dc` | `0x129f4` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x1ed0` | `0x1ee0` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0xa598` | `0xa588` | **`-0x10`** |
| `__AUTH.__data` | `0x358` | `0x360` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x113c` | `0x1144` | **`+0x8`** |

### Same-size Content Changes

- `__TEXT.__oslogstring`

### Other Changes

```diff

-3893.100.7.0.0
+3895.100.17.2.1

-  Functions: 6859
-  Symbols:   11648
-  CStrings:  2063
+  Functions: 6860
+  Symbols:   11641
+  CStrings:  2048
Symbols:
+ -[MFComposeWebView _keyboardOnScreenStateDidChange:]
+ -[MFComposeWebView set_keyboardDidHideObserverToken:]
+ -[MFComposeWebView set_keyboardDidShowObserverToken:]
+ GCC_except_table223
+ GCC_except_table237
+ GCC_except_table259
+ GCC_except_table283
+ _EMIsCurrentUserManagedAppleAccountForShare
+ _OBJC_CLASS_$_TIPreferencesController
+ _OBJC_CLASS_$_UIKeyboardSceneDelegate
+ _OBJC_IVAR_$_MFComposeWebView.__keyboardDidHideObserverToken
+ _OBJC_IVAR_$_MFComposeWebView.__keyboardDidShowObserverToken
+ _OUTLINED_FUNCTION_10
+ _OUTLINED_FUNCTION_11
+ _OUTLINED_FUNCTION_9
+ ___40-[MFComposeWebView becomeFirstResponder]_block_invoke
+ ___block_descriptor_40_ea8_32w_e24_v16?0"NSNotification"8lw32l8
- -[MFComposeWebView _showWritingToolsAction]
- GCC_except_table249
- GCC_except_table253
- GCC_except_table265
- _EMIsManagedAppleAccount
- __MergedGlobals
- ___43-[MFComposeWebView _showWritingToolsAction]_block_invoke
- ___isPlatformVersionAtLeast
- __availability_version_check
- __initializeAvailabilityCheck
- _compatibilityInitializeAvailabilityCheck
- _dispatch_once_f
- _fclose
- _fopen
- _fread
- _fseek
- _ftell
- _initializeAvailabilityCheck
- _malloc
- _rewind
- _sscanf
- _swift_getEnumCaseMultiPayload
- _swift_storeEnumTagMultiPayload
- _swift_willThrowTypedImpl
CStrings:
+ "Share owner is MAA — skipping IDS check, adding all recipients as named participants"
- "%d.%d.%d"
- "/System/Library/CoreServices/SystemVersion.plist"
- "CFDataCreateWithBytesNoCopy"
- "CFDictionaryGetValue"
- "CFGetTypeID"
- "CFPropertyListCreateFromXMLData"
- "CFPropertyListCreateWithData"
- "CFRelease"
- "CFStringCreateWithCStringNoCopy"
- "CFStringGetCString"
- "CFStringGetTypeID"
- "Current user is MAA — skipping IDS check, adding all recipients as named participants"
- "ProductVersion"
- "Show Writing Tools"
- "kCFAllocatorNull"
- "r"
```
