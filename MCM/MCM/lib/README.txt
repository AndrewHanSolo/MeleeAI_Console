###############################################################################
#               PyiiASMH - Cross-Platform WiiRd ASM Helper Tool               #
###############################################################################

=== Contents ===
 1. Contents
 2. About
 3. License
 4. Features
 5. Prerequisites
 6. Install
 7. Usage
 8. Changelog
 9. Credits
 10. Other

=== About ===
PyiiASMH is a cross-platform WiiRd helper tool that is designed to help users
with making WiiRd ready ASM codes. This application supports assembling powerpc
opcodes into Gecko codes using any of the Gecko ASM codetypes (C0, C2/D2, and 
F2/F4), or you can assemble them into raw hex. Disassembling of Gecko codes or 
raw hex into PPC assembly opcodes is also supported.

=== License ===
This project is licensed under the "new" or "modified" or 3-clause BSD license.
For more info, see the file COPYING. All libraries used are licensed under
their respective licenses.

=== Features ===
 - Free and open-source
 - Cross-platform (Windows, Linux, Mac OS X supported)
 - Multiple session support (opening and saving)
 - Two interfaces: a GUI implementation in Qt and a CLI implementation
 - Assemble powerpc opcodes into Gecko codes using any of the ASM 
     codetypes (C0, C2/D2, F2/F4) or also into plain raw hex
 - Disassemble Gecko codes into powerpc assembly opcodes
 - For more, check out the changelog

=== System Requirements ===
All:
 - Python 2.6.x, 2.7.x (NOT 3.x; older 2.x releases untested/not supported) 

All (GUI):
 - PySide 1.0.6+ (older releases untested/not supported)
   * Qt 4.x is also required

 OR (PySide or PyQt)

 - PyQt 4.7.x (or higher; older releases untested/not supported)
   * Qt 4.x is also required; depending on your method of install this may be
     installed automatically with PyQt
 
=== Install ===
No installation needed (other than the prerequisites listed above); 
just extract the archive and run!

=== Usage ===
Windows:
 - GUI: Double click the PyiiASMH.py file
Linux and Mac OS X:
 - GUI: run the bash script 'PyiiASMH'
 - CLI: run the bash script 'PyiiASMH-cli'
   * You may need to run `chmod +x' first on either script
All:
 - GUI: `python pyiiasmh.py'
 - CLI: `python pyiiasmh-cli.py'
   * Note: some Linux distributions name Python 2 as 'python2' instead

=== Changelog ===
See the file HISTORY.

=== Credits ===
See the file CREDITS.

=== Other ===
Bug reports, feature requests, questions, patches, etc. can be 
handled at the Google Code Project Web site (link at end of file).

        ###########################################################
        #          Copyright (c) 2009, 2010, 2011, 2012           #
        #        Sean Power <hawkeye2777[at]gmail[dot]com>        #
        #                  All rights reserved.                   #
        #     Google Code: http://code.google.com/p/pyiiasmh/     #
        ###########################################################
