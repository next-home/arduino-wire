**This fork repo is modified for using i2c1 (secondary i2c) instead of i2c0.**

# Arduino Wire (I2C) library for Mongoose OS

This library provides an Arduino compatibility layer for the I2C protocol by
providing a `Wire.h` public header, so that one could pick an existing Arduino
program which uses I2C, throw it into the Mongoose OS application sources, and
ideally, it "just works".
