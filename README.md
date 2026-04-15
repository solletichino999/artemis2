Equipment used:
- WiMo 80 cm 2.4 GHz Wi-Fi grid dish (23.3 dB at 2.2 GHz) with stock linear dipole feed (-3 dB with Orion RHCP)
- Mini-Circuits ZX60-242GLN-S+ LNA powered via USB
- Sysmocom S-Band cavity filter (2170-2300 MHz)
- Nooelec Ham It Down downconverter powered by USB (1500 MHz LO)
- Airspy R2 in linear mode with 16x decimation
- Nooelec In-Line DC Block and premium SMA connectors
- MacBook Air M4 with SatDump running
- AmazonBasics lightweight camera tripod
- Custom dish-tripod adapter with diving counterweight (designed by ChatGPT)

An AntRunner rotator was available but wasn't used since Orion was moving slowly in the sky, the dish had 11° beamwidth (at -3 dB) and was manually oriented every ten minutes with the help of an Android smartphone.
A Leo Bodnar LBE-1420 GPSDO was available but wasn't used because precise Doppler measurement was out of scope.
Pointing was done using the attached Jupyter notebook (made with the help of Claude Code), which took the updated data from JPL Horizons.
Time in the screenshots and in file names is UTC+2.

First night (08/04/2026):
- Orion was at 360885 km (210.5 dB free-space path loss)
- Maximum elevation was 19.7° at 02:26 UTC (180° azimuth)
- Carrier was detected at 2216.507 MHz (+7 KHz Dopppler)
- Carrier was 5.5 dB over noise floor

<img src="photos/20260408 031353.jpg" alt="Dish" width="800">
<img src="signal/2026-04-08 03.21.44.png" alt="Signal" width="800">

Second night (09/04/2026):
- Orion was at 292654 km (208.7 dB free-space path loss)
- Maximum elevation was 18° at 02:33 UTC (180° azimuth)
- Carrier was detected at 2216.509 MHz (+9 KHz Dopppler)
- Carrier was 6.5 dB over noise floor

<img src="photos/20260409 021516.jpg" alt="Dish" width="800">
<img src="signal/2026-04-09 03.05.51.png" alt="Signal" width="800">

The signal was received on a rooftop in the center of Bari, Italy, with a clear view of the sky. The system was left to run for half an hour before reception. The radio pollution was heavy and two previous reception attempts using a modified MMDS downconverter with SAW filters failed.
The photos were shot using a Realme GT 8 Pro.

Also featured on:
- <a href="https://www.rtl-sdr.com/receiving-the-artemis-2-s-band-carrier-with-a-wi-fi-dish-and-airspy-r2/">RTL-SDR.COM Blog</a>
- <a href="https://community.libre.space/t/artemis-ii-mission/14334/63">Libre Space Community</a>
