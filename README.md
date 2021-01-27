# grub-mod-setup_var
patch grub 2.04 to use setup_var.  
# How to use?
git clone https://github.com/gamecss/grub-mod-setup_var.git  
git clone --branch grub-2.04 https://git.savannah.gnu.org/git/grub.git  
cd grub/  
patch -p1 < ../grub-mod-setup_var/setup_var.patch
