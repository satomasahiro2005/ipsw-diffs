## pcapd

> `/usr/libexec/pcapd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xe1b0` | `0xd2c0` | **`-0xef0`** |
| `__TEXT.__cstring` | `0x1244` | `0xe14` | **`-0x430`** |
| `__TEXT.__oslogstring` | `0x2934` | `0x2644` | **`-0x2f0`** |
| `__TEXT.__auth_stubs` | `0xd60` | `0xcc0` | **`-0xa0`** |
| `__DATA_CONST.__const` | `0x548` | `0x4b8` | **`-0x90`** |
| `__DATA.__data` | `0x388` | `0x310` | **`-0x78`** |
| `__DATA_CONST.__auth_got` | `0x6b8` | `0x668` | **`-0x50`** |
| `__DATA_CONST.__cfstring` | `0x40` | `—` | **`-0x40`** |
| `__TEXT.__unwind_info` | `0x278` | `0x238` | **`-0x40`** |
| `__DATA_CONST.__got` | `0x108` | `0xf0` | **`-0x18`** |
| `__DATA.__bss` | `0x10e0` | `0x10f0` | **`+0x10`** |
| `__TEXT.__const` | `0x1ca` | `0x1ba` | **`-0x10`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-76.0.0.0.0
+77.0.0.0.0

-  Functions: 235
-  Symbols:   282
-  CStrings:  409
+  Functions: 217
+  Symbols:   268
+  CStrings:  375
Symbols:
- _CFArrayContainsValue
- _CFArrayCreate
- _CFArrayGetCount
- _CFArrayGetTypeID
- _CFDictionaryCreate
- _CFDictionaryGetTypeID
- _CFDictionaryGetValue
- ___CFConstantStringClassReference
- _dispatch_once
- _kCFTypeArrayCallBacks
- _kCFTypeDictionaryKeyCallBacks
- _kCFTypeDictionaryValueCallBacks
- _lockdown_get_socket
- _lockdown_receive_message
CStrings:
+ "%s:%d %s pktap_filters are full"
+ "%s:%d Setting filter_param_if_name to %s"
+ "%s:%d Setting filter_param_if_name to %s\n"
+ "%s:%d dispatch_source_create() for DISPATCH_SOURCE_TYPE_READ failed."
+ "%s:%d dispatch_source_create() for DISPATCH_SOURCE_TYPE_READ failed.\n"
+ "%s:%d failure to kernel control socket"
+ "%s:%d failure to kernel control socket\n"
+ "%s:%d ioctl(SIOCGDRVSPEC, %s): errno=%d"
+ "%s:%d ioctl(SIOCGDRVSPEC, %s): errno=%d\n"
+ "%s:%d ioctl(SIOCSDRVSPEC, %s), errno=%d"
+ "%s:%d ioctl(SIOCSDRVSPEC, %s), errno=%d\n"
+ "%s:%d not enough space for bpf and pktap headers"
+ "%s:%d not enough space for bpf and pktap headers\n"
+ "%s:%d pcap_setup_pktap_interface() fail - %s"
+ "%s:%d pcap_setup_pktap_interface() fail - %s\n"
+ "%s:%d read bpf %s"
+ "%s:%d read bpf %s\n"
+ "%s:%d socket(PF_INET, SOCK_DGRAM) failed, errno=%d"
+ "%s:%d socket(PF_INET, SOCK_DGRAM) failed, errno=%d\n"
+ "%s:%d unable to send packet"
+ "%s:%d unable to send packet\n"
+ "cleanup_pktap"
+ "enable_pktap_filter"
+ "handle_pcapd_service"
+ "handle_pcapd_service_block_invoke"
+ "pcapd_open_bpf_device"
- "%s:%d BPF on %s unavailable, continuing without it"
- "%s:%d BPF on %s unavailable, continuing without it\n"
- "%s:%d dispatch_source_create() failed for capability listener"
- "%s:%d dispatch_source_create() failed for capability listener\n"
- "%s:%d dispatch_source_create() for %s failed"
- "%s:%d dispatch_source_create() for %s failed\n"
- "%s:%d dispatch_source_create() for %s failed; continuing without it"
- "%s:%d dispatch_source_create() for %s failed; continuing without it\n"
- "%s:%d droptap reason 0x%x line %u func %.*s"
- "%s:%d droptap reason 0x%x line %u func %.*s\n"
- "%s:%d failed to open BPF on %s"
- "%s:%d failed to open BPF on %s\n"
- "%s:%d host advertised droptap, opening DROPTAP_IFNAME"
- "%s:%d host advertised droptap, opening DROPTAP_IFNAME\n"
- "%s:%d host capability message did not advertise droptap; staying v2-only"
- "%s:%d host capability message did not advertise droptap; staying v2-only\n"
- "%s:%d invalid metadata header (%s pth_length=%u caplen=%u type_next=%u)"
- "%s:%d invalid metadata header (%s pth_length=%u caplen=%u type_next=%u)\n"
- "%s:%d lockdown_get_socket() failed; capability handshake skipped"
- "%s:%d lockdown_get_socket() failed; capability handshake skipped\n"
- "%s:%d lockdown_receive_message(capabilities) failed [%d]"
- "%s:%d lockdown_receive_message(capabilities) failed [%d]\n"
- "%s:%d lockdown_send_message(capability greeting) failed [%d]"
- "%s:%d lockdown_send_message(capability greeting) failed [%d]\n"
- "%s:%d metadata header overruns bpf buffer (%s metadata_size=%zu)"
- "%s:%d metadata header overruns bpf buffer (%s metadata_size=%zu)\n"
- "%s:%d not enough space for bpf and pktap headers (%s)"
- "%s:%d not enough space for bpf and pktap headers (%s)\n"
- "%s:%d pcap_setup_pktap_interface(%s) fail - %s"
- "%s:%d pcap_setup_pktap_interface(%s) fail - %s\n"
- "%s:%d pcapd_start_source(%s) refused: source already open on fd %d (ifname=%s)"
- "%s:%d pcapd_start_source(%s) refused: source already open on fd %d (ifname=%s)\n"
- "%s:%d pktap_hdr == NULL"
- "%s:%d pktap_hdr == NULL\n"
- "%s:%d read bpf %s: %s"
- "%s:%d read bpf %s: %s\n"
- "%s:%d rvi_bpf_to_iptap refused %s record (metadata_size=%zu caplen=%u); skipping"
- "%s:%d rvi_bpf_to_iptap refused %s record (metadata_size=%zu caplen=%u); skipping\n"
- "%s:%d rvi_bpf_to_iptap: invalid metadata_size=%zu bh_caplen=%u"
- "%s:%d rvi_bpf_to_iptap: invalid metadata_size=%zu bh_caplen=%u\n"
- "%s:%d rvi_capabilities_dict_create() failed"
- "%s:%d rvi_capabilities_dict_create() failed\n"
- "%s:%d unable to send %s packet, error: %d"
- "%s:%d unable to send %s packet, error: %d\n"
- "(null)"
- "_strict_reallocf called with size 0"
- "capabilities"
- "cleanup_pktap_source"
- "pcapd_drain_bpf"
- "pcapd_open_bpf_source"
- "pcapd_send_capability_greeting"
- "pcapd_send_capability_greeting_block_invoke"
- "pcapd_start_capability_listener"
- "pcapd_start_capability_listener_block_invoke"
- "pcapd_start_source"
- "pktap_hdr == NULL"
- "rvi_log_droptap_fields"
- "rvi_pktap_metadata_size"
- "strict_calloc count * size would overflow"
- "strict_calloc(%zu, %zu) failed"
```
