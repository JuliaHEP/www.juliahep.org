## Making modifications and seeing the changes locally

Assuming you're at the repo's root directory.
```
julia --project=.
```
and then
```julia
julia> using Pkg; Pkg.instantiate()

julia> using Xranklin

julia> serve()
```

A few recommendations and tools can be found at [repo of Julia's
website](https://github.com/JuliaLang/www.julialang.org/blob/main/README.md).
