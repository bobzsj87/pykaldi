[mkl]
library_dirs = /opt/intel/mkl/lib/intel64
include_dirs = /opt/intel/mkl/include
mkl_libs = mkl_rt



LD_PRELOAD=/opt/intel/mkl/lib/intel64/libmkl_def.so:/opt/intel/mkl/lib/intel64/libmkl_avx2.so
LD_PRELOAD=/opt/intel/mkl/lib/intel64/libmkl_rt.so