# Advanced-ARM-SoC-Design

#### Design and develop an ARM Cortex M0 based SoC by interfacing the 
peripherals Timer and GPIO/LED and Synthesis it using ARTY A7 FPGA Kit 

![Screenshot 2025-01-02 001845](https://github.com/user-attachments/assets/7114396d-1644-4fba-9850-1baf1cb90d51)


#### 1) Timer is counting from ‘0F’ to ‘00’. Once the count reaches the minimum value (‘00’) , an interrupt is generated and then that is cleared (using clear register). 

#### 2) Once timer interrupt becomes high, LED peripheral should output the value ‘FF’.

#### 3) After a small delay, LED peripheral is cleared. 
