## FeedbackService

> `/System/Library/PrivateFrameworks/FeedbackService.framework/FeedbackService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x96d34` | `0x97db4` | **`+0x1080`** |
| `__DATA.__data` | `0x12e8` | `0x1638` | **`+0x350`** |
| `__DATA_DIRTY.__data` | `0x1a80` | `0x1730` | **`-0x350`** |
| `__AUTH_CONST.__objc_const` | `0x2fe0` | `0x31a0` | **`+0x1c0`** |
| `__TEXT.__cstring` | `0x2bd2` | `0x2d92` | **`+0x1c0`** |
| `__AUTH_CONST.__cfstring` | `0xe40` | `0xfe0` | **`+0x1a0`** |
| `__TEXT.__oslogstring` | `0x1476` | `0x1606` | **`+0x190`** |
| `__DATA.__bss` | `0xb570` | `0xb6b0` | **`+0x140`** |
| `__DATA_DIRTY.__bss` | `0xb6c0` | `0xb5a0` | **`-0x120`** |
| `__TEXT.__objc_methlist` | `0x1420` | `0x1500` | **`+0xe0`** |
| `__DATA_CONST.__objc_selrefs` | `0xbe8` | `0xc60` | **`+0x78`** |
| `__AUTH.__objc_data` | `0x3f0` | `0x440` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x2718` | `0x2760` | **`+0x48`** |
| `__DATA_CONST.__const` | `0x588` | `0x5c8` | **`+0x40`** |
| `__AUTH_CONST.__const` | `0x61c9` | `0x61f0` | **`+0x27`** |
| `__DATA.__common` | `0x28` | `0x40` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x120` | `0x138` | **`+0x18`** |
| `__DATA_DIRTY.__common` | `0xe8` | `0xd0` | **`-0x18`** |
| `__DATA_CONST.__got` | `0x438` | `0x440` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x150` | `0x158` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x70` | `0x78` | **`+0x8`** |

### Other Changes

```diff

-238.0.0.0.0
+240.0.0.0.0

-  Functions: 3897
-  Symbols:   2103
-  CStrings:  467
+  Functions: 3928
+  Symbols:   2144
+  CStrings:  487
Symbols:
+ +[FBKEnvironmentConfig configForEnvironmentName:]
+ +[FBKEnvironmentConfig internalEnvironmentsByName]
+ +[FBKEnvironmentConfig isInternalInstall]
+ +[FBKEnvironmentConfig productionConfig]
+ +[FBKEnvironmentConfig resolvedConfigForEnvironmentName:]
+ +[FBKEnvironmentConfig resolvedConfigForEnvironmentName:defaults:]
+ +[FBKSSharedConstants overrideEnvironment:]
+ +[FBKSSharedConstants usesCertificatePinning]
+ -[FBKEnvironmentConfig .cxx_destruct]
+ -[FBKEnvironmentConfig cookieName]
+ -[FBKEnvironmentConfig description]
+ -[FBKEnvironmentConfig disableCertificatePinning]
+ -[FBKEnvironmentConfig filerURL]
+ -[FBKEnvironmentConfig host]
+ -[FBKEnvironmentConfig initWithName:host:disableCertificatePinning:usesUATAuth:cookieName:filerURL:]
+ -[FBKEnvironmentConfig logDescription]
+ -[FBKEnvironmentConfig name]
+ -[FBKEnvironmentConfig usesUATAuth]
+ _FBKBoolFromPlistEntry
+ _FBKSCustomCookieNameKey
+ _FBKSCustomDisableCertificatePinningKey
+ _FBKSCustomFilerURLKey
+ _FBKSCustomHostKey
+ _FBKSCustomUsesUATAuthKey
+ _FBKStringFromPlistEntry
+ _FBKValidateBoolField
+ _FBKValidateStringField
+ _OBJC_CLASS_$_FBKEnvironmentConfig
+ _OBJC_IVAR_$_FBKEnvironmentConfig._cookieName
+ _OBJC_IVAR_$_FBKEnvironmentConfig._disableCertificatePinning
+ _OBJC_IVAR_$_FBKEnvironmentConfig._filerURL
+ _OBJC_IVAR_$_FBKEnvironmentConfig._host
+ _OBJC_IVAR_$_FBKEnvironmentConfig._name
+ _OBJC_IVAR_$_FBKEnvironmentConfig._usesUATAuth
+ _OBJC_METACLASS_$_FBKEnvironmentConfig
+ __OBJC_$_CLASS_METHODS_FBKEnvironmentConfig
+ __OBJC_$_INSTANCE_METHODS_FBKEnvironmentConfig
+ __OBJC_$_INSTANCE_VARIABLES_FBKEnvironmentConfig
+ __OBJC_$_PROP_LIST_FBKEnvironmentConfig
+ __OBJC_CLASS_RO_$_FBKEnvironmentConfig
+ __OBJC_METACLASS_RO_$_FBKEnvironmentConfig
+ ___40+[FBKEnvironmentConfig productionConfig]_block_invoke
+ ___50+[FBKEnvironmentConfig internalEnvironmentsByName]_block_invoke
+ ___block_descriptor_40_e5_v8?0l
+ ___block_descriptor_40_e8_32s_e15_v32?0816^B24ls32l8
+ _internalEnvironmentsByName.environments
+ _internalEnvironmentsByName.onceToken
+ _productionConfig.config
+ _productionConfig.onceToken
- +[FBKSSharedConstants overrideEnvironment:host:]
- _FBKSDevelopmentHostKey
- _FBKSEnvironmentDemoString
- _FBKSEnvironmentDevelopmentString
- _FBKSEnvironmentProductionString
- _FBKSEnvironmentStagingDevString
- _FBKSEnvironmentStagingString
- __overrideHostString
CStrings:
+ "%{public}s: -> %{public}@"
+ "%{public}s: resolved from defaults -> %{public}@"
+ "+[FBKSSharedConstants environment]"
+ "+[FBKSSharedConstants overrideEnvironment:]"
+ "/AppleInternal/Library/Application Support/com.apple.feedback/environments.plist"
+ "<%@: %@ host=%@ disablePinning=%@ usesUATAuth=%@>"
+ "Running in custom environment; skipping pinning check (internal only)."
+ "cookieName"
+ "custom"
+ "customCookieName"
+ "customDisableCertificatePinning"
+ "customFilerURL"
+ "customHost"
+ "customUsesUATAuth"
+ "disableCertificatePinning"
+ "environments.plist at %{public}@ is missing or not a dictionary"
+ "environments.plist contains a malformed top-level entry (key or value has wrong type); skipping"
+ "environments.plist entry '%{public}@' failed validation; skipping"
+ "environments.plist entry '%{public}@' missing or invalid required bool field '%{public}@'"
+ "environments.plist entry '%{public}@' missing or invalid required string field '%{public}@'"
+ "filerURL"
+ "host"
+ "https://cssubmissions.apple.com/CusSeedSub/submit?version=2"
+ "name=[%@] host=[%@] cookie=[%@] filer=[%@] disablePinning=[%@] usesUATAuth=[%@]"
+ "uat"
+ "usesUATAuth"
+ "v32@?0@8@16^B24"
- "%{public}s: %hd -> [%hd] [%{public}@]"
- "+[FBKSSharedConstants overrideEnvironment:host:]"
- "Running in development/stagingDev mode; skipping pinning check (internal only)."
- "Using non-production server: %{public}@"
- "developmentHost"
- "staging"
- "stagingDev"
```
