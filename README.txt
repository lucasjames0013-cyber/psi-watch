PSI WATCH — PRECISION BUILD

Optimized for a pressure display that is ALWAYS exactly 4 digits.
Alarm logic uses the FIRST TWO DIGITS:
- 22XX or below = LOW alarm
- 27XX or above = HIGH alarm

Reliability changes:
- Rejects OCR unless it finds exactly one 4-digit reading.
- OCR is restricted to digits 0-9.
- Tightened camera crop.
- 3x image enlargement, grayscale, contrast thresholding.
- Uses 2-of-last-3 classification consensus to reject one-frame mistakes.
- Alarm latches and repeats until ACKNOWLEDGE is pressed.
- Reading-lost warning after 3 seconds without a valid 4-digit read.
- Last two digits are displayed, but alarm decisions depend only on first two.

IMPORTANT: Browser OCR is not a certified safety instrument. Keep the four digits large, sharp, glare-free, and fully inside the yellow box. Keep the page open and iPhone awake while monitoring.
