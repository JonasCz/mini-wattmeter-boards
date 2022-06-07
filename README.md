# Simple DC wattmeter:

Status: in progress, untested, unfinished

Features:

* Configurable with solder-jumpers, to show:
   * Volts
   * Watts
   * Amps
   * Watt-hours
   * Amp-hours

* Minimal STM8 + segment LED display
* Linear-regulator powered (max current?) - need to check, tricks with cpu sleep, display dimming on high voltage?
* XT60 in - out
* Serial ouptut multiplexed onto segment outputs, activated only between digit cycle somehow?