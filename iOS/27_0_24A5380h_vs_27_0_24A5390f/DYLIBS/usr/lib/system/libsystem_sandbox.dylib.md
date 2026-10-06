## libsystem_sandbox.dylib

> `/usr/lib/system/libsystem_sandbox.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x84c` | `0xb68` | **`+0x31c`** |
| `__TEXT.__text` | `0x3b58` | `0x3ce4` | **`+0x18c`** |
| `__TEXT.__unwind_info` | `0x1d0` | `0x1d8` | **`+0x8`** |

### Other Changes

```diff

-3051.0.30.0.0
+3051.0.42.0.2

-  CStrings:  75
+  CStrings:  95
Functions:
~ _sandbox_extension_issue_file : 28 -> 36
~ _sandbox_extension_issue_file_to_process : 28 -> 36
~ __sandbox_extension_issue : 228 -> 292
~ _sandbox_extension_issue_generic : 24 -> 32
~ _sandbox_extension_issue_mach_to_process : 28 -> 36
~ _sandbox_extension_consume : 124 -> 180
~ _sandbox_extension_issue_generic_to_process : 24 -> 32
~ _sandbox_extension_issue_file_to_self : 96 -> 104
~ _sandbox_extension_issue_file_to_process_by_pid : 32 -> 40
~ _sandbox_extension_issue_mach : 28 -> 36
~ _sandbox_extension_issue_mach_to_process_by_pid : 32 -> 40
~ _sandbox_extension_issue_iokit_registry_entry_class : 28 -> 36
~ _sandbox_extension_issue_iokit_registry_entry_class_to_process : 28 -> 36
~ _sandbox_extension_issue_iokit_registry_entry_class_to_process_by_pid : 32 -> 40
~ _sandbox_extension_issue_generic_to_process_by_pid : 28 -> 36
~ _sandbox_extension_update_file : 56 -> 128
~ _sandbox_extension_update_file_by_fileid : 60 -> 152
~ _sandbox_extension_issue_related_file_to_process : 408 -> 416
CStrings:
+ "%s failed for %s: %d (%s)"
+ "%s failed for %x/%llu: %d (%s)"
+ "%s failed: %d (%s)"
+ "sandbox_extension_consume"
+ "sandbox_extension_issue_file"
+ "sandbox_extension_issue_file_to_process"
+ "sandbox_extension_issue_file_to_process_by_pid"
+ "sandbox_extension_issue_file_to_self"
+ "sandbox_extension_issue_generic"
+ "sandbox_extension_issue_generic_to_process"
+ "sandbox_extension_issue_generic_to_process_by_pid"
+ "sandbox_extension_issue_iokit_registry_entry_class"
+ "sandbox_extension_issue_iokit_registry_entry_class_to_process"
+ "sandbox_extension_issue_iokit_registry_entry_class_to_process_by_pid"
+ "sandbox_extension_issue_mach"
+ "sandbox_extension_issue_mach_to_process"
+ "sandbox_extension_issue_mach_to_process_by_pid"
+ "sandbox_extension_issue_related_file_to_process"
+ "sandbox_extension_update_file"
+ "sandbox_extension_update_file_by_fileid"
```
