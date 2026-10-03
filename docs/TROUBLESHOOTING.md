# Kraken HID — Troubleshooting

### Nothing happens when I plug it in
Use a **data** USB cable, not charge-only. Try a different port. On the Pico, confirm you're using the Micro-USB data port.

### No drive appears
The firmware may run the payload immediately instead of mounting. Re-plug while ready, or reflash pico-ducky and set it to expose the drive.

### It types too fast / misses keystrokes
Add or increase `DELAY` values, especially right after `GUI r` or app launches.

### Wrong characters typed
The host keyboard layout must match the payload's layout (default US). Set the layout in the firmware for non-US keyboards.

---

Still stuck? Open an issue here, or message us via https://p01ylabs.com.
