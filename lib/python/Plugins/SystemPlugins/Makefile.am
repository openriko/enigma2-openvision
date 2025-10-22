installdir = $(pkglibdir)/python/Plugins/SystemPlugins

SUBDIRS = SoftwareManager PositionerSetup Satfinder \
	SatelliteEquipmentControl Videomode VideoTune Hotplug \
	 CommonInterfaceAssignment \
	CableScan FastScan OSDPositionSetup OSD3DSetup HdmiCEC \
	WirelessLan NetworkWizard

if DMAMLOGIC
SUBDIRS += VideoEnhancementAML
else
SUBDIRS += VideoEnhancement
endif


if HAVE_OSDANIMATION
SUBDIRS += AnimationSetup
endif

if HAVE_FCC_ABILITY
SUBDIRS += FastChannelChange
endif

install_PYTHON =	\
	__init__.py
