sedit '16,17d' COLLADABaseUtils/include/COLLADABUPcreCompiledPattern.h &&
sedit '16i #include "pcre.h"' COLLADABaseUtils/include/COLLADABUPcreCompiledPattern.h &&

OPTS+=" -DUSE_STATIC=0 -DUSE_SHARED=1 -DCMAKE_POLICY_VERSION_MINIMUM=3.5" &&

default_cmake_build &&

ld_add /usr/lib/opencollada
