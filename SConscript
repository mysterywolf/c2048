from building import *

group = []
if not GetDepend(['PKG_USING_2048']):
    Return('group')

cwd = GetCurrentDir()
CPPPATH = [cwd]
src	= Glob('*.c')

group = DefineGroup('2048', src, depend = ['PKG_USING_2048'], CPPPATH = CPPPATH)

Return('group')
