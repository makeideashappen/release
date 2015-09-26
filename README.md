# release
Release image and patch

20150821 version 0.90 : https://s3.amazonaws.com/fastbot3d-firmware/2015/fastbot-rel-0.90.tar.xz
==================================
    Patch 20150911-0.91 
      1.When thermocouple wire is disconnected, interrupt heating.
      2.Add retract_feedrate, retract_recover_feedrate profile item.
      3.Fix other bugs.

    Patch 20150926-0.92 
      1.Fix wifi hot spot.
      2.Faster dhcp assign IP address.
      3.Check hit of Limit switch.
      4.Shutdown heater when OS start.
      5.Adjustable max pwm ouput that is heat for bed and hotend.
      6.When octoprint disconnect, don't move back orign.
      7.Please modify "max z jerk" in profile from 0.4 to 4, if you have youselves profile or 3d printer isn't Delta.
      8.Fix other bugs.



Note: when the blue led light in middle of BBP board flashes, Octoprint is ready for use.









