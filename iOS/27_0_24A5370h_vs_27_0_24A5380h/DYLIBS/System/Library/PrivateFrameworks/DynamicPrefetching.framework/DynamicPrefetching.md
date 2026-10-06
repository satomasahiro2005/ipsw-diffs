## DynamicPrefetching

> `/System/Library/PrivateFrameworks/DynamicPrefetching.framework/DynamicPrefetching`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x17fe4` | `0x18abc` | **`+0xad8`** |
| `__TEXT.__oslogstring` | `0x24ea` | `0x2774` | **`+0x28a`** |
| `__TEXT.__gcc_except_tab` | `0x11f4` | `0x12ec` | **`+0xf8`** |
| `__TEXT.__unwind_info` | `0x830` | `0x868` | **`+0x38`** |
| `__AUTH_CONST.__auth_got` | `0x3c0` | `0x3f0` | **`+0x30`** |
| `__DATA.__bss` | `0x228` | `0x248` | **`+0x20`** |
| `__TEXT.__cstring` | `0x86c` | `0x87e` | **`+0x12`** |
| `__TEXT.__const` | `0x4ae` | `0x4b6` | **`+0x8`** |

### Other Changes

```diff

-3.5.5.0.0
+3.5.8.0.0

-  Functions: 483
-  Symbols:   169
-  CStrings:  256
+  Functions: 492
+  Symbols:   175
+  CStrings:  266
Symbols:
+ __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEaSERKS5_
+ _localtime_r
+ _objc_retain_x21
+ _stat
+ _strftime
+ _utimensat
CStrings:
+ "%Y-%m-%d %H:%M:%S"
+ "end_scenario_internal: first launch after boot for bundleid %@ scenario %s — discarded %zu pageins, refreshed profile mtime"
+ "is_first_launch_after_boot: boot time unavailable, discarding pageins"
+ "mark_profile_seen_this_boot: Caught exception for bundleid %{public}s : %{public}s"
+ "mark_profile_seen_this_boot: Caught unknown exception for bundleid %{public}s"
+ "mark_profile_seen_this_boot: exists() failed for \"%s\": %{public}s"
+ "mark_profile_seen_this_boot: utimensat failed for \"%s\": %{darwin.errno}d"
+ "system_boot_time: boot time %lld.%09lld (epoch s)"
+ "system_boot_time: boot time %{public}s"
+ "system_boot_time: sysctl(KERN_BOOTTIME) failed: %{darwin.errno}d"
```
