# Kraken HID — Setup

## First-time setup

### 1. Confirm it mounts
Plug the device into a port on your own machine with a **data-capable** cable
(a charge-only cable is the #1 cause of "nothing happens"). On the Pico, the port
is **Micro-USB**. You should see a new removable drive appear.

### 2. The files on the drive
- `code.py` / `boot.py` — the pico-ducky firmware (leave these alone unless reflashing)
- `payload.dd` — **this is the file you edit**: your DuckyScript

### 3. Write a payload
Use the free **Mythoskull Payload Builder** (https://github.com/p0lygl07/KrakenPayloadBuilder) to generate DuckyScript, or
write it by hand. Save it as `payload.dd` on the drive.

### 4. Re-flashing firmware (only if needed)
To restore firmware, follow the upstream **pico-ducky** instructions (https://github.com/dbisu/pico-ducky).
In short: hold BOOTSEL while plugging in the Pico, drop the CircuitPython UF2 on the
RPI-RP2 drive, then copy the pico-ducky files over.


---

Stuck? See [TROUBLESHOOTING.md](TROUBLESHOOTING.md). Use responsibly — [SAFETY.md](SAFETY.md).
