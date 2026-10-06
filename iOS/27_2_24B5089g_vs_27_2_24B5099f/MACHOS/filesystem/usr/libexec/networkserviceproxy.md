## networkserviceproxy

> `/usr/libexec/networkserviceproxy`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc1da4` | `0xc20e8` | **`+0x344`** |
| `__TEXT.__oslogstring` | `0x1176c` | `0x11846` | **`+0xda`** |
| `__DATA_CONST.__cfstring` | `0x8c40` | `0x8ce0` | **`+0xa0`** |
| `__TEXT.__cstring` | `0xdf5b` | `0xdfe1` | **`+0x86`** |
| `__DATA.__objc_const` | `0xb178` | `0xb1b8` | **`+0x40`** |
| `__TEXT.__objc_methname` | `0x1043c` | `0x10474` | **`+0x38`** |
| `__TEXT.__gcc_except_tab` | `0x388c` | `0x3898` | **`+0xc`** |
| `__DATA.__objc_ivar` | `0xa00` | `0xa08` | **`+0x8`** |
| `__TEXT.__const` | `0x2a0` | `0x2a8` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x19c0` | `0x19b8` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-990.0.0.0.0
+990.40.2.0.0

-  CStrings:  6327
+  CStrings:  6336
CStrings:
+ "$"
+ "%@ failed to create \"SafariTechnologyPreview PRIVATE UNENCRYPTED\" policies"
+ "Device Identity Failure Code"
+ "Device Identity Failure Domain"
+ "Device identity would be fetched on %@; deferral triggered by %{public}@ error %ld"
+ "DeviceIdentityFailureCode"
+ "DeviceIdentityFailureDomain"
+ "_deviceIdentityFailureCode"
+ "_deviceIdentityFailureDomain"
+ "deferring fetching device identity until %@, after %u failed retries; last recorded failure was %{public}@ error %ld"
+ "previously failed to fetch device identity with %{public}@ error %ld, allowing retry %u"
+ "unrecorded domain"
- "Device identity would be fetched on %@"
- "deferring fetching device identity until %@"
- "previously failed to fetch device identity, allowing retry %u"
```
