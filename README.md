# froakie
Stratum 1 NTP server based on Raspberry Pi

----

oh, hi stranger!

that's just a simplest stratum 1 NTP server in this world ever.
right now i'm writing some docs about it, but currently it's just a bunch of drafts because
there is too much poopy things about time correction between NMEA packets and PPS

so, just remember - that is only a draft things, totally not suitable for production purposes

but if you enough brave to use it - here is a little description of files:

  - **ntp.conf** - ntpd configuration
  - **ntp.rules** - bunch of udev rules for ntpd-friendly device names
  - **cmdline.txt** - our example of kernel boot cmdline (be very carefull with it, especially on rootfstype)
  - **config.txt** - our example RPI boot configuration that suitable for NTP server

i think that's all for this time, and you can make this world better with your suggestions, commits and etc!

please stand by and keep being a good kitties ~

peace!