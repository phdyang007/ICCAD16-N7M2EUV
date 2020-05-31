# ICCAD 2016 CAD Contest Problem C - EUV Simulation

## Description

- The four designs testcase1, testcase2, testcase3 and testcase4 are originally from ICCAD 2016 CAD Contest Problem C
- Designs are shrinked to 16nm CD to match N7 EUV specific metal layer design
- Defect (Hotspot) information is in csv files with coordinates (dbu) in the corresponding layouts
- There might be redundant records of hotspots in csv files. The simulation is set with a certain process window and hotspot might occur at the same location under different process conditions (dose, focus).
- Simulation is on EUV lithography model considering mask 3D effect.
- Hotspot information is obtained with the following OPC->Child Models for Process Window->PV Band Simulation
- Only EPE, Bridging and Necking defects are considered and recorded.

## Acknowledgement

- [ICCAD2016Contest link](https://cad-contest-2016.el.cycu.edu.tw/CAD-contest-at-ICCAD2016/)

## References

- If you find the benchmark helpful in your research, please cite our research at

