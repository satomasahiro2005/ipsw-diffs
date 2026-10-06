## SecureMessagingAgent

> `/System/Library/PrivateFrameworks/SecureMessaging.framework/SecureMessagingAgent`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__objc_methname` | `0x5` | `0x144` | **`+0x13f`** |
| `__TEXT.__objc_methlist` | `—` | `0x104` | **`+0x104`** |
| `__DATA.__objc_const` | `0x90` | `0x190` | **`+0x100`** |
| `__DATA.__data` | `0xb8` | `0x180` | **`+0xc8`** |
| `__TEXT.__objc_methtype` | `—` | `0xad` | **`+0xad`** |
| `__DATA.__objc_selrefs` | `0x8` | `0xa8` | **`+0xa0`** |
| `__TEXT.__cstring` | `0xb8` | `0xe8` | **`+0x30`** |
| `__TEXT.__text` | `0x1414` | `0x1440` | **`+0x2c`** |
| `__TEXT.__swift5_typeref` | `0x4f` | `0x71` | **`+0x22`** |
| `__DATA_CONST.__objc_protolist` | `—` | `0x20` | **`+0x20`** |
| `__TEXT.__objc_classname` | `0x35` | `0x50` | **`+0x1b`** |
| `__DATA_CONST.__objc_protorefs` | `—` | `0x10` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0x350` | `0x360` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x1b0` | `0x1b8` | **`+0x8`** |
| `__TEXT.__eh_frame` | `0x118` | `0x120` | **`+0x8`** |
| `__TEXT.__swift5_capture` | `0x14` | `0x18` | **`+0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
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
- `__TEXT.__unwind_info`

### Other Changes

```diff

-48.100.2.0.0
+51.100.1.0.0

-  Symbols:   77
-  CStrings:  7
+  Symbols:   78
+  CStrings:  48
Symbols:
+ _os_transaction_create
Functions:
~ sub_10000189c -> sub_1000019dc : 492 -> 516
~ sub_100001b00 -> sub_100001c58 : 56 -> 64
~ sub_100001b38 -> sub_100001c98 : 180 -> 192
CStrings:
+ "#16@0:8"
+ "@\"NSString\"16@0:8"
+ "@16@0:8"
+ "@24@0:8:16"
+ "@32@0:8:16@24"
+ "@40@0:8:16@24@32"
+ "B16@0:8"
+ "B24@0:8#16"
+ "B24@0:8:16"
+ "B24@0:8@\"Protocol\"16"
+ "B24@0:8@16"
+ "NSObject"
+ "OS_os_transaction"
+ "Q16@0:8"
+ "T#,R"
+ "T@\"NSString\",?,R,C"
+ "T@\"NSString\",R,C"
+ "TQ,R"
+ "Vv16@0:8"
+ "^{_NSZone=}16@0:8"
+ "autorelease"
+ "class"
+ "com.apple.securemessaging.agent.startup"
+ "conformsToProtocol:"
+ "debugDescription"
+ "description"
+ "hash"
+ "isEqual:"
+ "isKindOfClass:"
+ "isMemberOfClass:"
+ "isProxy"
+ "performSelector:"
+ "performSelector:withObject:"
+ "performSelector:withObject:withObject:"
+ "release"
+ "respondsToSelector:"
+ "retain"
+ "retainCount"
+ "self"
+ "superclass"
+ "zone"
```
