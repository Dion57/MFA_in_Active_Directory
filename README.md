# MFA_in_Active_Directory on Microsoft Azure Portal
# Setup MFA to ensure conditional access within Subscription
On Your browser tab, search [aka.ms/mfasetup](https://aka.ms/mfasetup.com)

login with credentials of account

Specify the type of authentication you want

For mobile phone, OTP will be sent to the number that was uploaded.

Input the OTP number that was sent.

On the Azure Portal,

Under Active Directory, select Users

At the far end of the menu bar, click on the ellipses to open Mulifactor Authentication.

This will bring out all the users from which you can enable MFA on.

MFA cannot be set on a guest user but onl on domain  users that are part of this AD.

Best practices demands that MFA should be used only on certain conditions and not always.
It can be implemented when;
- There is a change in Location;
- New Ip Address
- Change of Device
