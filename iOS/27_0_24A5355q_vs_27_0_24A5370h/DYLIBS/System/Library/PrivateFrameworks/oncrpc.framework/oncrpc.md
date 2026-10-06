## oncrpc

> `/System/Library/PrivateFrameworks/oncrpc.framework/oncrpc`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x13600` | `0x1362c` | **`+0x2c`** |

### Other Changes

```diff

-93.0.0.0.0
+94.0.0.0.0
Functions:
~ __newrpclib_clnt_multicasts_buf_timeout : 2048 -> 2052
~ _clnt_sperror_r : 556 -> 576
~ __newrpclib_clnt_sperrno : 60 -> 68
~ __newrpclib_clnt_perrno : 72 -> 80
~ __newrpclib_clnt_spcreateerror : 420 -> 428
~ __svcauth_unix : 392 -> 400
~ _xdrrec_putbytes : 164 -> 168
~ _get_input_bytes : 196 -> 200
~ _realloc_stream : 120 -> 124
~ __newrpclib_xdr_union : 184 -> 168
~ __newrpclib_xdr_string : 304 -> 300
~ _search_local_ifaddr_cache : 984 -> 992
~ __newrpclib_socparms2netid : 232 -> 228
~ __newrpclib_netid2socparms : 216 -> 236
~ _ugetport : 272 -> 256
~ _getnetconfigent : 204 -> 200
~ _compare_sa : 372 -> 364
```
