
# Claymore's Dual Miner

Claymore's Dual Miner is a versatile and high-performance GPU mining software designed specifically for Ethereum (ETH) mining, along with the ability to mine a second coin simultaneously. It supports both AMD and NVIDIA GPUs, using OpenCL and CUDA for optimized performance and maximum hashrate. 

## Features

- **Dual Mining**: The software allows you to mine Ethereum (ETH) alongside another coin like Decred, Siacoin, Pascal, or Lbry. This simultaneous dual mining maximizes your GPU’s potential.
  
- **GPU Support**: Full support for both AMD and NVIDIA graphics cards, making it accessible for most miners. Claymore’s Dual Miner is optimized for high performance on both platforms.

- **OpenCL & CUDA Optimization**: The software utilizes both OpenCL (for AMD GPUs) and CUDA (for NVIDIA GPUs), ensuring that you get the most out of your hardware. 

- **Automatic GPU Tuning**: The miner automatically tunes GPUs for optimal performance, reducing the need for manual intervention and ensuring the best possible mining performance.

- **Detailed Statistics**: The software offers a comprehensive display of various statistics, such as hash rates, temperatures, fan speeds, and power consumption, so you can monitor your mining performance in real time.

- **Stability Watchdog**: Claymore’s Dual Miner comes equipped with a watchdog feature that ensures stability during long-term mining operations. It will automatically restart the miner if it detects any instability or errors, ensuring uninterrupted mining.

## System Requirements

- **Operating System**: Windows 7/8/10, Linux
- **GPU**: AMD or NVIDIA GPU
- **Dependencies**: OpenCL for AMD GPUs, CUDA for NVIDIA GPUs
- **Internet**: A stable internet connection is recommended for mining.

## Installation

1. Download the latest version of Claymore’s Dual Miner from the official repository or trusted sources.
2. Extract the files to a folder of your choice.
3. Configure the miner by editing the `start.bat` (Windows) or `start.sh` (Linux) file.
4. Insert your mining pool's information and wallet address in the appropriate fields.
5. Launch the miner and start earning rewards.

## Configuration

To configure the miner, you’ll need to edit the `start.bat` or `start.sh` file. Here’s an example of the basic configuration:

```
ethminer.exe -epool eth.pool.com:3333 -ewal YourWalletAddress.WorkerName
```

Replace `eth.pool.com:3333` with your Ethereum mining pool’s address and `YourWalletAddress.WorkerName` with your Ethereum wallet address and worker name.

## Tips for Optimization

- **Overclocking**: Overclocking your GPU can significantly improve mining performance. However, it’s important to balance power consumption and stability. Claymore’s Dual Miner includes automatic tuning to help with this.
  
- **Cooling**: Proper cooling is essential for maintaining GPU performance and stability over time. Ensure your system has adequate ventilation to prevent overheating.

- **Miner Stability**: If you experience crashes or instability, check your GPU drivers, update them if needed, and ensure your system is running at a stable temperature.

## Troubleshooting

- **Low Hashrate**: If your hashrate seems lower than expected, check if your GPU drivers are up to date and whether the mining software is configured correctly.
  
- **Miner Stops Running**: This can happen due to a system crash or instability. Ensure that the stability watchdog is enabled and that your system is properly cooled.

- **Errors in Logs**: Check the log files for any specific errors that might provide more information on what’s causing issues. 

## Disclaimer

Use this software at your own risk. While Claymore’s Dual Miner is highly reliable, mining involves risks such as hardware failure and potential software instability. Always ensure that your hardware is well-maintained and monitor your system regularly.

Claymore’s Dual Miner is a powerful tool for maximizing your mining profitability, offering flexibility with dual mining and robust performance on both AMD and NVIDIA GPUs. Whether you're an experienced miner or a beginner, Claymore’s Dual Miner provides a stable and efficient mining experience.
