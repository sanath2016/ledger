include(GNUInstallDirs)

if(CMAKE_INSTALL_DATAROOTDIR)

  install(DIRECTORY "${CMAKE_CURRENT_SOURCE_DIR}"
    DESTINATION "${CMAKE_INSTALL_DATAROOTDIR}"
    USE_SOURCE_PERMISSIONS
    PATTERN CMakeLists.txt EXCLUDE)

endif(CMAKE_INSTALL_DATAROOTDIR)
