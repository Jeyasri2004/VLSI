# VLSI
The objective of the License Plate Recognition (LPR) system is to accurately and
efficiently identify vehicle license plates from images or video streams. By leveraging
FPGA technology, the system aims to perform real-time processing, ensuring fast
recognition with minimal latency and power consumption. The LPR system is designed
to handle various environmental conditions, including different lighting, vehicle
speeds, and plate formats, making it suitable for applications such as toll collection,
traffic monitoring, and security surveillance.
A plate license recognition system is implemented in Matlab and then it is
implemented on FPGA Xilinx Spartan-6 using Verilog.
In Matlab,one car image is converted into hex and load the Hex file in verilog code.
In verilog,Hex file is read by $memreadh this command and converted into hex values.
And then Hex values are write into another file and process the hex values to find the License plate.
