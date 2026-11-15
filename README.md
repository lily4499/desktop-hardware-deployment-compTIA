
# IT Support Project: Desktop Deployment, Hardware Upgrades & RAID 5 Workstation

**Focus:** CompTIA A+ hands-on simulations | Desktop setup | USB peripherals | Motherboard installation | Graphics upgrades | Dual displays | RAID 5  
**Environment:** CompTIA virtual hardware lab  
**Project type:** Portfolio project built from seven separate CompTIA labs

## 1. Real-world context: why this project matters

A growing office needs several computers ready for employees. A support technician must assemble desks, connect screens and peripheral devices, choose compatible replacement parts, install graphics hardware, configure two-monitor workstations, and prepare a higher-capacity workstation for audio/video work.

An incomplete setup can cause black screens, disconnected keyboards, undetected printers, or computers that will not turn on. For the A/V workstation, incorrect disk configuration may prevent the required RAID array from being created.

**My assignment (simulated):** Follow a repeatable deployment process that takes a workstation from individual parts to a connected and configured system.

**What success looks like:**
- A basic computer, monitor, keyboard, and mouse are connected and powered on.
- A USB hub, printers, scanner, and portable drive use the correct cables.
- A fully equipped desktop has power, sound, printing, and Ethernet.
- A compatible Socket 1151 motherboard is installed and wired correctly.
- A video card is upgraded from VGA output to HDMI output.
- Two monitors are connected and arranged in Windows to match their physical locations.
- An A/V workstation has a discrete graphics card, two monitors, and a three-disk RAID 5 volume.

## 2. Tools and technologies

| Category | Items used |
| --- | --- |
| Simulation | CompTIA virtual hardware workstation, Inventory, Workspace, Change View / Front / Back / Motherboard views |
| Display | Monitor, DVI-D cable, HDMI-to-HDMI cable, VGA/DB-15 cable |
| Peripheral connections | USB Type-A, USB Type-B, USB Mini-B, USB hub, keyboard, mouse, printers, scanner, portable HDD |
| Hardware | Motherboard Socket 1151, PCIe video card, 6-pin PCIe power, case headers, 8-pin CPU power, 20+4 motherboard power |
| Networking and audio | Cat6a Ethernet cable, RJ45 port, green mini-TRS audio port |
| Storage and firmware | Three SATA HDDs, SATA data cables, SATA power, BIOS/UEFI SATA Operation, Intel-style RAID configuration utility, RAID 5 |

## 3. Lab 2.1.2 — Explore the Lab Interface

**Business context:** A newly delivered computer needs its monitor and input devices connected before an employee can start work.

**Goal:** Learn the simulator interface while connecting a monitor, keyboard, and mouse and powering on the workstation.

### Exact CompTIA simulation steps

1. At the top, choose **Floor 1 Overview**.
2. Choose **Office 2 → Hardware** to open the workstation.
3. In **Inventory**, expand **Peripherals**.
4. Drag the **Monitor** to the bench beside the computer.
5. Above the monitor, click the **two-arrow / Change View** icon; choose **Back**.
6. Above the computer, click the same icon; choose **Back**.
7. In **Inventory**, expand **Cables** and select **HDMI to HDMI Cable**.
8. In **Selected Item**, drag one HDMI connector to the **HDMI port on the computer**.
9. Drag the other HDMI connector to the **HDMI port on the monitor**.
10. In **Inventory**, choose **AC Power Cable**.
11. Drag the female power connector to the power port indicated in the simulation; drag the male connector to the **wall outlet**.
12. In **Inventory → Peripherals**, drag the **Keyboard** to an available **USB port** on the computer.
13. Drag the **Mouse** to another available **USB port**.
14. Change both the monitor and computer to their **Front** views.
15. Press the **monitor power button**.
16. Press the **computer power button**.
17. Check that the workstation turns on and the monitor receives an image.

**Source detail to watch:** The supplied instructions call step 11 “Provide power to the monitor,” but also say the female cable goes to the back of the *computer*. If the simulator presents both ports, follow the highlighted target and the lab's task indicator rather than assuming the wording is consistent.

