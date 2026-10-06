## ckdiscretionaryd

> `/System/Library/PrivateFrameworks/CloudKitDaemon.framework/Support/ckdiscretionaryd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x69ec` | `0x6d34` | **`+0x348`** |
| `__TEXT.__objc_stubs` | `0x1500` | `0x16a0` | **`+0x1a0`** |
| `__TEXT.__objc_methname` | `0x1a2e` | `0x1bc4` | **`+0x196`** |
| `__TEXT.__oslogstring` | `0x763` | `0x7ec` | **`+0x89`** |
| `__DATA.__objc_selrefs` | `0x718` | `0x780` | **`+0x68`** |
| `__DATA.__objc_const` | `0x1428` | `0x1458` | **`+0x30`** |
| `__DATA_CONST.__cfstring` | `0x1e0` | `0x200` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0xa64` | `0xa84` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x180` | `0x198` | **`+0x18`** |
| `__TEXT.__objc_methtype` | `0x52f` | `0x541` | **`+0x12`** |
| `__TEXT.__auth_stubs` | `0x5c0` | `0x5d0` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x2f0` | `0x2f8` | **`+0x8`** |
| `__TEXT.__gcc_except_tab` | `0x384` | `0x38c` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0xd4` | `0xd8` | **`+0x4`** |
| `__TEXT.__cstring` | `0x367` | `0x36a` | **`+0x3`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-2720.15.0.0.0
+2720.17.0.0.0

-  Functions: 204
-  Symbols:   145
-  CStrings:  461
+  Functions: 207
+  Symbols:   149
+  CStrings:  479
Symbols:
+ _CKAssetRepairPushProxyFormat
+ _OBJC_CLASS_$_CKEntitlements
+ ___sTestOverridesAvailable
+ __os_log_fault_impl
CStrings:
+ "%@"
+ "%{public}@ is not entitled to set bundle identifier override '%{public}@'. Ignoring it and monitoring the caller's own identity instead."
+ "@\"CKEntitlements\""
+ "T@\"CKEntitlements\",&,N,V_clientEntitlements"
+ "_clientEntitlements"
+ "applicationBundleID"
+ "clientEntitlements"
+ "clientPrefixEntitlement"
+ "hasMasqueradingEntitlement"
+ "hasPrefix:"
+ "initWithAuditToken:pid:"
+ "length"
+ "processIdentifier"
+ "sanitizedBundleIdentifierOverride:"
+ "setApplicationBundleIdentifierOverride:"
+ "setClientEntitlements:"
+ "setSecondarySourceApplicationBundleId:"
+ "stringWithValidatedFormat:validFormatSpecifiers:error:"
```
