## AutomaticAssessmentConfiguration

> `/System/Library/Frameworks/AutomaticAssessmentConfiguration.framework/AutomaticAssessmentConfiguration`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7ae8` | `0x8800` | **`+0xd18`** |
| `__AUTH_CONST.__objc_const` | `0x1040` | `0x13a0` | **`+0x360`** |
| `__TEXT.__objc_methlist` | `0x894` | `0xa7c` | **`+0x1e8`** |
| `__TEXT.__cstring` | `0x34f` | `0x438` | **`+0xe9`** |
| `__AUTH.__objc_data` | `0x190` | `0x230` | **`+0xa0`** |
| `__DATA_CONST.__objc_selrefs` | `0x6f0` | `0x788` | **`+0x98`** |
| `__TEXT.__unwind_info` | `0x210` | `0x260` | **`+0x50`** |
| `__AUTH_CONST.__cfstring` | `0x1e0` | `0x220` | **`+0x40`** |
| `__DATA.__objc_ivar` | `0x108` | `0x130` | **`+0x28`** |
| `__DATA_CONST.__const` | `0xa8` | `0xd0` | **`+0x28`** |
| `__DATA_CONST.__got` | `0x120` | `0x130` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x28` | `0x38` | **`+0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x20` | `0x30` | **`+0x10`** |

### Other Changes