**Why each major action matters:** HDMI carries video; USB connects the keyboard and mouse; the power cable supplies electricity; pressing power starts the system.

**Evidence to capture:** Monitor placed in Workspace; HDMI connection visible at the rear; keyboard/mouse connections; powered-on workstation.

**Reference instruction screenshot:**

![CompTIA Lab 2.1.2 instructions](assets/lab-2-1-2-instructions.png)

---

## 4. Lab 2.1.7 — Install USB Devices

**Business context:** An employee needs several peripherals, but the computer has limited USB ports. A powered workplace USB hub provides more connections.

**Goal:** Connect a USB hub, inkjet printer, laser printer, scanner, and external USB hard drive.

### Exact CompTIA simulation steps

**Part A — Connect the USB hub**

1. Switch to the **Back** view of the computer.
2. In **Inventory**, expand **Networking Devices**.
3. Drag the **External USB Hub** into the **Workspace**.
4. Switch to the **Back** view of the USB hub.
5. In **Inventory → Cables**, select **USB Cable Mini-B to Type A**.
6. In **Selected Item**, drag the **USB Mini-B Vertical Connector** to the back of the USB hub.
7. Drag the **USB Type A Standard Connector** to an open USB port on the back of the computer.
8. Switch the USB hub to its **Front** view to see its open ports.

**Part B — Connect the inkjet printer**

9. Switch the **inkjet printer** to its **Back** view and find its USB port.
10. In **Inventory**, select **USB Cable Type B (Standard) to Type A (Standard)**.
11. Connect the **USB Type B** end to the **inkjet printer**.
12. Connect the **USB Type A** end to an available port on the **USB hub**.

**Part C — Connect the laser printer**

13. Above the **laser printer**, choose **Change View → Back**.
14. In **Inventory**, select another **USB Cable Type B (Standard) to Type A (Standard)**.
15. Connect the **USB Type B** end to the **laser printer**.
16. Connect the **USB Type A** end to a different port on the **USB hub**.

**Part D — Connect the scanner**

17. Above the **scanner**, choose **Change View → Back**.
18. Select another **USB Cable Type B (Standard) to Type A (Standard)**.
19. Connect the **USB Type B** end to the **scanner**.
20. Connect the **USB Type A** end to another port on the **USB hub**.

**Part E — Connect the portable hard drive**

21. In **Inventory → Storage**, drag the **Portable USB Hard Drive** into the **Workspace**.
22. Choose **Change View → Back** on the portable drive.
23. In **Inventory → Cables**, select **USB Cable Mini-B to Type A**.
24. Connect the **USB Mini-B Vertical Connector** to the **external hard drive**.
25. Connect the **USB Type A Standard Connector** directly to an open USB port on the **computer** (not the hub, per this lab).
26. Review all the connections in the simulation.

**Why this matters:** USB Type-B commonly plugs into printers/scanners; Mini-B is used by these simulated devices; Type-A connects to the computer or hub.

**Evidence to capture:** Hub-to-PC cable; three devices connected to the hub; portable HDD directly connected to the PC.

![CompTIA Lab 2.1.7 instructions](assets/lab-2-1-7-instructions.png)

---

## 5. Lab 2.1.16 — Set Up a Desktop Computer

**Business context:** A new employee requires a complete ready-to-use desktop, including display, speakers, printer, and a wired network connection.

**Goal:** Install a desktop workstation and connect its power, user peripherals, audio, display, printer, and Ethernet.

### Exact CompTIA simulation steps

