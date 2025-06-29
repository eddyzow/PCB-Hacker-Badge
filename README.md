# PCB-Hacker-Badge
A PCB business card for Hack Club's Undercity hackathon with special features! An upgrade to my original PCB business card, this card features two LEDs instead of one and additional updated information about myself. Created for Hack Club's Highway program.

# PCB Design

![image](https://github.com/user-attachments/assets/2f004adb-f444-4433-b7b7-bb08bc498c3e)
![image](https://github.com/user-attachments/assets/8a2e0afc-7687-4536-8749-3673af76db83)

# Schematic

![image](https://github.com/user-attachments/assets/77e37ce8-a9fd-4dcb-b06c-814c41355bb3)

# Bill of Materials

| Item Name                                | Purpose                                                  | Item Source | Quantity | Unit Cost (includes taxes) | Cost    |
|:-----------------------------------------|:----------------------------------------------------------|:------------|---------:|:----------------------------|:--------|
| Printed Circuit Board with Assembly      | The entire project, with all components SMT soldered by JLCPCB.        | JLCPCB      |        1 | $?                      | $?   |

## Parts BOM for PCB

| Item Name | Purpose | Item Source | Quantity | Unit Cost (USD) | Cost (USD) |
| :--- | :--- | :--- | ---:| :--- | ---:|
| **Electronic Components** | | | | | |
| ST25DV04K NFC Chip (TSSOP-8) | High-performance NFC tag IC with energy harvesting | LCSC | 1 | $0.612 | $0.612 |
| 2.2µF Capacitor (0603) | Energy storage/smoothing for the NFC `V_EH` output | LCSC | 1 | $0.006 | $0.006 |
| Blue LED (0603) | Visual indicator for NFC field detection | LCSC | 1 | $0.010 | $0.010 |
| Green LED (0805) | Second visual indicator for NFC field detection | LCSC | 1 | $0.011 | $0.011 |
| 47Ω Resistors (0603) | Current limiting for each of the parallel LEDs | LCSC | 2 | $0.001 | $0.002 |
| **Subtotal (Components)** | | | | | **$0.641** |
