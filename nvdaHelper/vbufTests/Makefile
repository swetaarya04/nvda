###
# tests/Makefile
# Part of the NV  Virtual Buffer Library
# This library is copyright 2007, 2008 NV Virtual Buffer Library Contributors
# This library is licensed under the GNU Lesser General Public Licence. See license.txt which is included with this library, or see
# http://www.gnu.org/licenses/old-licenses/lgpl-2.1.html
###

TOPDIR=..
!include $(TOPDIR)\make.opts

all:
	cd test_utils && $(MAKE) /nologo DEBUG=$(DEBUG)
	cd storage && $(MAKE) /nologo DEBUG=$(DEBUG)
	cd test_printExampleBackendXML && $(MAKE) /nologo DEBUG=$(DEBUG)

clean:
	cd test_utils && $(MAKE) /nologo clean
	cd storage && $(MAKE) /nologo clean
	cd test_printExampleBackendXML && $(MAKE) /nologo clean
