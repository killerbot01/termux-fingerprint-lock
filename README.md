# TERMUX FINGERPRINT LOCK
***Disclaimer:*** It's cool to have fingerprint authentication in termux but it's not safe and can easily be bypassed (How?🤫). So, if FBI find your data and a nuclear war start. I won't be held responsible. Use at your own risk.
### Created by [MrAlpha786](https://github.com/MrAlpha786)
***Request:*** Please use or modify this with proper credit. Add link to my github in your README.md.

_Add Fingerprint Lock to your Termux._

***Note: It's not an app lock. It's only for Termux.
      If you don't know what Termux is, You don't need this.***

## Prerequisites
1. Smartphone with Fingerprint Sensor
2. Termux:API app installed
3. Android 6.0+

## Installation

Detailed video instruction here: [YOUTUBE](https://youtu.be/A6EHpyLn3fM)

Just enter following command:

```bash
wget https://raw.githubusercontent.com/MrAlpha786/termux-fingerprint-lock/master/setup; chmod u+x setup; bash setup
```
or
```bash
curl -O https://raw.githubusercontent.com/MrAlpha786/termux-fingerprint-lock/master/setup; chmod u+x setup; bash setup
```

## Remove Lock

**[ ! ]** _Make sure you are in the same directory where the setup is saved._

Enter the command below:

```bash
bash setup
```
or
```bash
./setup
```
***Note: Removing lock will remove all files. To install again you have to follow the above instructions.***

