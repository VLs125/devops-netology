# Домашнее задание к занятию 2.4

1.команда - git log -1 --pretty=oneline aefea
aefead2207ef7e2aa5dc81a34aedf0cad4c32545 Update CHANGELOG.md 


2.команда - git show 85024d3 
v0.12.23 

3.команда - git rev-list --parents -n 1 b8d720 
2
 
4.команда - git log  v0.12.23..v0.12.24  --oneline
b14b74c49 [Website] vmc provider links
3f235065b Update CHANGELOG.md
6ae64e247 registry: Fix panic when server is unreachable
5c619ca1b website: Remove links to the getting started guide's old location
06275647e Update CHANGELOG.md
d5f9411f5 command: Fix bug when using terraform login on Windows
4b6d06cc5 Update CHANGELOG.md
dd01a3507 Update CHANGELOG.md
225466bc3 Cleanup after v0.12.23 release

5.5af1e6234 main: Honor explicit provider_installation CLI config when present
8c928e835 main: Consult local directories as potential mirrors of providers

6. команда git log -S'globalPluginDirs' --oneline
35a058fb3
c0b176109
8364383c3

7.команда - git log -S 'synchronizedWriters'
 Author: Martin Atkins <mart@degeneration.co.uk>

