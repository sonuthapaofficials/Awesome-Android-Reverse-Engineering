# Awesome Android Reverse Engineering
<p align="center">
   <img width=100% src="assets/cover.gif">
 </a>
</p>


<p align="center">
 <b>A curated list of awesome Android Reverse Engineering training, resources, and tools.</b>


<div align="center">


[![Awesome](https://awesome.re/badge.svg)](https://github.com/MarketingPipeline/Awesome-Repo-Template/)
![GitHub contributors](https://img.shields.io/github/contributors/user1342/Awesome-Android-Reverse-Engineering)
![GitHub Repo stars](https://img.shields.io/github/stars/user1342/Awesome-Android-Reverse-Engineering?style=social)
![GitHub watchers](https://img.shields.io/github/watchers/user1342/Awesome-Android-Reverse-Engineering?style=social)
![GitHub last commit](https://img.shields.io/github/last-commit/user1342/Awesome-Android-Reverse-Engineering)


</div>


# How to Use
Awesome-Android-Reverse-Engineering is an amazing list for people who need a certain feature on their app, so the best ways to use are:


Simply press ```command + F``` to search for a keyword or go through our Content Menu


# Contents
- [Training](#Training "Training")
 -  [Courses and Material](#Courses "Courses-and-Material")
 - [Books](#Books "Books")
- [Tools](#Tools "Tools")
  - [Static Analysis Tools](#Static-Analysis-Tools)
  - [Dynamic Analysis Tools](#Dynamic-Analysis-Tools)
  - [Decompilers](#Decompilers "Decompilers")
  - [Machine Learning](#Machine-Learning)
- [Resources](#Resources "Resources")
 - [Documentation](#Documentation)
 - [Case Studies](#case-studies)
- [CTFs and CrackMe's](#CTFs-and-CrackMe's)


## Training
### Courses and Material
- [Maddie Stone's Android Reverse Engineering Training ](https://www.ragingrock.com/AndroidAppRE/ "Maddie Stone's Android Reverse Engineering Training ")- A comprehensive online training course on Android reverse engineering by Maddie Stone, a well-known expert in the field.
- [Introduction to Assembly from Azeria Labs](https://azeria-labs.com/writing-arm-assembly-part-1/) - Covering everything from Data Types, Registers, the ARM Instruction Set, Memory Instructions, and more
- [Kristina Balaam Android Reverse Engineering](https://www.youtube.com/@chmodxx) - A video series on reverse engineering basics and reverse engineering ANdroid malware.
- [LaurieWired Android Reverse Engineering videos](https://www.youtube.com/@lauriewired) - A YouTube channel focusing on Android reverse engineering.
- [Using Frida To Modify Android Games | Mobile Dynamic Instrumentation](https://www.youtube.com/watch?v=BXtAujoPhQw) - Focusing on Reverse engineering Android applications, however, focuses on using Frida to dynamically modify Android games.


## Books
- [Android Internals: A Confectioner's Cookbook](http://newandroidbook.com/ "Android Internals: A Confectioner's Cookbook") - An in-depth exploration of the inner-workings of Android: In Volume I, we take the perspective of the Power User as we delve into the foundations of Android, filesystems, partitions, boot process, native daemons and services.
- [Blue Fox: Arm Assembly Internals and Reverse Engineering](https://www.amazon.co.uk/dp/1119745306) - Provides readers with a solid foundation in Arm assembly internals and reverse-engineering fundamentals as the basis for analysing and securing billions of Arm devices.
- [Android Software Internals Quick Reference](https://www.amazon.co.uk/Android-Software-Internals-Quick-Reference/dp/1484269136) - This book focuses on easily digestible, useful, and interesting techniques in Java and the Android system. Including: encryption and obfuscation, debugging, and APK extraction.


## Tools
### Static Analysis Tools
- [QARK](https://github.com/linkedin/qark "QARK") - An open-source tool developed by LinkedIn for automatic Android app vulnerability scanning, including identifying potential security issues such as SQL injection, insecure data storage, and more.
- [MobSF](https://github.com/MobSF/Mobile-Security-Framework-MobSF "MobSF") - An open-source mobile app security testing framework that supports static and dynamic analysis of Android apps for vulnerabilities and privacy issues.
- [AndroBugs Framework](https://github.com/AndroBugs/AndroBugs_Framework "AndroBugs Framework") - An open-source framework for analysing and scanning Android apps for security issues, including static and dynamic analysis capabilities.
- [imjtool](http://newandroidbook.com/tools/imjtool.html) - Firmware unpacking tool applicable to the widest variety of vendors and formats.
- [Android Studio](https://developer.android.com/studio) - Useful if you don’t have a JEB licence and want to open a decompiled (via JADx) app into a proper IDE.
- [APK Dependency Graph](https://github.com/alexzaitsev/apk-dependency-graph) - An APK class dependency visualizer. Useful for attack surface mapping.
- [disarm](http://newandroidbook.com/tools/disarm.html) - A simple command line utility that takes as an argument a 32-bit hexadecimal number, and parses it as an ARM-64 instruction, providing the disassembly.


#### De-Obfuscation
- [Obfu[DE]scate](https://github.com/user1342/Obfu-DE-Scate) - Obfu[DE]scate is a de-obfuscation tool for Android APKs that uses fuzzy comparison logic to identify similarities between functions, even if they have been renamed as part of obfuscation. It compares two versions of an APK and generates a mapping text file and an interactive HTML file as outputs!
- [TinySmaliEmulator](https://github.com/amoulu/TinySmaliEmulator) - A minimalist smali emulator that could be used to "decrypt" obfuscated. strings


### Dynamic Analysis Tools
- [Frida](https://frida.re/ "Frida") - A dynamic instrumentation toolkit for Android apps that allows for runtime manipulation and analysis of app behaviour.
- Xposed Framework - A powerful framework for hooking and modifying the behaviour of Android apps at runtime, commonly used for reverse engineering and analysis.
- [Objection](https://github.com/sensepost/objection "Objection") - A runtime mobile exploration tool for Android that provides various features for analysing, manipulating, and bypassing app security controls.
- [Burp Suite](https://portswigger.net/burp "Burp Suite") - A popular commercial web security testing tool that can be used for analysing network traffic of Android apps for potential security vulnerabilities.
- [Wireshark](https://www.wireshark.org/ "Wireshark") - A widely used open-source network protocol analyzer that can capture, analyse, and dissect network traffic generated by Android apps for security analysis.
- [SSLsplit](https://github.com/droe/sslsplit "SSLsplit") - An open-source tool for intercepting and manipulating SSL/TLS encrypted traffic, which can be used for analysing SSL/TLS communication in Android apps.
- [Drozer](https://github.com/WithSecureLabs/drozer "Drozer") - An open-source framework for Android security testing that provides a comprehensive set of tools for dynamic analysis, including intercepting, modifying, and analysing app traffic.
- [MITMProxy](https://mitmproxy.org/ "MITMProxy") - An open-source man-in-the-middle proxy that allows for intercepting and analysing network traffic generated by Android apps for security testing and analysis.
- [jnitrace](https://github.com/chame1eon/jnitrace) - A Frida based tool to trace use of the JNI API in Android apps.
- [jtrace](http://newandroidbook.com/tools/jtrace.html) - strace for Android - for tracing system-level calls including Binder.
- [sesearch](https://linux.die.net/man/1/sesearch) - Command line tool to query SELinux policies.
- [AutoDroid](https://github.com/user1342/AutoDroid) - Tool for mass gathering APKs from a device(s), decompiling, filtering on strings, etc.
- [RMS Runtime Mobile Security](https://github.com/m0bilesecurity/RMS-Runtime-Mobile-Security) - Frida web interface.
- [FriDump](https://github.com/Nightbringer21/fridump) - A Python script that utilises Frida to dump the memory of a running gadget, such as an app activity.


### Decompilers
- [JADX](https://github.com/skylot/jadx "JADX") - An open-source tool for decompiling and analysing Android APK files into Java source code for reverse engineering and analysis.
- [Procyon](https://github.com/mstrobel/procyon "Procyon") - An open-source Java decompiler that can decompile Android APK files into readable Java source code for reverse engineering and analysis.
- [Cfr](https://github.com/leibnitz27/cfr "Cfr") - An open-source Java decompiler that supports decompilation of Android APK files into Java source code, including support for newer Java language features.
- [FernFlower](https://github.com/fesh0r/fernflower "FernFlower") - An open-source Java decompiler that supports decompilation of Android APK files into Java source code, including support for deobfuscation and other advanced features.
- [Apktool](https://ibotpeaches.github.io/Apktool/ "Apktool") - A popular open-source tool for decompiling and recompiling Android APK files.
- [DEX2JAR](https://github.com/pxb1988/dex2jar "DEX2JAR") - A tool for converting Android DEX files to JAR files, which can be further analysed using Java decompilers.
- [JDGui](http://java-decompiler.github.io/) - JD-GUI is a standalone graphical utility that displays Java source codes of “.class” files.
- [ IDA Pro](https://hex-rays.com/ida-pro/ " IDA Pro") - A powerful commercial disassembler and debugger for analysing Android native code.
- [Ghidra](https://ghidra-sre.org/ "Ghidra") - A free and open-source software reverse engineering (SRE) framework developed by the National Security Agency (NSA) that supports Android analysis.
- JEB Decompiler - A commercial decompiler for Android apps that can decompile APK files into Java source code for analysis.
- [Radare2](https://rada.re/n/ "Radare2") - A free and open-source reverse engineering framework that supports Android analysis, including disassembly, debugging, and binary analysis.
- [Androguard](https://github.com/androguard/androguard "Androguard") - An open-source tool for analysing and reverse engineering Android apps, including decompiling APK files, analysing Dalvik bytecode, and more.


### Machine Learning
- [DroidDetective](https://github.com/user1342/DroidDetective) - A machine learning malware analysis framework for Android apps.


## Resources
### Documentation
- [Android Security Documentation](https://source.android.com/docs/security "Android Security Documentation") - Official documentation from Google on Android security, including topics related to reverse engineering.
- [Android Reverse Engineering Challenges ](https://github.com/apsdehal/awesome-ctf#reverse-engineering "Android Reverse Engineering Challenges ")- A curated list of Android reverse engineering challenges and CTFs (Capture The Flag) for practice.
- [AndroidXref](http://androidxref.com/) - Open code search for Android source.
- [APKMirror](https://www.apkmirror.com/) - Repository of AndroidAPKs from sources such as the Play Store and user uploads.
- [APKPure](https://m.apkpure.com/) - Repository of AndroidAPKs from sources such as the Play Store and user uploads.


### Case Studies
- [A Reverse Engineer’s Post-mortem Of The Houseparty Video Chat App](https://www.jamesstevenson.me/a-reverse-engineers-post-mortem-of-the-houseparty-video-chat-app/)
- [SharkBot: a “new” generation Android banking Trojan being distributed on Google Play Store](https://research.nccgroup.com/2022/03/03/sharkbot-a-new-generation-android-banking-trojan-being-distributed-on-google-play-store/)
- [In-the-Wild Series: Android Exploits](https://googleprojectzero.blogspot.com/2021/01/in-wild-series-android-exploits.html)


## CTFs and CrackMe's
- [UnCrackable Mobile Apps](https://github.com/OWASP/owasp-mastg/tree/master/Crackmes) - A set of OWASP Android app Crackme's. These challenges are used as examples throughout the OWASP MASTG. Of course, you can also solve them for fun.
- [CyberTruckChallenge19](https://github.com/nowsecure/cybertruckchallenge19) - Android security workshop material taught during the CyberTruck Challenge 2019 (Detroit USA).
- [KGB Messenger](https://github.com/tlamb96/kgb_messenger) - KGB Messenger is an open source CTF practice challenge that aims to help people learn how to reverse engineer Android applications.






## Contributing
Your contributions are always welcome! Please read the contribution guidelines first. We  follow the Contributor Covenant Code of Conduct. Please make sure to review. and adhere to this code of conduct when contributing.


## Licence <a href="LICENCE"> ![GitHub](https://img.shields.io/github/license/MarketingPipeline/Awesome-Repo-Template) </a>


This project is licensed under the MIT License - see the LICENSE.md file for details.
