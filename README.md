# Interactive-Hopfield-network
This is an interactive Julia Pluto notebook, where the workings of the Hopfield network are visualized and which easily extendable by training it with new easy to do patterns.  

# How to install and open the Pluto Notebook

The code was developed with Julia v1.11.2. 
To run the code, you need to download and install Julia first, e.g., from the official [download website](https://julialang.org/downloads/).

This file is not a normal Julia file, but a [Pluto.jl](https://github.com/fonsp/Pluto.jl) notebook, which are similarish to a Jupyter notebooks.


# How do open Pluto notebooks after having installed Julia

Download ``Hopfield_network.jl`` together with ``Manifest.toml`` and ``Project.toml`` and put it in the same directory.

## Working from a terminal (e.g., Linux or macOS)

Open a terminal and run

```bash
julia -e 'import Pkg; Pkg.activate(pwd()); Pkg.instantiate(); import Pluto; Pluto.run()'
```

in this directory. Then, open the Pluto notebook of interested.


## Windows

Open the Julia REPL in this directory, e.g., by navigating
to this directory in the Windows File Explorer and typing "julia" the address bar.
A console window should open. There, execute

```julia
import Pkg; Pkg.activate(pwd()); Pkg.add("Pluto"); Pkg.instantiate(); import Pluto; Pluto.run()
```

in the Julia REPL. Then, open the Pluto notebook.

