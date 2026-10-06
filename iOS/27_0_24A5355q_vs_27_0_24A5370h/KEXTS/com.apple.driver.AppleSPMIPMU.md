## com.apple.driver.AppleSPMIPMU

> `com.apple.driver.AppleSPMIPMU`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__auth_stubs` | `0x0` | `0x4d0` | **`+0x4d0`** |
| `__TEXT_EXEC.__text` | `0xcbe4` | `0xcbf4` | **`+0x10`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-1371.0.0.0.0
+1372.0.0.0.0
Functions:
~ _panic : 256 -> 276
~ __ZN18AppleDialogSPMIPMU30_updateOff2WakeSourceRegistersEv : 1180 -> 1176
CStrings:
+ "%s::handleStart: %s _pmuNub: %p ** configuration not found ** built 19:34:29 Jun 18 2026\n"
+ "%s::handleStart: ro=%d nvram=%d helper=%d %s _pmuNub: %p 0x%04x:0x%04x-0x%04x built 19:34:29 Jun 18 2026\n"
+ "%s::start: %s _pmuNub: %p ** configuration not found ** built 19:34:30 Jun 18 2026\n"
+ "%s::start: %s _pmuNub: %p built 19:34:30 Jun 18 2026\n"
- "%s::handleStart: %s _pmuNub: %p ** configuration not found ** built 22:46:09 May 27 2026\n"
- "%s::handleStart: ro=%d nvram=%d helper=%d %s _pmuNub: %p 0x%04x:0x%04x-0x%04x built 22:46:09 May 27 2026\n"
- "%s::start: %s _pmuNub: %p ** configuration not found ** built 22:46:10 May 27 2026\n"
- "%s::start: %s _pmuNub: %p built 22:46:10 May 27 2026\n"
```
