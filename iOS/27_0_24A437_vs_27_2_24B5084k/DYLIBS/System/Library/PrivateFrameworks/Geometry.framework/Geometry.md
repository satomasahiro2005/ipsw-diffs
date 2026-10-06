## Geometry

> `/System/Library/PrivateFrameworks/Geometry.framework/Geometry`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1c1108` | `0x1c128c` | **`+0x184`** |
| `__TEXT.__cstring` | `0x16fc` | `0x172c` | **`+0x30`** |
| `__TEXT.__gcc_except_tab` | `0x1660` | `0x1670` | **`+0x10`** |

### Other Changes

```diff

-67.0.5.0.0
+67.40.1.0.0

-  CStrings:  190
+  CStrings:  191
Functions:
~ __ZN4geom2mp44add_vertex_face_adjacency_attributes_to_meshERNS0_4meshE : 548 -> 572
~ __ZN4geom2mp49remapVerticesOnVertexFaceAdjacencyTableAttributesERNS0_4meshERKS1_RKNS0_9index_mapE : 740 -> 780
~ __ZN4geom2mp25makeConditionedMeshForGPUERKNS0_4meshERS1_RNS0_9index_mapES6_RKNS0_24gpu_conditioning_optionsE : 2812 -> 3140
~ __ZN4geom2mp32compute_vertex_face_connectivityERKNS0_4meshERNSt3__16vectorIjNS4_9allocatorIjEEEES9_ : 680 -> 676
CStrings:
+ "Vertex-face adjacency table overflowed. "
```
