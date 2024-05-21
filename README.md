# GNU-GRUB-2.06
When you stuck in GNU GRUB Version 2.06 you can try this

#First you have use this command to know which your memory need to windows boot
```bibtex
grub>> ls
```
that code will show all memory you have


#Second if you know where is your boot windows use this command
example you found your boot windows : (hd0,gpt1)/efi/microsoft/boot/bootmgfw.efi
```bibtex
grub>>chainloader (hd0,gpt1)/efi/microsoft/boot/bootmgfw.efi
```
