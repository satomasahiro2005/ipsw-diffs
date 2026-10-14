## DeviceConfiguration

> `/System/Library/PrivateFrameworks/DeviceConfiguration.framework/DeviceConfiguration`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xe2004` | `0xe4f24` | **`+0x2f20`** |
| `__DATA.__bss` | `0xa080` | `0xa800` | **`+0x780`** |
| `__TEXT.__cstring` | `0x1a78` | `0x20e7` | **`+0x66f`** |
| `__TEXT.__const` | `0xc830` | `0xcd00` | **`+0x4d0`** |
| `__TEXT.__eh_frame` | `0x92e8` | `0x95b0` | **`+0x2c8`** |
| `__TEXT.__oslogstring` | `0x41c4` | `0x4304` | **`+0x140`** |
| `__TEXT.__unwind_info` | `0x35c8` | `0x36b0` | **`+0xe8`** |
| `__TEXT.__swift5_typeref` | `0x2b82` | `0x2c5a` | **`+0xd8`** |
| `__AUTH_CONST.__auth_got` | `0xff8` | `0x1050` | **`+0x58`** |
| `__DATA.__data` | `0x10d0` | `0x1128` | **`+0x58`** |
| `__DATA_DIRTY.__data` | `0x2938` | `0x28e8` | **`-0x50`** |
| `__TEXT.__swift5_proto` | `0x7c8` | `0x804` | **`+0x3c`** |
| `__TEXT.__swift5_assocty` | `0x538` | `0x568` | **`+0x30`** |
| `__AUTH_CONST.__const` | `0x66f8` | `0x6720` | **`+0x28`** |
| `__TEXT.__swift5_fieldmd` | `0x1e3c` | `0x1e64` | **`+0x28`** |
| `__TEXT.__constg_swiftt` | `0x20b8` | `0x20d8` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0x12c8` | `0x12e1` | **`+0x19`** |
| `__DATA_DIRTY.__common` | `0x1f9` | `0x1e1` | **`-0x18`** |
| `__TEXT.__swift5_builtin` | `0xdc` | `0xf0` | **`+0x14`** |
| `__DATA_CONST.__objc_selrefs` | `0x3b8` | `0x3c8` | **`+0x10`** |
| `__TEXT.__swift_as_cont` | `0x5e8` | `0x5f4` | **`+0xc`** |
| `__TEXT.__swift5_types` | `0x26c` | `0x270` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0x330` | `0x334` | **`+0x4`** |

### Other Changes

```diff

-39.40.3.0.0
+39.42.1.0.0

