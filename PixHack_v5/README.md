The PixHack V5 is based on the FMUv5 designed flight control controller hardware, designed, produced and sold by CUAV. The hardware design file is completely open by CUAV and And abide by the BSD protocol.

The V5 flight controller has two main components:

1: V5_Core

This is a complete master core, which contains the F765 processor and the main sensors, and expands the I/O through the DF17 series 80P interface.

note: It may look like a SOLO or PIX2 Cube, because it all looks like a small square��but it is completely different, including the shape, screw hole installation position, interface definition,size,internal structure, are completely different, so V5 CORE and Cube are completely incompatible, if you need to V5_Core For secondary development, please refer to our open reference design.

2: V5_Base

This is a docking station and its main functions are:
1: Built-in 3-way power redundant switching circuit
2: Built-in a PX4_IO_V2 processor
3: Extend the V5_Core I/O through the wire-to-board connector.

Design files or libraries may reference some references from PX4\PIXHAWK\3DR\Proficnc, thanks for their contributions to open source hardware. If there is any infringement, please contact us for deletion and modification.