## DoNotDisturbServer

> `/System/Library/PrivateFrameworks/DoNotDisturbServer.framework/DoNotDisturbServer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc2e78` | `0xc2ee4` | **`+0x6c`** |

### Other Changes

```diff

-  Functions: 3950
+  Functions: 3951
Functions:
~ _DNDSRedactSysdiagnose : 88 -> 92
~ -[DNDSSyncEngineMetadataStore recordWithID:].cold.1 : 148 -> 144
~ -[DNDSSyncEngineMetadataStore purge].cold.1 : 64 -> 72
~ -[DNDSSyncEngineMetadataStore _read].cold.1 : 96 -> 92
~ -[DNDSSyncEngineMetadataStore _write].cold.1 : 64 -> 72
+ -[DNDSIDSSyncEngineMetadataStore _read].cold.1
```
