# WifiWebServer


Sample source code

    void loop(){
      WiFiClient client = server.available();   // Listen for incoming clients

      if (client) {                             // If a new client connects,
        Serial.println("New Client.");          // print a message out in the serial port
        String currentLine = "";                // make a String to hold incoming data from the client
        currentTime = millis();
    ...


Here is a link to markdown for the readme file [GitHub Markdown](https://guides.github.com/features/mastering-markdown/)

Project purpose 
---

To simulate a phone leaving the zone of a lockbox.
This is accomplished but using an Arduino board with WIFI capability to host a server that allows the user to remotely turn on and off a lock.  
