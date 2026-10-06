## AppIntentsDiagnosticExtension

> `/System/Library/Frameworks/AppIntents.framework/PlugIns/AppIntentsDiagnosticExtension.appex/AppIntentsDiagnosticExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__objc_methname` | `0xeb6` | `0xfb1` | **`+0xfb`** |
| `__TEXT.__objc_methtype` | `0x960` | `0x99d` | **`+0x3d`** |
| `__TEXT.__objc_methlist` | `0x3ec` | `0x424` | **`+0x38`** |
| `__DATA.__objc_const` | `0x310` | `0x338` | **`+0x28`** |
| `__DATA.__objc_selrefs` | `0x368` | `0x390` | **`+0x28`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-301.0.43.6.0
+301.0.45.4.101

-  CStrings:  218
+  CStrings:  225
CStrings:
+ "Vv24@0:8@?<v@?B@\"NSError\">16"
+ "checkOperationRestrictionsForBundleIdentifier:reply:"
+ "entityForBundleIdentifier:withEntityIdentifier:waitForIndexing:reply:"
+ "purgeBundleWithoutReindexingWithIdentifier:reply:"
+ "searchForQuery:reply:"
+ "subscribeForOperationRestrictionInvalidationsWithReply:"
+ "v32@0:8@\"NSString\"16@?<v@?@\"LNSearchResult\"@\"NSError\">24"
+ "v40@0:8@\"NSString\"16@\"NSString\"24@?<v@?@\"NSData\"@\"NSError\">32"
+ "v40@0:8@\"NSString\"16@\"NSString\"24@?<v@?@\"NSString\"@\"NSError\">32"
+ "v44@0:8@\"NSString\"16@\"NSString\"24B32@?<v@?@\"NSString\"@\"NSError\">36"
- "v40@0:8@\"NSString\"16@\"NSString\"24@?<v@?@\"LNEntityMetadata\"@\"NSError\">32"
- "v40@0:8@\"NSString\"16@\"NSString\"24@?<v@?@\"LNQueryMetadata\"@\"NSError\">32"
- "v44@0:8@\"NSString\"16@\"NSString\"24B32@?<v@?@\"LNActionMetadata\"@\"NSError\">36"
```
