installdir = $(pkglibdir)/python/Plugins/SystemPlugins

SUBDIRS = SoftwareManager OSDPositionSetup NFIFlash PositionerSetup Satfinder \
	VideoTune Hotplug \
	DefaultServicesScanner CommonInterfaceAssignment \
	HdmiCEC VideoClippingSetup \
	VideoEnhancement WirelessLan NetworkWizard \
	SABnzbdSetup FastScan SatelliteEquipmentControl DiseqcTester

if DREAMBOX
SUBDIRS += FrontprocessorUpgrade NFIFlash
endif

if VUSOLO2
SUBDIRS += CableScan
endif

if VUSOLOSE
SUBDIRS += CableScan
endif

if VUDUO2
SUBDIRS += CableScan
endif

if VUUNO
SUBDIRS += CableScan
endif

if VUULTIMO
SUBDIRS += CableScan
endif

if VUSOLO4K
SUBDIRS += CableScan
endif

if VUUNO4K
SUBDIRS += CableScan
endif

if VUULTIMO4K
SUBDIRS += CableScan
endif

if HAVE_LIBVUGLES2
SUBDIRS += AnimationSetup
endif

install_PYTHON = __init__.py
