\## Session 1 — June 23 2026



\### What I did

\- Installed STM32CubeIDE 2.1.1 and STM32CubeMX

\- Updated ST-Link firmware from V2.J37 to V2.J48. Initial issue with AliExpress clone hardware.

\- Wrote register-level LED blink on PC13, confirmed working on hardware.

\- Installed Git, initialized repo, first commit made.

\- Created GitHub account (bnguyen-eng), pushed repo live.



\### What I learned

\- STM32 peripherals need their clock enabled before use (RCC register)

\- Pins must be configured as input or output explicitly

\- Git commit messages follow: type(scope): description

### Thoughts

\- First project intending to learn about GNC, Hardware, C, C++, GitHub.





\## Session 2 — June 24 2026



\### Goal

\- Wire MPU-6050 to Blue Pill

\- Read raw accelerometer and gyroscope data over I2C

\- Send data to PC over UART to verify readings

### Thoughts

\- Application of communication protocols.

