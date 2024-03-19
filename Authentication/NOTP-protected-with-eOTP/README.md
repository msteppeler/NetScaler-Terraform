This script contains everything to configure native OTP Feature on Netscaler.

Due to the fact, that users wants to create their token from everywhere,  the /manageotp site is published through the internet.
Using only username and password is too weak to protect this site, so I decided to use email OTP for protection.

To access the /manageotp site, user has to enter username, LDAP password and a 6 digit OTP which is sent to the primary mail address.
