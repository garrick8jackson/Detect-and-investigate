# Detect and investigate

![image](https://github.com/garrick8jackson/Detect-and-investigate/blob/76d5d1b47981aba4b97eae34fd952bff6135cf57/detect%201.png)

After navigating to the incidents tab and adjusting the the time range range to 6 months I detected an attempt to turn off Microsoft defender antivirus protection. I clicked into the notification to view the device involved, user account involved, time of execution, event name, and incident category

![image](https://github.com/garrick8jackson/Detect-and-investigate/blob/c29b6a6b9bbf944536f0457c7fcc800c12082ded/detect%202.png)

Diving further into the event I can see the date and time of the event, severity, process name, and command line tool used to disable microsoft defender antivirus

![image](https://github.com/garrick8jackson/Detect-and-investigate/blob/12c3de41aba1d083cd5993b9bd9570611c3ffceb/detect%203.png)

If I was to categorize the event as malicious I could then collect the investigation package, start Microsoft defender XDR automated investigation, initiate a live response session, or isolate the device. 
