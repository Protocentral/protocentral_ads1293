ProtoCentral ADS1293 breakout board
================================
![ADS1293 Breakout](docs/img/IMG_20201109_205852905.jpg)
Are you looking for a miniature that can read your heart? Well, here it is!!! The ADS1293 breakout board has a capacity of 3 channels and the integration of 4 leads to the reading of the electrical activity of the heart. The ADS1293 is a simple ECG breakout that delivers excellent measurement and precision data.

This breakout board for the TI ADS1293 Analog front-end IC with three High-Resolution Digital ECG Channels With Simultaneous Pace Output helps you measure both ECG and respiration. This is a simple board to connect ECG / Respiration to your Arduino, Raspberry Pi or any microcontroller you like.

Features
--------
* ADS1293 Analog Front End IC.
* Three High-Resolution Digital ECG Channels.
* Low Power: 0.3 mW/channel.
* Onboard 3.3V voltage regulator for low noise.
* Onboard logic level translators for Arduino interface.
* Prototyping area for adding additional components.

Includes
--------
* ADS1293 Breakout Board
* Electrode cable with 3.5mm connector
* Pack of disposable stick-on ECG electrodes-10 each

## Wiring to your Arduino

|ADS1293 Pin | Pin Function         |Arduino Uno Pin Connection|
|-----------------|:--------------------:|-----------------:|
| DRDY            | Data ready Output pin|  D2              |             
| MISO            | Slave Out            |  D12             |
| MOSI            | Slave In             |  D11             |
| SCLK            | Serial Clock         |  D13             |
| CS              | Chip Select          |  D10             |
| vcc             | Digital VDD          |  +5V             |
| GND             | Digital Gnd          |  Gnd             |


License Information
===================

This product is open source! Both, our hardware and software are open source and licensed under the following licenses:

Hardware
---------

**All hardware is released under [Creative Commons Share-alike 4.0 International](http://creativecommons.org/licenses/by-sa/4.0/).**
![CC-BY-SA-4.0](https://i.creativecommons.org/l/by-sa/4.0/88x31.png)

You are free to:

* Share — copy and redistribute the material in any medium or format
* Adapt — remix, transform, and build upon the material for any purpose, even commercially.
The licensor cannot revoke these freedoms as long as you follow the license terms.

Under the following terms:

* Attribution — You must give appropriate credit, provide a link to the license, and indicate if changes were made. You may do so in any reasonable manner, but not in any way that suggests the licensor endorses you or your use.
* ShareAlike — If you remix, transform, or build upon the material, you must distribute your contributions under the same license as the original.

Software
--------

**All software is released under the MIT License(http://opensource.org/licenses/MIT).**

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.


Please check [*LICENSE.md*](LICENSE.md) for detailed license descriptions.
