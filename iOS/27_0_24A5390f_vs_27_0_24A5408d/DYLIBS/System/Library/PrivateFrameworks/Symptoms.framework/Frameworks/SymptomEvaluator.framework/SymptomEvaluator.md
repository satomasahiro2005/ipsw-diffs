## SymptomEvaluator

> `/System/Library/PrivateFrameworks/Symptoms.framework/Frameworks/SymptomEvaluator.framework/SymptomEvaluator`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2a0800` | `0x2a0bd0` | **`+0x3d0`** |
| `__AUTH_CONST.__objc_const` | `0x41a08` | `0x41ae0` | **`+0xd8`** |
| `__AUTH_CONST.__cfstring` | `0x1f360` | `0x1f400` | **`+0xa0`** |
| `__TEXT.__cstring` | `0x27840` | `0x278d0` | **`+0x90`** |
| `__AUTH.__objc_data` | `0x1178` | `0x11c8` | **`+0x50`** |
| `__TEXT.__objc_methlist` | `0x18c80` | `0x18cb0` | **`+0x30`** |
| `__TEXT.__oslogstring` | `0x47e15` | `0x47e45` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x6fc0` | `0x6fe8` | **`+0x28`** |
| `__AUTH_CONST.__const` | `0x3210` | `0x3230` | **`+0x20`** |
| `__DATA_CONST.__objc_arraydata` | `0x960` | `0x980` | **`+0x20`** |
| `__AUTH_CONST.__objc_arrayobj` | `0x1b0` | `0x1c8` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0xd4f0` | `0xd508` | **`+0x18`** |
| `__DATA.__bss` | `0xed0` | `0xee0` | **`+0x10`** |
| `__TEXT.__const` | `0x1278` | `0x1268` | **`-0x10`** |
| `__DATA.__objc_ivar` | `0x31a0` | `0x31a8` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x8b0` | `0x8b8` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x7a98` | `0x7aa0` | **`+0x8`** |

### Other Changes

```diff

-2394.0.0.0.0
+2394.0.4.0.0

-  Functions: 12227
-  Symbols:   20018
-  CStrings:  12214
+  Functions: 12233
+  Symbols:   20030
+  CStrings:  12219
Symbols:
+ -[CanUseAppsCacheEntry .cxx_destruct]
+ -[CellFallbackHandler _assessEligibilityOfApps:bundleNamesWithState:exceptions:verdict:explain:headroom:overdraft:extraPolicy:mustReply:replyQueue:reply:]
+ -[NetworkAnalyticsEngine _fireWiFiPrimaryWithoutActiveEpochABC]
+ -[NetworkAnalyticsEngine _setWiFiShimForTesting:]
+ GCC_except_table217
+ GCC_except_table260
+ GCC_except_table270
+ GCC_except_table272
+ GCC_except_table296
+ GCC_except_table301
+ GCC_except_table303
+ GCC_except_table414
+ _OBJC_CLASS_$_CanUseAppsCacheEntry
+ _OBJC_IVAR_$_CanUseAppsCacheEntry.insertedAt
+ _OBJC_IVAR_$_CanUseAppsCacheEntry.rationaleCode
+ _OBJC_METACLASS_$_CanUseAppsCacheEntry
+ __OBJC_$_INSTANCE_METHODS_CanUseAppsCacheEntry
+ __OBJC_$_INSTANCE_VARIABLES_CanUseAppsCacheEntry
+ __OBJC_CLASS_RO_$_CanUseAppsCacheEntry
+ __OBJC_METACLASS_RO_$_CanUseAppsCacheEntry
+ ___154-[CellFallbackHandler _assessEligibilityOfApps:bundleNamesWithState:exceptions:verdict:explain:headroom:overdraft:extraPolicy:mustReply:replyQueue:reply:]_block_invoke
+ ___63-[NetworkAnalyticsEngine _fireWiFiPrimaryWithoutActiveEpochABC]_block_invoke
+ ____considerAlternateUpdateBundleSuppressList_block_invoke
+ ___block_descriptor_40_e8_32s_e28_"NSString"16?0"NSObject"8ls32l8
+ __considerAlternateUpdateBundleSuppressList.onceToken
+ __considerAlternateUpdateBundleSuppressList.set
- -[CellFallbackHandler _assessEligibilityOfApps:bundleNamesWithState:exceptions:verdict:explain:headroom:overdraft:strictlyUsage:mustReply:replyQueue:reply:]
- GCC_except_table165
- GCC_except_table216
- GCC_except_table253
- GCC_except_table263
- GCC_except_table269
- GCC_except_table271
- GCC_except_table299
- GCC_except_table307
- GCC_except_table355
- GCC_except_table394
- GCC_except_table411
- GCC_except_table422
- ___156-[CellFallbackHandler _assessEligibilityOfApps:bundleNamesWithState:exceptions:verdict:explain:headroom:overdraft:strictlyUsage:mustReply:replyQueue:reply:]_block_invoke
CStrings:
+ "%@(aged)"
+ "CFSM AON usage: optimistic YES, evaluate later (app: %@, state: %ld, ratio: %.2f)"
+ "CFSM AON usage: verdict %@ from cache (app: %@, state: %ld, ratio: %.2f)"
+ "CFSM cache: aged out for (appName/state/code/age): %@/%ld/%@/%.1fs (ttl %.0fs)"
+ "CFSM cache: hit for (appName/state/code/age): %@/%ld/%@/%.1fs"
+ "WiFi Primary Without Active Epoch"
+ "WiFi Primary Without Active Epoch ABC case response: %@"
+ "com.apple.WebKit.GPU"
+ "com.apple.WebKit.WebContent"
+ "com.apple.WebKit.WebContent.EnhancedSecurity"
- "CFSM AON usage: free pass no ratio (app: %@, state: %ld)"
- "CFSM AON usage: verdict %@ from usage cache (app: %@, state: %ld)"
- "CFSM AON usage: verdict optimistic YES, evaluate later (app: %@, state: %ld)"
- "CFSM cache: hit for (appName/state/code): %@/%ld/%@"
- "CFSM dynamic denylist freepass %@ (app: %@, state: %@)"
```
