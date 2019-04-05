# Robot-motion-on-grid
There is one python file that generates a CNF file.
This code is for the movement of two robots on a 5X5 grid, in a way that they do not collide. Motion is calculated using a SAT Solver, that takes this CNF file. Each position in a grid is labelled from 1 to 25. Now for the time t, ith block is numbered 25* I +t.  The output of the SATsolver gives the desired path.
