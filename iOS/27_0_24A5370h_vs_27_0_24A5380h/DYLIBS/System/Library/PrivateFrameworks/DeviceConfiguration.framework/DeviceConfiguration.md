## DeviceConfiguration

> `/System/Library/PrivateFrameworks/DeviceConfiguration.framework/DeviceConfiguration`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xab2c8` | `0xb17b8` | **`+0x64f0`** |
| `__TEXT.__eh_frame` | `0x7c1c` | `0x8144` | **`+0x528`** |
| `__AUTH_CONST.__const` | `0x5868` | `0x5ae0` | **`+0x278`** |
| `__TEXT.__oslogstring` | `0x18cb` | `0x1aab` | **`+0x1e0`** |
| `__TEXT.__const` | `0xa8a0` | `0xaa08` | **`+0x168`** |
| `__TEXT.__unwind_info` | `0x2d48` | `0x2e98` | **`+0x150`** |
| `__DATA.__bss` | `0xca80` | `0xcb80` | **`+0x100`** |
| `__AUTH.__objc_data` | `0x880` | `0x948` | **`+0xc8`** |
| `__AUTH_CONST.__objc_const` | `0x2848` | `0x2900` | **`+0xb8`** |
| `__TEXT.__swift5_capture` | `0x9a0` | `0xa44` | **`+0xa4`** |
| `__AUTH_CONST.__cfstring` | `—` | `0xa0` | **`+0xa0`** |
| `__TEXT.__constg_swiftt` | `0x1da0` | `0x1e10` | **`+0x70`** |
| `__TEXT.__cstring` | `0x1588` | `0x15f8` | **`+0x70`** |
| `__TEXT.__swift5_typeref` | `0x253a` | `0x25a7` | **`+0x6d`** |
| `__TEXT.__objc_methlist` | `0x5fc` | `0x664` | **`+0x68`** |
| `__TEXT.__swift5_fieldmd` | `0x1b58` | `0x1bb4` | **`+0x5c`** |
| `__DATA.__data` | `0x1ba8` | `0x1be8` | **`+0x40`** |
| `__DATA_CONST.__const` | `0x130` | `0x168` | **`+0x38`** |
| `__AUTH.__data` | `0xe80` | `0xeb0` | **`+0x30`** |
| `__DATA_CONST.__objc_selrefs` | `0x320` | `0x340` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0x1088` | `0x10a8` | **`+0x20`** |
| `__TEXT.__swift_as_cont` | `0x558` | `0x578` | **`+0x20`** |
| `__TEXT.__swift_as_ret` | `0x2e0` | `0x300` | **`+0x20`** |
| `__TEXT.__swift_as_entry` | `0x2e0` | `0x2fc` | **`+0x1c`** |
| `__TEXT.__swift5_assocty` | `0x4d8` | `0x4f0` | **`+0x18`** |
| `__AUTH_CONST.__auth_got` | `0xef8` | `0xee8` | **`-0x10`** |
| `__DATA_DIRTY.__data` | `0xa00` | `0xa10` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0xe8` | `0xf0` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x6e0` | `0x6e8` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x230` | `0x238` | **`+0x8`** |

### Other Changes

```diff

-25.0.0.0.0
+26.0.0.0.0

