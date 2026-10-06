## MessageSecurity

> `/System/Library/PrivateFrameworks/MessageSecurity.framework/MessageSecurity`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4c4dc` | `0x4d1a0` | **`+0xcc4`** |
| `__TEXT.__oslogstring` | `0xebc` | `0x100c` | **`+0x150`** |
| `__TEXT.__const` | `0x14a4` | `0x14b4` | **`+0x10`** |

### Other Changes

```diff

-341.40.8.0.0
+341.40.12.0.0

-  CStrings:  608
+  CStrings:  613
CStrings:
+ "Invalid AES-GCM nonce length %ld, expected 12 to 16 octets"
+ "Invalid AES-GCM tag length %ld, RFC 5084 requires 12 to 16 octets"
+ "Invalid data - AES-GCM algorithm identifier carries no parameters"
+ "Invalid data - aes-ICVlen is negative or too large"
+ "aes-ICVlen %ld does not match mac length %ld"
```