1. In **Inventory → Electrical Outlets**, drag a **Power Strip** to the **wall outlet**.
2. Change the **computer** to its **Back** view.
3. In **Inventory → Cables**, select **AC Power Cable**.
4. Connect the **male AC power connector** to the **power strip outlet**.
5. Connect the **female AC power connector** to the **power port at the back of the computer**.
6. In **Inventory → Peripherals**, connect the **Keyboard** to a USB port on the computer.
7. Connect the **Mouse** to another USB port on the computer.
8. Connect the **Speakers** to the computer's **green mini-TRS audio jack**.
9. In **Inventory → Peripherals**, place the **Monitor** on the desktop.
10. Switch the **monitor** to its **Back** view.
11. In **Inventory → Cables**, select **DVI-D to DVI-D**.
12. Connect one **DVI-D connector** to the monitor's DVI-I port indicated in the lab.
13. Connect the other **DVI-D connector** to the **computer's DVI-I port** indicated in the lab.
14. In **Inventory → Cables**, choose an **AC Power Cable**.
15. Connect its **male connector** to an available power-strip outlet and its **female connector** to the monitor's power port.
16. In **Inventory → Peripherals**, drag the **Printer** into the Workspace.
17. Switch the **printer** to its **Back** view.
18. In **Inventory → Cables**, select **USB Cable (A/B)**.
19. Connect the **USB Type B** end to the printer and the **USB Type A** end to a USB port on the computer.
20. In **Inventory**, select **Power Adapter for HP**.
21. Connect the **DC power connector** to the printer and the **AC power connector** to the power strip.
22. In **Inventory**, select a **Cat6a cable**.
23. Connect one **RJ45 connector** to the computer's **RJ45 Ethernet port**.
24. Connect the other **RJ45 connector** to the **RJ45 port on the wall plate**.
25. Turn on the **monitor** using its lower-right power button.
26. Turn on the **computer** using the front power button.
27. Confirm that the cables and ports are correctly connected in the simulator.

**Why this matters:** A computer needs more than a power cord. Display, sound, printing, and network access are separate connections with different cables.

**Evidence to capture:** Power strip; connected rear ports; printer power/USB; Ethernet wall jack; working desktop.

![CompTIA Lab 2.1.16 instructions](assets/lab-2-1-16-instructions.png)

---

## 6. Lab 2.2.11 — Choose and Install a Motherboard

**Business context:** A desktop requires a replacement motherboard. The technician must choose a compatible socket and reconnect case buttons, lights, USB ports, cooling fans, and power.

**Goal:** Install the correct **Socket 1151** motherboard and connect all required motherboard headers.

### Exact CompTIA simulation steps

**Part A — Choose the board**

1. In **Workbench**, choose **Hardware**.
2. Above the computer, choose **Change View → Motherboard**.
3. In **Inventory**, expand **Motherboards**.
4. Select a motherboard, then click the **information icon** beside its image in **Selected Item**.
5. Read its specifications and compare them with the scenario requirements.
6. Close the details window and repeat until you find the required **Motherboard, Socket 1151**.
7. Drag **Motherboard, Socket 1151** to the motherboard position inside the case.

**Part B — Locate and attach case connectors**

8. Select the installed motherboard, click its **information icon**, and use its diagrams to identify these connector locations:

| Connector | Diagram location number |
| --- | ---: |
| USB 3.0 header (blue) | 9 |
| Front-panel audio | 18 |
| USB 2.0 header (black) | 14 |
| 3-pin fan (front) | 4 |
| 3-pin fan (rear) | 4 |
| Case speaker | 13 |
| Hard drive LED (HDD LED) | 13 |
| Power LED 3-1 pin — use the **bottom PLED** location | 13 |
| Power switch (PWR SW) | 13 |

9. Select **System Case**.
10. In **Selected Item**, drag each available case **Connector** to the correct header on the motherboard, using the location diagram.
11. Repeat until the USB, audio, fan, speaker, HDD LED, power LED, and power-switch connections are in place.
12. Zoom in if a connector is difficult to place.

**Part C — Connect motherboard power**

13. Select the **Motherboard, Socket 1151** and open its **information/details** diagram.
14. Find **location 2** for the **8-pin CPU power connector** and **20+4 motherboard power connector**.
15. Select the **Power Supply**.
16. Drag **Connector, Power Supply, 8-pin CPU** to the matching motherboard port.
17. Drag **Connector, Power Supply, 20+4 pin** to the main motherboard power port.
18. Review every required connection in the simulator.

**Why this matters:** The motherboard is the main connection board. Even if it fits physically, the PC may fail to power on or its front USB/power buttons may not work if the small connectors are missing.

**Evidence to capture:** Motherboard selection/specs; case-header connections; CPU and motherboard power connectors.

![CompTIA Lab 2.2.11 instructions](assets/lab-2-2-11-instructions.png)

---

