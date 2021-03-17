# Physical-design-using-eda-tools
This repository is to give brief idea about the VSD's 'Beginner Soc/Physical Design using open source EDA tools' Workshop. The workshop gives me a hands on experience with the EDA tools used in Physical Design.

* Here are some sources used in this workshop:
1.YOSYS : Synthesis.

2.Graywolf :Placement.

3.Qrouter : Routing.

4.Qflow : RTL2GDS integration.

5.MAGIC : VLSI Layout tool.

6.Netgen : LVS.

7.OpenSTA & Opentimer : Prelayout & postlayout Static Timing Analysis.
The total workshop is divided into 5 days with lab activities on each day as follows
# Day1 & 2 Labs

Type the command “yosys” to open ‘yosys open synthesis tool’.
 
<img src = "https://github.com/nageswarchedella/Physical-design-using-eda-tools/blob/main/day1/yosys.png" width = 700>


  -> Type "which sta" to see the ‘sta tool’s’ directory.
  
  -> git clone https://github.com/kunalg123/vsdflow.git.
  
  -> command to clone the vsdflow.
  
cloning git repository
<img src = "https://github.com/nageswarchedella/Physical-design-using-eda-tools/blob/main/day1/cloning%20git%20repository.png" width = 700>
 
<img src = "https://github.com/nageswarchedella/Physical-design-using-eda-tools/blob/main/day1/sta%20path.png" width = 700>


This image shows the number of regiesters used in the design by using Qflow

<img src = "https://github.com/nageswarchedella/Physical-design-using-eda-tools/blob/main/day1/registers%20percentage.png" width = 700>

Commands
  -> cd vsdflow
  
  -> ./vsdflow spi_slave_design_details.csv
  
  -> ls -ltr outdir_spi_slave/
  
  -> ls -ltr outdir_spi_slave | wc
   and here can see the total created files
   
<img src = "https://github.com/nageswarchedella/Physical-design-using-eda-tools/blob/main/day1/files%20creation.png" width = 700>




finding area
<img src = "https://github.com/nageswarchedella/Physical-design-using-eda-tools/blob/main/day1/area%20calculation.png" width = 700>


day2 
chip area
<img src="https://github.com/nageswarchedella/Physical-design-using-eda-tools/blob/main/day1/day2%20quiz.png" width=700>

# Day3
trainsistor characteristics
<img src = "https://github.com/nageswarchedella/Physical-design-using-eda-tools/blob/main/day3/tran1.png" width = 700>


post layout
<img src = "https://github.com/nageswarchedella/Physical-design-using-eda-tools/blob/main/day3/postlayout.png" width = 700>


transfer characteristics
<img src = "https://github.com/nageswarchedella/Physical-design-using-eda-tools/blob/main/day3/mcq8.png" width = 700>


dc characteristics
<img src = "https://github.com/nageswarchedella/Physical-design-using-eda-tools/blob/main/day3/mcq10.png" width = 700>


changed dc characteristics
<img src = "https://github.com/nageswarchedella/Physical-design-using-eda-tools/blob/main/day3/mcq%205.png" width = 700>


draw layout
<img src = "https://github.com/nageswarchedella/Physical-design-using-eda-tools/blob/main/day3/draw%20layout.png" width = 700>


area of the chip in microns
<img src = "https://github.com/nageswarchedella/Physical-design-using-eda-tools/blob/main/day3/d3sk3%20q4.png" width = 700>


transistor charactersistics
<img src = "https://github.com/nageswarchedella/Physical-design-using-eda-tools/blob/main/day3/d3sk3%20q5.png" width = 700>

# Day 4

inputs and outputs details
<img src = "https://github.com/nageswarchedella/Physical-design-using-eda-tools/blob/main/day%204/d4sk1%20q6.png" width = 700>


transistor characteristics
<img src = "https://github.com/nageswarchedella/Physical-design-using-eda-tools/blob/main/day%204/d4sk1%20q7.png" width = 700>


transistor characteristics
<img src = "https://github.com/nageswarchedella/Physical-design-using-eda-tools/blob/main/day%204/d4sk1%20q8.png" width = 700>


details of threshold values
<img src = "https://github.com/nageswarchedella/Physical-design-using-eda-tools/blob/main/day%204/d4sk2%20q6.png" width = 700>


power lut template details
<img src = "https://github.com/nageswarchedella/Physical-design-using-eda-tools/blob/main/day%204/d4sk2%20q8.png" width = 700>


inverter standard cell details
<img src = "https://github.com/nageswarchedella/Physical-design-using-eda-tools/blob/main/day%204/d4sk2%20q9.png" width = 700>


cell rise function details
<img src = "https://github.com/nageswarchedella/Physical-design-using-eda-tools/blob/main/day%204/d4sk2%20q10.png" width = 700>


clock and slack
<img src="https://github.com/nageswarchedella/Physical-design-using-eda-tools/blob/main/day%204/d4sk2%20q14.png" width=700>

# Day5
routing
<img src = "https://github.com/nageswarchedella/Physical-design-using-eda-tools/blob/main/day5/routing.png" width = 700>


sta log details
<img src = "https://github.com/nageswarchedella/Physical-design-using-eda-tools/blob/main/day5/d5sk2-mcq1.JPG" width = 700>


post sta details
<img src = "https://github.com/nageswarchedella/Physical-design-using-eda-tools/blob/main/day5/d5sk2-mcq2.JPG" width = 700>

