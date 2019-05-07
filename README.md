# Thingspeak_processing                                                                                                             
Connect Arduino to Thingspeak using processing IDE                                                                                  
This code is used to send any sensor values received from Arduino to Thingspeak using processing IDE.                                                                                            
                                                                                                                                          
PROCESSING IDE                                                                                                                                
Processing IDE uses a sketchbook that can gather data by blocking the serial port of Arduino sketch and throw the data to the specified URL.                                                                                                                                
Note: Arduino Code provided here sends current sensor values to thingspeak and displays the same in Lcd. Processing will look for the keyword "begin" sent to the Serial port and passes the consecutive values. 
