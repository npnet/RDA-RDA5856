## ----------------------------------------------------------- ##
## Don't touch the next line unless you know what you're doing.##
## ----------------------------------------------------------- ##
include ${SOFT_WORKDIR}/env/compilation/compilevars.mk

# Name of the module
LOCAL_NAME := platform/edrv/gpio/gpio_5856e

LOCAL_API_DEPENDS := platform \
                    platform/service\
                    platform/edrv \
                    platform/edrv/pmd \
                    platform/edrv/pmd/${PM_MODEL} \
                    platform/edrv/gpio \
                    platform/rtos/common \
                    platform/rtos/std \
                    platform/rtos/sx \
                    platform/chip/hal \
                    platform/chip/${CT_ASIC}/hal \
                    platform/chip/${CT_ASIC}/regs \
                    platform/chip/comn/hal \
                    platform/chip/comn\
                    platform/chip/defs \
                    platform/service/bt \
                    platform/service/bt/btadp   \
                    platform/edrv/mcd \
                    platform/edrv/memd \
                    target



LOCAL_MODULE_DEPENDS :=

# This is a top-level module
IS_TOP_LEVEL = 
# Copy module lib to ./lib/${ASIC}
IS_MODULE_LIB := 
# This needs to deliver environment related files also
DELIV_ENV_FILES := 0

        

# Generates the CoolWatcher headers automatically.
AUTO_XMD2H ?= yes

# Generates the CoolProfile headers automatically.
#AUTO_XCP2H ?= yes

# Generate the revision (version) file automatically during the make process.
AUTO_GEN_REVISION_HEADER := yes

# Compilation mode for the version string.


# Flags exported throughout the build
LOCAL_EXPORT_FLAG +=


## ------------------------------------------------------------------------- ##
##	                       Source files                                      ##
## ------------------------------------------------------------------------- ##
# No source files in the top-level itself...
S_SRC := ${notdir ${wildcard src/*.S}} # uncomment to take all .S files
C_SRC := ${notdir ${wildcard src/*.c}} # uncomment to take all .c files

## ------------------------------------- ##
##  Do Not touch below this line         ##
## ------------------------------------- ##
include ${SOFT_WORKDIR}/env/compilation/compilerules.mk


