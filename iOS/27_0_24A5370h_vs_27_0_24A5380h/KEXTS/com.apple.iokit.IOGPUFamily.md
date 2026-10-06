## com.apple.iokit.IOGPUFamily

> `com.apple.iokit.IOGPUFamily`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x421a0` | `0x424b8` | **`+0x318`** |
| `__TEXT.__os_log` | `0x521d` | `0x5267` | **`+0x4a`** |
| `__TEXT.__cstring` | `0x616e` | `0x61b3` | **`+0x45`** |

### Other Changes

```diff

-162.6.0.0.0
-  Functions: 1997
+162.9.0.0.0
+  Functions: 2001

-  CStrings:  915
+  CStrings:  919
CStrings:
+ "%s: resource does not own its backing (resType=0x%x child=%u device_cache=%s)\n"
+ "%s: resource does not own its backing (resType=0x%x)\n"
+ "IOGPUSysMemory *IOGPUResource::owns_replaceable_backing() const"
+ "IOReturn IOGPUSysMemory::replace_backing_bytes_locked(task_t, mach_vm_address_t, uint64_t)"
+ "IOReturn IOGPUSysMemory::replace_backing_ranges_locked(task_t, IOAddressRange *, uint32_t, bool)"
+ "NO"
+ "YES"
- "Attempting to detach memory for invalid resource type: %u\n"
- "virtual IOReturn IOGPUSysMemory::replace_backing_bytes(task_t, mach_vm_address_t, uint64_t)"
- "virtual IOReturn IOGPUSysMemory::replace_backing_ranges(task_t, IOAddressRange *, uint32_t, bool)"
```