-  Functions: 3415
-  Symbols:   1210
-  CStrings:  261
+  Functions: 3506
+  Symbols:   1230
+  CStrings:  270
Symbols:
+ _DCProviderClassEducation
+ _DCProviderClassEnterprise
+ _DCProviderClassFamilyControls
+ _DCProviderClassRegulatory
+ _DCProviderClassUnspecified
+ _OBJC_CLASS_$_DCClassifiedConfigurationItem
+ _OBJC_METACLASS_$_DCClassifiedConfigurationItem
+ __DATA_DCClassifiedConfigurationItem
+ __INSTANCE_METHODS_DCClassifiedConfigurationItem
+ __IVARS_DCClassifiedConfigurationItem
+ __METACLASS_DATA_DCClassifiedConfigurationItem
+ __PROPERTIES_DCClassifiedConfigurationItem
+ ___CFConstantStringClassReference
+ ___swift_closure_destructor.6Tm
+ ___swift_memcpy48_8
+ _associated conformance 19DeviceConfiguration13ProviderClassOSHAASQ
+ _get_enum_tag_for_layout_string s8Sendable_pSg
+ _symbolic SSSb__________y_____G______pIetMHgTyTgrzo_ 19DeviceConfiguration24AsyncConsumerServerActorC AA11XPCResponseO AA16SandboxExtensionC s5ErrorP
+ _symbolic SSSbx_____y_____G______p_____Rz_____RzlIetMHgTyTgrzo_ 19DeviceConfiguration11XPCResponseO AA16SandboxExtensionC s5ErrorP AA16AsyncConsumerXPCP 11Distributed01_J9ActorStubP
+ _symbolic SSSbx_____y_____G______p_____RzlIetWHgTyTgrzo_ 19DeviceConfiguration11XPCResponseO AA16SandboxExtensionC s5ErrorP AA16AsyncConsumerXPCP
+ _symbolic Shy_____G 19DeviceConfiguration13ProviderClassO
+ _symbolic _____ 19DeviceConfiguration010ClassifiedB4ItemV
+ _symbolic _____ 19DeviceConfiguration010ClassifiedB8ItemShimC
+ _symbolic _____ 19DeviceConfiguration13ProviderClassO
+ _symbolic _____ySS_____G s18_DictionaryStorageC 19DeviceConfiguration010ClassifiedD4ItemV
+ _symbolic _____ySS_____G s18_DictionaryStorageC 19DeviceConfiguration010ClassifiedD8ItemShimC
+ _symbolic _____ySS_____G s18_DictionaryStorageC 19DeviceConfiguration13ProviderClassO
+ _symbolic _____y_____G s11_SetStorageC 19DeviceConfiguration13ProviderClassO
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 19DeviceConfiguration13ProviderClassO
+ _type_layout_string 19DeviceConfiguration010ClassifiedB4ItemV
- ___swift_closure_destructor.4Tm
- ___swift_memcpy64_8
- _associated conformance 19DeviceConfiguration16ProviderCategoryOSHAASQ
- _get_enum_tag_for_layout_string 19DeviceConfiguration16ProviderCategoryO
- _swift_willThrowTypedImpl
- _symbolic SS__________y_____G______pIetMHgTgrzo_ 19DeviceConfiguration24AsyncConsumerServerActorC AA11XPCResponseO AA16SandboxExtensionC s5ErrorP
- _symbolic SSx_____y_____G______p_____Rz_____RzlIetMHgTgrzo_ 19DeviceConfiguration11XPCResponseO AA16SandboxExtensionC s5ErrorP AA16AsyncConsumerXPCP 11Distributed01_J9ActorStubP
- _symbolic SSx_____y_____G______p_____RzlIetWHgTgrzo_ 19DeviceConfiguration11XPCResponseO AA16SandboxExtensionC s5ErrorP AA16AsyncConsumerXPCP
- _symbolic _____ 19DeviceConfiguration16ProviderCategoryO
- _type_layout_string 19DeviceConfiguration16ProviderCategoryO
CStrings:
+ "DeviceConfiguration.ClassifiedConfigurationItemShim"
+ "Education"
+ "Enterprise"
+ "Failed to load provider registration for %{public}s, using unspecified instead. Error: %{public}@"
+ "FamilyControls"
+ "No cached provider class for %{public}s, using unspecified instead."
+ "Regulatory"
+ "Unspecified"
+ "getConfigurationSandboxExtension failed for '%{public}s' valuesOnly: '%{bool,public}d' Error: %{public}@"
+ "getConfigurationSandboxExtension returned nil sandboxExtension and nil error for '%{public}s' valuesOnly: '%{bool,public}d'"
+ "getConfigurationSandboxExtension succeeded for '%{public}s' valuesOnly: '%{bool,public}d'"
+ "getConfigurationSandboxExtension(configurationID:valuesOnly:)"
+ "getConfigurationWithProviderClasses(async) called for '%{public}s' isDaemon=%{bool,public}d"
+ "getConfigurationWithProviderClasses(sync) called for '%{public}s' isDaemon=%{bool,public}d"
- "ParentalControls"
- "getConfigurationSandboxExtension failed for '%{public}s': %{public}@"
- "getConfigurationSandboxExtension returned nil sandboxExtension and nil error for '%{public}s'"
- "getConfigurationSandboxExtension succeeded for '%{public}s'"
- "getConfigurationSandboxExtension(configurationID:)"
```
