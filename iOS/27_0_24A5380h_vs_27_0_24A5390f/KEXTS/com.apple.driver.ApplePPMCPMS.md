## com.apple.driver.ApplePPMCPMS

> `com.apple.driver.ApplePPMCPMS`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x52f7c` | `0x5326c` | **`+0x2f0`** |
| `__TEXT.__os_log` | `0x3e3d` | `0x3eb3` | **`+0x76`** |
| `__TEXT.__cstring` | `0xf84a` | `0xf888` | **`+0x3e`** |
| `__DATA_CONST.__const` | `0x5af0` | `0x5b00` | **`+0x10`** |

### Other Changes

```diff

-1191.0.16.0.0
-  Functions: 2168
+1191.0.27.0.0
+  Functions: 2170

-  CStrings:  1855
+  CStrings:  1858
CStrings:
+ "%s::%s:Error: PPMInterfaceAPICallBack failed with 0x%08x\n\n"
+ "ApplePPMInterfaceAPIFunction"
+ "SystemCapability%s_Battery%d"
+ "virtual IOReturn ApplePPMCPMS::PPMInterfaceAPICallBack(OSObject *, OSDictionary *, OSDictionary **)"
- "virtual void ApplePPMCPMS::PPMInterfaceAPICallBack(OSObject *, OSDictionary *, OSDictionary **)"
```
