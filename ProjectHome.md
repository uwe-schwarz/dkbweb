Based upon Christian Hoffmann's GitHub project "dkb-visa", see here https://github.com/hoffie/dkb-visa, who only fetches the credit card transactions and stores them in a CSV file or converts it to QIF format.

This project extends "dkb-visa" and adds some more features:

1. Also fetch bank account transactions and store them in CSV or QIF format.

2. Submit PIN code on the command line. This makes it very useful for automation and batch scripting but is insecure because the PIN is stored somewhere in plain text (e.g. in a .bat or .sh script).

3. Performs a logout to close the session at the DKB server.

You still need "dkb.py" from Christian Hoffmann's "dkb-visa" project. My project file "dkb-web.py" is based upon "dkb.py" and needs to import it as a module.

For that reason you still can do everything in exactly the same way as you would do with "dkb.py".