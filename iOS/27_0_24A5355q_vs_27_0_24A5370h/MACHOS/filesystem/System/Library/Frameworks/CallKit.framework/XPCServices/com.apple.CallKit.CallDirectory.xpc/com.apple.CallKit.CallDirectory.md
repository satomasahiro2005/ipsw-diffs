## com.apple.CallKit.CallDirectory

> `/System/Library/Frameworks/CallKit.framework/XPCServices/com.apple.CallKit.CallDirectory.xpc/com.apple.CallKit.CallDirectory`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x210ac` | `0x21f9c` | **`+0xef0`** |
| `__TEXT.__objc_methname` | `0x3f41` | `0x40b9` | **`+0x178`** |
| `__TEXT.__objc_stubs` | `0x2900` | `0x2a20` | **`+0x120`** |
| `__TEXT.__cstring` | `0x773` | `0x84b` | **`+0xd8`** |
| `__DATA.__objc_selrefs` | `0xd60` | `0xda8` | **`+0x48`** |
| `__DATA.__objc_const` | `0x2928` | `0x2968` | **`+0x40`** |
| `__TEXT.__eh_frame` | `0x530` | `0x560` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x1714` | `0x1744` | **`+0x30`** |
| `__TEXT.__auth_stubs` | `0x10b0` | `0x10d0` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x760` | `0x780` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0x868` | `0x878` | **`+0x10`** |
| `__DATA.__data` | `0x7a0` | `0x7a8` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x1d8` | `0x1e0` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0x28` | `0x2c` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-139.100.27.2.9
+143.100.11.2.1

-  Functions: 746
-  Symbols:   246
-  CStrings:  998
+  Functions: 754
+  Symbols:   248
+  CStrings:  1013
Symbols:
+ _OBJC_CLASS_$_NSUserDefaults
+ _swift_getObjCClassFromMetadata
CStrings:
+ "TB,N,R"
+ "boolForKey:"
+ "boolValue"
+ "immediateKeyExpirationEnabled"
+ "initWithKeyExpirationMinutes:keyRotationBeforeExpirationMinutes:keyRotationIgnoreMissingEvaluationKey:useCases:networkConfig:requirePowerOfTwoShardCount:"
+ "initWithType:endpoint:issuer:bearerToken:featureId:privacyProxyFailOpen:useUserTierTokenKey:fetchConfigViaProxy:"
+ "instancesRespondToSelector:"
+ "liveCallerIDImmediateKeyExpirationDisabled"
+ "liveCallerIDReducedMaxShardCountDisabled"
+ "liveCallerIDRequirePowerOfTwoShardCountDisabled"
+ "livecalleridProfileEnabled"
+ "reducedMaxShardCountEnabled"
+ "requirePowerOfTwoShardCountEnabled"
+ "robustNetworkManagerDisabled"
+ "robustNetworkManagerEnabled"
+ "standardUserDefaults"
- "initWithKeyExpirationMinutes:keyRotationBeforeExpirationMinutes:useCases:networkConfig:"
```
