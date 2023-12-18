# Analysing-a-Memory-dump-using-Volatility-2
# Forensics Challenge Write-Up

This repository contains a forensics write-up for analyzing a memory dump using Volatility 2.

## About Volatility 2

[Volatility](https://github.com/volatilityfoundation/volatility) is an open-source memory forensics framework that allows you to analyze memory dumps from Windows, Linux, and macOS systems. It is widely used in digital forensics and incident response to extract valuable information from volatile memory.

### Installing Volatility 2

### windows:
.[installing volatility](https://github.com/volatilityfoundation/volatility/releases/tag/2.6)
.Extract the contents of the downloaded archive.
### MacOs: 
. You can run this command :
```bash
brew install volatility
```
#### Linux:

```bash
git clone https://github.com/volatilityfoundation/volatility.git
cd volatility
sudo apt-get install python2.7
sudo apt-get install python-pip
pip install -r requirements.txt
python vol.py
```
# for more details about Memory Forensics using volatility check this video :
[Memory Forensics using Volatility2](https://www.youtube.com/watch?v=2S_pi9qnIo8)
