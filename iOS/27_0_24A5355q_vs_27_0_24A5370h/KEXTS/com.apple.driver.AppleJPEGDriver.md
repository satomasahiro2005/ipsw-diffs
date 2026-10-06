## com.apple.driver.AppleJPEGDriver

> `com.apple.driver.AppleJPEGDriver`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__auth_stubs` | `0x0` | `0x680` | **`+0x680`** |
| `__TEXT_EXEC.__text` | `0x2b1c4` | `0x2b56c` | **`+0x3a8`** |

### Other Changes

```diff

-8.1.0.0.0
+8.1.3.0.0
Functions:
~ sub_fffffff0090103ec -> sub_fffffff00903e70c : 132 -> 128
~ sub_fffffff009012d74 -> sub_fffffff009041090 : 84 -> 100
~ sub_fffffff009012dc8 -> sub_fffffff0090410f4 : 84 -> 100
~ sub_fffffff009012e1c -> sub_fffffff009041158 : 172 -> 216
~ sub_fffffff009013134 -> sub_fffffff00904149c : 268 -> 264
~ __ZN15AppleJPEGDriver10getCPUTypeEv : 432 -> 436
~ sub_fffffff00901487c -> sub_fffffff009042be4 : 248 -> 264
~ __ZN15AppleJPEGDriver15finish_io_gatedEP11JpegRequestijb : 1324 -> 1676
~ sub_fffffff009017cd4 -> sub_fffffff0090461ac : 340 -> 348
~ sub_fffffff009017e28 -> sub_fffffff009046308 : 324 -> 344
~ __ZN15AppleJPEGDriver14queue_io_gatedEP11JpegRequest : 1660 -> 1828
~ sub_fffffff009019188 -> sub_fffffff009047724 : 388 -> 376
~ __ZN15AppleJPEGDriver15startEncoderExtEP27_AppleJPEGDriverIOStructExtS1_P8ipc_portP12IOUserClientP4task : 1112 -> 1120
~ __ZN15AppleJPEGDriver16startEncoder2024EP28_AppleJPEGDriverIOStruct2024S1_P8ipc_portP12IOUserClientP4task : 1232 -> 1240
~ sub_fffffff00901b270 -> sub_fffffff009049810 : 204 -> 200
~ __os_log_internal : 340 -> 336
~ sub_fffffff00901d4cc -> sub_fffffff00904ba64 : 232 -> 256
~ sub_fffffff00901d63c -> sub_fffffff00904bbec : 184 -> 188
~ sub_fffffff00901e058 -> sub_fffffff00904c60c : 304 -> 328
~ sub_fffffff00901e9a0 -> sub_fffffff00904cf6c : 160 -> 176
~ sub_fffffff00901f200 -> sub_fffffff00904d7dc : 156 -> 172
~ sub_fffffff00901fabc -> sub_fffffff00904e0a8 : 160 -> 176
~ sub_fffffff009020318 -> sub_fffffff00904e914 : 156 -> 172
~ sub_fffffff009020bc0 -> sub_fffffff00904f1cc : 232 -> 256
~ sub_fffffff009021464 -> sub_fffffff00904fa88 : 156 -> 172
~ sub_fffffff0090222cc -> sub_fffffff009050900 : 184 -> 188
~ sub_fffffff009022c98 -> sub_fffffff0090512d0 : 236 -> 260
~ sub_fffffff009023558 -> sub_fffffff009051ba8 : 160 -> 176
~ sub_fffffff009025238 -> sub_fffffff009053898 : 644 -> 656
~ __ZN12AppleJPEGHal25enableDeviceClockLowLevelEbj : 348 -> 344
~ sub_fffffff009026130 -> sub_fffffff009054798 : 40 -> 36
~ sub_fffffff00902ac24 -> sub_fffffff009059288 : 156 -> 172
~ sub_fffffff00902bb80 -> sub_fffffff00905a1f4 : 160 -> 176
~ sub_fffffff00902ee00 -> sub_fffffff00905d484 : 184 -> 188
~ sub_fffffff00903293c -> sub_fffffff009060fc4 : 192 -> 200
~ sub_fffffff0090332f4 -> sub_fffffff009061984 : 228 -> 252
~ __ZN25AppleJPEGWrapperControlV813jpeg_qtbl_setEiNSt3__14spanIKtLm18446744073709551615EEE : 184 -> 188
~ sub_fffffff0090372ec -> sub_fffffff009065998 : 408 -> 404
~ sub_fffffff009037c40 -> sub_fffffff0090662e8 : 232 -> 256
~ __ZN15RequestHandling19matrixConvYUVtoRGBAEP13ajpeg_setup_t : 272 -> 280
~ sub_fffffff009037ec0 -> sub_fffffff009066588 : 248 -> 236
~ __ZN15RequestHandling20decodeHWRequestSetupEP11JpegRequest : 1536 -> 1540
~ __ZN15RequestHandling20encodeHWRequestSetupEP11JpegRequest : 1860 -> 1868
```
