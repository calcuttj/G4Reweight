#------------------------------------------------------------------------------
# CMakeLists.txt
# Module : G4emhighenergy
# Package: Geant4.src.G4processes.G4electromagnetic.G4emhighenergy
#
# CMakeLists.txt for building a single granular library.
#
# Generated on : 24/9/2010
#
# $Id: CMakeLists.txt 66816 2013-01-12 16:13:54Z gcosmo $
#
#------------------------------------------------------------------------------

if(GEANT4_BUILD_GRANULAR_LIBS)
    include(Geant4MacroLibraryTargets)
    GEANT4_GRANULAR_LIBRARY_TARGET(COMPONENT sources.cmake)
endif()

