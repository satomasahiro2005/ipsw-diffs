## com.apple.driver.AppleProcessorTrace

> `com.apple.driver.AppleProcessorTrace`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x33bcc` | `0x3c314` | **`+0x8748`** |
| `__DATA_CONST.__const` | `0x9d90` | `0xb188` | **`+0x13f8`** |
| `__TEXT.__cstring` | `0x548e` | `0x5981` | **`+0x4f3`** |
| `__DATA_CONST.__kalloc_type` | `0x680` | `0x740` | **`+0xc0`** |
| `__DATA.__common` | `0x6e8` | `0x760` | **`+0x78`** |
| `__DATA_CONST.__mod_init_func` | `0xd0` | `0xe8` | **`+0x18`** |
| `__DATA_CONST.__mod_term_func` | `0xd0` | `0xe8` | **`+0x18`** |

### Other Changes

```diff

-  Functions: 1185
+  Functions: 1314

-  CStrings:  500
+  CStrings:  519
CStrings:
+ "121111121222121211111112112211211211211211211211211211211211"
+ "AppleProcessorTraceT8152"
+ "AppleProcessorTraceT8160"
+ "AppleProcessorTraceT8320"
+ "site.AppleProcessorTraceT8152"
+ "site.AppleProcessorTraceT8160"
+ "site.AppleProcessorTraceT8320"
+ "uint64_t AppleProcessorTraceT8152::apt_msr_ro_ctl_read(ml_topology_cpu_t, uint8_t)"
+ "uint64_t AppleProcessorTraceT8160::apt_msr_ro_ctl_read(ml_topology_cpu_t, uint8_t)"
+ "uint64_t AppleProcessorTraceT8320::apt_msr_ro_ctl_read(ml_topology_cpu_t, uint8_t)"
+ "virtual AppleProcessorTrace::ClusterChunkInfo AppleProcessorTraceT8152::getChunkForCluster(unsigned int, uint64_t)"
+ "virtual AppleProcessorTrace::ClusterChunkInfo AppleProcessorTraceT8160::getChunkForCluster(unsigned int, uint64_t)"
+ "virtual AppleProcessorTrace::ClusterChunkInfo AppleProcessorTraceT8320::getChunkForCluster(unsigned int, uint64_t)"
+ "virtual void AppleProcessorTraceT8152::defeatureCore(bool)"
+ "virtual void AppleProcessorTraceT8160::defeatureCore(bool)"
+ "virtual void AppleProcessorTraceT8320::defeatureCore(bool)"
+ "void AppleProcessorTraceT8152::apt_msr_ro_ctl_write(ml_topology_cpu_t, uint8_t, uint64_t)"
+ "void AppleProcessorTraceT8160::apt_msr_ro_ctl_write(ml_topology_cpu_t, uint8_t, uint64_t)"
+ "void AppleProcessorTraceT8320::apt_msr_ro_ctl_write(ml_topology_cpu_t, uint8_t, uint64_t)"
```
