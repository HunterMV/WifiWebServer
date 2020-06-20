# WifiWebServer


Sample source code
<code>
void loop(){
  WiFiClient client = server.available();   // Listen for incoming clients

  if (client) {                             // If a new client connects,
    Serial.println("New Client.");          // print a message out in the serial port
    String currentLine = "";                // make a String to hold incoming data from the client
    currentTime = millis();
    previousTime = currentTime;
</code>

Here is a link to markdown for the readme file [GitHub Markdown](https://guides.github.com/features/mastering-markdown/)