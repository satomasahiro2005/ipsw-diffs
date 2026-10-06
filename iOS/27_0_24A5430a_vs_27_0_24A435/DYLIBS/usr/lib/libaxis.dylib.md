## libaxis.dylib

> `/usr/lib/libaxis.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x55abc8` | `0x55aff8` | **`+0x430`** |

### Other Changes

```text
Functions:
~ sub_2c040e714 -> sub_2c0f52714 : 1480 -> 1500
~ sub_2c040f9d8 -> sub_2c0f539ec : 2928 -> 2912
~ sub_2c0411900 -> sub_2c0f55904 : 816 -> 820
~ sub_2c0416224 -> sub_2c0f5a22c : 912 -> 900
~ sub_2c04165b4 -> sub_2c0f5a5b0 : 912 -> 900
~ sub_2c0418380 -> sub_2c0f5c370 : 2940 -> 2944
~ __ZN5terra14MeshValidation7is_2p5dERKNS_5TMeshEPNSt3__16vectorINS0_15ValidationErrorENS4_9allocatorIS6_EEEE : 6696 -> 6700
~ __ZN5terra14MeshValidation24get_connected_componentsERKNS_5TMeshE : 3032 -> 3004
~ sub_2c041efc0 -> sub_2c0f62f9c : 460 -> 472
~ __ZN5terra14MeshValidation11is_manifoldERKNSt3__16vectorIdNS1_9allocatorIdEEEERKNS2_IiNS3_IiEEEEPNS2_INS0_15ValidationErrorENS3_ISC_EEEE : 7108 -> 7120
~ sub_2c0426ccc -> sub_2c0f6acc0 : 3344 -> 3312
~ sub_2c0427ad0 -> sub_2c0f6baa4 : 308 -> 312
~ sub_2c0427c04 -> sub_2c0f6bbdc : 388 -> 392
~ sub_2c0427ee0 -> sub_2c0f6bebc : 2292 -> 2228
~ sub_2c042b34c -> sub_2c0f6f2e8 : 4336 -> 4252
~ sub_2c042c43c -> sub_2c0f70384 : 4880 -> 4860
~ sub_2c042d81c -> sub_2c0f71750 : 2292 -> 2228
~ sub_2c042e110 -> sub_2c0f72004 : 236 -> 240
~ sub_2c042e3fc -> sub_2c0f722f4 : 852 -> 872
~ sub_2c04304d4 -> sub_2c0f743e0 : 336 -> 384
~ sub_2c043f0f8 -> sub_2c0f83034 : 48 -> 32
~ sub_2c043f128 -> sub_2c0f83054 : 24 -> 48
~ sub_2c043f140 -> sub_2c0f83084 : 20 -> 24
~ sub_2c043f154 -> sub_2c0f8309c : 28 -> 20
~ __ZN5terra10MeshRepair18repair_nonmanifoldEb : 8400 -> 8452
~ __ZN5terra10MeshRepair27count_high_valence_verticesEibRNSt3__16vectorINS_14MeshValidation15ValidationErrorENS1_9allocatorIS4_EEEE : 3252 -> 3260
~ __ZN5terra10MeshRepair19repair_high_valenceEib : 5608 -> 5612
~ __ZN5terra11MeshDensify7densifyERKNS_5TMeshEdb : 1648 -> 1656
~ sub_2c045bc18 -> sub_2c0f9fba0 : 1108 -> 1120
~ sub_2c045f168 -> sub_2c0fa30fc : 852 -> 872
~ sub_2c046046c -> sub_2c0fa4414 : 388 -> 392
~ __ZN5terra15Polygon3DMesher14get_tmesh_dataERKNS_9Polygon3DERNSt3__16vectorIdNS4_9allocatorIdEEEERNS5_IiNS6_IiEEEE : 4852 -> 4892
~ sub_2c0472148 -> sub_2c0fb611c : 1108 -> 1120
~ sub_2c04728ec -> sub_2c0fb68cc : 852 -> 872
~ sub_2c0473804 -> sub_2c0fb77f8 : 1500 -> 1520
~ sub_2c0474a08 -> sub_2c0fb8a10 : 852 -> 872
~ sub_2c0491c4c -> sub_2c0fd5c68 : 460 -> 456
~ sub_2c0492034 -> sub_2c0fd604c : 460 -> 456
~ sub_2c0493f0c -> sub_2c0fd7f20 : 1500 -> 1520
~ sub_2c0495110 -> sub_2c0fd9138 : 852 -> 872
~ __ZN5terra13MeshFlattener20refine_tnp_into_meshEv : 3192 -> 3160
~ __ZN5terra10Distance3D23get_intersection_pointsERKN4axis10Triangle2DES4_b : 1928 -> 1908
~ __ZN5terra10Distance3D16get_points_aboveERKNS_5TMeshES3_db : 1872 -> 1864
~ sub_2c04a1d84 -> sub_2c0fe5d84 : 5260 -> 5268
~ sub_2c04a5f08 -> sub_2c0fe9f10 : 932 -> 928
~ sub_2c04a64d4 -> sub_2c0fea4d8 : 412 -> 416
~ sub_2c04a8218 -> sub_2c0fec220 : 852 -> 872
~ __ZN5terra11MeshOverlay6refineERKN4axis10Geometry2DE : 2432 -> 2456
~ __ZN5terra11MeshOverlay19map_isolated_pointsERKN4axis10Geometry2DE : 1388 -> 1384
~ __ZN5terra11MeshOverlay22intersect_and_map_segsERKN4axis10Geometry2DE : 7348 -> 7316
~ sub_2c04b3d2c -> sub_2c0ff7d3c : 1488 -> 1492
~ sub_2c04b42fc -> sub_2c0ff8310 : 860 -> 852
~ __ZN5terra11IndexedMesh13collapse_edgeEiibb : 1660 -> 1652
~ __ZN5terra11IndexedMesh17is_collapse_legalEii : 3516 -> 3552
~ __ZN5terra11IndexedMesh14get_componentsERNSt3__16vectorIiNS1_9allocatorIiEEEE : 1276 -> 1292
~ __ZN5terra11IndexedMesh12get_boundaryEv : 2924 -> 2916
~ __ZN5terra5TMeshC2ERKNSt3__16vectorINS1_10shared_ptrIS0_EENS1_9allocatorIS4_EEEE : 1792 -> 1800
~ __ZNK5terra5TMesh12get_boundaryEv : 3668 -> 3660
~ __ZN5terra5TMesh11is_equal_nfERKS0_ : 644 -> 656
~ __ZNK5terra9GeoRasterIfE5splitEii : 1256 -> 1248
~ sub_2c04dffd4 -> sub_2c1024008 : 808 -> 788
~ sub_2c04e4b98 -> sub_2c1028bb8 : 4964 -> 4956
~ __ZN5terra19TriangulatedTerrain18assemble_from_meshERKNS_5TMeshE : 17508 -> 17436
~ sub_2c04f1bf0 -> sub_2c1035bc0 : 500 -> 516
~ sub_2c04f7370 -> sub_2c103b350 : 392 -> 368
~ sub_2c04fc694 -> sub_2c104065c : 1108 -> 1120
~ sub_2c04fcae8 -> sub_2c1040abc : 852 -> 872
~ sub_2c04fda00 -> sub_2c10419e8 : 1500 -> 1520
~ sub_2c04fec04 -> sub_2c1042c00 : 852 -> 872
~ sub_2c04ff90c -> sub_2c104391c : 852 -> 872
~ sub_2c0500448 -> sub_2c104446c : 376 -> 392
~ sub_2c0502118 -> sub_2c104614c : 288 -> 284
~ sub_2c050241c -> sub_2c104644c : 300 -> 296
~ sub_2c0507bb0 -> sub_2c104bbdc : 1500 -> 1520
~ sub_2c0508db4 -> sub_2c104cdf4 : 852 -> 872
~ sub_2c050a584 -> sub_2c104e5d8 : 404 -> 408
~ sub_2c050fa98 -> sub_2c1053af0 : 2072 -> 2084
~ sub_2c051109c -> sub_2c1055100 : 4192 -> 4196
~ sub_2c0552aa4 -> sub_2c1096b0c : 408 -> 396
~ sub_2c0566498 -> sub_2c10aa4f4 : 408 -> 396
~ sub_2c0568aec -> sub_2c10acb3c : 408 -> 396
~ sub_2c0576c40 -> sub_2c10bac84 : 2720 -> 2740
~ sub_2c05776e0 -> sub_2c10bb738 : 2720 -> 2740
~ sub_2c0578180 -> sub_2c10bc1ec : 2720 -> 2740
~ sub_2c057a320 -> sub_2c10be3a0 : 3084 -> 3088
~ sub_2c057af2c -> sub_2c10befb0 : 3084 -> 3088
~ sub_2c057bb38 -> sub_2c10bfbc0 : 3084 -> 3088
~ sub_2c057c920 -> sub_2c10c09ac : 21592 -> 21616
~ sub_2c0583c88 -> sub_2c10c7d2c : 608 -> 612
~ sub_2c0598fe0 -> sub_2c10dd088 : 5000 -> 5056
~ sub_2c05a096c -> sub_2c10e4a4c : 4684 -> 4668
~ sub_2c05a32c8 -> sub_2c10e7398 : 2712 -> 2704
~ sub_2c05a5364 -> sub_2c10e942c : 3576 -> 3580
~ sub_2c05a68fc -> sub_2c10ea9c8 : 3584 -> 3588
~ sub_2c05ad48c -> sub_2c10f155c : 1724 -> 1732
~ sub_2c05ae044 -> sub_2c10f211c : 852 -> 872
~ sub_2c05e2570 -> sub_2c112665c : 340 -> 348
~ sub_2c05e8078 -> sub_2c112c16c : 340 -> 348
~ sub_2c05e83ec -> sub_2c112c4e8 : 396 -> 404
~ sub_2c05e8b84 -> sub_2c112cc88 : 320 -> 328
~ sub_2c05e9a38 -> sub_2c112db44 : 4652 -> 4624
~ sub_2c05eb414 -> sub_2c112f504 : 852 -> 872
~ sub_2c05eb98c -> sub_2c112fa90 : 852 -> 872
~ sub_2c05f0d58 -> sub_2c1134e70 : 884 -> 896
~ sub_2c05f147c -> sub_2c11355a0 : 852 -> 872
~ sub_2c05f8f0c -> sub_2c113d044 : 3348 -> 3340
~ sub_2c05faaf8 -> sub_2c113ec28 : 3060 -> 3052
~ sub_2c05ff518 -> sub_2c1143640 : 456 -> 460
~ sub_2c05ff6e0 -> sub_2c114380c : 456 -> 460
~ sub_2c0608b10 -> sub_2c114cc40 : 648 -> 652
~ sub_2c060ebc0 -> sub_2c1152cf4 : 872 -> 880
~ sub_2c060ef28 -> sub_2c1153064 : 3084 -> 3056
~ sub_2c060ffa0 -> sub_2c11540c0 : 3320 -> 3332
~ sub_2c0612460 -> sub_2c115658c : 884 -> 892
~ sub_2c0613898 -> sub_2c11579cc : 3336 -> 3348
~ sub_2c061d3ac -> sub_2c11614ec : 3028 -> 3036
~ __ZN4axis10ClusteringILi2EE13dbscan_workerERKNS_12MultiPoint2DEdm : 2668 -> 2660
~ __ZN4axis10ClusteringILi3EE13dbscan_workerERKN5terra12MultiPoint3DEdm : 2980 -> 2984
~ sub_2c06802a8 -> sub_2c11c43ec : 924 -> 920
~ sub_2c06813f8 -> sub_2c11c5538 : 848 -> 852
~ sub_2c0681a44 -> sub_2c11c5b88 : 1052 -> 1048
~ sub_2c0682094 -> sub_2c11c61d4 : 388 -> 392
~ sub_2c0682774 -> sub_2c11c68b8 : 1880 -> 1884
~ sub_2c0682ecc -> sub_2c11c7014 : 1892 -> 1896
~ sub_2c0683630 -> sub_2c11c777c : 1892 -> 1896
~ sub_2c06845f4 -> sub_2c11c8744 : 848 -> 852
~ __ZN4axis8Stitcher6stitchERKNS_10Geometry2DE : 16632 -> 16640
~ sub_2c0688cc8 -> sub_2c11cce24 : 10952 -> 10960
~ sub_2c068b790 -> sub_2c11cf8f4 : 13004 -> 12980
~ sub_2c068ea5c -> sub_2c11d2ba8 : 6668 -> 6676
~ sub_2c0690c48 -> sub_2c11d4d9c : 6676 -> 6684
~ sub_2c0699ffc -> sub_2c11de158 : 7880 -> 7832
~ sub_2c06a90f4 -> sub_2c11ed220 : 7576 -> 7532
~ sub_2c06b2494 -> sub_2c11f6594 : 1288 -> 1312
~ sub_2c06b5af4 -> sub_2c11f9c0c : 1304 -> 1328
~ __ZN4axis10SliceDonut5sweepEv : 2820 -> 2796
~ __ZN4axis10SliceDonut10get_resultEv : 1776 -> 1772
~ __ZN4axis10SliceDonut24create_segs_and_verticesERKNS_9Polygon2DE : 1668 -> 1660
~ sub_2c06c29d0 -> sub_2c1206adc : 5520 -> 5524
~ sub_2c06c3f60 -> sub_2c1208070 : 1132 -> 1152
~ sub_2c06c9b88 -> sub_2c120dcac : 852 -> 856
~ sub_2c06cba60 -> sub_2c120fb88 : 1132 -> 1152
~ sub_2c06cc790 -> sub_2c12108cc : 3020 -> 2992
~ sub_2c06d1e34 -> sub_2c1215f54 : 324 -> 368
~ sub_2c06d4110 -> sub_2c121825c : 1644 -> 1636
~ sub_2c06d477c -> sub_2c12188c0 : 1644 -> 1636
~ sub_2c06d59a0 -> sub_2c1219adc : 2600 -> 2596
~ sub_2c06d81a4 -> sub_2c121c2dc : 2700 -> 2692
~ sub_2c06ec7f0 -> sub_2c1230920 : 416 -> 404
~ __ZN4axis19ConvexDecomposition27compute_exact_decompositionERKNS_9Polygon2DE : 2100 -> 2096
~ sub_2c06f23fc -> sub_2c123651c : 2208 -> 2292
~ __ZN4axis10MedialAxis30compute_simplified_medial_axisENSt3__110shared_ptrINS_9Polygon2DEEEdd : 11628 -> 11600
~ sub_2c07336e4 -> sub_2c127783c : 852 -> 872
~ sub_2c0743668 -> sub_2c12877d4 : 604 -> 608
~ sub_2c07523c4 -> sub_2c1296534 : 700 -> 720
~ sub_2c075c310 -> sub_2c12a0494 : 908 -> 900
~ sub_2c076f4f0 -> sub_2c12b366c : 1040 -> 1036
~ sub_2c0791914 -> sub_2c12d5a8c : 2116 -> 2120
~ sub_2c0798d9c -> sub_2c12dcf18 : 352 -> 360
~ sub_2c079e8f4 -> sub_2c12e2a78 : 2280 -> 2284
~ sub_2c079f1dc -> sub_2c12e3364 : 6540 -> 6516
~ sub_2c07a2b0c -> sub_2c12e6c7c : 612 -> 616
~ sub_2c07d0d00 -> sub_2c1314e74 : 852 -> 872
~ sub_2c07d3484 -> sub_2c131760c : 1288 -> 1292
~ sub_2c07d6efc -> sub_2c131b088 : 604 -> 608
~ sub_2c07da6d8 -> sub_2c131e868 : 852 -> 872
~ sub_2c07ded2c -> sub_2c1322ed0 : 1196 -> 1200
~ sub_2c07df228 -> sub_2c13233d0 : 1528 -> 1532
~ sub_2c07e5614 -> sub_2c13297c0 : 4524 -> 4504
~ sub_2c07e79bc -> sub_2c132bb54 : 852 -> 872
~ sub_2c07e7e18 -> sub_2c132bfc4 : 852 -> 872
~ __ZN4axis16PolylineSplitter22split_at_intersectionsERKNS_15MultiGeometry2DEd : 4048 -> 4052
~ sub_2c0803be0 -> sub_2c1347da4 : 600 -> 604
~ sub_2c0809528 -> sub_2c134d6f0 : 1320 -> 1340
~ sub_2c0809ab8 -> sub_2c134dc94 : 1220 -> 1232
~ sub_2c0813864 -> sub_2c1357a4c : 2116 -> 2120
~ __ZNK4axis4DCEL13extract_facesEv : 3660 -> 3600
~ __ZNK4axis4DCEL9write_wkbERNSt3__113basic_ostreamIcNS1_11char_traitsIcEEEE : 5220 -> 5244
~ sub_2c082910c -> sub_2c136d2d4 : 492 -> 488
~ sub_2c082e8bc -> sub_2c1372a80 : 852 -> 872
~ sub_2c0855578 -> sub_2c1399750 : 1108 -> 1120
~ sub_2c08559cc -> sub_2c1399bb0 : 852 -> 872
~ sub_2c085846c -> sub_2c139c664 : 2124 -> 2132
~ sub_2c0859dc0 -> sub_2c139dfc0 : 852 -> 872
~ sub_2c085aac8 -> sub_2c139ecdc : 488 -> 496
~ sub_2c085afd0 -> sub_2c139f1ec : 404 -> 416
~ sub_2c085ba68 -> sub_2c139fc90 : 812 -> 816
~ sub_2c085ce60 -> sub_2c13a108c : 488 -> 492
~ sub_2c085d048 -> sub_2c13a1278 : 2516 -> 2540
~ sub_2c085da1c -> sub_2c13a1c64 : 2656 -> 2684
~ sub_2c085e47c -> sub_2c13a26e0 : 736 -> 756
~ sub_2c085e8e8 -> sub_2c13a2b60 : 1452 -> 1404
~ sub_2c085f634 -> sub_2c13a387c : 1548 -> 1500
~ sub_2c08613e0 -> sub_2c13a55f8 : 852 -> 872
~ sub_2c0867c24 -> sub_2c13abe50 : 1600 -> 1620
~ sub_2c086ea94 -> sub_2c13b2cd4 : 1500 -> 1520
~ sub_2c0872b1c -> sub_2c13b6d70 : 1576 -> 1648
~ sub_2c0878048 -> sub_2c13bc2e4 : 852 -> 872
~ sub_2c0879328 -> sub_2c13bd5d8 : 1132 -> 1144
~ sub_2c087c22c -> sub_2c13c04e8 : 852 -> 872
~ sub_2c087d200 -> sub_2c13c14d0 : 2124 -> 2132
~ sub_2c087df2c -> sub_2c13c2204 : 852 -> 872
~ sub_2c088f08c -> sub_2c13d3378 : 852 -> 872
~ sub_2c088f7c4 -> sub_2c13d3ac4 : 852 -> 872
~ sub_2c088fefc -> sub_2c13d4210 : 852 -> 872
~ sub_2c08906ec -> sub_2c13d4a14 : 852 -> 872
~ sub_2c0890e24 -> sub_2c13d5160 : 852 -> 872
~ sub_2c089e084 -> sub_2c13e23d4 : 696 -> 700
~ sub_2c08b3918 -> sub_2c13f7c6c : 672 -> 676
~ sub_2c08bbed4 -> sub_2c140022c : 1364 -> 1368
~ sub_2c08bc428 -> sub_2c1400784 : 860 -> 852
~ __ZN4axis13CubicBezier2D19approximate_segmentERKNS_11PointData2DES3_S3_S3_dNSt3__110shared_ptrINS_10Polyline2DEEE : 1400 -> 1404
~ sub_2c08c48b8 -> sub_2c1408c10 : 852 -> 872
~ sub_2c08ca418 -> sub_2c140e784 : 924 -> 920
~ __ZN4axis8GeomUtilILm2EE13to_multipointENSt3__110shared_ptrINS_10Geometry2DEEE : 2360 -> 2352
~ __ZN4axis8GeomUtilILm3EE13to_multipointENSt3__110shared_ptrIN5terra10Geometry3DEEE : 2532 -> 2512
~ sub_2c08d9ac0 -> sub_2c141de0c : 4352 -> 4360
~ sub_2c08dc210 -> sub_2c1420564 : 1104 -> 1108
~ sub_2c08dc660 -> sub_2c14209b8 : 1096 -> 1088
~ sub_2c08df8c0 -> sub_2c1423c10 : 1496 -> 1504
~ sub_2c08e2174 -> sub_2c14264cc : 852 -> 872
~ sub_2c08e278c -> sub_2c1426af8 : 924 -> 920
~ sub_2c08eac10 -> sub_2c142ef78 : 924 -> 920
~ _axis_tiler_rasterize_ex1 : 1480 -> 1496
~ sub_2c08f5ef8 -> sub_2c143a26c : 320 -> 328
~ sub_2c090b1dc -> sub_2c144f558 : 4712 -> 4672
~ sub_2c090d27c -> sub_2c14515d0 : 4860 -> 4848
~ sub_2c0910988 -> sub_2c1454cd0 : 820 -> 824
~ sub_2c0910d60 -> sub_2c14550ac : 3052 -> 3112
~ sub_2c0914adc -> sub_2c1458e64 : 2412 -> 2400
~ sub_2c0915a58 -> sub_2c1459dd4 : 436 -> 468
~ sub_2c091cffc -> sub_2c1461398 : 148 -> 152
~ sub_2c091f2cc -> sub_2c146366c : 692 -> 700
~ sub_2c092007c -> sub_2c1464424 : 776 -> 780
~ sub_2c0920710 -> sub_2c1464abc : 3592 -> 3580
~ sub_2c0929720 -> sub_2c146dac0 : 20720 -> 20680
~ sub_2c0932b68 -> sub_2c1476ee0 : 1112 -> 1116
~ sub_2c093b718 -> sub_2c147fa94 : 20300 -> 20424
~ sub_2c0940eb8 -> sub_2c14852b0 : 600 -> 612
~ sub_2c094d3b8 -> sub_2c14917bc : 616 -> 620
~ sub_2c094d620 -> sub_2c1491a28 : 604 -> 624
~ sub_2c094e9b4 -> sub_2c1492dd0 : 1496 -> 1472
~ sub_2c0950ff8 -> sub_2c14953fc : 1296 -> 1340
~ sub_2c0951508 -> sub_2c1495938 : 760 -> 764
~ sub_2c09560bc -> sub_2c149a4f0 : 2696 -> 2704
~ sub_2c095716c -> sub_2c149b5a8 : 3404 -> 3384
~ sub_2c095cc10 -> sub_2c14a1038 : 536 -> 548
~ sub_2c095d230 -> sub_2c14a1664 : 1412 -> 1408
```
