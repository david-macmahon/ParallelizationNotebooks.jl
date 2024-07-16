# Julia Parallelization (p15n)

The Julia programming language offers multiple ways to run code in parallel to
take advantage of the multiple CPUs of a computer or even multiple CPUs of
multiple computers.  This project contains a collection of notebooks that
showcase some of the techniques available.  They are intended to give an
introduction to Julia's built-in capabilities rather than serving as a
comprehensive treatise on parallel/concurrent programming.  Additional Julia
packages build on these capabilities to offer more parallization techniques and
abstractions, but these notebooks do not cover those.

The notebooks are intended to be usable on any system that has a POSIX-like
filesystem.  Some of the notebooks that parallelize across multiple computers
need to specify the host names of the other computers, so some customization may
be necessary.  Because these notebooks are for illustrative purposes some of
what they do is rather contrived, but the concepts portrayed should be readily
transferrable to your own projects.

## Topics covered

The main topics covered are:

- Hardware resources and Julia threads
- Julia multi-threading
- Julia multi-processing, single host
- Julia multi-processing, multiple hosts
  - One process per host, multi-threaded
  - Multiple processes per host, single threaded
