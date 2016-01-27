# OpenGLBlocks

This program displays colored blocks to a window on the screen. It uses OpenGL 
for rendering/rasterization and SDL for window management and I/O. 

#Files

'.ycm_extra_conf.py' is a python script used to generate relevant tags and 
search information for the YouCompleteMe Vim plugin that is used in development 
for this project.

'ctags_with_dep.sh' is a bash script that checks the included libraries from all 
of the source files and calls ctags to assemble a tags file with every 
identifier in every included library present

'frag.f.glsl' is the fragment shader used to render the blocks

'vert.v.glsl' is the vertex shader used to render the blocks
