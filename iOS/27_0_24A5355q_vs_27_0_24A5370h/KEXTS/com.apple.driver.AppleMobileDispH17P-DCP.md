## com.apple.driver.AppleMobileDispH17P-DCP

> `com.apple.driver.AppleMobileDispH17P-DCP`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__auth_stubs` | `0x0` | `0xe50` | **`+0xe50`** |
| `__TEXT_EXEC.__text` | `0x241d4` | `0x244d0` | **`+0x2fc`** |
| `__TEXT.__cstring` | `0x6a39` | `0x6b10` | **`+0xd7`** |

### Other Changes

```diff

-700.50.66.0.0
-  Functions: 1439
+700.50.72.0.0
+  Functions: 1440

-  CStrings:  559
+  CStrings:  563
CStrings:
+ "%s: Lock acquired in %d itr (fallback)\n"
+ "%s: Swap queue drained before power state change\n"
+ "( \"Lock acquired in %d itr (fallback)\\n\" ) @%s:%d"
+ "( \"Swap queue drain timed out (500ms)\\n\" ) @%s:%d"
+ "Lock acquired in %d itr (fallback)\n"
+ "Swap queue drain timed out (500ms)\n"
+ "Swap queue drained before power state change\n"
- "%s: Lock acquired in %d itr\n"
- "( \"Lock acquired in %d itr\\n\" ) @%s:%d"
- "Lock acquired in %d itr\n"
```
