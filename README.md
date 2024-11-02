This TorMatrix repository was created for the following purposes:
1) Hosting a simple to download Element modification (nicknamed "TorMatrix") which connects to an Onion server by default and has a number of privacy improvements.
2) Providing instructions on how to set up Element with Orbot on Android. (Work in Progress)
3) Providing instructions on how to set up Element Desktop on Windows to use TOR and a Socks5 proxy. (Work in Progress)
4) Providing nstructions on how to set up your own Matrix homeserver behind TOR. (Work in Progress)

TorMatrix is not affiliated in any way with Vector.IM, TOR, Matrix, Orbot or any of the software authors referenced in the document. It is merely a dirty (but working) solution for those who just need a quick and simple way to create a community that is outside the clear web.

## TorMatrix for Android
- ### [DOWNLOAD THE UNIVERSAL APK FROM HERE](https://mega.nz/file/yIJnUZpT#EDeK4phU6ff7c0TN3no1ZDLtWyiwTlYhKp9ynsu6m8c)
- Alternative APK versions: [arm64](https://mega.nz/file/bcJ0FaRC#ltubT1G-vtXNnRf4qoXpcke2SWg8w3G1tUx6n5OuANo), [armeabi](https://mega.nz/file/SABFHADD#Z_0SqGvTn_IW-m3eIhpFz7b_5ipOXT_eEJJ03V8K2dQ), [x86](https://mega.nz/file/aAoyhCqJ#Y_LH9tjEbqgz4PFNWIGatCvl2q5kzmuGGDSoIPsnOAI), [x86-64](https://mega.nz/file/2RIzHYQB#wDlGyULJ_QfWUEfgV8G66SRukoLtzKUZSImDdBljzUk)
- Note: you don't have to use this altered version of Element to connect to the TorMatrix server. But it is highly recommended.

## Element? Matrix? Tor? Orbot? What are these?
- Element is a chat application for your phone, similar to Viber, Telegram, Session, etc. You can send messages, photos and videos to people and groups. The client supports end-to-end encryption. You can connect to any Matrix server using Element.
- Matrix is software which runs on a server (you can self-host your chat groups and data) and is responsible for serving the database with the chats and media.
- TOR is software and a network run by privacy enthusiasts. It allows anyone to browse the web without revealing their IP address and makes tracing very hard. It also allows services to be hosted on the network (using Onion domains) without the need for any clear web (regular) domain name or IP address.
- Orbot is an Android app which allows you to tunnel your other apps into using the TOR network.

## TorMatrix vs Element differences
- Different application name and icon, so that you can install TorMatrix alongside your regular Element app and tunnel it through Orbot.
- TorMatrix uses an Onion (TOR) Matrix server by default instead of matrix.org.
- Analytics disabled and crippled by default.
- No identity servers, no phoning home to any vector.im or matrix.org hosts unlike the reference client.
- No relying on Google Play services (it's based on the F-Droid version of Element).
- No Firebase push services or any external third party connections.
- Crash reporting is disabled.
- You can't do voice and video calls, it's just for chatting.
- You probably won't be able to use federation (joining groups or talking to contacts on servers outside your home server).

## Who can use the TorMatrix server?
- For now, anyone. It is an experimental project.
- It comes with no guarantees in terms of privacy, safety, data retention or anything like that. It is provided "as is". It's subject to change, go down at any time.
- Depending on how popular it gets, registration will likely be limited in the future and inactive accounts will be purged.
- It is run anonymously and will remain behind an Onion service.

