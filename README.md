# awesome-tinygo
A curated list of awesome TinyGo projects. Inspired by [awesome-go](https://github.com/avelino/awesome-go).

**Contributing**: 

* **Issues**. Please add which category you believe fits it best along with the following markdown:
    ```markdown
    * [<project name>](<project url>) - <project description>
    ```

* **Pull requests** There is no guidelines or requirements one has to meet to be added though it would be desirable the project be original.

* [Awesome TinyGo](#awesome-tinygo)
    - [Continuous Integration](#continuous-integration)
    - [Display Hardware](#display-hardware)
    - [Embedded Systems](#embedded-systems)
        - [General use](#general-use)
        - [Protocol implementations](#protocol-implementations)
        - [Instrumentation and control with sensors and actuators](#instrumentation-and-control-with-sensors-and-actuators)
    - [WebAssembly](#webassembly)
        - [WebSockets](#websockets)
        - [DOM Manipulation](#dom-manipulation)
    - [Wireless Communication](#wireless-communication)

* [Awesome TinyGo Creations](#awesome-tinygo-creations)

* [Awesome Libraries](#awesome-libraries)

* [Resources](#resources)
    - [Websites](#websites)
        - [TinyGo Community](#tinygo-community)    
        - [Tutorials](#tutorials)


# Awesome TinyGo

## Continuous Integration

* [TinyHCI](https://github.com/tinygo-org/tinyhci) - Test actual hardware connections for microcontrollers. It is intended to provide smoke test implementations that exercise the basic functionality for each kind of hardware interface for each supported microcontroller.
## Display Hardware
* [TinyDraw](https://github.com/tinygo-org/tinydraw) - Draw primitives on TinyGo displays. It is heavily based on the Adafruit GFX library.
* [TinyFont](https://github.com/tinygo-org/tinyfont) - Font/text package for TinyGo displays. It is heavily based on Adafruit's GFX library.
* [TinyTerm](https://github.com/tinygo-org/tinyterm) - A minimal terminal for TinyGo devices supporting 256-color ANSI escape codes.
* [SSD1306 font](https://github.com/Nondzu/ssd1306_font) - Lite SSD1306 OLED font library using TinyGo.



## Embedded Systems

### General use
* [go-pico](https://github.com/djthorpe/go-pico) - Raspberry Pi RP2040 Pico SDK for golang.
* [mm-go](https://github.com/joetifa2003/mm-go) - Generic manual memory management for golang
* [tinyfs](https://github.com/tinygo-org/tinyfs) - Embedded filesystems for TinyGo like FATfs and LittleFS on microcontrollers.
* [TinyGo Drivers](https://github.com/tinygo-org/drivers) - Provides a collection of hardware drivers for devices such as sensors and displays that can be used together with TinyGo.
* [bouncer](https://github.com/eyelight/bouncer) - bouncer is a button input handler library supporting press-lengths of different durations, and debouncing.

### Protocol implementations
* [achicken](https://github.com/soypat/achicken) - Dead-simple serial protocol with CRC for small projects.
* [ether-swtch](https://github.com/soypat/ether-swtch) - Low level Ethernet/IP/TCP/HTTP stack marshaller/unmarshaller for use in tiny places.
* [go-canard](https://github.com/soypat/go-canard) - CAN/OpenCyphal implementation in pure Go. Port of libcanard.
* [natiu-mqtt](https://github.com/soypat/natiu-mqtt) - A dead-simple, extensible MQTT implementation well suited for embedded systems.
* [peamodbus](https://github.com/soypat/peamodbus) - Fault tolerant, TCP modbus implementation in Go that just works. Apt for embedded systems.
* [peasocket](https://github.com/soypat/peasocket) - Dead-simple, extensible websocket implementation in Go.
* [tiny-sproto](https://github.com/soypat/tiny-sproto) - A simple Point-to-Point Protocol implementation written in Go.

### Instrumentation and control with sensors and actuators
* [fusion](https://github.com/aykevl/fusion) - Sensor fusion algorithms (gyroscope/accelerometer) implemented in pure Go.
* [magcal](https://github.com/ysoldak/magcal) - (Magical) Magnetometer Calibration
* [pctl](https://github.com/brandondube/pctl) - "process control" is a package for industrial control in Go. Filtering and control theory algorithms.


## WebAssembly
### DOM Manipulation

* [TinyDom](https://github.com/Nerzal/tinydom) - DOM manipulation library. For use in WASM

### WebSockets

* [TinyWebSocket](https://github.com/Nerzal/tinywebsocket) - Wraps the `syscall/js` api to provide a better developer experience, while being compileable by TinyGo
## Wireless Communication

* [Go Bluetooth](https://github.com/tinygo-org/bluetooth) - Go Bluetooth is a cross-platform package for using Bluetooth Low Energy hardware from the Go programming language.


# Awesome TinyGo Creations
**Hardware and software implementations**
* [Arduino Mega Programmer](https://github.com/Gustavomurta/Arduino_Mega_Programmer) - Read ROMs, EPROM, Flash of older computers such as a Commodore C128 ROM chip.
* [LED Cube](https://github.com/tinygo-org/things/tree/master/ledcube) - 6x32x32 LED cube, inspired by a LED cube I've seen at CCC and the SquareWave Dot cube.
* [HeadTracker](https://github.com/ysoldak/HeadTracker) - Bluetooth DIY Head Tracker, for Nano 33 BLE and XIAO BLE Sense boards.
* [RC PWM to RGB LED](https://github.com/ysoldak/pwm-ws2812) - WS2812 LED strip color and brightness control with two RC PWM channels

# Awesome Libraries
**Packages that make life easier or more awesome in TinyGo**

* [`math32`](https://github.com/chewxy/math32) - 32bit math functions in pure Go.
* [`mathgl`](https://github.com/go-gl/mathgl) - A pure Go 3D math library.
* [`lap`](https://github.com/soypat/lap) - Extremely lightweight linear algebra package similar to gonum.

# Resources

## Websites

### TinyGo Community

* [TinyGopher Worldmap](https://getethermap.org/m/tinygophers) - Locate Tinygophers all over the world!
### Tutorials

* [Blinky tutorial](https://github.com/tinygo-org/tinygo-site/blob/379c887947063e08bc9547a034b7ced68ab30628/content/getting-started/blinky.md) - A tutorial to get familiar with TinyGo basics.
