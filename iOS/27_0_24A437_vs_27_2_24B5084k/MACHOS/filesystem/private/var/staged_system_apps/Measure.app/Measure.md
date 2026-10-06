## Measure

> `/private/var/staged_system_apps/Measure.app/Measure`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3a9674` | `0x3aa754` | **`+0x10e0`** |
| `__TEXT.__const` | `0x1a8fc` | `0x1ab2c` | **`+0x230`** |
| `__DATA.__bss` | `0x23bb0` | `0x23d10` | **`+0x160`** |
| `__DATA.__objc_const` | `0x14b60` | `0x14c90` | **`+0x130`** |
| `__DATA.__data` | `0x11300` | `0x113d0` | **`+0xd0`** |
| `__TEXT.__swift5_reflstr` | `0xabf4` | `0xac84` | **`+0x90`** |
| `__TEXT.__objc_stubs` | `0x7ce0` | `0x7d60` | **`+0x80`** |
| `__TEXT.__objc_methtype` | `0x5208` | `0x5278` | **`+0x70`** |
| `__TEXT.__objc_methname` | `0x140e5` | `0x14145` | **`+0x60`** |
| `__TEXT.__swift5_fieldmd` | `0x8554` | `0x85b4` | **`+0x60`** |
| `__TEXT.__cstring` | `0x1a4ef` | `0x1a52f` | **`+0x40`** |
| `__TEXT.__swift5_capture` | `0x20cc` | `0x2104` | **`+0x38`** |
| `__TEXT.__swift5_typeref` | `0x613a` | `0x6172` | **`+0x38`** |
| `__DATA_CONST.__const` | `0x17040` | `0x17070` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x4498` | `0x44c0` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x97d0` | `0x97f0` | **`+0x20`** |
| `__DATA.__objc_data` | `0x99f0` | `0x9a08` | **`+0x18`** |
| `__DATA.__objc_selrefs` | `0x35a8` | `0x35c0` | **`+0x18`** |
| `__TEXT.__swift5_assocty` | `0xd40` | `0xd58` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x13e8` | `0x13f8` | **`+0x10`** |
| `__DATA_CONST.__auth_ptr` | `0x1920` | `0x1928` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x728` | `0x730` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x48` | `0x4c` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_stublist`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__init_offsets`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-196.0.6.0.0
+196.40.1.0.0

