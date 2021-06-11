# Intrusion-alert-system
Arduino IDE is used for writting code of Arduino, language used is c. 
The Arduino code triggers the ultrasonic sound sensor and fetches value through the echo pin of sensor. The fetched data corresponds to soundwave travel duration, which is then converted into distance by program. This distance is sent to IoT platform in order to compare current data with threshold. As soon as threshold is crossed a notification is sent to registered user by sms/mail. Also, the buzzer is triggered high, so as to make awareness in surrounding.
Different libraries are instantiated for interfacing Arduino with iot board. The baud rate of serial communication of each board is kept 9600.
Turn on the trig pin of sensor and Send a sound wave and wait for 10 Micro seconds so that the operation happens and then turn off the pin. Get the sound wave reflection time through echo pin and convert the duration to centimetres and print on serial monitor.
