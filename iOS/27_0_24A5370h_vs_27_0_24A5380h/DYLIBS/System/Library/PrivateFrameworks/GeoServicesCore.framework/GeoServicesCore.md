## GeoServicesCore

> `/System/Library/PrivateFrameworks/GeoServicesCore.framework/GeoServicesCore`

### Other Changes

```diff

-2073.30.6.5.1
+2075.30.6.12.3
Functions:
~ _geo_dispatch_queue_create_with_qos -> -[geo_state_capture_handle dealloc] : 128 -> 80
~ _GEOUnregisterStateCaptureLegacy -> -[geo_state_capture_handle .cxx_destruct] : 228 -> 88
~ -[geo_state_capture_handle dealloc] -> _geo_dispatch_queue_create_with_qos : 80 -> 128
~ -[geo_state_capture_handle .cxx_destruct] -> _GEOUnregisterStateCaptureLegacy : 88 -> 228
```
