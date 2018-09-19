# u-boot-tiny210
1th:make smdkv210_config
2th:make spl/u-boot-spl.bin
3th:make -j4
then :
prepare a sd card,use dd_for_windows to write image to sd
3.1:write u-boot-spl.bin to start of 1 block
3.2:write u-boot.bin to start of 32 block
