# Adding /dev/sex for the funnies
- made by https://github.com/Laith-GLaDOS in collaboration with me

License originally was GPL on the c file
im assuming it was v3 so i updated it to be more clearer cuz there wasnt any option for GPL so i picked V3

# How to install
- run `git clone https://github.com/tryzen-0/dev-sex.git`
- run `cd dev-sex`
- run `make`
- run `make` again
- run `sudo insmod devsex_module.ko`
- run `sudo dmesg | grep 'Sex'`
- run `./make_device_file <whatever major number dmesg command outputted>`

# NOTE: you need to rerun the last 3 commands every time you reboot. Sorry for that :(
