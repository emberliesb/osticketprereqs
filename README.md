<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used</h2>

- Windows 10 (21H2)

<h2>List of Prerequisites</h2>

-A subscription in Microsoft Azure

<h2>Installation Steps</h2>

[Your installation Link Resources]

<a href="https://drive.google.com/drive/u/2/folders/1APMfNyfNzcxZC6EzdaNfdZsUwxWYChf6" rel="nofollow">https://drive.google.com/drive/u/2/folders/1APMfNyfNzcxZC6EzdaNfdZsUwxWYChf6</a>

<p>
<img src="https://camo.githubusercontent.com/6638fe24179160bdb20c0e2ce6f4cb12b86ff4e449b902d266df73ea519191c9/68747470733a2f2f692e696d6775722e636f6d2f6b4d70306a437a2e706e67" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lets head on over to <a href="https://portal.azure.com" rel="nofollow">https://portal.azure.com</a> to create you first subscription. After, you will begin to traverse to 'VIrtual Machines' and click on 'Create'
</p>
<br />

<p>
<img src="https://camo.githubusercontent.com/111b26b711152b95f35e1850eeedd0470ca4f12da71d160aaf09cff2a05c3cae/68747470733a2f2f692e696d6775722e636f6d2f434a30615978722e706e67" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Click on the first option, as you see from above. 
</p>
<br />

<p>
<img src="https://camo.githubusercontent.com/8e9e322cc7f89a2d5692bd28169dc1c888eed74a449591f0fc6baee6230f42df/68747470733a2f2f692e696d6775722e636f6d2f4e3755796350462e706e67" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Onto filling out the details.Leave the 'Resource Group' ield as it, it will automatically be created while you make your VM (Virtual Machine). Next, select whichever region you'd like. Select the 'Windows 10 Pro' as your Image.
</p>
<br />

<p>
<img src="https://camo.githubusercontent.com/b3210623c43a9d578af3ab31a8d34b016b878a2dcdd66c9166592f389b7c87cb/68747470733a2f2f692e696d6775722e636f6d2f744a41757344452e706e67" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next up, the 'Size' option is whatever to your liking, however, it does determine the speed and cost of your VM. (Recommended is 2 VCPU). Create your username and password you will be using to enter in your machine, make sure you write it down somewhere. Click 'Next' until you reach the 'Network' section.
</p>
<br />

<p>
<img src="https://camo.githubusercontent.com/569957a0932322ac7ce945521159ceacfcdfd58d5383a51aeca21a76eafba451/68747470733a2f2f692e696d6775722e636f6d2f7054314659414f2e706e67" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Ensure that you have a virtual network and a public IP address.
</p>
<br />

<p>
<img src="https://camo.githubusercontent.com/44e0c100cb1f090726d123f0ea6795120fce7b701851f519de519566a14f18e4/68747470733a2f2f692e696d6775722e636f6d2f517262756a7a432e706e67" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Click 'Create + Review', after it finishes processing proceed to click 'Create'
</p>
<br />

<p>
<img src="https://camo.githubusercontent.com/b6adbaf4094881fbe9c8c37e59ce58afe328e264ae5e4ca341b826d62a7ef9ee/68747470733a2f2f692e696d6775722e636f6d2f4b4958475a784d2e706e67" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Once done click 'Go To Resources'
</p>
<br />

<p>
<img src="https://camo.githubusercontent.com/e12902f4a9591cec7b91a3e07342ff0f2e4950c84467ff495c2dae93b287e2d1/68747470733a2f2f692e696d6775722e636f6d2f6b354c786c31632e706e67" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Click on the copy icon next to the Public Ip address, and then pull up Remote Desktop on your computer. (Window Users simply need to look up the application on Start) (Mac Users will need to download Microsoft RDP first)
</p>
<br />

<p>
<img src="https://camo.githubusercontent.com/7ff31e5670f1dfeab09566d5030289cdcbf1ff7b6f30ede1ec094ab8ed867971/68747470733a2f2f692e696d6775722e636f6d2f6d536a6a3057522e706e67" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Paste your Vms Public IP address.
</p>
<br />

<p>
<img src="https://camo.githubusercontent.com/0faef72850642a8fbe02da940a10e25c5518f622284e5db88a07b603a6d79d71/68747470733a2f2f692e696d6775722e636f6d2f713946465a78472e706e67" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After you have pasted the IP, click on 'Show Options'. When you've click 'Options' proceed on entering your username and password you made when creating the machine in Azure
</p>
<br />

<p>
<img src="https://camo.githubusercontent.com/a9c4eaa3f5678d505c407a10ebf26efc2b88bb7362ad808a21ef251dac159363/68747470733a2f2f692e696d6775722e636f6d2f477636775578432e706e67" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  Once you log in successfully, you will be on the home screen, follow the steps below

  <div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>Go to your Windows key and right-click the menu.
