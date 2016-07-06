##################################################################
##################################################################
##################################################################
##################################################################
########						  ########
########						  ########
########	     Mailjet - Magento plugin	          ########
########						  ########
########						  ########
########		   INSTALLATION			  ########
########						  ########
########						  ########
##################################################################
##################################################################
##################################################################
##################################################################

This Plug-in replaces your default Magento SMTP by Mailjet's SMTP relay for advanced Deliverability and Statistics

Please note that the plugin is compatible with v1 and v3 MailJet users. 

1) Unzip plugin/MJ_Customsmtp-1.0.0.tgz or Upload it using Magento Connect Manager (System > Magento Connect > Magento Connect Manager). If you prefer the second option you should avoid the step 2 of this instructions
2) Upload all its content in your Magento's root directory (If you not using Magento Connect Manager).
3) Log in as administrator in Mangento.
4) Flush Magento cache.
5) Log out.
6) Log in as administrator again.
7) Your plugin is accessible by "System > Mailjet settings".
8) Make sure that in "System > Configuration > Store Email Addresses" you have set "Sender Email" with a validated sender email from your Mailjet account.

If you have any problem :

1) Flush Magento cache.
2) Log out and log in as administrator in Magento.
3) Check "System > Configuration > Advanced". Module "MJ_Customsmtp" must be enabled.
