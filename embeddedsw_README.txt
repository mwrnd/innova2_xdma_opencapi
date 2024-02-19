This directory contains the files from github.com/Xilinx/embeddedsw
necessary to implement IIC (I2C) over XDMA

No changes were made to the files from Commit c9a0ee3, tag xilinx_v2023.2, Oct. 17, 2023
https://github.com/Xilinx/embeddedsw/releases/tag/xilinx_v2023.2
https://github.com/Xilinx/embeddedsw/tree/c9a0ee31b2a14cbcfcb56ca369037319b4ad4847

All included files are licensed under the MIT License:
https://github.com/Xilinx/embeddedsw/blob/c9a0ee31b2a14cbcfcb56ca369037319b4ad4847/license.txt

with the exception of print.c which is BSD 2-Clause:
https://github.com/Xilinx/embeddedsw/blob/c9a0ee31b2a14cbcfcb56ca369037319b4ad4847/lib/bsp/standalone/src/common/print.c#L5


Directories and files:

embeddedsw/lib/bsp/standalone/src/common
embeddedsw/XilinxProcessorIPLib/drivers/common/src
embeddedsw/XilinxProcessorIPLib/drivers/iic/src


embeddedsw/license.txt
embeddedsw/README.txt

embeddedsw/lib/bsp/standalone/src/common/CMakeLists.txt
embeddedsw/lib/bsp/standalone/src/common/inbyte.c
embeddedsw/lib/bsp/standalone/src/common/outbyte.c
embeddedsw/lib/bsp/standalone/src/common/pm_api_version.h
embeddedsw/lib/bsp/standalone/src/common/print.c
embeddedsw/lib/bsp/standalone/src/common/sleep.h
embeddedsw/lib/bsp/standalone/src/common/xbasic_types.h
embeddedsw/lib/bsp/standalone/src/common/xdebug.h
embeddedsw/lib/bsp/standalone/src/common/xenv.h
embeddedsw/lib/bsp/standalone/src/common/xenv_standalone.h
embeddedsw/lib/bsp/standalone/src/common/xil_assert.c
embeddedsw/lib/bsp/standalone/src/common/xil_assert.h
embeddedsw/lib/bsp/standalone/src/common/xil_cache_vxworks.h
embeddedsw/lib/bsp/standalone/src/common/xil_cryptoalginfo.h
embeddedsw/lib/bsp/standalone/src/common/xil_hal.h
embeddedsw/lib/bsp/standalone/src/common/xil_io.h
embeddedsw/lib/bsp/standalone/src/common/xil_macroback.h
embeddedsw/lib/bsp/standalone/src/common/xil_mem.c
embeddedsw/lib/bsp/standalone/src/common/xil_mem.h
embeddedsw/lib/bsp/standalone/src/common/xil_printf.c
embeddedsw/lib/bsp/standalone/src/common/xil_printf.h
embeddedsw/lib/bsp/standalone/src/common/xil_sleepcommon.c
embeddedsw/lib/bsp/standalone/src/common/xil_testcache.c
embeddedsw/lib/bsp/standalone/src/common/xil_testcache.h
embeddedsw/lib/bsp/standalone/src/common/xil_testio.c
embeddedsw/lib/bsp/standalone/src/common/xil_testio.h
embeddedsw/lib/bsp/standalone/src/common/xil_testmem.c
embeddedsw/lib/bsp/standalone/src/common/xil_testmem.h
embeddedsw/lib/bsp/standalone/src/common/xil_types.h
embeddedsw/lib/bsp/standalone/src/common/xil_util.c
embeddedsw/lib/bsp/standalone/src/common/xil_util.h
embeddedsw/lib/bsp/standalone/src/common/xplatform_info.c
embeddedsw/lib/bsp/standalone/src/common/xplatform_info.h
embeddedsw/lib/bsp/standalone/src/common/xpm_init.c
embeddedsw/lib/bsp/standalone/src/common/xpm_init.h
embeddedsw/lib/bsp/standalone/src/common/xstatus.h

embeddedsw/XilinxProcessorIPLib/drivers/common/src/CMakeLists.txt
embeddedsw/XilinxProcessorIPLib/drivers/common/src/Makefile
embeddedsw/XilinxProcessorIPLib/drivers/common/src/xbasic_types.c
embeddedsw/XilinxProcessorIPLib/drivers/common/src/xbasic_types.h
embeddedsw/XilinxProcessorIPLib/drivers/common/src/xdebug.h
embeddedsw/XilinxProcessorIPLib/drivers/common/src/xenv.h
embeddedsw/XilinxProcessorIPLib/drivers/common/src/xenv_linux.h
embeddedsw/XilinxProcessorIPLib/drivers/common/src/xenv_none.h
embeddedsw/XilinxProcessorIPLib/drivers/common/src/xenv_standalone.h
embeddedsw/XilinxProcessorIPLib/drivers/common/src/xenv_vxworks.h
embeddedsw/XilinxProcessorIPLib/drivers/common/src/xparameters.h
embeddedsw/XilinxProcessorIPLib/drivers/common/src/xstatus.h
embeddedsw/XilinxProcessorIPLib/drivers/common/src/xutil.h
embeddedsw/XilinxProcessorIPLib/drivers/common/src/xutil_memtest.c
embeddedsw/XilinxProcessorIPLib/drivers/common/src/xversion.c
embeddedsw/XilinxProcessorIPLib/drivers/common/src/xversion.h

embeddedsw/XilinxProcessorIPLib/drivers/iic/src/CMakeLists.txt
embeddedsw/XilinxProcessorIPLib/drivers/iic/src/Makefile
embeddedsw/XilinxProcessorIPLib/drivers/iic/src/xiic.c
embeddedsw/XilinxProcessorIPLib/drivers/iic/src/xiic_dyn_master.c
embeddedsw/XilinxProcessorIPLib/drivers/iic/src/xiic_g.c
embeddedsw/XilinxProcessorIPLib/drivers/iic/src/xiic.h
embeddedsw/XilinxProcessorIPLib/drivers/iic/src/xiic_i.h
embeddedsw/XilinxProcessorIPLib/drivers/iic/src/xiic_intr.c
embeddedsw/XilinxProcessorIPLib/drivers/iic/src/xiic_l.c
embeddedsw/XilinxProcessorIPLib/drivers/iic/src/xiic_l.h
embeddedsw/XilinxProcessorIPLib/drivers/iic/src/xiic_master.c
embeddedsw/XilinxProcessorIPLib/drivers/iic/src/xiic_multi_master.c
embeddedsw/XilinxProcessorIPLib/drivers/iic/src/xiic_options.c
embeddedsw/XilinxProcessorIPLib/drivers/iic/src/xiic_selftest.c
embeddedsw/XilinxProcessorIPLib/drivers/iic/src/xiic_sinit.c
embeddedsw/XilinxProcessorIPLib/drivers/iic/src/xiic_slave.c
embeddedsw/XilinxProcessorIPLib/drivers/iic/src/xiic_stats.c

