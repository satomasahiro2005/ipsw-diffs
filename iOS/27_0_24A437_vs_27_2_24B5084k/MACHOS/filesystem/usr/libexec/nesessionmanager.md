## nesessionmanager

> `/usr/libexec/nesessionmanager`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb6ea0` | `0xb852c` | **`+0x168c`** |
| `__TEXT.__oslogstring` | `0x113c7` | `0x11b5b` | **`+0x794`** |
| `__TEXT.__cstring` | `0x5a93` | `0x5e08` | **`+0x375`** |
| `__TEXT.__objc_methname` | `0x9b2f` | `0x9d7c` | **`+0x24d`** |
| `__TEXT.__objc_stubs` | `0x8a20` | `0x8c20` | **`+0x200`** |
| `__DATA_CONST.__cfstring` | `0x2a40` | `0x2b20` | **`+0xe0`** |
| `__DATA.__objc_selrefs` | `0x2640` | `0x26c8` | **`+0x88`** |
| `__TEXT.__gcc_except_tab` | `0x2394` | `0x23f4` | **`+0x60`** |
| `__DATA.__objc_const` | `0x8738` | `0x8780` | **`+0x48`** |
| `__TEXT.__objc_methtype` | `0x2270` | `0x22b4` | **`+0x44`** |
| `__DATA_CONST.__const` | `0x1e48` | `0x1e88` | **`+0x40`** |
| `__TEXT.__auth_stubs` | `0x1e10` | `0x1e30` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x3fc4` | `0x3fe4` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x1738` | `0x1750` | **`+0x18`** |
| `__DATA_CONST.__auth_got` | `0xf18` | `0xf28` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x7f4` | `0x7fc` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x7e8` | `0x7f0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`

### Other Changes

```diff

-2340.0.0.0.4
+2365.40.1.0.0

