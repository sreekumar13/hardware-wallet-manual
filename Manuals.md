# Checking the Genuineness of your Skywallet

## Checking your Skywallet Package for Tampering

Once you receive the Skywallet shipment, please check for any physical tampering or damage to the package of any sort.

Tampering or damage can be anything from a small tear on the package to a package that is torn open.

**Do not accept a shipment which seems to be damaged in any such way.**

### An Untampered Shipment:

<A Picture of an untampered shipment before opening>

Please ensure that the holographic sticker with the Skycoin logo on the Skywallet box is not broken.
<A Picture of the unbroken holographic seal on the box>

## Checking the Firmware

The Skywallet is built to provide maximum security to the user.

However, it is vital to check that your Skywallet is not compromised before using it.

## Step 1 - Connecting Your Skywallet

First, connect the Skywallet to your USB port.

## Step 2 - Checking the message on your Skywallet's Display

The display on your Skywallet shows one of the following three messages when connected via USB port, marking the authenticity of your Skywallet.

### Scenario 1:

If the Skywallet is a genuine one and is being used for the first time, then the screen will display the following message:

**Welcome!**

**Please visit skycoin.net** 

Along with the Skycoin Logo.

<A photo of the Hardware Wallet displaying the welcome message>

A Skywallet that is being used for the first time will not have a firmware installed.

The firmware is the software interface which helps the hardware to interact with both the user as well as a computer. Thus without a firmware, your Skywallet will not work correctly.

Any message apart from this welcome message implies that your Skywallet has been tampered with by a third party. Thus if you get any message apart from the welcome message, proceed to disconnect the device and contact support immediately.

### Scenario 2:

A previously used Skywallet may have a firmware initialized, and if it has, then it might mean that it has been manipulated. Such a Skywallet will display the following message on its display screen:

**Need Seed!**

Along with the Skycoin Logo.

<A picture of the Hardware Wallet which displays the message NEED SEED>

If you get a "Need Seed!" message on your first use, it means that your Skywallet is not a new one and has a firmware already initialized.

**Note - If you do get a Need Seed! message on your first use of the Skywallet, refrain from using the device.**

For further assistance, **Please contact the support team immediately.**

You can use the following link to contact support: **[Support Page](store.skycoin.net/pages/support)**

Alternatively, you can detail your concerns and send an email to **support@skycoin.zendesk.com**

### Scenario 3:

The third and final message that might be displayed is a warning:

**Unofficial Firmware Detected**

such a message denote that the Skywallet is running on a firmware that is not approved by Skycoin. 

Do **not** use a Skywallet displaying that warning as the software version on your Skywallet might be corrupted, and it is ***unsafe*** to use the Skywallet, as using the said Skywallet could potentially make you lose your coins.

<A picture showing the message Unofficial firmware detected>
  
**Please note that if you get an Unofficial Firmware Detected message on your Skywallet then immediately disconnect the device and contact the Skycoin support.**

You can use the following link to the **[Support page](store.skycoin.net/pages/support)**.

Alternatively, you can detail your concerns and send an email to **support@skycoin.zendesk.com**

# Initializing your Skywallet

After successfully checking that your Skywallet is genuine, you can begin with the initialization of your Skywallet.

## Step 1:

The first step in initializing your Skywallet is to install the Skycoin Desktop Wallet.

