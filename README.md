# WisNode-Sense-Home-RAK7204

Adressing the "stop sending" issue. 
New periodic reset command is added.

Command: at+set_config=lora:periodic_rst_interval:xxx. xxx is the period to restart the device. The unit is in seconds.

For example, at+set_config=lora:periodic_rst_interval:86400

There are two bin files in the zip:
1. RAK7204_HF-p_rst.02.bin - For High bands - EU868, US915, etc...
2. RAK7204_LF-p_rst.02.bin - For Low bands - CN470, EU433.
