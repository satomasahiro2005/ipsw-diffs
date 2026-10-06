## BulletinBoard

> `/System/Library/PrivateFrameworks/BulletinBoard.framework/BulletinBoard`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7dfc4` | `0x7e13c` | **`+0x178`** |
| `__AUTH.__objc_data` | `0x50` | `—` | **`-0x50`** |
| `__DATA_DIRTY.__objc_data` | `0x18b0` | `0x1900` | **`+0x50`** |
| `__TEXT.__oslogstring` | `0x68a6` | `0x68c9` | **`+0x23`** |
| `__DATA.__bss` | `0xa8` | `0x88` | **`-0x20`** |
| `__DATA_DIRTY.__bss` | `0x1a8` | `0x1c8` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x40f0` | `0x40f8` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x87dc` | `0x87e4` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x2128` | `0x2130` | **`+0x8`** |

### Other Changes

```diff

-955.2.1.0.0
+955.2.2.0.0

-  Functions: 3415
-  Symbols:   5261
+  Functions: 3416
+  Symbols:   5262
Symbols:
+ -[BBSectionInfo _applyDestinationCapabilities:]
+ -[BBServer _copySectionSettingsFromSectionID:toSectionID:destinationCapabilities:]
+ -[BBServer copySectionSettingsFromSectionID:toSectionID:destinationCapabilities:withHandler:]
+ -[BBSettingsGateway copySectionSettingsFromSectionID:toSectionID:destinationCapabilities:withCompletion:]
+ ___105-[BBSettingsGateway copySectionSettingsFromSectionID:toSectionID:destinationCapabilities:withCompletion:]_block_invoke
+ ___105-[BBSettingsGateway copySectionSettingsFromSectionID:toSectionID:destinationCapabilities:withCompletion:]_block_invoke_2
+ ___93-[BBServer copySectionSettingsFromSectionID:toSectionID:destinationCapabilities:withHandler:]_block_invoke
- -[BBServer _copySectionSettingsFromSectionID:toSectionID:]
- -[BBServer copySectionSettingsFromSectionID:toSectionID:withHandler:]
- -[BBSettingsGateway copySectionSettingsFromSectionID:toSectionID:withCompletion:]
- ___69-[BBServer copySectionSettingsFromSectionID:toSectionID:withHandler:]_block_invoke
- ___81-[BBSettingsGateway copySectionSettingsFromSectionID:toSectionID:withCompletion:]_block_invoke
- ___81-[BBSettingsGateway copySectionSettingsFromSectionID:toSectionID:withCompletion:]_block_invoke_2
CStrings:
+ "Copying section settings from %{public}@ to %{public}@ [ destinationCapabilities: 0x%lx ]"
- "Copying section settings from %{public}@ to %{public}@"
```
