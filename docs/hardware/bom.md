# Hardware BOM — Rev 2 and Rev 3 (excluding the PCB)

Parts for **one Tiny Engineer**, with separate build lists for **Rev 2** and **Rev 3** of the main control board. Both use the same external hardware; prices, sourcing links, compact-servo alternatives, and fasteners are shared below. This is **not** the PCB fabrication or assembly BOM. The control board and its soldered components are excluded, except for optional replacement/assembly sockets.

**AliExpress links below are searches, not verified product listings.** Check the selected variant, dimensions, connector, quantity, and seller before ordering. Generic alternatives are not guaranteed drop-in replacements for the reference parts.

## Rev 2 BOM

Use the [Rev 2 source snapshot](https://github.com/jamro/tiny-engineer/tree/8f0da46274f5246792c82cdede6c00cdba50a4b9/hardware/boards/main-control-board) and its [board documentation](https://github.com/jamro/tiny-engineer/blob/8f0da46274f5246792c82cdede6c00cdba50a4b9/hardware/boards/main-control-board/README.md). The current repository board is Rev 3, so exporting the current KiCad project will not produce Rev 2 manufacturing files.

| External part | Qty | AliExpress search | Details / other suppliers |
| --- | --- | --- | --- |
| Waveshare ESP32-C3-Zero (or Zero-M with headers) | 1 | [ESP32-C3-Zero](https://www.aliexpress.com/w/wholesale-waveshare-esp32-c3-zero.html) | [Electronics and prices](#main-electronics) |
| SG90 positional analog servo | 5 | [SG90](https://www.aliexpress.com/w/wholesale-sg90-9g-180-degree-servo.html) | Or five matching compact servos: [FS0307](https://www.aliexpress.com/w/wholesale-feetech-fs0307.html) / [ES9051](https://www.aliexpress.com/w/wholesale-emax-es9051.html); [matching prints](#optional-compact-servo-choices) |
| Waveshare 0.91-inch OLED 14657 with cable | 1 | [Waveshare 0.91-inch OLED](https://www.aliexpress.com/w/wholesale-waveshare-0.91-oled-12832.html) | [Electronics and prices](#main-electronics) |
| Adafruit 3923 mini oval speaker, 8 Ω / 1 W | 1 | [Generic 8 Ω / 1 W, 30 × 20 mm speaker](https://www.aliexpress.com/w/wholesale-8-ohm-1w-3020-speaker.html) | Exact Adafruit part not verified on AliExpress; [reference part and distributor prices](#main-electronics) |
| 5 V / ≥2 A USB supply | 1 | [5 V / 3 A USB supply](https://www.aliexpress.com/w/wholesale-5v-3a-usb-power-adapter.html) | [Power and cables](#power-and-cables) |
| USB-C data cable | 1 | [USB-C data cable](https://www.aliexpress.com/w/wholesale-usb-c-data-cable-3a.html) | [Power and cables](#power-and-cables) |
| M2 self-tapping screws | 8 × 4 mm, 27 × 8 mm, 15 × 16 mm | [M2×4](https://www.aliexpress.com/w/wholesale-m2x4-self-tapping-screw.html) / [M2×8](https://www.aliexpress.com/w/wholesale-m2x8-self-tapping-screw.html) / [M2×16](https://www.aliexpress.com/w/wholesale-m2x16-self-tapping-screw.html) | [Type and head-size requirements](#fasteners) |
| M2 nuts | 6 | [M2 nuts](https://www.aliexpress.com/w/wholesale-m2-hex-nut.html) | [Fasteners](#fasteners) |
| Servo horn-retaining screws | 5 | Normally included with servos above | Confirm supplied screws match the servos |
| 1×9 female ESP32 sockets, 2.54 mm | 2, only if not supplied/fitted | [1×9 female sockets](https://www.aliexpress.com/w/wholesale-1x9-2.54mm-female-header.html) | [Conditional socket purchase](#conditional-socket-purchase) |

**Already on the board:** PCA9685 servo driver, MAX98357A amplifier, USB-C, and supporting components. Do not buy separate breakouts for these. Rev 2 does not have Rev 3's 12-pin expansion port; no expansion hardware is needed for the stock robot.

## Rev 3 BOM

Use the [Rev 3 board sources](../../hardware/boards/main-control-board/) and [board documentation](../../hardware/boards/main-control-board/README.md). The [Rev 3 change](https://github.com/jamro/tiny-engineer/commit/eabb3b966784afcc91bf36f7fa7877810ba44d94) adds a **12-pin expansion port** and layout/component refinements, but does not change the stock robot's external shopping list.

| External part | Qty | AliExpress search | Details / other suppliers |
| --- | --- | --- | --- |
| Waveshare ESP32-C3-Zero (or Zero-M with headers) | 1 | [ESP32-C3-Zero](https://www.aliexpress.com/w/wholesale-waveshare-esp32-c3-zero.html) | [Electronics and prices](#main-electronics) |
| SG90 positional analog servo | 5 | [SG90](https://www.aliexpress.com/w/wholesale-sg90-9g-180-degree-servo.html) | Or five matching compact servos: [FS0307](https://www.aliexpress.com/w/wholesale-feetech-fs0307.html) / [ES9051](https://www.aliexpress.com/w/wholesale-emax-es9051.html); [matching prints](#optional-compact-servo-choices) |
| Waveshare 0.91-inch OLED 14657 with cable | 1 | [Waveshare 0.91-inch OLED](https://www.aliexpress.com/w/wholesale-waveshare-0.91-oled-12832.html) | [Electronics and prices](#main-electronics) |
| Adafruit 3923 mini oval speaker, 8 Ω / 1 W | 1 | [Generic 8 Ω / 1 W, 30 × 20 mm speaker](https://www.aliexpress.com/w/wholesale-8-ohm-1w-3020-speaker.html) | Exact Adafruit part not verified on AliExpress; [reference part and distributor prices](#main-electronics) |
| 5 V / ≥2 A USB supply | 1 | [5 V / 3 A USB supply](https://www.aliexpress.com/w/wholesale-5v-3a-usb-power-adapter.html) | [Power and cables](#power-and-cables) |
| USB-C data cable | 1 | [USB-C data cable](https://www.aliexpress.com/w/wholesale-usb-c-data-cable-3a.html) | [Power and cables](#power-and-cables) |
| M2 self-tapping screws | 8 × 4 mm, 27 × 8 mm, 15 × 16 mm | [M2×4](https://www.aliexpress.com/w/wholesale-m2x4-self-tapping-screw.html) / [M2×8](https://www.aliexpress.com/w/wholesale-m2x8-self-tapping-screw.html) / [M2×16](https://www.aliexpress.com/w/wholesale-m2x16-self-tapping-screw.html) | [Type and head-size requirements](#fasteners) |
| M2 nuts | 6 | [M2 nuts](https://www.aliexpress.com/w/wholesale-m2-hex-nut.html) | [Fasteners](#fasteners) |
| Servo horn-retaining screws | 5 | Normally included with servos above | Confirm supplied screws match the servos |
| 1×9 female ESP32 sockets, 2.54 mm | 2, only if not supplied/fitted | [1×9 female sockets](https://www.aliexpress.com/w/wholesale-1x9-2.54mm-female-header.html) | [Conditional socket purchase](#conditional-socket-purchase) |

**Already on the board:** PCA9685 servo driver, MAX98357A amplifier, USB-C, and supporting components. Do not buy separate breakouts for these. Peripherals for the new expansion port are optional and outside this stock BOM.

## Shared board-ordering notes

For **either revision**, the integrated board replaces these standalone purchases:

| Skip as a standalone purchase | Already included in the PCBA design |
| --- | --- |
| PCA9685 servo-driver breakout (such as Adafruit 815) | PCA9685 and servo connectors |
| MAX98357A I2S amplifier breakout | Amplifier and supporting components |
| Adafruit 5993 USB-C breakout | USB-C power/data connector and supporting components |
| Separate board-level protection/passive parts | Fuse, eFuse, resistors, capacitors, and indicators in the assembly BOM |

Choose **bare PCB plus its complete assembly BOM** for DIY assembly, or **PCBA** for factory assembly. The project documents top-side PCBA with two through-hole ESP32 sockets left to fit, or both-side PCBA including those sockets. Verify included parts in the final quote. Ordering guides: [Rev 2](https://github.com/jamro/tiny-engineer/blob/8f0da46274f5246792c82cdede6c00cdba50a4b9/docs/hardware/order-main-control-board.md), [Rev 3/current](order-main-control-board.md).

Generate Gerbers, PCB assembly BOM, and placement files from the **same revision**. Do not mix Rev 2 and Rev 3 files. Board fabrication, assembly, and individual SMD-part costs are not included in the external-hardware prices below.

### Conditional socket purchase

| Part | Qty | Buy only when | Sourcing / price |
| --- | --- | --- | --- |
| 1×9 straight female socket strip, 2.54 mm pitch, through-hole | 2 | ESP32 sockets are not fitted and the assembler does not supply them loose. Not needed with fully assembled PCBA. | Rev 2 references **J7/J8**, LCSC **C2897372**; confirm socket dimensions against your chosen revision's assembly BOM. [AliExpress search](https://www.aliexpress.com/w/wholesale-1x9-2.54mm-female-header.html), [Mouser search](https://www.mouser.com/c/?q=1x9%202.54mm%20female%20socket), [DigiKey search](https://www.digikey.com/en/products?keywords=1x9%202.54mm%20female%20socket). Exact alternatives and prices **not verified**. |

This is purchasing guidance from revision-specific documentation and footprint metadata, **not an independent connectivity or manufacturing validation**. Both linked board READMEs label the design draft/not tested; confirm physical-test status with the supplier before ordering.

## Prices and distributor sourcing (USD)

**Price research: 2026-10-29.** Prices are per unit unless stated otherwise, in **USD**, excluding shipping, Norwegian VAT, import/handling fees, and any distributor tariff surcharge. They are reference prices, not checkout quotes. No NOK conversion is assumed; use your payment provider's exchange rate when ordering.

- **Direct** means the price was readable on the linked seller page.
- **Indexed** means the distributor listing/price was found in search results; automated page access was blocked or timed out. Recheck price and stock in a browser.
- **Not found** means no exact-model listing was located during this check, not that the distributor can never supply it. Search links are provided for rechecking.
- **Quote needed** means no reliable USD price was readable. In particular, AliExpress search results vary by destination, selected variant, pack size, and new-customer discounts; no unverified prices are presented as quotes.

### Main electronics

AliExpress search links for each part remain in the detailed BOM below.

| Part / required qty | AliExpress unit price | Mouser source / unit price | DigiKey source / unit price | Other source / unit price |
| --- | --- | --- | --- | --- |
| Waveshare ESP32-C3-Zero / 1 | Quote needed | Exact model not found; [search](https://www.mouser.com/c/?q=ESP32-C3-Zero). No verified price. | Exact model not found; [search](https://www.digikey.com/en/products?keywords=ESP32-C3-Zero). No verified price. | [Waveshare](https://www.waveshare.com/esp32-c3-zero.htm): **$3.49–$4.49**, header-version range (direct). Choose **ESP32-C3-Zero-M** for pre-soldered headers; confirm its selected price. |
| SG90 analog servo / 5 | Quote needed | [Soldered 555044, TowerPro SG90](https://www.mouser.com/ProductDetail/Soldered/555044): **$5.89**, or **$29.45 for five** (indexed). Stock shown in indexed catalog. | [Gearbox Labs PART-MICRO-SERVO-SG-90-ANALOG](https://www.digikey.com/en/products/detail/gearbox-labs/PART-MICRO-SERVO-SG-90-ANALOG/16159912): **$6.00**, or **$30.00 for five** (indexed). Listed as shipping in indexed results. | Compare servo dimensions and supplied horns with the SG90 preset before ordering either listing. |
| Waveshare OLED 14657 / 1 | Quote needed | Exact module not found; [search](https://www.mouser.com/c/?q=Waveshare%2014657). No verified price. | Exact module not found; [search](https://www.digikey.com/en/products?keywords=Waveshare%2014657). No verified price. | [Waveshare](https://www.waveshare.com/0.91inch-oled-module.htm): **$6.99** at qty 1 (direct); package includes a **PH2.0 4-pin cable**. |
| Adafruit speaker 3923 / 1 | Quote needed for a generic equivalent; exact Adafruit part not verified | [Adafruit 3923 / 485-3923](https://www.mouser.com/ProductDetail/Adafruit/3923): **$2.44–$2.60** across indexed product/catalog results; indexed catalog shows stock. Confirm current price. | [Adafruit 3923](https://www.digikey.com/en/products/detail/adafruit-industries-llc/3923/9658610): **$3.00** (indexed), listed in stock. Exact reference part. | [Adafruit](https://www.adafruit.com/product/3923): **$1.95** (direct); page showed **out of stock** when fetched. |

**Do not substitute a Seeed XIAO ESP32C3 or an Espressif DevKit just because it is available at a distributor:** the stock PCB footprint, mounting, and firmware pin mapping target the Waveshare board.

### Power, cables, and fasteners

These are sourcing candidates, not additional mandatory parts. Reuse a suitable supply/cable if you already own one. None of these alternatives has been bench-tested as part of this BOM research.

| Part / required qty | AliExpress price | Mouser source / price | DigiKey source / price | Selection notes |
| --- | --- | --- | --- | --- |
| USB supply / 1 | Quote needed | [CUI SWI20CB-T-E](https://www.mouser.com/ProductDetail/CUI-Inc/SWI20CB-T-E): **$16.25** (indexed), stock shown. EU plug, USB-C socket, **5 V / 3 A** output mode. | [RAKwireless RAK-PSU-5V3A-EU-TC](https://www.digikey.com/en/products/detail/rakwireless-technology-limited/RAK-PSU-5V3A-EU-TC/29287298): **$8.41** at qty 1 (indexed). EU, 5 V / 3 A USB-C supply candidate; confirm cable and stock. | Choose an EU plug for Norway. For the CUI supply use a C-to-C cable. Use only the default **5 V** USB output, never a higher-voltage trigger. A captive power lead does **not** replace a data cable for flashing. |
| USB-C data cable / 1 | Quote needed | [Adafruit 4199 / 485-4199](https://www.mouser.com/ProductDetail/Adafruit/4199): **$9.95** (indexed), stock shown. | [Adafruit 4199](https://www.digikey.com/en/products/detail/adafruit-industries-llc/4199/10230016): **$9.95** (indexed in DigiKey project BOM); product listing found, recheck current stock/price. | **1 m C-to-C data cable** with E-Mark. For a USB-A host, [Adafruit 4474](https://www.mouser.com/ProductDetail/Adafruit/4474) is **$4.95** at Mouser (indexed), but its manufacturer describes it as **up to approximately 2 A**, not a 3 A cable. |
| Optional female/female jumper set / 1 pack | Quote needed | [Adafruit 1951 / 485-1951](https://www.mouser.com/ProductDetail/Adafruit/1951): **$1.95 per 20-wire pack** (indexed); live stock not verified. | [Adafruit 1951](https://www.digikey.com/en/products/detail/adafruit-industries-llc/1951/6827085): **$1.95 per pack** (indexed); live stock not verified. | **75 mm, 2.54 mm** jumpers; only for matching headers and adequate cable reach. These do not plug directly into the Waveshare OLED's **PH2.0** socket. Prefer the OLED's included cable. |
| M2 × 4 / 8 / 16 mm self-tapping screws / 8 + 27 + 15 | Quote needed for packs meeting the quantities below | [Self-tapping screws catalog](https://www.mouser.com/c/electromechanical/hardware/screws-fasteners/?type=Self%20Tapping): no exact set verified; no price quoted. | [Screws catalog](https://www.digikey.com/en/products/filter/screws-bolts/572): no exact set verified; no price quoted. | Buy the correct plastic-thread-forming type, lengths, and head dimensions. **M2.5**, US **#2**, and M2 machine screws are not interchangeable with these requirements. |
| M2 nuts / 6 | Quote needed | [Search M2 hex nuts](https://www.mouser.com/c/?q=M2%20hex%20nut): no exact item/price verified. | [Search M2 hex nuts](https://www.digikey.com/en/products?keywords=M2%20hex%20nut): no exact item/price verified. | Check pack quantity; do not assume the price is per nut. Servo horn screws should come with the servos. |

### Compact servo prices

These **replace**, rather than supplement, the five SG90 servos. AliExpress searches and matching print folders are below.

| Model / required qty | AliExpress unit price | Mouser | DigiKey | Other source / price |
| --- | --- | --- | --- | --- |
| Feetech FS0307 / 5 | Quote needed | Exact model not found; [search](https://www.mouser.com/c/?q=FS0307). No verified price. | Exact model not found; [search](https://www.digikey.com/en/products?keywords=FS0307). No verified price. | [Pololu 3420](https://www.pololu.com/product/3420): **$9.95 each**, or **$9.35 each at qty 5 = $46.75** (direct). Backorders allowed; immediate stock not confirmed. |
| EMAX ES9051 / 5 | Quote needed | Exact model not found; [search](https://www.mouser.com/c/?q=ES9051). No verified price. | Exact model not found; [search](https://www.digikey.com/en/products?keywords=ES9051). No verified price. | [EMAX USA](https://shop.emax-usa.com/products/emx-sv-0272-es9051): **$4.99 each = $24.95 for five** (direct), page showed in stock. Confirm delivery to Norway. |

**Core-electronics reference subtotal:** budgeting **$4.49** for the Waveshare header variant, **$6.99** for its OLED, **$3.00** for the exact DigiKey speaker, and the five-servo prices above gives **$43.93 with Mouser SG90s**, **$61.23 with Pololu FS0307s**, or **$39.43 with EMAX ES9051s**. These are mixed-supplier reference sums, **not complete or delivered robot totals**; power, cables, fasteners, PCB, printed parts, and all order fees are excluded. The FS0307 price may require a backorder.

## Electronics

| Part | Qty | What to buy / check | AliExpress |
| --- | --- | --- | --- |
| Waveshare ESP32-C3-Zero | 1 | Exact **Waveshare ESP32-C3-Zero**, preferably with headers fitted. Other ESP32-C3 development boards may not fit the sockets or printed desk. The firmware target name `esp32-c3-devkitm-1` is not the physical board to buy. | [Search ESP32-C3-Zero](https://www.aliexpress.com/w/wholesale-waveshare-esp32-c3-zero.html) |
| SG90 analog micro servo | 5 | Tower Pro SG90 or equivalent **9 g positional analog servo**, with horns and horn-retaining screws. Buy five of one model. Avoid **360° continuous-rotation** variants. Print the matching [SG90 parts](../../3d_models/parts/sg90/3mf/). | [Search SG90 servos](https://www.aliexpress.com/w/wholesale-sg90-9g-180-degree-servo.html) |
| 0.91-inch OLED module | 1 | Reference: [Waveshare 0.91inch OLED Module, SKU 14657](https://www.waveshare.com/0.91inch-oled-module.htm). **SSD1306, 128×32, I2C, address `0x3C`, 3.3 V operation**. Not 128×64 or SPI. Generic modules may differ in dimensions and pin order; check against the printed head and wiring. | [Search Waveshare 0.91-inch OLED](https://www.aliexpress.com/w/wholesale-waveshare-0.91-oled-12832.html) |
| Mini oval speaker | 1 | Reference: [Adafruit 3923](https://www.adafruit.com/product/3923), **8 Ω, 1 W, 30 × 20 × 5 mm**, with leads. For a substitute, match the size and impedance and check the mounting fit. The reference uses a **2-pin, 1.25 mm Molex PicoBlade** connector; a generic “JST” plug is not necessarily compatible. Alternatively use the board's speaker solder pads. | [Search 8 Ω 1 W oval speaker](https://www.aliexpress.com/w/wholesale-8-ohm-1w-3020-speaker.html) |

The main control board already contains the **PCA9685 servo driver, MAX98357A amplifier, and USB-C connector**. Do not buy separate breakout modules for the default build. For the alternative breakout build, use the [advanced shopping list](../shopping.md#advanced-extra-modules) and [wiring guide](wiring.md).

## Power and cables

| Part | Qty | What to buy / check | AliExpress |
| --- | --- | --- | --- |
| USB power supply | 1 | Regulated **5 V / ≥2 A** USB supply; a reputable **5 V / 3 A** unit provides source headroom. Check the actual **5 V output rating**, not just advertised total watts. Choose the correct mains plug and a cable-compatible USB port. | [Search 5 V 3 A USB supply](https://www.aliexpress.com/w/wholesale-5v-3a-usb-power-adapter.html) |
| USB-C data cable | 1 | USB-C at the robot end; USB-A or USB-C at the source end as appropriate. Must support **data** for flashing and serial, and carry the required power. Avoid charge-only cables. | [Search USB-C data cable](https://www.aliexpress.com/w/wholesale-usb-c-data-cable-3a.html) |
| OLED connection cable | 1, if not supplied | Four conductors compatible with the module and board headers. Check connector pitch and ends before buying; a **2.54 mm female-to-female jumper set** is useful when both ends have matching male headers. Wire by signal name, not wire color or assumed pin order. | [Search female-to-female jumper wires](https://www.aliexpress.com/w/wholesale-dupont-female-female-2.54mm.html) |

The assembled robot's external connector is **USB-C on the main control board**; no additional USB breakout is needed. A supply with more current capacity does not increase the board's approximately 2 A servo-rail limit. Supply requirements: [power.md](power.md).

## Fasteners

Quantities match the [main shopping list](../shopping.md#fasteners). Buy spares or packs covering at least these amounts. Use **M2 thread-forming/self-tapping screws for plastic**, with pan or button heads—not an assortment containing only machine screws.

| Part | Qty | What to buy / check | AliExpress |
| --- | --- | --- | --- |
| M2 × 4 mm self-tapping screws | 8 | Pan/button head. | [Search M2 × 4 screws](https://www.aliexpress.com/w/wholesale-m2x4-self-tapping-screw.html) |
| M2 × 8 mm self-tapping screws | 27 | Includes six bottom-cover screws; those heads must be **≤4.0 mm diameter and ≤2.0 mm high**. | [Search M2 × 8 screws](https://www.aliexpress.com/w/wholesale-m2x8-self-tapping-screw.html) |
| M2 × 16 mm self-tapping screws | 15 | Pan/button head. | [Search M2 × 16 screws](https://www.aliexpress.com/w/wholesale-m2x16-self-tapping-screw.html) |
| M2 nuts | 6 | Standard M2 nuts as used in the assembly guide. | [Search M2 nuts](https://www.aliexpress.com/w/wholesale-m2-hex-nut.html) |
| Servo horn-retaining screws | 5 | Normally supplied with the servos; verify the servo pack includes them. Use screws matching the servo output shaft. | Included with servos above |

Placement and screw lengths by assembly step: [3D models → Screws](../../3d_models/README.md#screws).

## Optional compact servo choices

Replace the five SG90s with **five of one** model below, not additional servos. Print that model's matching parts; do not assume the SG90 body fits.

| Servo | Qty | Matching printed parts | AliExpress |
| --- | --- | --- | --- |
| Feetech FS0307 | 5 | [FS0307](../../3d_models/parts/fs0307/3mf/) | [Search FS0307](https://www.aliexpress.com/w/wholesale-feetech-fs0307.html) |
| EMAX ES9051 | 5 | [ES9051](../../3d_models/parts/es9051/3mf/) | [Search ES9051](https://www.aliexpress.com/w/wholesale-emax-es9051.html) |

## Before ordering

- **Board revision:** confirm Rev 2 or Rev 3 and whether the quote includes assembly, all required components, and ESP32 sockets.
- **Servos:** buy five of one model with matching printed parts, horns, and horn-retaining screws. Avoid continuous-rotation variants.
- **OLED:** confirm SSD1306, 128×32, I2C, 3.3 V compatibility, module dimensions, connector/pin order, and included cable.
- **Speaker:** confirm 8 Ω / 1 W, 30 × 20 × 5 mm reference dimensions, mounting fit, lead length, and a compatible plug—or allow for replacing the plug.
- **Power and USB:** confirm the supply's **5 V / ≥2 A** rating, suitable mains plug, and cable connectors. The USB cable must support data as well as the required current.
- **Fasteners:** check screw type, lengths, pack quantities, and the bottom-cover head-size limits above; allow spares.
- **Total cost:** include shipping, VAT/import fees, and any minimum order or pack quantities. Printed parts, filament, tools, PCB fabrication, and PCB assembly are outside the prices in this BOM.

For wiring and operation, use the [main control board connection guide](main-control-board.md) and [getting-started checklist](../getting-started.md).
