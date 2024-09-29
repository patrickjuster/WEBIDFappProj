<h1>AWS WEBIDF App</h1>

<h2>Description</h2>
The purpose of this project is to build a WEBIDF App that uses Cognito and IAM to utilize a Google Token for AWS credentials inside a browser app.
<br />
<br />
<br />
Assumptions I had going into this project are that it was going to be much more complex. WEBIDF authentification is my prefferred method of autentification for sites that enable it -- its just more convinenient being able to use one account and sign-on compared to making dozens of accounts and losing track of them. When I recently created a LinkedIn account, I used Google authentification to signup without the hassle of filling and creating another account. This is why I consider this project to be valuable as its a function that is used everyday by the average person -- enabling me to better understand from a customer/user perspective.
<br />
<br />
Reference: This project is based on Adrian Cantrill's mini-project:  (https://www.youtube.com/watch?v=DyiJZz07g_E&list=WL&index=3)
<br />
<br />
<h2>Arhitecture Example</h2>
<img src="https://i.imgur.com/Td6mfju.png"/>
<br />
<br />

<h2>AWS Services & Features Used</h2>

- <b>AWS Cognito</b>
- <b>S3<b>
- <b>Google WEBIDF</b>
- <b>CloudFormation<b>
- <b>IAM roles<b>


<h2>Project walk-through:</h2>
<br />
<br />
<p align="center">
CloudFront Distribution: <br/>
<img src="https://i.imgur.com/3LAuwBW.png"/>
<br />
<br />
<br /> 
Google API & Client ID:  <br/>
<img src="https://i.imgur.com/mZR4Moe.png"/>
<img src="https://i.imgur.com/01POYGu.png"/>
<img src="https://i.imgur.com/63AWyYk.png"/>
<img src="https://i.imgur.com/OcUV50m.png"/>
<br />
<br />
<br />
Create Cognito Identity Pool: <br/>
<img src="https://i.imgur.com/5glGY7n.png"/>
<img src="https://i.imgur.com/c73BbDG.png"/>
<img src="https://i.imgur.com/I0MlMae.png"/>
<img src="https://i.imgur.com/K8YHkzd.png"/>
<img src="https://i.imgur.com/FRBiOvS.png"/>
<br />
<br />
<br /> 
Update App Bucket & Test App:  <br/>
<img src="https://i.imgur.com/RYKfSlx.png"/>
<img src="https://i.imgur.com/wYvzSDU.png"/>
<img src="https://i.imgur.com/ty2fZQr.png"/>
<img src="https://i.imgur.com/SkxrI9F.png"/>
<img src="https://i.imgur.com/iGhJGVQ.png"/>
<img src="https://i.imgur.com/MISlmiu.png"/>
<img src="https://i.imgur.com/IEXuI5O.png"/>
<img src="https://i.imgur.com/RyxlwQS.png"/>
<img src="https://i.imgur.com/qP8yQJe.png"/>
<br />
<br />
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
