# Magma
Utilities and extensions of various Magma intrinsics plus intrinsics for efficiantly working with Conrey characters and their Galois orbits, integrated with Magma's built-in support for Dirichlet characters.

You can create the Dirichlet character with Conrey label `13.3` in the Galois orbit with LMFDB label `13.c` using either `chi:=DirichletCharacter("13.2");` or `chi:=DirichletCharacter(`13.c`);` and you can recover these labels using `ConreyLabel(chi)` or `CharacterOrbitLabel(chi)`.

To use this package add `AttachSpec("somewhere/magma.spec")` to your Magma startup script.
