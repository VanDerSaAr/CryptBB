This application, the encrypted forum with the open source code, provides a more secure private communication between the people. All messages are transmitted over the internet and are stored in the database in the encrypted format. All the mathematical cryptographic operations are executed by the client (internet browser), not by the server. This forum uses the symmetric military-class encryption AES (Rijndael) 256 CTR (Counter mode) for encrypting the messages and one of the best asymmetric ciphers RSA (Rivest-Shamir-Adleman) 768-2048 OAEP for exchanging the passwords between the members. Here You can create Your own forums and discuss with Your friends any topics securely. Anybody (even administrator) cannot read Your closed messages. Join the encrypted community!

Official site: http://cryptbb.us.to

Description.

The site has a simple structure:
- Forums &#8594; Forum &#8594; Topic &#8594; Post
- Forums &#8594; Users
- User profile &#8594; Private messages &#8594; Exchange password

The forums contain the topics, the topics consist of posts. All topics have own passwords, all posts are encrypted. Depending on options, the forum also can have own password to encrypt the names of its topics. The author of the post can delete his post, the topic starter can delete any post in his topic and the topic itself, the forum creator can delete any post or topic in his forum and the forum itself. Administrator can delete any post, topic or forum.

The function of restriction the rights for the users and the guests to view, read and write in forums and topics is supported. The module "Users" displays the numbers of all registered members to set the rights for a definite users in the corresponding section.

The module "User profile" allows to change own password to login the application, and also to move to the module "Private messages", where the members can exchange their password of the topic or the forum between themselves.

It is allowed a short links to the topics, for example, http://cryptbb.us.to/forum/?t=2

In this case the application realizes the automatic moving from the main page of the forum to the topic with number 2. While the user registers and logins, the redirect is kept.

Administrator can restrict the members to create a new forums. Also he can define the invite code, which is demanded to register a new users, and announce this code to a needed guests, for example, http://cryptbb.us.to/forum/reg.php?i=123456

Besides, to increase a safety, the offline tools to generate a random password, to create a keys and to encrypt and veilize a message are created. The attaching the encrypted file to the post is realized. BB-codes and the smileys are supported.

History.

2012-05-31: Version 1. The forum in english (eng) language was hosted. AES-256 CTR encryption of the messages was added.

2012-07-10: RSA 768-2048 exchanging the password between the users was added. The offline utilities ASYM, SYMM were created. CONSOLE captcha was added.

2013-01-22: MT 19937 random generator based on the offline utility RAND was added. The supporting of russian (rus) language was added. CONSOLE captcha was upgraded.

2013-03-10: CAPSUL capsulation of the small messages was added. The source code (PHP, HTML and JS) of the application was published under MIT license.

2013-06-14: Version 2. VEIL veilization of the messages for english (eng) and russian (rus) languages was added.

2014-02-01: Version 3. The supporting of PHPSECLIB + JS was added. RAND, CAPSUL were upgraded. The design of the elements was changed.

2015-01-25: Version 4. ASYM, SYMM utilities were upgraded. SCRAMBLE scrambling of the messages after CAPSUL was added.

2015-05-09: Version 5. BB-codes are supported. User "crapspacle" asked about the image posting, therefore the attaching the encrypted file to the message was realized.

2015-06-02: The smileys are supported. User "Sophia Kiss" wrote and shared the open source WIN32-application to locally convert Base64-text to a binary data and save it to a file.

2016-12-31: Version 6. CAPSUL was simplified up to NOISE, SCRAMBLE was simplified up to SWAP. The offline utility SIGN to digitally sign and verify a published files was created.

2017-09-09: Version 7. The offline utility VEIL to veilize a messages and to reencode between the different pools of Base64-symbols was created.

2018-01-03: The ability of demanding the invite code to register a new users is realized. The utility SIGN was upgraded.

2018-08-11: The design of the elements was changed.

Download.

cryptbb-7.18.8.11.zip

See also the offline utilities: http://cryptbb.us.to/soft/curr/

Read the official discussion on the resource since 2013: http://www.php-forum.com/phpforum/viewtopic.php?f=30&t=22732
