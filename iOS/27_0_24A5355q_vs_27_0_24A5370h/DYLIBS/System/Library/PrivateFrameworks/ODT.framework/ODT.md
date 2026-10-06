## ODT

> `/System/Library/PrivateFrameworks/ODT.framework/ODT`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4c5c7c` | `0x522cf8` | **`+0x5d07c`** |
| `__TEXT.__gcc_except_tab` | `0x1dcb8` | `0x23d08` | **`+0x6050`** |
| `__TEXT.__const` | `0x2a750` | `0x2dca8` | **`+0x3558`** |
| `__AUTH_CONST.__const` | `0x17210` | `0x1a370` | **`+0x3160`** |
| `__TEXT.__cstring` | `0xfa61` | `0x11ca2` | **`+0x2241`** |
| `__TEXT.__unwind_info` | `0xb738` | `0xd350` | **`+0x1c18`** |
| `__TEXT.__eh_frame` | `0x1700` | `0xd90` | **`-0x970`** |
| `__DATA.__bss` | `0x9b0` | `0xe98` | **`+0x4e8`** |
| `__TEXT.__oslogstring` | `0x894` | `0x954` | **`+0xc0`** |
| `__AUTH_CONST.__auth_got` | `0xf40` | `0xfd0` | **`+0x90`** |
| `__DATA.__data` | `0x220` | `0x280` | **`+0x60`** |
| `__AUTH.__thread_vars` | `0x18` | `0x48` | **`+0x30`** |
| `__AUTH.__thread_bss` | `0x8` | `0x18` | **`+0x10`** |
| `__DATA.__common` | `0x70` | `0x80` | **`+0x10`** |

### Other Changes

```diff

-21.0.0.0.0
+24.6.0.0.0

