## com.apple.iokit.IOGPUFamily

> `com.apple.iokit.IOGPUFamily`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x42488` | `0x42670` | **`+0x1e8`** |
| `__TEXT.__os_log` | `0x5267` | `0x52f6` | **`+0x8f`** |

### Other Changes

```diff

-162.10.0.0.0
-  Functions: 2001
+162.11.0.0.0
+  Functions: 2002

-  CStrings:  919
+  CStrings:  921
CStrings:
+ "%s: child resource (offset=0x%llx, size=0x%llx) exceeds parent memory size 0x%llx.\n"
+ "%s: client_buffer (0x%llx) precedes client_base (0x%llx).\n"
```
