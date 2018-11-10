# NI-SystemLink-APIs-Example
We will look at how developing ‘web monitor and control application’ is made easier through NI SystemLink API

# Example: Monitor and Control a simple Temperature Controller
This is the example of a simple temperature controller that turns ON\OFF the heater to keep the temperature within the set point range. The temperature, limits and heater state data from LabVIEW VI is being continuously published to the Web page built using WebVI. I have embedded the quick demo of application through a GIF

![](https://boringengineer.com/wp-content/uploads/2018/10/Monitor-and-Control-application-demo.gif)

Demo GIF explaining the control and monitor application 

# Example: Publish and Subscribe using SystemLink Message APIs

![Alt Text](https://boringengineer.com/wp-content/uploads/2018/10/SystemLink-Code-Snapshot.png)
![Alt Text](https://boringengineer.com/wp-content/uploads/2018/10/SystemLink-Code-Snapshot-of-WebVI.png)

Above example code snapshot shows how to Publish and Subscribe to a topic using SystemLink API (in LabVIEW as well as WebVI)

- Use the URL of you NI Web Server to configure the HTTP and open SystemLink connection
- Use the SystemLink reference created to subscribe to a topic, read, publish to a topic or unsubscribe from the topic
- Based on the application, use the APIs in LabVIEW VI as well as WebVI
- Close the connection and destroy the HTTP configuration at the end

# Details on how to build this system is given [here](https://boringengineer.com/2018/10/21/web-monitor-and-control-application-using-ni-systemlink-apis/)
