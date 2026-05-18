# Add Custom Libraries to DrawIO / diagrams.net

This repository contains local/custom draw.io library XML files for diagrams.net.

## Load a custom library from the web

You can load these libraries directly from GitHub by using the raw URLs below.

## RAW URLs

```text
https://raw.githubusercontent.com/vanimal666/draw.io.io/refs/heads/main/Battery-Lithium.xml
https://raw.githubusercontent.com/vanimal666/draw.io.io/refs/heads/main/Battery.xml
https://raw.githubusercontent.com/vanimal666/draw.io.io/refs/heads/main/Bms.xml
https://raw.githubusercontent.com/vanimal666/draw.io.io/refs/heads/main/Busbar.xml
https://raw.githubusercontent.com/vanimal666/draw.io.io/refs/heads/main/Charger.xml
https://raw.githubusercontent.com/vanimal666/draw.io.io/refs/heads/main/Circuit-Breaker.xml
https://raw.githubusercontent.com/vanimal666/draw.io.io/refs/heads/main/Combiner.xml
https://raw.githubusercontent.com/vanimal666/draw.io.io/refs/heads/main/Communication.xml
https://raw.githubusercontent.com/vanimal666/draw.io.io/refs/heads/main/Connector.xml
https://raw.githubusercontent.com/vanimal666/draw.io.io/refs/heads/main/Controller.xml
https://raw.githubusercontent.com/vanimal666/draw.io.io/refs/heads/main/Converter.xml
https://raw.githubusercontent.com/vanimal666/draw.io.io/refs/heads/main/Display.xml
https://raw.githubusercontent.com/vanimal666/draw.io.io/refs/heads/main/Distribution.xml
https://raw.githubusercontent.com/vanimal666/draw.io.io/refs/heads/main/Fuse.xml
https://raw.githubusercontent.com/vanimal666/draw.io.io/refs/heads/main/Generator.xml
https://raw.githubusercontent.com/vanimal666/draw.io.io/refs/heads/main/Icon.xml
https://raw.githubusercontent.com/vanimal666/draw.io.io/refs/heads/main/Inverter-Charger.xml
https://raw.githubusercontent.com/vanimal666/draw.io.io/refs/heads/main/Inverter.xml
https://raw.githubusercontent.com/vanimal666/draw.io.io/refs/heads/main/Isolation-Transformer.xml
https://raw.githubusercontent.com/vanimal666/draw.io.io/refs/heads/main/Isolator.xml
https://raw.githubusercontent.com/vanimal666/draw.io.io/refs/heads/main/Miscellaneous.xml
https://raw.githubusercontent.com/vanimal666/draw.io.io/refs/heads/main/Mppt.xml
https://raw.githubusercontent.com/vanimal666/draw.io.io/refs/heads/main/Sensor.xml
https://raw.githubusercontent.com/vanimal666/draw.io.io/refs/heads/main/Shunt.xml
https://raw.githubusercontent.com/vanimal666/draw.io.io/refs/heads/main/Solar-Charge-Controller.xml
https://raw.githubusercontent.com/vanimal666/draw.io.io/refs/heads/main/Solar.xml
https://raw.githubusercontent.com/vanimal666/draw.io.io/refs/heads/main/Switch.xml
https://raw.githubusercontent.com/vanimal666/draw.io.io/refs/heads/main/Wire.xml
```

## Add directly to DrawIO configuration

The raw URLs are required to be URL-encoded and prepended with `U`.

In diagrams.net / draw.io:

1. Click **Extras**.
2. Click **Configuration**.
3. Click **Preferences**.
4. Add these entries to the `customLibraries` array.

