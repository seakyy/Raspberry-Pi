# Raspberry-Pi
Documentation about the Raspberry Pi 5


## Photos


# How to Connect to a Raspberry Pi 5 Without a Mini HDMI and Still Get a Display
First, place your Raspberry Pi 5 into the Argon NEO 5 Case for better airflow and cooling.

Next, take your microSD card, install your preferred Raspberry Pi OS from the official website, and format the card if necessary.

After that, connect your power supply (via the USB-C port) and insert the microSD card into the Raspberry Pi.

After a few seconds, the Pi should boot up completely.

Now, scan your network to confirm that the Raspberry Pi is working correctly. I used Angry IP Scanner for this.

In this application, search for the hostname "raspberrypi.local"—this will be your Raspberry Pi. The corresponding IP address of the Pi will also be displayed there.

Next, open PuTTY and connect to your Raspberry Pi using the IP address you found in the IP scan.

Once connected, enter the following command:

```bash
sudo raspi-config
```

Go to "Advanced Options" (Option 6) and select "Display Options" (Option 2).

Reboot your Raspberry Pi.

Now, you can use VNC Viewer to connect to your Raspberry Pi 5.

Enter the IP address of the Pi and click Connect.

After a short while, you should see the Raspberry Pi’s desktop on your screen.

Congratulations! Your Raspberry Pi is now set up for remote access!



