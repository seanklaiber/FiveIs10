-----------------------------
Julia on WSL
- https://julialang.org/downloads/platform.html#generic-linux-binaries
-----------------------------
1. Download 64-bit generic linux binaries for x86 from:
    https://julialang.org/downloads/index.html
2. Unpack with:
    $ tar -xvzf julia-0.6.2-linux-x86_64.tar.gz
3. Move to Linux ~/Julia/
4. Rename based on version. For example: julia-0.6.2
5. Create a symbolic link to julia's bin folder from a dir on the path
    $ sudo ln -s ~/Julia/julia-0.6.2/bin/julia /usr/local/bin/julia

