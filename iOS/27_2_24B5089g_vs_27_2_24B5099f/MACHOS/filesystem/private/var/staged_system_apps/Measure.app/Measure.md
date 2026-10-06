## Measure

> `/private/var/staged_system_apps/Measure.app/Measure`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3aa754` | `0x3aa874` | **`+0x120`** |
| `__TEXT.__objc_methname` | `0x14145` | `0x141b5` | **`+0x70`** |
| `__TEXT.__eh_frame` | `0x2d58` | `0x2d80` | **`+0x28`** |
| `__DATA.__objc_const` | `0x14c90` | `0x14cb0` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x7d60` | `0x7d80` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0xac84` | `0xaca4` | **`+0x20`** |
| `__TEXT.__auth_stubs` | `0x4a00` | `0x4a10` | **`+0x10`** |
| `__TEXT.__objc_methtype` | `0x5278` | `0x5288` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x97f0` | `0x9800` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x85b4` | `0x85c0` | **`+0xc`** |
| `__DATA.__objc_data` | `0x9a08` | `0x9a10` | **`+0x8`** |
| `__DATA.__objc_selrefs` | `0x35c0` | `0x35c8` | **`+0x8`** |
| `__DATA_CONST.__auth_got` | `0x2510` | `0x2518` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_stublist`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__cstring`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__init_offsets`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-196.40.1.0.0
+196.40.3.0.0

