## libsystem_platform.dylib

> `/usr/lib/system/libsystem_platform.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7144` | `0x7040` | **`-0x104`** |

### Other Changes

```diff

-401.0.0.0.0
+402.0.0.0.0
Functions:
~ __platform_strncpy : 1192 -> 1080
~ __platform_memmove : 720 -> 736
~ __platform_strcpy : 592 -> 560
~ __platform_strlcpy : 1144 -> 1136
~ __os_unfair_lock_unlock_slow : 196 -> 172
~ ___os_security_config_init : 372 -> 368
~ __platform_strstr : 136 -> 140
~ __simple_asl_msg_set : 324 -> 332
~ _hex : 312 -> 308
~ _ydec : 288 -> 280
~ _OUTLINED_FUNCTION_3 : 28 -> 32
~ _OUTLINED_FUNCTION_4 : 16 -> 12
~ _OUTLINED_FUNCTION_7 : 36 -> 32
~ ___sme_memchr : 272 -> 296
~ ___sme_memcpy : 240 -> 248
~ __platform_memccpy : 1200 -> 1080
~ __simple_sappend : 100 -> 116
~ _put_c : 148 -> 152
~ ___simple_bprintf.cold.1 : 1060 -> 1040
~ _hex.cold.2 : 68 -> 64
```
