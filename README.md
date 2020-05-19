 
# ddmake

[ddmake is an easy-to-use programming educational Robot]

## Basic usage

* Set the direction and speed of ddmake motor

```blocks
 ddmake.motorRun(ddmake.Motors.M1, ddmake.Dir.CW, 120)
 ddmake.motorRun(ddmake.Motors.M2, ddmake.Dir.CCW, 120)
```

* Read ultrasonic sensor

```blocks
basic.showNumber(ddmake.Ultrasonic(PingUnit.Centimeters))
```

* Set the  ddmake servos 

```blocks
ddmake.servoRun(ddmake.Servos.S1, 90)
```

* Stop the ddmake motor 

```blocks
ddmake.motorStop(ddmake.Motors.M1)
```

* Read line tracking sensor

```blocks
serial.writeNumber(ddmake.readPatrol(ddmake.Patrol.PatrolLeft))
```

* Turn on/off the LEDs

```blocks
ddmake.writeLED(ddmake.LED.LEDLeft, ddmake.LEDswitch.turnOn)
```

* Read IR sensor value

```blocks
basic.showNumber(ddmake.IR_read())
```

* Read the version number

```blocks
basic.showString(ddmake.IR_read_version())
```

## License

MIT

Copyright (c) 2018, microbit/micropython Chinese community  


## Supported targets

* for PXT/microbit
(The metadata above is needed for package search.)
