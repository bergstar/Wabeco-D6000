# Install additional packages 
sudo apt install git build-essential

# Clone repository and create pncconf symlink
ln -s Wabeco-D6000/Wabeco-D6000.pncconf Wabeco-D6000.pncconf

# Install toolchanger.comp
cd Wabeco-D6000/
sudo halcompile --install toolchanger.comp


## From original creator:

The 240 should have an index proximity switch signalling each station, but mine was U/S along with a lot of other low voltage components
My 160 did not have one and as I knew it could be indexed without, I did not replace the expensive Boxford 240 switch
If you want to use an index pulse, then you will have to re-write so that the position-cmd is incremented until the signal and then 
locked back by an appropriate amount

These 8 station ATCs do not have the tool and drill stations at perfect 45 degrees as you would expect
Stations 1,3,5,7 are tools and 2,4,6,8 are drills or round shank tooling
Therefore requires different movement depending upon whether current tool is odd or even number.

One "Odd" move + one "even" move should add up to 90°

The Jogging seems to only work for values >= 0.30 in the GUI box
