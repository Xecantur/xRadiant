OBJS=ChunkyTriMesh.cpp RecastAlloc.cpp RecastArea.cpp RecastContour.cpp Recast.cpp RecastFilter.cpp RecastLayers.cpp RecastMesh.cpp RecastMeshDetail.cpp RecastRasterization.cpp RecastRegion.cpp
OBJNAME=librecast
VERSION=1.0
CFLAGS= -Wall
LFLAGS= -shared -fPIC

all:
	g++ ${OBJS} -o ${OBJNAME}-${VERSION}.so ${CFLAGS} ${LFLAGS}
	mv ${OBJNAME}-${VERSION}.so ../../
