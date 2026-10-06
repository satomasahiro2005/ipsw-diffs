## neagent

> `/usr/libexec/neagent`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1af1c` | `0x1b1e4` | **`+0x2c8`** |
| `__TEXT.__objc_methname` | `0x2db5` | `0x2efa` | **`+0x145`** |
| `__TEXT.__objc_stubs` | `0x25a0` | `0x2680` | **`+0xe0`** |
| `__TEXT.__oslogstring` | `0x3efa` | `0x3fbd` | **`+0xc3`** |
| `__TEXT.__cstring` | `0x18d3` | `0x195d` | **`+0x8a`** |
| `__DATA_CONST.__cfstring` | `0xb00` | `0xb60` | **`+0x60`** |
| `__DATA.__objc_selrefs` | `0xd30` | `0xd68` | **`+0x38`** |
| `__DATA.__objc_const` | `0x21e8` | `0x2208` | **`+0x20`** |
| `__TEXT.__auth_stubs` | `0x950` | `0x970` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0x4b8` | `0x4c8` | **`+0x10`** |
| `__TEXT.__const` | `0xf0` | `0xe0` | **`-0x10`** |
| `__DATA.__objc_ivar` | `0x174` | `0x178` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-2340.0.0.0.4
+2365.40.1.0.0

-  Symbols:   218
-  CStrings:  1175
+  Symbols:   220
+  CStrings:  1189
Symbols:
+ _NEGetConsoleUserUID
+ _getpwuid
Functions:
~ sub_100008610 : 116 -> 120
~ sub_10000868c -> sub_100008690 : 4304 -> 5012
CStrings:
+ "%@: %s - Register with PIR Server (group <%@> use case <%@> PrivacyProxyFailOpen <%d> serverURL <%@> privacyPassIssuer <%@> pirEnforceSecurity <%d>"
+ "%@: %s - pirPrivacyPassIssuerURL does not match NSPIRConfiguration.PrivacyPassIssuerURL for %@"
+ "%@: %s - pirServerURL does not match NSPIRConfiguration.PIRServerURL for %@"
+ "-[NEPIRChecker validatePIRConfiguration:]"
+ "/Library/Managed Preferences"
+ "_pirEnforceSecurity"
+ "com.apple.networkextension.urlfilter.plist"
+ "dictionaryWithContentsOfFile:"
+ "infoPlistPIRServerURL"
+ "infoPlistPrivacyPassIssuerURL"
+ "initWithKeyExpirationMinutes:keyRotationBeforeExpirationMinutes:keyRotationIgnoreMissingEvaluationKey:useCases:networkConfig:requirePowerOfTwoShardCount:"
+ "setPirPrivacyPassIssuerURL:"
+ "setPirServerURL:"
+ "setUseUserTierTokenKey:"
+ "urlfilterProfileEnabled"
- "%@: %s - Register with PIR Server (group <%@> use case <%@> PrivacyProxyFailOpen <%d> serverURL <%@> privacyPassIssuer <%@>"
```
