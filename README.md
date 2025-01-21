# awesome-tinygo
A curated list of awesome TinyGo projects. Inspired by [awesome-go](https://github.com/avelino/awesome-go).

**Contributing**:

* **Issues**. Please add which category you believe fits it best along with the following markdown:
    ```markdown
    * [<project name>](<project url>) - <project description>
    ```

* **Pull requests** There are no guidelines or requirements one has to meet to be added though it would be desirable the project be original.

* [Awesome TinyGo](#awesome-tinygo)
    - [Code Editing](#code-editing)
    - [Continuous Integration](#continuous-integration)
    - [Display Hardware](#display-hardware)
    - [Embedded Systems](#embedded-systems)
        - [General use](#general-use)
        - [Protocol implementations](#protocol-implementations)
        - [Instrumentation and control with sensors and actuators](#instrumentation-and-control-with-sensors-and-actuators)
    - [Gaming](#gaming)
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

## Code Editing
* [VSCode](https://github.com/tinygo-org/vscode-tinygo) - TinyGo support for Visual Studio Code.
* [Goland](https://plugins.jetbrains.com/plugin/16915-tinygo) - TinyGo support for Goland.
* [Vim](https://github.com/sago35/tinygo.vim) - TinyGo support for Vim/NeoVim.
* [bash/zsh/clink](https://github.com/sago35/tinygo-autocmpl) - Adds bash/zsh/clink auto-completion to TinyGo.
* [Display Simulator](https://github.com/sago35/tinydisplay) - `tinydisplay` is a tiny display for TinyGo development.

## Continuous Integration
* [TinyHCI](https://github.com/tinygo-org/tinyhci) - Test actual hardware connections for microcontrollers. It is intended to provide smoke test implementations that exercise the basic functionality for each kind of hardware interface for each supported microcontroller.

## Display Hardware
* [TinyDraw](https://github.com/tinygo-org/tinydraw) - Draw primitives on TinyGo displays. It is heavily based on the Adafruit GFX library.
* [TinyFont](https://github.com/tinygo-org/tinyfont) - Font/text package for TinyGo displays. It is heavily based on Adafruit's GFX library.
* [TinyTerm](https://github.com/tinygo-org/tinyterm) - A minimal terminal for TinyGo devices supporting 256-color ANSI escape codes.
* [SSD1306 font](https://github.com/Nondzu/ssd1306_font) - Lite SSD1306 OLED font library using TinyGo.



## Embedded Systems

### General use
* [bouncer](https://github.com/eyelight/bouncer) - bouncer is a button input handler library supporting press-lengths of different durations, and debouncing.
* [fat](https://github.com/soypat/fat) - Filesystem implementation using the File Allocation Table in pure Go.
* [go-maquina](https://github.com/soypat/go-maquina) - Finite State Machine (FSM) implementation with simplicity and maintainability in mind using Go generics.
* [go-pico](https://github.com/djthorpe/go-pico) - Raspberry Pi RP2040 Pico SDK for golang.
* [mm-go](https://github.com/joetifa2003/mm-go) - Generic manual memory management for golang.
* [periph/devices](https://github.com/periph/devices) - Device drivers.
* [schedule](https://github.com/soypat/schedule) - Event-loop scheduling library for synchronizing actions over long periods of time.
* [tinyfs](https://github.com/tinygo-org/tinyfs) - Embedded filesystems for TinyGo like FATfs and LittleFS on microcontrollers.
* [TinyGo Drivers](https://github.com/tinygo-org/drivers) - Provides a collection of hardware drivers for devices such as sensors and displays that can be used together with TinyGo.

### Protocol implementations
* [achicken](https://github.com/soypat/achicken) - Dead-simple serial protocol with CRC for small projects.
* [ether-swtch](https://github.com/soypat/ether-swtch) - Low level Ethernet/IP/TCP/HTTP stack marshaller/unmarshaller for use in tiny places.
* [go-canard](https://github.com/soypat/go-canard) - CAN/OpenCyphal implementation in pure Go. Port of libcanard.
* [gomavlib](https://github.com/bluenviron/gomavlib) - Mavlink protocol (2.0 and 1.0) implementation in Go for control and instrumentation of autonomous vehicles.
* [mlkem768](https://github.com/FiloSottile/mlkem768) - Quantum-resistant key encapsulation method ML-KEM (formerly known as Kyber) implementation in Go.
* [natiu-mqtt](https://github.com/soypat/natiu-mqtt) - A dead-simple, extensible MQTT implementation well suited for embedded systems.
* [peamodbus](https://github.com/soypat/peamodbus) - Fault tolerant, TCP modbus implementation in Go that just works. Apt for embedded systems.
* [peasocket](https://github.com/soypat/peasocket) - Dead-simple, extensible websocket implementation in Go.
* [seqs](https://github.com/soypat/seqs) - Networking library for use on microcontrollers. Basically a more featureful LWIP.
* [tiny-sproto](https://github.com/soypat/tiny-sproto) - A simple Point-to-Point Protocol implementation written in Go.

### Instrumentation and control with sensors and actuators
* [fusion](https://github.com/aykevl/fusion) - Sensor fusion algorithms (gyroscope/accelerometer) implemented in pure Go.
* [magcal](https://github.com/ysoldak/magcal) - (Magical) Magnetometer Calibration
* [pctl](https://github.com/brandondube/pctl) - "process control" is a package for industrial control in Go. Filtering and control theory algorithms.

## Gaming
* [Hunt the Wumpus](https://github.com/smittytone/pi-pico-go.git) - Handheld gaming powered by the Raspberry Pi Pico and TinyGo.
* [tinygba](https://github.com/tinygo-org/tinygba) - Tools and helpers for developing GBA programs using TinyGo.
* [gonx](https://github.com/racerxdl/gonx) - Wrapper around libnx for developing Nintendo Switch programs using TinyGo.
* [Flapy Boot](https://github.com/bjatkin/flappy-boot) - clone of flappy bird for the GBA written using TinyGo.
* [koebiten](https://github.com/sago35/koebiten) - Koebiten is a 2D game engine that runs on TinyGo. It’s inspired by Ebitengine and is characterized by its simple API.


## WebAssembly

### DOM Manipulation

* [TinyDom](https://github.com/Nerzal/tinydom) - DOM manipulation library. For use in WASM
* [GoUI](https://github.com/goui-org/goui) - A web framework for making user interfaces

### WebSockets

* [TinyWebSocket](https://github.com/Nerzal/tinywebsocket) - Wraps the `syscall/js` api to provide a better developer experience, while being compilable by TinyGo

## Wireless Communication

* [Go Bluetooth](https://github.com/tinygo-org/bluetooth) - Go Bluetooth is a cross-platform package for using Bluetooth Low Energy hardware from the Go programming language.


# Awesome TinyGo Creations
**Hardware and software implementations**
* [Arduino Mega Programmer](https://github.com/Gustavomurta/Arduino_Mega_Programmer) - Read ROMs, EPROM, Flash of older computers such as a Commodore C128 ROM chip.
* [LED Cube](https://github.com/tinygo-org/things/tree/master/ledcube) - 6x32x32 LED cube, inspired by a LED cube I've seen at CCC and the SquareWave Dot cube.
* [HeadTracker](https://github.com/ysoldak/HeadTracker) - Bluetooth DIY Head Tracker, for Nano 33 BLE and XIAO BLE Sense boards.
* [RC PWM to RGB LED](https://github.com/ysoldak/pwm-ws2812) - WS2812 LED strip color and brightness control with two RC PWM channels
* [USB HID Keyboard firmware for TinyGo](https://github.com/sago35/tinygo-keyboard) - keyboard firmware for tinygo
* [Gopherbot](https://github.com/hybridgroup/gopherbot) - A robotic gopher plushie that you can code using TinyGo
* [Gobadge](https://github.com/tinygo-org/gobadge) - TinyGo powered badge using Adafruit Pybadge Hardware
* [TinyGlobo](https://github.com/hybridgroup/tinyglobo) - A pico balloon floats into the great big world, towing a RP2040 Pico programmed with TinyGo using LoraWAN to communicate along the way.
* [FPV Combat Gadget](https://github.com/ysoldak/fpvc-gadget) - [FPV Combat](https://fpv-combat.com/) configurator with display and a rotary encoder (multi-level menu system with input), runs on XIAO.
* [gopher-board](https://github.com/sat0ken/gopher-board) - Original board with Gopher design for Waveshare RP2040-Zero and XIAO.
* [gopher.pretty](https://github.com/sat0ken/gopher.pretty) - Kicad footprint file of Gopher design. Lets you make your own board.

# Awesome Libraries
**Packages that make life easier or more awesome in TinyGo**
* [`cbor`](https://github.com/fxamacker/cbor) - Library for encoding and decoding Concise Binary Object Representation data and Sequences (RFC8949).
* [`cereal`](https://github.com/soypat/cereal) - All-you-need serial device tooling integrating bugst, goburrow, tarm and sers serial libraries.
* [`float16`](https://github.com/x448/float16) - IEEE 754 half-precision floating-point format (binary16) library.
* [`godsp`](https://github.com/goccmack/godsp) - Basic digital signal processing functions using the discrete wavelet transform (DWT).
* [`lap`](https://github.com/soypat/lap) - Extremely lightweight linear algebra package similar to gonum.
* [`math32`](https://github.com/chewxy/math32) - 32bit math functions in pure Go.
* [`mathgl`](https://github.com/go-gl/mathgl) - A pure Go 3D math library.
* [`tvd`](https://github.com/soypat/tvd) - Total Variation Denoising filter ideal for capturing edge transitions.
* [`u-root`](https://github.com/u-root/u-root) - Go versions of many standard Linux tools, such as ls, cp, or shutdown among other awesome OS stuff.

# Resources

## Websites

### TinyGo Community

* [TinyGopher Worldmap](https://getethermap.org/m/tinygophers) - Locate Tinygophers all over the world!
### Tutorials

* [Blinky tutorial](https://github.com/tinygo-org/tinygo-site/blob/379c887947063e08bc9547a034b7ced68ab30628/content/getting-started/blinky.md) - A tutorial to get familiar with TinyGo basics.
