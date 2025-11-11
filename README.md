The [JuliaPy](https://github.com/JuliaPy) organisation on GitHub is the home for Julia-Python interoperability, providing packages to bridge the gap between these two excellent and complementary languages.

Within this, there are two ecosystems of packages, one centered around **PythonCall.jl** and the other around **PyCall.jl**. While PythonCall is newer and more actively maintained, both are popular and power many wrapper packages outside of this org.

The core packages of the PythonCall ecosystem are:

* **PythonCall.jl** ([repo](https://github.com/JuliaPy/PythonCall.jl)) itself, which
  lets you call Python code. Comes "batteries included" with support for numpy
  arrays, tabular data, multimedia display and more.

* **pyjuliacall** ([repo](https://github.com/JuliaPy/PythonCall.jl)) is the Python side
  of PythonCall.jl, letting you call into Julia from Python.

* **CondaPkg.jl** ([repo](https://github.com/JuliaPy/CondaPkg.jl)) is a Conda package
  manager for Julia, like Pkg but for Conda. Used by PythonCall for automatic package
  management.

* **pyjuliapkg** ([repo](https://github.com/JuliaPy/pyjuliapkg)) is the Python analogue
  of CondaPkg.jl, used by pyjuliacall for automatic package installation.

* Plus wrapper package
  **PythonPlot.jl** ([repo](https://github.com/JuliaPy/PythonPlot.jl))
  and many more [external packages...](https://juliahub.com/ui/Packages/General/PythonCall#dependents)

The core packages of the PyCall ecosystem are:

* **PyCall.jl** ([repo](https://github.com/JuliaPy/PyCall.jl)) is another Julia package
  that lets you call Python code. Older than PythonCall but still popular and maintained.

* **pyjulia** ([repo](https://github.com/JuliaPy/pyjulia)) is another Python package
  that lets you call Julia code. Experimental and deprecated in favour of pyjuliacall.

* **Conda.jl** ([repo](https://github.com/JuliaPy/Conda.jl)) makes Conda available in
  Julia. Used by PyCall.jl to automatically install Python and packages.

* Plus wrapper packages
  **SymPy.jl** ([repo](https://github.com/JuliaPy/SymPy.jl)),
  **PyPlot.jl** ([repo](https://github.com/JuliaPy/PyPlot.jl)),
  **Pandas.jl** ([repo](https://github.com/JuliaPy/Pandas.jl)),
  **Seaborn.jl** ([repo](https://github.com/JuliaPy/Seaborn.jl)),
  **PyCallJLD.jl** ([repo](https://github.com/JuliaPy/PyCallJLD.jl)),
  **PyInteract.jl** ([repo](https://github.com/JuliaPy/PyInteract.jl))
  and many more [external packages...](https://juliahub.com/ui/Packages/General/PyCall#dependents)

Feel free to **get in touch**:
* You can create issues or discussions on any of our GitHub repos.
* The [Julia Discourse forum](https://discourse.julialang.org/) is a good place to ask
  questions. Using the 'PythonCall' or 'PyCall' tags helps.
* The [Julia Slack](https://julialang.org/slack/) is good for quick questions. We'd
  recommend [#expytriates](https://julialang.slack.com/archives/CQG6KQMR7) but many just
  use [#helpdesk](https://julialang.slack.com/archives/C6A044SQH).
