# WifiHelp
Auto reconnect wifi when have no internet access (fix lost internet after resume from window sleep).
If wifi down -> turn on wifi ap that have ssid setup in config.cmd.
If wifi still on but no internet access -> restart wifi with the same ssid.

* REQUIRE: DOT.NET 3.0

* INSTALL SERVICE:
Set SSID and check interval TICK in config.cmd before run install.cmd

* UNINSTALL SERVICE: run uninstall.cmd
