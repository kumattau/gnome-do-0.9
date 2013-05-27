# Usage

    $ apt-get source gnome-do
    $ mkdir git; cd git
    $ git clone https://github.com/kumattau/gnome-do-0.9.git
    $ find gnome-do-0.9 | cpio -pdumv ../
    $ cd ../gnome-do-0.9
    $ debuild -us -uc