Click on 'Run' and then type in 'Control Panel'.
Click on 'Programs' and then select 'Turn Windows features on or off'.
Click the box next to 'Internet Information Services' and then click the '+' sign."
</code></pre><div class="zeroclipboard-container position-absolute right-0 top-0">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn js-clipboard-copy m-2 p-0 tooltipped-no-delay" data-copy-feedback="Copied!" data-tooltip-direction="w" value="Go to your Windows key and right-click the menu.
Click on 'Run' and then type in 'Control Panel'.
Click on 'Programs' and then select 'Turn Windows features on or off'.
Click the box next to 'Internet Information Services' and then click the '+' sign.&quot;" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon m-2">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success m-2 d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>

</p>
<br />

<p>
<img src="https://camo.githubusercontent.com/f5e5a406c682a8eb91239da638cde16a9bae980d90c54e94667660b4a57fe3a1/68747470733a2f2f692e696d6775722e636f6d2f6f417146536d412e706e67" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Select 'CGI' and then click 'Ok'.
</p>
<br />

<p>
<img src="https://camo.githubusercontent.com/6f7f90e42952ae0da8d1a74bbda6fa450efd328aafd1bea1b114b9df728b8084/68747470733a2f2f692e696d6775722e636f6d2f4c4b56526679352e706e67" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
<img src="https://camo.githubusercontent.com/97ac973df1624db1c61d90827f49c1d057dcc34a9dedd9457cf7d961d5bd7640/68747470733a2f2f692e696d6775722e636f6d2f787630554357772e706e67" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
"After installing IIS, create the directory C:\PHP. Then, after downloading PHP 7.3.8, right-click on the downloaded PHP file and click 'Extract All'. Next, click 'Browse' to find your PHP file, and then click 'Extract'."
</p>
<br />

<p>
<img src="https://camo.githubusercontent.com/02a3e8a9ac6742a1f570b93ba3744eee6ef311ed1c0bc4be652a93483287c151/68747470733a2f2f692e696d6775722e636f6d2f334d45704b7a672e706e67" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
"Next, download the VC_redist.x86.exe file. Afterwards, download MySQL 5.5.62 (mysql-5.5.62-win32.msi), and then apply these steps. Typical Setup -> Launch Configuration Wizard (after install) -> Standard Configuration -> Password1 "
</p>
<br />

<p>
<img src="https://camo.githubusercontent.com/9a449b412d66e9705e0d1e12627d4795eda6ed384634cc5cbaf7df9ed2ec77b0/68747470733a2f2f692e696d6775722e636f6d2f3430375147656d2e706e67" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Go to your Windows search, type in IIS, and open IIS as an adminstrator
</p>
<br />

<p>
<img src="https://camo.githubusercontent.com/c09fa18cb65057e5287961184d91722d5d5253404882663a4bae4b19d54c9757/68747470733a2f2f692e696d6775722e636f6d2f7349494b49736f2e706e67" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Once open, click on PHP manager
</p>
<br />

<p>
<img src="https://camo.githubusercontent.com/816e38a78145f8156c03be56a316596522ad5a246dae730b57f70c4c1579caf7/68747470733a2f2f692e696d6775722e636f6d2f5a4239397a58732e706e67" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now, once you open PHP Manager, go to Register PHP version, then click the three dots. Next, find your PHP folder and click on it. Inside, click on php.cgi. (Also, restart your IIS in the manage sever.)
</p>
<br />

<p>
<img src="https://camo.githubusercontent.com/942359c2ce3b019845f3983cee997e87cdc4d6549d8bee70db04191941053189/68747470733a2f2f692e696d6775722e636f6d2f4d704459566f382e706e67" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
"Install osTicket v1.15.8. Download osTicket from the Installation Files Folder. Extract and copy the "upload" folder to c:\inetpub\wwwroot. Within c:\inetpub\wwwroot, rename "upload" to "osTicket"." (Also, restart your IIS in the manage sever. After these steps)
</p>
<br />

<p>
<img src="https://camo.githubusercontent.com/3c74fab1cff40be6811627a1c7de47ddca83ed8f8721852bf6122adbd2efe184/68747470733a2f2f692e696d6775722e636f6d2f416632664153512e706e67" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Go to sites -> Default -> osTicket On the right, click “Browse *:80”
</p>
<br />

<p>
<img src="https://camo.githubusercontent.com/8aa8a1dde97b19f4567549730618369a2a7f4bd027abfd70c40eb59da17c4619/68747470733a2f2f692e696d6775722e636f6d2f756b53737848582e706e67" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
"After clicking on browser 80, a pop-up for osTicket should appear on your screen, Now you are halfway through the process.
</p>
<br />

<p>
<img src="https://camo.githubusercontent.com/c604a7032525992bc81891bdd18e05f3faf126b7862809de50e2a68365742bfc/68747470733a2f2f692e696d6775722e636f6d2f423069434470332e706e67" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
<img src="https://camo.githubusercontent.com/d0bdb5cfe595632a6985b5920f4e9b946539b9c629bc04d6510083a4fdb7af40/68747470733a2f2f692e696d6775722e636f6d2f6a4170486b39762e706e67" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Follow, The step provided on the picture above
</p>
<br />

