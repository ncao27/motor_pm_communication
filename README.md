# Project Description

This project contains scripts enabling the user to interface with the OptoSigma piezoelectric motors and the Thorlabs PM400 power meter.

## 1. Hyperterminal

Hyperterminal uses the pyserial package to communicate with the OptoSigma piezoelectric motors. By detecting the COM3 port connection we leverage user inputs (axis, frequency, rotations, etc.) to control the piezoelectric motor.

## 2. pm_interface

pm_interface uses NI VISA and the python wrapper class pyvisa in order to communicate with the Thorlabs PM400 power meter.
