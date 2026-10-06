## HomeUICommon

> `/System/Library/PrivateFrameworks/HomeUICommon.framework/HomeUICommon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x34a34` | `0x34b64` | **`+0x130`** |
| `__AUTH_CONST.__auth_got` | `0xf80` | `0xf88` | **`+0x8`** |

### Same-size Content Changes

- `__TEXT.__oslogstring`

### Other Changes

```diff

-1232.3.0.0.0
+1238.0.0.0.0
Functions:
~ sub_214106dac -> sub_214d18dac : 2060 -> 2364
CStrings:
+ "nameAndIcon hit accessory-level fallback for accessory %{public}s; accessory has no resolvable HMService or StaticEndpoint"
- "nameAndIcon hit accessory-level fallback for accessory %{public}s; accessory has no resolvable HMService or StaticMatterDevice"
```
