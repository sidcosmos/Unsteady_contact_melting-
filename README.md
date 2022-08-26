# Unsteady_contact_melting-

Read the .mlx file in live editor.

Change inputs like height, temperature, etc as required

The ode23s is a stiff solver, the output shall depend on what time step resolution has been selected, what relative tolerance is set and what convergence limit for final melted height is checked e.g at 10^-3 or 10^-6 or 10^-9. This all can vary end melting time by few tens of seconds.

Since, near completion of melting, it becomes a stiff set of equations, the time step modification has to be checked for stage 3 in some cases   
