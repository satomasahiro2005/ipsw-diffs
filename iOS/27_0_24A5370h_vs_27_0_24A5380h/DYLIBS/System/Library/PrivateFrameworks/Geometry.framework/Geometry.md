## Geometry

> `/System/Library/PrivateFrameworks/Geometry.framework/Geometry`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0x50` | `0x1ae0` | **`+0x1a90`** |
| `__DATA_DIRTY.__objc_data` | `0x1a40` | `—` | **`-0x1a40`** |
| `__TEXT.__text` | `0x1c0078` | `0x1c0674` | **`+0x5fc`** |
| `__AUTH_CONST.__objc_const` | `0x2fd0` | `0x3060` | **`+0x90`** |
| `__TEXT.__unwind_info` | `0x78f0` | `0x7968` | **`+0x78`** |
| `__TEXT.__const` | `0x15fe8` | `0x16048` | **`+0x60`** |
| `__TEXT.__gcc_except_tab` | `0x15dc` | `0x1638` | **`+0x5c`** |
| `__TEXT.__objc_methlist` | `0x1298` | `0x12d0` | **`+0x38`** |
| `__AUTH_CONST.__auth_got` | `0x6e8` | `0x708` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x498` | `0x4b8` | **`+0x20`** |
| `__TEXT.__eh_frame` | `0xf20` | `0xf38` | **`+0x18`** |
| `__DATA.__data` | `0x1868` | `0x1870` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x2a8` | `0x2b0` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x2a8` | `0x2b0` | **`+0x8`** |

### Other Changes

```diff

-67.0.1.0.0
+67.0.2.0.0

-  Functions: 9589
-  Symbols:   10296
+  Functions: 9626
+  Symbols:   10341
Symbols:
+ +[OS_geom_mp_build_box_options new]
+ -[OS_geom_mp_build_box_options dealloc]
+ -[OS_geom_mp_build_box_options init]
+ GCC_except_table18
+ GCC_except_table25
+ _CFArrayAppendValue
+ _CFArrayCreateMutable
+ _OBJC_CLASS_$_NSArray
+ _OBJC_CLASS_$_OS_geom_mp_build_box_options
+ _OBJC_METACLASS_$_OS_geom_mp_build_box_options
+ __OBJC_$_CLASS_METHODS_OS_geom_mp_build_box_options
+ __OBJC_$_INSTANCE_METHODS_OS_geom_mp_build_box_options
+ __OBJC_CLASS_RO_$_OS_geom_mp_build_box_options
+ __OBJC_METACLASS_RO_$_OS_geom_mp_build_box_options
+ __Z31geom_mp_build_box_options_classv
+ __Z35geom_mp_build_box_options_obj_allocv
+ __ZN4geom2mp12_GLOBAL__N_17addGridERNS1_8MeshDataERKDv3_fS6_S6_S6_RKDv2_fRKfjj
+ __ZN4geom2mp30sanitizeSplitToSourceVertexMapERNS0_9index_mapEjj
+ __ZNSt3__16vectorIN4geom2mp4meshENS_9allocatorIS3_EEE16__destroy_vectorclB9fqn220106Ev
+ _geom_mp_build_box_options_create
+ _geom_mp_build_box_options_get_add_normals
+ _geom_mp_build_box_options_get_add_uvs
+ _geom_mp_build_box_options_get_corner_radius
+ _geom_mp_build_box_options_get_corner_segment_count
+ _geom_mp_build_box_options_get_depth
+ _geom_mp_build_box_options_get_depth_segment_count
+ _geom_mp_build_box_options_get_height
+ _geom_mp_build_box_options_get_height_segment_count
+ _geom_mp_build_box_options_get_merge_vertices
+ _geom_mp_build_box_options_get_non_overlapping_uvs
+ _geom_mp_build_box_options_get_width
+ _geom_mp_build_box_options_get_width_segment_count
+ _geom_mp_build_box_options_set_add_normals
+ _geom_mp_build_box_options_set_add_uvs
+ _geom_mp_build_box_options_set_corner_radius
+ _geom_mp_build_box_options_set_corner_segment_count
+ _geom_mp_build_box_options_set_depth
+ _geom_mp_build_box_options_set_depth_segment_count
+ _geom_mp_build_box_options_set_height
+ _geom_mp_build_box_options_set_height_segment_count
+ _geom_mp_build_box_options_set_merge_vertices
+ _geom_mp_build_box_options_set_non_overlapping_uvs
+ _geom_mp_build_box_options_set_width
+ _geom_mp_build_box_options_set_width_segment_count
+ _geom_mp_mesh_create_box
+ _geom_mp_mesh_create_box_sides
+ _kCFAllocatorDefault
+ _kCFTypeArrayCallBacks
+ _swift_dynamicCastObjCClass
- GCC_except_table16
- GCC_except_table19
- GCC_except_table34
- __ZN4geom2mp12_GLOBAL__N_17addGridERNS1_8MeshDataERKDv3_fS6_S6_S6_jj
```
