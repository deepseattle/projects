Hard-Learning

# Project Name

## Using machine learning to create hardware

# Project Leader

Jaime Espinosa

Project Leader Slack Username

@jaime

# Project Slack Channel

None (we just use email)
jaime.e.espinosa @ g__

# Description

**Can machine learning be used to develop circtuits that accelerate machine learning computation?**

Circuit development will be done on an FPGA. The FPGA is a gate array that can be configured into logical circuits.  There are also 
often other accelerators built in, for example DSP blocks (digital signal processing for streaming data) and RAM blocks.

In FPGA's circuits are represented by 'code' that is fed to the FPGA to configure it. So this project begins to look like 
"genetic programming".  

# Dataset

*Fitness function: speed-up (dt) 
*Learning data: test set for the circuit, and expected output (set can be generated with CPU)

*Starting small:
Matrix multiplication, for example to accelerate a simple NN that runs on CPU (like a math co-processor)
*Reach goal: develop a simple NN on chip. (pick a canonical example so we can compare with white papers)

# Hardware

Instance of an AWS EC2 F1.  It's an FPGA mounted on a linx box.  The tools and setup are preloaded and preconfigured. 

# Possible details to overcome

*The FPGA programming time is too long. Possible solution is to test multiple circuits at once by partitioning the array.
*Test set may not be complete. For simplicity we can generate tests randomly, create the answers on CPU
*This approach might give results that look overfitted -- which might be ok for this purpose. 

# Group meetup schedule

TBD 

More info...

Contact the project leader (jaime) via emai at jaime.e.espinosa @ g___.com to join the project team
