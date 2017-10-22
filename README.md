# ESPCLOCK
###### NTP-enbling a cheap $2 Ikea analog clock using ESP-12/NodeMCU/Arduino

This is a fork for clock that have a continous running gear, ie. although it looks like the second hand is running continously, it is actually running on many small pulses. The one I have runs on a 22ms positive pulse than delay for 44ms and another 22ms negative pulse cycle. Each second arc there is approx. 16 cycles. Now how accurate this still needs to be confirm. These pulses were what I observe from my scope. But one reason why I can mess with this clock is, it is actually running slow. Since for ESPCLOCK, I really only need the coil bit, I can tweet the this cycle until I get an accurate second.

### Links:

* [Project](https://hackaday.io/project/16742-espclock)
* [Blog](http://rsequence.blogspot.com/2016/10/hacking-analog-clock-to-sync-with-ntp.html)
