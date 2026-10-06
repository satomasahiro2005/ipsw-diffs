## PasswordSettingsAppIntentsExtension

> `/System/Library/ExtensionKit/Extensions/PasswordSettingsAppIntentsExtension.appex/PasswordSettingsAppIntentsExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x7a5` | `0x2e1` | **`-0x4c4`** |
| `__DATA.__bss` | `0xc10` | `0x1020` | **`+0x410`** |
| `__TEXT.__const` | `0x778` | `0xaa8` | **`+0x330`** |
| `__TEXT.__text` | `0x4190` | `0x3ed4` | **`-0x2bc`** |
| `__TEXT.__eh_frame` | `0x68` | `0x238` | **`+0x1d0`** |
| `__DATA_CONST.__auth_ptr` | `0x3b8` | `0x4e0` | **`+0x128`** |
| `__TEXT.__unwind_info` | `0x1d8` | `0x268` | **`+0x90`** |
| `__TEXT.__swift5_typeref` | `0x30f` | `0x389` | **`+0x7a`** |
| `__TEXT.__swift5_assocty` | `0xa8` | `0x118` | **`+0x70`** |
| `__DATA_CONST.__const` | `0x251` | `0x2a0` | **`+0x4f`** |
| `__DATA.__data` | `0x178` | `0x1b8` | **`+0x40`** |
| `__TEXT.__constg_swiftt` | `0x7c` | `0xb4` | **`+0x38`** |
| `__TEXT.__auth_stubs` | `0x5d0` | `0x600` | **`+0x30`** |
| `__TEXT.__swift5_reflstr` | `0xe7` | `0x117` | **`+0x30`** |
| `__TEXT.__swift_as_entry` | `0x8` | `0x38` | **`+0x30`** |
| `__TEXT.__swift5_fieldmd` | `0x88` | `0xa8` | **`+0x20`** |
| `__TEXT.__swift5_proto` | `0x60` | `0x80` | **`+0x20`** |
| `__TEXT.__swift_as_ret` | `0x4` | `0x24` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0x2e8` | `0x300` | **`+0x18`** |
| `__TEXT.__swift_as_cont` | `—` | `0x14` | **`+0x14`** |
| `__DATA.__common` | `0x38` | `0x30` | **`-0x8`** |
| `__DATA_CONST.__got` | `0x70` | `0x78` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x10` | `0x18` | **`+0x8`** |

### Same-size Content Changes

- `__TEXT.__swift5_entry`

### Other Changes

```diff

-7625.1.18.10.4
+7625.1.20.10.3

-  Functions: 132
-  Symbols:   53
-  CStrings:  30
+  Functions: 171
+  Symbols:   57
+  CStrings:  21
Symbols:
+ _malloc_size
+ _swift_arrayInitWithCopy
+ _swift_cvw_assignWithCopy
+ _swift_cvw_assignWithTake
+ _swift_cvw_destroy
+ _swift_cvw_initWithCopy
+ _swift_cvw_initializeBufferWithCopyOfBuffer
+ _swift_errorRelease
+ _swift_release_x24
+ _swift_retain_x19
+ _swift_retain_x8
+ _swift_task_switch
- __swiftEmptyDictionarySingleton
- _bzero
- _swift_arrayDestroy
- _swift_arrayInitWithTakeBackToFront
- _swift_arrayInitWithTakeFrontToBack
- _swift_deallocClassInstance
- _swift_release_x25
- _swift_setDeallocating
CStrings:
+ "Clean up verification codes"
+ "Open Passwords Settings"
+ "Password AutoFill"
+ "Passwords Settings"
+ "Set up verification codes"
+ "clean up otp code"
+ "com.apple.Passwords-Settings.extension"
+ "com.apple.Preferences"
+ "otp code clean up"
+ "password manager"
+ "passwordAutofill"
+ "verification code clean up"
- "AutoFill Passwords and Passkeys"
- "AutoFill Passwords and Passkeys control under root pane of AutoFill & Passwords settings. This control determines if passwords, passkeys and verification codes are automatically suggested when signing into apps and websites."
- "AutoFill passwords"
- "Clean verification codes"
- "Delete After Use"
- "Delete After Use control under root pane of AutoFill & Passwords settings. This control determines if verification codes in Messages and Mail are deleted after being used."
- "General → AutoFill & Passwords"
- "Open Password Settings"
- "Password Settings"
- "Root pane of AutoFill & Passwords settings"
- "Set Up Codes In control under root pane of AutoFill & Passwords settings. This control determines if verification code setup links and QR codes are opened with the selected app."
- "Suggest Strong Passwords"
- "Suggest Strong Passwords control under root pane of AutoFill & Passwords settings. This control determines if unique, strong passwords are suggested when creating or changing account passwords in Safari and other apps."
- "autoFill"
- "com.apple.graphic-icon.autofill"
- "root"
- "settings-navigation://com.apple.Settings.General/AUTOFILL#autoFillProvidersSection"
- "settings-navigation://com.apple.Settings.General/AUTOFILL#otpAuthHandlersSection"
- "settings-navigation://com.apple.Settings.General/AUTOFILL#suggestStrongPasswordsToggle"
- "settings-navigation://com.apple.Settings.General/AUTOFILL#verificationCodesSection"
- "suggestStrongPasswords"
```
