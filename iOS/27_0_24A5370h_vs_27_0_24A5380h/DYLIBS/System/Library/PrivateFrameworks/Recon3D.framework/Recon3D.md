## Recon3D

> `/System/Library/PrivateFrameworks/Recon3D.framework/Recon3D`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x171ef90` | `0x17059b4` | **`-0x195dc`** |
| `__TEXT.__gcc_except_tab` | `0xed98c` | `0xebcf8` | **`-0x1c94`** |
| `__TEXT.__const` | `0x1135f0` | `0x112110` | **`-0x14e0`** |
| `__TEXT.__unwind_info` | `0x37220` | `0x36f90` | **`-0x290`** |
| `__AUTH_CONST.__const` | `0x60aa8` | `0x609d0` | **`-0xd8`** |
| `__TEXT.__eh_frame` | `0xb34` | `0xbfc` | **`+0xc8`** |
| `__DATA.__common` | `0x7a8` | `0x848` | **`+0xa0`** |
| `__DATA_DIRTY.__bss` | `0x3f60` | `0x3ec0` | **`-0xa0`** |
| `__TEXT.__cstring` | `0x4d48f` | `0x4d400` | **`-0x8f`** |
| `__AUTH.__data` | `0x10` | `0x20` | **`+0x10`** |
| `__DATA_DIRTY.__data` | `0x68` | `0x58` | **`-0x10`** |
| `__AUTH_CONST.__auth_got` | `0x1638` | `0x1630` | **`-0x8`** |

### Other Changes

```diff

-9.26.6.1.0
+9.26.6.16.1

