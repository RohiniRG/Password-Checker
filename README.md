# Password-Checker

Using the API provided by https://haveibeenpwned.com/ through the requests module of Python, the project involves determining a given password's strength and the number of times a weak password has been hacked. We also use the hashlib module of Python which uses the SHA1 hashing and send only the first 5 characters of our hashed password through the API, thus keeping our passwords secure.
