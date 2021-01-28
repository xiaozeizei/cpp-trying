
BUILD_PATH=./build
INCLUDE_PATH=./include
SRC_PATH=./src




all: ${BUILD_PATH}/hello
.PHONY: all 
# hello: ${BUILD_PATH}/hello

${BUILD_PATH}/hello: ${INCLUDE_PATH}/common.h ${SRC_PATH}/hello.cpp
	clang++  ${SRC_PATH}/hello.cpp -I${INCLUDE_PATH} -o ${BUILD_PATH}/hello

.PHONY: clean
clean:
	rm -rf ${BUILD_PATH}/*