```json
    "Uhttps%3A%2F%2Fraw.githubusercontent.com%2Fvanimal666%2Fdraw.io.io%2Frefs%2Fheads%2Fmain%2FBattery-Lithium.xml",
    "Uhttps%3A%2F%2Fraw.githubusercontent.com%2Fvanimal666%2Fdraw.io.io%2Frefs%2Fheads%2Fmain%2FBattery.xml",
    "Uhttps%3A%2F%2Fraw.githubusercontent.com%2Fvanimal666%2Fdraw.io.io%2Frefs%2Fheads%2Fmain%2FBms.xml",
    "Uhttps%3A%2F%2Fraw.githubusercontent.com%2Fvanimal666%2Fdraw.io.io%2Frefs%2Fheads%2Fmain%2FBusbar.xml",
    "Uhttps%3A%2F%2Fraw.githubusercontent.com%2Fvanimal666%2Fdraw.io.io%2Frefs%2Fheads%2Fmain%2FCharger.xml",
    "Uhttps%3A%2F%2Fraw.githubusercontent.com%2Fvanimal666%2Fdraw.io.io%2Frefs%2Fheads%2Fmain%2FCircuit-Breaker.xml",
    "Uhttps%3A%2F%2Fraw.githubusercontent.com%2Fvanimal666%2Fdraw.io.io%2Frefs%2Fheads%2Fmain%2FCombiner.xml",
    "Uhttps%3A%2F%2Fraw.githubusercontent.com%2Fvanimal666%2Fdraw.io.io%2Frefs%2Fheads%2Fmain%2FCommunication.xml",
    "Uhttps%3A%2F%2Fraw.githubusercontent.com%2Fvanimal666%2Fdraw.io.io%2Frefs%2Fheads%2Fmain%2FConnector.xml",
    "Uhttps%3A%2F%2Fraw.githubusercontent.com%2Fvanimal666%2Fdraw.io.io%2Frefs%2Fheads%2Fmain%2FController.xml",
    "Uhttps%3A%2F%2Fraw.githubusercontent.com%2Fvanimal666%2Fdraw.io.io%2Frefs%2Fheads%2Fmain%2FConverter.xml",
    "Uhttps%3A%2F%2Fraw.githubusercontent.com%2Fvanimal666%2Fdraw.io.io%2Frefs%2Fheads%2Fmain%2FDisplay.xml",
    "Uhttps%3A%2F%2Fraw.githubusercontent.com%2Fvanimal666%2Fdraw.io.io%2Frefs%2Fheads%2Fmain%2FDistribution.xml",
    "Uhttps%3A%2F%2Fraw.githubusercontent.com%2Fvanimal666%2Fdraw.io.io%2Frefs%2Fheads%2Fmain%2FFuse.xml",
    "Uhttps%3A%2F%2Fraw.githubusercontent.com%2Fvanimal666%2Fdraw.io.io%2Frefs%2Fheads%2Fmain%2FGenerator.xml",
    "Uhttps%3A%2F%2Fraw.githubusercontent.com%2Fvanimal666%2Fdraw.io.io%2Frefs%2Fheads%2Fmain%2FIcon.xml",
    "Uhttps%3A%2F%2Fraw.githubusercontent.com%2Fvanimal666%2Fdraw.io.io%2Frefs%2Fheads%2Fmain%2FInverter-Charger.xml",
    "Uhttps%3A%2F%2Fraw.githubusercontent.com%2Fvanimal666%2Fdraw.io.io%2Frefs%2Fheads%2Fmain%2FInverter.xml",
    "Uhttps%3A%2F%2Fraw.githubusercontent.com%2Fvanimal666%2Fdraw.io.io%2Frefs%2Fheads%2Fmain%2FIsolation-Transformer.xml",
    "Uhttps%3A%2F%2Fraw.githubusercontent.com%2Fvanimal666%2Fdraw.io.io%2Frefs%2Fheads%2Fmain%2FIsolator.xml",
    "Uhttps%3A%2F%2Fraw.githubusercontent.com%2Fvanimal666%2Fdraw.io.io%2Frefs%2Fheads%2Fmain%2FMiscellaneous.xml",
    "Uhttps%3A%2F%2Fraw.githubusercontent.com%2Fvanimal666%2Fdraw.io.io%2Frefs%2Fheads%2Fmain%2FMppt.xml",
    "Uhttps%3A%2F%2Fraw.githubusercontent.com%2Fvanimal666%2Fdraw.io.io%2Frefs%2Fheads%2Fmain%2FSensor.xml",
    "Uhttps%3A%2F%2Fraw.githubusercontent.com%2Fvanimal666%2Fdraw.io.io%2Frefs%2Fheads%2Fmain%2FShunt.xml",
    "Uhttps%3A%2F%2Fraw.githubusercontent.com%2Fvanimal666%2Fdraw.io.io%2Frefs%2Fheads%2Fmain%2FSolar-Charge-Controller.xml",
    "Uhttps%3A%2F%2Fraw.githubusercontent.com%2Fvanimal666%2Fdraw.io.io%2Frefs%2Fheads%2Fmain%2FSolar.xml",
    "Uhttps%3A%2F%2Fraw.githubusercontent.com%2Fvanimal666%2Fdraw.io.io%2Frefs%2Fheads%2Fmain%2FSwitch.xml",
    "Uhttps%3A%2F%2Fraw.githubusercontent.com%2Fvanimal666%2Fdraw.io.io%2Frefs%2Fheads%2Fmain%2FWire.xml",
```

NOTE: Some libraries are large and may take a moment to load.

## Raw base URL

```text
https://raw.githubusercontent.com/vanimal666/draw.io.io/refs/heads/main/
```
