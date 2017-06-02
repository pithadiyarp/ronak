     * For Nordic - HW_PLATFORM = nrf52dk
     * For NucleoF401RE - HW_PLATFORM = nucleo-f401
     * For Example: `make -C RIOT/examples/dw1000_rtls_arm BOARD=nrf52dk`
* Command to build and flash
    ```bash
     $ sudo make -C RIOT/examples/dw1000_rtls_arm BOARD=HW_PLATFORM flash
    ```
   * For Nordic - HW_PLATFORM = nrf52dk
   * For NucleoF401RE - HW_PLATFORM = nucleo-f401
   * For Example: `sudo make -C RIOT/examples/dw1000_rtls_arm BOARD=nrf52dk flash`


#### KNOWN ISSUES

* Tracking Use case
Observed Anchor to anchor bias corrected range(ma), Tag to anchor bias
corrected range(mc) and Tag to anchor raw range(mr) range deviation is between 25-40 cm instead of 15cm for all modes randomly.
* Navigation Use case
Observed that T0 to A0, A1, A2 Range info is detected as 0 randomly
* Geo-Fencing Use case
Log Pattern is not proper as expected: A0:T0, A0:T1, A0:T0 & A0:T2 instead of
A0:T0, A0:T1, A0:T2 for all modes. In case of Mode 3, this is observed occasionally

#### Known Limitations

  Due to EVB 1000 Hardware constraints with External Microcontroller

  * Range Distance Estimation is displayed on PyTerm Terminal
  * Selection of Mode(Mode-1/2/3/4), UNIT(Tag/Anchor) and UNIT ID (0 to 2) is
    configured in DecaRange RTLS ARM Application based on User Input

## DOCUMENTATION

* Userguide is available in DW1000/doc/PP_DecaWave_BSP_ReleaseNotes.pdf
* ReleaseNote is available in DW1000/doc/PP_DecaWave_BSP_UserGuide.pdf
     * For Nordic - HW_PLATFORM = nrf52dk
     * For NucleoF401RE - HW_PLATFORM = nucleo-f401
     * For Example: `make -C RIOT/examples/dw1000_rtls_arm BOARD=nrf52dk`
* Command to build and flash
    ```bash
     $ sudo make -C RIOT/examples/dw1000_rtls_arm BOARD=HW_PLATFORM flash
    ```
   * For Nordic - HW_PLATFORM = nrf52dk
   * For NucleoF401RE - HW_PLATFORM = nucleo-f401
   * For Example: `sudo make -C RIOT/examples/dw1000_rtls_arm BOARD=nrf52dk flash`


#### KNOWN ISSUES

* Tracking Use case
Observed Anchor to anchor bias corrected range(ma), Tag to anchor bias
corrected range(mc) and Tag to anchor raw range(mr) range deviation is between 25-40 cm instead of 15cm for all modes randomly.
* Navigation Use case
Observed that T0 to A0, A1, A2 Range info is detected as 0 randomly
* Geo-Fencing Use case
Log Pattern is not proper as expected: A0:T0, A0:T1, A0:T0 & A0:T2 instead of
A0:T0, A0:T1, A0:T2 for all modes. In case of Mode 3, this is observed occasionally

#### Known Limitations

  Due to EVB 1000 Hardware constraints with External Microcontroller

  * Range Distance Estimation is displayed on PyTerm Terminal
  * Selection of Mode(Mode-1/2/3/4), UNIT(Tag/Anchor) and UNIT ID (0 to 2) is
    configured in DecaRange RTLS ARM Application based on User Input

## DOCUMENTATION

* Userguide is available in DW1000/doc/PP_DecaWave_BSP_ReleaseNotes.pdf
* ReleaseNote is available in DW1000/doc/PP_DecaWave_BSP_UserGuide.pdf
