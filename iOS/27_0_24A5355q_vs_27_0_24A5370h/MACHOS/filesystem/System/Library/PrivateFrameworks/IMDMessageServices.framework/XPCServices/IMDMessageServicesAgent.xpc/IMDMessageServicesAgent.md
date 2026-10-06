## IMDMessageServicesAgent

> `/System/Library/PrivateFrameworks/IMDMessageServices.framework/XPCServices/IMDMessageServicesAgent.xpc/IMDMessageServicesAgent`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__oslogstring` | `0x127a` | `0x1303` | **`+0x89`** |
| `__TEXT.__text` | `0x76cc` | `0x774c` | **`+0x80`** |
| `__TEXT.__gcc_except_tab` | `0x850` | `0x85c` | **`+0xc`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1481.100.29.2.9
+1483.100.10.2.4

-  CStrings:  344
+  CStrings:  345
Functions:
~ sub_1000026d0 : 468 -> 524
~ sub_100002d68 -> sub_100002da0 : 984 -> 944
~ sub_100003140 -> sub_100003150 : 836 -> 832
~ sub_10000389c -> sub_1000038a8 : 752 -> 748
~ sub_100004044 -> sub_10000404c : 568 -> 564
~ sub_10000485c -> sub_100004860 : 828 -> 824
~ sub_10000647c : 668 -> 664
~ sub_100006a30 -> sub_100006a2c : 1368 -> 1452
~ sub_1000075c0 -> sub_100007610 : 1852 -> 1908
~ sub_100007cfc -> sub_100007d84 : 316 -> 312
~ sub_100007ea4 -> sub_100007f28 : 1992 -> 1988
CStrings:
+ "Message (%@) cannot be sent via SMS because sms fallback is not enabled (encrypted: %{BOOL}d)"
+ "Not getting pending routes (isDefaultTextApp:%{BOOL}d  isSMSEnabled:%{BOOL}d  isSMSFallBackEnabled:%{BOOL}d  RCSEnabled:%{BOOL}d)"
+ "Watchdog: Nothing to do for message with guid %@ because it is already sent"
- "Message (%@) cannot be sent via SMS because it is using RCS Encryption."
- "Not getting pending routes (isDefaultTextApp:%@  isSMSEnabled:%@  isSMSFallBackEnabled:%@)"
```
