# STM32WBA Zephyr custom binaries

- WBA6_LinkLayer15_4.a and WBA6_LinkLayer_Thread_lib.a are the 802.15.4 linklayer libraries modified that are needed in Zephyr.

- WBA6_Mac15_4.a is a custom library containing only the mac.c file that was originally embedeed in WBA6_LinkLayer15_4.a.

These lib must not be used in CubeFW environment.

## Troubleshooting

**Caution** : Issues and the pull-requests are **not supported** to submit problems or suggestions related to the software delivered in this repository. The STM32WBA-Zephyr-custom-binaries example is being delivered as-is, and not necessarily supported by ST.

**For any other question** related to the product, the hardware performance or characteristics, the tools, the environment, you can submit it to the **ST Community** on the STM32 MCUs related [page](https://community.st.com/s/topic/0TO0X000000BSqSWAW/stm32-mcus).