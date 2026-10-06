## otctl

> `/usr/sbin/otctl`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x189a4` | `0x186cc` | **`-0x2d8`** |
| `__TEXT.__cstring` | `0x39f9` | `0x3988` | **`-0x71`** |
| `__DATA_CONST.__cfstring` | `0x11c0` | `0x1220` | **`+0x60`** |
| `__TEXT.__objc_methname` | `0x3d8e` | `0x3d68` | **`-0x26`** |
| `__TEXT.__objc_stubs` | `0x2620` | `0x2640` | **`+0x20`** |
| `__TEXT.__auth_stubs` | `0x5d0` | `0x5c0` | **`-0x10`** |
| `__DATA.__objc_selrefs` | `0xe88` | `0xe90` | **`+0x8`** |
| `__DATA_CONST.__auth_got` | `0x2f8` | `0x2f0` | **`-0x8`** |
| `__TEXT.__const` | `0xa0` | `0xa8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-62460.2.3.0.0
+62460.40.49.502.1

-  Functions: 341
-  Symbols:   156
-  CStrings:  1216
+  Functions: 343
+  Symbols:   155
+  CStrings:  1215
Symbols:
+ _OBJC_CLASS_$_MetricSessionInfo
- _kSecurityRTCEventCategoryAccountDataAccessRecovery
- _objc_retain_x28
CStrings:
+ "  %s%lu pairs\n"
+ "Allowed MID/Stable IDs:           "
+ "Evicted Removals:                 "
+ "Unknown Reason Removals:          "
+ "User-Initiated Removals:          "
+ "allowed_mid_stable_trusted_device_ids"
+ "initWithSession:eventName:"
+ "sessionInfoWithAltDSID:flowID:deviceSessionID:"
+ "v104@?0@\"NSSet\"8@\"NSSet\"16@\"NSSet\"24@\"NSSet\"32@\"NSString\"40@\"NSString\"48@\"NSString\"56@\"NSNumber\"64@\"NSString\"72@\"OTMetricsSessionData\"80q88@\"NSError\"96"
- "    - %s\n"
- "  Evicted Removals:                 %lu devices\n"
- "  Machine IDs:                      %lu devices\n"
- "  Stable Trusted Device IDs:        %lu pairs\n"
- "  Unknown Reason Removals:          %lu devices\n"
- "  User-Initiated Removals:          %lu devices\n"
- "initWithKeychainCircleMetrics:altDSID:flowID:deviceSessionID:eventName:testsAreEnabled:canSendMetrics:category:"
- "machine_ids"
- "mid_stable_trusted_device_ids"
- "v112@?0@\"NSSet\"8@\"NSSet\"16@\"NSSet\"24@\"NSSet\"32@\"NSString\"40@\"NSString\"48@\"NSString\"56@\"NSNumber\"64@\"NSString\"72@\"OTMetricsSessionData\"80@\"NSSet\"88q96@\"NSError\"104"
```
