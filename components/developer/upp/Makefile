#
# This file and its contents are supplied under the terms of the
# Common Development and Distribution License ("CDDL)". You may
# only use this file in accordance with the terms of the CDDL.
#
# A full copy of the text of the CDDL should have accompanied this
# source. A copy of the CDDL is also available via the Internet at
# http://www.illumos.org/license/CDDL.
#

#
# Copyright (C) 2025 Seppo Pakonen
#

BUILD_BITS=64
BUILD_STYLE=justmake
include ../../../make-rules/shared-macros.mk

COMPONENT_NAME=		upp
COMPONENT_MJR_VERSION=	2024.1.1
COMPONENT_VERSION=	17490
COMPONENT_SUMMARY=	Ultimate++ framework
COMPONENT_PROJECT_URL=	https://www.ultimatepp.org/
COMPONENT_FMRI=         developer/upp
COMPONENT_SRC=		$(COMPONENT_NAME)
COMPONENT_ARCHIVE=	$(COMPONENT_SRC)-posix-$(COMPONENT_VERSION).tar.xz
COMPONENT_ARCHIVE_HASH= sha256:9c88c384d42d88c5ac09095851fa48dd3ac6dcde9000e4095cdc86d7bc2e2073
COMPONENT_ARCHIVE_URL=	https://github.com/ultimatepp/ultimatepp/releases/download/$(COMPONENT_MJR_VERSION)/$(COMPONENT_ARCHIVE)
COMPONENT_CLASSIFICATION=	Development/UPP
COMPONENT_LICENSE=      BSD

include $(WS_MAKE_RULES)/common.mk

