## storekitd

> `/System/Library/Frameworks/StoreKit.framework/Support/storekitd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5c4590` | `0x5c95ec` | **`+0x505c`** |
| `__DATA.__bss` | `0x55de8` | `0x567e8` | **`+0xa00`** |
| `__TEXT.__const` | `0x3eea0` | `0x3f410` | **`+0x570`** |
| `__DATA_CONST.__const` | `0x6ce08` | `0x6d358` | **`+0x550`** |
| `__TEXT.__eh_frame` | `0x3790c` | `0x3743c` | **`-0x4d0`** |
| `__TEXT.__cstring` | `0x1ebb5` | `0x1ef05` | **`+0x350`** |
| `__TEXT.__constg_swiftt` | `0x918c` | `0x9328` | **`+0x19c`** |
| `__TEXT.__swift5_typeref` | `0xbbc4` | `0xbd5e` | **`+0x19a`** |
| `__TEXT.__swift5_capture` | `0x1d5b4` | `0x1d74c` | **`+0x198`** |
| `__DATA.__objc_const` | `0x1cf68` | `0x1d0c0` | **`+0x158`** |
| `__TEXT.__swift5_fieldmd` | `0xc990` | `0xcae4` | **`+0x154`** |
| `__DATA.__data` | `0x13150` | `0x13290` | **`+0x140`** |
| `__DATA.__objc_data` | `0x5148` | `0x5270` | **`+0x128`** |
| `__TEXT.__objc_methlist` | `0x7b5c` | `0x7bf4` | **`+0x98`** |
| `__TEXT.__swift5_reflstr` | `0x72ef` | `0x737f` | **`+0x90`** |
| `__TEXT.__unwind_info` | `0x15e38` | `0x15eb0` | **`+0x78`** |
| `__TEXT.__swift5_proto` | `0x2cc8` | `0x2d20` | **`+0x58`** |
| `__TEXT.__objc_classname` | `0x25bf` | `0x260f` | **`+0x50`** |
| `__TEXT.__swift_as_ret` | `0x1f14` | `0x1ec4` | **`-0x50`** |
| `__DATA_CONST.__cfstring` | `0x5040` | `0x5000` | **`-0x40`** |
| `__TEXT.__oslogstring` | `0x708f` | `0x70c2` | **`+0x33`** |
| `__DATA_CONST.__auth_ptr` | `0x1850` | `0x1880` | **`+0x30`** |
| `__TEXT.__objc_methname` | `0x11e79` | `0x11e49` | **`-0x30`** |
| `__TEXT.__objc_methtype` | `0x4328` | `0x42f8` | **`-0x30`** |
| `__TEXT.__swift5_assocty` | `0x17a0` | `0x17d0` | **`+0x30`** |
| `__TEXT.__objc_stubs` | `0xcc40` | `0xcc60` | **`+0x20`** |
| `__TEXT.__swift5_types` | `0xd74` | `0xd8c` | **`+0x18`** |
| `__TEXT.__swift_as_entry` | `0x103c` | `0x1048` | **`+0xc`** |
| `__DATA.__common` | `0x1090` | `0x1088` | **`-0x8`** |
| `__DATA.__objc_selrefs` | `0x4580` | `0x4578` | **`-0x8`** |
| `__DATA_CONST.__got` | `0x1030` | `0x1038` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x618` | `0x620` | **`+0x8`** |
| `__TEXT.__swift5_protos` | `0x74` | `0x78` | **`+0x4`** |
| `__TEXT.__swift_as_cont` | `0x2ecc` | `0x2ec8` | **`-0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`

### Other Changes

```diff

-816.0.30.2.1
+816.0.34.0.0

-  Functions: 37364
-  Symbols:   1791
-  CStrings:  7255
+  Functions: 37514
+  Symbols:   1792
+  CStrings:  7274
Symbols:
+ _LSSystemApplicationType
CStrings:
+ " for Load Products API"
+ " is a system app"
+ " is installed for development and specifies its own storeItemID"
+ " is not of type "
+ " is not of type array"
+ " is not of type dictionary"
+ " is not of type string"
+ " is not of type url"
+ " is not using Octane, can't create a bag!"
+ " to create a bag, creating a new session"
+ "10:10:01"
+ "AppStoreItemIdentifier"
+ "Creating a new receipt signing identity"
+ "Failed to create snapshot bag: "
+ "Failed to load Octane configuration to create Octane bag, will use default values. "
+ "Failed to load Octane configuration to fetch simulated error: "
+ "Found an unknown StoreKitSimulatedError with no corresponding mapping: "
+ "Found simulated failure "
+ "Jun 13 2026"
+ "Octane server is not active, device is using Octane 2"
+ "Octane server is not enabled, device is using Octane 2"
+ "Some requested products were not found: "
+ "Unknown bag value of type "
+ "Using cached receipt signing identity"
+ "_TtC9storekitdP33_CB757B748C19B5637E5E295674DE926615LegacyOctaneBag"
+ "_TtC9storekitdP33_CB757B748C19B5637E5E295674DE926616OctaneServiceBag"
+ "commitmentPriceString"
+ "isPendingUnbundle"
+ "receivedPushAction:bundleIDs:"
+ "storekitd.LegacyOctaneBag"
+ "storekitd.OctaneServiceBag"
+ "typeForInstallMachinery"
- "21:32:53"
- "Assets"
- "Failed to create snapshot bag: %{public}@"
- "Found simulated failure: "
- "May 31 2026"
- "StoreKit/Octane/LoadSigningCertificate"
- "StoreKit/Octane/LoadSigningKey"
- "_TtC9storekitdP33_CB757B748C19B5637E5E295674DE92669OctaneBag"
- "_appNameForContext:"
- "initWithOctaneSimulatedError:"
- "receivedPushAction:bundleIDs:completionHandler:"
- "storekitd.OctaneBag"
- "v40@0:8Q16@\"NSArray\"24@?<v@?>32"
```
