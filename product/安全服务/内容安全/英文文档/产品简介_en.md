## What is Antispam?
Antispam is a security service provided by Tencent Cloud for filtering the illegal and harmful information of websites and Apps, including two sub-services — text recognition and image recognition. With Antispam, customers can be free from large-scale manual recognitions, and improve the recognition efficiency, purify the network environment, enhance the product experience and protect the healthy development of businesses, while minimizing the cost.

## Text Recognition
## Product Overview
With the vigorous development of Internet, users generate massive amounts of text contents, which inevitably include some spam texts. These spam texts may not only impact user experience, but also violate laws and regulations, and can even lead to website shutdown. Most of these spam texts are made by the professional practitioners in the black industry of Internet. In order to prevent customers from being distracted and restrained by the spam contents and to help them get liberated from the complicated confrontation with the black industry, BSP launched the text recognition service.
The text recognition service is suitable for website and App contents, including message posting, remarks, on-screen comment, chatting, etc. It can accurately identify the malicious texts and images, such as illegal contents, spam advertisements, malicious marketing contents, and can effectively minimize various types of illegal advertisements and pornographic or vulgar contents.

### Product Features
#### Anti-interference
To circumvent the blow of product security policy, the practitioners in underground industry often use symbols, icons, phonetic transcription, foreign languages and other methods to interfere with texts. It becomes difficult for the traditional text mining technology to effectively identify the "Psoriasis" advertisements in businesses. As an innovation, the anti-interference engine developed by BSP can convert the symbols, icons and other interferences in the contents and restore the original text contents through text preprocessing and OCR recognition, thus easily seeing through the "camouflage" of practitioners in underground industry.
#### Dirty Word Database
In addition to the original text restoration feature, BSP provides the fastest and most comprehensive dirty word scanning technology. Based on the most complete dirty word database in the industry accumulated by Tencent Ecology and the multi-Tree model matching technology, BSP text recognition service can provide the fastest, most comprehensive identification of malicious texts and advertising contents. The BSP dirty word database contains more than 30 categories and hundreds of thousands of keywords, ranging from the pornography, gambling to the unlocking, tea and other advertisements.
#### Underground Industry Characteristics
The BSP text recognition service has extracted three underground industry behavior characteristic models based on Tencent's years of experience in fighting against underground industry as well as characteristic collecting and intelligent learning. No matter what interference methods the malicious users continue to create, the characteristic fingerprint model of BSP can identify them.
- Device fingerprint database: BSP's massive underground industry database. It collects fingerprint information of PC, mobile phone, network and other devices from malicious users, so as to identify suspicious users on the device level, thus making it more difficult for users to conduct malicious operations.
- Text characteristics: BSP's textual characteristics mainly include profitability, redirection, noise and so on. Based on these textual characteristics and BSP text-mining capability, the text recognition service can detect suspicious contents. In addition to redirection, noise and other intuitive characteristics, BSP uses LDA to automatically explore more characteristics.
- Image redirection recognition: As a high-level confrontational behavior, image redirection is often used by the practitioners in underground industry. Now, the BSP text recognition API has integrated the OCR image recognition capability which has been used in QQ/Qzone and other Tencent products for many years and can effectively recognize advertising and pornographic images.
#### Risk Level
The BSP text recognition service supports three risk levels of user contents, i.e. malicious, suspicious and credible. It is recommended to adopt different policies for different risk levels.
- Credible: Operate the business normally.
- Suspicious: It is recommended to restrain such contents based on the user's behavioral characteristics, such as IP aggregation, content sent frequently.
- Malicious: It is recommended to directly restrain the business of this user.
#### Risk Notification
If the contents generated by users are found to be of the malicious risk level, the BSP text recognition service will explicitly inform the user of the malicious contents, including the hit keywords and categories.

### Product Advantages

