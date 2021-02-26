# Contact info

- Mobile：18502108924
- Email：huangjuecheng@163.com
- Wechat：18502108924

---

# Personal info.

 - Juecheng Huang/male/1982
 - Bachelor/Beijing Jiaotong University(BJTU)-EE(school)-Automation(Major)
 - Work Experience: >10 years
---

# Self introduction

- More than ten years of software development experience in the mobile phone industry
- Familiar with the working principle of android development platform and android security mechanism
- Familiar with 3GPP call protocol and various mobile phone development languages
- Have a certain understanding of artificial intelligence neural networks, CNN, RNN
- Have good teamwork and management skills
- The research on new technologies has always maintained sufficient enthusiasm
Steady, responsible for work, proactively help other colleagues to solve technical problems

---

# Work Experience

## KaiOS 2018.12~now

focus on customer support for KaiOS communication related APPs:
- Telephony related APPs(callscreen, contact, call log, stk) business (field test, agreement consistency, operator network access test related), etc...
- gaia upper-level application refactoring-optimize startup speed, add unit test
- Responsible for some management work of the FE team as a technical leader
 
## UNISOC 2011.2~2018.12

>Description: Android Telephony&Fingerprint development and as an FAE for customers.

|  period   | work summary  |
|  :----  | :----  |
|  2011.04~2016.10 Telepony-SH Team |   Upgrade Android version for telephony module- Develop some SPRD' features and customers' request;  Take in chager of these modules(Call. SIM. STK) |
|  2016.10~2018.12 APP-Security Team |  Form 2016.10 to now my job change into Security Team and focus on Fingerprint module: Develop some new features for FP and reslove some FP' issues from customers. Guide customers finish to develop TA in TEE(Trusty).Develop fingerprint'payment(SOTER) in platform. As an owner of fingerprint module with customers|


##  Beijing Samsung communication research (BST) 2007.8 ~ 2011.2
>Description:	
Development and support of applications in the Chinese market (including support for local network issues in Hong Kong and Taiwan)

|  period   | work summary |
|  ----  | :----     |
| 2007.09~2010.03 Telephony-Symbian  | Symbian mobile APP development, in charge of Telephony module, trouble-shooting for Application , Support to launch Symbian mobile into marketing in China, make some analysis report about mobile application from customer and send it to Korea headquarters. I went to Korea twice. One is for Symbian skills training. aslo is a big team building with Korean engineers together. It is very useful for further work and communications together. Another is that porting “Samsung handwriting input method” to Symbian mobile with Korean engineers in two months. |
| 2010.03~2011.04 Android APP/Phone  | Mainly responsibility is that Supporting localization Android solutions from Korean or European/American markets. Also need to resolve some issue from CMCC test or CMT(SAMSUNG)for Android mobile and make a suggestion how to modify the APP can better for Customer in China marketing. And for the new received APK we need create test cases and make an analysis report for every functional model according to testing and modify some source code. That is very important work to launch a new APP into China marketing more quickly and effectively. |

##  TechFaith Wireless 2005.7~2007.8
>Description: 
- In charge of coding for some new features which clients provided and debugging in some modules（phonebook&STK）.
- Completed the optimization of the Phonebook module code at the MMI layer, mainly encapsulating all common interface functions, greatly reducing the amount of code modification of the new project, thereby reducing the workload of bugs and later maintenance; 
- responsible for the design and design of the SSME(philip platform) side (module STK) of the dual-card project Development, the main work is to analyze AT commands and ensure the normal operation of basic functions

---

# Project experience

## Message-net(KaiOS)
```
Project Description: Realize 5G SMS function, including itinerary code, official account, etc.

Responsibility description: Use React to rewrite the message application, and use web idl to implement the corresponding interface
```
## Orange Operation(KaiOS)
```
Project description: The call interface obtains the number type (such as emergency number, suspected fraud, merchant information, etc.) by accessing the server according to the number, and displays the corresponding information on the interface

Responsibility description: Responsible for the evaluation of the overall project, the development part is responsible for the coding of the callscreen interface
```

## AI Trainning (SJTU)
```
period: 2018/8~2018/8(7days)

Project description: understand new technologies and applications of artificial intelligence, familiar with machine learning, artificial neural networks, and deep learning

Responsibility description: Each group submits its own projects and applications, and is guided by a dedicated teacher. The project is [Traffic monitoring uses deep neural networks to accurately identify pedestrians] The main function is to use CNN to train a model to recognize people, and then use image algorithm calculations Find out whether there is any illegal or threat to safe driving behavior, such as running a red light or entering a steering shift area. This solution can guide the vehicle in real time or deal with it urgently, which greatly improves safe driving.
```
## WW 9863 Fingerprint development(UNISOC)
```
Description:	To develop the fingerprint function to customer's resolution with FP vendor

Responsibility:	To guard the FP vendor how to develop CA and TA, In CA side main job is how to implement the interface provided by Android original functions for fingerprint and in TA side we need to guide the vendor how to use some interface from UNiSOC' TEE, such as the IPC between CA and TA, SPI interface and Storage interface, the function of get random, the HMAC function, get auth token key function and Selinux policy config and so on.
```

## SOTER(UNISOC)
```
Description:	To develop the SOTER in UNISOC' software platform according to the documents provided by Tencent
Responsibility:	To develop the function for encryption and decryption using OPENSSL lib and the following keys:
1. ATTK // device verification key
2. ASK // to verify the application
3. Authkey // to verify one business logic
Tips: the operation of keys must in TEE

```

