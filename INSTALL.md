Install
=======

Requirements:
-------------
+	gcc (>=4.7)
+	Kernel (>=3.6) for the necessary LinuxCan code.
+	Kernel >=3.9

Installation:
-------------
Change working dir into the Sources.


    make
    make modules_install
    depmod -a
    modprobe ce_gw


References
==========

__Sources:__
  [https://github.com/can-eth-gw/can_eth_gw/](https://github.com/can-eth-gw/can_eth_gw/ "Sources")
__Homepage:__
  [http://can-eth-gw.github.io/](http://can-eth-gw.github.io/ "Homepage")

__Authors:__

   + Fabian Raab _<fabian.raab@tum.de>_
   + Stefan Smarzly _<stefan.smarzly@in.tum.de>_
   + Dylan Kozicki _<dylan.kozicki@gmail.com>_
