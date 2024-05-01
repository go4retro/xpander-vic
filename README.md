# X-Pander VIC

## Introduction

Cousin to the X-Pander 3 for the C64/SX/C128/C128D, X-Pander VIC opens up a wealth of expansion options for your Commodore VIC-20/VIC-1001. This design continues on tradition of vintage designs like the CardCo Cardboard, while adding more granular controls over select lines like the CMD EX-3/EX2+1 for the C64. The X-Pander VIC offers the following features:

- Individually-selectable expansion ports
- sPower indicators for each port
- Ability to swap IO select lines ports
- Easily accessed piano-style configuration switches
- Top-loading or back-loading terminal port.
- Terminal port can accommodate 2 cartridges at the same time*
- Reset switch

\* Both top and back-loading options for terminal port share a single set of configuration switches, requiring 2 cartridges that can coexist without configuration.

## Requirements

- Commodore VIC-20 or VIC-1001

## Purchase

The current X-Pander VIC design is not yet available, but an older model (which requires some modification by the consumer can be purchased at the [RETRO Innovations Online Store](https://store.go4retro.com/non-functional-goodies/).

## Technical Details

X-Pander VIC creates a “passive” cartridge port “bus”, with switches on the following lines:

- Power (2 switches)
- IO2
- IO3
- RAM1
- RAM2
- RAM3
- BLK1
- BLK2
- BLK3
- BLK5
- AUDIO

Additionally, all ports except the first contain jumpers allowing one to “swap”  IO2 and IO3. This can be used to move a peripheral cartridge (like a  serial card or ethernet card) normally residing at IO3 to the  alternative IO3 position so that it can coexist with another IO cartridge. Jumpers are provided, but the jumper  pins can be removed and replaced with a subminiature DPDT (double pole,  double throw) switch.

## Support

Expansion port cartridges were not normally designed to coexist with  other cartridges. Thus, it is impossible to detail the nearly infinite  combinations and whether each works or not. Also, since the “bus”  places additional load on the unbuffered expansion port IO lines,  cartridges that are susceptible to signal degradation may not work with  X-Pander VIC, even when installed alone.

Some helpful hints:

- Always insert or remove X-Pander VIC with the system port off
- Clean cartridge contacts before installation
- Switches are “on” when depressed. Normally, all switches can be left in the “on” position
- IO2/IO3 swap jumpers must be moved as a pairs