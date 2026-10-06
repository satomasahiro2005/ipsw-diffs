## networkserviceproxy

> `/usr/libexec/networkserviceproxy`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xbcc30` | `0xbc650` | **`-0x5e0`** |
| `__TEXT.__oslogstring` | `0x110f2` | `0x10fcd` | **`-0x125`** |
| `__TEXT.__auth_stubs` | `0x1970` | `0x18e0` | **`-0x90`** |
| `__DATA_CONST.__const` | `0x22b0` | `0x2238` | **`-0x78`** |
| `__TEXT.__objc_stubs` | `0xcc20` | `0xcc80` | **`+0x60`** |
| `__TEXT.__objc_methname` | `0xff49` | `0xff9a` | **`+0x51`** |
| `__TEXT.__gcc_except_tab` | `0x35a4` | `0x3554` | **`-0x50`** |
| `__DATA_CONST.__auth_got` | `0xcc8` | `0xc80` | **`-0x48`** |
| `__DATA.__objc_const` | `0xb0a0` | `0xb0d0` | **`+0x30`** |
| `__DATA_CONST.__objc_intobj` | `0x6a8` | `0x6d8` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x1970` | `0x1948` | **`-0x28`** |
| `__DATA_CONST.__cfstring` | `0x8b00` | `0x8ae0` | **`-0x20`** |
| `__TEXT.__cstring` | `0xdcf2` | `0xdd0b` | **`+0x19`** |
| `__DATA.__objc_selrefs` | `0x39b0` | `0x39c8` | **`+0x18`** |
| `__TEXT.__objc_methtype` | `0x2a75` | `0x2a69` | **`-0xc`** |
| `__DATA.__objc_ivar` | `0x9e8` | `0x9ec` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-964.0.0.502.1
+974.0.0.0.0

-  Functions: 2152
-  Symbols:   647
-  CStrings:  6226
+  Functions: 2147
+  Symbols:   638
+  CStrings:  6223
Symbols:
+ _OBJC_CLASS_$_NEPvDFetcher
+ _nw_resolver_config_set_oblivious_proxy_url
- __dispatch_data_empty
- _nw_content_context_copy_protocol_metadata
- _nw_http_fields_access_value_by_name
- _nw_http_metadata_copy_response
- _nw_http_response_copy_header_fields
- _nw_http_response_get_status_code
- _nw_parameters_copy
- _nw_protocol_copy_http_definition
- _nw_protocol_definition_get_identifier
- _nw_protocol_options_copy_definition
- _nw_protocol_stack_remove_protocol
CStrings:
+ "AdAttributionEnabled"
+ "Enabling discovered map for %@ (%u%% chance of enablement)"
+ "Installed app %@ is in OHTTP or proxied content map config, re-applying proxy info"
+ "Not enabling discovered map for %@ (%u%% chance of enablement)"
+ "PvD fetch failed: %@"
+ "TB,N,V_adAttributionEnabled"
+ "_adAttributionEnabled"
+ "adAttributionEnabled"
+ "aggregator config changed"
+ "aggregatorConfig"
+ "fetchPvDWithEndpoint:parameters:queue:completionHandler:"
+ "https://mask-api.icloud.com/v6_1/fetchConfigFile"
+ "rawDictionary"
+ "setAdAttributionEnabled:"
+ "v24@?0@\"NEPvDConfiguration\"8@\"NSError\"16"
- "@24@0:8r*16"
- "Ignoring proxy match dictionary, not applicable for internal"
- "Ignoring proxy match dictionary, not applicable for public"
- "Internal"
- "Public"
- "PvD JSON content: %@"
- "PvD Request"
- "PvD fetch for proxied content map to %@ received PvD JSON"
- "PvD fetch for proxied content map to %@ received empty response"
- "PvD fetch for proxied content map to %@ received malformed PvD JSON: %@"
- "PvD fetch for proxied content map to %@ received no HTTP metadata"
- "PvD fetch for proxied content map to %@ received no PvD JSON (status %u)"
- "PvD fetch for proxied content map to %@ received no response, error %@"
- "application/pvd+json"
- "createPvDRequestForName:"
- "https://%s/.well-known/pvd"
- "startPvDConnectionForSessionTicketsWithEndpoint:parameters:completionHandler:"
- "v16@?0r*8"
```
