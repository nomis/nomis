Highlights ✨
=============

A few of the many `repositories <https://github.com/nomis?tab=repositories>`_...

Applications and libraries 📦
-----------------------------

`dtee <https://github.com/nomis/dtee>`_ (double tee)
    Split and recombine standard output and standard error (primarily to detect
    output to standard error when running things from
    `cron <https://en.wikipedia.org/wiki/Cron>`_)

`fiv <https://github.com/nomis/fiv>`_ (Fast Image Viewer)
    Minimal image viewer to support rapid navigation and selection of large
    (50MP) JPEG photos. It preloads multiple images before and after the current
    image into memory so that it takes practically no time to switch between
    them.

`mcu-uuid-log <https://github.com/nomis/mcu-uuid-log>`_, `mcu-uuid-syslog <https://github.com/nomis/mcu-uuid-syslog>`_, `mcu-uuid-console <https://github.com/nomis/mcu-uuid-console>`_, `mcu-uuid-telnet <https://github.com/nomis/mcu-uuid-telnet>`_
    Console shell for ESP (and other Arduino-based) microcontrollers with
    tab completion and integrated logging framework (log output is displayed
    above the shell prompt so that it doesn't interrupt commands being typed)

`mcu-uuid-modbus <https://github.com/nomis/mcu-uuid-modbus>`_
    Asynchronous modbus library for ESP (and other Arduino-based)
    microcontrollers

`qmk-hid-identify <https://github.com/nomis/qmk-hid-identify>`_
    Identify the current OS to `QMK <https://qmk.fm/>`_ [keyboard] device
    (currently only supports Linux and Windows)

`aurora-coriolis <https://github.com/nomis/aurora-coriolis>`_
    ESP32 WS281x multi-channel LED controller with MicroPython

    (Needs documentation on how to use it)

`candle-dribbler <https://github.com/nomis/candle-dribbler>`_
    ESP32 Zigbee multi-channel light controller

`eightfold-seal <https://github.com/nomis/eightfold-seal>`_
    ESP32 Zigbee door open alarm

`tempus-redux <https://github.com/nomis/tempus-redux>`_
    ESP32 "Time from NPL" (MSF) Radio clock signal generator

`slf4j-android <https://github.com/nomis/slf4j-android>`_
    `SLF4J <https://slf4j.org/>`_ binding for the
    `Android logger <https://developer.android.com/reference/android/util/Log>`_

`bookmarks <https://github.com/nomis/bookmarks>`_
    Bookmarks management website and Ruby on Rails experiment

`all-the-maps <https://github.com/nomis/all-the-maps>`_
    `Web page <https://maps.uuid.uk/>`_ with links to all the map services for a `latitude/longitude location <https://maps.uuid.uk/#38.897778,-77.036389>`_

`cursus-core <https://github.com/nomis/cursus-core>`_, `cursus-ui <https://github.com/nomis/cursus-ui>`_
    Race series management program (incomplete but able to calculate results)

Contributions to other projects 🎁
----------------------------------

`linux <https://github.com/nomis/linux>`_
    * Support for full size (1500 byte) packets on
      `PPPoE <https://en.wikipedia.org/wiki/Point-to-Point_Protocol_over_Ethernet>`_
      with `RFC4638 <https://datatracker.ietf.org/doc/html/rfc4638>`_ (see also:
      `ppp <https://github.com/nomis/ppp>`_ repository)

    * Raspberry Pi (BCM2835) peripheral drivers for the interrupt controller,
      timer, watchdog, DMA, SDHCI, etc. (only some of these have made it into
      the mainline kernel)

    * V4L/DVB bug fixes

    * DSL stats on the Conexant AccessRunner USB ADSL modem

`GnuCash <https://github.com/nomis/gnucash>`_ (personal and small-business financial-accounting software)
    * Previous and next working day behaviour for scheduled transactions

    * Display blank/new transaction at the current date instead of after future
      transactions (essential when there are 3 months of future dated scheduled
      transactions)

    * Quickly switch tab position from the View menu

    * Performance improvements with large files and many open registers

    * Better handling of complex Jump to other split operations

    * Various bug fixes, new preferences and British English translations

`charybdis <https://github.com/nomis/charybdis>`_ (IRC server)
    * Support restarting ssld processes (to upgrade the TLS library) without
      affecting existing connections

    * Support `SCTP <https://en.wikipedia.org/wiki/Stream_Control_Transmission_Protocol>`_
      for dual IPv4+IPv6 use making server to server connections more reliable

Scripts and tools 🧰
--------------------

`intel-amt <https://github.com/nomis/intel-amt>`_
    Python tools for interacting with `Intel's AMT <https://en.wikipedia.org/wiki/Intel_Active_Management_Technology>`_
    hardware control interfaces (modified to allow provisioning of X.509
    certificates for TLS)

`rlmutag <https://github.com/nomis/rlmutag>`_
    Music tagging program using a multiple-history GNU readline interface
    (optimised for minimum effort sequential entry)

`sshfp <https://github.com/nomis/sshfp>`_
    Format SSH host key fingerprints in a text file and GPG sign it

`wsl-assuan-unix-proxy <https://github.com/nomis/wsl-assuan-unix-proxy>`_
    Windows Subsystem for Linux Assuan Unix Proxy (capable of forwarding the GPG
    agent to a remote host)

Other stuff 🤪
--------------

`logitech-z906 <https://github.com/nomis/logitech-z906>`_
    Unofficial documentation for Logitech® Z906 Surround Sound Speakers

`ikea-tradfri-e1812 <https://github.com/nomis/ikea-tradfri-e1812>`_
    Unofficial documentation for the IKEA® TRÅDFRI Shortcut Button (E1812)

`utility-usage-website <https://github.com/nomis/utility-usage-website>`_, `network-traffic-usage-website <https://github.com/nomis/network-traffic-usage-website>`_
    Rendering client-side SVG graphs and HTML pages with XSLT 1.0

`rf433-ook <https://github.com/nomis/rf433-ook>`_
    Arduino 433MHz OOK Receiver/Transmitter (realtime sampling of the code
    period without running out of time to handle the next interrupt)

`scd30 <https://github.com/nomis/scd30>`_
    Monitoring of temperature, humidity and CO₂ using a SCD30 sensor

Work in progress 🚧
-------------------

`ggroohauga <https://github.com/nomis/ggroohauga>`_
    Alternative console and simulated amplifier interface for the ESP32-S3
    microcontroller interacting with Logitech® Z906 Surround Sound Speakers

`hx711-weigh-scales-logger <https://github.com/nomis/hx711-weigh-scales-logger>`_
    Data logger for the `HX711 <https://cdn.sparkfun.com/datasheets/Sensors/ForceFlex/hx711_english.pdf>`_
    24-Bit `ADC <https://en.wikipedia.org/wiki/Analog-to-digital_converter>`_
    for Weigh Scales
