# LTE_HACKRF

## Requirements
- HackRF device
- Computer running Linux
- Smartphone

## Setup
1. Download and unzip the zip file attached to this post.
2. Install the HackRF firmware: `sudo apt-get install hackrf`
3. Connect the HackRF device to your computer.
4. Run the following command: `hackrf_transfer -t srslte.bin -f 2649800000 -a 0 -s 15360000 -R -x 45`
5. On your smartphone, go to settings, SIM card settings, operator selection, and select network search.
6. If everything worked, you should see a new 4G network named TestNet PLMN 00101.

## Troubleshooting
If you encounter any issues, please let us know by creating a new issue on this repository.