-  Functions: 4046
-  Symbols:   1353
-  CStrings:  440
+  Functions: 4091
+  Symbols:   1372
+  CStrings:  488
Symbols:
+ _NSURLIsDirectoryKey
+ _OBJC_CLASS_$_NSLock
+ _associated conformance 19DeviceConfiguration0B5ErrorO10Foundation09LocalizedC0AAs0C0
+ _associated conformance 19DeviceConfiguration10StoreErrorO10Foundation09LocalizedD0AAs0D0
+ _associated conformance 19DeviceConfiguration12SandboxErrorO10Foundation09LocalizedD0AAs0D0
+ _associated conformance 19DeviceConfiguration13InternalErrorO10Foundation09LocalizedD0AAs0D0
+ _associated conformance 19DeviceConfiguration13ProviderErrorO10Foundation09LocalizedD0AAs0D0
+ _associated conformance 19DeviceConfiguration15SubscriberErrorO10Foundation09LocalizedD0AAs0D0
+ _associated conformance 19DeviceConfiguration15ValidationErrorO10Foundation09LocalizedD0AAs0D0
+ _associated conformance 19DeviceConfiguration8XPCErrorO10Foundation14LocalizedErrorAAs0F0
+ _associated conformance 19DeviceConfiguration9SpecErrorO10Foundation09LocalizedD0AAs0D0
+ _associated conformance So16NSURLResourceKeyaSHSCSQ
+ _associated conformance So16NSURLResourceKeyas20_SwiftNewtypeWrapperSCSY
+ _associated conformance So16NSURLResourceKeyas20_SwiftNewtypeWrapperSCs35_HasCustomAnyHashableRepresentation
+ _swift_willThrowTypedImpl
+ _symbolic _____ So16NSURLResourceKeya
+ _symbolic _____ySS______t______pG s6ResultOsRi_zRi0_zrlE 19DeviceConfiguration09EffectiveC0V s5ErrorP
+ _symbolic _____y_____G s11_SetStorageC So16NSURLResourceKeya
+ _symbolic _____y_____G s23_ContiguousArrayStorageC So16NSURLResourceKeya
+ _symbolic _____y______SDySSypGt______pG s6ResultOsRi_zRi0_zrlE 19DeviceConfiguration15StoreIdentifierC s5ErrorP
+ _symbolic _____y___________pG s6ResultOsRi_zRi0_zrlE 19DeviceConfiguration0C4DataV s5ErrorP
+ _symbolic _____y_____ySS______t______pGG s23_ContiguousArrayStorageC s6ResultOsRi_zRi0_zrlE 19DeviceConfiguration09EffectiveF0V s5ErrorP
+ _symbolic _____y_____y______SDySSypGt______pGG s23_ContiguousArrayStorageC s6ResultOsRi_zRi0_zrlE 19DeviceConfiguration15StoreIdentifierC s5ErrorP
+ _symbolic _____y_____y___________pGG s23_ContiguousArrayStorageC s6ResultOsRi_zRi0_zrlE 19DeviceConfiguration0F4DataV s5ErrorP
- _symbolic SS______t 19DeviceConfiguration09EffectiveB0V
- _symbolic ______SDySSypGt 19DeviceConfiguration15StoreIdentifierC
- _symbolic _____ySS______tG s23_ContiguousArrayStorageC 19DeviceConfiguration09EffectiveE0V
- _symbolic _____y_____G s23_ContiguousArrayStorageC 19DeviceConfiguration0E4DataV
- _symbolic _____y______SDySSypGtG s23_ContiguousArrayStorageC 19DeviceConfiguration15StoreIdentifierC
CStrings:
+ "' cannot be used with setting '"
+ "' defined for setting '"
+ "' defines no permitted values."
+ "' for provider '"
+ "' in configuration '"
+ "' is defined more than once."
+ "' is not a valid configuration ID."
+ "' is not a valid setting in configuration '"
+ "' is not authorized to write configuration(s): "
+ "' is not one of the permitted values."
+ "' is not permitted."
+ "' was found for provider '"
+ ", but received a value of type "
+ "Combine operator '"
+ "Duplicate stores were submitted: "
+ "Expected a value of type "
+ "Failed to collect diagnostics"
+ "Failed to collect provider effective data with configurationID %{public}s. Error: %{public}@"
+ "Failed to collect store data with configurationID %{public}s. Error: %{public}@"
+ "Failed to commit stores"
+ "Failed to create current container. Error: %@"
+ "Failed to get all users"
+ "Failed to get container URL"
+ "Failed to get effective configuration"
+ "Failed to get providers"
+ "Failed to get store"
+ "Failed to get store descriptors"
+ "Failed to get store identifiers"
+ "Failed to load provider effective data for configurationID %{public}s. Error: %{public}@"
+ "Failed to load store data for configurationID %{public}s. Error: %{public}@"
+ "Failed to restore state for stores %{public}s. Error: %{public}@"
+ "Invalid value for setting '"
+ "Missing sandbox extension while accessing store '"
+ "No configuration ID was provided."
+ "No configuration named '"
+ "No file was found for the sandbox extension."
+ "No store named '"
+ "Not authorized to read configuration(s): "
+ "Provider priorities could not be found."
+ "The XPC connection has no audit token."
+ "The XPC proxy is not of the expected type '"
+ "The caller is not authorized to perform this operation."
+ "The provider registration for '"
+ "The sandbox extension token is malformed."
+ "The spec for configuration '"
+ "There is no current XPC connection."
+ "Unable to consume the sandbox extension (error "
+ "Unable to decode the underlying error."
+ "Unable to issue a sandbox extension token."
+ "Unauthorized provider(s): "
+ "Unknown configuration ID '"
+ "Unknown provider '"
- "DeviceConfiguration/ContainerManager.swift"
- "Failed to collect provider effective data for %{public}s with configurationID %{public}s. Error: %{public}@"
- "Failed to collect store data for %{public}@ with configurationID %{public}s. Error: %{public}@"
- "Failed to create current container. Error: "
```