## 7. Lab 2.2.13 — Upgrade a Video Card

**Business context:** An older graphics card provides VGA output, but the employee's monitor setup requires an HDMI connection.

**Goal:** Replace the old video adapter with an HDMI-capable card, supply additional PCIe power, and reconnect the display.

### Exact CompTIA simulation steps

1. Switch both the **computer** and **monitor** to their **Back** views.
2. Disconnect the **DB-15 / VGA cable** by dragging it from the computer to the **Workspace**.
3. Drag it from the monitor into **Inventory**.
4. On the computer, choose **Change View → Motherboard**.
5. Remove the old graphics adapter by dragging **VGA Video Adapter** from the computer into **Inventory**.
6. In **Inventory → GPUs/Expansion Cards**, locate an **HDMI-capable video card**.
7. Drag **Video Adapter, DVI-I, HDMI** into an available **PCI Express** slot on the motherboard.
8. Select the **Power Supply**.
9. From **Selected Item**, drag the **6-pin PCIe power connector** into the card's power socket on its right side.
10. Above the computer, choose **Back**.
11. In **Inventory → Cables**, select **HDMI to HDMI Cable**.
12. Connect one **HDMI connector** to the new graphics card's HDMI port.
13. Connect the other **HDMI connector** to the monitor's HDMI port.
14. Check that the card is seated, powered, and connected to the screen.

**Why this matters:** The PCIe slot carries data, while the 6-pin PCIe connector supplies extra power. HDMI replaces the older VGA cable and provides digital video.

**Evidence to capture:** Old VGA disconnected; new PCIe graphics card; 6-pin power; HDMI cable at both ends.

![CompTIA Lab 2.2.13 instructions](assets/lab-2-2-13-instructions.png)

---

## 8. Lab 2.3.2 — Select and Configure Dual Monitors

**Business context:** An employee needs additional screen space. Two displays must work, and Windows must know which physical screen is on the left.

**Goal:** Install a suitable video card, connect the existing display and a second monitor, then configure the main display and screen order.

### Exact CompTIA simulation steps

**Part A — Install the graphics card**

1. Select the computer's **power** button to turn it **off**.
2. Above the computer, choose **Change View → Motherboard**.
3. In **Inventory → GPUs/Expansion Cards**, choose **Video Adapter, DVI-I, HDMI, Crossfire, PCIe**.
4. Drag the card into the computer's **PCIe slot**.
5. Select the **Power Supply**.
6. In **Selected Item**, drag **Connector, Power Supply, 6-pin PCIe** to the new video card's power port.

**Part B — Connect both monitors**

7. Choose **Change View → Back** on the computer.
8. Drag the **DVI connector** from the computer's **built-in video port** to the new graphics card's **DVI port**. This transfers the original monitor connection to the new card in the simulator.
9. Above the **new monitor on the left**, choose **Change View → Back**.
10. In **Inventory → Cables**, select **HDMI to HDMI Cable**.
11. Connect one **HDMI connector** to the new graphics card.
12. Connect the other **HDMI connector** to the new left monitor.

**Part C — Configure Windows displays**

13. Above the **left monitor**, choose **Front**.
14. Above the **computer**, choose **Front** and press the computer's **power** button.
15. On the Windows desktop, right-click an empty area and select **Display settings**.
16. Maximize **Display settings** for easier viewing.
17. Under **Select and rearrange displays**, select **monitor 2**.
18. Under **Multiple displays**, check **Make this my main display**.
19. Select **Identify** to see which monitor is which.
20. Since the new monitor is physically on the **left**, drag display **2** to the **left** of display **1**.
21. Choose **Apply**.
22. Confirm that mouse movement between the screens matches the physical arrangement and the main screen is correct.

**Why this matters:** Adding a second monitor is only half the work. Windows needs the correct left/right arrangement, and users need the main taskbar and Start menu on their preferred display.

**Evidence to capture:** Two monitors plugged into the graphics card; Windows Display settings with **2** left of **1**; main-display selection.

![CompTIA Lab 2.3.2 instructions](assets/lab-2-3-2-instructions.png)

---

## 9. Lab 2.4 — Set Up an A/V Workstation

