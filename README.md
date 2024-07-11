# EcoDecibel

Use at your own risk, expect everything to crash and burn.  

**Research Question:**
Can an IoT-based noise measurement device, EcoDecibel, provide accurate and continuous noise monitoring comparable to standard noise meters, and how effectively can it forecast noise levels using various predictive models?

## Features:
* Easy to use, just plug and start measuring.  
* Consume very little power.  
* Only collects decibel value and stored in the SD card localy.
* Looks cool!

<p align="center">
<img src="https://github.com/SCWhite/EcoDecible/assets/11376362/8538c3b6-0a91-4a51-98a7-f5913ca7396b" width="600">
</p>



## EcoDecibel components: 
* SAMD21 microcontroller 
* SPH0645 Microphone
* DS3231 RTC Clock
* MicroSD Memory Card
* Error Indicate LED
* A custom made pcb

<p align="center">
<img src="https://github.com/SCWhite/EcoDecible/assets/11376362/79f6c2ee-d813-4f2f-b3f6-9bfdab01b7bd" width="600">
</p>



> [!NOTE]
> It is important to note that we still found a difference of a few seconds between the RTC times.  
> It is recommended to check and calibrate the time before starting the test.


## Steps for use:
1. Make sure the memory card is inserted into the machine, else it won't do anything.
2. Connect power supply (battery, solar panel, power bank or a bunch potato)
3. Check if the error light is on
4. The system will start recording data automatically.

## Making your own:
1. Gether each part
2. Make the pcb
3. Combine every parts
4. Upload firmware
5. Insert MicroSD card
6. Connect power supply
7. There is no step 7
8. Profit :-) 

## How much does it cost?

- **Class 1 noise meter**: $3000 USD. Ouch.
- **Class 2 noise meter**: $900 USD. Still pricey.
- **EcoDecibel**: A mere $90 USD. Your wallet will thank you.


## Important source

https://github.com/waagsociety/amsterdam-sounds-kit  
https://gitlab.waag.org/lodewijk/amsterdam-sounds-kit  

## Testing and Performance
We evaluated the performance of the EcoDecibel across various settings and compared its accuracy against established professional instruments. 
The results demonstrate that the EDM performs consistently and reliably in multiple scenarios, making it a viable environmental noise monitoring and prediction tool. When placed side-by-side with Class 1 and Class 2 sound meters, it showed an R-squared value of 0.983 when compared to the Class 2 meter and 0.949 when compared to the Class 1 meter. 


<p align="center">
<img src="https://github.com/SakshiNYCU/EcoDecibel/raw/main/images/1.jpg" width="600">
</p>

<p align="center">
<img src="https://github.com/SakshiNYCU/EcoDecibel/raw/main/images/2.png" width="600">
</p>

This level of accuracy is sufficient for many practical applications, allowing the EDM to be used as a cost-effective alternative to more expensive professional-grade meters. The field verification tests in different outdoor environments also confirmed its robustness and reliability. 

Here's a glimpse of EcoDecibel in action!

<p align="center">
<img src="https://github.com/SakshiNYCU/EcoDecibel/raw/main/images/3.jpg" width="600">
</p>

<p align="center">
<img src="https://github.com/SakshiNYCU/EcoDecibel/raw/main/images/4.png" width="600">
</p>
