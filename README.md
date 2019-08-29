CryptBB is an open source encrypted forum that provides securer private communication between people since 2012. All messages are transmitted over the Internet and stored in a database in encrypted format. All mathematical cryptographic operations are executed by the client (Internet browser), not by the server. This forum uses the military-class symmetric cipher AES (Rijndael) 256 CTR (Counter mode) for encrypting messages and one of the best asymmetric ciphers RSA (Rivest-Shamir-Adleman) 768-2048 OAEP for exchanging passwords between users. You can create Your own forums and securely discuss any topic with Your friends. No one (even administrator) can read Your closed messages. Join the encrypted community!

Official site: http://cryptbb.us.to

Description.

The site has a simple structure:
- Forums &#8594; Forum &#8594; Topic &#8594; Post
- Forums &#8594; Users
- User profile &#8594; Private messages &#8594; Exchange password

Forums contain topics, topics consist of posts. All topics have own passwords, all posts are encrypted. Depending on the options, the forum can also have own password to encrypt the names of its topics. The author of the post can delete his post, the topic starter can delete any post in his topic and the topic itself, the forum creator can delete any post or topic in his forum and the forum itself. The administrator can delete any post, topic or forum.

The function of restricting the rights of users and guests to view, read and write on forums and topics is supported. The module "Users" displays the numbers of all registered members to set permissions for specific users in the corresponding section.

The module "User profile" enables to change own password for logging into the application, as well as move to the module "Private messages", where members can exchange their password for a topic or forum between themselves.

Short links to topics are allowed, for example, http://cryptbb.us.to/forum/?t=2

In this case the application automatically redirects from the main page of the forum to the topic with number 2. While the user registers and logs in, the redirect is kept.

The administrator can prohibit members from creating new forums. He can also define an invitation code, which is required for registering new users, and announce this code to the desired guests, for example, http://cryptbb.us.to/forum/reg.php?i=123456

In addition, for increased safety, offline tools were developed for generating a random password, creating keys and also for encrypting and veilizing a message. Attaching an encrypted file to a post was implemented. BB-codes and smileys are supported.

History.

2012-05-31: Version 1. The forum in english (eng) language has been hosted. The AES-256 CTR cipher for encrypting messages has been implemented.

2012-07-10: The RSA 768-2048 cipher for exchanging passwords between members has been implemented. Offline utilities ASYM and SYMM have been created. The CONSOLE captcha has been added.

2013-01-22: The MT 19937 algorithm based on the RAND utility for generating secure random passwords has been implemented. Support for russian (rus) language has been added. The CONSOLE captcha has been upgraded.

2013-03-10: The CAPSUL algorithm for encapsulating small messages has been added. The source code (PHP, HTML and JS) of the application has been published under the MIT license.

2013-06-14: Version 2. The VEIL algorithm for veilizing messages has been implemented for english (eng) and russian (rus) languages.

2014-02-01: Version 3. Support for PHPSECLIB + JS has been added. The CAPSUL algorithm has been modified, the RAND utility has been upgraded. The design of the elements has been changed.

2015-01-25: Version 4. Utilities ASYM and SYMM have been upgraded. The SCRAMBLE algorithm for scrambling messages after encapsulation has been added.

2015-05-09: Version 5. BB-codes are supported. User "crapspacle" asked about posting images, therefore attaching an encrypted file to a message has been implemented.

2015-06-02: Smileys are supported. User "Sophia Kiss" wrote and shared the open source WIN32-application to locally convert Base64-text into binary data and save it to a file.

2016-12-31: Version 6. The CAPSUL algorithm has been simplified to NOISE, the SCRAMBLE algorithm has been simplified to SWAP. The SIGN utility for digitally signing and verifying published files has been created.

2017-09-09: Version 7. The VEIL utility for veilizing messages and transcoding between different pools of Base64-characters has been created.

2018-01-03: The ability of the require an invitation code to register new users has been implemented. The SIGN utility has been upgraded.

2018-08-11: The design of the elements has been changed.

2019-01-12: The module "Private messages" has been upgraded. The VERIFY utility has been created.

2019-08-08: The dark theme for the forum interface has been added. New BB-codes are supported in the posts. The optional KEY-OSSL utility for extracting keys from OpenSSL to the supported format has been created.

Download.

cryptbb-7.19.8.8.zip

See also offline utilities: http://cryptbb.us.to/soft/curr/

Send all questions to the official discussion on the resource php-forum.com since 2013:

http://www.php-forum.com/phpforum/viewtopic.php?f=30&t=22732
