

# Release Notes for
# <mark>STM32WLxx SubGHz Physical Layer Middleware</mark>
Copyright &copy; 2021 STMicroelectronics\

[![ST logo](_htmresc/st_logo_2020.png)](https://www.st.com)

# Purpose

This Middleware provides the SubGHz Physical Layer for the stm32wlxx products. This covers

- STM32WLxx devices

This driver is composed of the radio driver and radio interface under "stm32_radio_driver" directory.


# Update History

<label for="collapse-section4" aria-hidden="true">__V1.3.0 / 21-Oct-2022__</label>
<div>

## Main Changes

- Feature: 169MHz validation support
- Feature: Add LoRa-E support (LR-FHSS)
- Feature: RF output optimization
- Chore: Sync Word register addresses not matching Semtech SX1261/2 datasheet
- Fix: SUBGHz GCFO registers not in line with the RM
- Fix: AGC of radio stuck when jammed
- Release Notes update

## Known limitations:

None

</div>

<label for="collapse-section3" aria-hidden="true">__V1.2.0 / 14-Dec-2021__</label>
<div>

## Main Changes

- Feature: Add defines RADIO_SIGFOX_ENABLE and RADIO_GENERIC_CONFIG_ENABLE to reduce code size when not needed
- Feature: Add Tx GMSK support
- Chore: Align register names with Reference Manual
- Chore: Clarify node/broadcast address
- Fix: Set_RxDutyCycle() function (Rx timeout Issue)
- Licensing update: New way to declare licenses
- Release Notes update

## Known limitations:

None

</div>

<label for="collapse-section2" aria-hidden="true">__V1.1.0 / 29-Apr-2021__</label>
<div>

## Main Changes

- fix: SMPS drive level init
- fix: GENERIC_BPSK in RadioSetTxGenericConfig function (test mode)
- fix: MODEM_BPSK is not handled in RadioSetModem in radio.c
- feature: add cfo calculation
- fix: reduce interrupt scope to minimize privilege stack code execution
- feature:add long packet in radio_fw
- feature: Support IBM whitening by firmware radio_fw
- fix: Channel Activity Detection: antenna switch set in rx mode
- fix: Deadlock of WL RF driver
- fix: PingPong RxErrors when SF12, BW500, CR 4/8
- feature: move GetFskBandwidthRegValue in radio_driver
- fix: Incorrect LoRa PER Results
- feature: align to LoRaWAN Semtech stack v4.4.7 integration - Radio Part

## Known limitations:

None

</div>

<label for="collapse-section1" aria-hidden="true">__V1.0.0 / 21-Oct-2020__</label>
<div>

## Main Changes

- First Release

## Known limitations:

None

</div>


For complete documentation on STM32WLxx,
visit: [www.st.com/stm32wl](http://www.st.com/stm32wl)

*This release note uses up to date web standards and, for this reason, should not be opened with Internet Explorer but preferably with popular browsers such as Google Chrome, Mozilla Firefox, Opera or Microsoft Edge.*
<abbr title="Based on template cx566953 version 2.0">Info</abbr>