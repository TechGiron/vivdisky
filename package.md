<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/TechGiron/vivdisky">
    <img src="https://play-lh.googleusercontent.com/7ByFpdTmtc3JCmTUCUKQTmQChqbvlk79JSnyt27ORfTKK-51m_kyFs3B6YE7xRzLM2k=rw" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">Vivdisky</h3>

  <p align="center">
   An Unofficial Python version of Vivdisky API wrapper
    <br />
    ·
    <a href="https://www.telegram.dog/ask_admin001">Report Bug</a>
  </p>
</div>


---

# Vivdisky
An Unofficial Python version of Mdisk API wrapper. Used to convert and rename Mdisk Files.

## Installation

Install mdisky with pip

```bash
pip install vivdisky
```
    
To Upgrade

```bash
pip install --upgrade vivdisky
```
    
    
## Usage

```python
from vivdisky import Mdisk
import asyncio

async def main():
    mdisk = Mdisk('us5CqX8oandALtQ86FLq')
    link = await mdisk.convert('https://vivdisk.com/convertor/play/1DWoKjvHH43M')
    print(link)

asyncio.run(main())
```

```python
Output: https://vivdisk.com/convertor/play/9oJ9jAD3CwwlFws
```
---
## See the [documentation](https://github.com/kevinnadar22/mdisky) for more information about the Mdisk API wrapper.
