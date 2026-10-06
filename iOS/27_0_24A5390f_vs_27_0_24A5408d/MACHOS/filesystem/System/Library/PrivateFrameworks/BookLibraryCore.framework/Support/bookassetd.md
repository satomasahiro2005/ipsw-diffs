## bookassetd

> `/System/Library/PrivateFrameworks/BookLibraryCore.framework/Support/bookassetd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xe1014` | `0xe11c4` | **`+0x1b0`** |
| `__TEXT.__objc_stubs` | `0xd240` | `0xd340` | **`+0x100`** |
| `__TEXT.__objc_methname` | `0x11826` | `0x118ce` | **`+0xa8`** |
| `__DATA.__objc_const` | `0xb260` | `0xb2a0` | **`+0x40`** |
| `__DATA.__objc_selrefs` | `0x4098` | `0x40d8` | **`+0x40`** |
| `__DATA_CONST.__const` | `0x7df0` | `0x7e10` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x6338` | `0x6350` | **`+0x18`** |
| `__TEXT.__oslogstring` | `0xc522` | `0xc53a` | **`+0x18`** |
| `__DATA_CONST.__objc_catlist` | `0x40` | `0x48` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-2309.0.0.0.0
+2310.0.0.0.0

-  Functions: 2406
+  Functions: 2407

-  CStrings:  4563
+  CStrings:  4571
CStrings:
+ "(dID=%{public}@) [Purchase-Mgr]: presentingSceneIdentifier: %@, auditToken.length: %lu"
+ "auditToken"
+ "bl_clientInfoForPurchase:auditTokenData:"
+ "callerBundleId"
+ "clientId"
+ "dq_performPurchaseWithRequest:downloadID:uiHostProxy:auditTokenData:completion:"
+ "initWithBytes:length:"
+ "setAuditTokenData:"
+ "setClientInfo:"
+ "setProxyAppBundleID:"
- "(dID=%{public}@) [Purchase-Mgr]: presentingSceneIdentifier: %@"
- "dq_performPurchaseWithRequest:downloadID:uiHostProxy:completion:"
```
