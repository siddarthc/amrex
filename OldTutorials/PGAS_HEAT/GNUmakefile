# AMREX_HOME defines the directory in which we will find all the BoxLib code
# If you set AMREX_HOME as an environment variable, this line will be ignored
AMREX_HOME = ../..

DEBUG     = FALSE
USE_MPI3  = TRUE
USE_UPCXX = TRUE
USE_OMP   = FALSE
PROFILE   = FALSE
COMP      = g++
DIM       = 3
PRECISION = DOUBLE
EBASE     = Heat

include ./Make.package

include $(AMREX_HOME)/Tools/GNUMake/Make.defs

include $(AMREX_HOME)/Src/Base/Make.package

include $(AMREX_HOME)/Tools/GNUMake/Make.rules
