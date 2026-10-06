## libdyld.dylib

> `/usr/lib/system/libdyld.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x4cb5` | `0x4d20` | **`+0x6b`** |
| `__TEXT.__text` | `0x1ce38` | `0x1ce24` | **`-0x14`** |

### Other Changes

```diff

-  CStrings:  540
+  CStrings:  548
Functions:
~ __ZNK6mach_o12Architecture8baseNameEv : 76 -> 96
~ ___clang_call_terminate : 28 -> 24
~ __ZNK6mach_o21FunctionVariantFixups5validENSt3__14spanIKNS_13MappedSegmentELm18446744073709551615EEE : 188 -> 184
~ __ZNK6mach_o19GradedArchitectures8bestArchENSt3__14spanIKNS_12ArchitectureELm18446744073709551615EEE : 164 -> 148
~ __ZNK6mach_o19GradedArchitectures8containsENS_12ArchitectureE : 92 -> 84
~ __ZNK6mach_o19GradedArchitectures11forEachArchEU13block_pointerFvNS_12ArchitectureEE : 108 -> 100
~ __ZNK6mach_o6Header22validStructureLinkeditERKNS_6PolicyEy : 1612 -> 1608
~ __ZNK6mach_o5Image13linkeditBytesENS_6Header13LinkEditRangeE : 152 -> 160
~ ____ZNK6mach_o5Image13validLinkeditERKNS_6PolicyE_block_invoke : 720 -> 716
CStrings:
+ "16777228--2147483636"
+ "arm64.x1"
+ "arm64.x2"
+ "arm64e.x1"
+ "arm64e.x1.kernel"
+ "arm64e.x1.old"
+ "arm64e.x2"
+ "arm64e.x2.kernel"
```
