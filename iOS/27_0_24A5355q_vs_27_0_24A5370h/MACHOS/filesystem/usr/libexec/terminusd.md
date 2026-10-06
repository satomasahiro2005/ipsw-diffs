## terminusd

> `/usr/libexec/terminusd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1f756c` | `0x1f8a04` | **`+0x1498`** |
| `__TEXT.__cstring` | `0x509f1` | `0x50cb9` | **`+0x2c8`** |
| `__TEXT.__objc_methname` | `0x135e5` | `0x136f5` | **`+0x110`** |
| `__TEXT.__oslogstring` | `0x2c8f` | `0x2d7e` | **`+0xef`** |
| `__DATA_CONST.__cfstring` | `0xdac0` | `0xdb80` | **`+0xc0`** |
| `__TEXT.__objc_stubs` | `0x92e0` | `0x93a0` | **`+0xc0`** |
| `__DATA.__objc_const` | `0x19a48` | `0x19ab8` | **`+0x70`** |
| `__TEXT.__swift5_typeref` | `0x478` | `0x4ce` | **`+0x56`** |
| `__DATA_CONST.__const` | `0x4cb8` | `0x4d08` | **`+0x50`** |
| `__DATA.__objc_selrefs` | `0x2ea0` | `0x2ed0` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x5bac` | `0x5bdc` | **`+0x30`** |
| `__TEXT.__auth_stubs` | `0x3e70` | `0x3e90` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0x1f48` | `0x1f58` | **`+0x10`** |
| `__DATA_CONST.__got` | `0xd90` | `0xda0` | **`+0x10`** |
| `__TEXT.__swift5_capture` | `0x450` | `0x460` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x1fa4` | `0x1fb0` | **`+0xc`** |
| `__DATA_CONST.__auth_ptr` | `0x1d0` | `0x1d8` | **`+0x8`** |
| `__TEXT.__eh_frame` | `0xe88` | `0xe90` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x3128` | `0x3130` | **`+0x8`** |
| `__TEXT.__gcc_except_tab` | `0x6200` | `0x61fc` | **`-0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-890.0.0.0.7
+914.0.1.0.4

-  Functions: 3981
-  Symbols:   1525
-  CStrings:  11559
+  Functions: 3992
+  Symbols:   1530
+  CStrings:  11586
Symbols:
+ _$s7Network0A10ConnectionC11forceCancelyyF
+ _$s7Network3TCPV8MetadataVMn
+ _OBJC_CLASS_$_NRMeshIdentifier
+ _malloc_type_realloc
+ _nrXPCKeyUsesMultiplexedASForNWSC
+ _nw_proxy_hop_set_migration_for_non_transport
- _reallocf
CStrings:
+ "%s%.30s:%-4d %@ Updating usesMultiplexedASForNWSC %d to %d"
+ "%s%.30s:%-4d ABORTING: strict_calloc called with count 0"
+ "%s%.30s:%-4d ABORTING: strict_memalign called with size 0"
+ "%s%.30s:%-4d [SD] failed to inject broadcast state from device %@ w/ error %@"
+ "%s%.30s:%-4d [SD] generating payload for device %@"
+ "%s%.30s:%-4d [SD] no device for deviceID %@"
+ "%s%.30s:%-4d [SD] received broadcast state from device %@ (%lu bytes)"
+ "%s%.30s:%-4d [SD] received remote service payload without a request"
+ "%s%.30s:%-4d [SD] received requested payload from device %@"
+ "%s%.30s:%-4d [SD] unable to find current persona"
+ "%s%.30s:%-4d [SD] unable to produce payload for device %@"
+ "%s%.30s:%-4d handling change for usesMultiplexedASQUIC"
+ "%s%.30s:%-4d ignoring endpoint: %@ (interface %@)"
+ "%s%.30s:%-4d ignoring interface %@ of type %u (intf subfamily: %u)"
+ "%{public}s strict_calloc called with count 0"
+ "%{public}s strict_memalign called with size 0"
+ "+[NRDLocalDevice updateUsesMultiplexedASForNWSC:nrUUID:]"
+ "-[NRApplicationServiceManager setupResolverAgent]_block_invoke_11"
+ "-[NRApplicationServiceManager setupResolverAgent]_block_invoke_5"
+ "-[NRApplicationServiceManager setupResolverAgent]_block_invoke_7"
+ "-[NRDDeviceConductor handleUsesMultiplexedASQUICChanged]"
+ "-[NRLinkWired copyNotifyPayloadsToSendWithProxy:sendingClassC:]"
+ "19:49:34"
+ "914.0.1.0.4"
+ "Failed to receive data over Wi-Fi Aware session connection: %@"
+ "Jun 18 2026"
+ "NRBabelSubTLVAppleLinkType[%u]"
+ "NRBabelTLVName[\"%@\"]"
+ "Received data over Wi-Fi Aware session connection: this should not happen."
+ "Received empty data over the Wi-Fi Aware session connection, the connection has been closed by the other side."
+ "TB,N,V_sentInitialSDBroadcastState"
+ "_latestBroadcastState"
+ "_sentInitialSDBroadcastState"
+ "_serviceConnectorPolicyIdentifier"
+ "initWithIdentifier:"
+ "queryEphemeralLocalPKBootstrappingRecords:"
+ "sentInitialSDBroadcastState"
+ "service-connector"
+ "service-connector.asquic"
+ "service-connector.asquic.muxed"
+ "service-connector.tcp"
+ "setMeshIdentifier:"
+ "setRoomDistributorFeatureEnabled:"
+ "setSentInitialSDBroadcastState:"
+ "usesMultiplexedASForNWSC"
- "%s%.30s:%-4d ABORTING: strict_calloc called with size 0"
- "%s%.30s:%-4d failed to inject broadcast state from device %@ w/ error %@"
- "%s%.30s:%-4d ignoring interface %@ of type %u"
- "%s%.30s:%-4d no device for deviceID %@"
- "%s%.30s:%-4d received broadcast state from device %@ (%lu bytes)"
- "%s%.30s:%-4d received remote service payload without a request"
- "%s%.30s:%-4d unable to find current persona"
- "%s%.30s:%-4d unable to produce payload for device %@"
- "%{public}s strict_calloc called with size 0"
- "-[NRApplicationServiceManager setupResolverAgent]_block_invoke_3"
- "-[NRApplicationServiceManager setupResolverAgent]_block_invoke_6"
- "-[NRApplicationServiceManager setupResolverAgent]_block_invoke_8"
- "21:14:17"
- "890.0.0.0.7"
- "Jun  3 2026"
- "Received data over Wi-Fi Aware."
- "queryLocalPKBootstrappingRecords:"
- "receive task has been cancelled"
```
