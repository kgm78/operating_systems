# Florida Polytechnic University Spring 2022 Operating Systems
## Running OS
To run: 
1. Clone this repository https://github.com/kgm78/operating_systems.git
> git clone https://github.com/kgm78/operating_systems.git
2. Go to root directory of OS
> cd operating_systems
3. Run make qemu-nox to start OS
> make qemu-nox
4. To exit operating system hit ctrl+a, unpress, then hit x
> ctrl a + release hand from keyboard + x

## Modifying OS
### user/ - hosts user command files.
To add a command: 
1. Create a .c file in user/ folder program command functionality
2. Add command file name to makefile.mk 
3. It may be necessary to add it to usys.S

### kernal/ - hosts OS kernal and backend processes

## Maintained By:
1. Kyle (kgm78)
2. Dominique (TosnEula)
3. Jacob (Thaxes)
