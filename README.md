[![Board Status](https://dev.azure.com/gideondavid3280822/d7418fba-a543-4c55-a433-a3bb553d030c/499160e7-d98f-481f-a037-d0f38efc4f82/_apis/work/boardbadge/a727a327-1c93-412d-a99e-8ccb7ab84c3a)](https://dev.azure.com/gideondavid3280822/d7418fba-a543-4c55-a433-a3bb553d030c/_boards/board/t/499160e7-d98f-481f-a037-d0f38efc4f82/Microsoft.RequirementCategory)
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
