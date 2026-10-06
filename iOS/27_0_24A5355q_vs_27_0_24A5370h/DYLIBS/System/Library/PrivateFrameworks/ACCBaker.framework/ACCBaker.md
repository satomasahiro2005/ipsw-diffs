## ACCBaker

> `/System/Library/PrivateFrameworks/ACCBaker.framework/ACCBaker`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x39ae0` | `0x350c4` | **`-0x4a1c`** |
| `__TEXT.__gcc_except_tab` | `0x2d98` | `0x2a04` | **`-0x394`** |
| `__TEXT.__const` | `0x22818` | `0x22728` | **`-0xf0`** |
| `__TEXT.__unwind_info` | `0xd30` | `0xd08` | **`-0x28`** |
| `__AUTH_CONST.__auth_got` | `0x390` | `0x398` | **`+0x8`** |
| `__AUTH_CONST.__const` | `0xb70` | `0xb78` | **`+0x8`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-2.4.0.0.0
+2.5.0.0.0

-  Functions: 421
-  Symbols:   173
+  Functions: 414
+  Symbols:   175
Symbols:
+ __ZNKSt3__119__shared_weak_count13__get_deleterERKSt9type_info
+ _malloc_type_aligned_alloc
+ _snprintf
- _malloc_type_posix_memalign
CStrings:
+ "\n"
+ " : %.*s"
+ "%s: %s:%d"
+ "std::aligned_alloc failed to allocate "
- " (ENOMEM)"
- " : "
- ": error code "
- "posix_memalign failed to allocate "
```
