## PolarisBufferService

> `/System/Library/PrivateFrameworks/PolarisBufferService.framework/PolarisBufferService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5d1e4` | `0x5d3f4` | **`+0x210`** |
| `__TEXT.__oslogstring` | `0xa8b2` | `0xa99e` | **`+0xec`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-256.0.2.500.1
+256.0.3.0.0

-  CStrings:  1540
+  CStrings:  1543
Symbols:
+ __Z24handle_allocate_resourceP19resfact_alloc_msg_tjP17PSResourceFactoryPK16ps_caller_info_t
+ __ZN17PSResourceFactory18handle_client_diedEP25resfact_client_died_msg_tPK16ps_caller_info_t
+ __ZN17PSResourceFactory22handle_ringbuffer_infoEP29resfact_ringbuffer_info_msg_tjPK16ps_caller_info_t
+ __ZN17PSResourceFactory28handleResourceFactoryMessageEP17res_factory_msg_tjP21mach_msg_descriptor_tPK16ps_caller_info_t
+ __ZN17PSResourceFactory28validate_client_entitlementsEP25resfact_register_sb_msg_tjPK16ps_caller_info_t
+ __ZN17PSResourceFactory29handle_register_shbuffergroupEP25resfact_register_sb_msg_tjPK16ps_caller_info_t
+ __ZN17PSResourceFactory31handle_unregister_shbuffergroupEP25resfact_register_sb_msg_tjPK16ps_caller_info_t
+ ____ZN17PSResourceFactory28handleResourceFactoryMessageEP17res_factory_msg_tjP21mach_msg_descriptor_tPK16ps_caller_info_t_block_invoke
- __Z24handle_allocate_resourceP19resfact_alloc_msg_tjP17PSResourceFactory
- __ZN17PSResourceFactory18handle_client_diedEP25resfact_client_died_msg_t
- __ZN17PSResourceFactory22handle_ringbuffer_infoEP29resfact_ringbuffer_info_msg_tj
- __ZN17PSResourceFactory28handleResourceFactoryMessageEP17res_factory_msg_tjP21mach_msg_descriptor_ti
- __ZN17PSResourceFactory28validate_client_entitlementsEP25resfact_register_sb_msg_tj13audit_token_t
- __ZN17PSResourceFactory29handle_register_shbuffergroupEP25resfact_register_sb_msg_tj13audit_token_t
- __ZN17PSResourceFactory31handle_unregister_shbuffergroupEP25resfact_register_sb_msg_tj13audit_token_t
- ____ZN17PSResourceFactory28handleResourceFactoryMessageEP17res_factory_msg_tjP21mach_msg_descriptor_ti_block_invoke
CStrings:
+ "%s: Rejected CLIENT_DIED message from unauthorized sender\n"
+ "%s: Rejecting CLIENT_DIED from unauthorized pid=%d (expected polarisd pid=%d)\n"
+ "%s: Rejecting non-zero map_addr from external process (type: %d flags: %x pid: %d map_addr: %lx)\n"
+ "01:16:55"
+ "Jun 27 2026"
- "21:58:35"
- "Jun 16 2026"
```
