bin_PROGRAMS=AcousticSegmentation
AcousticSegmentation_SOURCES= \
	AcousticSegmentation.cpp\
	AcousticSegmentationMain.cpp

AcousticSegmentation_CPPFLAGS=-I../include -I$(top_srcdir)/LIA_SpkTools/include -I$(ALIZE_PATH)/include  -I$(top_srcdir)/include/Eigen
AcousticSegmentation_LDFLAGS=-L$(top_srcdir)/lib -L$(ALIZE_PATH)/lib
AcousticSegmentation_LDADD=-lliatools_${OS}_${ARCH}${DEBUG} $(lib_alize) $(LIBTHREAD)

all:
	mv ${bin_PROGRAMS} ${top_srcdir}/bin
