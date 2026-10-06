## SecureMessagingAgent

> `/System/Library/PrivateFrameworks/SecureMessaging.framework/SecureMessagingAgent`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__objc_methname` | `0x144` | `0x5` | **`-0x13f`** |
| `__TEXT.__objc_methlist` | `0x104` | `—` | **`-0x104`** |
| `__DATA.__objc_const` | `0x190` | `0x90` | **`-0x100`** |
| `__DATA.__data` | `0x180` | `0xb8` | **`-0xc8`** |
| `__TEXT.__objc_methtype` | `0xad` | `—` | **`-0xad`** |
| `__DATA.__objc_selrefs` | `0xa8` | `0x8` | **`-0xa0`** |
| `__TEXT.__eh_frame` | `0x120` | `0x168` | **`+0x48`** |
| `__TEXT.__swift5_typeref` | `0x71` | `0x4f` | **`-0x22`** |
| `__DATA_CONST.__objc_protolist` | `0x20` | `—` | **`-0x20`** |
| `__TEXT.__objc_classname` | `0x50` | `0x35` | **`-0x1b`** |
| `__DATA_CONST.__objc_protorefs` | `0x10` | `—` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0xd0` | `0xe0` | **`+0x10`** |
| `__TEXT.__swift5_capture` | `0x18` | `0x14` | **`-0x4`** |
| `__TEXT.__text` | `0x1444` | `0x1448` | **`+0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-59.100.1.0.0
+59.200.21.0.0

-  CStrings:  48
+  CStrings:  8
Functions:
~ sub_100001420 -> sub_1000012e0 : 248 -> 264
~ sub_100001844 -> sub_100001714 : 192 -> 200
~ sub_100001904 -> sub_1000017dc : 100 -> 112
~ sub_100001968 -> sub_10000184c : 100 -> 112
~ sub_1000019dc -> sub_1000018cc : 516 -> 492
~ sub_100001c58 -> sub_100001b30 : 64 -> 56
~ sub_100001c98 -> sub_100001b68 : 192 -> 180
CStrings:
- "#16@0:8"
- "@\"NSString\"16@0:8"
- "@16@0:8"
- "@24@0:8:16"
- "@32@0:8:16@24"
- "@40@0:8:16@24@32"
- "B16@0:8"
- "B24@0:8#16"
- "B24@0:8:16"
- "B24@0:8@\"Protocol\"16"
- "B24@0:8@16"
- "NSObject"
- "OS_os_transaction"
- "Q16@0:8"
- "T#,R"
- "T@\"NSString\",?,R,C"
- "T@\"NSString\",R,C"
- "TQ,R"
- "Vv16@0:8"
- "^{_NSZone=}16@0:8"
- "autorelease"
- "class"
- "conformsToProtocol:"
- "debugDescription"
- "description"
- "hash"
- "isEqual:"
- "isKindOfClass:"
- "isMemberOfClass:"
- "isProxy"
- "performSelector:"
- "performSelector:withObject:"
- "performSelector:withObject:withObject:"
- "release"
- "respondsToSelector:"
- "retain"
- "retainCount"
- "self"
- "superclass"
- "zone"
```
