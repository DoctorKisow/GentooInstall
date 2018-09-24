## Gentoo Install Script
**install** - A script to install Gentoo according to the handbook.  
Matthew R. Kisow, D.Sc. <matthew.kisow@kisow.org>  
Copyright &copy; Kisow Foundation, Inc.&reg; 2015-2017.

## Getting Started
**Assumptions**  
This script assumes the following:  
   1. You know how to get the installation media from the Gentoo repository.  
   2. You know how to make the installation media bootable.  
   3. You are familiar with networking and are able to setup the installation media to connect to the Internet.  

**Variable Definition**  
This script uses the following prefixes to define variables:  
   g) (g_<variable>) - Global declaration, variables defined for use throughout  
                       the scripts execution.  
   l) (l_<variable>) - Local declaration, variables defined for use in function(s),  
                       local variables cannot be accessed globally.  
   v) (v_<variable>) - Variable declaration, variables defined in the configuration  
                       file and are used globally throughout the scripts execution.  
   
## License
License (GPL v3.0)

This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with this program.  If not, see <http://www.gnu.org/licenses/>.

## Acknowledgments
This script is based on [ **Sakaki's EFI Install Guide** ](https://wiki.gentoo.org/wiki/Sakaki's_EFI_Install_Guide) and has been expanded to permit both workstation and server installations in a variety of different configurations per best-practice installation.

## TODO
  1. Update the "get_cflags" function with all Intel processors.  
  2. Add more options under "use_variables".  
  3. Error check the configuration file.  
  4. Include a function that configures the kernel to VMWare.  
  5. Function to check if script is up-to-date.  
