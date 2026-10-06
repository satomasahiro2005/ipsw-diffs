## SiriAudioSupport

> `/System/Library/PrivateFrameworks/SiriAudioSupport.framework/SiriAudioSupport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x233314` | `0x233194` | **`-0x180`** |
| `__TEXT.__oslogstring` | `0x231ee` | `0x231ce` | **`-0x20`** |
| `__TEXT.__const` | `0xd248` | `0xd258` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x4938` | `0x4930` | **`-0x8`** |

### Other Changes

```diff

-3605.20.1.0.0
+3605.21.1.0.0
Functions:
~ sub_2ac2e7e60 -> sub_2ac625e60 : 240 -> 44
~ sub_2ac2e7f50 -> sub_2ac625e8c : 796 -> 340
~ sub_2ac2e826c -> sub_2ac625fe0 : 44 -> 240
~ sub_2ac2e8298 -> sub_2ac6260d0 : 340 -> 796
~ sub_2ac3ec3c4 -> sub_2ac72a3c4 : 508 -> 516
~ sub_2ac3ec7fc -> sub_2ac72a804 : 1316 -> 1332
~ sub_2ac3edfc8 -> sub_2ac72bfe0 : 1380 -> 1388
~ sub_2ac463eb8 -> sub_2ac7a1ed8 : 4096 -> 3680
CStrings:
+ "PlaybackHelpers#resolver using x scheme, itemURLs: %{public}s"
- "PlaybackHelpers#resolver using x scheme, url: %{public}s, container url: %{public}s"
```
