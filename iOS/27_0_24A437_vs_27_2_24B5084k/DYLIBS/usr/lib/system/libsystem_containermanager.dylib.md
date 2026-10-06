## libsystem_containermanager.dylib

> `/usr/lib/system/libsystem_containermanager.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x300b8` | `0x30d74` | **`+0xcbc`** |
| `__TEXT.__oslogstring` | `0x59cf` | `0x5ca9` | **`+0x2da`** |
| `__TEXT.__cstring` | `0x3c49` | `0x3d98` | **`+0x14f`** |
| `__DATA_CONST.__const` | `0x1d08` | `0x1d50` | **`+0x48`** |
| `__TEXT.__const` | `0x434` | `0x424` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x708` | `0x718` | **`+0x10`** |

### Other Changes

```diff

-833.0.8.0.1
+833.40.14.0.0

-  Functions: 626
-  Symbols:   1009
-  CStrings:  905
+  Functions: 632
+  Symbols:   1017
+  CStrings:  926
Symbols:
+ ___container_operation_copy_superseded_block_invoke
+ __container_serialize_copy_deserialized_reference
+ _container_frozenset_get_instance_uuid_of_container_at_index
+ _container_get_instance_uuid
+ _container_object_get_instance_uuid
+ _container_object_set_instance_uuid
+ _container_operation_copy_superseded
+ _container_query_set_instance_uuid
+ _mbr_uid_to_uuid
+ _uuid_clear
- __container_serialize_copy_deserialized_reference_v1
- __container_serialize_copy_deserialized_reference_v2
CStrings:
+ "%s: SPI MISUSE: predecessor required but not valid"
+ "%s: SPI MISUSE: successor provided but not valid"
+ "*"
+ ":"
+ "<none: resuming>"
+ "@(#)VERSION:Container Manager: Sep  4 2026 00:50:22; MobileContainerManager_system-833.40.14~50/arm64e"
+ "CmCo:3:%llu:%u:%s:%s:%s:%s:%s:%u:%u:%s:%s"
+ "ContainerMetadataInstanceUUID"
+ "Failed to convert uid to uuid for required instance uuid; uid = %u, errno = %{darwin.errno}d"
+ "IDENTITY_ALREADY_SUPERSEDED"
+ "INSTANCE_UUID_MISMATCH"
+ "InstanceUUID"
+ "MCMMetadataInstanceUUID"
+ "Metadata plist [%{private}s] has a corrupt instance UUID [🔒%{private}s]."
+ "No usable container in reply during %s"
+ "Query; euid = %u, uid = %u, class = %llu%s, identifier = [%s](%zu), gidentifier = [%s](%zu), instance = 🔒%{private}s, uuid = 🔒%{private}s, flags = %llx"
+ "Query; personaid = %u, type = %{public}s, name = %{public}s, origin [pid = %d, personaid = %u], proximate [pid = %d, personaid = %u], euid = %u, uid = %u, class = %llu%s, identifier = [%s](%zu), gidentifier = [%s](%zu), persona = 🔒%{private}s, instance = 🔒%{private}s, uuid = 🔒%{private}s, flags = %llx"
+ "STALE_FS_NODE"
+ "STALE_XATTR"
+ "Set data protection; personaid = %u, type = %{public}s, name = %{public}s, origin [pid = %d, personaid = %u], proximate [pid = %d, personaid = %u], euid = %u, uid = %u, dpclass = %d, container = 🔒%{private}s, flags = %llx"
+ "SuccessorContainer"
+ "Supersede container; personaid = %u, type = %{public}s, name = %{public}s, origin [pid = %d, personaid = %u], proximate [pid = %d, personaid = %u], euid = %u, uid = %u, successor = 🔒%{private}s, predecessor = 🔒%{private}s, flags = %llx"
+ "[%s%s:%s:%u:%s:(%s%s%s):%s%s%s]%s"
+ "container_get_instance_uuid"
+ "container_operation_copy_superseded"
+ "container_operation_copy_superseded_block_invoke"
+ "container_query_set_instance_uuid"
- "@(#)VERSION:Container Manager: Aug  8 2026 13:52:04; MobileContainerManager_system-833.0.8.0.1~205/arm64e"
- "CmCo:2:%llu:%u:%s:%s:%s:%s:%s:%u:%u:%s"
- "Query; euid = %u, uid = %u, class = %llu%s, identifier = [%s](%zu), gidentifier = [%s](%zu), flags = %llx"
- "Query; personaid = %u, type = %{public}s, name = %{public}s, origin [pid = %d, personaid = %u], proximate [pid = %d, personaid = %u], euid = %u, uid = %u, class = %llu%s, identifier = [%s](%zu), gidentifier = [%s](%zu), flags = %llx"
- "Set data protection; personaid = %u, type = %{public}s, name = %{public}s, origin [pid = %d, personaid = %u], proximate [pid = %d, personaid = %u], euid = %u, uid = %u, dpclass = %d, container = %s, flags = %llx"
- "[%s%s:%s:%u:%s:(%s%s%s):%s]%s"
```