## A incoming call processing method, device and terminal -patent(UNISOC)
```
Patent application number: 2017108275627

Abstract: The present invention provides an incoming call processing method, device and terminal. The method includes: receiving fingerprint information input by the user when the terminal calls; matching the caller number with the caller whitelist or caller blacklist corresponding to the fingerprint information; and selecting to answer the call or reject the call according to the matching result. The invention dynamically enables the black and white list through fingerprint authentication, filters the black and white list of the incoming call number, realizes the answer or rejection of the incoming call, and can prevent the numbers in the black list and the white list at the same time from conflicting when the call comes in.

```

## Application-Lock (UNISOC)
```
Description:	Add the fire wall for any application in handset, when the function is activate, you must input password/pattern or fingerprint and then enter to the application. The function protect user information and private data.

Responsibility:	Responsible for the development of the whole function: 1. Related to the development of Android interface layout, application list interface and unlock interface, in the unlock interface and related to the layout of the screen 2. It involves interacting with the cell phone Keyguard module, typing the number of errors and the number of times the phone's own password needs to be unified 3. The key point of this feature is how to start the Unlock interface when setting the application lock-primarily by using the changes in the foreground activity to determine whether the current application needs to apply the lock function
```

## HUAWEI PAD in Wuhan(UNISOC)
```
Description:	Onsite support on telephony-stk

Responsibility:	Telephony-STK Module Onsite support:
1. 3GPP Test specification function implementation, mainly involves the STK message exception processing or the message escalation format
2. Machine card compatibility test, there are a large number of different national operators in the lab Sim, some of which are not strictly in accordance with the requirements of the 3GPP specification, we need to do some compatible phone-side processing

```
## WingTech Y360(UNISOC)
```
Description:	onsite support in telephony

Responsible for the functional development of all telephony modules in the field: 
different countries or operators of customized requirements: such as number matching digits, the virtual operator to judge (different SIM card judged by the same criteria: IMSI,EF_GID,EF_SPN), Current PLMN and SPN display (mobile phone standby interface Ali Network/China Mobile), SMS center number, emergency call number (with cards, no cards, cards and card priority or network priority), and when to load the above configuration file and so on.

```

## Mexico TELCEL(UNISOC)
```
Description:	Stk-bip function Support, Google native code does not support the implementation of the BIP protocol inside the need for each vendor to achieve their own, and Mexican operators Telcel must have to this function otherwise can not get the certificate

Responsibility:	The BIP protocol mainly contains the following commands:
1. Open Channel
2. Send Data
3. Receive Data
4. Close Channel
5. Event Download
6. Data available
Above commands need to be implemented in accordance with the 3GPP protocol requirements, the main functions are implemented on the Java side, and other reference schemes implement most of the functions in Ril
```

## DUAL-SIM(UNISOC)
```
Description:	Google native code only single SIM function, in response to the needs of the customer dual card, in the exhibition platform to achieve dual-sim function

Responsibility:	Responsible for the RIL part of the dual-card implementation, in the original rild based on the addition of demon process rild1, the upper layer through the Phoneid to select the Rild1,phoneid to 0 when the use of the default Rild can be, the upper layer only need to add Phoneid in the appropriate location of the assignment can be Responsible for completing the design of the upper dial interface, displaying two dialing icons when the phone is plugged into two SIM cards, and displaying the name of the current SIM card on the icon, which can be defined by itself or by default display the SPN name in the SIM card file (for example: China Mobile/China Unicom)
```

## Engineering mode(UNISOC)
```
Description:	The first TD mobile phone for Spreadtrum, need to refer to feature phone to achieve the project mode function, mainly through the combination into the project mode interface, in the engineering mode can operate the modem-related functions

Responsibility:	Responsible for the development of the engineering model needs to refer to the feature phone to achieve the project mode function, mainly through the combination into the project mode interface, in the engineering mode can operate modern functions, such as: Set the current PLMN for lock network function, call automatic answer for automated testing, Read and set the UPLMN list on the SIM (you need to refer to the 3GPP protocol to resolve files read from the SIM), and some special features that are not visible to end users
```
## VIP (TechFaith)
```
Description:	VIP group and Anti-theft tracking function

Responsibility:	
Responsible for the development of the whole project telephone module: 
1. The content has the VIP group function, when the user opens this function only then I can see the contact person under this VIP group
2. In this contact person caller can display the custom call name to prevent the information leakage  
3. when active the anti-theft function, When the user replaces the SIM, the system automatically sends a message to the set phone number. You can also send the missing number to the owner by name or group in a fixed format, while sending a custom message to the stolen phone to keep the stolen phone from restarting for unusable purposes.
```

---

# Education

##  2001/9-2005/7	Beijing Jiaotong University | Bachelor| Automation

Major:
-Computer culture foundation (principle), communication technology foundation, signal and system, digital signal processing
-Analog integrated circuit, digital electronic technology, detection technology, microcomputer principle and interface technology, computer control technology, automatic control principle
-Single-chip microcomputer principle and interface technology, EDA electronic design technology, electronic measurement, Auto CAD
-C, C++, JAVA

# Programming language

- Java(Android)
- Javascript
- C/C++

---

# Thanks
Thank you for taking your precious time to read my resume, and I look forward to having the opportunity to work with you kindly.
