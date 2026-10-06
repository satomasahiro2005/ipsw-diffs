## fskitd

> `/usr/libexec/fskitd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4bf60` | `0x4c4d0` | **`+0x570`** |
| `__TEXT.__cstring` | `0x388e` | `0x3959` | **`+0xcb`** |
| `__TEXT.__oslogstring` | `0x44b0` | `0x4555` | **`+0xa5`** |
| `__TEXT.__objc_stubs` | `0x5240` | `0x52c0` | **`+0x80`** |
| `__TEXT.__objc_methname` | `0x67ec` | `0x683b` | **`+0x4f`** |
| `__TEXT.__gcc_except_tab` | `0x1f08` | `0x1f4c` | **`+0x44`** |
| `__DATA_CONST.__const` | `0x2610` | `0x2638` | **`+0x28`** |
| `__DATA_CONST.__cfstring` | `0x8e0` | `0x900` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x1138` | `0x1158` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0x1908` | `0x1920` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x22cc` | `0x22e4` | **`+0x18`** |
| `__TEXT.__auth_stubs` | `0xb40` | `0xb50` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x5b0` | `0x5b8` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x360` | `0x368` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`

### Other Changes

```diff

-971.0.0.0.5
+974.0.1.0.2

-  Functions: 1480
-  Symbols:   302
-  CStrings:  2087
+  Functions: 1486
+  Symbols:   304
+  CStrings:  2097
Symbols:
+ _FSTaskParameterConstantOptionReadOnly
+ _audit_token_to_euid
CStrings:
+ "%s: Privileged LiveFS.connection client"
+ "%s: caller euid %u not authorized to mount on %s (owner %u)"
+ "%s: failed to stat mountpoint %s for authorization: %d"
+ "-[fskitdXPCServer mountSingleVolumeForResource:bundleID:mountPath:options:replyHandler:]_block_invoke_3"
+ "Unable to return bundleID '%@' from entry %u to kernel"
+ "_S_module_bundle_id"
+ "_mountVolume:fileSystem:displayName:provider:domainError:on:how:optionsAsArray:auditToken:reply:"
+ "enumerateOptionsUsingBlock:"
+ "getBundleIDAttrData:"
+ "mountEntryTransaction:%@:%@:%@:teardown"
+ "removeMountPoint:"
+ "v40@?0@\"NSString\"8@\"NSString\"16Q24^B32"
- "%s: Client has LiveFS.connection entitlement"
- "mountVolume:fileSystem:displayName:provider:domainError:on:how:optionsAsArray:reply:"
```
