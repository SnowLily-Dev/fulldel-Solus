# fulldel-Solus
(Fulldel for Solus uses eopkg instead of apt)

Fulldel(A.K.A. Full Delete) for Solus is a script made for easily removing packages with the apt package manager and directly
removing the eopkg cache and unnecessary dependencies of recently removed packages.
Syntax for removing a package, it's dependencies and the apt cache:

Code:
fulldel -p (package)

Syntax for removing only the dependencies of recently removed apps/unused packages and clearing apt cache without
removing packages:

Code:
fulldel -n
OR
fulldel --no-package

Installation:

NOTE: Do NOT extract fulldel to /usr/bin or any other system folder or it will break your system!
Make sure to keep fulldel-Solus.tar.xz somewhere in your home folder and use the "install script" within
the archive to install fulldel!

Code:

mkdir ~/Documents/fulldel

cp /path/to/fulldel-Solus.tar.xz ~/Documents/fulldel

cd ~/Documents/fulldel

tar -xf ./fulldel-Solus.tar.xz

chmod 775 ./install

./install
