# My Secure Home - User’s Manual

## Why This App?

As an ex-Facebook engineer, I really hate the fact that giant companies are peeking into everyone's privacy.  I hope there is a tool for everyone in the world that allows them to store their information securely.  At the same time, I want to make the collaborations with small social circles easier.

My Secure Home has a distinct difference that all the texts and images within each social circle is encrypted using the circle password, which makes it impossible to read unless the password is possessed.  This eliminates the possibility of others peeking into your data.

## Installation

### iOS

Search for “My Secure Home” on App Store and you can download.

<img src="pic/App_store.png" alt="drawing" width="300"/>

### Android

Search for “Secure Home” in the Google Play Store, or use the [download link](https://play.google.com/store/apps/details?id=com.k8sllc.securehome).

<img src="pic/Play_store.png" alt="drawing" width="300"/>


Note our App does not send annoying trash notification at all.  Please grant it permissions when asked! Otherwise, you will lose important features.

## Account Management

### Registration

<img src="pic/Login_page.png" alt="drawing" width="300"/>

Click "CREATE AN ACCOUNT" at the bottom and you will be guided step-by-step to create your account using your cell phone.  Please be aware that if you don't receive the verification code, please check if you blocked the sender (650) 409-9686.  Contact us support@k8sllc.com if you have problems.

### Profile Customization

<img src="pic/Main_page.png" alt="drawing" width="300"/>

<img src="pic/Bottom_menu.png" alt="drawing" width="300"/>


Use the bottom-right button to go to settings page, where you can modify your name, your email, profile picture, etc.

### Language Selection

We support American English and Simplified Chinese.

### Logout

You can log out using the LOGOUT button in the settings page.

## Circle / Family Management

There are two types of social circles we support: "Circle" for friends and activities, and "Family" for the real families. At this moment, they have no real differences. But in the future this may change.

### Create Circle / Family

Every normal user can create up to 5 circles / families.  VIP users have much higher limits.

<img src="pic/Create_circle.png" alt="drawing" width="300"/>

Use the bottom-right button to create a circle / family. During creation, there are two ways to provide the password. You can either provide a strong password by yourself, or use the "Generate strong password" button to generate a new one on your phone (ONLY ON YOU PHONE). When a new password is generated, you can export it to clipboard, or even export as an image.  Please save it.

We NEVER store your circle password! We store a random secret and the encrypted value using your circle password and the AES algorithm, and will use them for password validation. Even if some hacker compromises our whole database and cloud files, they still won't see your circle contents, including all texts and images, until (1) they are approved to join the circle, and (2) they know the actual circle password. Therefore, please carefully store your circle password!

### Share Circle / Family

In the circle / family, you can use the menu to display or export a QR code. Other members would have to scan this QR code to join your circle / family.

<img src="pic/Circle_settings.png" alt="drawing" width="300"/>


### Join Circle / Family

Use the bottom-right button to scan and join the family. You will be prompted to verify the password. If the verification passes, the circle creator will receive a push notification.  They can then approve the joining request.  

<img src="pic/Main_page.png" alt="drawing" width="300"/>

Note in this verification step, the circle password is not transmitted online!

### Export Locally-cached Passwords

In the settings menu, you can export locally-cached passwords if you have provided them after logging in.  Note this will only be available after you entered the circle passwords.

## To-dos

<img src="pic/Todo.png" alt="drawing" width="300"/>

To-dos is a synchronized to-do list for the circle. 

On the top-right of every page, we provide this encryption toggle that allows you to see how your data is stored on the server.

```text
Create to-do: click the top-right "+" button.
Edit to-do: click the to-do item.
Status change: click the button on the left of a to-do item.
Delete a to-do: left swipe on a to-do item, then click delete.
Re-order to-dos: press and hold a to-do item, then drag.
```

## Events

Events is for circle-specific events. The creation is very intuitive.  Note that the events will be automatically synchronized to your device.  On iOS it is synchronized to the "Home" calendar on your iCloud account.  You can update images for an event, which will be encrypted.  You can add locations to events.

<img src="pic/Event3.png" alt="drawing" width="300"/>
<img src="pic/Event4.png" alt="drawing" width="300"/>
<img src="pic/Event5.png" alt="drawing" width="300"/>
<img src="pic/Event6.png" alt="drawing" width="300"/>

## Chats

Chats are self-explanatory.  Currently, it may feel slower when sending messages because there is some optimization work missing.  However, this will be fixed.

## Circle Logs

You can check out the circle logs to see who has recently modified anything.

<img src="pic/Logs.png" alt="drawing" width="300"/>

## Albums

We are working on it. It will be out in Jan 2020.

## Contact Us

Use the "contact us" button to email us anytime!

## Clear Cache

<img src="pic/Settings.png" alt="drawing" width="300"/>

We cache images for faster image loading.  Use the top-right button to clear all local cache!
