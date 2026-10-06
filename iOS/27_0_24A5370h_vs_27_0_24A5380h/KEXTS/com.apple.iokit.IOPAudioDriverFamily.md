## com.apple.iokit.IOPAudioDriverFamily

> `com.apple.iokit.IOPAudioDriverFamily`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_CONST.__kalloc_var` | `—` | `0x320` | **`+0x320`** |
| `__TEXT.__cstring` | `0x3b50` | `0x3be7` | **`+0x97`** |
| `__TEXT_EXEC.__auth_stubs` | `0x510` | `0x530` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0x288` | `0x298` | **`+0x10`** |
| `__TEXT_EXEC.__text` | `0x13ea4` | `0x13e9c` | **`-0x8`** |

### Other Changes

```diff

-400.11.0.0.0
+400.12.0.0.0

-  CStrings:  319
+  CStrings:  323
Functions:
~ sub_fffffff00a209820 -> sub_fffffff00a209ea0 : 272 -> 280
~ __ZN8IOPAudio16CommandInterface12memoryAccessERKNS_29MemoryAccessCommandDescriptorE : 740 -> 748
~ sub_fffffff00a209c24 -> sub_fffffff00a20a2b4 : 12 -> 16
~ sub_fffffff00a209c40 -> sub_fffffff00a20a2d4 : 16 -> 12
~ sub_fffffff00a209c50 -> sub_fffffff00a20a2e0 : 16 -> 8
~ sub_fffffff00a209d30 -> sub_fffffff00a20a3b8 : 412 -> 392
~ sub_fffffff00a20a0b4 -> sub_fffffff00a20a728 : 396 -> 400
CStrings:
+ "site.Packet.uint8_t"
+ "site.RegisterAccess::Packet.uint8_t"
+ "site.struct GetNodePropertyOutputPacket.uint8_t"
+ "site.struct SetNodePropertyInputPacket.uint8_t"
```