-  Functions: 1960
-  Symbols:   711
-  CStrings:  4302
+  Functions: 1968
+  Symbols:   714
+  CStrings:  4369
Symbols:
+ _OBJC_CLASS_$_NEGuardProxyManager
+ __os_feature_enabled_impl
+ _getpwuid
CStrings:
+ "%@ cannot send outgoing call message, the provider is not running"
+ "%@ ignoring disposal of superseded provider"
+ "%@ ignoring extension exit from a superseded provider"
+ "%@ ignoring provider report from a superseded provider"
+ "%@ ignoring provider stop from a superseded provider"
+ "%@: %s - Failed to locate app bundle for %@"
+ "%@: %s - Register with PIR Server (group <%@> use case <%@> PrivacyProxyFailOpen <%d> serverURL <%@> privacyPassIssuer <%@> pirEnforceSecurity <%d>"
+ "%@: %s - pirPrivacyPassIssuerURL does not match NSPIRConfiguration.PrivacyPassIssuerURL for %@"
+ "%@: %s - pirServerURL does not match NSPIRConfiguration.PIRServerURL for %@"
+ "%@: Deregister last Filter Session calling stopGuardProxyManager: %@"
+ "%@: PreserveExistingConnections setting is enabled, updating filter configuration"
+ "%@: deferred provider start did not take effect"
+ "%@: deferring provider start until the previous provider is disposed"
+ "%@: ignoring start result from a superseded provider"
+ "%@: provider disposal did not complete within %d seconds, terminating the provider"
+ "%@: registration failed, rejecting start command from %@"
+ "%@: starting provider deferred by provider disposal"
+ "%s: Failed to install airPrint pass policies"
+ "%s: Policy IDs added for %@: %@"
+ "%s: Policy IDs to be removed for %@: %@"
+ "&"
+ "-[NEPIRChecker validatePIRConfiguration:]"
+ "-[NEPolicySession(AlwaysOnVPN) addAirPrintExceptionWithOrder:action:isAOVPN:policyIDList:]"
+ "-[NEPolicySession(AlwaysOnVPN) addBonjourWithOrder:policyIDList:]"
+ "-[NEPolicySession(AlwaysOnVPN) addPortPoliciesWithOrder:eAppUUID:appUUID:port:local:policyIDList:]"
+ "-[NESMPolicySession setPoliciesForAppRules:interfaceName:agentPIDs:hasDNS:hasProxy:skipTunnel:criticalDomains:excludedDomains:]_block_invoke"
+ "-[NESMPolicySession setPoliciesForAppRules:interfaceName:agentPIDs:hasDNS:hasProxy:skipTunnel:criticalDomains:excludedDomains:]_block_invoke_3"
+ "-[NESMPolicySession setPoliciesForFlowDivertRules:flowDivertControlUnit:hasDNS:hasProxy:providerUUIDs:excludedDomains:]_block_invoke"
+ "-[NESMPolicySession setPoliciesForFlowDivertRules:flowDivertControlUnit:hasDNS:hasProxy:providerUUIDs:excludedDomains:]_block_invoke_3"
+ "-[NESMURLFilterSession getInfoPlistPIRConfiguration]"
+ "/Library/Managed Preferences"
+ "<%@> Failed to allocate a control unit"
+ "<%@> Registered URL Filter session: %@"
+ "<%@> Registered content filter session: %@"
+ "EnableGuardProxy"
+ "Failed to register Always-On VPN session %@, the configuration is disabled"
+ "Failed to register DNS proxy session %@, the configuration is disabled"
+ "Failed to register DNS settings session %@, the configuration is disabled"
+ "Failed to register URL filter session %@, the configuration is disabled"
+ "Failed to register content filter session %@, the configuration is disabled"
+ "Failed to register enterprise VPN session %@, the configuration is disabled"
+ "Failed to register hotspot session %@, the configuration is disabled"
+ "Failed to register path controller session %@, the configuration is disabled"
+ "Failed to register per-app VPN session %@, the configuration is disabled"
+ "Failed to register personal %sVPN Session %@ due to enterprise %sVPN session %@ (status %d)"
+ "Failed to register personal VPN session %@, the configuration is disabled"
+ "Failed to register relay session %@, the configuration is disabled"
+ "Failed to register session %@, session with ID %@ and type %d is different: %@"
+ "Failed to register session %@, session with ID %@ not found"
+ "NESessionManager: starting guard proxy manager."
+ "NESessionManager: stopping guard proxy manager."
+ "NSPIRConfiguration"
+ "PIRServerURL"
+ "PreserveExistingConnections"
+ "PrivacyPassIssuerURL"
+ "Registered Always-On VPN session: %@"
+ "Registered DNS Proxy session: %@"
+ "Registered enterprise %sVPN session %@: stopping personal %sVPN session %@"
+ "Registered enterprise VPN session: %@"
+ "Registered path controller session: %@"
+ "^{__SecIdentity=}24@0:8@\"NEPvDFetcher\"16"
+ "^{__SecIdentity=}24@0:8@16"
+ "_disposingPlugin"
+ "_pirEnforceSecurity"
+ "bundleWithURL:"
+ "com.apple.networkextension.urlfilter.plist"
+ "copyCurrentIdentityForPvDFetcher:"
+ "dictionaryWithContentsOfFile:"
+ "infoDictionary"
+ "infoPlistPIRServerURL"
+ "infoPlistPrivacyPassIssuerURL"
+ "initWithKeyExpirationMinutes:keyRotationBeforeExpirationMinutes:keyRotationIgnoreMissingEvaluationKey:useCases:networkConfig:requirePowerOfTwoShardCount:"
+ "lookupIdentifier:plugins:"
+ "setInfoPlistPIRServerURL:"
+ "setInfoPlistPrivacyPassIssuerURL:"
+ "setPirPrivacyPassIssuerURL:"
+ "setPirServerURL:"
+ "setPreserveExistingConnections:"
+ "setUseUserTierTokenKey:"
+ "start"
+ "started guard proxy"
+ "stopWithCompletionHandler:"
+ "stringByAppendingPathComponent:"
+ "urlfilterProfileEnabled"
- "%@: %s - Register with PIR Server (group <%@> use case <%@> PrivacyProxyFailOpen <%d> serverURL <%@> privacyPassIssuer <%@>"
- "%@: <%@> Failed to allocate a control unit"
- "%@: <%@> Register DNS Proxy Session: %@"
- "%@: <%@> Register Filter Session: %@"
- "%@: <%@> Register URL Filter Session: %@"
- "%@: Failed to register Personal %sVPN Session %@ due to Enterprise %sVPN session %@ (status %d)"
- "%@: Failed to register session %@, session with ID %@ and type %d is different: %@"
- "%@: Failed to register session %@, session with ID %@ not found"
- "%@: Register Always-On VPN Session: %@"
- "%@: Register Enterprise %sVPN Session %@: stopping Personal %sVPN session %@"
- "%@: Register Enterprise VPN Session: %@"
- "%@: Register Path Controller Session: %@"
- "-[NEPolicySession(AlwaysOnVPN) addAirPrintExceptionWithOrder:action:isAOVPN:]"
- "-[NEPolicySession(AlwaysOnVPN) addBonjourWithOrder:]"
- "-[NEPolicySession(AlwaysOnVPN) addPortPoliciesWithOrder:eAppUUID:appUUID:port:local:]"
- "Failed to register session: %@ type: %d grade: %d vpn enabled: %d"
- "Policy IDs added for %@: %@"
```
