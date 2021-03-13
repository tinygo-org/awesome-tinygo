# awesome-tinygo
A curated list of awesome TinyGo projects. Inspired by [awesome-go](https://github.com/avelino/awesome-go).

Contributing: For now just pull request. There is no guidelines or requirements one has to meet to be added though it would be desirable the project be original.

* [Awesome TinyGo](#awesome-tinygo)
    - [Continuous Integration](#continuous-integration)
    - [Display Hardware](#display-hardware)
    - [Embedded Systems](#embeddded-systems)

    - [WebAssembly](#webassembly)
        - [WebSockets](#websockets)
        - [DOM Manipulation](#dom-manipulation)
    - [Wireless Communication](#wireless-communication)

* [Awesome TinyGo Creations](#awesome-projects)
   - [LED controllers](#led-controllers)

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


## Embedded Systems

* [TinyGo Drivers](https://github.com/tinygo-org/drivers) - Provides a collection of hardware drivers for devices such as sensors and displays that can be used together with TinyGo.

## WebAssembly
### DOM Manipulation

* [TinyDom](https://github.com/Nerzal/tinydom) - DOM manipulation library. For use in WASM

### WebSockets

* [TinyWebSocket](https://github.com/Nerzal/tinywebsocket) - Wraps the `syscall/js` api to provide a better developer experience, while being compileable by TinyGo
## Wireless Communication

* [Go Bluetooth](https://github.com/tinygo-org/bluetooth) - Go Bluetooth is a cross-platform package for using Bluetooth Low Energy hardware from the Go programming language.


# Awesome TinyGo Creations
**Hardware and software implementations**
## LED controllers

* [LED Cube](https://github.com/tinygo-org/things/tree/master/ledcube) - 6x32x32 LED cube, inspired by a LED cube I've seen at CCC and the SquareWave Dot cube. 

# Resources

## Websites

### TinyGo Community

* [TinyGopher Worldmap](https://getethermap.org/m/tinygophers) - Locate Tinygophers all over the world!
### Tutorials

* [Blinky tutorial](https://github.com/tinygo-org/tinygo-site/blob/379c887947063e08bc9547a034b7ced68ab30628/content/getting-started/blinky.md) - A tutorial to get familiar with TinyGo basics.