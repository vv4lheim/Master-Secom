This report explores the vulnerabilities of IoT devices through SDR techniques. Conducted at Sorbonne University, the project addresses the inherent risks of radio communications, where signals propagate in open space, making them susceptible to interception and jamming.

The study utilizes a Raspberry Pi platform equipped with RTL-SDR and PlutoSDR hardware to analyze devices operating on various frequencies. Key experiments include:
* Replay Attacks: Intercepting and re-emitting fixed codes to control smart plugs and roller shutters using tools like 433Utils and URH.
* False Data Injection Attacks: Manipulating weather station displays by injecting forged temperature frames.
* Advanced Signal Analysis: Moving to the 2.442 GHz band to reverse-engineer drone communications using GNU Radio, which involved bypassing XOR encryption and calculating CRC to retrieve a hidden flag.

The project demonstrates that many consumer IoT devices remain fragile due to the use of simple modulations (ASK/OOK) and the absence of protective mechanisms such as rolling codes or robust encryption.