**Business context:** A team editing audio and video needs dual monitors and a storage configuration that can continue operating if a single drive fails. The support technician installs hardware and builds a RAID 5 volume.

**Goal:** Add a graphics card and second monitor, install three SATA drives, enable RAID in BIOS, and create a three-disk **RAID 5 (parity)** array.

### Exact CompTIA simulation steps

**Part A — Install the graphics card**

1. Above the computer, choose **Change View → Motherboard**.
2. In **Inventory → GPUs/Expansion Cards**, select **Video Adapter, DVI-I, HDMI, Crossfire, PCIe**.
3. Drag it into the **PCIe slot**.
4. Select **Power Supply**.
5. In **Selected Item**, drag **Connector, Power Supply, 6-pin PCIe** to the graphics card's power socket.
6. Return to **GPUs/Expansion Cards** in Inventory if needed.

**Part B — Install and cable three drives**

7. In **Inventory → Storage**, drag **three Hard Drives** into the **three 3.5-inch drive bays**.
8. In **Inventory → Cables**, choose **Cable, SATA**.
9. Connect one **SATA connector** to a hard drive and the other end to an open **SATA port on the motherboard**.
10. Repeat for the other **two** drives, using a separate motherboard SATA port for each.
11. Select the **Power Supply** from the component list beside the computer.
12. In **Selected Item**, connect an unused **SATA power connector** to the first drive.
13. Repeat for the other two drives.
14. Confirm that **each drive has one SATA data cable and one SATA power connection**.

**Part C — Connect the displays**

15. Above the computer, choose **Change View → Back**.
16. Transfer the original monitor's **DVI connector** from the built-in graphics port to the new graphics card's DVI port.
17. In **Inventory → Peripherals**, place another **Monitor** on the **left** side of the desktop.
18. Switch that monitor to its **Back** view.
19. In **Inventory → Cables**, choose **HDMI to HDMI Cable**.
20. Connect its HDMI ends to the new **graphics card** and the **left monitor**.
21. In **Inventory**, choose **AC Power Cable**.
22. Connect its **female AC connector** to the left monitor and its **male AC connector** to a **wall outlet**.
23. Switch the left monitor to **Front**, then press its **power button**.

**Part D — Enable RAID in BIOS**

24. Switch the computer to **Front** and press its **power button**.
25. During startup, press **F2** (or **Delete**, as shown by the simulator) to open the **BIOS**.
26. In the left menu, expand **System Configuration**.
27. Choose **SATA Operation**.
28. In the right pane, choose **RAID On**.
29. Select **Apply**.
30. Choose **Exit** to restart the computer.

**Part E — Create the RAID 5 volume**

31. After restart, wait for the **RAID controller** to load.
32. At its startup prompt, press **Ctrl + I** (the letter I).
33. Highlight **Create RAID Volume** and press **Enter**.
34. In the **Name** field, press **Enter** to accept the displayed name.
35. On **RAID Level**, use the **Up/Down arrows** to choose **RAID5 (Parity)**, then press **Enter**.
36. At **Select Disks**, press **Enter**.
37. Use the **Up/Down arrows** to move through the drive list; press **Spacebar** to select each drive.
38. Select **all three drives** with the model number **WD800JD** shown in the instructions, and press **Enter**.
39. Press **Tab** to reach **Strip Size**.
40. Make sure **Strip Size = 128 KB**; use the arrows to change it if needed.
41. Press **Enter**.
42. Press **Enter** to accept the **default capacity**.
43. Highlight **Create Volume** and press **Enter**.
44. Press **Y** to confirm the new volume.
45. Press **Esc** to exit the menu.
46. Press **Y** to exit the RAID utility.
47. Check the simulator's tasks to confirm the storage configuration is complete.

**Why this matters:** RAID 5 spreads information and parity across three or more drives. A single disk can fail without immediate loss of the RAID volume's data, but **RAID is not a backup**. Real organizations still need separate backups.

**Evidence to capture:** Three SATA drives in bays; their SATA data and power connectors; RAID On in BIOS; RAID5 (Parity), three selected disks, and **128 KB** strip-size screen; final volume summary.