```diff

-56.0.0.0.0
+56.0.3.0.0

-  Functions: 258
-  Symbols:   450
-  CStrings:  18
+  Functions: 301
+  Symbols:   521
+  CStrings:  21
Symbols:
+ +[AEAssessmentBinaryExecutable instanceFromApplicationDescriptor:]
+ +[AEAssessmentBinaryExecutableConfiguration instanceFromIndividualConfiguration:]
+ +[AEAssessmentBinaryExecutableConfiguration new]
+ -[AEAssessmentBinaryExecutable .cxx_destruct]
+ -[AEAssessmentBinaryExecutable applicationDescriptor]
+ -[AEAssessmentBinaryExecutable binaryExecutableURL]
+ -[AEAssessmentBinaryExecutable copyWithZone:]
+ -[AEAssessmentBinaryExecutable description]
+ -[AEAssessmentBinaryExecutable hash]
+ -[AEAssessmentBinaryExecutable initWithBinaryExecutableURL:]
+ -[AEAssessmentBinaryExecutable initWithBinaryExecutableURL:teamIdentifier:]
+ -[AEAssessmentBinaryExecutable initWithBinaryExecutableURL:teamIdentifier:requiresSignatureValidation:]
+ -[AEAssessmentBinaryExecutable isEqual:]
+ -[AEAssessmentBinaryExecutable isEqualToBinaryExecutable:]
+ -[AEAssessmentBinaryExecutable requiresSignatureValidation]
+ -[AEAssessmentBinaryExecutable setRequiresSignatureValidation:]
+ -[AEAssessmentBinaryExecutable teamIdentifier]
+ -[AEAssessmentBinaryExecutableConfiguration allowsNetworkAccess]
+ -[AEAssessmentBinaryExecutableConfiguration copyWithZone:]
+ -[AEAssessmentBinaryExecutableConfiguration description]
+ -[AEAssessmentBinaryExecutableConfiguration hash]
+ -[AEAssessmentBinaryExecutableConfiguration individualConfiguration]
+ -[AEAssessmentBinaryExecutableConfiguration init]
+ -[AEAssessmentBinaryExecutableConfiguration isEqual:]
+ -[AEAssessmentBinaryExecutableConfiguration isEqualToConfiguration:]
+ -[AEAssessmentBinaryExecutableConfiguration isRequired]
+ -[AEAssessmentBinaryExecutableConfiguration setAllowsNetworkAccess:]
+ -[AEAssessmentBinaryExecutableConfiguration setRequired:]
+ -[AEAssessmentConfiguration _allowsAccessibilityIntelligence]
+ -[AEAssessmentConfiguration _allowsVisualIntelligence]
+ -[AEAssessmentConfiguration _setAllowsAccessibilityIntelligence:]
+ -[AEAssessmentConfiguration _setAllowsVisualIntelligence:]
+ -[AEAssessmentConfiguration allowVirtualMachine]
+ -[AEAssessmentConfiguration allowsForceQuit]
+ -[AEAssessmentConfiguration configurationsByBinaryExecutable]
+ -[AEAssessmentConfiguration removeBinaryExecutable:]
+ -[AEAssessmentConfiguration setAllowVirtualMachine:]
+ -[AEAssessmentConfiguration setAllowsForceQuit:]
+ -[AEAssessmentConfiguration setBackingConfigurationsByBinaryExecutable:]
+ -[AEAssessmentConfiguration setConfiguration:forBinaryExecutable:]
+ _OBJC_CLASS_$_AEAssessmentBinaryExecutable
+ _OBJC_CLASS_$_AEAssessmentBinaryExecutableConfiguration
+ _OBJC_IVAR_$_AEAssessmentBinaryExecutable._binaryExecutableURL
+ _OBJC_IVAR_$_AEAssessmentBinaryExecutable._requiresSignatureValidation
+ _OBJC_IVAR_$_AEAssessmentBinaryExecutable._teamIdentifier
+ _OBJC_IVAR_$_AEAssessmentBinaryExecutableConfiguration._allowsNetworkAccess
+ _OBJC_IVAR_$_AEAssessmentBinaryExecutableConfiguration._required
+ _OBJC_IVAR_$_AEAssessmentConfiguration.__allowsAccessibilityIntelligence
+ _OBJC_IVAR_$_AEAssessmentConfiguration.__allowsVisualIntelligence
+ _OBJC_IVAR_$_AEAssessmentConfiguration._allowVirtualMachine
+ _OBJC_IVAR_$_AEAssessmentConfiguration._allowsForceQuit
+ _OBJC_IVAR_$_AEAssessmentConfiguration._backingConfigurationsByBinaryExecutable
+ _OBJC_METACLASS_$_AEAssessmentBinaryExecutable
+ _OBJC_METACLASS_$_AEAssessmentBinaryExecutableConfiguration
+ _OUTLINED_FUNCTION_1
+ __OBJC_$_CLASS_METHODS_AEAssessmentBinaryExecutable
+ __OBJC_$_CLASS_METHODS_AEAssessmentBinaryExecutableConfiguration
+ __OBJC_$_INSTANCE_METHODS_AEAssessmentBinaryExecutable
+ __OBJC_$_INSTANCE_METHODS_AEAssessmentBinaryExecutableConfiguration
+ __OBJC_$_INSTANCE_VARIABLES_AEAssessmentBinaryExecutable
+ __OBJC_$_INSTANCE_VARIABLES_AEAssessmentBinaryExecutableConfiguration
+ __OBJC_$_PROP_LIST_AEAssessmentBinaryExecutable
+ __OBJC_$_PROP_LIST_AEAssessmentBinaryExecutableConfiguration
+ __OBJC_CLASS_PROTOCOLS_$_AEAssessmentBinaryExecutable
+ __OBJC_CLASS_PROTOCOLS_$_AEAssessmentBinaryExecutableConfiguration
+ __OBJC_CLASS_RO_$_AEAssessmentBinaryExecutable
+ __OBJC_CLASS_RO_$_AEAssessmentBinaryExecutableConfiguration
+ __OBJC_METACLASS_RO_$_AEAssessmentBinaryExecutable
+ __OBJC_METACLASS_RO_$_AEAssessmentBinaryExecutableConfiguration
+ ___49-[AEAssessmentConfiguration configurationWrapper]_block_invoke_2
+ ___block_descriptor_40_e8_32s_e88_v32?0"AEAssessmentBinaryExecutable"8"AEAssessmentBinaryExecutableConfiguration"16^B24ls32l8
+ ___block_descriptor_48_e8_32s40s_e87_v32?0"AEAssessmentApplicationDescriptor"8"AEAssessmentIndividualConfiguration"16^B24ls32l8s40l8
- ___block_descriptor_40_e8_32s_e87_v32?0"AEAssessmentApplicationDescriptor"8"AEAssessmentIndividualConfiguration"16^B24ls32l8
CStrings:
+ "<%@: %p { allowsNetworkAccess = %@, required = %@ }>"
+ "<%@: %p { binaryExecutableURL = %@, teamIdentifier = %@, requiresSignatureChecks = %@ }>"
+ "v32@?0@\"AEAssessmentBinaryExecutable\"8@\"AEAssessmentBinaryExecutableConfiguration\"16^B24"
```
