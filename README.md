
## Progress

[7/22/22](updates_md/7-22-22.md)

[7/17/22](updates_md/7-17-22.md)

[7/8/22](updates_md/7-8-22.md)


---
# Mag Pot
This project is was started in the hopes to make it easy and affordable to completley remove all potentiometer wear/oddities in Gamecube Controllers.


# What is the Mag Pot?
The Mag Pot is a drop in replacement for the resistive potentioimeter found in Gamecube Controllers. 

# Why make this?
I wanted to make it easier (and much cheeper) for anyone to turn **ANY** Gamecube Controller into one with nearly percect stick inputs that will never wear.

# How dos it work?
The Mag Pot uses small magnetic encoders to read stick box angles. The angles are read by a micro controller that will output a corisponding analog voltage to be read by the GCC.

While the above explaination is simple, the process involves a lot of linear algera and low level programming. I will be making an in depth explaination of the maths and programming eventually but I'm currently more focused on getting a final product.

# Features
1. Similar to the highly sought after [PhobGCC](https://github.com/Phobos132/PhobGCC), the notch positions (including custom notches such as firefox notches) will be able to be calibrated allowing for high input accuracy and repeatability. I plan to have a computer/phone interface to make calibration easy and doable without a smashscope (I'm also working on making a mini usb/bluetooth smashscope). 

2. The stick snapback will be highly tuneable in the software interface. This will essentially be able to do the same this as a snapback mod but about 10x better. For anyone wanting to know, I'm representing the stick inputs as a second order system that can be convienently put into a statespace equation.

3. Low cost: I'm thinking of pricing this module in the range of $35(not decided yet) making it significantly less expensive than a full custom pcb controller. I think anyone reading this page knows how absudly expensive controllers can get for the sake of precise stick inputs or controllers with favorable pode. 