![CompTIA Lab 2.4 instructions](assets/lab-2-4-instructions.png)

---

## 10. Troubleshooting and verification checklist

| Symptom | First things to check |
| --- | --- |
| Computer does not power on | AC power cable, power strip, motherboard **20+4-pin**, **8-pin CPU**, and **power-switch header** |
| Monitor stays black | Monitor power; HDMI/DVI cable at both ends; connection to the **installed video card** rather than wrong output |
| Keyboard/mouse not responding | They are inserted into USB ports on the computer |
| Printer or scanner unavailable | **USB Type B** in the device, **USB Type A** in the hub; hub attached to computer |
| New graphics card is unpowered | **6-pin PCIe** power connector fully connected |
| Screens are reversed | **Display settings → Identify → drag 2 left of 1 → Apply** |
| RAID utility does not appear | Verify **SATA Operation = RAID On**, save, restart, then press **Ctrl + I** at the prompt |
| RAID 5 not available | Confirm **all three drives** have data and power cables and are selected in the RAID utility |

## 11. My skills demonstrated

- Hardware installation and peripheral cabling
- Desktop setup and end-user readiness
- USB, HDMI, DVI, VGA, SATA, audio, Ethernet, and AC power connector identification
- Component compatibility checks and motherboard header mapping
- PCIe graphics-card replacement and supplemental power
- Windows multiple-display configuration
- BIOS settings and RAID 5 storage configuration
- Methodical troubleshooting and documentation

### A concise resume / portfolio bullet

> Documented seven CompTIA A+ hardware simulations covering desktop deployment, USB devices, Socket 1151 motherboard installation, PCIe graphics upgrades, dual-display configuration, and three-disk RAID 5 setup, with component-level procedures and troubleshooting checks.

## 12. Evidence and honest project status

- [ ] Lab 2.1.2 — completion/score screenshot
- [ ] Lab 2.1.7 — completion/score screenshot
- [ ] Lab 2.1.16 — completion/score screenshot
- [ ] Lab 2.2.11 — completion/score screenshot
- [ ] Lab 2.2.13 — completion/score screenshot
- [ ] Lab 2.3.2 — completion/score screenshot
- [ ] Lab 2.4 — completion/score screenshot

**Note:** The reference images in `assets/` are the instruction screenshots provided with this project. They do not, by themselves, prove that the lab objectives were completed. Replace the checklist with your real results after you verify them.

You can save your own proof-of-work screenshots in an `evidence/` folder and insert them into this README with Markdown, for example:

```md
![My completed dual-monitor configuration](evidence/dual-monitor-complete.png)
```

## 13. How I publish this project on GitHub

1. Sign in at [GitHub](https://github.com).
2. In the top-right **+** menu, choose **New repository**.
3. Give it a clear name, such as **desktop-hardware-deployment-compTIA**.
4. Choose **Public** if you want recruiters to see the portfolio.
5. Select **Add a README file** and choose **Create repository**.
6. Open `README.md`, select the **pencil / Edit** icon, replace the default content with this file's content, then **Commit changes**.
7. Upload the seven images from the package's `assets/` directory into the repository under the same `assets/` path. The paths must stay identical for GitHub to show the images.
8. When you have your own screenshots from the running CompTIA labs, upload them to `evidence/` and add image links to the corresponding sections.
9. Open the repository's main page and scroll through the README. Confirm images and headings display correctly.
10. Copy the GitHub repository URL into your personal portfolio under **Hardware Deployment & Workstation Configuration**.

### Suggested repository structure

```text
desktop-hardware-deployment-compTIA/
├── README.md
├── assets/
│   ├── lab-2-1-2-instructions.png
│   ├── lab-2-1-7-instructions.png
│   ├── lab-2-1-16-instructions.png
│   ├── lab-2-2-11-instructions.png
│   ├── lab-2-2-13-instructions.png
│   ├── lab-2-3-2-instructions.png
│   └── lab-2-4-instructions.png
└── evidence/        # add your actual completion screenshots here
```

---

### Quick memory trick

**Power → Connect → Configure → Verify.**  
First supply power, then connect the right cables, then configure BIOS/Windows when needed, and finally check that the workstation actually works.
