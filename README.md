# LibHDF5.jl

LibHDF5.jl is a bare bones complement to [HDF5.jl](https://github.com/JuliaIO/HDF5.jl) that was generated by [Clang.jl](https://github.com/JuliaInterop/Clang.jl) by parsing [hdf5.h](https://github.com/HDFGroup/hdf5/blob/develop/src/hdf5.h). The objective is to expose the entire 
HDF5 API directly through automation and nothing more. For a Julian interface to HDF5, see [HDF5.jl](https://github.com/JuliaIO/HDF5.jl).

The project to generate the module is located in the `gen` folder. Execute or include the file `generator.jl`. Currently, the generated file has to be manually edited. However, we hope to fully automate the process in the near future.