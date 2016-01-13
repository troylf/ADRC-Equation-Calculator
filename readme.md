### About

This is an IPython Notebook that calculates the discrete time equations for a Active Disturbance Rejection Controller. This will calculate the equations, but how to implement those equations needs to be looked up.

### To Use

1. Open in IPython Notebook.
2. If LaTeX is not installed, then comment out the LaTeX lines under ***Settings***.
3. Set the estimated order of the system under ***Settings***.
4. Run all cells
5. Retrive equations from the ***Equations*** section.

### Known Issues / To Do

* If LaTeX isn't installed, but the code to use LaTeX is left in, then the script will error out
* The extended state variable sets the extended state (at the very beginning of the calculation section). It is unknown if this produces reliable equations for anything other than one(1) extended state. A single extended state is consistant and tested.
* Other information is needed to implement the calculated equations. Links are provided to papers to help with the implementation.