-  Functions: 10765
-  Symbols:   2321
-  CStrings:  6311
+  Functions: 10783
+  Symbols:   2322
+  CStrings:  6320
Symbols:
+ _CGRectNull
CStrings:
+ "\nGeneral configuration for OpenCV 3.4.0 =====================================\n  Version control:               unknown\n\n  Platform:\n    Timestamp:                   2026-09-05T08:54:30Z\n    Host:                        Darwin 10.0 x86_64\n    Target:                      Darwin 16.0.0 arm\n    CMake:                       4.0.3\n    CMake generator:             Xcode\n    CMake build tool:            /AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/usr/bin/xcodebuild\n    Xcode:                       27.0\n\n  CPU/HW features:\n    Baseline:\n      requested:                 DETECT\n\n  C/C++:\n    Built as dynamic libs?:      NO\n    C++11:                       YES\n    C++ Compiler:                /AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Toolchains/iOS27.2.xctoolchain/usr/bin/clang++  (ver 21.0.0.21000334)\n    C++ flags (Release):         -isysroot'/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk' -F'/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/System/Library/PrivateFrameworks' -isysroot'/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk' -F'/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/System/Library/PrivateFrameworks'   -fsigned-char  -O3 -DNDEBUG \n    C++ flags (Debug):           -isysroot'/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk' -F'/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/System/Library/PrivateFrameworks' -isysroot'/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk' -F'/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/System/Library/PrivateFrameworks'   -fsigned-char  -g \n    C Compiler:                  /AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Toolchains/iOS27.2.xctoolchain/usr/bin/clang\n    C flags (Release):           -isysroot'/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk' -F'/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/System/Library/PrivateFrameworks' -isysroot'/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk' -F'/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/System/Library/PrivateFrameworks'   -fsigned-char  -O3 -DNDEBUG \n    C flags (Debug):             -isysroot'/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk' -F'/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/System/Library/PrivateFrameworks' -isysroot'/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk' -F'/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/System/Library/PrivateFrameworks'   -fsigned-char  -g \n    Linker flags (Release):\n    Linker flags (Debug):\n    ccache:                      NO\n    Precompiled headers:         NO\n    Extra dependencies:          /AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/usr/lib/libz.tbd -framework Accelerate -framework CoreGraphics -framework QuartzCore -framework AssetsLibrary -framework UIKit\n    3rdparty dependencies:       libjpeg libpng\n\n  OpenCV modules:\n    To be built:                 core imgcodecs imgproc\n    Disabled:                    -\n    Disabled by dependency:      -\n    Unavailable:                 -\n    Applications:                -\n    Documentation:               NO\n    Non-free algorithms:         NO\n\n  GUI: \n    Cocoa:                       YES\n\n  Media I/O: \n    ZLib:                        /AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/usr/lib/libz.tbd (ver 1.2.12)\n    JPEG:                        build (ver 90)\n    PNG:                         build (ver 1.6.34)\n\n  Video I/O:\n    AVFoundation:                YES\n\n  Parallel framework:            GCD\n\n  Trace:                         YES (built-in)\n\n  Other third-party libraries:\n    Custom HAL:                  NO\n\n  Python (for build):            NO\n\n  Install to:                    /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/Measure/install/TempContent/Objects/opencv/build/build-iphoneos/install\n-----------------------------------------------------------------\n\n"
+ ", rebuilding EdgeDetector"
+ "T{CGRect={CGPoint=dd}{CGSize=dd}},N,V_lastCorrectedBounds"
+ "Viewport changed "
+ "_lastCorrectedBounds"
+ "_sceneViewport"
+ "frameLayoutGuide"
+ "lastCorrectedBounds"
+ "setLastCorrectedBounds:"
+ "v48@0:8{CGRect={CGPoint=dd}{CGSize=dd}}16"
+ "{CGRect=\"origin\"{CGPoint=\"x\"d\"y\"d}\"size\"{CGSize=\"width\"d\"height\"d}}"
- "\nGeneral configuration for OpenCV 3.4.0 =====================================\n  Version control:               unknown\n\n  Platform:\n    Timestamp:                   2026-08-09T04:47:41Z\n    Host:                        Darwin 10.0 x86_64\n    Target:                      Darwin 16.0.0 arm\n    CMake:                       4.0.3\n    CMake generator:             Xcode\n    CMake build tool:            /AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/usr/bin/xcodebuild\n    Xcode:                       27.0\n\n  CPU/HW features:\n    Baseline:\n      requested:                 DETECT\n\n  C/C++:\n    Built as dynamic libs?:      NO\n    C++11:                       YES\n    C++ Compiler:                /AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Toolchains/iOS27.0.xctoolchain/usr/bin/clang++  (ver 21.0.0.21000331)\n    C++ flags (Release):         -isysroot'/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk' -F'/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/System/Library/PrivateFrameworks' -isysroot'/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk' -F'/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/System/Library/PrivateFrameworks'   -fsigned-char  -O3 -DNDEBUG \n    C++ flags (Debug):           -isysroot'/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk' -F'/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/System/Library/PrivateFrameworks' -isysroot'/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk' -F'/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/System/Library/PrivateFrameworks'   -fsigned-char  -g \n    C Compiler:                  /AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Toolchains/iOS27.0.xctoolchain/usr/bin/clang\n    C flags (Release):           -isysroot'/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk' -F'/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/System/Library/PrivateFrameworks' -isysroot'/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk' -F'/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/System/Library/PrivateFrameworks'   -fsigned-char  -O3 -DNDEBUG \n    C flags (Debug):             -isysroot'/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk' -F'/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/System/Library/PrivateFrameworks' -isysroot'/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk' -F'/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/System/Library/PrivateFrameworks'   -fsigned-char  -g \n    Linker flags (Release):\n    Linker flags (Debug):\n    ccache:                      NO\n    Precompiled headers:         NO\n    Extra dependencies:          /AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/lib/libz.tbd -framework Accelerate -framework CoreGraphics -framework QuartzCore -framework AssetsLibrary -framework UIKit\n    3rdparty dependencies:       libjpeg libpng\n\n  OpenCV modules:\n    To be built:                 core imgcodecs imgproc\n    Disabled:                    -\n    Disabled by dependency:      -\n    Unavailable:                 -\n    Applications:                -\n    Documentation:               NO\n    Non-free algorithms:         NO\n\n  GUI: \n    Cocoa:                       YES\n\n  Media I/O: \n    ZLib:                        /AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/lib/libz.tbd (ver 1.2.12)\n    JPEG:                        build (ver 90)\n    PNG:                         build (ver 1.6.34)\n\n  Video I/O:\n    AVFoundation:                YES\n\n  Parallel framework:            GCD\n\n  Trace:                         YES (built-in)\n\n  Other third-party libraries:\n    Custom HAL:                  NO\n\n  Python (for build):            NO\n\n  Install to:                    /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/Measure/install/TempContent/Objects/opencv/build/build-iphoneos/install\n-----------------------------------------------------------------\n\n"
- "sceneViewTraits"
```
