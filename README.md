# Preliminaries
 
## Disclaimer and Licensing
 
DmrgAndBeyond is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.
DmrgAndBeyond is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the
GNU General Public License for more details.
You should have received a copy of the GNU General Public License
along with DmrgAndBeyond. If not, see <http://www.gnu.org/licenses/>.
The full software license for DmrgAndBeyond version 1.0.0 
can be found in
file LICENSE. 

## Please cite this work

DmrgAndBeyond is porcelain for ITensor.
The full software license for DmrgAndBeyond version 0.1
can be found in
file LICENSE. 
You are welcomed to use it and publish data 
obtained with DmrgAndBeyond. If you do, please cite this
work. Explain How To Cite This Work. FIXME. TBW.

## About ITensor

ITensor is developed by E. M. Stoudenmire and S. R. White and contributors.
The full software license for ITensor can be found
at https://github.com/ITensor/ITensor/blob/master/LICENSE

## Hash of the latest commit 

Hash of the latest commit is also posted at
https://web.ornl.gov/~gz1/hashes.html

# Building and Running DmrgAndBeyond

## Required Software

* GNU C++
* The LAPACK and BLAS libraries
* ITensor (see below)
* PsimagLite (see below)

## Optional Software

* make or gmake (only needed to use the Makefile)
* perl (may be needed to run some auxiliary script) 

## Quick Start

1. Use your distribution repository tool to install gcc with support for C++,
the LAPACK and BLAS libraries, make, perl, and git 
if you don't have them.

2. Issue

    cd someDirectory/

    git clone https://github.com/ITensor/ITensor
    (Note: I do not maintain ITensor and I am not an author of ITensor)
    
    git clone https://github.com/g1257/PsimagLite.git

    git clone https://github.com/g1257/DmrgAndBeyond.git

3. Compile ITensor
    
    cd ITensor
    and follow the instructions there.
    
4. Compile PsimagLite

    cd PsimagLite/lib/

    make -f Makefile.sample

    cd ../../

5. Now issue

    cd DmrgAndBeyond/src

    make

6. You can run it with TBW.
 
