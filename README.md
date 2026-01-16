## Milesight UC100 Payload Converter with History Decoder.
In the UC100 you can set the device to log historical data when the device loses comms, it will then retransmit that data when it comes back on line.

### UC100 Decoder with history 

The following is a JS script to decode the Milesight UC100 modbus device and convert that data as well as historical transmissions into a single format for consumption by a webhook or similar.  

It uses the existing Milesight payload decoders and then puts it in a structured format. 

Currently the real time and historical is in two seperate payload formats from the device, the prupose of this is to have both real time and history data in the same format. 
