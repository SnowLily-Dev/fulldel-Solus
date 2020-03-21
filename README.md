# fulldel-Solus
(Fulldel for Solus uses eopkg instead of apt)

Fulldel(A.K.A. Full Delete) for Solus is a script made for easily removing packages with the apt package manager and directly
removing the eopkg cache and dependencies of recently removed or unused packages.
Syntax for removing a package, it's dependencies and the apt cache:

Code:
fulldel -p (package)

Syntax for removing only the dependencies of recently removed apps/unused packages and clearing apt cache without
removing packages:

Code:
fulldel -n
OR
fulldel --no-package
