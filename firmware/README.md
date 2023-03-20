# How to determinate the right firmware

Open the PCMaster and read out all parameters. The you'll also get SW version and HW version.
![image](https://user-images.githubusercontent.com/17761850/226378182-b9914181-9da4-4d82-b58b-185ea13af9d0.png)

"BMS hardware version number" records the hardware chip scheme selected by
the BMS. For a total of thirteen characters, the first three digits are fixing as BMS,
the middle is MCU, as shown in Table 1, and the last four digits are AFE, as
shown in Table 2.
![image](https://user-images.githubusercontent.com/17761850/226378862-f021d99c-3852-474d-a59c-ddf92bd9d719.png)
"BMS software version number" records the project software version of the BMS.
Total of thirteen characters, the first two digits represent the chip solution, the
middle represents the release date, the last four digits are reserved, and the
default represents the project code.
1. The first item of the item number: 1, STM32F103; 2, STM32F030; 3,
GD32E230.
1. The second digit of the item number: 1, 309; 2, 303; 3, 9818; 4, DVC.