Please make sure to download the latest compatible version from the Skycoin [Downloads](https://www.skycoin.net/downloads/) Page.

If you already have the latest Desktop Wallet installed and configured, then you can skip this step.

## Step 2:

The next step is to download and install the daemon.

Following are the steps to install the daemon in different operating systems:

### Windows

* Download the daemon from the following link - []()

* You have to run the daemon every time you want to use the Skywallet.

### macOS

* Download the .pkg file from the following link - []()

* Double Click on the downloaded file and follow the instructions in the installer.

* Once completed, the daemon runs in the background, so you do not have to start it manually.

### Linux

* Open terminal on your Linux machine.

* Execute the following command using the terminal:  
*run wget -O /tmp/skyhwd.deb https://downloads.skycoin.net/skywallet-daemon/skyhwd_0.1.0_amd64.deb*

* After the process is complete execute the following command:  
*run dpkg -i /tmp/skyhwd.deb*

* Once completed, the daemon will run in the background.

## Step 3:

Connect your Skywallet to the USB port.

## Step 4:

Once you have connected the Skywallet to the USB port, open the Skycoin Desktop Wallet.

If it is the first time you are using your Skywallet, please make sure to go through the following section of the user manual,(Checking the Genuineness of your Skywallet)[https://github.com/skycoin/hardware-wallet/wiki/How-to-check-whether-device-is-genuine], to ensure that you are using a genuine Skywallet.

The instructions for a Desktop Wallet which is used for the first time and an already configured Desktop Wallet are different.

### Step 4.1: First Time Use of a Desktop Wallet

If you are using the Desktop Wallet for the first time, you will see the following screen :

<Screenshot of a Desktop Wallet which is used for the first time>

To configure your Skywallet, proceed to click on **“Using a hardware wallet?”** button.

<can be removed> <Screenshot of a Desktop Wallet highlighting Using a hardware wallet button>

Upon pressing the “Using a hardware wallet?” button, the display screen on your Skywallet will show a welcome message:

<Reusing the Picture showing the Skywallet display with the welcome message>

To configure your Skywallet for the first time, you have to install the firmware for the Skywallet, as explained in [step #4](#Step_4).

### Step 4.2: Previously Configured Desktop Wallet

If you are **not** using your Desktop Wallet for the first time, then on connecting the Skywallet via USB, the following window will be displayed.

<Screenshot of a previously configured Desktop Wallet with other Wallets as well>

The window will display a list of all the Wallets that are already configured in your Desktop Wallet. (*Note - This may include both Hardware and Software Wallets*)

To configure your Skywallet click on the **“Hardware Wallet”** button.

<can be removed> <Screenshot highlighting the Hardware Wallet button along with the context>

On pressing “Hardware Wallet” button, the display screen on the Skywallet will show a welcome message:

<Reusing the Picture showing the Skywallet display with the welcome message>

Once the welcome message is displayed on the Skywallet screen, you can proceed to install the firmware.

## Step 5: Installing the Firmware

To indicate the beginning of the firmware installation, the Desktop Wallet will show the following window:

<Screenshot of the Desktop Wallet showing the message about the installation of the firmware>

You can click on continue to start installing the firmware for your Skywallet.

The installation process will take a few seconds to complete. 

Once the installation is complete, you can proceed to configure the Skywallet.

**Note - If the installation process gets abruptly terminated for any reasons, you can disconnect the Skywallet, close the Desktop Wallet and then restart the whole process from the start.**

## Step 6: Skywallet Configuration

Once the firmware installation is complete, the “NEEDS SEED!” message is displayed by the Skywallet.

<can be removed> <Reusing the picture of the Skywallet display showing the message Needs seed>

Simultaneously, the following window will be displayed by the Desktop Wallet.

<Screenshot of Desktop Wallet displaying the message of detecting an unconfigured Hardware Wallet>

In this window, you can select two options :

**“Configure automatically”**

**"Restore backup"**

### Step 6.1: Configure automatically

If you are using a Skywallet for the **first** time, then you can proceed with the option of “Configure Automatically”.

“Configure automatically” button will configure your Skywallet as a new one.

Once the configuration is complete, the following window will be displayed.

<Screenshot of the configuration process completion>

You can use this window to change the name of your Skywallet. After which you can click on the “Close” button to close the window.

<Screenshot of a changed Skywallet name>

### Step 6.2: Restore backup

If you have already made a backup of a previously used Skywallet and need to restore it on the new Skywallet, then you can opt for the Restore Backup option.

The restoration process is explained in detail in this section - [Restore Configuration](https://github.com/skycoin/hardware-wallet/wiki/Restore-configuration)

If the Skywallet is **not** connected or not detected by your computer, then the following error message will be displayed:

<Screenshot of the error message showing no Skywallet detected>

# Personalizing your Skywallet

After completing the initialization of your Skywallet, you can start to personalize your Skywallet using the Desktop Wallet.

Upon configuring your Skywallet, it will be listed in the Wallet list. The list can be viewed when you open your Desktop Wallet.

<can be removed> <Screenshot of the list of Wallets displayed when the Desktop Wallet is opened. One of the Wallets in the list needs to be a Skywallet>

To personalize your Skywallet, connect your Skywallet via USB to your computer and then open the Desktop Wallet.

Once the Desktop Wallet is opened, click on the **Hardware Wallet** button in the Desktop Wallet window.

<can be removed> <Screenshot of the Desktop Wallet highlighting the Hardware Wallet button>

Once you click on the "Hardware Wallet" button, the following window will appear:

![Hardware Wallet Window](https://github.com/sreekumar13/hardware-wallet-manual/blob/master/Personalization%20-%201.PNG)

When you use the Skywallet for the first time, you will find two warnings associated with **Creating a Backup** and **Setting a Pin**, displayed in the Desktop Wallet window.

Both of these warnings are to be dealt with seriously, or it may compromise the security of your Skywallet.

To complete these two tasks, you can use the options in the Hardware Wallet window.

Following are the options available in this window:

**Create a backup**

**Create PIN code**

**Wipe the device**

## Create a backup

The Seed of your Skywallet is a key component. A Seed is the only way to access the coins stored in your Skywallet. 

Once the initialization is complete, it is essential to backup this Seed and store it in a secure location.

To backup the Seed of your Skywallet, click on the button **"Create a backup"**.

<can be removed> <Screenshot of the Hardware Wallet window with an arrow pointing towards the create a backup button or highlighting the button>

Once you click the "Create a backup" button, a warning message will be displayed.

After accepting this warning message, the Skywallet will start to display the words in your Seed one by one.
<Picture of the Skywallet display screen showing different words in the Seed> <at least two pictures needed>

**You need to note down each of these words and store it in a secure location.**

**You would have obtained a Seed card along with your Skywallet, we recommend you to use this Seed card to note down your Seed.** 

**Note - Make sure that it is retrievable because if anything happens to your device, it will be impossible to retrieve your coins without the Seed.**

After completing the display of the words in the Seed, the screen displays ***all the words in the Seed again***, so that you can verify your entries.

**Note - After completing the Backup process, you cannot repeat the same. Hence it is essential to note the Seed down during this process. Once you have completed the backup process, the "Create a backup" button will be replaced by "Confirm Seed" button.**

To ensure optimal security, please make sure to go through this section of the user manual - [Optimize account security](https://github.com/skycoin/hardware-wallet/wiki/Optimize-account-security)

## Create  PIN code

Creating a PIN code for your Skywallet enhances its security, as only a person with the PIN can access the device. 

To create a PIN for your Skywallet for the first time, click on the button - **Create PIN code**

Once you click on the button "Create PIN code" the following window will appear on the Desktop Wallet:

![Keypad to enter the PIN code](https://github.com/sreekumar13/hardware-wallet-manual/blob/master/Personalization%20-%202.PNG)

<it is mentioned in the wiki page that the hash symbol which is currently used to mask the numbers in the keypad will be changed to dot if so then the latest version screenshot will be needed>

Simultaneously a number Matrix will be displayed on your Skywallet display screen.

<Picture of the Skywallet showing the number matrix>

To set the PIN, you have to use both the matrix as well as the Desktop Wallet window.

**Each position of the number in the matrix corresponds to its position in the keypad shown by the Desktop Wallet window.**

<A side by side picture of the two pictures mentioned above>

<An explanation of this side by side picture>
<The explanation can also be an edited image showing the correct position of the numbers in the masked keypad of the Desktop Wallet window>

Alternatively, you can utilize the number keypad on your computer for entering the PIN. 

However, if you are using the number pad then note that **the position of the number in the matrix is what decides which number you are entering.**

<Reusing the picture of the matrix>

<An example comment using a single number on the position of the number keypad and the position of number in the matrix>

***Note - While setting up your PIN you have to enter it twice.***

After setting up your PIN, you can manage the PIN by changing or deleting the same. 

**Changing the PIN code**

Once you have created a PIN code, you can make modifications to your PIN code using the Hardware Wallet window.

You can use the **Change PIN Code** option to change your current PIN code to a new one.

Upon clicking the "Change PIN Code" button, the Hardware Wallet window will show you a keypad similar to the one you used to create the PIN code.

<Picture of the Hardware wallet showing the number matrix>
  
![Keypad to enter the PIN code](https://github.com/sreekumar13/hardware-wallet-manual/blob/master/Personalization%20-%202.PNG)

You can enter the PIN code by utilizing the number matrix displayed by the Skywallet in the same way you used it for creating the PIN code.

To change the PIN code, you have to enter the current PIN code first and then the new PIN code twice. 

**Deleting the PIN code**

Ideally, a Skywallet should always have a PIN code, and it is a recommended precaution to improve the security of your Skywallet.

However, you can choose to delete the PIN code of your Skywallet using the Hardware Wallet window.

To delete the PIN code of your Skywallet, you can click on the **Delete PIN Code** button. 

After accepting the confirmation message, you will be asked to enter the PIN code of your Skywallet. Once entered and comfirmed, the PIN code of your Skywallet will be deleted.

To ensure optimal security, please make sure to go through this section of the user manual - [Optimize account security](https://github.com/skycoin/hardware-wallet/wiki/Optimize-account-security)

## Wipe the device

**Wipe the device** button helps you to delete the data on your Skywallet.

Once you click on the "Wipe the device" button, you will be asked to confirm the operation on both the Skywallet as well as Desktop Wallet.

While confirming, note that there is an option to remove your Skywallet from the Wallet list in Desktop Wallet. By default, this option will be checked, and if not unchecked, your Skywallet will be removed from the Wallet list.

After confirming the warning message to wipe the device, **all the data in your Skywallet will be erased except for the firmware updates.** The firmware updates of your Skywallet cannot be deleted and will remain the same as before even after the deletion process.

You can also restore all your coins by using the Seed of a previously configured Skywallet, details on how to restore your Skywallet are available on this section [Restore Backup](https://github.com/skycoin/hardware-wallet/wiki/Restore-configuration).

# Updating the Firmware of your Skywallet

The firmware of your Skywallet is its user interface. A brand new Skywallet will not have a firmware installed.

Hence the first thing you have to do when you receive your Skywallet is to install the firmware. Once installed, the firmware of your Skywallet also needs periodic updates.

It is essential you do these updates; otherwise, you would not benefit from the latest security features and upgrades, ultimately putting your coins under risk of security threats.  
Also, at times, the firmware updates are made to improve the functionality of your Skywallet.

## Knowing when to Update:

The Skywallet is designed to store your coins on a long term basis. However, it is essential to connect your Skywallet periodically to check for an available firmware update.

To check this, you can connect your Skywallet to your computer and open the Hardware Wallet window from the Desktop Wallet.

If your firmware is an outdated version then the following warning message will be displayed:

<A screenshot of the warning message showing the firmware is outdated>

If you ignore this dialogue box, the warning message will continue to be displayed in the next window.

<A screenshot of the warning message in the Hardware Wallet window>

## Updating your Firmware:

**Warning - Before you start updating your firmware, ensure that you have backed up the Seed of your Skywallet. It is vital that you have the backup of the Seed because once the update is complete, you will need the Seed to restore your coins.**

***If you need assistance on how to backup the Seed, visit the following link - [Personalization of your Skywallet](https://github.com/skycoin/hardware-wallet/wiki/Getting-to-know-the-wallet).***

Once you have completed the backup of your Seed, you can proceed to update the firmware.

You can begin by clicking on the **Update** button from the dialogue box which appears right after you connect your Skywallet to the computer.

<can be removed> <Reusing the Screenshot of the warning message dialogue box by highlighting the update button>

If you have ignored this message and are in the Hardware Wallet option window, you can click on the **Update Firmware** button.

<can be removed> <Reusing the screenshot of the warning message in the Hardware Wallet window by highlighting the update firmware button>

Once you have clicked on either the "Update" button or "Update Firmware" button, a dialogue box with the warning message to **Backup your Seed** will appear on your computer:

<can be removed> <Warning message to start the device in bootloader mode and backup the Seed>

The warning message will also ask you to connect your Skywallet in bootloader mode.

To connect your Skywallet in bootloader mode, you have to follow these steps:

**Step 1 - Disconnect your Skywallet from the computer.**

**Step 2 - Reconnect the Skywallet while simultaneously pressing both the physical buttons on the Skywallet.**

When connected in the bootloader mode, the display screen on your Skywallet shows the following:

<Picture of the Skywallet in bootloader mode>

After which the display will show the Welcome message.

<Reusing the picture of the welcome message on the Skywallet>

To continue the update you have to accept the operation on your computer. 

The update process will be completed within a few seconds.

**Note - If the update process gets abruptly terminated for any reasons, you can disconnect the Skywallet, close the Desktop Wallet and then restart the whole process from the start.**

# Testing Your Seed

Once you have made the backup of a Seed, this Seed can be used to access your Skywallet. 

If you want to check, whether a Seed you have written down belongs to a given Skywallet, you can use the **Confirm Seed** button. This is a security procedure to check whether the backup has been successful.

The "Confirm Seed" button will not be available when you are using your Skywallet for the first time. Instead, you will see the button **Create Backup**.

Once you have clicked on the **Create Backup** button on the Hardware Wallet window and completed the process of the Seed backup,  the "Confirm Seed" button will replace the "Create Backup" button.

Hardware Wallet window, Before Seed backup:

![Create Backup](https://github.com/sreekumar13/hardware-wallet-manual/blob/master/Testing%20your%20Seed%20-%201.png)

Hardware Wallet window, after Seed backup:

![Confirm Seed](https://github.com/sreekumar13/hardware-wallet-manual/blob/master/Testing%20your%20Seed%20-%202.PNG)

To check whether a Seed belongs to a particular Skywallet, you have to connect your Skywallet first. 

***If you are connecting the Skywallet for the first time, please read the following manuals - [Initialization of your Skywallet](https://github.com/skycoin/hardware-wallet/wiki/Initialize-the-wallet-setting-up) and [Personalization of your Skywallet](https://github.com/skycoin/hardware-wallet/wiki/Getting-to-know-the-wallet) to understand how to initialize and personalize your Skywallet for its first time use.***

If you see the "Confirm Seed" button on your Hardware Wallet window, then it means that you have already taken the backup of the Seed.

After clicking on the "Confirm Seed" button, the Skywallet will ask you to enter the different words in your Seed.

**However, the sequence of these word positions will be in random order.**

<Picture of the Skywallet asking the user to enter a word on a particular position and a screenshot of the Desktop Wallet with the window showing the simultaneous message to enter the specific word at that position>

<can be removed> <Optional picture may be to explain the random sequence by reusing the last image and screenshot along with the next message displayed by the Skywallet to enter another word in another position and its simultaneous Desktop Wallet screenshot>

Along with asking you to enter the words of the Seed at a particular position, **the Skywallet may ask you to enter random words which are not part of the Seed.**

**Both the random words and the random sequence are a security measure to ensure that a potential attacker who might have access to your computer does get neither the full Seed nor the right sequence.**

Once this process is complete, the Desktop Wallet will confirm whether the Seed you have entered is the correct Seed for the connected Skywallet.

<can be removed> <Screenshot1 the Desktop Wallet showing that the Seed is of the connected Wallet>
<can be removed> <Screenshot2 the Desktop Wallet showing that the Seed is not of the connected Wallet>

# Restoring Backup with an Existing Seed

If you have bought a brand new Skywallet and wish to restore the backup of another Skywallet, then you can utilize the "Restore Backup" option during the initialization of your Skywallet.

To restore your coins, you only need the Seed of the other Skywallet.

***A Seed is a combination of 12 or 24 words which serves as the key to access your Skywallet.***

**NOTE - You can use the Seed of a Skywallet on another Skywallet, but it is not recommended to use the same Seed for a Desktop Wallet, as this could comprise the security of your Skywallet.**

To begin the restoration process follow these steps:

### Step 1 

Connect the new Skywallet to your computer.

### Step 2

Once the Skywallet is connected, you will see a welcome message on its display, which also denotes the genuineness of your Skywallet. 

If you want to know more how to check the genuineness of your Skywallet. Please visit the following link - [Checking the Genuineness of your Skywallet](https://github.com/skycoin/hardware-wallet/wiki/How-to-check-whether-device-is-genuine)

<Picture of the Welcome message on the Skywallet>

### Step 3

After connecting the Skywallet to your computer, you can proceed to open your Desktop Wallet.

If you do not have the latest version of the Desktop Wallet, then please download the same from the [Downloads](https://www.skycoin.net/downloads/) page.

If it is your first-time use of the Desktop Wallet, then the following window will be displayed:

<Screenshot of a Desktop Wallet used for the first time> <That is with no Wallets configured>

Proceed to click on the **Using a hardware wallet?** button.

<can be removed> <Reusing the last screenshot with the using a Hardware Wallet button highlighted>

If it is not your first-time use of the Desktop Wallet, then all the Wallets configured using your Desktop Wallet will appear in a list.

![Wallet list in Desktop Wallet](https://github.com/sreekumar13/hardware-wallet-manual/blob/master/Restore%20Wallet%20-%201.PNG)

In this case, proceed to click on the **Hardware Wallet** button, at the bottom.

<can be removed> <Reusing the last screenshot with the Hardware Wallet button highlighted>

### Step 4

Once you have clicked either "Using a hardware wallet?" button or "Hardware Wallet" button, the following window will be displayed by your Desktop Wallet.

<can be removed> <Screenshot  of the Hardware Wallet window>

Proceed to click on the **Restore backup** button.

<can be removed> <Reusing the last screenshot with Restore backup button highlighted>

Upon clicking "Restore backup" button, the Skywallet will start asking you to enter each words of your Seed by their position.
<Image of the Skywallet asking to enter a word at a particular position>

**The sequence of these positions will be random, i.e., the first word asked to be entered might be the word at position #6, but the next word might be the word at position #11 and so on.**

<At least two images to show the random nature of the Seed entering process>

**The Skywallet might also ask you to enter random words that are not part of your Seed as well.**
<Image of the Skywallet requesting the user to enter a random word>

**The random sequence of words and the random words are a security precaution and because of this security measures it can be ensured that a potential hacker/malware, who has access to your computer does get neither the full Seed nor right sequence of the Seed.**

If you have successfully entered both the random words and the words in your Seed according to their position, the Desktop Wallet will display a confirmation window that your new Skywallet was added to the Wallet list.

<can be removed> <Screenshot of the confirmation window from the Desktop Wallet>

You can also rename your Skywallet using this window.

<can be removed> <Reusing the last screenshot with the name of the Wallet edited>

However, if you fail to enter either the random words correctly, or incorrectly enter the words of your Seed, the process will fail, and you will have to restart the procedure from the beginning.

# Optimizing the Security of your Skywallet

Even though a Skywallet provides greater security when compared to a Desktop Wallet, it is essential to follow these security optimizations to get maximum security benefit from your Skywallet.

One of two things is necessary for a third party to access your Skywallet, which is either your Skywallet along with your PIN code of the Skywallet or the Seed of your Skywallet.  
So when it comes to security optimizations, these are the two vital components to be considered.

## PIN Code

Your PIN code is a four-digit combination, and a brand new Skywallet which you receive via shipment will not have a PIN code.

Hence, it is essential first to set a PIN code right after you receive your Skywallet. If you want to know more about how to set the PIN code and personalize your Skywallet, please visit the user manual [Personalization of your Skywallet](https://github.com/skycoin/hardware-wallet/wiki/Getting-to-know-the-wallet).

Although the PIN code is only a combination of four digits, it is improbable for an attacker to guess a secure PIN.

Because after each failed attempt, one has to wait for a specific time before attempting the next combination and with each failed attempt the waiting time increases exponentially thus making it highly unlikely for an attacker/hacker to obtain access to your Skywallet.

However, such a security precaution is ineffective if you create an insecure PIN.

Examples of an insecure PIN include, but are not limited to, important dates, or sequences (like 1234) or repeating digits(1111).

Hence a secure PIN code is something easy to remember and at the same time not easy to guess for a third party.

## Seed

A Seed of the Skywallet is even more critical than a PIN code, as a hacker/malware without access to your Skywallet physically, can remotely access or steal your fund just using the Seed.

As the Seed is not created by you and is generated on the device, you need not worry about the strength of the Seed as such.

**However, it is imperative to keep the backup of the Seed in a safe and accessible place, as it is the only way to access your funds if anything happens to your Skywallet.**

Following are some recommendations to backup and store your Seed safely:

* **Do not Store the Seed in an electronic device. Because saving a Seed in an electronic device effectively nullifies the security it ensures, as the electronic device can potentially be hacked by an attacker, thereby giving access to your Seed.**  
Hence it is recommended to store the Seed in a paper or a notebook which can then be stored in a safe place that is inaccessible to any unauthorized person at the same time not prone to any accidents.  
**The only instance when the Seed is entered into a computer is when you are restoring the backup of your Skywallet**, in that case, the Skywallet and Desktop Wallet process the Seed in a secure way which ensures that a third party will not gain access to your Seed.  
The process is explained in detail in the section (Restore Backup)[https://github.com/skycoin/hardware-wallet/wiki/Restore-configuration].

* Create multiple copies of the Seed and store it in separate locations.

* Make sure to inform of at least one location of the Seed to your immediate family member(s) as a precaution in case of an emergency.

* You can also go for splitting up the Seed in parts to store it in different locations or to have a cipher code for the words in the Seed.  
However, both these methods have a risk factor and are not recommended approaches unless you are ready to take the risk.

# Sending and Receiving Coins Using your Skywallet

To send or receive coins using your Skywallet, you have to initialize and personalize your Skywallet first. Details on how to initialize and personalize your Skywallet can be found in the following chapters:

**[Initialization of your Skywallet](https://github.com/skycoin/hardware-wallet/wiki/Initialize-the-wallet-setting-up)**

**[Personalization of your Skywallet](https://github.com/skycoin/hardware-wallet/wiki/Getting-to-know-the-wallet)**

Once you have completed the initialization and personalization of your Skywallet, you can see your Skywallet in the list of Wallets configured using your Desktop Wallet.

<can be removed> <Screenshot of the Desktop Wallet showing the list of configured Wallets>

## Receive Coins

To receive coins to your Skywallet, you need the address of your Skywallet.

To get the address of the Skywallet, follow these steps :

**Step 1** - Connect your Skywallet to your computer via USB.

**Step 2** - Open the Desktop Wallet from your computer.

**Step 3** - The window will display the list of all the Wallets configured using your Desktop Wallet. From this list, you can click on your Skywallet name to get the address of your Skywallet.

However, only the partial address will be visible for you.

![Partial Address of Skywallet](https://github.com/sreekumar13/hardware-wallet-manual/blob/master/Sending%20and%20Receiving%20-%201.PNG)

**Step 4** - Click on the **Press to Show** button.

Once you have clicked on the "Press to Show" button, the address of the Skywallet will be displayed both by the Desktop Wallet as well as your Skywallet.

**Wallets Showing Same Addresses**

<Screenshot and image of the same address being displayed>

**NOTE - Please check whether both these addresses are the same. If they are not the same, then cancel the operation and stop using the Skywallet. Immediately contact Support by visiting this link - [store.skycoin.net/pages/support](store.skycoin.net/pages/support).  
Alternatively, you can also send an email detailing the issue to **support@skycoin.zendesk.com**.  
It is imperative you do this as showing different addresses means your SkyWallet might have been compromised and using the same would lead you to the loss of your coins.**

**Step 5** - After confirming both the addresses are the same. You can use this address to receive coins to your Skywallet. 

Once the transaction is confirmed in the blockchain, your coins will appear in the balance.

***Unlike the Desktop Wallet, which supports multiple addresses, the Skywallet only supports one address.***

## Sending Coins

### Simple Send

To send coins from your Skywallet using the Simple Send option, you only need the complete address of the receiving Wallet.

**Step 1** - Connect your Skywallet to your computer via the USB.

**Step 2** - Open the Desktop Wallet from your computer.

**Step 3** - Click on the **Send** tab.

![Simple Send tab](https://github.com/sreekumar13/hardware-wallet-manual/blob/master/Sending%20and%20Receiving%20-%202.PNG)

**Note - When you click on the Send tab, by default, the Simple Send option is selected.** 

**Step 4** - Click on the drop-down arrow in the first box - **Send from**, to select your Skywallet from the list.

<can be removed> <Screenshot highlighting the click on the drop-down and highlighting the Skywallet from the list of Wallets >

**Step 5** - Enter the full address of the receiving Wallet in the second box - **Send to**.

<can be removed> <Screenshot of a dummy address entered into the Send to box>

**Warning - Thoroughly verify the address of the receiving Wallet, as entering a wrong address could result in loss of your coins.**

**Step 6** - Enter the amount of Skycoins you want to send in the third box - **Amount**.

<can be removed> <Screenshot of the Desktop Wallet with a certain amount entered and highlighted>

**Step 7** - Click on the **Preview** button to get a preview of your transaction, you can once again verify all the data entered.

![Preview button](https://github.com/sreekumar13/hardware-wallet-manual/blob/master/Sending%20and%20Receiving%20-%203.PNG)

![Preview of Transaction](https://github.com/sreekumar13/hardware-wallet-manual/blob/master/Sending%20and%20Receiving%20-%204.PNG)

**Step 8** - After verifying the entered data, click on the **Send** button to proceed with your transaction.

<can be removed> <Screenshot of the Desktop Wallet with the Send button highlighted>

**Step 9** - Once you click on the "Send" button, a confirmation message will be displayed on your Skywallet.
<image of the Skywallet display screen with the confirmation message to send a certain amount of coins to a specific address>

**Wallets Showing Same Addresses**
<Screenshot and image of the same address being displayed>

 **NOTE - Please make sure that the receiving Wallet address entered by you and the one displayed by the Skywallet in the confirmation message is the same.  
 If it is not the same, abort the whole process and stop using the Skywallet and immediately contact Support by visiting this link - [store.skycoin.net/pages/support](store.skycoin.net/pages/support).  
Alternatively, you can also send an email detailing the issue to **support@skycoin.zendesk.com**.  
 It is imperative you do this as showing different addresses means your SkyWallet might have been compromised and using the same would lead you to the loss of your coins.**

**Step 10** - After you verify both the address you have entered in the Desktop Wallet and the one displayed by the Skywallet in its confirmation message is the same, you can confirm the operation on your Skywallet to send the coins. 
 
## Advanced Send
 
As the name suggests, "Advanced Send" option is to be used in case if you need to access advanced settings when Sending Skycoins.

Sending coins using the Simple Send option is relatively easy as you only need to enter the correct address for the receiving Wallet and the exact amount of Skycoins.

However, if you need to customize your transaction using advanced options, then you can go for the "Advanced Send" option.

Follow the steps below to send coins using the "Advanced Send" option.

**Step 1** - Connect your Skywallet to your computer via the USB.

**Step 2** - Open the Desktop Wallet from your computer.

**Step 3** - Click on the **Send** tab.
<can be removed> <Screenshot of the Desktop Wallet showing the Send window>

**Step 4** - When you click on the Send tab, by default, the Simple Send option is selected, to select Advanced Send option click on the **Advanced Send** button next to the "Simple Send" button.

![Advanced Send tab](https://github.com/sreekumar13/hardware-wallet-manual/blob/master/Sending%20and%20Receiving%20-%205.PNG)

**Step 5** - Click on the drop-down arrow in the first box - **Select Wallet**, to select your Skywallet from the list.
<can be removed> <Screenshot highlighting the click on the drop-down and highlighting the Skywallet from the list of Wallets >

**Step 6** - Enter the full address of the receiving Wallet in the second box named **Destinations**.
<can be removed> <Screenshot of at least two dummy addresses entered into the Destinations box>

**NOTE - You can add multiple addresses when using the Advanced Send option, to add additional address click on the green plus symbol to the extreme right of your screen.**
<can be removed> <Screenshot highlighting the green plus symbol>

**Step 7** - Once you entered the receiving Wallet addresses, you can enter the number of coins you want to send to each of these addresses.

**NOTE - You can toggle between entering the number of Skycoins you want to Send or the equivalent amount of United States Dollars. The Toggle button is available on top of the Destinations box.**

<can be removed> <Screenshot highlighting the toggle button between Sky and USD>

**Step 8** - Next option is the Coin Hours, by default, the Coin Hours for each transaction will be automatically allocated. However, you can change this by unchecking the box **Automatic coin hours allocation** at the bottom of your screen.
<can be removed> <Screenshot highlighting the automatic coin hours allocation box>

**Step 9** - Once you have unchecked the "Automatic coin hours allocation" box, an additional box will appear next to the box where you enter the number of coins.
<can be removed> <Screenshot highlighting the Coin hours box>

**Step 10** - After entering all the destination Wallet addresses, the number of coins and the coin hours, please verify all the data entered is correct.

**Warning - Thoroughly verify the addresses of the receiving Wallets, as entering wrong addresses could result in loss of your coins.**

**Step 11** - After verifying the entered data, you can proceed to enter the change address. If you wish to use a Wallet from the Wallet list for the change address, you can click on the "Select" drop-down.
<can be removed> <Screenshot highlighting the change address box and showing the Wallet list by highlighting and clicking on the drop down>

**Step 12** - In the final box named "Personal Notes", you can add a message which will appear as a remark once the transaction is completed and it appears in the transaction history.
<can be removed> <Screenshot highlighting the personal notes box and showing a transaction in the transaction history tab with a personal note>

**Step 13** - Once all these data are entered or selected, you can reverify this by clicking on the **Preview** button, which shows a preview of your transaction with all the details.

![Preview Transaction](https://github.com/sreekumar13/hardware-wallet-manual/blob/master/Sending%20and%20Receiving%20-%206.PNG) 

**Step 14** - After reviewing and verifying all the data, you can click on the "Send" button. Once you click on the "Send" button, a confirmation message will be displayed on your Skywallet.
<Image of the Skywallet display screen with the confirmation message to send a certain amount of coins to a specific address>

**Wallets Showing Same Addresses**
<Screenshot and image of the same address being displayed>

 **NOTE - Please make sure that the receiving Wallet addresses entered by you and those displayed by the Skywallet in the confirmation message are the same.  
If they are not the same, abort the whole process and stop using the Skywallet and immediately contact Support by visiting this link - [store.skycoin.net/pages/support](store.skycoin.net/pages/support).  
Alternatively, you can also send an email detailing the issue to support@skycoin.zendesk.com.  
It is imperative you do this as showing different addresses means your SkyWallet might have been compromised and using the same would lead you to the loss of your coins.**

# Miscellaneous Operations on Your Skywallet

The basic initialization and personalization operations are mentioned in the chapters:

* [Initialization of your Skywallet](https://github.com/skycoin/hardware-wallet/wiki/Initialize-the-wallet-setting-up)

* [Personalization of your Skywallet](https://github.com/skycoin/hardware-wallet/wiki/Getting-to-know-the-wallet) 

However, you can also perform some additional operations on your Skywallet like: 

* Renaming your Skywallet.

* Removing your Skywallet from the Wallet list.

* Checking the firmware version of your Skywallet.

## Renaming Your Skywallet

**Step 1** - Connect your Skywallet to your computer via USB.

**Step 2** - Open your Desktop Wallet from your computer.

**Step 3** - A window will show the list of all the Wallets configured using your Desktop Wallet.
<can be removed> <Screenshot of the window showing all the Wallets in the Wallet list>

**Step 4** - Select the particular Skywallet which you wish to rename.
<can be removed> <Screenshot highlighting a single Skywallet from the Wallet list>

**Step 5** - Click on the **Edit Wallet** button.
<can be removed> <Screenshot highlighting the Edit Wallet button>

**Step 6** - Once you click on the "Edit Wallet" button a window to edit the name of your Skywallet will appear.
<can be removed> <Screenshot of the window to rename the Wallet>

**Step 7** - Enter a name for your Skywallet and click on the **Rename** button to confirm.
<can be removed> <Reusing the last Screenshot of the window with the rename button highlighted>

You can check your Skywallet in the Wallet list to see the changed name.
<can be removed> <Screenshot of the Skywallet in the Wallet list with the changed name>

## Removing a Skywallet from the Wallet List

**Step 1** - Open your Desktop Wallet from your computer.
<can be removed> <Screenshot of the Desktop Wallet window showing the Wallet list>

**Step 2** - Select the Skywallet you want to remove from the Wallet list.
<can be removed> <Screenshot of the highlighted selection of the Wallet from the Wallet list>

**Step 3** - Click on the **Delete Wallet** button from the window.
<can be removed> <Screenshot of the Desktop Wallet window highlighting the Delete Wallet button>

**Step 4** - Confirm the operation by ticking the box **Yeah, I want to delete the Wallet** and clicking on the **Yes** button.
<can be removed> <Screenshot of the confirmation dialogue box>

**NOTE 1 - To remove a Skywallet from the Wallet list you don't need to connect it to your computer necessarily.**

**NOTE 2 - This whole operation only removes the Skywallet from the Wallet list and does not wipe the device**.  
To know more about how to wipe your Skywallet to remove any personalizations, visit the following chapter - [Personalization of your Skywallet](https://github.com/skycoin/hardware-wallet/wiki/Getting-to-know-the-wallet).  

Also if you want to add the device back to the Wallet list, you can follow the same steps in the chapter - [Initialization of your Skywallet](https://github.com/skycoin/hardware-wallet/wiki/Initialize-the-wallet-setting-up).

## Checking the Firmware Version of Your Skywallet

The firmware is essential for your Skywallet to work properly. You can check the following chapter to know more about firmware and how to update it periodically - [Update Firmware](https://github.com/skycoin/hardware-wallet/wiki/Update-firmware).

To check the current firmware version of your Skywallet, you can follow these steps:

**Step 1** - Connect your Skywallet to your computer via USB.

**Step 2** - Open the Desktop Wallet from your computer.

**Step 3** - A window will show you the list of all the Wallets configured using your Desktop Wallet.
<can be removed> <Screenshot of the highlighted selection of the Wallet from the Wallet list>

**Step 4** - Select your Skywallet from the Wallet list.
<can be removed> <Screenshot of the Desktop Wallet window highlighting the Skywallet from the list>

**Step 5** - You can check for the firmware version in the following window, which appears when you select the Skywallet from the Wallet list.

![Firmware Version](https://github.com/sreekumar13/hardware-wallet-manual/blob/master/Misc%20-%201.PNG)

# Troubleshooting

Here are some of the most common issues you might encounter when using a Skywallet and the best possible resolutions for troubleshooting these issues. 

If you do not find a resolution for your issue, make sure you contact the support team via - **[store.skycoin.net/pages/support](store.skycoin.net/pages/support)**.

You can also send an email at **support@skycoin.zendesk.com**.

## 1. Lost/Stolen Skywallet

If your Skywallet is lost or stolen, the recommended solution is to **get a new one** as soon as possible. 

Once you got the new Skywallet, restore the coins using the Seed of your old Skywallet.

Even though **not a recommended** method, as an immediate solution, you can also create a new Desktop Wallet to restore the lost Skywallet.

This method is not recommended and should only be used if you cannot get a new Skywallet, as entering the Seed of your Skywallet into any electronic device could potentially compromise the security of the Seed of your Skywallet and hence putting your coins at risk.

**NOTE - If you are opting for this solution, note that this is a temporary solution, and it is always recommended that you transfer your coins (not restore the backup of the old Skywallet) to a new Skywallet as soon as you obtain one.  
Also, it is vital that you configure your new Skywallet as a new one with a new Seed and not restore the backup of your old Skywallet if the Seed has already been entered in your Desktop Wallet.**

## 2. Lost the PIN code of Your Skywallet

If you have forgotten or lost the PIN code to your Skywallet **then the only way to retrieve your funds is using your Seed**.

You can use the Seed of your Skywallet to **Wipe the Device** and then restore the device using the same Seed.

The wiped device will not have a PIN code set, and it is recommended that you immediately set a PIN code that is easy to remember but at the same time not easy to guess.

You can visit the following chapter to know more about setting a PIN and the security recommendations for your Skywallet - **(Optimize account security)[https://github.com/skycoin/hardware-wallet/wiki/Optimize-account-security].**

## 3. Too Many Transactions Issue

When you try to send coins to a Wallet and if the particular transaction has too many inputs or outputs, then an error message will be displayed upon pressing the "Preview" button or the "Send" button.
<Screenshot of the error message>

To still transfer your funds, you can split up your transaction into multiple transactions and then send the coins.

**Note - This issue will be fixed in a future update.**
