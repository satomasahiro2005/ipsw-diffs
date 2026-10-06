## com.apple.kernel

> `com.apple.kernel`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x8f03e4` | `0x8f1334` | **`+0xf50`** |
| `__TEXT.__os_log` | `0x41edb` | `0x41fdc` | **`+0x101`** |
| `__TEXT.__cstring` | `0x8f0fb` | `0x8f16f` | **`+0x74`** |
| `__LINKINFO.__symbolsets` | `0x48d7b` | `0x48de8` | **`+0x6d`** |
| `__DATA_CONST.__const` | `0xb8208` | `0xb81e0` | **`-0x28`** |
| `__BOOTDATA.__init_entry_set` | `0x143b8` | `0x143a0` | **`-0x18`** |
| `__DATA.__bss` | `0xa5298` | `0xa52b0` | **`+0x18`** |
| `__DATA_CONST.__assert` | `0x1194` | `0x11a8` | **`+0x14`** |
| `__TEXT.__const` | `0x37010` | `0x37020` | **`+0x10`** |

### Other Changes

```diff

-13432.40.162.0.0
-  Functions: 21941
+13432.40.177.0.3
+  Functions: 21949

-  CStrings:  21248
+  CStrings:  21256
CStrings:
+ "11111122"
+ "22111220222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222220222121222221111111222211111112222211111122222111111222221111112222211222211122211112111111111111"
+ "FilterDropBadDirection"
+ "SK[%u]: %-30s dropped packet injected on ring %u whose wrap flag does not match the ring direction: pkt_pflags 0x%llx\n"
+ "SK[%u]: %-30s filter packet is not mbuf-wrapped: pkt_pflags 0x%llx\n"
+ "SK[%u]: %-30s filter packet is not packet-wrapped: pkt_pflags 0x%llx\n"
+ "com.apple.private.vfs.unmunged-access-time"
+ "com.apple.security.cs.debugger"
+ "nx_netif_filter_pkt_to_mbuf"
+ "nx_netif_filter_pkt_to_pkt"
+ "ret == TB_ERROR_SUCCESS"
- "221112202222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222121222221111111222211111112222211111122222111111222221111112222211222211122211112111111111111"
- "protect_privileged_from_untrusted"
- "vm_protect_privileged_from_untrusted"
```
