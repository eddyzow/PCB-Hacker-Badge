# PCB-Hacker-Badge
A PCB business card for Hack Club's Undercity hackathon with special features! An upgrade to my original PCB business card, this card features two LEDs instead of one and additional updated information about myself. Created for Hack Club's Highway program.

# PCB Design

![image](https://github.com/user-attachments/assets/f949c9a9-bf6c-46ab-9243-dd976c9e5088)
![image](https://github.com/user-attachments/assets/0ce165f8-cc93-4010-bbaa-cc94ac492b49)

# Schematic

![image](https://github.com/user-attachments/assets/d7ec7488-1709-4dd5-ae31-eb80fc904bc2)

# Bill of Materials

| Item Name                                | Purpose                                                  | Item Source | Quantity | Unit Cost (includes taxes) | Cost    |
|:-----------------------------------------|:----------------------------------------------------------|:------------|---------:|:----------------------------|:--------|
| Printed Circuit Board with Assembly      | The entire project, with all components SMT soldered by JLCPCB.        | JLCPCB      |        1 | $?                      | $?   |

## Parts BOM for PCB

| Item Name | Purpose | Item Source | Quantity | Unit Cost (USD) | Cost (USD) |
| :--- | :--- | :--- | ---:| :--- | ---:|
| **Electronic Components** | | | | | |
| NT3H2111 NFC Chip (XQFN-8) | The NFC tag IC that stores the URL and harvests power | LCSC | 1 | $0.882 | $0.882 |
| 220nF Capacitor (C0603) | RF tuning and rectifying capacitor for the NT3H2111's power output | LCSC | 1 | $0.006 | $0.006 |
| Blue LED (0603) | Visual indicator for when the NFC field is active | LCSC | 1 | $0.010 | $0.010 |
| Green LED (0805) | Second visual indicator for NFC field detection | LCSC | 1 | $0.011 | $0.011 |
| 47Ω Resistors (0603) | Current limiting for each of the parallel LEDs | LCSC | 2 | $0.001 | $0.002 |
| **Subtotal (Components)** | | | | | **$0.911** |
