## mDNSResponder

> `/usr/sbin/mDNSResponder`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x10a26c` | `0x10aa28` | **`+0x7bc`** |
| `__TEXT.__oslogstring` | `0x20ef8` | `0x210d6` | **`+0x1de`** |
| `__TEXT.__const` | `0x14bc` | `0x14f4` | **`+0x38`** |
| `__TEXT.__cstring` | `0x17aea` | `0x17ab8` | **`-0x32`** |
| `__TEXT.__auth_stubs` | `0x2fb0` | `0x2fc0` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x17e8` | `0x17f0` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x16d0` | `0x16d8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-3089.0.0.0.1
+3109.0.0.0.0

-  Functions: 1869
-  Symbols:   4149
-  CStrings:  4774
+  Functions: 1870
+  Symbols:   4151
+  CStrings:  4777
Symbols:
+ GCC_except_table1249
+ GCC_except_table1255
+ GCC_except_table1418
+ GCC_except_table1601
+ GCC_except_table1833
+ __exit
+ _mdns_powerlog_service_register_start
- GCC_except_table1248
- GCC_except_table1254
- GCC_except_table1417
- GCC_except_table1600
- GCC_except_table1832
Functions:
~ _mDNS_Deregister_internal : 4712 -> 4680
~ _mDNS_Execute : 25412 -> 25424
~ _request_callback : 44040 -> 44140
~ _register_service_instance : 3416 -> 4636
~ _mDNSCoreReceiveQuery : 10872 -> 10896
~ _SendResponses : 7580 -> 7588
~ _mDNSGetTSRForAuthRecordNamed : 304 -> 408
- _mDNS_ExtractKeepaliveInfo
+ _mDNS_ExtractKeepaliveInfo
~ _mDNSCoreReceiveResponse : 28056 -> 28064
~ _mDNS_StopNATOperation_internal : 1892 -> 1884
+ _mdns_powerlog_service_register_start
~ _SetRData : 4588 -> 4804
~ _handle_tsr_update_request : 1004 -> 1012
~ _mDNSPlatformGetRemoteMacAddr : 1368 -> 1288
~ _HandleSIG : 152 -> 160
~ __DNSRecordDataToStringEx2 : 5216 -> 5316
~ __mdns_message_copy_description : 3844 -> 3968
CStrings:
+ " ["
+ " key%u"
+ "FormatKeepaliveRData: not a valid record %s for keepalive %#a:%d %#a:%d"
+ "SetRData: rdata length %u for type %u exceeds storage %u"
+ "UpdateKeepaliveRDataWithMAC: Freed allocated memory for keep alive packet: %s "
+ "UpdateKeepaliveRDataWithMAC: successfully updated the record %s"
+ "mDNSResponder-3109"
+ "register_service_instance: TSR registration rejected, different host key for %{sensitive, mdnsresponder:domain_name}.*P %{mdns:dn_hash}u"
+ "register_service_instance: TSR registration rejected, existing non-TSR record for %{sensitive, mdnsresponder:domain_name}.*P %{mdns:dn_hash}u"
+ "register_service_instance: non-TSR registration rejected, existing TSR record for %{sensitive, mdnsresponder:domain_name}.*P %{mdns:dn_hash}u"
- " %s%s"
- " key%u=\""
- "UpdateKeepaliveRData: Freed allocated memory for keep alive packet: %s "
- "UpdateKeepaliveRData: could not allocate memory %s"
- "UpdateKeepaliveRData: not a valid record %s for keepalive %#a:%d %#a:%d"
- "UpdateKeepaliveRData: successfully updated the record %s"
- "mDNSResponder-3089.0.0.0.1"
```
