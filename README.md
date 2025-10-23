# ADC Single Channel with DMA on STM32F411RE

This project demonstrates how to use the ADC in single-channel mode with DMA on an STM32F411RE microcontroller.

## Description

The project is configured to read a single ADC channel (channel 6) continuously. The ADC is configured to use DMA to transfer the converted data to memory without CPU intervention. This allows the CPU to perform other tasks while the ADC conversion is in progress.

The project is created using STM32CubeIDE.

## Hardware

*   **Board:** NUCLEO-F411RE
*   **ADC Pin:** PA6 (ADC1_IN6)
*   **USART:** USART2 (PA2, PA3) is configured for communication (e.g., for debugging).

## Software

*   **STM32CubeIDE:** The project is created and can be opened with STM32CubeIDE.
*   **STM32Cube FW_F4 V1.28.3:** The project uses the STM32F4xx HAL library.

## How to Use

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/your-username/ADC_Single_Channel_with_DMA_STM32F411RE.git
    ```
2.  **Open the project in STM32CubeIDE:**
    *   Go to `File > Open Projects from File System...`.
    *   Select the cloned repository's directory.
    *   Click `Finish`.
3.  **Build the project:**
    *   Right-click on the project in the Project Explorer.
    *   Select `Build Project`.
4.  **Run the project:**
    *   Connect the NUCLEO-F411RE board to your computer.
    *   Right-click on the project in the Project Explorer.
    *   Select `Run As > STM32 Cortex-M C/C++ Application`.

## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue if you find any bugs or have suggestions for improvements.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
