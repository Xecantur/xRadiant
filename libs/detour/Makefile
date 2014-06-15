OBJS=DebugDraw.cpp DetourAlloc.cpp DetourCommon.cpp DetourDebugDraw.cpp DetourNavMeshBuilder.cpp DetourNavMesh.cpp DetourNavMeshQuery.cpp DetourNode.cpp DetourPathCorridor.cpp DetourTileCacheBuilder.cpp DetourTileCache.cpp
OBJNAME=libdetour
VERSION=1.0
CFLAGS= -Wall
LFLAGS= -shared -fPIC

all:
	g++ ${OBJS} -o ${OBJNAME}-${VERSION}.so ${CFLAGS} ${LFLAGS}
	mv ${OBJNAME}-${VERSION}.so ../../
