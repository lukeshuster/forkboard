# FORKBOARD
A from scratch keyboard heavily inspired by [Sinc 75% split](https://keeb.io/collections/sinc)
The plan is to design the pcb, 3d print a case and write custom firmware in rust.
## Build Progress
 - [x] think about starting project
 - [ ] design PCB
 - [ ] acquire parts
 - [ ] design case
 - [ ] write firmware
## Layout
![Layout](https://i.imgur.com/rqr67XE.png)
[Keyboard Layout Editor](http://www.keyboard-layout-editor.com/##@_name=forkboard&author=luke.shuster;&@=Esc&_x:0.25;&=F1&=F2&=F3&=F4&_x:0.25;&=F5&=F6&_x:1.5;&=F7&=F8&_x:0.25;&=F9&=F10&=F11&=F12&_x:1.25&fa@:1;;&=Rotary%20Encoder;&@_y:0.25;&=~%0A%60&=!%0A1&=/@%0A2&=#%0A3&=$%0A4&=%25%0A5&=%5E%0A6&_x:1.5;&=/&%0A7&=*%0A8&=%28%0A9&=%29%0A0&=/_%0A-&=+%0A/=&_fa@:1&:1&:0&:0&:1;&w:2;&=Backspace%0ADel%0A%0A%0A2&=Home;&@_f:3&w:1.5;&=Tab%0A%0A%0A%0A1.5&_f:3;&=Q&_f:3;&=W&_f:3;&=E&_f:3;&=R&_f:3;&=T&_x:1.5&f:3;&=Y&_f:3;&=U&_f2:1;&=I%0AInsert&=O%0ADel&=P&_f:3;&=%7B%0A%5B&_f:3;&=%7D%0A%5D&_f:3&w:1.5;&=%7C%0A%5C%0A%0A%0A1.5&=End;&@_f:3&w:1.75;&=Caps%20Lock%0A%0A%0A%0A1.75&=A&=S&=D&=F&=G&_x:1.5;&=H&_f:3;&=J%0APsc//SRq&_f:3;&=K%0AScrLk&_f:3;&=L%0APus//Brk&_f:3;&=/:%0A/;&_f:3;&=%22%0A%27&_f:3&w:2.25;&=Enter%0A%0A%0A%0A2.25&_f:3;&=Pg%20Up%0AVol%20Up;&@_f:3&w:2.25;&=Shift%0A%0A%0A%0A2.25&=Z&=X&=C&=V&=B&_x:1.5;&=N&=M&_f:3;&=%3C%0A,&_f:3;&=%3E%0A.&_f:3;&=?%0A//%0A%0A%0A1&_f:3&w:1.75;&=Shift%0A%0A%0A%0A1.75&_f:3;&=Up%0A%0A%0A%0A1&_f:3;&=Pg%20Dn%0AVol%20Dn;&@_f:3&w:1.25;&=Ctrl%0A%0A%0A%0A1.25&_f:3;&=Win%0A%0A%0A%0A1&_f:3&w:1.25;&=Alt%0A%0A%0A%0A1.25&_f:3&w:2.75;&=Space%0A%0A%0A%0A2.75&_f:3;&=Macro%0A%0A%0A%0A1&_x:1.5&f:3&w:2.75;&=Space%0A%0A%0A%0A2.75&_f:3;&=Alt%0A%0A%0A%0A1&_f:3;&=Fn%0A%0A%0A%0A1&_f:3;&=Ctrl%0A%0A%0A%0A1&_f:3;&=Left%0A%0A%0A%0A1&_f:3;&=Down%0A%0A%0A%0A1&_f:3;&=Right%0A%0A%0A%0A1)
## Resources
 - [RP2040 Minimal Design Guide](https://datasheets.raspberrypi.com/rp2040/hardware-design-with-rp2040.pdf)
 - [Footprints and Symbols for MX switches](https://github.com/ebastler/marbastlib)
 - [Good tutorial series on making a keyboard from scratch](https://www.masterzen.fr/2020/05/03/designing-a-keyboard-part-1/)
 - [Blog about key matrix](http://blog.komar.be/how-to-make-a-keyboard-the-matrix/)
