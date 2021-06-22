# Encryption using DataWeave

An application on encryption using DataWeave.

This is the code which does the following:
- Reads a JSON payload.
- Encrypts the needed field using "HMACBinary" and converts the payload to its "Base64" counterpart.
- Inserts the encrypted (partially in this case) payload in a database.

And thats it!

I have kept the properties in a properties file. Feel free to amend it as per the need!
