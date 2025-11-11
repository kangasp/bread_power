# Bread Board Power Module
Goal is to power a bread board.

## Reqs
* Use 18650 to power the board
* Ability to charge the battery with USB-C
* Form factor for bread board
* LEDs to indicate on / charging
* Fuse - resetable circuit protection

## Parts to use
* Boost:  C915088 Boost IC, TPS61022RWUR
* BMS:  C15220, BQ24073RGTR,    https://www.ti.com/lit/ds/symlink/bq24073.pdf?ts=1761246632036&ref_url=https%253A%252F%252Fwww.ti.com%252Fproduct%252FBQ24073%252Fpart-details%252FBQ24073RGTR%253Futm_source%253Dgoogle%2526utm_medium%253Dcpc%2526utm_campaign%253Dapp-null-null-app_opn_en-cpc-storeic-google-ww_en_pur%2526utm_content%253DDevice%2526ds_k%253DBQ24073RGTR%2526DCM%253Dyes%2526gclsrc%253Daw.ds%2526gad_source%253D1%2526gad_campaignid%253D8178941673%2526gbraid%253D0AAAAAC068F1OY5LTfCSqCOSRi7oG12xUk%2526gclid%253DCjwKCAjwpOfHBhAxEiwAm1SwEnpGtKfSzLroLLaXasqsRVhPzDe272zBBU-BZBLuSHX_bdEM7pz5ABoC5aUQAvD_BwE

* USB-C:  C3151650,     USB4125-GF-A
* Inductor (boost):  XAL7030-102MEC, C19191626, SMD,7.5x7.5mm
* Battery Holder: C2979183, MY-18650-01
* Thermistor:  C2892547, KNTC0603/10KF3950, 0603
* PGOOD LED: C34499, KT-0805W, white 0805
* CHG LED: C2297, KT-0805G, green 0805


* Resistors:
    * 5.1k: C25905      (0402) USB cc1 & cc2
    * 680:  C23228      (0603)  iset
    * 1.2k: C22765      (0603)  ilim
    * 1k:   C11702      (0402)  led cur limit
    * 100k: C25741      (0402)  voltage FB divider
    * 732k: C5159692    (0402)  voltage FB divider

Capacitors:
    * 22u:  C12891      (1206)  
    * 10u:  C15850      (0805)
    * 1u:   C28323      (0805)


Switch the battery symbol to be a one pin symbol and use 2.
Battery:BatteryClip_Keystone_54_D16-19mm

Plan to stradle the bread board.


