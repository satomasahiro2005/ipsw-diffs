## diskimagescontroller

> `/System/Library/PrivateFrameworks/DiskImages2.framework/XPCServices/diskimagescontroller.xpc/diskimagescontroller`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1e503c` | `0x1eea0c` | **`+0x99d0`** |
| `__TEXT.__const` | `0x1482a` | `0x17a9a` | **`+0x3270`** |
| `__TEXT.__cstring` | `0x174c8` | `0x18508` | **`+0x1040`** |
| `__TEXT.__gcc_except_tab` | `0x1b908` | `0x1bd88` | **`+0x480`** |
| `__TEXT.__unwind_info` | `0xe0b8` | `0xe390` | **`+0x2d8`** |
| `__DATA_CONST.__const` | `0x39cd0` | `0x39dd0` | **`+0x100`** |
| `__TEXT.__auth_stubs` | `0x2120` | `0x2220` | **`+0x100`** |
| `__DATA_CONST.__auth_got` | `0x10a8` | `0x1128` | **`+0x80`** |
| `__DATA_CONST.__got` | `0x568` | `0x5c8` | **`+0x60`** |
| `__TEXT.__objc_methname` | `0x685c` | `0x6803` | **`-0x59`** |
| `__TEXT.__objc_stubs` | `0x5c40` | `0x5c00` | **`-0x40`** |
| `__TEXT.__objc_methlist` | `0x34ac` | `0x3494` | **`-0x18`** |
| `__DATA.__objc_selrefs` | `0x1b80` | `0x1b70` | **`-0x10`** |
| `__TEXT.__objc_methtype` | `0x2365` | `0x2355` | **`-0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_typeref`

### Other Changes

```diff

-593.0.0.0.1
+596.0.0.0.0

