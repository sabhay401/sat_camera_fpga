1. Install AMD Vivado with support for the selected XQRKU060 device.
2. Open Vivado Tcl Console.
3. cd to the project directory.
4. Run:
       source Vivado/build.tcl
5. After synthesis:
       source Vivado/reports.tcl
6. Review the reports in Reports/.
7. Run the simulation using the supplied testbench.
8. Replace sample_pixels.csv with the supplied Figure-1 CSV if available.
9. Compare generated edge addresses/values with expected_edges.csv.