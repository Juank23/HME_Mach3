# HME_Mach3
A group of VB scripts for Mach 3 CNC Machining 

ZEROING AND TOOL CHNAGES

M3 - Spidle start - calls M8 (coolant), sets FRO to 20% for safety. Starts log

M5 - turns off coolant

M6 - changes tool - checks tool length to make touch off

M200 - zero script

M1002 - log start

M1003 - log end

M1111 - Moves around border of current job

M1112 - Sets co-ordinate based on camera position.
