# Mirage realms to EXE

- [Mirage realms to EXE](#mirage-realms-to-exe)
  - [Which client should I use?](#which-client-should-i-use)
  - [Who is this launcher recommended for?](#who-is-this-launcher-recommended-for)
  - [Download](#download)
    - [Choosing the right version of Launcher MRtoEXE](#choosing-the-right-version-of-launcher-mrtoexe)
  - [Why is this client larger than the official size?](#why-is-this-client-larger-than-the-official-size)
  - [Make this executable yourself](#make-this-executable-yourself)
    - [You will need](#you-will-need)
  - [About this project](#about-this-project)
    - [Possible next steps for this project](#possible-next-steps-for-this-project)
  - [Contributing to this repository](#contributing-to-this-repository)

Executable Mirage Realms MMORPG launcher for Windows  bundled with JRE.

No need to install Java. Just download and have fun.

## Which client should I use?

If the official client works fine for you, always choose to use the official Mirage client downloaded directly from the [website](https://www.miragerealms.co.uk/devblog/play/).

If you find yourself in any of the situations listed below, give this launcher a try.

## Who is this launcher recommended for?

I recommend using it in the following situations:

- Compatibility issues that happen on older devices with Intel HD Graphics 2000/3000

  - From the Java 8 update 51 version, some devices running Windows 10 present incompatibility.
  - One of the solutions would be to downgrade your JAVA to version 8u51
       > I do not recommend it as it may open breach for possible vulnerabilities existing in this older version.

- The official client opens and closes quickly when clicked, but it can open normally using CMD.

- Want convenience of not having to install Java or an older version of it.¯\\\_(ツ)\_/¯
  
## Download

Choose the best version for you [here](https://github.com/cent222/MRtoEXE/releases), extract, click on the executable and enjoy.

### Choosing the right version of Launcher MRtoEXE

- The JRE version that is packaged together with the executable is specified in the filename after the underscore.
   > mirage-x-x-xx **_jre-version**.zip

**Initially I will distribute the following versions:**

- If followed by **default**, it is the most recent build of JRE 8 distributed by [Azul](https://www.azul.com/downloads/?package=jdk).
   > mirage-x-x-xx _jre-version-**default**.zip

- If followed by **compatibility**, it's the version of JRE 8 update 51 distributed by Oracle, some players have problems running the game in versions higher than this one, I don't know if this also happens with a packaged JRE so whoever has this problem in the official client, you can test the default version first and leave your feedback.
   > mirage-x-x-xx_jre-version-**compatibility**.zip

Maybe... soon I will make available **Installer** version

- Installer will install Mirage like any other program you have installed on your PC, it comes with the two versions described above and you choose which one you want to install.
- I currently use this one, I built it using InnoSetup, but I still haven't figured out the correct way to do a decent setup with both versions.

## Why is this client larger than the official size?

This client brings the JRE (Java Runtime Environment) bundled with it, and therefore it should take up more space on your disk.

## Make this executable yourself

I would like the community to get involved in this project and also create and distribute their own launchers to their friends and guildmates, remembering that we shouldn't trust and click on any executable, so:

> If you want something done right, do it yourself.

I'll be creating a more detailed guide on this soon, but I found this [video](https://www.youtube.com/watch?v=51iMSVUOQNM) very helpful which pretty much describes the basics for you to do this.

- Launch4j documentation is also a great value if you have any questions

### You will need

- **Latest version of official Mirage realms client**
  - [Download the desktop version directly from the website](https://www.miragerealms.co.uk/devblog/play/)
- [Launch4j](https://launch4j.sourceforge.net/) (to create an _exe_ from the _jar_ file and link to the JRE)
- JRE (Java Runtime Environment)(optional - only if you want a JRE packaged along with your executable)
  - To avoid annoying software licenses and selling your soul to Oracle, I suggest you use the Zulu distributions from [Azul](https://www.azul.com/downloads/?package=jdk).

## About this project

This project was created with the aim of helping new players to solve possible problems when running Mirage for the first time.

Any trademark, service mark, trade name, or other intellectual property rights used in this project are owned by the respective owners.

### Possible next steps for this project

- [ ] ⭐ Automated generation of packages
- [ ] ⭐ Auto search for updates
- [ ] When Liam officially starts distributing a client bundled with the JRE
  - [ ] 🌟 End of this project

## Contributing to this repository

Help correct typos and give suggestions to improve this readme, I used a translator for most of it.

If you find any bugs or want to contribute to this project feel free to open an issue or a pull request, this is not my main github so I might take a while to see.
