# RPi CM4 - LiM Carrier Board

A minimalistic Raspberry Pi (RPi) Compute Module 4 (CM4) Carrier Board. Less is More (LiM) refers to the minimalistic design only providing 5V power via USB-C power connector and two status (power/activity) LEDs.

This is meant for CM4 boards with onboard storage and wifi as this carrier boards provides no other functionalty other than power and status LEDs.

LiM Carrier Board - top view             |  LiM Carrier Board - bottem view
:-------------------------:|:-------------------------:
![Rendered RPi CM4 LiM Carrier Board PCB Top](https://raw.githubusercontent.com/l00nix/rpi-cm4-LiM-board/main/images/rpi-cm4-LiM-board-top.PNG)  |  ![Rendered RPi CM4 LiM Carrier Board PCB Bottom](https://raw.githubusercontent.com/l00nix/rpi-cm4-LiM-board/main/images/rpi-cm4-LiM-board-bottom.PNG)

The idea for such a minimalistic board was born from a conversation with [Jeff Geerling](https://www.jeffgeerling.com/) when I asked him if he know of a more minimalistic design than [this board](https://www.tindie.com/products/dronecz/minimal-carrier-board-for-compute-module-4/)? He pointed me to to uptime.lab's [Upberry](https://www.instagram.com/p/CPGakesLwBo/).

Neither of these boards are exactly what I was looking for for my use case. So insipired by Jeff I decided to design my own, customized board to my specs and that how the Less-is-More board came to be. 

I forked this board design from [Shawn Hymel](https://github.com/ShawnHymel/rpi-cm4-base-carrier). He has a two part youtube series where he goes through how to design a CM4 Carrier Board.

- [Part 1 - How to Make a Raspberry Pi Compute Module 4 Carrier Board in KiCad](https://www.youtube.com/watch?v=ypcPJC_umPQ)
- [Part 2 - How to Make a Raspberry Pi Compute Module 4 Carrier Board in KiCad](https://www.youtube.com/watch?v=ge6gYIENo8Q&t)

Feel free to modify this design for your own application. This PCB is currently being prototyped and a case is in the works as well.

Other iterations of the LiM board, inlcuding SD card tray and flashing capability are in the design stages.

You can read more about my RPi musings and projects on my [l00nix's RPi Musings Blog](https://rpi.loonix.ca/).

## License

Schematic and PCB layout files are licensed under the [CC BY 4.0](https://creativecommons.org/licenses/by/2.0/) license.

Individual components and footprints found in the CM4IO library are licensed as per the Design Files license found [here](https://datasheets.raspberrypi.org/license.html).

THE DESIGN IS PROVIDED "AS IS" AND THE AUTHOR DISCLAIMS ALL WARRANTIES WITH REGARD TO THIS DESIGN INCLUDING ALL IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS. IN NO EVENT SHALL THE AUTHOR BE LIABLE FOR ANY SPECIAL, DIRECT, INDIRECT, OR CONSEQUENTIAL DAMAGES OR ANY DAMAGES WHATSOEVER RESULTING FROM LOSS OF USE, DATA OR PROFITS, WHETHER IN AN ACTION OF CONTRACT, NEGLIGENCE OR OTHER TORTIOUS ACTION, ARISING OUT OF OR IN CONNECTION WITH THE USE OR PERFORMANCE OF THIS DESIGN.
