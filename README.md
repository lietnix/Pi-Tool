![Pi Tool Logo](https://i.imgur.com/Mjtqx6w.png)

> Overclocking, monitoring and button remapping utility for Raspberry Pi 4, designed for systems housed in the Cooler Master Pi Case 40.

The utility allows users access to a basic set of overclocking profiles, tested and validated based on the thermal perfomance of Cooler Master's Pi Case 40 enclosure, monitoring of system metrics and assignment of multiple functions to the built-in button.

# Getting Started

TODO

# Features

### Overclocking
The overclocking functions included in Pi Tool modify the following values in `/boot/config.txt: over_voltage, arm_freq, gpu_freq`.
Users can further modify these settings by entering the following code in the terminal window: `sudo nano /boot/config.txt`.
<br />
<br />
*For this operation, a 3A 5V power supply is highly recommended.*
<br />
<br />
Overclocking may cause system's instabilities, most show up immediately with a failure to boot. If this occurs, hold down the shift key during the next boot. This will temporarily disable all overclocking, allowing you to boot successfully and then edit your settings.<br />
<br />
**The utility offers multiple overclocking presets to the users:**
- **Base Clock**
  - Restores `config.txt` to the stock values

- **10%**
  - `arm_freq=1650`
  - `gpu_freq=550`
  - `over_voltage=2`

- **20%**
  - `arm_freq=1800`
  - `gpu_freq=600`
  - `over_voltage=4`

- **30%**
  - `arm_freq=1950`
  - `gpu_freq=650`
  - `over_voltage=5`

## System Monitoring

The Pi Tool offers a section dedicated to monitoring the systems status and performance, useful to track thermal output and clock speed when adjusting overclocking settings and to have a quick visual representation of the system's status.

**Included metrics**:
- **Core Temperature**
- **Core Frequency**
- **RAM Usage**
- **System Load**

## Button Remapping

The Pi Case 40 includes a button that shortens pin 5 and 6 when pressed (`GPIO3` and `GND`). Out of the box, this allows to wake up a Raspberry Pi from its halt state. Pi Tool builds upon this function by allowing users to not only assign a function to the button to be triggered when the system is running, but also to set up sequences of short and long button presses, allowing additional functions to be triggered by the same button.

**Included button actions**:
- **System Shutdown**
- **System Restart**
- **Run Custom Script**
- **Open in Browser**

<br />

<p align="center">
  <img src="https://i.imgur.com/9uufTjP.jpg" alt="Sublime's custom image"/>
</p>
<br />
<br />

## We recommend using the Pi Tool in conjunction with Cooler Master's Pi Case 40
<br />
Pi Tool is designed to be used in conjunction with Pi Case 40. The overclocking profiles are defined based on the thermal perfomance of the enclosure and the power button re-mapping features is also based on the phisical implementation of the switch in Pi Case 40.
<br />
Any user is free to install Pi Tool, although we strongly recommend to avoid overclocking non cooled system via Pi Tool.<br />
The button remapping feature works with any 3rd party PUSH switches connected to PIN5 and PIN6 on the GPIO (GPIO3 / GND).
<br />
<br />




## Why is Cooler Master on GitHub?
<br />
Cooler Master recently entered the Raspberry Pi ecosystem with the Pi Case 40, a premium cooling enclosure for on-the-go Raspberry Pi users.<br />
The project was fully founded in under an hour on Kickstarter and the goal behind the campaign was simple: develop everything based on community's feedback and deliver what the community needs. All CAD files for the enclosure are publicly available on Cooler Master's website as well as some additional alternative designs for the users to play with.<br />
Following the same "Make It Yours" philosophy we developed the Pi Tool utility, a simple platform that allows users to explore overclocking safely and customize how they interact with their Raspberry Pi based systems. We host this project on GitHub to allow downloading and remixing of the files to further improve the users experience and enable them to share their work to others in the community. <br />

[Pi Case 40 Kickstarter](https://www.kickstarter.com/projects/coolermaster/pi-case-40) • [Product Page](http://www.coolermaster.com/catalog/cases/raspberry-pi/pi-case-40/) • [Contact Us](https://account.coolermaster.com/IntroSupport.aspx)
<br />
<br />
<br />

## History of Cooler Master

Cooler Master Co., Ltd. is a computer hardware manufacturer based in Taiwan. Founded in 1992, the company produces computer cases, power supplies, air and liquid CPU coolers, laptop cooling pads, peripherals and more.<br />
<br />
Our components represent so many different personalities because our community does not fit into just one mold. It doesn’t matter if you’re a student on a tight budget, a graphic designer that’s brand new to building, or a veteran modder of high-end gaming PCs; we offer components to inspire creative freedom in everyone. **We believe that personal preference and individual expression leads to innovation.**<br />
<br />
**Cooler Master's community is never short on feedback and strong opinions—we love that.** Hearing your thoughts and ideas give us the opportunity to be a part of your building journey, it helps us perfect the DIY experience, and it encourages us to adapt our product development process. After all, it is the community of builders, creators, and gamers who are an integral part of Cooler Master, helping bring our ideas to life. Together, we have been able to heighten the standards of how PCs are configured, transform the way they look and feel, and surpass the technological expectations of today. That’s where our passion stems from and that’s what it means to truly Make It Yours.<br />
<br />
<br />

## Join our community!

[Reddit](https://www.reddit.com/r/coolermaster/) • [Facebook](https://www.facebook.com/coolermaster/) • [Instagram](https://www.instagram.com/coolermaster/) • [Youtube](https://www.youtube.com/channel/UCojNjp-K3t9NyTTlsFXQkGA) • [Twitter](https://twitter.com/CoolerMaster)