-  Functions: 9830
-  Symbols:   717
-  CStrings:  1564
+  Functions: 10720
+  Symbols:   735
+  CStrings:  1675
Symbols:
+ _CFDictionaryCreate
+ _IOSurfaceGetID
+ __ZNSt3__118condition_variable15__do_timed_waitERNS_11unique_lockINS_5mutexEEENS_6chrono10time_pointINS5_12system_clockENS5_8durationIxNS_5ratioILl1ELl1000000000EEEEEEE
+ __ZNSt3__118condition_variable4waitERNS_11unique_lockINS_5mutexEEE
+ __ZNSt3__121recursive_timed_mutex4lockEv
+ __ZNSt3__121recursive_timed_mutex6unlockEv
+ __ZNSt3__121recursive_timed_mutexC1Ev
+ __ZNSt3__121recursive_timed_mutexD1Ev
+ __ZNSt3__16chrono12system_clock3nowEv
+ __ZNSt3__16thread4joinEv
+ __ZNSt3__17promiseIvE10get_futureEv
+ __ZNSt3__17promiseIvEC1Ev
+ _dispatch_time
+ _e5rt_e5_compiler_options_set_experimental_match_e5_minimal_cpu_patterns_for_states
+ _e5rt_execution_stream_operation_get_inout_names
+ _e5rt_execution_stream_operation_get_num_inouts
+ _e5rt_execution_stream_operation_retain_inout_port
+ _objc_release_x26
+ _objc_retain_x26
+ _pthread_getname_np
+ _pthread_self
+ _pthread_setname_np
+ _vImageScale_CbCr8
+ _vImageScale_Planar8
- __ZNSt3__115recursive_mutex4lockEv
- __ZNSt3__115recursive_mutex6unlockEv
- __ZNSt3__115recursive_mutexC1Ev
- __ZNSt3__115recursive_mutexD1Ev
- _objc_release_x25
- _objc_retain_x25
CStrings:
+ " (inouts). Model input ports: ["
+ " : %.*s"
+ " allocating buffer for inout: "
+ " binding inout buffer: "
+ " characters, but has "
+ " getting tensor size for inout: "
+ " model inouts but received "
+ " retaining inout port: "
+ " retaining tensor desc for inout: "
+ "%s: %s:%d"
+ "' is out of range [0,"
+ "' too long. Must have at most "
+ "'. Thread already has name '"
+ "'. Use allow_overwrite=true to replace name."
+ "((std::is_same_v<UT, uint8_t> && data_type == BufferDataType::Uint8) || (std::is_same_v<UT, uint16_t> && data_type == BufferDataType::Uint16) || (std::is_same_v<UT, half> && data_type == BufferDataType::Float16) || (std::is_same_v<UT, float> && data_type == BufferDataType::Float32))"
+ "(params.inputs.size() + params.inouts.size()) >= 1"
+ ". Model inouts ports: ["
+ ". Model output ports: ["
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/ODT/library/Kit/IOSurface/src/IOSurfaceRef_maybe_mno_unaligned_access.cpp"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/ODT/library/Kit/Image/src/ImageStorage.cpp"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/ODT/library/Kit/ML/src/Private/EspressoV2ModelInstance_maybe_mno_unaligned_access.mm"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/ODT/library/Kit/Memory/include_private/Kit/Memory/ProtectedMemoryPrivate.h"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/ODT/library/VIO/Geometry/include/VIO/Geometry/RANSAC/DataPointCorrespondenceUtil.h"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/ODT/library/VIO/Geometry/include/VIO/Geometry/RANSAC/Model/ResectionModel.h"
+ "Cannot nest CallProtected with different memory access implementations"
+ "Cannot set thread name '"
+ "CbCr"
+ "CopyViewsProtected: protected copy failed"
+ "Failed to capture stack pointer"
+ "Failed to convert bundle URL to string"
+ "Invalid inout: The given view for inout "
+ "ODT: ChildSurfaceCache (%s) exceeded max size (%zu), surfaces are not being recycled as expected"
+ "ODT: PixelBufferViewCache exceeded max size (%zu), surfaces are not being recycled as expected"
+ "Only Gray8u, Gray16u, Gray16f, and Gray32f input tensors supported"
+ "The DataView does not contain uint16 data"
+ "Thread name '"
+ "Unable to retain inout port: "
+ "ValidViewStructure<uint8_t>(Structure(inout))"
+ "Y"
+ "cam_to_base_poses.size() == 2"
+ "circular_queue"
+ "circular_queue_"
+ "correspondences.size() >= SampleSize"
+ "format.Contains(FormatFlags::UINT16)"
+ "idx * 2 + 1 < xs.size()"
+ "idx * 3 + 2 < Xs.size()"
+ "idx < p_->GetCachedBaseAddresses().size()"
+ "inout.Format().IsValidFormat()"
+ "inout__"
+ "io"
+ "result"
+ "sp != nullptr"
+ "static auto cv3d::esn::TypeNameHelpers::PrettyArgName() [T = cv3d::kit::img::ArrayImageBuffer<Format::Abgr16f>]"
+ "static auto cv3d::esn::TypeNameHelpers::PrettyArgName() [T = cv3d::kit::img::ArrayImageBuffer<Format::Abgr16u>]"
+ "static auto cv3d::esn::TypeNameHelpers::PrettyArgName() [T = cv3d::kit::img::ArrayImageBuffer<Format::Abgr32f>]"
+ "static auto cv3d::esn::TypeNameHelpers::PrettyArgName() [T = cv3d::kit::img::ArrayImageBuffer<Format::Abgr8u>]"
+ "static auto cv3d::esn::TypeNameHelpers::PrettyArgName() [T = cv3d::kit::img::ArrayImageBuffer<Format::Argb16f>]"
+ "static auto cv3d::esn::TypeNameHelpers::PrettyArgName() [T = cv3d::kit::img::ArrayImageBuffer<Format::Argb16u>]"
+ "static auto cv3d::esn::TypeNameHelpers::PrettyArgName() [T = cv3d::kit::img::ArrayImageBuffer<Format::Argb32f>]"
+ "static auto cv3d::esn::TypeNameHelpers::PrettyArgName() [T = cv3d::kit::img::ArrayImageBuffer<Format::Argb8u>]"
+ "static auto cv3d::esn::TypeNameHelpers::PrettyArgName() [T = cv3d::kit::img::ArrayImageBuffer<Format::Bgr16f>]"
+ "static auto cv3d::esn::TypeNameHelpers::PrettyArgName() [T = cv3d::kit::img::ArrayImageBuffer<Format::Bgr16u>]"
+ "static auto cv3d::esn::TypeNameHelpers::PrettyArgName() [T = cv3d::kit::img::ArrayImageBuffer<Format::Bgr32f>]"
+ "static auto cv3d::esn::TypeNameHelpers::PrettyArgName() [T = cv3d::kit::img::ArrayImageBuffer<Format::Bgr8u>]"
+ "static auto cv3d::esn::TypeNameHelpers::PrettyArgName() [T = cv3d::kit::img::ArrayImageBuffer<Format::Bgra16f>]"
+ "static auto cv3d::esn::TypeNameHelpers::PrettyArgName() [T = cv3d::kit::img::ArrayImageBuffer<Format::Bgra16u>]"
+ "static auto cv3d::esn::TypeNameHelpers::PrettyArgName() [T = cv3d::kit::img::ArrayImageBuffer<Format::Bgra32f>]"
+ "static auto cv3d::esn::TypeNameHelpers::PrettyArgName() [T = cv3d::kit::img::ArrayImageBuffer<Format::Bgra8u>]"
+ "static auto cv3d::esn::TypeNameHelpers::PrettyArgName() [T = cv3d::kit::img::ArrayImageBuffer<Format::Four16f>]"
+ "static auto cv3d::esn::TypeNameHelpers::PrettyArgName() [T = cv3d::kit::img::ArrayImageBuffer<Format::Four16u>]"
+ "static auto cv3d::esn::TypeNameHelpers::PrettyArgName() [T = cv3d::kit::img::ArrayImageBuffer<Format::Four32f>]"
+ "static auto cv3d::esn::TypeNameHelpers::PrettyArgName() [T = cv3d::kit::img::ArrayImageBuffer<Format::Four8u>]"
+ "static auto cv3d::esn::TypeNameHelpers::PrettyArgName() [T = cv3d::kit::img::ArrayImageBuffer<Format::Gray16f>]"
+ "static auto cv3d::esn::TypeNameHelpers::PrettyArgName() [T = cv3d::kit::img::ArrayImageBuffer<Format::Gray16u>]"
+ "static auto cv3d::esn::TypeNameHelpers::PrettyArgName() [T = cv3d::kit::img::ArrayImageBuffer<Format::Gray32f>]"
+ "static auto cv3d::esn::TypeNameHelpers::PrettyArgName() [T = cv3d::kit::img::ArrayImageBuffer<Format::Rgb16f>]"
+ "static auto cv3d::esn::TypeNameHelpers::PrettyArgName() [T = cv3d::kit::img::ArrayImageBuffer<Format::Rgb16u>]"
+ "static auto cv3d::esn::TypeNameHelpers::PrettyArgName() [T = cv3d::kit::img::ArrayImageBuffer<Format::Rgb32f>]"
+ "static auto cv3d::esn::TypeNameHelpers::PrettyArgName() [T = cv3d::kit::img::ArrayImageBuffer<Format::Rgb8u>]"
+ "static auto cv3d::esn::TypeNameHelpers::PrettyArgName() [T = cv3d::kit::img::ArrayImageBuffer<Format::Rgba16f>]"
+ "static auto cv3d::esn::TypeNameHelpers::PrettyArgName() [T = cv3d::kit::img::ArrayImageBuffer<Format::Rgba16u>]"
+ "static auto cv3d::esn::TypeNameHelpers::PrettyArgName() [T = cv3d::kit::img::ArrayImageBuffer<Format::Rgba32f>]"
+ "static auto cv3d::esn::TypeNameHelpers::PrettyArgName() [T = cv3d::kit::img::ArrayImageBuffer<Format::Rgba8u>]"
+ "static auto cv3d::esn::TypeNameHelpers::PrettyArgName() [T = cv3d::kit::img::ArrayImageBuffer<Format::Three16f>]"
+ "static auto cv3d::esn::TypeNameHelpers::PrettyArgName() [T = cv3d::kit::img::ArrayImageBuffer<Format::Three16u>]"
+ "static auto cv3d::esn::TypeNameHelpers::PrettyArgName() [T = cv3d::kit::img::ArrayImageBuffer<Format::Three32f>]"
+ "static auto cv3d::esn::TypeNameHelpers::PrettyArgName() [T = cv3d::kit::img::ArrayImageBuffer<Format::Three8u>]"
+ "static auto cv3d::esn::TypeNameHelpers::PrettyArgName() [T = cv3d::kit::img::ArrayImageBuffer<Format::Two16f>]"
+ "static auto cv3d::esn::TypeNameHelpers::PrettyArgName() [T = cv3d::kit::img::ArrayImageBuffer<Format::Two16u>]"
+ "static auto cv3d::esn::TypeNameHelpers::PrettyArgName() [T = cv3d::kit::img::ArrayImageBuffer<Format::Two32f>]"
+ "static auto cv3d::esn::TypeNameHelpers::PrettyArgName() [T = cv3d::kit::img::ArrayImageBuffer<Format::Two8u>]"
+ "static auto cv3d::esn::TypeNameHelpers::PrettyArgName() [T = cv3d::kit::img::ArrayImageBuffer<cv3d::kit::img::Format::Gray8u>]"
+ "static auto cv3d::esn::TypeNameHelpers::PrettyArgName() [T = cv3d::kit::img::Format::Abgr16f]"
+ "static auto cv3d::esn::TypeNameHelpers::PrettyArgName() [T = cv3d::kit::img::Format::Abgr16u]"
+ "static auto cv3d::esn::TypeNameHelpers::PrettyArgName() [T = cv3d::kit::img::Format::Abgr32f]"
+ "static auto cv3d::esn::TypeNameHelpers::PrettyArgName() [T = cv3d::kit::img::Format::Argb16f]"
+ "static auto cv3d::esn::TypeNameHelpers::PrettyArgName() [T = cv3d::kit::img::Format::Argb32f]"
+ "static auto cv3d::esn::TypeNameHelpers::PrettyArgName() [T = cv3d::kit::img::Format::Bgr16f]"
+ "static auto cv3d::esn::TypeNameHelpers::PrettyArgName() [T = cv3d::kit::img::Format::Bgr16u]"
+ "static auto cv3d::esn::TypeNameHelpers::PrettyArgName() [T = cv3d::kit::img::Format::Bgr32f]"
+ "static auto cv3d::esn::TypeNameHelpers::PrettyArgName() [T = cv3d::kit::img::Format::Bgra16f]"
+ "static auto cv3d::esn::TypeNameHelpers::PrettyArgName() [T = cv3d::kit::img::Format::Bgra16u]"
+ "static auto cv3d::esn::TypeNameHelpers::PrettyArgName() [T = cv3d::kit::img::Format::Four16f]"
+ "static auto cv3d::esn::TypeNameHelpers::PrettyArgName() [T = cv3d::kit::img::Format::Four16u]"
+ "static auto cv3d::esn::TypeNameHelpers::PrettyArgName() [T = cv3d::kit::img::Format::Four32f]"
+ "static auto cv3d::esn::TypeNameHelpers::PrettyArgName() [T = cv3d::kit::img::Format::Four8u]"
+ "static auto cv3d::esn::TypeNameHelpers::PrettyArgName() [T = cv3d::kit::img::Format::Rgb16f]"
+ "static auto cv3d::esn::TypeNameHelpers::PrettyArgName() [T = cv3d::kit::img::Format::Rgb32f]"
+ "static auto cv3d::esn::TypeNameHelpers::PrettyArgName() [T = cv3d::kit::img::Format::Rgba16u]"
+ "static auto cv3d::esn::TypeNameHelpers::PrettyArgName() [T = cv3d::kit::img::Format::Three16f]"
+ "static auto cv3d::esn::TypeNameHelpers::PrettyArgName() [T = cv3d::kit::img::Format::Three16u]"
+ "static auto cv3d::esn::TypeNameHelpers::PrettyArgName() [T = cv3d::kit::img::Format::Three32f]"
+ "static auto cv3d::esn::TypeNameHelpers::PrettyArgName() [T = cv3d::kit::img::Format::Three8u]"
+ "static auto cv3d::esn::TypeNameHelpers::PrettyArgName() [T = cv3d::kit::img::Format::Two16u]"
+ "unique_lock::lock: already locked"
+ "unique_lock::lock: references null mutex"
+ "unique_lock::unlock: not locked"
+ "vImage scale failed."
+ "xs.size() / 2 == pt_to_cam_map.size()"
- " : "
- "((std::is_same_v<UT, uint8_t> && data_type == BufferDataType::Uint8) || (std::is_same_v<UT, half> && data_type == BufferDataType::Float16) || (std::is_same_v<UT, float> && data_type == BufferDataType::Float32))"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/ODT/library/Kit/IOSurface/src/IOSurfaceRef.cpp"
- "HeatMaps"
- "HeatMapsCompressed"
- "Only Gray8u and Gray32f input tensors supported"
- "Runtime error"
- "idx < p_->GetCachedBaseAddress().size()"
```
