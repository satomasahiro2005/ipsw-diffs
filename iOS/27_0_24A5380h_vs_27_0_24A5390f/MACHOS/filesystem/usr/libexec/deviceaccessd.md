## deviceaccessd

> `/usr/libexec/deviceaccessd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x91490` | `0x91ba4` | **`+0x714`** |
| `__TEXT.__cstring` | `0x151c4` | `0x152c4` | **`+0x100`** |
| `__TEXT.__objc_methname` | `0xa334` | `0xa3b4` | **`+0x80`** |
| `__TEXT.__objc_stubs` | `0x7e60` | `0x7ee0` | **`+0x80`** |
| `__DATA_CONST.__cfstring` | `0x21a0` | `0x21e0` | **`+0x40`** |
| `__TEXT.__const` | `0x1cc8` | `0x1c88` | **`-0x40`** |
| `__TEXT.__gcc_except_tab` | `0x408c` | `0x40c0` | **`+0x34`** |
| `__DATA.__objc_selrefs` | `0x2718` | `0x2738` | **`+0x20`** |
| `__DATA.__bss` | `0xeb8` | `0xec8` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x8d0` | `0x8c8` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x1a98` | `0x1aa0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-2700.27.0.0.0
+2700.30.0.0.0

-  Functions: 2514
-  Symbols:   915
-  CStrings:  3955
+  Functions: 2515
+  Symbols:   914
+  CStrings:  3966
Symbols:
- _OBJC_CLASS_$_NSSet
CStrings:
+ "### FlushPending: failed to open message with nil handler: %@"
+ "### FlushPending: failed to seal message with nil handler: %@"
+ "### _reportDiscoveredBTDevice %@ no advertised name yet (sighting %lu/%lu), deferring report"
+ "### _reportDiscoveredBTDevice adopting OTA name '%@' for %@"
+ "DAConnectedServiceMatch"
+ "Failed to create app store lockup request: %@"
+ "Failed to download icon for %@: %@"
+ "Failed to load app store assets: %@"
+ "Missing or invalid icon data for bundle ID: %@"
+ "NSString *get_ASCLockupKeyDistributorBundleId(void)"
+ "NamelessSightings"
+ "Reported"
+ "_ASCLockupKeyDistributorBundleId"
+ "_lockupRequestForBundleID:withContext:enableAppDistribution:completionBlock:"
+ "dsBd"
+ "finishTasksAndInvalidate"
+ "preUpgradeDiscoveryConfiguration"
+ "setManufacturerURL:"
+ "setPreUpgradeDiscoveryConfiguration:"
+ "v56@?0@\"NSString\"8@\"NSString\"16@\"NSString\"24@\"NSData\"32@\"NSString\"40@\"NSError\"48"
- "### Failed to create app store lockup request: %@"
- "### Failed to load app store assets: %@"
- "### _reportDiscoveredBTDevice %@ %@ has no bluetooth name"
- "(none)"
- "Failed to download icon: %@, using empty placeholder"
- "Missing or invalid icon data, using empty placeholder"
- "Successfully fetched app asset for %@: adamID=%@, name=%@, developer=%@, icon=%lu bytes"
- "_lockupRequestForBundleID:withContext:completionBlock:"
- "v48@?0@\"NSString\"8@\"NSString\"16@\"NSString\"24@\"NSData\"32@\"NSError\"40"
```
