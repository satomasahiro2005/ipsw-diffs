## com.apple.driver.AppleH16ANEInterface

> `com.apple.driver.AppleH16ANEInterface`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x1476a8` | `0x149aa4` | **`+0x23fc`** |
| `__TEXT.__os_log` | `0x3ac29` | `0x3ace0` | **`+0xb7`** |
| `__DATA_CONST.__const` | `0xf950` | `0xf990` | **`+0x40`** |
| `__TEXT_EXEC.__auth_stubs` | `0x1250` | `0x1270` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0x928` | `0x938` | **`+0x10`** |
| `__TEXT.__const` | `0x1030` | `0x1020` | **`-0x10`** |
| `__DATA.__common` | `0x7b0` | `0x7b8` | **`+0x8`** |
| `__TEXT.__cstring` | `0x11588` | `0x1158a` | **`+0x2`** |

### Other Changes

```diff

-10.15.4.0.0
-  Functions: 4916
+10.16.2.0.0
+  Functions: 4921

-  CStrings:  5201
+  CStrings:  5203
CStrings:
+ "%s: %s:   surface=%p uuid=0x%llx mode=%u\n"
+ "%s: %s: Client program size : %llu maxMapSize: %llu minMapSize %llu\n"
+ "%s: %s: Disabling acc power rail (refcount 1 -> 0)\n"
+ "%s: %s: Enabling acc power rail (refcount 0 -> 1)\n"
+ "%s: %s: evaluateLocalFence: trylock failed for dep 0x%llx, request 0x%llx — falling back to LocalStrict\n"
+ "/.resolve/2%.*s"
+ "[ERROR] %s: %s: Ignoring stale firmware ack for un-sent command at ANE address 0x%llx (sentToFW=false)\n"
- "%s: %s:   surface=%p uuid=0x%llx\n"
- "%s: %s: Client program size : %llu maxMapSize: %u minMapSize %u\n"
- "/.resolve/2%s"
- "[ERROR] %s: %s: Failed to allocate anecMutableWeightFileData for %u entries\n"
- "[ERROR] %s: %s: Failed to allocate symbol storage for %u entries\n"
```
