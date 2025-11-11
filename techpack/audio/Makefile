# Use USERINCLUDE when you must reference the UAPI directories only.
USERINCLUDE     += \
                -I$(srctree)/techpack/audio/include/uapi \

# Use LINUXINCLUDE when you must reference the include/ directory.
# Needed to be compatible with the O= option
LINUXINCLUDE    += \
                -I$(srctree)/techpack/audio/include/uapi \
                -I$(srctree)/techpack/audio/include

# Add current directory to include path for config.h and other local headers
ccflags-y += -I$(src)

obj-y += asoc/
obj-y += dsp/
obj-y += ipc/
obj-y += soc/
