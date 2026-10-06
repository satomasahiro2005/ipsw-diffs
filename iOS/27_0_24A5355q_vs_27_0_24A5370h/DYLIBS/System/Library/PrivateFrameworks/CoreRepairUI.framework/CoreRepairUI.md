## CoreRepairUI

> `/System/Library/PrivateFrameworks/CoreRepairUI.framework/CoreRepairUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x2f67` | `0x301d` | **`+0xb6`** |
| `__TEXT.__text` | `0x19720` | `0x197a4` | **`+0x84`** |
| `__AUTH_CONST.__cfstring` | `0x39e0` | `0x3a20` | **`+0x40`** |
| `__TEXT.__gcc_except_tab` | `0x3c0` | `0x3d0` | **`+0x10`** |
| `__TEXT.__const` | `0xb8` | `0xb0` | **`-0x8`** |

### Other Changes

```diff

-1291.0.0.502.1
+1307.0.16.0.0

-  CStrings:  602
+  CStrings:  604
Functions:
~ sub_256967034 -> sub_257d06034 : 1896 -> 2252
~ sub_25696779c -> sub_257d06900 : 2360 -> 2184
~ sub_25696e1dc -> sub_257d0d290 : 916 -> 908
~ sub_25696e608 -> sub_257d0d6b4 : 696 -> 692
~ sub_25696e8d4 -> sub_257d0d97c : 2188 -> 2168
~ sub_256978108 -> sub_257d1719c : 296 -> 292
~ sub_256978800 -> sub_257d17890 : 364 -> 360
~ sub_2569794b0 -> sub_257d1853c : 668 -> 660
CStrings:
+ "[%s] First time pending repair. Posting lock-screen notification."
+ "[%s] Sealed SN changed"
+ "[%s] Sealed SN changed. Posting lock-screen notification."
+ "[%s] Sealed SN unchanged. Continuing existing timer."
+ "[%s] Sealed SN unchanged. Silently updating UI to Finish Repair."
+ "[%s] Throttling Finish Repair reminder. Scheduling unlock checker activity for %f seconds"
+ "[%s] reminder threshold met (interval: %lld), posting lock screen notification"
- "[%s] Unknown Part SN differs from Finish Repair SN"
- "[%s] Upgrade to Finish Repair from Unknown Part"
- "[%s] component has displayed follow up"
- "[%s] component has not displayed finish repair"
- "[%s] scheduling finish repair unlock checker activity Interval:%f "
```
