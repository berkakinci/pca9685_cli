# PCA9685 Command Line Interface
## pca9685_cli
Shortcuts to Linux i2c-tools on a PCA9685 16-Channel PWM GPIO expander

## USAGE:
Configure I2C bus and slave address in .config.sh.

Run the scripts in this directory from the command line.

In my implementation, I use the PCA9685 to demo control of a servo motor.  This is done in ./angle and ./demo

## Dependencies you'll need:
- i2c-tools: "heterogeneous set of I2C tools for Linux"
- bash:      "GNU Bourne Again SHell"
