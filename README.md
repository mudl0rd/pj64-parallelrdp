# pj64-parallelrdp

[Download for DLL](https://www.mediafire.com/file/neig4q7r788puj3/pj64-parallelrdp.rar)

Implementation of Themaister's Parallel-RDP simulator for PJ64.
Vulkan is used as the GPU compute backend, and OpenGL 3.3 is 
used for the blitting of image buffers captured from the backend.

Made after a few days of messing around with GCC and some misc. sources.

To compile using MSYS2 
1) Clone/fork the Github repo only.
2) use "make all platform=win"

For best results: use cxd4's RSP plugin or Maister's Parallel-RSP. Zilmar's RSP has several LLE GFX bugs.
