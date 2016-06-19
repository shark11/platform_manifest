Mediatek Open Kang Project
============================

The Project
-----------

Based on AOSP with Slim+CM modifications. We are trying to make best in class, stable, daily driver and easy to use ROM.
This is a WORK-IN-PROGRESS project. We are no 'professionals', just learning to become ones.

Do refer the [AOSP building guide](http://source.android.com/source/index.html) before proceeding.

Setting up Repository
---------------------

Initiate manifest in local directory:

    $ mkdir MOKP && cd MOKP
    $ repo init -u https://github.com/TeamMOKP/platform_manifest.git -b android-6.0

Sync the repository:

    $ repo sync

***

Building
--------

After the sync is finished, please read the [instructions from the Android site](http://s.android.com/source/building.html) on how to build.

    $ . build/envsetup.sh
    $ lunch

You can also build for specific devices (eg. mt6582) like this:

    $ . build/envsetup.sh
    $ brunch mokp_mt6582-userdebug

TeamMOKP
--------

    - rohantaneja (Rohan Taneja)
    - UchihaDev (Ajit Guraya)
    - MrUnt1tled (John Reinel Caluag)
    - diparthshah (DIPARTH SHAH)
    - Roger That Members (Pawan, Ashutosh, Vipul, Pranav, Ankit)

Special Mention
---------------
Thanks to following developers, who made CyanogenMod on Mediatek possible.

    - Santhosh M
    - ferhung-mtk
    - ariafan 
    - superdragonpt
    - Al3XKOoL
    - chrmhoffmann
    - fire855
    - axet
    - chrmhoffmann
    - DerTeufel1980
    - xen0n
    - and other devs...
