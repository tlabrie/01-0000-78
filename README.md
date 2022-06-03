# 01-0000-78
RS232 Serial Console, can run scripts

Hello!

If this program is still in it's initial release state, the only format of script it can run is a format where is goes COMMAND LINE, followed by the command,
and so on, like:

Connection Check
08 34 00 00 00 00 FF C5
Request Board Type
08 34 4E 00 00 00 FF 77
Request Firmware Version
08 34 A4 00 00 00 FF 21
Request Protocol Version
08 34 44 00 00 00 FF 81
