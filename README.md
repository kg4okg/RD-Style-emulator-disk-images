# RD-Style-emulator-disk-images
A repository for RD-disk images for an MFM disk emulator

These disk images are meant to be used for PDP-11 computers using an RQDX3 controller.
They are created for this MFM Disk Emulator: https://www.pdp8online.com/mfm/mfm.shtml

The RD disk drives supported are the following:

MFM "ST506/412 interface" (on RQDX{1,2,3})
==========================================
disk	cap.	sec/trk	trk/cyl	cyl	notes

=== 5.25" FH
RD50	5M	17	4	153	Seagate ST506 seek 85/3?/??
RD51	10M	17	4	306	Seagate ST412 seek 85/16.6?/??
RD52	31M	18	7	480	Quantum 540 / ATASI 3046 (also Evotek?)
RD53	71M	18	8	1024?	Microp 1325 (or 1335) w/ jumper at J7
RD54	156M	17	15	1225	Maxtor XT-2190D

=== 5.25" HH
RD31	20M	17	4	615	ST225 seek (ms) 65/20/150
RD32	40M	17	6	820	ST251(-1*) seek 40(28*)/8/70
					ST277R(-1*) [MFM format] 40(28*)/8/70
RD33	71M				Microscience HH-1090 [Never released]

(The above copied from https://www.ultimate.com/phil/pdp10/dec.disks)
