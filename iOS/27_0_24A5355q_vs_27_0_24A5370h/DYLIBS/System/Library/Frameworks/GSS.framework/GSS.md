## GSS

> `/System/Library/Frameworks/GSS.framework/GSS`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x27f1c` | `0x27124` | **`-0xdf8`** |
| `__TEXT.__cstring` | `0x3b55` | `0x3abb` | **`-0x9a`** |
| `__AUTH_CONST.__auth_got` | `0xf78` | `0xf68` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x728` | `0x730` | **`+0x8`** |

### Other Changes

```diff

-720.0.0.0.0
+725.0.6.0.0

-  Functions: 673
-  Symbols:   1523
-  CStrings:  592
+  Functions: 668
+  Symbols:   1520
+  CStrings:  582
Symbols:
- __gsskrb5_make_header
- _krb5_decrypt_ivec
- _krb5_encrypt_ivec
CStrings:
- "encdata.length == 8"
- "get_mic.c"
- "mic_des3"
- "tmp.length == datalen"
- "tmp.length == input_message_buffer->length - len"
- "unwrap.c"
- "unwrap_des3"
- "wrap.c"
- "wrap_des3"
- "\xff\xff"
```
