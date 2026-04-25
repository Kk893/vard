# RFID Card Print Design – Library Orbit

Website ke RFID card design se match karta hua printable card template.

## Files

| File | Description |
|------|-------------|
| `RFIDPrintCard.html` | Main print-ready HTML file |

## Card Variants

| Variant | Gradient | Badge |
|---------|----------|-------|
| User (default) | Purple `#667eea → #764ba2` | Blue |
| Admin | Orange `#f97316 → #ea580c` | Orange |
| Inactive | Gray `#6B7280 → #4B5563` | Red |

## Card Size

Standard **CR-80** credit card format:
- Width: **85.6 mm**
- Height: **53.98 mm**
- Aspect ratio: **1.586**

## Print Karne Ka Tarika

1. `RFIDPrintCard.html` browser mein open karo
2. Neeche **🖨️ Print Cards** button click karo
3. Print settings mein:
   - Paper: **A4**
   - Margins: **Minimum / None**
   - Scale: **100%** (fit to page mat karo)
4. Print ke baad card borders ke along cut karo

## Design Elements

### Front Side
- Gold chip (top-left)
- QR code with logo (top-right)
- "Library Orbit" brand strip (center-top)
- Card number (monospace, bottom)
- Card holder name (bottom-left)
- Status badge (bottom-right)
- Watermark "LO" (center, 8% opacity)

### Back Side
- Magnetic stripe (black bar, top)
- Card Number, Access Level, Card Holder, Issued Date, Library
- Signature area (bottom)

## Customization

Blank fields (`____ ____ ____ ____`) ko manually fill karo ya
`RFIDPrintCard.html` mein directly edit karo before printing.
