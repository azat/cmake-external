
CMake modules
============

    - AddCompilerFlags (Follow http://www.cmake.org/Wiki/CMakeMacroParseArguments convention)
        AddCompilerFlags([FAIL_ON_ERROR ]FLAGS flag1[ flagN] LANGUAGES C[ CXX])

    - AddFilesGlobRecursiveToList
    - FindLibrariesOrFatalError
    - FindLibraryOrFatalError
    - FindIconv (look in libc and for libiconv)
    - GitVersion
    - JoinArguments - breaking overly long lines without creating a list

TODO
====
    Take a look at - http://www.cmake.org/Wiki/CMakeMacroParseArguments

