## MessagesPluginNotificationExtension

> `/private/var/staged_system_apps/MobileSMS.app/PlugIns/MessagesPluginNotificationExtension.appex/MessagesPluginNotificationExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4cc8` | `0x5294` | **`+0x5cc`** |
| `__TEXT.__objc_stubs` | `0x3e0` | `0x420` | **`+0x40`** |
| `__TEXT.__oslogstring` | `0x3e3` | `0x423` | **`+0x40`** |
| `__TEXT.__eh_frame` | `0xe0` | `0x110` | **`+0x30`** |
| `__TEXT.__objc_methname` | `0x561` | `0x591` | **`+0x30`** |
| `__TEXT.__cstring` | `0x11e` | `0x13a` | **`+0x1c`** |
| `__DATA.__objc_selrefs` | `0x1f0` | `0x200` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x178` | `0x180` | **`+0x8`** |
| `__TEXT.__swift5_capture` | `0x3c` | `0x40` | **`+0x4`** |
| `__TEXT.__swift5_typeref` | `0xc0` | `0xc4` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-1483.100.10.2.4
+1486.100.5.2.1

-  CStrings:  124
+  CStrings:  128
Symbols:
+ _objc_retain_x28
+ _swift_release_x22
- _objc_retain_x22
- _objc_retain_x25
Functions:
~ sub_1000023dc : 1028 -> 1476
~ sub_100003500 -> sub_1000036c0 : 4012 -> 4992
~ sub_1000044ac -> sub_100004a40 : 196 -> 208
~ sub_100004570 -> sub_100004b10 : 188 -> 200
~ sub_10000645c -> sub_100006a08 : 80 -> 88
~ sub_1000064ac -> sub_100006a60 : 172 -> 196
CStrings:
+ "CKBBContextKeyMessageGUID"
+ "Missing message GUID for notification identifier: %s"
+ "account"
+ "strippedLogin"
```
