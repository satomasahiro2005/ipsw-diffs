## DMCEnrollmentLibrary

> `/System/Library/PrivateFrameworks/DMCEnrollmentLibrary.framework/DMCEnrollmentLibrary`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2beb0` | `0x2cd74` | **`+0xec4`** |
| `__TEXT.__oslogstring` | `0x46a2` | `0x47ab` | **`+0x109`** |
| `__DATA_CONST.__const` | `0x13a8` | `0x1498` | **`+0xf0`** |
| `__TEXT.__gcc_except_tab` | `0x880` | `0x8e4` | **`+0x64`** |
| `__AUTH_CONST.__cfstring` | `0x1980` | `0x19e0` | **`+0x60`** |
| `__TEXT.__cstring` | `0x278f` | `0x27e8` | **`+0x59`** |
| `__TEXT.__objc_methlist` | `0x1d1c` | `0x1d74` | **`+0x58`** |
| `__TEXT.__unwind_info` | `0x998` | `0x9f0` | **`+0x58`** |
| `__TEXT.__dlopen_cstrs` | `0xae` | `0x104` | **`+0x56`** |
| `__AUTH_CONST.__objc_intobj` | `0xb28` | `0xb70` | **`+0x48`** |
| `__DATA_CONST.__objc_selrefs` | `0x1d38` | `0x1d80` | **`+0x48`** |
| `__AUTH_CONST.__objc_const` | `0x2030` | `0x2060` | **`+0x30`** |
| `__DATA_CONST.__objc_arraydata` | `0x558` | `0x578` | **`+0x20`** |
| `__AUTH_CONST.__objc_arrayobj` | `0x4e0` | `0x4f8` | **`+0x18`** |
| `__DATA.__bss` | `0x218` | `0x220` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x1a4` | `0x1a8` | **`+0x4`** |

### Other Changes

```diff

-113.2.5.0.0
+113.40.17.0.0

-  Functions: 854
-  Symbols:   1491
-  CStrings:  617
+  Functions: 870
+  Symbols:   1519
+  CStrings:  624
Symbols:
+ +[DMCEnrollmentFlowController(Utilities) _createSignInErrorFromError:]
+ -[DMCEnrollmentFlowController _checkExistingESSOApplicationWithITunesStoreID:debuggingAppIDs:]
+ -[DMCEnrollmentFlowController _checkExistingRequiredApplicationWithITunesStoreID:essoITunesStoreID:]
+ -[DMCEnrollmentFlowController _presentAndHandleRemovalForITunesStoreID:installedBundleID:reason:allowSkip:]
+ -[DMCEnrollmentFlowController requiredAppID]
+ -[DMCEnrollmentFlowController setRequiredAppID:]
+ -[DMCEnrollmentFlowController(Sequence) _ADxE_ESSO_displayManagementDetailsSteps]
+ GCC_except_table150
+ GCC_except_table153
+ GCC_except_table154
+ GCC_except_table155
+ GCC_except_table158
+ GCC_except_table160
+ GCC_except_table162
+ GCC_except_table176
+ GCC_except_table203
+ GCC_except_table206
+ GCC_except_table213
+ GCC_except_table220
+ GCC_except_table223
+ GCC_except_table227
+ GCC_except_table230
+ GCC_except_table262
+ _AppleAccountLibraryCore.frameworkLibrary
+ _OBJC_IVAR_$_DMCEnrollmentFlowController._requiredAppID
+ ___100-[DMCEnrollmentFlowController _checkExistingRequiredApplicationWithITunesStoreID:essoITunesStoreID:]_block_invoke
+ ___100-[DMCEnrollmentFlowController _checkExistingRequiredApplicationWithITunesStoreID:essoITunesStoreID:]_block_invoke_2
+ ___107-[DMCEnrollmentFlowController _presentAndHandleRemovalForITunesStoreID:installedBundleID:reason:allowSkip:]_block_invoke
+ ___107-[DMCEnrollmentFlowController _presentAndHandleRemovalForITunesStoreID:installedBundleID:reason:allowSkip:]_block_invoke_2
+ ___107-[DMCEnrollmentFlowController _presentAndHandleRemovalForITunesStoreID:installedBundleID:reason:allowSkip:]_block_invoke_3
+ ___107-[DMCEnrollmentFlowController _presentAndHandleRemovalForITunesStoreID:installedBundleID:reason:allowSkip:]_block_invoke_4
+ ___94-[DMCEnrollmentFlowController _checkExistingESSOApplicationWithITunesStoreID:debuggingAppIDs:]_block_invoke
+ ___94-[DMCEnrollmentFlowController _checkExistingESSOApplicationWithITunesStoreID:debuggingAppIDs:]_block_invoke_2
+ ___AppleAccountLibraryCore_block_invoke
+ ___block_descriptor_48_e8_32s40w_e29_v24?0"NSArray"8"NSError"16lw40l8s32l8
+ ___block_descriptor_48_e8_32w_e17_v16?0"NSError"8lw32l8
+ ___block_descriptor_56_e8_32s40s_e5_v8?0ls32l8s40l8
+ ___block_descriptor_56_e8_32s40w_e23_v24?0B8B12"NSError"16lw40l8s32l8
+ ___block_descriptor_74_e8_32s40s48s56w_e5_v8?0ls32l8s40l8s48l8w56l8
+ _audit_stringAppleAccount
- GCC_except_table149
- GCC_except_table151
- GCC_except_table165
- GCC_except_table192
- GCC_except_table195
- GCC_except_table198
- GCC_except_table202
- GCC_except_table212
- GCC_except_table216
- GCC_except_table219
- GCC_except_table251
- GCC_except_table47
CStrings:
+ "CheckExistingESSOApplication"
+ "CheckExistingRequiredApplication"
+ "DMC_MAA_TERMS_NOT_ACCEPTED"
+ "Failed to fetch bundle IDs while checking for an existing Enrollment SSO app: %{public}@"
+ "Failed to fetch bundle IDs while checking for an existing required app, skipping removal prompt: %{public}@"
+ "Required app matches ESSO app, skipping required-app removal prompt"
+ "softlink:r:path:/System/Library/PrivateFrameworks/AppleAccount.framework/AppleAccount"
```
