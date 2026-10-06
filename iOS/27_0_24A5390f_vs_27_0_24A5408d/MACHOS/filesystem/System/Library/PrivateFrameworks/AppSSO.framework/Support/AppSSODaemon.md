## AppSSODaemon

> `/System/Library/PrivateFrameworks/AppSSO.framework/Support/AppSSODaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7f20` | `0x8038` | **`+0x118`** |
| `__TEXT.__oslogstring` | `0x8f1` | `0x93a` | **`+0x49`** |
| `__DATA_CONST.__cfstring` | `0x520` | `0x540` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x1480` | `0x14a0` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0x1630` | `0x164f` | **`+0x1f`** |
| `__TEXT.__cstring` | `0xd97` | `0xdb3` | **`+0x1c`** |
| `__DATA.__objc_selrefs` | `0x688` | `0x690` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-643.0.33.0.0
+643.0.47.0.0

-  CStrings:  445
+  CStrings:  448
Functions:
~ sub_100007bd8 : 652 -> 932
CStrings:
+ "auditTokenFromData:auditToken:"
+ "com.apple.WebKit.Networking"
+ "using impersonated audit token supplied by entitled %{public}@ transport"
```