-  Functions: 38096
-  Symbols:   1892
-  CStrings:  6733
+  Functions: 38035
+  Symbols:   1894
+  CStrings:  6734
Symbols:
+ __ZNKSt3__119bad_expected_accessIvE4whatEv
+ __ZTINSt3__119bad_expected_accessIvEE
CStrings:
+ "%d [%t] %p %c: %m%n"
+ "(null)"
+ "another file exporter already exists at the same location"
+ "static auto cv3d::esn::TypeNameHelpers::PrettyArgName() [T = cv3d::kit::concurrency::ChannelOutput<std::expected<cv3d::recon::frame::KeyframeData, cv3d::esn::Error>>]"
+ "static auto cv3d::esn::TypeNameHelpers::PrettyArgName() [T = cv3d::kit::concurrency::ChannelOutput<std::expected<std::shared_ptr<const cv3d::recon::kfplanes::PlaneDetectionResult>, cv3d::esn::Error>>]"
+ "static auto cv3d::esn::TypeNameHelpers::PrettyArgName() [T = cv3d::kit::concurrency::ChannelOutput<std::expected<std::shared_ptr<cv3d::recon::kf::KeyframeEngineResult>, cv3d::esn::Error>>]"
+ "static auto cv3d::esn::TypeNameHelpers::PrettyArgName() [T = cv3d::kit::concurrency::OptionalReturn<cv3d::recon::sng::MeshingNodeMeshUpdateResult> (const std::expected<std::shared_ptr<const cv3d::recon::kfplanes::PlaneDetectionResult>, cv3d::esn::Error> &)]"
+ "static auto cv3d::esn::TypeNameHelpers::PrettyArgName() [T = cv3d::kit::concurrency::OptionalReturn<cv3d::recon::sng::MeshingNodeMeshUpdateResult> (cv3d::kit::concurrency::ChannelLimitedInput<std::expected<std::shared_ptr<cv3d::recon::kf::KeyframeEngineResult>, cv3d::esn::Error>, 1>)]"
+ "static auto cv3d::esn::TypeNameHelpers::PrettyArgName() [T = std::expected<cv3d::recon::frame::KeyframeData, cv3d::esn::Error> (const cv3d::esn::random::UUID &)]"
+ "static auto cv3d::esn::TypeNameHelpers::PrettyArgName() [T = std::expected<cv3d::recon::frame::KeyframeData, cv3d::esn::Error>]"
+ "static auto cv3d::esn::TypeNameHelpers::PrettyArgName() [T = std::expected<std::shared_ptr<const cv3d::recon::kfplanes::PlaneDetectionResult>, cv3d::esn::Error> (const std::expected<std::shared_ptr<cv3d::recon::kf::KeyframeEngineResult>, cv3d::esn::Error> &)]"
+ "static auto cv3d::esn::TypeNameHelpers::PrettyArgName() [T = std::expected<std::shared_ptr<const cv3d::recon::kfplanes::PlaneDetectionResult>, cv3d::esn::Error> (const std::expected<std::shared_ptr<cv3d::recon::sng::KeyframeEngineResultSync>, cv3d::esn::Error> &)]"
+ "static auto cv3d::esn::TypeNameHelpers::PrettyArgName() [T = std::expected<std::shared_ptr<const cv3d::recon::kfplanes::PlaneDetectionResult>, cv3d::esn::Error>]"
+ "static auto cv3d::esn::TypeNameHelpers::PrettyArgName() [T = std::expected<std::shared_ptr<cv3d::recon::kf::KeyframeEngineResult>, cv3d::esn::Error> (const cv3d::recon::frame::FrameBundle &)]"
+ "static auto cv3d::esn::TypeNameHelpers::PrettyArgName() [T = std::expected<std::shared_ptr<cv3d::recon::kf::KeyframeEngineResult>, cv3d::esn::Error> (const cv3d::recon::sng::FrameBundleSync &)]"
+ "static auto cv3d::esn::TypeNameHelpers::PrettyArgName() [T = std::expected<std::shared_ptr<cv3d::recon::kf::KeyframeEngineResult>, cv3d::esn::Error>]"
- " : %.*s"
- "%s: %s:%d"
- "static auto cv3d::esn::TypeNameHelpers::PrettyArgName() [T = cv3d::kit::concurrency::ChannelOutput<std::experimental::expected<cv3d::recon::frame::KeyframeData, cv3d::esn::Error>>]"
- "static auto cv3d::esn::TypeNameHelpers::PrettyArgName() [T = cv3d::kit::concurrency::ChannelOutput<std::experimental::expected<std::shared_ptr<const cv3d::recon::kfplanes::PlaneDetectionResult>, cv3d::esn::Error>>]"
- "static auto cv3d::esn::TypeNameHelpers::PrettyArgName() [T = cv3d::kit::concurrency::ChannelOutput<std::experimental::expected<std::shared_ptr<cv3d::recon::kf::KeyframeEngineResult>, cv3d::esn::Error>>]"
- "static auto cv3d::esn::TypeNameHelpers::PrettyArgName() [T = cv3d::kit::concurrency::OptionalReturn<cv3d::recon::sng::MeshingNodeMeshUpdateResult> (const std::experimental::expected<std::shared_ptr<const cv3d::recon::kfplanes::PlaneDetectionResult>, cv3d::esn::Error> &)]"
- "static auto cv3d::esn::TypeNameHelpers::PrettyArgName() [T = cv3d::kit::concurrency::OptionalReturn<cv3d::recon::sng::MeshingNodeMeshUpdateResult> (cv3d::kit::concurrency::ChannelLimitedInput<std::experimental::expected<std::shared_ptr<cv3d::recon::kf::KeyframeEngineResult>, cv3d::esn::Error>, 1>)]"
- "static auto cv3d::esn::TypeNameHelpers::PrettyArgName() [T = std::experimental::expected<cv3d::recon::frame::KeyframeData, cv3d::esn::Error> (const cv3d::esn::random::UUID &)]"
- "static auto cv3d::esn::TypeNameHelpers::PrettyArgName() [T = std::experimental::expected<cv3d::recon::frame::KeyframeData, cv3d::esn::Error>]"
- "static auto cv3d::esn::TypeNameHelpers::PrettyArgName() [T = std::experimental::expected<std::shared_ptr<const cv3d::recon::kfplanes::PlaneDetectionResult>, cv3d::esn::Error> (const std::experimental::expected<std::shared_ptr<cv3d::recon::kf::KeyframeEngineResult>, cv3d::esn::Error> &)]"
- "static auto cv3d::esn::TypeNameHelpers::PrettyArgName() [T = std::experimental::expected<std::shared_ptr<const cv3d::recon::kfplanes::PlaneDetectionResult>, cv3d::esn::Error> (const std::experimental::expected<std::shared_ptr<cv3d::recon::sng::KeyframeEngineResultSync>, cv3d::esn::Error> &)]"
- "static auto cv3d::esn::TypeNameHelpers::PrettyArgName() [T = std::experimental::expected<std::shared_ptr<const cv3d::recon::kfplanes::PlaneDetectionResult>, cv3d::esn::Error>]"
- "static auto cv3d::esn::TypeNameHelpers::PrettyArgName() [T = std::experimental::expected<std::shared_ptr<cv3d::recon::kf::KeyframeEngineResult>, cv3d::esn::Error> (const cv3d::recon::frame::FrameBundle &)]"
- "static auto cv3d::esn::TypeNameHelpers::PrettyArgName() [T = std::experimental::expected<std::shared_ptr<cv3d::recon::kf::KeyframeEngineResult>, cv3d::esn::Error> (const cv3d::recon::sng::FrameBundleSync &)]"
- "static auto cv3d::esn::TypeNameHelpers::PrettyArgName() [T = std::experimental::expected<std::shared_ptr<cv3d::recon::kf::KeyframeEngineResult>, cv3d::esn::Error>]"
```
