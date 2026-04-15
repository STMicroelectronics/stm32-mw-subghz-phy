

# <small>Release Notes for</small> STM32WLxx SubGHz Physical Layer Middleware
Copyright &copy; 2021 STMicroelectronics\

    
[![ST logo](../../../_htmresc/st_logo_2020.png)](https://www.st.com)


# License

Licensed by ST under BSD 3-Clause license (the \"License\"). You may
not use this component except in compliance with the License. You may
obtain a copy of the License at:

[https://opensource.org/licenses/BSD-3-Clause](https://opensource.org/licenses/BSD-3-Clause)

# Purpose

This Middlewares provides the SubGHz Physical Layer for the stm32wlxx products. This covers

- STM32WLxx devices

This driver is composed of the radio driver and radio interface under "stm32_radio_driver" directory.


# Update History
<label for="collapse-section2" aria-hidden="true">v1.1.0 / 29-Apr-2021</label>
<div>

## Main Changes
### fix: SMPS drive level init
### fix: GENERIC_BPSK in RadioSetTxGenericConfig function (test mode)
### fix: MODEM_BPSK is not handled in RadioSetModem in radio.c
### feature: add cfo calculation
### fix: reduce interrupt scope to minimize privilege stack code execution
### feature:add long packet in radio_fw
### feature: Support IBM whitening by firmware radio_fw
### fix: Channel Activity Detection: antenna switch set in rx mode 
### fix: Deadlock of WL RF driver
### fix: PingPong RxErrors when SF12, BW500, CR 4/8
### feature: move GetFskBandwidthRegValue in radio_driver
### fix: Incorrect LoRa PER Results
### feature: align to LoRaWAN Semtech stack v4.4.7 integration - Radio Part


</div>

<label for="collapse-section1" aria-hidden="true">v1.0.0 / 21-Oct-2020</label>
<div>

## Main Changes
### First Release

</div>



For complete documentation on STM32, visit: http://www.st.com/stm32)]

This release note uses up to date web standards and, for this reason, should not be opened with Internet Explorer
but preferably with popular browsers such as Google Chrome, Mozilla Firefox, Opera or Microsoft Edge.