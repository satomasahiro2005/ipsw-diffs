## SMBClientEngine

> `/System/Library/PrivateFrameworks/SMBClientEngine.framework/SMBClientEngine`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2ddc4` | `0x2ddd0` | **`+0xc`** |

### Other Changes

```text
Functions:
~ _smb2_smb_parse_file_stream_info : 1520 -> 1524
~ _smb2_smb_parse_file_all_info : 1412 -> 1432
~ -[SMBNode dealloc] : 232 -> 236
~ -[SMBNode parseNextHeader:retNTStatus:retMdpp:] : 1136 -> 1132
~ -[SMBNode resetCmpdRequest] : 140 -> 144
~ -[SMBNode .cxx_destruct] : 100 -> 108
~ ___piston_session_setup_block_invoke : 2380 -> 2384
~ _piston_ntstatus_to_errno : 264 -> 272
~ _smb_convert_network_to_path : 544 -> 540
~ _smb_convert_from_network : 932 -> 928
~ _smb_convert_path_to_network : 440 -> 436
~ _SMBGetFileSystemRepresentation : 568 -> 572
~ _smb2_smb_create : 3380 -> 3376
~ _piston_hexdump : 492 -> 488
~ _smb2_smb_ioctl : 4308 -> 4304
~ _piston_validate_negotiate : 716 -> 708
~ _piston_gss_parse_server_mechs : 788 -> 784
~ ___piston_negotiate_block_invoke : 1784 -> 1780
```
