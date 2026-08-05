# STM32WBA Zephyr custom binaries

- LinkLayer_802_15_4_V3_0_Zephyr.a is the 802.15.4 linklayer libraries modified that are needed in Zephyr.

- LinkLayer_BLE_Basic_802_15_4_V3_0_Zephyr.a is the concurrent mode BLE Basic - 802.15.4 linklayer libraries modified that are needed in Zephyr.

- LinkLayer_BLE_Basic_Plus_802_15_4_V3_0_Zephyr.a is the concurrent mode BLE Basic Plus - 802.15.4 linklayer library modified that is needed in Zephyr.

- MAC_802_15_4_V3_0.a is a custom library containing only the mac.c file that was originally embedded in LinkLayer_802_15_4_V3_0.a

- MAC_802_15_4_Concurrent_BLE_Basic_V3_0.a is a custom library containing only the mac.c file that was originally embedded in LinkLayer_BLE_Basic_802_15_4_V3_0.a

- MAC_802_15_4_Concurrent_BLE_Basic_Plus_V3_0.a is a custom library containing only the mac.c file that was originally embedded in LinkLayer_BLE_Basic_Plus_802_15_4_V3_0.a

These lib must not be used in CubeFW environment.

## Troubleshooting

**Caution** : Issues and the pull-requests are **not supported** to submit problems or suggestions related to the software delivered in this repository. The STM32WBA-Zephyr-custom-binaries example is being delivered as-is, and not necessarily supported by ST.

**For any other question** related to the product, the hardware performance or characteristics, the tools, the environment, you can submit it to the **ST Community** on the STM32 MCUs related [page](https://community.st.com/s/topic/0TO0X000000BSqSWAW/stm32-mcus).