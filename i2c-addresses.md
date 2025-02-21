# Overview of I2C addresses in relation to the Supercon 8 Add-On Badge

The below list is a work in progress for documenting the different I2C addresses used on SAOs that will be around at Supercon 8, either the official ones, or SAOs made by other people.

For a good list of commercial chips' addresses, see [Adafruit's List of I2C Addresses](https://learn.adafruit.com/i2c-addresses/the-list).

If you have made an SAO that you are bringing, please add it to this list submitting a pull request.

| Address    | SAO                       | Notes                           | Link to SAO info                   |
| ---------- | ------------------------- | ------------------------------- | ---------------------------------- |
| 0x00       | LED Petal Matrix          | AS1115's default. Can override. |                                    |
| 0x12       | I2C Proto Badge (default) | In firmware, change to whatever |                                    |
| 0x19       | Blinky Loop SAO           | Can also use 0x18               | [hackaday.io](https://hackaday.io/project/198163-blinky-loop-sao) |
| 0x1A       | Hack-Man SAO              | See project for commands        | [hackaday.io](https://hackaday.io/project/198301-hack-man-sao) |
| 0x54       | TouchwheelSAO             | Can change addr in Arduino src  | [hackaday.io](https://hackaday.io/project/199100-touchwheelsao) |
| 0x55       | Badge Tag NFC SAO         | Can be changed in a register    | [hackaday.io](https://hackaday.io/project/198165-badge-tag-nfc-sao) |
| 0x6C       | duckGLOW SAO              | Change to 0x6C-06F w/ solder jumpers | [hackaday.io](https://hackaday.io/project/198918-duckglow-sao) |
| 0x13       | Skull of Fate SAO         | Can be changed. See doc.        | [hackaday.io](https://hackaday.io/project/198974-skull-of-fate-sao) |
