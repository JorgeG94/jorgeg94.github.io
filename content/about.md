+++
title = "About"
date = "2025-08-04"
author = "Jorge"
+++

# Hi there

<div style="display: flex; align-items: flex-start; gap: 2em; flex-wrap: wrap;">
<div style="flex: 1; min-width: 220px;">

My name is Jorge and I am a weird hybrid mixture of computational chemist and research software engineer with 
experience in High Performance Computing (HPC), specially on using GPUs to solve cool, challenging problems. 

I have experience using Python, Julia, C, C++, CUDA, HIP, and Fortran for developing scientific applications. 
Lately, I have had enough in my life of C++ and I am currently favouring Fortran a bit more than what I did during my postdoctoral appointment. 

</div>
<div style="flex: 0 0 auto;">
<img src="/images/jorge_hat_photo.JPG" alt="Jorge" style="width: 200px; border-radius: 8px; display: block;" />
</div>
</div>

## Background 

I studied Chemistry in the Universidad de las Americas, Puebla in Mexico - after this I went on 
to do a PhD in Physical Chemistry at Iowa State University under Prof. Mark Gordon, 
where I began my HPC journey. During my PhD I was involved in the Exascale Computing Project (ECP)
from the Department of Energy (DOE),  where I helped write speedy GPU accelerated algorithms into the GAMESS quantum chemistry program. 

I mostly did electron repulsion integral evaluation and general Self-Consistent Field (SCF) work, 
which is at the core of all quantum chemistry. After my PhD I left Iowa to go to Canberra, Australia
as a Research Fellow at the Australian National University under (now) Prof. Giuseppe Barca. Here
we continued the research we did during the ECP and spinned out a program called EXESS, built upon
the core ideas developed we explored during my PhD. 

Along with the students, we managed to write a very speedy code that was able to scale up on Frontier, 
at OLCF and we won an ACM Gordon Bell prize in 2024, woo! This was very fun.

After this, I was a bit tired and decided a change was in order.

## Interests

## Currently 

I am currently an HPC specialist at the National Computational Infrastructure (NCI) in Canberra, Australia 
where I am helping codebases in the geophysics, climate, and weather domain to modernise and optimise their 
code to use modern HPC architectures, like GPUs. 

My main work focuses on porting the ANUGA flood simulator and the Modular Ocean Model (MOM6) to use
GPUs. 

## Current work projects

