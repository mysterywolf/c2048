from building import *

group = []
if not GetDepend(['PKG_USING_2048']):
    Return('group')

src	= Glob('*.c')

group = DefineGroup('2048', src, depend = ['PKG_USING_2048'])

Return('group')
