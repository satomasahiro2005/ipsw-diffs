## GSS

> `/System/Library/Frameworks/GSS.framework/GSS`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__data` | `—` | `0x1360` | **`+0x1360`** |
| `__DATA_DIRTY.__data` | `0x1360` | `—` | **`-0x1360`** |
| `__TEXT.__text` | `0x27124` | `0x27fd0` | **`+0xeac`** |
| `__TEXT.__cstring` | `0x3abb` | `0x3b55` | **`+0x9a`** |
| `__AUTH_CONST.__auth_got` | `0xf68` | `0xf78` | **`+0x10`** |
| `__TEXT.__const` | `0x43a` | `0x44a` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x730` | `0x738` | **`+0x8`** |

### Other Changes

```diff

-725.0.6.0.0
+725.0.8.0.0

-  Functions: 668
-  Symbols:   1520
-  CStrings:  582
+  Functions: 673
+  Symbols:   1523
+  CStrings:  592
Symbols:
+ __gsskrb5_make_header
+ _krb5_decrypt_ivec
+ _krb5_encrypt_ivec
CStrings:
+ "encdata.length == 8"
+ "get_mic.c"
+ "mic_des3"
+ "tmp.length == datalen"
+ "tmp.length == input_message_buffer->length - len"
+ "unwrap.c"
+ "unwrap_des3"
+ "wrap.c"
+ "wrap_des3"
+ "\xff\xff"
```
