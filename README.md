# DIY Desktop Variable Power Supply

<img src="https://raw.githubusercontent.com/Ballistyxx/eliferrara/master/assets/Desktop-Power-Supply/render.png" alt="Full CAD model of desktop power supply" width="600" ALIGN="left" HSPACE="20" VSPACE="20"/>

## Overview
This project is a **DIY Desktop Variable Power Supply** built using a **laptop power supply**, a **DC-DC buck converter**, and a **custom enclosure**. It provides a variable voltage output for electronics projects, making it an essential tool for any DIY electronics enthusiast.

📜 **Read the full blog post here:** [How I Built a DIY Desktop Variable Power Supply](https://eliferrara.com/2025/01/15/Desktop_Power_Supply.html)

## Features
✔ **Adjustable voltage output (1.25V - 20V)**  
✔ **Built-in voltage & current display**  
✔ **Power switch for easy operation**  
✔ **Custom 3D-printed enclosure**  
✔ **Banana plug outputs for easy connections**  
✔ **Compact and portable design**  

## Project Images

### Final Build
<img src="https://raw.githubusercontent.com/Ballistyxx/eliferrara/master/assets/Desktop-Power-Supply/frontpanel.png" alt="Front panel of power supply" width="500" ALIGN="left" HSPACE="20" VSPACE="20"/>

## Hardware Components
- **Laptop Power Supply (~65W, 20V output)**
- **DC-DC Adjustable Buck Converter**
- **Voltage & Current Display**
- **Banana Plug Connectors**
- **10kΩ Potentiometer for Voltage Control**
- **Power Switch**
- **3D-Printed Enclosure**

## Software & Wiring
This power supply does not require any software but follows a structured wiring diagram:

1. **Laptop power supply** → **DC-DC buck converter input**
2. **DC-DC converter output** → **Current shunt resistor** → **Banana plugs**
3. **Power switch in series with ground** for total control
4. **Voltage & current meter** wired in parallel to display values

### Example Wiring Diagram (Simplified)
```plaintext
[ Laptop PSU ] --> [ Buck Converter ] --> [ Shunt Resistor ] --> [ Banana Plugs ]
                                    |
                                    V
                            [ Voltage/Current Meter ]
```

## 3D Printing Files & Assembly Guide
All **.STEP**, **STL**, and **wiring diagrams** are provided in the repository.

📂 **Download Here:** [GitHub Repository](https://github.com/Ballistyxx/desktop-power-supply)

## Known Limitations & Future Improvements
⚠ **Voltage Range Limited to 20V** – Due to the laptop PSU constraints.  
⚠ **Enclosure Design Can Be Improved** – More compact and enclosed future iterations possible.  
⚠ **Better Internal Cable Management Needed** – PCB design could replace excessive wiring.  

## License
This project is open-source under the **MIT License**. Feel free to modify and improve!

## Author
Developed by **Ballistyxx**  
📧 **Contact:** [GitHub Issues](https://github.com/Ballistyxx/desktop-power-supply/issues)

---
✨ **If you like this project, consider giving it a ⭐ on GitHub!**


