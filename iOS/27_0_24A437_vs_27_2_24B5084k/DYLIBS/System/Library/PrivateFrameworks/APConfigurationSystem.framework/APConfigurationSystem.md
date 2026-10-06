## APConfigurationSystem

> `/System/Library/PrivateFrameworks/APConfigurationSystem.framework/APConfigurationSystem`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1d4d0` | `0x22e6c` | **`+0x599c`** |
| `__TEXT.__oslogstring` | `0x1069` | `0x1343` | **`+0x2da`** |
| `__TEXT.__const` | `0x3048` | `0x31f0` | **`+0x1a8`** |
| `__AUTH_CONST.__const` | `0x18a0` | `0x1a28` | **`+0x188`** |
| `__TEXT.__eh_frame` | `0x778` | `0x8b0` | **`+0x138`** |
| `__TEXT.__cstring` | `0x1680` | `0x1784` | **`+0x104`** |
| `__AUTH_CONST.__objc_const` | `0x32b0` | `0x33b0` | **`+0x100`** |
| `__AUTH_CONST.__auth_got` | `0x728` | `0x808` | **`+0xe0`** |
| `__TEXT.__unwind_info` | `0x9c8` | `0xa98` | **`+0xd0`** |
| `__AUTH.__objc_data` | `—` | `0xc8` | **`+0xc8`** |
| `__TEXT.__swift5_typeref` | `0xa62` | `0xb22` | **`+0xc0`** |
| `__TEXT.__swift5_reflstr` | `0x64f` | `0x6f8` | **`+0xa9`** |
| `__TEXT.__swift5_fieldmd` | `0xa80` | `0xb28` | **`+0xa8`** |
| `__DATA.__data` | `0x810` | `0x8a8` | **`+0x98`** |
| `__DATA.__bss` | `0x3980` | `0x3a00` | **`+0x80`** |
| `__TEXT.__constg_swiftt` | `0x9ac` | `0xa2c` | **`+0x80`** |
| `__TEXT.__objc_methlist` | `0xc64` | `0xcdc` | **`+0x78`** |
| `__DATA_CONST.__objc_selrefs` | `0x798` | `0x7e0` | **`+0x48`** |
| `__AUTH_CONST.__cfstring` | `0xaa0` | `0xae0` | **`+0x40`** |
| `__AUTH.__data` | `—` | `0x28` | **`+0x28`** |
| `__DATA_CONST.__got` | `0x2f0` | `0x318` | **`+0x28`** |
| `__TEXT.__swift5_capture` | `0xd8` | `0xf8` | **`+0x20`** |
| `__DATA_DIRTY.__data` | `0x7c0` | `0x7d8` | **`+0x18`** |
| `__TEXT.__swift5_assocty` | `—` | `0x18` | **`+0x18`** |
| `__DATA_CONST.__const` | `0x1d8` | `0x1e0` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x178` | `0x180` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x2a8` | `0x2b0` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0xe8` | `0xf0` | **`+0x8`** |
| `__TEXT.__swift5_protos` | `0x14` | `0x18` | **`+0x4`** |

### Other Changes

```diff

-557.1.33.0.0
+557.2.8.0.0

-  Functions: 970
-  Symbols:   301
-  CStrings:  240
+  Functions: 1046
+  Symbols:   314
+  CStrings:  257
Symbols:
+ _OBJC_CLASS_$_APConfigurationOverrideStore
+ _OBJC_CLASS_$_NSUUID
+ _OBJC_METACLASS_$_APConfigurationOverrideStore
+ _bzero
+ _kAPConfigSystemDeletingDir
+ _objc_retain_x25
+ _objc_retain_x27
+ _swift_arrayInitWithCopy
+ _swift_bridgeObjectRelease_n
+ _swift_release_x21
+ _swift_release_x23
+ _swift_release_x24
+ _swift_release_x25
CStrings:
+ " is not valid text."
+ "%@-%@"
+ "APCS-DELETING"
+ "APConfigurationSystem.ConfigurationOverrideStore"
+ "ConfigurationOverrideStore: Node %{public}s can not be overridden."
+ "ConfigurationOverrideStore: Overriding node %{public}s properties: %{public}s"
+ "Reset Configuration System: Configuration was already removed before it could be moved aside, nothing to do."
+ "Reset Configuration System: Container is gone, no scratch directories to delete."
+ "Reset Configuration System: Could not delete scratch directory, error: %{public}@."
+ "Reset Configuration System: Could not enumerate container to delete scratch directories, error: %{public}@."
+ "Reset Configuration System: Could not move current configuration aside, error: %{public}@, falling back to removing it in place."
+ "Reset Configuration System: Scratch directory deleted."
+ "com.apple.ap.configurationsystem.reset"
+ "configurationOverrideEnabled"
+ "coreAnalyticsThresholdMs"
+ "override_config_"
+ "slowQueryThresholdMs"
```
