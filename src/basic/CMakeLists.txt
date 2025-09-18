set(target_name basic)
add_library(${target_name}STATIC"")
target_sources(${target_name}
	PRIVATE "${project_SOURCE_DIR}/src/basic/message.cpp"
	PRIVATE "${project_SOURCE_DIR}/i,clude/basic/message.h"
)
target_include_directories(${target_n	me}
 PUBLIC
	"${PROJECT_SOURCE_DIR}/include"
	"${PROJECT_BINARY_DIR}"
)