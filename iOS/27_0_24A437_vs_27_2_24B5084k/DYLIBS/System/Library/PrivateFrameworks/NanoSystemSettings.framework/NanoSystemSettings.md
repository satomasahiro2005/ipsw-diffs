## NanoSystemSettings

> `/System/Library/PrivateFrameworks/NanoSystemSettings.framework/NanoSystemSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x37400` | `0x37b80` | **`+0x780`** |
| `__TEXT.__gcc_except_tab` | `0x650` | `0x6cc` | **`+0x7c`** |
| `__TEXT.__oslogstring` | `0x6e2` | `0x722` | **`+0x40`** |
| `__DATA_CONST.__const` | `0x918` | `0x940` | **`+0x28`** |
| `__TEXT.__objc_methlist` | `0x3fcc` | `0x3fec` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0xec0` | `0xee0` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0x5c0` | `0x5c8` | **`+0x8`** |
| `__AUTH_CONST.__objc_const` | `0x64d0` | `0x64d8` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x1448` | `0x1450` | **`+0x8`** |

### Other Changes

```diff

-376.2.0.0.0
+383.0.0.0.0

-  Functions: 1586
-  Symbols:   2513
-  CStrings:  335
+  Functions: 1594
+  Symbols:   2519
+  CStrings:  336
Symbols:
+ -[NSSManager obliterateGizmoPreservingeSIM:overwriteStorage:completionHandler:]
+ GCC_except_table127
+ GCC_except_table137
+ GCC_except_table151
+ GCC_except_table165
+ GCC_except_table176
+ GCC_except_table183
+ GCC_except_table190
+ GCC_except_table197
+ GCC_except_table204
+ GCC_except_table211
+ GCC_except_table220
+ ___79-[NSSManager obliterateGizmoPreservingeSIM:overwriteStorage:completionHandler:]_block_invoke
+ ___79-[NSSManager obliterateGizmoPreservingeSIM:overwriteStorage:completionHandler:]_block_invoke_2
+ ___block_descriptor_50_e8_32s40bs_e5_v8?0ls32l8s40l8
+ _objc_retain_x4
- GCC_except_table129
- GCC_except_table135
- GCC_except_table149
- GCC_except_table168
- GCC_except_table175
- GCC_except_table182
- GCC_except_table189
- GCC_except_table196
- GCC_except_table203
- GCC_except_table212
CStrings:
+ "replyBlock: (%p); preserveeSIM: (%d); overwriteStorage: (%d)"
```
