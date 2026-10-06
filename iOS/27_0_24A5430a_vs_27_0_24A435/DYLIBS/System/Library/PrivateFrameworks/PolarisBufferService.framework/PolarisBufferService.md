## PolarisBufferService

> `/System/Library/PrivateFrameworks/PolarisBufferService.framework/PolarisBufferService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5d25c` | `0x5d288` | **`+0x2c`** |
| `__TEXT.__unwind_info` | `0x1d98` | `0x1d90` | **`-0x8`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff
Functions:
~ __ZN15PSBufferService11AtomicDeque23InitializeIntoRawBufferEPhj : 260 -> 268
~ __ZN15PSBufferService11AtomicDeque22FindMissingNodeInQueueERj : 180 -> 176
~ __ZN17PSAtomicWnRnArray9_clearIdxEmyPy : 216 -> 220
~ _OUTLINED_FUNCTION_8 -> _OUTLINED_FUNCTION_6 : 24 -> 16
~ _OUTLINED_FUNCTION_10 -> _OUTLINED_FUNCTION_8 : 20 -> 24
~ _ps_atomic_ringbuffer_writer_relinquish_entry : 184 -> 192
~ _ps_atomic_ringbuffer_reader_relinquish_entry : 184 -> 192
~ _ps_atomic_ringbuffer_handle_death : 200 -> 208
~ _ps_ringbuffer_allocate_closed : 224 -> 228
~ __ZN17PSAtomicWnRnArray18getReservationMaskEPy : 240 -> 248
~ _ps_atomic_ringbuffer_init : 332 -> 336
~ _ps_atomic_ringbuffer_writer_acquire_entry : 368 -> 356
~ _ps_atomic_ringbuffer_reader_acquire_entry : 276 -> 288
CStrings:
+ "16:12:08"
- "19:12:59"
```