<p>
<img src="https://camo.githubusercontent.com/3e37ca526ed42bafed09c548482d4bbdf7d9950676e206adc48437602ca228ed/68747470733a2f2f692e696d6775722e636f6d2f7075394644714a2e706e67" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Rename: ost-config.php 1.From: C:\inetpub\wwwroot\osTicket\include\ost-sampleconfig.php

2.To: C:\inetpub\wwwroot\osTicket\include\ost-config.php
</p>
<br />

<p>
<img src="https://camo.githubusercontent.com/b1ccb0a2cf49e47389008cfbc755d5444e4f700608d45794440e345a9c80bf18/68747470733a2f2f692e696d6775722e636f6d2f724438536e454d2e706e67" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
<img src="https://camo.githubusercontent.com/64feb406d8bf7a9436af753ee29cc098b6f68ce7510236377c1a82cc019e18fa/68747470733a2f2f692e696d6775722e636f6d2f706557465974792e706e67" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
<img src="https://camo.githubusercontent.com/7d39b02bb47cfed31ccc64ee4b652656c2ac2eecd1f0ce3b5122a0b36a70888f/68747470733a2f2f692e696d6775722e636f6d2f415361307a63582e706e67" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next, Assign Permissions: ost-config.php ( Right Click, Click properties, Click security) Disable inheritance -> Remove All New Permissions -> Everyone -> All
</p>
<br />

<p>
<img src="" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Continue Setting up osTicket in the browser (click Continue)
</p>
<br />

<p>
<img src="https://camo.githubusercontent.com/048fb25b7c964783a27e1d1e1b33a6b4c5824e2678c5be679ca3c6f719d5443a/68747470733a2f2f692e696d6775722e636f6d2f6f5872545356722e706e67" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
<img src="https://camo.githubusercontent.com/dca4e5677fc4c345b543767fd3c79bdf506a226387ee7a21a2ce0f1556db1a8c/68747470733a2f2f692e696d6775722e636f6d2f48726f564e78762e706e67" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Download HeidiSQL. ( Follow These Steps) 1.Open Heidi SQL 2.Create a new session, root/Password1 3.Connect to the session 4.Create a database called “osTicket
</p>
<br />

<p>
<img src="" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Continue Setting up osticket in the browser MySQL Database: osTicket, MySQL Username: root, MySQL Password: Password1, Click “Install Now!”
</p>
<br />

<p>
<img src="https://camo.githubusercontent.com/6cf983973016f0b69f0311fc4bdafb0a8c0a8f1c439dbfa672d5263212ef45d7/68747470733a2f2f692e696d6775722e636f6d2f716a654568766e2e706e67" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
It is very important to take care of the patient, the patient will be followed by the patient, but this time it will happen that there is a lot of work and pain. For to come to the smallest detail, no one should practice any kind of work unless he derives some benefit from it. Do not be angry with the pain in the rebuke, in the pleasure he wants to be a hair from the pain, let no one be born.
</p>
<br />

<p>
<img src="https://camo.githubusercontent.com/142ef48e7197bbb1e4426475adbb358f357a0524556f1369e8d3fbf5311ffc73/68747470733a2f2f692e696d6775722e636f6d2f32614b535564422e706e67" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
It is very important to take care of the patient, the patient will be followed by the patient, but this time it will happen that there is a lot of work and pain. For to come to the smallest detail, no one should practice any kind of work unless he derives some benefit from it. Do not be angry with the pain in the rebuke, in the pleasure he wants to be a hair from the pain, let no one be born.
</p>
<br />

<p>
<img src="https://camo.githubusercontent.com/3e135bc17f3fb5dbae915611e7731f1458086716c638c5ace61d2d8fc5ab370b/68747470733a2f2f692e696d6775722e636f6d2f507152396464712e706e67" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
It is very important to take care of the patient, the patient will be followed by the patient, but this time it will happen that there is a lot of work and pain. For to come to the smallest detail, no one should practice any kind of work unless he derives some benefit from it. Do not be angry with the pain in the rebuke, in the pleasure he wants to be a hair from the pain, let no one be born.
</p>
<br />

<p>
<img src="https://camo.githubusercontent.com/4c9db5fe512be9ba350f591b54a0b12581839ac9620102b420242bef467acdb9/68747470733a2f2f692e696d6775722e636f6d2f5a6769676a76642e706e67" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
It is very important to take care of the patient, the patient will be followed by the patient, but this time it will happen that there is a lot of work and pain. For to come to the smallest detail, no one should practice any kind of work unless he derives some benefit from it. Do not be angry with the pain in the rebuke, in the pleasure he wants to be a hair from the pain, let no one be born.
</p>
<br />
