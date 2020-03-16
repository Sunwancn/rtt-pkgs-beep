Import('RTT_ROOT')
Import('rtconfig')
from building import *

cwd     = GetCurrentDir()
src     = Glob('beep.c') 

CPPPATH = [cwd]

group = DefineGroup('Packages', src, depend = ['PKG_USING_BEEP'], CPPPATH = CPPPATH)

Return('group')