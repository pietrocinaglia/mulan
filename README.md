# MuLaN
MuLaN - A Local Alignment Algorithm for Multilayer Networks.

It is a software tool for the Local Network Alignment (LNA) of Multilayer Networks.

We tested MuLaN on macOS Ventura (Apple M1, arm64) with Python v3.11.

## Requirements
MuLaN needs Python >= 3.9, and the packages listed into 'requirements.txt'. The latter may be installed automatically by using [Python Package Installer (pip)](https://pip.pypa.io/en/stable/):

```
pip3 install -r requirements.txt
```

or (alias: pip=pip3):

```
pip install -r requirements.txt
```
<br />

## Run the example
You may use the dataset included into this repository ('example'), for demonstration purposes only, as follows:

```
./mulan example/data/n0.1_synt1.txt example/data/synt1.txt example/data/synt1_seed_L1.txt example/data/synt1_seed_L2.txt example/output
```

The dataset consists of two multilayer networks consisting of:
- source: 1901 nodes and 2075 edges.
- target: 2000 nodes and 2298 edges.

Default: Louvain is the method for community detection.

## Help
MuLaN may be used as shell-command, or through its own Command Line Interface (CLI).

Arguments (arg):
1) Multilayer Network 1 (source)
2) Multilayer Network 2 (target)
3) Seed nodes Layer 1
4) Seed nodes Layer 2
5) Output's name

<br />

## MIT License

Copyright (c) 2022

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
