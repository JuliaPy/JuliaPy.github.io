The [JuliaPy](https://github.com/JuliaPy) organisation on GitHub is the home for Julia-Python interoperability, providing packages to bridge the gap between these two excellent and complementary languages.

Within this, there are two ecosystems of packages, one centered around **PythonCall.jl** and the other around **PyCall.jl**. While PythonCall is newer and more actively maintained, both are popular and power many wrapper packages outside of this org.

## The PythonCall ecosystem

* **PythonCall.jl** ([repo](https://github.com/JuliaPy/PythonCall.jl)):
  A Julia package that lets you call Python code. Installs any Python dependencies
  automatically using CondaPkg.jl. Comes "batteries included" with support for numpy
  arrays, tabular data, multimedia display and more.

* **pyjuliacall** ([repo](https://github.com/JuliaPy/PythonCall.jl)):
  A Python package that lets you call Julia code - the Python side of PythonCall.jl. In
  fact this package is mostly implemented in Julia as part of PythonCall, they are two
  sides of the same codebase. This makes interoperation more symmetric and predictable
  from either side. Installs any Julia dependencies automatically using pyjuliapkg.

* **CondaPkg.jl** ([repo](https://github.com/JuliaPy/CondaPkg.jl)):
  A Conda package manager for Julia, like Pkg but for Conda. You declare your Julia
  project's Conda/PyPI dependencies in a CondaPkg.toml file (anaologous to Project.toml)
  and it automatically creates a Conda environment specific to your project with these in.
  Used by default by PythonCall for package management.

* **pyjuliapkg** ([repo](https://github.com/JuliaPy/pyjuliapkg)):
  The Python analogue of CondaPkg.jl, namely a Python package which reads your Julia
  dependencies from a juliapkg.json file and automatically installs Julia and any
  required packages into a Julia project specific to your Python/Conda environment.
  Used by default by pyjuliacall.

* **PythonPlot.jl** ([repo](https://github.com/JuliaPy/PythonPlot.jl)):
  A Julia plotting package wrapping matplotlib. A port of PyPlot.jl to use PythonCall.jl.

* **MicroMamba.jl** ([repo](https://github.com/JuliaPy/MicroMamba.jl)):
  Makes the micromamba implementation of Conda available. Mostly an implementation
  detail of CondaPkg.jl.

* Plus many more [external packages...](https://juliahub.com/ui/Packages/General/PythonCall#dependents)

## The PyCall ecosystem

* **PyCall.jl** ([repo](https://github.com/JuliaPy/PyCall.jl)):
  Another Julia package that lets you call Python code. Older than PythonCall but still
  popular and maintained.

* **pyjulia** ([repo](https://github.com/JuliaPy/pyjulia)):
  Another Python package that lets you call Julia code. Experimental and deprecated in
  favour of pyjuliacall.

* **Conda.jl** ([repo](https://github.com/JuliaPy/Conda.jl)):
  Makes Conda available and lets you install packages manually into a central Julia-wide
  Conda environment. Used by PyCall.jl to automatically install Python and packages.

* **SymPy.jl** ([repo](https://github.com/JuliaPy/SymPy.jl)):
  A Julia wrapper of the Python SymPy library.

* **PyPlot.jl** ([repo](https://github.com/JuliaPy/PyPlot.jl)):
  A Julia plotting package wrapping matplotlib.

* **Pandas.jl** ([repo](https://github.com/JuliaPy/Pandas.jl)):
  A Julia wrapper of the Python Pandas library, making DataFrames available in Julia.

* **Seaborn.jl** ([repo](https://github.com/JuliaPy/Seaborn.jl)):
  A Julia plotting package wrapping Seaborn.

* **PyCallJLD.jl** ([repo](https://github.com/JuliaPy/PyCallJLD.jl)):
  An integration allowing Python objects to be saved using JLD.jl.

* **PyInteract.jl** ([repo](https://github.com/JuliaPy/PyInteract.jl)):
  Provides Julia support for IPython-based interactive widgets.

* Plus many more [external packages...](https://juliahub.com/ui/Packages/General/PyCall#dependents)

## Join the discussion!

* You can create issues or discussions on any of our GitHub repos.
* The [Julia Discourse forum](https://discourse.julialang.org/) is a good place to ask
  questions. Using the 'PythonCall' or 'PyCall' tags helps.
* The [Julia Slack](https://julialang.org/slack/) is good for quick questions. We'd
  recommend [#expytriates](https://julialang.slack.com/archives/CQG6KQMR7) but many just
  use [#helpdesk](https://julialang.slack.com/archives/C6A044SQH).
