

### <div align=center>**Claymore's Dual Miner**</div>

###### Claymore's Dual Miner is a powerful and efficient software designed for mining Ethereum (ETH) and other cryptocurrencies simultaneously. It works with both NVIDIA and AMD GPUs, using CUDA for NVIDIA cards and OpenCL for AMD cards, which allows it to maximize the performance of your system. The miner lets you mine Ethereum and another coin like Decred (DCR), Siacoin (SC), Pascal (PASC), or Lbry (LBC) at the same time, which is great for people who want to make the most of their hardware.

### *Key Features*

##### - Dual Mining: With Claymore's Dual Miner, you can mine Ethereum (ETH) while also mining another cryptocurrency like Decred, Siacoin, Pascal, or Lbry. The software optimizes both coins to ensure you get the best performance possible.
  
##### - High Performance: The miner is optimized to use the full power of both NVIDIA and AMD GPUs. It uses CUDA for NVIDIA GPUs and OpenCL for AMD, making sure you're getting the most out of your hardware.

##### - GPU Optimization: Claymore's Dual Miner can automatically tune the GPU settings for better efficiency, so you can get higher hash rates without wasting too much power.

##### - Stability Watchdog: This feature ensures that the miner automatically restarts if it ever crashes, helping you keep your system running without downtime.

##### - Real-Time Stats: You get live stats showing hash rates, temperature, and power usage for each GPU. This makes it easy to keep an eye on your mining setup and adjust settings as needed.

##### - Multi-GPU Support: The miner works well on systems with multiple GPUs, so if you're running a big mining rig, this software will help you maximize your setup.

### *Supported Hardware*

##### - NVIDIA GPUs: Works best with CUDA-enabled NVIDIA GPUs, such as the GTX 1060, GTX 1070, GTX 1080, RTX 2060, RTX 2070, RTX 2080, and even the newer RTX 3000 series cards.

##### - AMD GPUs: Compatible with AMD GPUs that support OpenCL, including the Radeon RX series like RX 580, RX 570, Vega 56, and Vega 64.

##### - Operating Systems: The miner works on both Windows (10 and 7) and Linux. If you're on Windows, tools like MSI Afterburner can help with GPU tuning and overclocking. For Linux, the miner works with command-line and GUI options.

##### - Minimum Requirements: For Ethereum mining, you’ll need at least 3GB of VRAM on your GPU, but for dual mining, having more VRAM is better to avoid performance issues due to increasing DAG file size.

### *Installation Instructions*

##### 1. Download the latest release from the official GitHub page: [Claymore's Dual Miner Releases](https://github.com/barrrry1/Claymore-s-Dual-Miner/releases).

##### 2. Extract the ZIP file to a folder of your choice.

##### 3. Locate the `.bat` (for Windows) or `.sh` (for Linux) file and open it in a text editor. Add your Ethereum wallet address and the mining pool details.

##### 4. Run the `.bat` or `.sh` file to start mining.

### *Example for Ethereum and Decred setup:*

##### ethminer -epool eth-us1.ethermine.org:4444 -ewal YOUR_ETH_WALLET_ADDRESS -eworker WORKER_NAME -dpool stratum+tcp://dcr-us1.fpmpool.com:3333 -dwal YOUR_DECRED_WALLET_ADDRESS

##### Troubleshooting Common Issues

#### - *Low Hashrate*:
  ##### - Make sure your GPU drivers are up-to-date. Outdated drivers can really hurt mining performance.
  ##### - If you’re using an AMD GPU, adjusting memory timings or overclocking might help boost your performance.
  ##### - For NVIDIA GPUs, tweaking CUDA settings could improve your results.

#### - *System Instability*:
  ##### - If the miner crashes, check your power supply and make sure your system isn’t overheating. You can monitor temperatures using software like HWMonitor or MSI Afterburner.
 ##### - Sometimes, reducing the intensity of the secondary coin (in dual mining mode) can help with stability.

#### - *Dual Mining Problems*:
 ##### - If dual mining is causing crashes or low performance, try lowering the difficulty of the second coin (like Decred or Siacoin).

#### - *GPU Recognition Issues*:
  ##### - On Linux, make sure you’ve installed all the necessary drivers and libraries (like OpenCL or CUDA). For NVIDIA, make sure you have the correct CUDA toolkit installed.

### *Frequently Asked Questions (FAQ)*

##### Why is my mining speed lower than expected?

###### - NVIDIA GPUs: On Windows 10 with WDDM 2.x drivers, mining performance can be slower compared to older Windows 7/8 drivers. If you’re using an older card like the GTX 750 Ti, try downgrading to an older driver that was optimized for mining.
###### - AMD GPUs: Performance can drop a bit with older cards when mining Ethereum, especially as the DAG file size increases. If your card has less than 4GB of VRAM, you may notice a performance decline over time.

##### Can I mine Ethereum with less than 4GB VRAM?

###### - Mining Ethereum on GPUs with less than 4GB VRAM isn’t recommended, as the DAG file size now exceeds 4GB. While it’s still possible to mine, performance will degrade, and you’ll lose efficiency over time.

#### How can I optimize my miner for better performance?

###### - To improve performance, you can try overclocking your GPUs (both core and memory clock). Using tools like MSI Afterburner can help. Also, adjusting the intensity of the secondary coin (for dual mining) can make a big difference.

#### How can I monitor my miner’s performance?

###### - The miner displays real-time stats in the command line, showing you the hash rates, temperatures, and power usage of each GPU. You can also use third-party tools like HWMonitor or GPU-Z for more detailed monitoring of your system’s performance.

### *Supported Coins*

#### Claymore's Dual Miner supports these coins for dual mining:

#### - Ethereum (ETH)
#### - Decred (DCR)
#### - Siacoin (SC)
#### - Pascal (PASC)
#### - LBRY (LBC)

#### These coins work perfectly with the miner, allowing you to mine Ethereum and another coin at the same time for extra profitability.

### *Release Information*

#### For the latest versions, bug fixes, and new features, visit the official release page: [Claymore's Dual Miner Releases](https://github.com/barrrry1/Claymore-s-Dual-Miner/releases).

### *License*

#### This software is licensed under the MIT License. Check the LICENSE file for full details.
