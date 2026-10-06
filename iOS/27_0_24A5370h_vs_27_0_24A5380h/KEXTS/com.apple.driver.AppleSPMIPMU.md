## com.apple.driver.AppleSPMIPMU

> `com.apple.driver.AppleSPMIPMU`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_CONST.__const` | `0x14f0` | `0x1520` | **`+0x30`** |
| `__TEXT.__cstring` | `0x2bd8` | `0x2be7` | **`+0xf`** |
| `__TEXT_EXEC.__text` | `0xcbf4` | `0xcbec` | **`-0x8`** |

### Other Changes

```diff

-1372.0.0.0.0
+1372.0.1.0.0

-  CStrings:  378
+  CStrings:  381
Functions:
~ __ZN18AppleDialogSPMIPMU23_resetLpemInRestoreModeEv : 364 -> 368
~ __ZN18AppleDialogSPMIPMU21_updateBootPropertiesEb : 2140 -> 2148
~ __ZN18AppleDialogSPMIPMU17_writeLpemLogDataEv : 508 -> 488
CStrings:
+ "%s::handleStart: %s _pmuNub: %p ** configuration not found ** built 20:59:17 Jun 30 2026\n"
+ "%s::handleStart: ro=%d nvram=%d helper=%d %s _pmuNub: %p 0x%04x:0x%04x-0x%04x built 20:59:17 Jun 30 2026\n"
+ "%s::start: %s _pmuNub: %p ** configuration not found ** built 20:59:18 Jun 30 2026\n"
+ "%s::start: %s _pmuNub: %p built 20:59:18 Jun 30 2026\n"
+ "B2CA"
+ "B2PD"
+ "B2VT"
- "%s::handleStart: %s _pmuNub: %p ** configuration not found ** built 19:34:29 Jun 18 2026\n"
- "%s::handleStart: ro=%d nvram=%d helper=%d %s _pmuNub: %p 0x%04x:0x%04x-0x%04x built 19:34:29 Jun 18 2026\n"
- "%s::start: %s _pmuNub: %p ** configuration not found ** built 19:34:30 Jun 18 2026\n"
- "%s::start: %s _pmuNub: %p built 19:34:30 Jun 18 2026\n"
```
