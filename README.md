Dependencies required:
1. SSMTP. Command to install:
   ```
   $sudo apt install ssmtp
   ```
2. Mailutils. Command to install:
   ```
   $sudo apt install mailutils -y
   ```

Command used to configure the ssmtp utility:
   ```
   $nano /etc/ssmtp/ssmtp.conf
   ```

Command to execute the bash script to send the email using the contents of the text file:
   ```
   $ssmtp user@domain.com < msg.txt
   ```
