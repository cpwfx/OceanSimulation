make_library()

include_directories(
    ${PLOG_INCLUDE_DIR}
    ${GLM_INCLUDE_DIR}
    ${OPENGL_INCLUDE_DIR}
    ${GLFW_INCLUDE_DIR}
    ${GLAD_INCLUDE_DIR}
    ${FREETYPE_INCLUDE_DIRS}
    )

target_link_libraries(${PROJECT}
    MathLib
    FftLib
    GraphicsLib
    )
