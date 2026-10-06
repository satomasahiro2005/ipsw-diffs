## libdns_services.dylib

> `/usr/lib/libdns_services.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xdec0` | `0xdeb8` | **`-0x8`** |

### Other Changes

```diff

-3066.0.0.502.1
+3085.0.0.0.1
Functions:
~ ____dnssd_client_handle_message_block_invoke : 3980 -> 3992
~ ___dnssd_svcb_access_address_hints_block_invoke : 212 -> 208
~ ___dnssd_svcb_access_address_hints_block_invoke_2 : 184 -> 180
~ _advertising_proxy_enable_with_interfaces : 264 -> 272
~ _adv_host_service_get_callback : 2920 -> 2916
~ __dnssd_getaddrinfo_result_copy_description : 620 -> 624
~ ___dnssd_svcb_is_valid_block_invoke : 152 -> 156
~ ___dnssd_svcb_access_sla_values_block_invoke : 100 -> 108
~ ___dnssd_svcb_access_tls_supported_groups_block_invoke : 124 -> 136
~ _advertising_proxy_subscription_cancel : 2788 -> 2784
~ _adv_instance_unsubscribe : 808 -> 804
~ _adv_instance_state_finalize : 1160 -> 1148
~ _adv_service_state_finalize : 1260 -> 1248
~ _advertising_proxy_browse_callback : 1180 -> 1176
~ _advertising_proxy_resolve_callback : 1488 -> 1484
~ _adv_subscriber_add : 1212 -> 1208
```