-  Functions: 11412
-  Symbols:   811
-  CStrings:  3598
+  Functions: 11567
+  Symbols:   829
+  CStrings:  3659
Symbols:
+ __ZNKSt13runtime_error4whatEv
+ __ZNSt13runtime_errorC2EPKc
+ __ZNSt13runtime_errorD2Ev
+ __ZNSt3__16localeC1ERKS0_
+ __ZNSt3__16localeaSERKS0_
+ __ZNSt3__18numpunctIcE2idE
+ __ZNSt3__18to_charsEPcS0_d
+ __ZNSt3__18to_charsEPcS0_dNS_12chars_formatE
+ __ZNSt3__18to_charsEPcS0_dNS_12chars_formatEi
+ __ZNSt3__18to_charsEPcS0_e
+ __ZNSt3__18to_charsEPcS0_eNS_12chars_formatE
+ __ZNSt3__18to_charsEPcS0_eNS_12chars_formatEi
+ __ZNSt3__18to_charsEPcS0_f
+ __ZNSt3__18to_charsEPcS0_fNS_12chars_formatE
+ __ZNSt3__18to_charsEPcS0_fNS_12chars_formatEi
+ ___udivti3
+ ___umodti3
+ _time
CStrings:
+ " does not allow the "
+ " formatting argument"
+ " option"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/local/include/c++/previous/__format/formatter_output.h:237: libc++ Hardening assertion __first <= __last failed: Not a valid range\n"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/local/include/c++/previous/__format/formatter_output.h:250: libc++ Hardening assertion __first <= __last failed: Not a valid range\n"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/local/include/c++/previous/__format/formatter_output.h:264: libc++ Hardening assertion __first <= __last failed: Not a valid range\n"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/local/include/c++/previous/__format/parser_std_format_spec.h:594: libc++ Hardening assertion __begin != __end failed: when called with an empty input the function will cause undefined behavior by evaluating data not in the input\n"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/local/include/c++/previous/string_view:329: libc++ Hardening assertion __len <= static_cast<size_type>(numeric_limits<difference_type>::max()) failed: string_view::string_view(_CharT *, size_t): length does not fit in difference_type\n"
+ "0"
+ "01"
+ "01234567"
+ "0123456789abcdef"
+ "0123456789abcdefghijklmnopqrstuvwxyz"
+ "0B"
+ "0X"
+ "0b"
+ "596"
+ "An argument index may not have a negative value"
+ "End of input while parsing an argument index"
+ "End of input while parsing format specifier precision"
+ "Error creating (unlocked) backend"
+ "Integral value outside the range of the char type"
+ "Legacy prepended-header UDIF image is not supported by this framework"
+ "Replacement argument isn't a standard signed or unsigned integer type"
+ "The argument index is invalid"
+ "The argument index should end with a ':' or a '}'"
+ "The argument index starts with an invalid character"
+ "The argument index value is too large for the number of arguments supplied"
+ "The fill option contains an invalid value"
+ "The format specifier contains malformed Unicode characters"
+ "The format specifier for "
+ "The format specifier should consume the input or end with a '}'"
+ "The format string contains an invalid escape sequence"
+ "The format string terminates at a '{'"
+ "The numeric value of the format specifier is too large"
+ "The precision option does not contain a value or an argument index"
+ "The replacement field misses a terminating '}'"
+ "The type does not fit in the mask"
+ "The type option contains an invalid value for "
+ "The type option contains an invalid value for a string formatting argument"
+ "The value of the argument index exceeds its maximum value"
+ "The width option should not have a leading zero"
+ "Unexpected error creating (unlocked) backend"
+ "Using automatic argument numbering in manual argument numbering mode"
+ "Using manual argument numbering in automatic argument numbering mode"
+ "\\\""
+ "\\'"
+ "\\\\"
+ "\\n"
+ "\\r"
+ "\\t"
+ "\\u{"
+ "\\x{"
+ "a bool"
+ "a character"
+ "a floating-point"
+ "a pointer"
+ "alternate form"
+ "an integer"
+ "auto AEAHelper::key_params_t::run(function &&) [function = di_utils::overloaded<(lambda at /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/DiskImages2/DiskImagesLib/DiskImageParamsXPC.mm:221:8), (lambda at /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/DiskImages2/DiskImagesLib/DiskImageParamsXPC.mm:225:8), (lambda at /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/DiskImages2/DiskImagesLib/DiskImageParamsXPC.mm:229:8), (lambda at /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/DiskImages2/DiskImagesLib/DiskImageParamsXPC.mm:232:8)> &]"
+ "errorWithDIException:prefix:error:"
+ "false"
+ "infnanINFNAN"
+ "locale-specific form"
+ "precision"
+ "sign"
+ "true"
+ "void crypto::details::unset_futures_errors_reporter<std::ranges::transform_view<std::ranges::ref_view<container_it<std::__deque_iterator<FileLocalAsync::promise_io_t, FileLocalAsync::promise_io_t *, FileLocalAsync::promise_io_t &, FileLocalAsync::promise_io_t **, long>>>, (lambda at /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/DiskImages2/app/backends/file.cpp:1095:24)>::__iterator<false>>::report_errors(int) [It = std::ranges::transform_view<std::ranges::ref_view<container_it<std::__deque_iterator<FileLocalAsync::promise_io_t, FileLocalAsync::promise_io_t *, FileLocalAsync::promise_io_t &, FileLocalAsync::promise_io_t **, long>>>, (lambda at /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/DiskImages2/app/backends/file.cpp:1095:24)>::__iterator<false>]"
+ "void crypto::details::unset_futures_errors_reporter<std::ranges::transform_view<std::ranges::ref_view<container_it<std::__wrap_iter<FileLocalAsync::promise_io_t *>>>, (lambda at /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/DiskImages2/app/backends/file.cpp:997:23)>::__iterator<false>>::report_errors(int) [It = std::ranges::transform_view<std::ranges::ref_view<container_it<std::__wrap_iter<FileLocalAsync::promise_io_t *>>>, (lambda at /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/DiskImages2/app/backends/file.cpp:997:23)>::__iterator<false>]"
+ "zero-padding"
+ "{:02x}{:02x}"
- "593.0.0"
- "@48@0:8r^v16@24@32^@40"
- "Error creating AEA backend"
- "Failed reading sparse image header"
- "Unexpected error creating AEA backend"
- "auto AEAHelper::key_params_t::run(function &&) [function = di_utils::overloaded<(lambda at /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/DiskImages2/DiskImagesLib/DiskImageParamsXPC.mm:219:8), (lambda at /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/DiskImages2/DiskImagesLib/DiskImageParamsXPC.mm:223:8), (lambda at /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/DiskImages2/DiskImagesLib/DiskImageParamsXPC.mm:227:8), (lambda at /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/DiskImages2/DiskImagesLib/DiskImageParamsXPC.mm:230:8)> &]"
- "errorWithDIException:description:prefix:error:"
- "failWithDIException:description:error:"
- "nilWithDIException:description:error:"
- "void crypto::details::unset_futures_errors_reporter<std::ranges::transform_view<std::ranges::ref_view<container_it<std::__deque_iterator<FileLocalAsync::promise_io_t, FileLocalAsync::promise_io_t *, FileLocalAsync::promise_io_t &, FileLocalAsync::promise_io_t **, long>>>, (lambda at /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/DiskImages2/app/backends/file.cpp:1093:24)>::__iterator<false>>::report_errors(int) [It = std::ranges::transform_view<std::ranges::ref_view<container_it<std::__deque_iterator<FileLocalAsync::promise_io_t, FileLocalAsync::promise_io_t *, FileLocalAsync::promise_io_t &, FileLocalAsync::promise_io_t **, long>>>, (lambda at /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/DiskImages2/app/backends/file.cpp:1093:24)>::__iterator<false>]"
```
