# verilog-practice
Storage for verilog practice problems

Using OSX for development of practice problems found in tutorials here:
http://www.asic-world.com/verilog/veritut.html

I'm using iverilog to compile the code: 
http://iverilog.wikia.com/wiki/Getting_Started

I'm using GTKWAVE to view the waveform
http://iverilog.wikia.com/wiki/GTKWAVE

initial
 begin
    $dumpfile("test.vcd");
    $dumpvars(0,test);
 end

vvp foo.vvp -lxt2

gtkwave dump.lxt
