## com.apple.CallKit.CallDirectory

> `/System/Library/Frameworks/CallKit.framework/XPCServices/com.apple.CallKit.CallDirectory.xpc/com.apple.CallKit.CallDirectory`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x21f9c` | `0x21b00` | **`-0x49c`** |
| `__TEXT.__objc_stubs` | `0x2a20` | `0x2920` | **`-0x100`** |
| `__TEXT.__objc_methname` | `0x40b9` | `0x4011` | **`-0xa8`** |
| `__TEXT.__cstring` | `0x84b` | `0x823` | **`-0x28`** |
| `__DATA.__objc_selrefs` | `0xda8` | `0xd88` | **`-0x20`** |
| `__TEXT.__auth_stubs` | `0x10d0` | `0x10b0` | **`-0x20`** |
| `__DATA_CONST.__auth_got` | `0x878` | `0x868` | **`-0x10`** |
| `__DATA.__data` | `0x7a8` | `0x7a0` | **`-0x8`** |
| `__DATA_CONST.__got` | `0x1e0` | `0x1d8` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x780` | `0x788` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
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

-145.100.7.2.1
+147.100.5.2.1

-  Symbols:   248
-  CStrings:  1013
+  Symbols:   246
+  CStrings:  1008
Symbols:
+ _swift_release_x24
- _OBJC_CLASS_$_NSUserDefaults
- _swift_getObjCClassFromMetadata
- _swift_release_x28
Functions:
~ sub_100019800 : 152 -> 124
~ sub_100019898 -> sub_10001987c : 148 -> 124
~ sub_10001a7bc -> sub_10001a788 : 708 -> 696
~ sub_10001aa80 -> sub_10001aa40 : 3572 -> 3352
~ sub_10001b9ac -> sub_10001b890 : 5528 -> 4928
~ sub_10001d074 -> sub_10001cd00 : 4000 -> 3940
~ sub_10001e014 -> sub_10001dc64 : 388 -> 372
~ sub_10001e198 -> sub_10001ddd8 : 4400 -> 4332
~ sub_10002160c -> sub_100021208 : 400 -> 244
~ sub_100021ed4 -> sub_100021a34 : 16 -> 76
~ sub_100021ee4 -> sub_100021a80 : 28 -> 16
~ sub_100021f00 -> sub_100021a90 : 20 -> 28
~ sub_100021f14 -> sub_100021aac : 84 -> 20
~ sub_100021f68 -> sub_100021ac0 : 72 -> 84
CStrings:
- "boolForKey:"
- "initWithType:endpoint:issuer:bearerToken:featureId:privacyProxyFailOpen:useUserTierTokenKey:fetchConfigViaProxy:"
- "instancesRespondToSelector:"
- "livecalleridProfileEnabled"
- "standardUserDefaults"
```
