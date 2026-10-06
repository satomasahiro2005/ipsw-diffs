## libspindump.dylib

> `/usr/lib/libspindump.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__oslogstring` | `0xd3e` | `0xde2` | **`+0xa4`** |
| `__TEXT.__text` | `0x39e0` | `0x3a4c` | **`+0x6c`** |
| `__TEXT.__cstring` | `0x4da` | `0x524` | **`+0x4a`** |
| `__DATA.__bss` | `0xf8` | `0x108` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x268` | `0x270` | **`+0x8`** |

### Other Changes

```diff

-453.0.0.0.0
+453.1.0.0.0

-  Symbols:   180
-  CStrings:  121
+  Symbols:   183
+  CStrings:  123
Symbols:
+ _gActionCountSinceLastSignpost
+ _gHIDEventCountSinceLastSignpost
+ _objc_release_x27
Functions:
~ _SPCheckHIDResponseTime2 : 2588 -> 2696
CStrings:
+ "%{public, signpost.description:begin_time}llu %{public, signpost.description:end_time}llu hidEventCountSinceLastSignpost=%{public,name=hidEventCountSinceLastSignpost}llu userActionCountSinceLastSignpost=%{public,name=userActionCountSinceLastSignpost}llu"
+ "hid_event_count_since_last_signpost"
+ "user_action_count_since_last_signpost"
- "%{public, signpost.description:begin_time}llu %{public, signpost.description:end_time}llu"
```