- Porting of [ANUGA](https://github.com/anuga-community/anuga_core) to GPUs 
- Porting of [MOM6](https://github.com/mom-ocean/MOM6) to GPUs 

## Current personal projects 

- Development of [pic](https://github.com/JorgeG94/pic) a library for common Fortran functionality for HPC programs 
- Development of [pic-mpi](https://github.com/JorgeG94/pic-mpi) a seamless wrapper to the `mpi` and 
`mpi_f08` modules that allows switching between them for convenience on HPC systems 
- Developent of [pic-blas](https://github.com/JorgeG94/pic-blas) a safe modular interface to BLAS and LAPACK routines from Fortran 
- Development of [Metalquicha](https://github.com/JorgeG94/metalquicha) a fragmentation first quantum chemistry library which uses XTB as a backend 
- Contributions to open source Fortran projects such as [Vapaa](https://github.com/jeffhammond/vapaa), the [FPM](https://github.com/fortran-lang/fpm), [test-drive](https://github.com/fortran-lang/test-drive), among others! 


## Other projects 

I am a very regular contributor to the [GAMESS](https://www.msg.chem.iastate.edu/gamess/index.html) program for 
quantum chemistry calculations. My goal is to modernize the Fortran 77 codebase to a modern Fortran one. 

You can stalk [my github profile](https://github.com/JorgeG94) to see what I am up to. 

## Publications 

1. Fiona Yu, **JL Galvez Vallejo**, Giuseppe Barca. "Automatic Molecular Fragmentation by Evolutionary Optimisation." *Journal of Cheminformatics, 16(1), 102*
2. Ryan Stocks, **JL Galvez Vallejo**, Calum Snowdon, Elise Palethorpe, Fiona Yu, Jakub Kurzak, Dymytro Bykov, Giuseppe Barca. "Breaking the Million Electron Barrier: Bio-scale Ab Initio Molecular Dynamics with MP2 Potentials." *SC '24.*
3. Fazeleh Kazemian, **JL Galvez Vallejo**, Giuseppe Barca. "Benchmark of Multiple MPI Communication Frameworks for the FMO Method." *Accepted, Int. Conf. Parallel Processing.*
4. Federico Zahariev, Peng Xu, … **JL Galvez Vallejo**, … Mark S. Gordon. "The General Atomic and Molecular Electronic Structure System (GAMESS): Novel Methods on Novel Architectures." *J. Chem. Theory Comput.* 19(20), 7031–7055.
5. **JL Galvez Vallejo**, Calum Snowdon, Ryan Stocks, … Giuseppe Barca. "Towards an Extreme Electronic Structure System." *J. Chem. Phys.* 159(4).
6. Daniel Del Angel Cruz, **JL Galvez Vallejo**, Mark S. Gordon. "Analysis of the Bonding in Tetrahedrane and Phosphorus-Substituted Tetrahedranes." *Phys. Chem. Chem. Phys.* 25(40), 27276–27292.
7. Masha Sosonkina, Vaibhav Sundriyal, **JL Galvez Vallejo**. "Runtime Power Allocation Based on Multi-GPU Utilization in GAMESS." *J. Comput. Commun.* 10, 66–80.
8. Giuseppe Barca, **JL Galvez Vallejo**, Calum Snowdon, Fazeleh Kazemian, Alistair Rendell, Mark S. Gordon. "Scaling the FMO Method on Summit." *SC '22.*
9. **JL Galvez Vallejo**, Garrett Tow, Ed Maginn, Buu Q. Pham, Dipayan Datta, Mark S. Gordon. "Quantum Chemical Modelling of Propellant Degradation." *J. Phys. Chem. A.*
10. **JL Galvez Vallejo**, Giuseppe Barca, Mark S. Gordon. "High-Performance GPU-Accelerated Evaluation of Electron Repulsion Integrals." *Mol. Phys.* e2112987.
11. David Poole, **JL Galvez Vallejo**, Mark S. Gordon. "A Task-Based Approach to Parallel Restricted Hartree–Fock Calculations." *J. Chem. Theory Comput.* (co-first author).
12. Giuseppe Barca, **JL Galvez Vallejo**, David Poole, Melisa Alkan, Ryan Stocks, Alistair Rendell, Mark S. Gordon. "Enabling Large-Scale Correlated Electronic Structure Calculations: Scaling the RI-MP2 Method on Summit." *SC '21.*
13. Giuseppe Barca, Melisa Alkan, **JL Galvez Vallejo**, David Poole, Alistair Rendell, Mark S. Gordon. "Faster Self-Consistent Field (SCF) Calculations on GPU Clusters." *J. Chem. Theory Comput.* 17(12), 7486–7503.
14. **JL Galvez Vallejo**, Julio Duchimaza-Heredia, Mark S. Gordon. "Bonding Analysis of Water Clusters Using Quasi Atomic Orbitals." *Phys. Chem. Chem. Phys.* 23, 18734–18743.
15. Giuseppe Barca, **JL Galvez Vallejo**, David Poole, Alistair Rendell, Mark S. Gordon. "High-Performance, GPU-Accelerated Fock Build Algorithm." *J. Chem. Theory Comput.* 16(12), 7232–7238.
16. Giuseppe Barca, David Poole, **JL Galvez Vallejo**, Melisa Alkan, Colleen Bertoni, Alistair Rendell, Mark S. Gordon. "Scaling the Fock Build on Summit." *SC '20.*
17. David Poole, **JL Galvez Vallejo**, Mark S. Gordon. "A New Kid on the Block: Application of Julia to Hartree–Fock Calculations." *J. Chem. Theory Comput.* 16(8), 5006–5013.
18. Giuseppe Barca, Colleen Bertoni, … **JL Galvez Vallejo**, … Mark S. Gordon. "Recent Developments in the General Atomic and Molecular Electronic Structure System." *J. Chem. Phys.* 152, 154102.
19. Mark S. Gordon, Giuseppe Barca, Sarom Leang, David Poole, Alistair Rendell, **JL Galvez Vallejo**, Bryce Westheimer. "Novel Computer Architectures and Quantum Chemistry." *J. Phys. Chem. A* 124(23), 4557–4582.
