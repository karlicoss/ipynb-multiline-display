This is a snippet of Ipython code showing how to display multiple Sympy (or anything capable of latex conversion) equations in single line. It turned out to be way more difficult to achieve than I expected, so I figured it's worth sharing.

Example output in EIN/console mode:

                                           2
                           ∂              ∂
    Solving heat type PDE  ──(U(x, t)) = ───(U(x, t)) subject to: U(0, t) = 0 and U(1, t) = 0
                           ∂t              2
                                         ∂x
    

See [ldisplay.ipynb](ldisplay.ipynb) for the details.
