# Interactive C++ code development using C++Explorer and GitHub Classroom for educational purposes

## Examples 

Note that you need need a [CxxExplorer](https://github.com/stevenrbrandt/CxxExplorer) running to execute the notebooks. However, you still can open the notebooks and
experience the C++Explorer features.

### Example for writing serial C++ code

At the begining of the course, the students learn to use the C++ standard template library and use the Markdown cells of 
the Jyputer notebooks to document the code. For larger projects, the intructor uses the Markdown cells to comment and the
code and gives intrusctions to the students which parts of the tempalte they should edit to accomplish the exercise. Please find a example for how to compute the median [here](https://github.com/diehlpk/gateways2020/blob/master/c%2B%2B.ipynb) and the template for the N-Body simualtion [here](https://github.com/diehlpkteaching/N-Body/blob/master/Nbody_template.ipynb). 

### Example for HPX's parallel algorithms

After the inroduction of HPX in the lecture, the students learn that the need to use

```cpp
run_hpx([](){

//My code 

});
```
within a Cling cell to execute the HPX code in parallel. Please find the example [here](https://github.com/diehlpk/gateways2020/blob/master/hpx_parallel.ipynb). 

### Example for asyncronous programming


### Example to use pybind



### Course materials

* [Lecture slides](https://github.com/diehlpkteaching/ParallelComputationMath)
* [Exercises](https://github.com/diehlpkteaching/ParallelComputationMathExercise)
* [Code](https://github.com/diehlpkteaching/ParallelComputationMathExamples)
* [Lecture notes](https://github.com/diehlpkteaching/ParallelComputationMathScript)
