TON DUC THANG UNIVERSITY
GRADUATION PROJECT
ELECTRONICS - TELECOMMUNICATIONS ENGINEERING
TITLE: SMART HOMES UTILIZE THE AIoT TECHNOLOGY
TITLE (IN VIETNAMESE): NHÀ THÔNG MINH ỨNG DỤNG AIoT
PERFORMED BY: LUU PHUOC SANG\ - STUDENT ID: 420H0317
INFORMING INSTRUCTOR: Dr. Nguyen Huu Khanh Nhan
CITY: Ho Chi Minh City, August 17, 2025


THE PROJECT IS COMPLETED AT TON DUC THANG UNIVERSITY.
I hereby declare that this is my own research work, conducted under the scientific guidance of Dr. Nguyen Huu Khanh Nhan. The research content and results presented in this project are truthful and have not been published in any form prior to this. The data included in the tables used for analysis, commentary, and evaluation were collected by the author from various sources, which are clearly cited in the references section. Additionally, this Graduation Project incorporates some comments, evaluations, and data from other authors and organizations, all of which have been properly cited and referenced. If any form of fraud is detected, I take full responsibility for the content of my Graduation Project. Ton Duc Thang University bears no responsibility for any copyright or intellectual property violations caused by me during the implementation of this project (if any).


ABSTRACT:
This project focuses on developing a Smart Home system that integrates Artificial Intelligence (AI) and the Internet of Things (IoT) to create an intelligent and automated living environment. The system consists of interconnected devices, including a Master Device (Gateway) and Node Devices, enabling seamless control and monitoring of home appliances. AI functionalities such as voice control and image processing are incorporated to enhance automation, allowing users to interact easily with smart devices. A user-friendly web application interface enables real-time device management and monitoring, while also supporting personalized automation based on user behaviors and preferences. This study aims to evaluate the effectiveness of the AIoT-based Smart Home system in improving energy efficiency, home security, and overall convenience, contributing to the advancement of smart living technologies. Through this project, we aim to build a scalable, secure, and efficient Smart Home platform that enhances the daily living experience of users.

INSTRUCTIONS FOR READING THE DOCUMENT:
- Go to the PDF Reading Board (full text) folder to refer to the full text of the essay in PDF format.
- Go to the Word Reading Board (full text) folder to refer to the full text in Word format.
- Go to the Resource folder to learn about the documents that were referenced during the author's graduation project.
- Go to the Source folder to learn about the documents of the author's graduation project.


USER GUIDE:
- Step 1: Prepare the Hardware
Connect the Sipeed Maixduino board and the ESP32 board Of the system to Laptop USB gate.
- Step 2: Install Arduino IDE and PIC C Compiler according to the software in the /Resource folder.
- Step 3: Upload the get_voice_model code to Maixduino board. after collected models, copy it to voice_model in the /Source/ to train for the system. 
Open Arduino IDE → upload the code from /Source/get_voice_model/ to the Maixduino board.
- Step 4: Upload the WEBSERVER code to ESP32 board (remember to change the Wifi's ID) to open the web interface of the system.
Open Arduino IDE → upload the code from /Source/WEBSERVER/ to the ESP32 board.
- Step 5: Upload the main code of the system to Maixduino board to running the whole system.
Open Arduino IDE → upload the code from /Source/Code/ to the Maixduino board.
- Step 6: Use trained commands to control the system through user voice.
ON/OFF servo and control fan speed from 0 - 100%.
- Step 7: The system's LCD LED display will display the received commands. 


REFERENCES:
[1] Alam, M. R., Reaz, M. B. I., & Ali, M. A. M. (2021). A review of smart homes Past, present, and future. IEEE Transactions on Systems, Man, and Cybernetics: Systems, 51(1), 119–133.
[2] Atzori, L., Iera, A., & Morabito, G. (2010).The internet of things: A survey. Computer Networks, 54(15), 2787–2805.
[3] Davis, S., & Mermelstein, P. (1980). Comparison of parametric representations for monosyllabic word recognition in continuously spoken sentences. IEEE Transactions on Acoustics, Speech, and Signal Processing, 28(4), 357–366.
[4] Espressif Systems. (2021). ESP32 Series Datasheet.
[5] Fielding, R., Gettys, J., Mogul, J., Frystyk, H., Masinter, L., Leach, P., & Berners-Lee, T. (1999). Hypertext Transfer Protocol — HTTP/1.1. IETF. RFC 2616.
[6] Fielding, R., & Reschke, J. (2014). Hypertext Transfer Protocol (HTTP/1.1): Semantics and Content. IETF. RFC 7231.
[7] Gubbi, J., Buyya, R., Marusic, S., & Palaniswami, M. (2013). Internet of Things (IoT): A vision, architectural elements, and future directions. Future Generation Computer Systems, 29(7), 1645–1660.
[8] Horowitz, P., & Hill, W. (2015). The Art of Electronics (3rd ed.). Cambridge University Press.
[9] Jordan, M. I., & Mitchell, T. M. (2015). Machine learning: Trends, perspectives, and prospects. Science, 349(6245), 255–260.
[10] Kendryte. (2019). Kendryte K210 Datasheet. Canaan Inc.
[11] Mermelstein, P. (1976). Distance measures for speech recognition, psychological and instrumental. Pattern Recognition and Artificial Intelligence, 116, 374–388.
[12] Müller, M. (2007). Dynamic Time Warping. In Information Retrieval for Music and Motion (pp. 69–84). Springer.
[13] OASIS. (2014). MQTT Version 3.1.1. OASIS Standard.
[14] Ogata, K. (2010). Modern Control Engineering (5th ed.). Prentice Hall.
[15] Oppenheim, A. V., & Schafer, R. W. (2009). Discrete-Time Signal Processing (3rd ed.). Pearson.
[16] Rabiner, L., & Schafer, R. (2011). Theory and Applications of Digital Speech Processing. Pearson.
[17] Sakoe, H., & Chiba, S. (1978). Dynamic programming algorithm optimization for spoken word recognition. IEEE Transactions on Acoustics, Speech, and Signal Processing, 26(1), 43–49.
[18] Salvador, S., & Chan, P. (2007). Toward accurate dynamic time warping in linear time and space. Intelligent Data Analysis, 11(5), 561–580.
[19] Sicari, S., Rizzardi, A., Grieco, L. A., & Coen-Porisini, A. (2015). Security, privacy and trust in Internet of Things: The road ahead. Computer Networks, 76, 146–164.
[20] Siciliano, B., Sciavicco, L., Villani, L., & Oriolo, G. (2009). Robotics: Modelling, Planning and Control. Springer.
[21] Sipeed Technology Co., Ltd. (2020). Maixduino User Manual.
[22] Smith, J., & Jones, A. (2021). Serial Communication Protocols in Embedded Systems. TechPress.
[23] Stallings, W. (2013). Data and Computer Communications (10th ed.). Pearson.
[24] Texas Instruments. (n.d.). LM2596 Simple Switcher® Regulator (Datasheet/Application note). Texas Instruments.
[25] Zhao, H., Li, M., & Guo, X. (2020). Development of a Voice-Controlled Smart Home System Based on ESP32 and Kendryte K210. International Journal of Smart Home Research, 8(1), 12–22.


CONTACT INFORMATION:
LUU PHUOC SANG
Phone number: 0825079971
Email: duyvt1023@gmail.com
I sincerely thank you!