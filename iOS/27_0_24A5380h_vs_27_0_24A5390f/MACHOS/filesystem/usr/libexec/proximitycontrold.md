## proximitycontrold

> `/usr/libexec/proximitycontrold`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2642e8` | `0x260944` | **`-0x39a4`** |
| `__DATA.__bss` | `0x2bc60` | `0x2b270` | **`-0x9f0`** |
| `__TEXT.__const` | `0x21618` | `0x210a8` | **`-0x570`** |
| `__DATA.__data` | `0x17c68` | `0x179a8` | **`-0x2c0`** |
| `__TEXT.__constg_swiftt` | `0xd7ec` | `0xd674` | **`-0x178`** |
| `__TEXT.__swift5_typeref` | `0xf2ea` | `0xf184` | **`-0x166`** |
| `__DATA.__objc_const` | `0x18930` | `0x187d8` | **`-0x158`** |
| `__DATA_CONST.__const` | `0x154a8` | `0x15368` | **`-0x140`** |
| `__TEXT.__objc_methname` | `0xdf39` | `0xde19` | **`-0x120`** |
| `__TEXT.__oslogstring` | `0x7d0e` | `0x7c0e` | **`-0x100`** |
| `__TEXT.__swift5_reflstr` | `0x99b3` | `0x98e3` | **`-0xd0`** |
| `__TEXT.__swift5_fieldmd` | `0x9360` | `0x9298` | **`-0xc8`** |
| `__TEXT.__cstring` | `0x7d29` | `0x7c69` | **`-0xc0`** |
| `__TEXT.__unwind_info` | `0x6be8` | `0x6b80` | **`-0x68`** |
| `__TEXT.__objc_stubs` | `0x4200` | `0x41a0` | **`-0x60`** |
| `__TEXT.__swift5_assocty` | `0xed0` | `0xe70` | **`-0x60`** |
| `__TEXT.__swift5_proto` | `0x17d8` | `0x1788` | **`-0x50`** |
| `__DATA_CONST.__cfstring` | `0x460` | `0x420` | **`-0x40`** |
| `__TEXT.__objc_classname` | `0x2407` | `0x23c7` | **`-0x40`** |
| `__TEXT.__swift5_capture` | `0x349c` | `0x345c` | **`-0x40`** |
| `__TEXT.__eh_frame` | `0x6694` | `0x66cc` | **`+0x38`** |
| `__DATA.__objc_data` | `0x3910` | `0x38f0` | **`-0x20`** |
| `__DATA.__objc_selrefs` | `0x1db0` | `0x1d98` | **`-0x18`** |
| `__TEXT.__swift5_builtin` | `0x5a0` | `0x58c` | **`-0x14`** |
| `__TEXT.__swift5_types` | `0x8c0` | `0x8ac` | **`-0x14`** |
| `__DATA.__common` | `0x890` | `0x888` | **`-0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x478` | `0x470` | **`-0x8`** |
| `__TEXT.__objc_methlist` | `0x29c8` | `0x29c0` | **`-0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-376.0.10.0.0
+376.0.14.0.0

-  Functions: 10330
+  Functions: 10266

-  CStrings:  4174
+  CStrings:  4151
CStrings:
+ "### Peer ACL blocks Handoff for non-autoPaired device: peerACL=%s, relationship=%s"
+ "AudioAccessory"
+ "_regionContext"
+ "rateLimitedBoopCount"
- "### Peer ACL blocks Handoff for non-SharedHome device: peerACL=%s, relationship=%s"
- "$__lazy_storage_$_accessControlLevelObserver"
- "$__lazy_storage_$_p2pAllowRawObserver"
- "%s-Init"
- "AudioAccessory1,"
- "AudioAccessory5,"
- "AudioAccessory6,"
- "Defaulting on access control level."
- "Initial accessControlLevel: %s"
- "New accessControlLevel: "
- "Observed key path changed. kp=%s"
- "Start observing AirPlay settings"
- "Stop observing AirPlay settings"
- "Updating control flags: %s -> %s"
- "_TtC17proximitycontrold25AccessControlLevelMonitor"
- "_accessControlLevel"
- "_accessControlLevelRaw"
- "_p2pAllowRaw"
- "_requireEligibleForUserSessionAlways"
- "accessControlLevel"
- "airplayPrefs"
- "com.apple.airplay"
- "controlFlags"
- "persistentDomainForName:"
- "requireEligibleForUserSessionAlways"
- "standardUserDefaults"
- "updateTask"
```
