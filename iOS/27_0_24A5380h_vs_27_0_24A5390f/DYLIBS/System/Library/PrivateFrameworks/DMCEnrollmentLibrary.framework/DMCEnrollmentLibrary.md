## DMCEnrollmentLibrary

> `/System/Library/PrivateFrameworks/DMCEnrollmentLibrary.framework/DMCEnrollmentLibrary`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2bb98` | `0x2beb0` | **`+0x318`** |
| `__TEXT.__oslogstring` | `0x46f3` | `0x46a2` | **`-0x51`** |
| `__DATA_CONST.__const` | `0x1358` | `0x13a8` | **`+0x50`** |
| `__TEXT.__cstring` | `0x2753` | `0x278f` | **`+0x3c`** |
| `__AUTH_CONST.__cfstring` | `0x1960` | `0x1980` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x978` | `0x998` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0x86c` | `0x880` | **`+0x14`** |
| `__TEXT.__const` | `0xf8` | `0x100` | **`+0x8`** |

### Other Changes

```diff

-111.0.0.0.0
+113.0.2.0.0

-  Functions: 851
-  Symbols:   1488
-  CStrings:  616
+  Functions: 854
+  Symbols:   1491
+  CStrings:  617
Symbols:
+ -[DMCEnrollmentFlowController _extensionIDsFromDeclarationProfiles:]
+ -[DMCEnrollmentFlowController _waitForESSODeclarations:]
+ GCC_except_table165
+ GCC_except_table198
+ GCC_except_table202
+ GCC_except_table212
+ GCC_except_table219
+ GCC_except_table251
+ ___56-[DMCEnrollmentFlowController _waitForESSODeclarations:]_block_invoke
+ ___56-[DMCEnrollmentFlowController _waitForESSODeclarations:]_block_invoke_2
+ ___68-[DMCEnrollmentFlowController _extensionIDsFromDeclarationProfiles:]_block_invoke
+ ___68-[DMCEnrollmentFlowController _extensionIDsFromDeclarationProfiles:]_block_invoke_2
+ ___block_descriptor_48_e8_32s40bs_e29_v24?0"NSArray"8"NSError"16ls32l8s40l8
+ ___block_descriptor_56_e8_32s40s48r_e17_v16?0"NSError"8ls32l8r48l8s40l8
+ ___block_descriptor_64_e8_32s40s48s56bs_e5_v8?0ls32l8s56l8s40l8s48l8
- -[DMCEnrollmentFlowController _extensionIDsFromDeclarationProfiles]
- -[DMCEnrollmentFlowController _waitForESSODeclarations]
- GCC_except_table189
- GCC_except_table199
- GCC_except_table206
- GCC_except_table213
- GCC_except_table248
- ___55-[DMCEnrollmentFlowController _waitForESSODeclarations]_block_invoke
- ___55-[DMCEnrollmentFlowController _waitForESSODeclarations]_block_invoke_2
- ___67-[DMCEnrollmentFlowController _extensionIDsFromDeclarationProfiles]_block_invoke
- ___67-[DMCEnrollmentFlowController _extensionIDsFromDeclarationProfiles]_block_invoke_2
- ___block_descriptor_40_e8_32s_e29_v24?0"NSArray"8"NSError"16ls32l8
CStrings:
+ "wait_for_esso_declarations"
+ "wait_for_esso_declarations_queue"
- "Pending cloud config does not require await configuration. Do not preserve apps."
```
