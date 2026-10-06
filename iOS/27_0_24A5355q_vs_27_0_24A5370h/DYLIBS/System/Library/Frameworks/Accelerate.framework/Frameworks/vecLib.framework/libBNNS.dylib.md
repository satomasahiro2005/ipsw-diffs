## libBNNS.dylib

> `/System/Library/Frameworks/Accelerate.framework/Frameworks/vecLib.framework/libBNNS.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1153a24` | `0x1137a2c` | **`-0x1bff8`** |
| `__TEXT.__cstring` | `0x5e8dc` | `0x5f847` | **`+0xf6b`** |
| `__TEXT.__gcc_except_tab` | `0x2dcf0` | `0x2e3e4` | **`+0x6f4`** |
| `__TEXT.__eh_frame` | `0xe030` | `0xd9e8` | **`-0x648`** |
| `__AUTH_CONST.__const` | `0x3a470` | `0x3a830` | **`+0x3c0`** |
| `__TEXT.__const` | `0x627bc` | `0x62a3c` | **`+0x280`** |
| `__DATA_CONST.__const` | `0x6d60` | `0x6da0` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x1bd90` | `0x1bda8` | **`+0x18`** |

### Other Changes

```diff

-2206.0.0.0.4
+2211.0.0.0.1

-  Functions: 39231
-  Symbols:   824
-  CStrings:  8627
+  Functions: 39318
+  Symbols:   827
+  CStrings:  8701
Symbols:
+ _BNNSGraphCompileOptionsGetCacheDequantizedWeights
+ _BNNSGraphCompileOptionsSetCacheDequantizedWeights
+ _BNNSGraphCompileOptionsSetResourceLookupCallback
CStrings:
+ "  before=[%u,%u,%u,%u,%u,%u,%u,%u] after=[%u,%u,%u,%u,%u,%u,%u,%u]\n"
+ "  kernel=[%llu,%llu,%llu] stride=[%llu,%llu,%llu] pad=[%llu,%llu,%llu,%llu,%llu,%llu] ceil=%c count_include_pad=%c\n"
+ "  kernel=[%llu,%llu,%llu] stride=[%llu,%llu,%llu] pad=[%llu,%llu,%llu,%llu,%llu,%llu] dilation=[%llu,%llu,%llu] groups=%llu bias=%c\n"
+ "  kernel=[%llu,%llu] stride=[%llu,%llu] pad=[%llu,%llu,%llu,%llu] ceil=%c count_include_pad=%c\n"
+ "  kernel=[%llu,%llu] stride=[%u,%u] pad=[%u,%u,%u,%u] dilation=[%u,%u] groups=%u bias=%c\n"
+ "  kernel=[%llu,%llu] stride=[%u,%u] pad=[%u,%u,%u,%u] dilation=[%u,%u] groups=%u bias=%c input_grad=%c weight_grad=%c bias_grad=%c\n"
+ "  mode=%s value=0x%08x simple=%c pad_value_as_input=%c\n"
+ " persistent_memory_offset=%llu"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:1161: libc++ Hardening assertion __position != end() failed: vector::erase(iterator) called with a non-dereferenceable iterator\n"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:414: libc++ Hardening assertion __n < size() failed: vector[] index out of bounds\n"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:419: libc++ Hardening assertion __n < size() failed: vector[] index out of bounds\n"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:434: libc++ Hardening assertion !empty() failed: front() called on an empty vector\n"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:438: libc++ Hardening assertion !empty() failed: front() called on an empty vector\n"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:442: libc++ Hardening assertion !empty() failed: back() called on an empty vector\n"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:446: libc++ Hardening assertion !empty() failed: back() called on an empty vector\n"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:509: libc++ Hardening assertion !empty() failed: vector::pop_back called on an empty vector\n"
+ "BNNS Graph Cast: contiguous access is out of bounds"
+ "BNNS Graph Cast: null pointer not expected"
+ "BNNS Graph Shape: null pointer not expected"
+ "BNNS Graph TTS_10: null pointer not expected"
+ "BNNS Graph TTS_11: null pointer not expected"
+ "BNNS Graph TTS_12: null pointer not expected"
+ "BNNS Graph TTS_13: null pointer not expected"
+ "BNNS Graph TTS_14: null pointer not expected"
+ "BNNS Graph TTS_15: null pointer not expected"
+ "BNNS Graph TTS_16: null pointer not expected"
+ "BNNS Graph TTS_17: null pointer not expected"
+ "BNNS Graph TTS_18: null pointer not expected"
+ "BNNS Graph TTS_19: null pointer not expected"
+ "BNNS Graph TTS_1: null pointer not expected"
+ "BNNS Graph TTS_20: null pointer not expected"
+ "BNNS Graph TTS_21: null pointer not expected"
+ "BNNS Graph TTS_22: null pointer not expected"
+ "BNNS Graph TTS_23: null pointer not expected"
+ "BNNS Graph TTS_24: null pointer not expected"
+ "BNNS Graph TTS_25: null pointer not expected"
+ "BNNS Graph TTS_26: null pointer not expected"
+ "BNNS Graph TTS_27: null pointer not expected"
+ "BNNS Graph TTS_28: null pointer not expected"
+ "BNNS Graph TTS_29: null pointer not expected"
+ "BNNS Graph TTS_2: null pointer not expected"
+ "BNNS Graph TTS_30: null pointer not expected"
+ "BNNS Graph TTS_31: null pointer not expected"
+ "BNNS Graph TTS_3: null pointer not expected"
+ "BNNS Graph TTS_4: null pointer not expected"
+ "BNNS Graph TTS_5: null pointer not expected"
+ "BNNS Graph TTS_6: null pointer not expected"
+ "BNNS Graph TTS_7: null pointer not expected"
+ "BNNS Graph TTS_8: null pointer not expected"
+ "BNNS Graph TTS_9: null pointer not expected"
+ "BNNS: wrong code path taken"
+ "BNNSGraphCompileOptionsGetCacheDequantizedWeights"
+ "BNNSGraphCompileOptionsSetCacheDequantizedWeights"
+ "BNNSGraphCompileOptionsSetResourceLookupCallback"
+ "BNNSGraphContextEnforceValidation: models with persistent memory are not supported"
+ "BNNSGraphContextEnforceValidation: operation has persistent memory offset but persistent memory is not supported"
+ "BNNSSGemvDWS SPI: Expected LDA >= M"
+ "BasicNeuralNetworkSubroutines-2211.0.0.0.1~50"
+ "ComputeOnce Tensor %llxx accessed oob. Attempted to read %zu bytes from offset %llu of span (%p, %zu)\n"
+ "Failed to lower AICode IR to BNNS-MLIR"
+ "KVertical validation failed: dilation must be <= 1"
+ "KVertical validation failed: groups must be <= 1"
+ "KVertical validation failed: input channels must be 1"
+ "KVertical validation failed: input height stride causes out-of-bounds access"
+ "KVertical validation failed: input width must equal output width"
+ "KVertical validation failed: kernel width must be 1"
+ "KVertical validation failed: output strides cause out-of-bounds access"
+ "KVertical validation failed: overflow in input offset calculation"
+ "KVertical validation failed: overflow in input stride calculation"
+ "KVertical validation failed: overflow in output channel stride calculation"
+ "KVertical validation failed: overflow in output height stride calculation"
+ "KVertical validation failed: overflow in output offset calculation"
+ "KVertical validation failed: strides must be 1"
+ "KVertical validation failed: y_padding must be less than kernel height"
+ "KVertical validation failed: zero output dimensions"
+ "SME conv transpose validation failed: scratch_size too small"
+ "UINT4 MATMUL: codepath not supported on this device"
+ "combo_dodge_v2_amx3"
+ "combo_dodge_v2_sme2_1"
+ "encode"
+ "init_encode"
+ "init_prepare_encode"
+ "init_reshape_encode"
+ "init_reshape_prepare_encode"
+ "persistent_memory(conv_repack:"
+ "persistent_memory(cookie_for:"
+ "persistent_memory(matmul_transpose:"
+ "runtime_invariant_propagation_pass"
+ "slice parameter vectors do not match input rank"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:1146: libc++ Hardening assertion __position != end() failed: vector::erase(iterator) called with a non-dereferenceable iterator\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:413: libc++ Hardening assertion __n < size() failed: vector[] index out of bounds\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:418: libc++ Hardening assertion __n < size() failed: vector[] index out of bounds\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:433: libc++ Hardening assertion !empty() failed: front() called on an empty vector\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:437: libc++ Hardening assertion !empty() failed: front() called on an empty vector\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:441: libc++ Hardening assertion !empty() failed: back() called on an empty vector\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:445: libc++ Hardening assertion !empty() failed: back() called on an empty vector\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:494: libc++ Hardening assertion !empty() failed: vector::pop_back called on an empty vector\n"
- "BNNS Graph: null pointer not expected"
- "BNNS Graph: null pointer not expected (1)"
- "BNNS Graph: null pointer not expected (2)"
- "BNNS Graph: null pointer not expected (3)"
- "BasicNeuralNetworkSubroutines-2206.0.0.0.4~65"
- "Failed to lower CoreML IR to BNNS-MLIR"
- "logits"
```