-  Functions: 10783
-  Symbols:   2322
-  CStrings:  6320
+  Functions: 10784
+  Symbols:   2323
+  CStrings:  6321
Symbols:
+ _$s17MeasureFoundation24ComputedCameraPropertiesV12updateShared_12viewportSize17viewRotationAngleySo7ARFrameC_s5SIMD2VySfG12CoreGraphics7CGFloatVtFZ
+ _$s17MeasureFoundation24ComputedCameraPropertiesV6camera12viewportSize17viewRotationAngleACSo8ARCameraC_s5SIMD2VySfG12CoreGraphics7CGFloatVtcfC
+ _$s17MeasureFoundation9SceneViewPAAE17viewRotationAngle7orUsing12CoreGraphics7CGFloatVSo22UIInterfaceOrientationV_tF
- _$s17MeasureFoundation24ComputedCameraPropertiesV12updateShared_12viewportSize11orientationySo7ARFrameC_s5SIMD2VySfGSo22UIInterfaceOrientationVtFZ
- _$s17MeasureFoundation24ComputedCameraPropertiesV6camera12viewportSize11orientationACSo8ARCameraC_s5SIMD2VySfGSo22UIInterfaceOrientationVtcfC
CStrings:
+ "\nGeneral configuration for OpenCV 3.4.0 =====================================\n  Version control:               unknown\n\n  Platform:\n    Timestamp:                   2026-09-28T09:27:38Z\n    Host:                        Darwin 10.0 x86_64\n    Target:                      Darwin 16.0.0 arm\n    CMake:                       4.0.3\n    CMake generator:             Xcode\n    CMake build tool:            /AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/usr/bin/xcodebuild\n    Xcode:                       27.0\n\n  CPU/HW features:\n    Baseline:\n      requested:                 DETECT\n\n  C/C++:\n    Built as dynamic libs?:      NO\n    C++11:                       YES\n    C++ Compiler:                /AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Toolchains/iOS27.2.xctoolchain/usr/bin/clang++  (ver 21.0.0.21000401)\n    C++ flags (Release):         -isysroot'/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk' -F'/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/System/Library/PrivateFrameworks' -isysroot'/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk' -F'/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/System/Library/PrivateFrameworks'   -fsigned-char  -O3 -DNDEBUG \n    C++ flags (Debug):           -isysroot'/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk' -F'/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/System/Library/PrivateFrameworks' -isysroot'/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk' -F'/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/System/Library/PrivateFrameworks'   -fsigned-char  -g \n    C Compiler:                  /AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Toolchains/iOS27.2.xctoolchain/usr/bin/clang\n    C flags (Release):           -isysroot'/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk' -F'/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/System/Library/PrivateFrameworks' -isysroot'/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk' -F'/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/System/Library/PrivateFrameworks'   -fsigned-char  -O3 -DNDEBUG \n    C flags (Debug):             -isysroot'/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk' -F'/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/System/Library/PrivateFrameworks' -isysroot'/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk' -F'/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/System/Library/PrivateFrameworks'   -fsigned-char  -g \n    Linker flags (Release):\n    Linker flags (Debug):\n    ccache:                      NO\n    Precompiled headers:         NO\n    Extra dependencies:          /AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/usr/lib/libz.tbd -framework Accelerate -framework CoreGraphics -framework QuartzCore -framework AssetsLibrary -framework UIKit\n    3rdparty dependencies:       libjpeg libpng\n\n  OpenCV modules:\n    To be built:                 core imgcodecs imgproc\n    Disabled:                    -\n    Disabled by dependency:      -\n    Unavailable:                 -\n    Applications:                -\n    Documentation:               NO\n    Non-free algorithms:         NO\n\n  GUI: \n    Cocoa:                       YES\n\n  Media I/O: \n    ZLib:                        /AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/usr/lib/libz.tbd (ver 1.2.12)\n    JPEG:                        build (ver 90)\n    PNG:                         build (ver 1.6.34)\n\n  Video I/O:\n    AVFoundation:                YES\n\n  Parallel framework:            GCD\n\n  Trace:                         YES (built-in)\n\n  Other third-party libraries:\n    Custom HAL:                  NO\n\n  Python (for build):            NO\n\n  Install to:                    /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/Measure/install/TempContent/Objects/opencv/build/build-iphoneos/install\n-----------------------------------------------------------------\n\n"
+ "setNeedsUpdateOfSupportedInterfaceOrientations"
+ "verticalBarUndoButtonItem"
- "\nGeneral configuration for OpenCV 3.4.0 =====================================\n  Version control:               unknown\n\n  Platform:\n    Timestamp:                   2026-09-12T19:11:54Z\n    Host:                        Darwin 10.0 x86_64\n    Target:                      Darwin 16.0.0 arm\n    CMake:                       4.0.3\n    CMake generator:             Xcode\n    CMake build tool:            /AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/usr/bin/xcodebuild\n    Xcode:                       27.0\n\n  CPU/HW features:\n    Baseline:\n      requested:                 DETECT\n\n  C/C++:\n    Built as dynamic libs?:      NO\n    C++11:                       YES\n    C++ Compiler:                /AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Toolchains/iOS27.2.xctoolchain/usr/bin/clang++  (ver 21.0.0.21000334)\n    C++ flags (Release):         -isysroot'/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk' -F'/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/System/Library/PrivateFrameworks' -isysroot'/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk' -F'/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/System/Library/PrivateFrameworks'   -fsigned-char  -O3 -DNDEBUG \n    C++ flags (Debug):           -isysroot'/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk' -F'/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/System/Library/PrivateFrameworks' -isysroot'/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk' -F'/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/System/Library/PrivateFrameworks'   -fsigned-char  -g \n    C Compiler:                  /AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Toolchains/iOS27.2.xctoolchain/usr/bin/clang\n    C flags (Release):           -isysroot'/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk' -F'/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/System/Library/PrivateFrameworks' -isysroot'/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk' -F'/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/System/Library/PrivateFrameworks'   -fsigned-char  -O3 -DNDEBUG \n    C flags (Debug):             -isysroot'/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk' -F'/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/System/Library/PrivateFrameworks' -isysroot'/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk' -F'/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/System/Library/PrivateFrameworks'   -fsigned-char  -g \n    Linker flags (Release):\n    Linker flags (Debug):\n    ccache:                      NO\n    Precompiled headers:         NO\n    Extra dependencies:          /AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/usr/lib/libz.tbd -framework Accelerate -framework CoreGraphics -framework QuartzCore -framework AssetsLibrary -framework UIKit\n    3rdparty dependencies:       libjpeg libpng\n\n  OpenCV modules:\n    To be built:                 core imgcodecs imgproc\n    Disabled:                    -\n    Disabled by dependency:      -\n    Unavailable:                 -\n    Applications:                -\n    Documentation:               NO\n    Non-free algorithms:         NO\n\n  GUI: \n    Cocoa:                       YES\n\n  Media I/O: \n    ZLib:                        /AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/usr/lib/libz.tbd (ver 1.2.12)\n    JPEG:                        build (ver 90)\n    PNG:                         build (ver 1.6.34)\n\n  Video I/O:\n    AVFoundation:                YES\n\n  Parallel framework:            GCD\n\n  Trace:                         YES (built-in)\n\n  Other third-party libraries:\n    Custom HAL:                  NO\n\n  Python (for build):            NO\n\n  Install to:                    /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/Measure/install/TempContent/Objects/opencv/build/build-iphoneos/install\n-----------------------------------------------------------------\n\n"
- "didPressUndo"
```
