# 
#  Copyright 2007 LAAS-CNRS
#  Author: Florent Lamiraux
# 

lib_LTLIBRARIES = libhppModel.la
libhppModel_la_SOURCES = \
	hppHumanoidRobot.cpp \
	hppDevice.cpp \
	hppBody.cpp \
	hppJoint.cpp 

libhppModel_la_LDFLAGS = \
	$(JRL_DYNAMICS_LIBS)$ 	\
	$(KINEOCONTROLLER_LIBS)$ 	\
	$(KWSIO_LIBS)			\
	-release ${PACKAGE_VERSION}

libhppModel_la_CPPFLAGS = \
	-I$(top_srcdir)/include \
	-I$(top_builddir)/include \
	$(JRL_DYNAMICS_CFLAGS)$ \
	$(KINEOCONTROLLER_CFLAGS)$ \
	$(KWSIO_CFLAGS)
