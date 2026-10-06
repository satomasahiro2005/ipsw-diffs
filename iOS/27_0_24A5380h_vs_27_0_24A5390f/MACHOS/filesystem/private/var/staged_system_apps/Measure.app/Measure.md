## Measure

> `/private/var/staged_system_apps/Measure.app/Measure`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3a7b80` | `0x3a83f4` | **`+0x874`** |
| `__TEXT.__swift5_reflstr` | `0xacd4` | `0xabd4` | **`-0x100`** |
| `__TEXT.__objc_methname` | `0x13fa5` | `0x13f15` | **`-0x90`** |
| `__DATA.__objc_const` | `0x14ba0` | `0x14b28` | **`-0x78`** |
| `__DATA.__data` | `0x11320` | `0x112e0` | **`-0x40`** |
| `__TEXT.__objc_methtype` | `0x51c8` | `0x5208` | **`+0x40`** |
| `__TEXT.__objc_stubs` | `0x7ca0` | `0x7ce0` | **`+0x40`** |
| `__TEXT.__const` | `0x1a89c` | `0x1a8cc` | **`+0x30`** |
| `__TEXT.__swift5_fieldmd` | `0x8578` | `0x8548` | **`-0x30`** |
| `__TEXT.__cstring` | `0x1a516` | `0x1a4f6` | **`-0x20`** |
| `__DATA.__objc_selrefs` | `0x3588` | `0x35a0` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x4480` | `0x4490` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x97c0` | `0x97d0` | **`+0x10`** |
| `__DATA_CONST.__auth_ptr` | `0x1928` | `0x1920` | **`-0x8`** |
| `__TEXT.__swift5_typeref` | `0x6142` | `0x613a` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA.__objc_stublist`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__init_offsets`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-196.0.2.0.0
+196.0.4.0.0

-  Functions: 10773
+  Functions: 10772

-  CStrings:  6308
+  CStrings:  6309
CStrings:
+ "\nGeneral configuration for OpenCV 3.4.0 =====================================\n  Version control:               unknown\n\n  Platform:\n    Timestamp:                   2026-07-11T13:51:48Z\n    Host:                        Darwin 10.0 x86_64\n    Target:                      Darwin 16.0.0 arm\n    CMake:                       4.0.3\n    CMake generator:             Xcode\n    CMake build tool:            /AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/usr/bin/xcodebuild\n    Xcode:                       27.0\n\n  CPU/HW features:\n    Baseline:\n      requested:                 DETECT\n\n  C/C++:\n    Built as dynamic libs?:      NO\n    C++11:                       YES\n    C++ Compiler:                /AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Toolchains/iOS27.0.xctoolchain/usr/bin/clang++  (ver 21.0.0.21000327)\n    C++ flags (Release):         -isysroot'/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk' -F'/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/System/Library/PrivateFrameworks' -isysroot'/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk' -F'/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/System/Library/PrivateFrameworks'   -fsigned-char  -O3 -DNDEBUG \n    C++ flags (Debug):           -isysroot'/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk' -F'/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/System/Library/PrivateFrameworks' -isysroot'/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk' -F'/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/System/Library/PrivateFrameworks'   -fsigned-char  -g \n    C Compiler:                  /AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Toolchains/iOS27.0.xctoolchain/usr/bin/clang\n    C flags (Release):           -isysroot'/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk' -F'/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/System/Library/PrivateFrameworks' -isysroot'/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk' -F'/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/System/Library/PrivateFrameworks'   -fsigned-char  -O3 -DNDEBUG \n    C flags (Debug):             -isysroot'/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk' -F'/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/System/Library/PrivateFrameworks' -isysroot'/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk' -F'/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/System/Library/PrivateFrameworks'   -fsigned-char  -g \n    Linker flags (Release):\n    Linker flags (Debug):\n    ccache:                      NO\n    Precompiled headers:         NO\n    Extra dependencies:          /AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/lib/libz.tbd -framework Accelerate -framework CoreGraphics -framework QuartzCore -framework AssetsLibrary -framework UIKit\n    3rdparty dependencies:       libjpeg libpng\n\n  OpenCV modules:\n    To be built:                 core imgcodecs imgproc\n    Disabled:                    -\n    Disabled by dependency:      -\n    Unavailable:                 -\n    Applications:                -\n    Documentation:               NO\n    Non-free algorithms:         NO\n\n  GUI: \n    Cocoa:                       YES\n\n  Media I/O: \n    ZLib:                        /AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/lib/libz.tbd (ver 1.2.12)\n    JPEG:                        build (ver 90)\n    PNG:                         build (ver 1.6.34)\n\n  Video I/O:\n    AVFoundation:                YES\n\n  Parallel framework:            GCD\n\n  Trace:                         YES (built-in)\n\n  Other third-party libraries:\n    Custom HAL:                  NO\n\n  Python (for build):            NO\n\n  Install to:                    /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/Measure/install/TempContent/Objects/opencv/build/build-arm64e-iphoneos/install\n-----------------------------------------------------------------\n\n"
+ "SIGNIFICANT_CHANGE_DESCRIPTION"
+ "SIGNIFICANT_CHANGE_WAITING_BUTTON"
+ "SIGNIFICANT_CHANGE_WAITING_MESSAGE"
+ "SIGNIFICANT_CHANGE_WAITING_TITLE"
+ "SIGNIFICANT_CHANGE_WARMING_BUTTON"
+ "SIGNIFICANT_CHANGE_WARMING_MESSAGE"
+ "SIGNIFICANT_CHANGE_WARMING_TITLE"
+ "[AMSKit] Evaluating significant change for version "
+ "isSupported"
+ "session:didChangeViewRotationAngle:"
+ "setAffineTransform:"
+ "useHorizontalTail"
+ "v32@0:8@\"ARSession\"16d24"
- "\nGeneral configuration for OpenCV 3.4.0 =====================================\n  Version control:               unknown\n\n  Platform:\n    Timestamp:                   2026-06-28T07:32:30Z\n    Host:                        Darwin 10.0 x86_64\n    Target:                      Darwin 16.0.0 arm\n    CMake:                       4.0.3\n    CMake generator:             Xcode\n    CMake build tool:            /AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/usr/bin/xcodebuild\n    Xcode:                       27.0\n\n  CPU/HW features:\n    Baseline:\n      requested:                 DETECT\n\n  C/C++:\n    Built as dynamic libs?:      NO\n    C++11:                       YES\n    C++ Compiler:                /AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Toolchains/iOS27.0.xctoolchain/usr/bin/clang++  (ver 21.0.0.21000325)\n    C++ flags (Release):         -isysroot'/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk' -F'/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/System/Library/PrivateFrameworks' -isysroot'/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk' -F'/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/System/Library/PrivateFrameworks'   -fsigned-char  -O3 -DNDEBUG \n    C++ flags (Debug):           -isysroot'/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk' -F'/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/System/Library/PrivateFrameworks' -isysroot'/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk' -F'/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/System/Library/PrivateFrameworks'   -fsigned-char  -g \n    C Compiler:                  /AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Toolchains/iOS27.0.xctoolchain/usr/bin/clang\n    C flags (Release):           -isysroot'/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk' -F'/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/System/Library/PrivateFrameworks' -isysroot'/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk' -F'/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/System/Library/PrivateFrameworks'   -fsigned-char  -O3 -DNDEBUG \n    C flags (Debug):             -isysroot'/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk' -F'/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/System/Library/PrivateFrameworks' -isysroot'/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk' -F'/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/System/Library/PrivateFrameworks'   -fsigned-char  -g \n    Linker flags (Release):\n    Linker flags (Debug):\n    ccache:                      NO\n    Precompiled headers:         NO\n    Extra dependencies:          /AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/lib/libz.tbd -framework Accelerate -framework CoreGraphics -framework QuartzCore -framework AssetsLibrary -framework UIKit\n    3rdparty dependencies:       libjpeg libpng\n\n  OpenCV modules:\n    To be built:                 core imgcodecs imgproc\n    Disabled:                    -\n    Disabled by dependency:      -\n    Unavailable:                 -\n    Applications:                -\n    Documentation:               NO\n    Non-free algorithms:         NO\n\n  GUI: \n    Cocoa:                       YES\n\n  Media I/O: \n    ZLib:                        /AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/lib/libz.tbd (ver 1.2.12)\n    JPEG:                        build (ver 90)\n    PNG:                         build (ver 1.6.34)\n\n  Video I/O:\n    AVFoundation:                YES\n\n  Parallel framework:            GCD\n\n  Trace:                         YES (built-in)\n\n  Other third-party libraries:\n    Custom HAL:                  NO\n\n  Python (for build):            NO\n\n  Install to:                    /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/Measure/install/TempContent/Objects/opencv/build/build-arm64e-iphoneos/install\n-----------------------------------------------------------------\n\n"
- "$__lazy_storage_$_segmentationBufferToViewportTransform"
- "$__lazy_storage_$_skViewToSegmentationBuffer"
- "$__lazy_storage_$_viewportToSK"
- "$__lazy_storage_$_viewportToSegmentationBufferTransform"
- "$__lazy_storage_$_visionToViewport"
- "Approval Required"
- "Ask for Approval"
- "Ask for Approval Again"
- "Measure has been updated."
- "This Measure update has new features. You'll need approval from your parent or guardian to continue using the app."
- "You'll be able to use Measure after your parent or guardian approves your request."
- "[AMSKit] Significant change enabled, evaluating for version "
```
