# double-box-moller

The transformation matrix contains all information: MIs(pre-canonical), Linear combination for the MIs, normalization factors for diagonals and correction terms for Off diagonals.

The pre-canonical MIs first get transformed by linear combination terms, then by given transformation matrix, this gives final Mis to obtain canonical forms; To be precise:
We applied the given linear combinations to pre canonical MIs and use them to reach epsilon forms in diagonal parts, that resulted MATRICES As0 and At0. Consequently, we worked out the transformation matrix with normalization factors and corrections terms for off diagonal. This last step provided us As and At as given in Github.

The As and At matrices are canonical forms, once pure and once with Dlogs; Dlogs are already provided in Master Thesis.
