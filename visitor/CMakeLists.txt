FILE(GLOB luasrc *.lua)
ADD_TORCH_PACKAGE(dp/visitor "${src}" "${luasrc}")
