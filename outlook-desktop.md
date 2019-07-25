---
layout: default
title: Outlook
parent: Desktop Clients
nav_order: 4
---

# Outlook Desktop

## Outlook 2010

1. Launch the program and click **Next** in the welcome screen.
2. In the **Account Setup** window, leave Yes as the default value and click Next. If you already have an Outlook account and want to add another, choose File  → Details and click Add a new account.
3. Select **Manual setup or additional server types** and click **Next**.
4. Leave the default value for Internet email and click Next.
5. Set the following account settings:
    * Name — {{ site.settings.name }}
    * Email address — {{ site.settings.email }}
    * Type of account — IMAP
    * Incoming mail server — {{ site.settings.imap.server }}
    * Outgoing mail server (SMTP) — {{ site.settings.smtp.server }}
    * User — {{ site.settings.username }}
    * Password – {{ site.settings.password }}
6. Leave default values for all other parameters and click Other settings.
7. Go to the Outgoing mail server tab, enable the SMTP server requires authentication checkbox, and select the Same as incoming mail server value.
8. Go to the Advanced tab. For the Use the following type of encrypted connection option, select SSL for the IMAP and SMTP servers. Set the following parameters:
    * IMAP server — {{ site.settings.imap.server }}
    * SMTP server — {{ site.settings.smtp.server }}
9. Click OK.
10. To finish account configuration, click Next in the Add a new account window to test the account settings. If all the settings are correct and confirmed, click Finish. If not, make sure that all the details are entered properly.
11. Synchronize the newly created account with the server to obtain a list of folders.
12. Open the File → Account settings menu, choose the account in the Email tab, and click Change.
13. Click Other settings and go to the Sent tab.
14. Set the field Save the sent items in the following folder on the server and choose the Sent folder.