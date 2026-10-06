## ReplicatorEngine

> `/System/Library/PrivateFrameworks/ReplicatorEngine.framework/ReplicatorEngine`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA.__bss` | `0x10920` | `0x10c20` | **`+0x300`** |
| `__TEXT.__text` | `0x1b1a34` | `0x1b1b5c` | **`+0x128`** |
| `__TEXT.__const` | `0xbb18` | `0xbbf8` | **`+0xe0`** |
| `__TEXT.__oslogstring` | `0x7eed` | `0x7f3d` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x4458` | `0x44a0` | **`+0x48`** |
| `__DATA.__data` | `0x2b48` | `0x2b68` | **`+0x20`** |
| `__TEXT.__swift5_proto` | `0x958` | `0x970` | **`+0x18`** |
| `__TEXT.__eh_frame` | `0x53bc` | `0x53cc` | **`+0x10`** |

### Other Changes

```diff

-172.0.0.0.0
+173.0.0.0.0

-  Functions: 6811
+  Functions: 6824
Symbols:
+ ___swift_closure_destructor.588Tm
+ ___swift_closure_destructor.632Tm
+ ___swift_closure_destructor.638Tm
+ ___swift_closure_destructor.745Tm
- ___swift_closure_destructor.587Tm
- ___swift_closure_destructor.631Tm
- ___swift_closure_destructor.637Tm
- ___swift_closure_destructor.744Tm
CStrings:
+ "(%{public}s) Discarding data for inactive relationship: %{public}s"
+ "(%{public}s) Received handshake complete: %{public}s"
+ "(%{public}s) Received handshake request: %{public}s"
+ "(%{public}s) Received handshake response: %{public}s"
+ "(%{public}s) Unpairing inactive relationship: %{public}s"
+ "Discarding metadata for %{public}ld orphaned relationships"
- "(%{public}s) Discarding data for inactive relationship: %s"
- "(%{public}s) Received handshake complete %s"
- "(%{public}s) Received handshake request: %s"
- "(%{public}s) Received handshake response: %s"
- "(%{public}s) Unpairing inactive relationship: %s"
- "Discarding %{public}ld orphaned records"
```
