thisdir = class/System.Data.DataSetExtensions
SUBDIRS = 
include ../../build/rules.make

LIBRARY = System.Data.DataSetExtensions.dll

LIB_REFS = System.Core System System.Data System.Xml
KEYFILE = ../ecma.pub
LIB_MCS_FLAGS = -nowarn:436 -d:COREFX

TEST_MCS_FLAGS = $(LIB_MCS_FLAGS) -nowarn:219 -nowarn:169 $(NUNIT_RESOURCE_FILES:%=/resource:%)

EXTRA_DISTFILES = $(RESOURCE_FILES) \
	Test/System.Data/testdataset1.xml

RESX_RESOURCE_STRING = \
	../../../external/corefx/src/System.Data.DataSetExtensions/src/Resources/Strings.resx

include ../../build/library.make
