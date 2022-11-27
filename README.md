# General Description
Hello together,

I found another workaround which can help with the problem that the PC causes bluescreens through the network adapter.

Please note here that there is a risk that this workaround may not necessarily fix the problem.

# Workaround
If you also have the problem with the I225-V network adapter, you should follow these steps, as they helped with my case.

I had multiple bluescreens for a while whenever I was gaming and never knew what the problem was. My guess was always the temperature,
but it was almost in the green zone.

After a long time of trying, I got the idea that it could be the network adapter, because according to the motherboard I have 2.5 GB Ethernet,
but my cables can only transfer 100 MB natively, which probably triggered some exception in Windows. As a result, I throttled the transfer speed,
which is shown in the next step.

1. open the device manager
2. navigate to the "network adapter" tab
3. search for the "I225-V" adapter, right-click on it and open its properties
4. after the window opens, go to the "Advanced" tab
5. now search for "Speed and Duplex" and try to set the speed of "Auto negotiation" to a fixed full duplex value

# YouTube
https://www.youtube.com/watch?v=99vEoNPO5zk
