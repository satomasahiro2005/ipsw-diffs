## networkserviceproxy

> `/usr/libexec/networkserviceproxy`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc17fc` | `0xc1cd4` | **`+0x4d8`** |
| `__TEXT.__oslogstring` | `0x11613` | `0x1176c` | **`+0x159`** |
| `__DATA_CONST.__cfstring` | `0x8ba0` | `0x8c20` | **`+0x80`** |
| `__TEXT.__objc_stubs` | `0xd200` | `0xd260` | **`+0x60`** |
| `__TEXT.__objc_methname` | `0x103e2` | `0x1043c` | **`+0x5a`** |
| `__TEXT.__cstring` | `0xdeda` | `0xdf2a` | **`+0x50`** |
| `__TEXT.__gcc_except_tab` | `0x3828` | `0x3858` | **`+0x30`** |
| `__DATA.__objc_const` | `0xb158` | `0xb178` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0x3b28` | `0x3b40` | **`+0x18`** |
| `__DATA_CONST.__const` | `0x22e0` | `0x22f8` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x19b8` | `0x19c0` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x9fc` | `0xa00` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-980.0.0.0.0
+985.0.0.0.0

-  Functions: 2161
+  Functions: 2162

-  CStrings:  6312
+  CStrings:  6326
CStrings:
+ "Failed to write reboot fetch state to preference file"
+ "NSPRebootFetchCount"
+ "NSPRebootFetchLastDate"
+ "No previous server state in UEA, treating as first launch after boot"
+ "Reboot"
+ "Reboot config refresh is disabled by configuration"
+ "Skipping reboot config refresh, already fetched %u times today (max %u)"
+ "Triggering reboot config refresh (%u of %u allowed today)"
+ "_firstLaunchAfterBoot"
+ "cloud.llm.waitlist"
+ "hasMaxRebootFetchesPerDay"
+ "max reboot fetches per day changed to %u"
+ "maxRebootFetchesPerDay"
+ "startOfDayForDate:"
+ "v48@?0@\"NSPPrivacyProxySuccessResponse\"8@\"NSData\"16q24@\"NSString\"32@\"NSString\"40"
- "v40@?0@\"NSPPrivacyProxySuccessResponse\"8q16@\"NSString\"24@\"NSString\"32"
```
