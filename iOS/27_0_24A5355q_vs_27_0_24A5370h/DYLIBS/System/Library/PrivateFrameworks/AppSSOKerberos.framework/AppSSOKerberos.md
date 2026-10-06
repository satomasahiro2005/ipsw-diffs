## AppSSOKerberos

> `/System/Library/PrivateFrameworks/AppSSOKerberos.framework/AppSSOKerberos`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__const` | `0x150` | `0x160` | **`+0x10`** |
| `__TEXT.__text` | `0x201d0` | `0x201c4` | **`-0xc`** |

### Other Changes

```diff

-635.0.0.0.0
+643.0.12.0.0
Functions:
~ +[SOSmartcard availableSmartCards] : 1404 -> 1400
~ ___114-[SOADSiteDiscovery discoverADInfoUsingSourceAppBundleIdentifier:auditTokenData:requireTLSForLDAP:withCompletion:]_block_invoke : 824 -> 796
~ -[SOKerberosRealmSettings removeAllValues] : 396 -> 392
~ -[SOKerberosRealmSettings cacheSiteCode:] : 544 -> 540
~ -[SOKerberosRealmSettings siteCodeForNetworkFingerprint:] : 456 -> 452
~ -[SOKerberosExtensionData initWithDictionary:] : 6012 -> 6000
~ -[SOKerberosExtensionProcess handleGetSiteCode:] : 1624 -> 1620
~ -[SOKerberosExtensionProcess settingsForContext:includeSiteCodeCache:] : 1888 -> 1884
~ -[SOKerberosExtensionProcess checkSourceAppACLWithContext:] : 632 -> 628
~ -[SOKerberosAuthentication mapErrorToKnownError:] : 648 -> 692
~ _get_kerbvalidationinfo : 1084 -> 1096
```