| Advantage | Description |
|---------|---------|
| High Technology | Hundreds of thousands of keywords, powerful anti-interference noise filtration technology and interference reduction techniques, LDA document theme characteristics extracting techniques and other text-level recognition techniques, together with URL recognition, porn detection and image OCR technology, ensures a relatively high malicious text recognition rate, even without IPs, mobile numbers and other auxiliary information. |
| Extensive Data | Through user reporting and other means, Tencent has accumulated massive underground industry databases based on years of data, such as malicious IP/mobile phone/QQ/WeChat database. Even if the IP, mobile number or QQ is changed, the malicious contents cannot escape from the tight encirclement set by the BSP text recognition service. |
| Multiple Dimensions | From mobile number, email, QQ, WeChat account and other dimensions, BSP accurately determines the levels of underground industry accounts and crack down on malicious advertising behaviors in depth. |
| Low Cost | A minimum of 0.3 CNY for 100 queries. Low cost to fight against malicious risks. |
| Fast | The advanced architecture of Tencent Cloud, the millisecond-level service response, and 10k-level concurrency per second, together with dynamic expansion, relieve your worries about the performance loss. |
| Convenient | Without installing any script files, you can use it directly via APIs in three steps. Non-Tencent Cloud customers can use it as well. |
| Accurate | With the malicious content recognition rate of more than 95%, the text recognition service has been used by both the largest city website and the earliest community website in China, and successfully blocked a large number of malicious advertisements. |


### Image Recognition
## Product Overview
Relying on the in-depth porn detection technology of Tencent YouTu, the BSP image recognition service can efficiently and accurately identify the pornographic and sexy images, thus solving the porn detection problem encountered by website and APP developers. Customers can be free from large-scale manual porn detections, improve the porn detection efficiency, and purify the network environment, while minimizing the cost.

### Product Features
#### Porn Detection
The BSP image recognition service automatically downloads images from the address provided by the developers and performs the porn detection, and then returns a confidence score to the customer. Any images with a score of more than 83 points are judged as the suspicious images, and developers can track and analyze the behaviors of the corresponding users.

#### Sexuality Identification
The BSP image recognition service performs sexuality identification for the images provided by developers for free. For any images with a score of more than 83 points, developers can track and analyze the behaviors of the corresponding users.

#### Automatic Porn Detection
The BSP image recognition service uses Tencent YouTu's DeepEye active porn recognition engine to analyze the porn confidence of the images, and carries out in-depth recognition training based on Tencent Social's massive image samples. The accuracy rate of recognition algorithm reaches 99.9% and above, and is higher than that of the artificial recognition. With this service, 90% manpower in the actual work can be saved. Besides, for the definition of pornography and sexuality, the most complex problem in the automatic image recognition field, the porn detection engine can accurately distinguish pornography and sexuality by using the map separation technology.

### Product Advantages

| Advantage | Description |
|---------|---------|
| Accurate | The accuracy rate of automatic porn detection is more than 99%, so it can accurately distinguish the normal, pornographic, and sexy images, thus facilitating the business development. |
| Manpower Saving | The image recognition service has been used by multiple LVB platforms for automatic porn detection, and reduced up to 90% of manpower review for them. |
| Confidence Score | The image recognition service provides confidence scores to help you accurately distinguish the normal, pornographic and sexy images, therefore facilitating the healthy business development. |
| Low Cost | A minimum of 0.1 CNY for 100 queries. Low cost to fight against pornographic risks. |
| Fast | The advanced architecture of Tencent Cloud, the millisecond-level service response, and 10k-level concurrency per second, together with dynamic expansion, relieve your worries about the performance loss. |
| Convenient | Without installing any script files, you can use it directly via APIs in three steps. Non-Tencent Cloud customers can use it as well. |

## Application Scenarios
### Community Forums
Antispam can be widely applied to BBSs, blogs, and other websites containing UGCs, including message posting, message replying, internal messaging, etc. It uses the intelligent anti-spam technology to detect the pornographic, advertising, spamming, abusing and other spam texts in real time.

### Porn Detection for LVB
BSP and Tencent Video Cloud provide LVB customers with a solution for video screenshot, storage, and automatic image recognition. You only need to deploy the LVB services on the Tencent Cloud, then you can activate the automatic porn detection service quickly.
Taking the LVB industry for example, with the BSP image recognition service deployed, the LVB contents of VJs will go into the environment deployed by Tencent Cloud's video porn detection service before being presented to viewers. In other words, BSP can perform the image recognition for video screenshots during the live broadcasting, making the screenshots, discovering, and notifying the callback business processing in real time. Besides, it can adjust the screenshot detection frequency for different rooms in different time ranges, so as to monitor the key rooms.

### IM
The content recognition service can perform the targeted detection and recognition for the spam contents hidden in nicknames, profile photos, signatures, C2C messages, group messages and more, to prevent the harassment from malicious users as well as the risky frauds.

