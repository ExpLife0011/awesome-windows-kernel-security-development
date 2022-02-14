# awesome-windows-kernel-security-development

![logo](https://w.wallhaven.cc/full/57/wallhaven-576e31.jpg)

![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)
![GitHub followers](https://shields.io/github/followers/ExpLife0011?label=Followers)
![GitHub forks](https://shields.io/github/forks/ExpLife0011/awesome-windows-kernel-security-development?style=social)
![GitHub stars](https://shields.io/github/stars/ExpLife0011/awesome-windows-kernel-security-development?style=social)
![GitHub watchers](https://shields.io/github/watchers/ExpLife0011/awesome-windows-kernel-security-development?style=social)

- [awesome-windows-kernel-security-development](#awesome-windows-kernel-security-development)
  - [powershell](#powershell)
  - [pe file format](#pe-file-format)
  - [asm ide](#asm-ide)
  - [meltdown/spectre poc](#meltdownspectre-poc)
  - [lightweight c++ gui library](#lightweight-c-gui-library)
  - [direct ui](#direct-ui)
  - [chrome](#chrome)
  - [chrome Extension](#chrome-extension)
  - [cef](#cef)
  - [WebBrowser](#webbrowser)
  - [d3d](#d3d)
  - [opencv](#opencv)
  - [bass](#bass)
  - [lua](#lua)
  - [c++ 11/14/17/20](#c-11141720)
  - [cmake](#cmake)
  - [DesignPattern](#designpattern)
  - [c++ & js](#c--js)
  - [gdi/gdi+](#gdigdi)
  - [QT](#qt)
  - [computer vision & machine learning](#computer-vision--machine-learning)
  - [compress](#compress)
  - [Dongle](#dongle)
  - [spy++](#spy)
  - [Shell Extension for Windows Explorer](#shell-extension-for-windows-explorer)
  - [windows system programming](#windows-system-programming)
  - [etw](#etw)
  - [wsl/unix](#wslunix)
  - [device tree](#device-tree)
  - [irp monitor](#irp-monitor)
  - [nt crucial modules](#nt-crucial-modules)
  - [windows kernel driver](#windows-kernel-driver)
  - [windows kernel driver with c++ runtime](#windows-kernel-driver-with-c-runtime)
  - [blackbone](#blackbone)
  - [hidinput](#hidinput)
  - [dkom](#dkom)
  - [ssdt hook](#ssdt-hook)
  - [eat/iat/object/irp/iat hook](#eatiatobjectirpiat-hook)
  - [InfinityHook](#infinityhook)
  - [inline hook](#inline-hook)
  - [hook engine](#hook-engine)
  - [anti hook](#anti-hook)
  - [inject technique (ring0)](#inject-technique-ring0)
  - [inject technique (ring3)](#inject-technique-ring3)
  - [WoW64 <-> x64](#wow64---x64)
  - [anti autorun](#anti-autorun)
  - [anti dll inject](#anti-dll-inject)
  - [load Dll from memory](#load-dll-from-memory)
  - [Unpack dll load in runtime](#unpack-dll-load-in-runtime)
  - [dll hijack](#dll-hijack)
  - [com hijack](#com-hijack)
  - [anti dll hijack](#anti-dll-hijack)
  - [process hollowing](#process-hollowing)
  - [pe loader](#pe-loader)
  - [memory pe dumper](#memory-pe-dumper)
  - [dll map detection](#dll-map-detection)
  - [dll to shellcode](#dll-to-shellcode)
  - [dll to exe](#dll-to-exe)
  - [hide process](#hide-process)
  - [hide & delete dll](#hide--delete-dll)
  - [load driver from memory](#load-driver-from-memory)
  - [bypass memory scanner](#bypass-memory-scanner)
  - [KeUserModeCallBack](#keusermodecallback)
  - [callback](#callback)
  - [keyboard filter](#keyboard-filter)
  - [usb filter](#usb-filter)
  - [sfilter](#sfilter)
  - [minifilter](#minifilter)
  - [anti Ransomware](#anti-ransomware)
  - [virtual disk](#virtual-disk)
  - [virtual file system](#virtual-file-system)
  - [lpc](#lpc)
  - [alpc](#alpc)
  - [lsp/spi](#lspspi)
  - [afd](#afd)
  - [tdi](#tdi)
  - [wfp](#wfp)
  - [ndis](#ndis)
  - [game accelerator](#game-accelerator)
  - [wsk](#wsk)
  - [rootkits](#rootkits)
  - [mbr](#mbr)
  - [bootkits](#bootkits)
  - [uefi/smm](#uefismm)
  - [bootloader](#bootloader)
  - [smc](#smc)
  - [anti debug](#anti-debug)
  - [crypters](#crypters)
  - [malware](#malware)
  - [EternalBlue && Doublepulsar && Mine](#eternalblue--doublepulsar--mine)
  - [shellcode analysis](#shellcode-analysis)
  - [malware analysis](#malware-analysis)
  - [av evasion](#av-evasion)
  - [arktools](#arktools)
  - [EDR](#edr)
  - [bypass patchguard](#bypass-patchguard)
  - [bypass dse](#bypass-dse)
  - [HackSysExtremeVulnerableDriver](#hacksysextremevulnerabledriver)
  - [windows exploits](#windows-exploits)
  - [linux exploits](#linux-exploits)
  - [windows kernel exploits](#windows-kernel-exploits)
  - [race condition](#race-condition)
  - [LPE](#lpe)
  - [linux exploit](#linux-exploit)
  - [office exploit](#office-exploit)
  - [flash exploit](#flash-exploit)
  - [sandbox](#sandbox)
  - [sandbox escape](#sandbox-escape)
  - [anti exploit](#anti-exploit)
  - [cve](#cve)
  - [hips](#hips)
  - [windows hypervisor](#windows-hypervisor)
  - [kvm](#kvm)
  - [vt](#vt)
  - [firmware](#firmware)
  - [fuzzer](#fuzzer)
  - [fuzz & vulnerability discovery learn](#fuzz--vulnerability-discovery-learn)
  - [emet](#emet)
  - [hotpatch](#hotpatch)
  - [memory hack](#memory-hack)
  - [game](#game)
  - [game network accelerator](#game-network-accelerator)
  - [game hack](#game-hack)
  - [anti cheat](#anti-cheat)
  - [software reverse](#software-reverse)
  - [pe protector](#pe-protector)
  - [unpacker](#unpacker)
  - [emulate code execution](#emulate-code-execution)
  - [pin](#pin)
  - [symbolic execution](#symbolic-execution)
  - [obfuscation](#obfuscation)
  - [deobfuscation](#deobfuscation)
  - [taint analyse](#taint-analyse)
  - [bin diff](#bin-diff)
  - [debugger](#debugger)
  - [x64dbg plugin](#x64dbg-plugin)
  - [live kernel debug](#live-kernel-debug)
  - [windbg plugin](#windbg-plugin)
  - [virtualkd](#virtualkd)
  - [ida script & plugin](#ida-script--plugin)
  - [ida sig maker](#ida-sig-maker)
  - [idapython](#idapython)
  - [pykd & FAQ](#pykd--faq)
  - [rpc](#rpc)
  - [hash dump](#hash-dump)
  - [auxiliary lib](#auxiliary-lib)
  - [ring3 nt api](#ring3-nt-api)
  - [winpcap](#winpcap)
  - [metasploit](#metasploit)
  - [shellcode generator](#shellcode-generator)
  - [shellcode encoder](#shellcode-encoder)
  - [shadow](#shadow)
  - [network lib](#network-lib)
  - [http](#http)
  - [https proxy](#https-proxy)
  - [sock proxy](#sock-proxy)
  - [reverse proxy](#reverse-proxy)
  - [mitm](#mitm)
  - [ssl](#ssl)
  - [json](#json)
  - [serialization](#serialization)
  - [awesome](#awesome)
  - [windows Driver Kit ddi (device driver interface) documentation](#windows-driver-kit-ddi-device-driver-interface-documentation)
  - [windbg preview & jsprovider](#windbg-preview--jsprovider)
  - [anti-anti-vm](#anti-anti-vm)
  - [vm](#vm)
  - [pe tool](#pe-tool)
  - [tools](#tools)
  - [post-exploitation](#post-exploitation)
  - [nsa security tools](#nsa-security-tools)
  - [apt](#apt)
  - [3rd party library](#3rd-party-library)
  - [adblock](#adblock)
  - [bypass uac](#bypass-uac)
  - [miscellaneous](#miscellaneous)
  - [slides](#slides)
  - [blogs](#blogs)
  - [sec tools](#sec-tools)
  - [waf](#waf)
  - [web security research site](#web-security-research-site)
  - [development documents](#development-documents)
  - [browser automated test](#browser-automated-test)
  - [docker](#docker)
  - [leaked source code](#leaked-source-code)
  - [sspi](#sspi)
  - [openssl](#openssl)
  - [pdb](#pdb)
  - [gpu](#gpu)
  - [crypto api](#crypto-api)
  - [ipc](#ipc)
  - [iot sec](#iot-sec)
  - [ascii banner](#ascii-banner)
  - [book code](#book-code)
  - [regex](#regex)
  - [paper](#paper)
  - [ebook](#ebook)
  - [ctf](#ctf)
  - [pentest](#pentest)
  - [wpad/pac](#wpadpac)
  - [javascript](#javascript)
  - [typescript](#typescript)
  - [js obfuscator/deobfuscator](#js-obfuscatordeobfuscator)
  - [js reverse engine](#js-reverse-engine)
  - [decompiler](#decompiler)
  - [encryption/decryption tools](#encryptiondecryption-tools)
  - [english](#english)
  - [downloader](#downloader)
  - [python](#python)
  - [golang](#golang)
  - [puppeteer](#puppeteer)
  - [java](#java)
  - [android](#android)
  - [android reverse engine](#android-reverse-engine)
  - [xposed](#xposed)
  - [Frida](#frida)
  - [library](#library)
  - [software collections](#software-collections)

## powershell

- github.com/rootclay/Powershell-Attack-Guide ![Github stars](https://shields.io/github/stars/rootclay/Powershell-Attack-Guide?style=social) ![Github forks](https://shields.io/github/forks/rootclay/Powershell-Attack-Guide?style=social) ![Github watchers](https://shields.io/github/watchers/rootclay/Powershell-Attack-Guide?style=social)

## pe file format

- github.com/corkami/pics ![Github stars](https://shields.io/github/stars/corkami/pics?style=social) ![Github forks](https://shields.io/github/forks/corkami/pics?style=social) ![Github watchers](https://shields.io/github/watchers/corkami/pics?style=social)

## asm ide

- github.com/ThomasJaeger/VisualMASM ![Github stars](https://shields.io/github/stars/ThomasJaeger/VisualMASM?style=social) ![Github forks](https://shields.io/github/forks/ThomasJaeger/VisualMASM?style=social) ![Github watchers](https://shields.io/github/watchers/ThomasJaeger/VisualMASM?style=social)
- github.com/Dman95/SASM ![Github stars](https://shields.io/github/stars/Dman95/SASM?style=social) ![Github forks](https://shields.io/github/forks/Dman95/SASM?style=social) ![Github watchers](https://shields.io/github/watchers/Dman95/SASM?style=social)
- github.com/mrfearless/UASM-with-RadASM ![Github stars](https://shields.io/github/stars/mrfearless/UASM-with-RadASM?style=social) ![Github forks](https://shields.io/github/forks/mrfearless/UASM-with-RadASM?style=social) ![Github watchers](https://shields.io/github/watchers/mrfearless/UASM-with-RadASM?style=social)

## meltdown/spectre poc

- github.com/turbo/KPTI-PoC-Collection ![Github stars](https://shields.io/github/stars/turbo/KPTI-PoC-Collection?style=social) ![Github forks](https://shields.io/github/forks/turbo/KPTI-PoC-Collection?style=social) ![Github watchers](https://shields.io/github/watchers/turbo/KPTI-PoC-Collection?style=social)
- github.com/gkaindl/meltdown-poc ![Github stars](https://shields.io/github/stars/gkaindl/meltdown-poc?style=social) ![Github forks](https://shields.io/github/forks/gkaindl/meltdown-poc?style=social) ![Github watchers](https://shields.io/github/watchers/gkaindl/meltdown-poc?style=social)
- github.com/feruxmax/meltdown ![Github stars](https://shields.io/github/stars/feruxmax/meltdown?style=social) ![Github forks](https://shields.io/github/forks/feruxmax/meltdown?style=social) ![Github watchers](https://shields.io/github/watchers/feruxmax/meltdown?style=social)
- github.com/Eugnis/spectre-attack ![Github stars](https://shields.io/github/stars/Eugnis/spectre-attack?style=social) ![Github forks](https://shields.io/github/forks/Eugnis/spectre-attack?style=social) ![Github watchers](https://shields.io/github/watchers/Eugnis/spectre-attack?style=social)

## lightweight c++ gui library

- github.com/Xoliper/ANGE ![Github stars](https://shields.io/github/stars/Xoliper/ANGE?style=social) ![Github forks](https://shields.io/github/forks/Xoliper/ANGE?style=social) ![Github watchers](https://shields.io/github/watchers/Xoliper/ANGE?style=social)
- github.com/iUIShop/LibUIDK (mfc skin ui) ![Github stars](https://shields.io/github/stars/iUIShop/LibUIDK?style=social) ![Github forks](https://shields.io/github/forks/iUIShop/LibUIDK?style=social) ![Github watchers](https://shields.io/github/watchers/iUIShop/LibUIDK?style=social)
- github.com/zlgopen/awtk ![Github stars](https://shields.io/github/stars/zlgopen/awtk?style=social) ![Github forks](https://shields.io/github/forks/zlgopen/awtk?style=social) ![Github watchers](https://shields.io/github/watchers/zlgopen/awtk?style=social)
- github.com/idea4good/GuiLite ![Github stars](https://shields.io/github/stars/idea4good/GuiLite?style=social) ![Github forks](https://shields.io/github/forks/idea4good/GuiLite?style=social) ![Github watchers](https://shields.io/github/watchers/idea4good/GuiLite?style=social)
- github.com/golang-ui/nuklear ![Github stars](https://shields.io/github/stars/golang-ui/nuklear?style=social) ![Github forks](https://shields.io/github/forks/golang-ui/nuklear?style=social) ![Github watchers](https://shields.io/github/watchers/golang-ui/nuklear?style=social)
- github.com/Dovyski/cvui ![Github stars](https://shields.io/github/stars/Dovyski/cvui?style=social) ![Github forks](https://shields.io/github/forks/Dovyski/cvui?style=social) ![Github watchers](https://shields.io/github/watchers/Dovyski/cvui?style=social)
- github.com/andlabs/libui ![Github stars](https://shields.io/github/stars/andlabs/libui?style=social) ![Github forks](https://shields.io/github/forks/andlabs/libui?style=social) ![Github watchers](https://shields.io/github/watchers/andlabs/libui?style=social)
- github.com/hasaranga/RFC-Framework ![Github stars](https://shields.io/github/stars/hasaranga/RFC-Framework?style=social) ![Github forks](https://shields.io/github/forks/hasaranga/RFC-Framework?style=social) ![Github watchers](https://shields.io/github/watchers/hasaranga/RFC-Framework?style=social)
- github.com/dustpg/LongUI ![Github stars](https://shields.io/github/stars/dustpg/LongUI?style=social) ![Github forks](https://shields.io/github/forks/dustpg/LongUI?style=social) ![Github watchers](https://shields.io/github/watchers/dustpg/LongUI?style=social)
- github.com/bognikol/Eleusis ![Github stars](https://shields.io/github/stars/bognikol/Eleusis?style=social) ![Github forks](https://shields.io/github/forks/bognikol/Eleusis?style=social) ![Github watchers](https://shields.io/github/watchers/bognikol/Eleusis?style=social)

## direct ui

- github.com/caozhiyi/DuiLib_c ![Github stars](https://shields.io/github/stars/caozhiyi/DuiLib_c?style=social) ![Github forks](https://shields.io/github/forks/caozhiyi/DuiLib_c?style=social) ![Github watchers](https://shields.io/github/watchers/caozhiyi/DuiLib_c?style=social)
- www.skinui.cn/
- www.showdoc.cc/skinui?page_id=135303
- help.5yyz.com/665984
- github.com/SOUI2/soui ![Github stars](https://shields.io/github/stars/SOUI2/soui?style=social) ![Github forks](https://shields.io/github/forks/SOUI2/soui?style=social) ![Github watchers](https://shields.io/github/watchers/SOUI2/soui?style=social)
- github.com/netease-im/NIM_Duilib_Framework ![Github stars](https://shields.io/github/stars/netease-im/NIM_Duilib_Framework?style=social) ![Github forks](https://shields.io/github/forks/netease-im/NIM_Duilib_Framework?style=social) ![Github watchers](https://shields.io/github/watchers/netease-im/NIM_Duilib_Framework?style=social)
- github.com/gclxry/EasyDuilib ![Github stars](https://shields.io/github/stars/gclxry/EasyDuilib?style=social) ![Github forks](https://shields.io/github/forks/gclxry/EasyDuilib?style=social) ![Github watchers](https://shields.io/github/watchers/gclxry/EasyDuilib?style=social)
- github.com/v-star0719/MFC_LogicalWnd ![Github stars](https://shields.io/github/stars/v-star0719/MFC_LogicalWnd?style=social) ![Github forks](https://shields.io/github/forks/v-star0719/MFC_LogicalWnd?style=social) ![Github watchers](https://shields.io/github/watchers/v-star0719/MFC_LogicalWnd?style=social)
- github.com/duzhi5368/FKDuiLibEditor ![Github stars](https://shields.io/github/stars/duzhi5368/FKDuiLibEditor?style=social) ![Github forks](https://shields.io/github/forks/duzhi5368/FKDuiLibEditor?style=social) ![Github watchers](https://shields.io/github/watchers/duzhi5368/FKDuiLibEditor?style=social)
- github.com/wanttobeno/bkuilib ![Github stars](https://shields.io/github/stars/wanttobeno/bkuilib?style=social) ![Github forks](https://shields.io/github/forks/wanttobeno/bkuilib?style=social) ![Github watchers](https://shields.io/github/watchers/wanttobeno/bkuilib?style=social)
- github.com/wanttobeno/XSkin1.0 ![Github stars](https://shields.io/github/stars/wanttobeno/XSkin1.0?style=social) ![Github forks](https://shields.io/github/forks/wanttobeno/XSkin1.0?style=social) ![Github watchers](https://shields.io/github/watchers/wanttobeno/XSkin1.0?style=social)
- github.com/idea4good/GuiLite ![Github stars](https://shields.io/github/stars/idea4good/GuiLite?style=social) ![Github forks](https://shields.io/github/forks/idea4good/GuiLite?style=social) ![Github watchers](https://shields.io/github/watchers/idea4good/GuiLite?style=social)
- github.com/redrains/DuiLib_Redrain ![Github stars](https://shields.io/github/stars/redrains/DuiLib_Redrain?style=social) ![Github forks](https://shields.io/github/forks/redrains/DuiLib_Redrain?style=social) ![Github watchers](https://shields.io/github/watchers/redrains/DuiLib_Redrain?style=social)
- github.com/wanttobeno/UIDesigner ![Github stars](https://shields.io/github/stars/wanttobeno/UIDesigner?style=social) ![Github forks](https://shields.io/github/forks/wanttobeno/UIDesigner?style=social) ![Github watchers](https://shields.io/github/watchers/wanttobeno/UIDesigner?style=social)
- github.com/zhongyang219/TrafficMonitor ![Github stars](https://shields.io/github/stars/zhongyang219/TrafficMonitor?style=social) ![Github forks](https://shields.io/github/forks/zhongyang219/TrafficMonitor?style=social) ![Github watchers](https://shields.io/github/watchers/zhongyang219/TrafficMonitor?style=social)
- github.com/wanttobeno/Duilib_Extension ![Github stars](https://shields.io/github/stars/wanttobeno/Duilib_Extension?style=social) ![Github forks](https://shields.io/github/forks/wanttobeno/Duilib_Extension?style=social) ![Github watchers](https://shields.io/github/watchers/wanttobeno/Duilib_Extension?style=social)
- github.com/zhongyang219/MusicPlayer2 ![Github stars](https://shields.io/github/stars/zhongyang219/MusicPlayer2?style=social) ![Github forks](https://shields.io/github/forks/zhongyang219/MusicPlayer2?style=social) ![Github watchers](https://shields.io/github/watchers/zhongyang219/MusicPlayer2?style=social)
- github.com/nmgwddj/duilib_tutorial ![Github stars](https://shields.io/github/stars/nmgwddj/duilib_tutorial?style=social) ![Github forks](https://shields.io/github/forks/nmgwddj/duilib_tutorial?style=social) ![Github watchers](https://shields.io/github/watchers/nmgwddj/duilib_tutorial?style=social)
- github.com/redrains/DuiLib_Redrain ![Github stars](https://shields.io/github/stars/redrains/DuiLib_Redrain?style=social) ![Github forks](https://shields.io/github/forks/redrains/DuiLib_Redrain?style=social) ![Github watchers](https://shields.io/github/watchers/redrains/DuiLib_Redrain?style=social)
- github.com/nmgwddj/InstallAssist ![Github stars](https://shields.io/github/stars/nmgwddj/InstallAssist?style=social) ![Github forks](https://shields.io/github/forks/nmgwddj/InstallAssist?style=social) ![Github watchers](https://shields.io/github/watchers/nmgwddj/InstallAssist?style=social)
- github.com/netease-im/NIM_PC_UIKit ![Github stars](https://shields.io/github/stars/netease-im/NIM_PC_UIKit?style=social) ![Github forks](https://shields.io/github/forks/netease-im/NIM_PC_UIKit?style=social) ![Github watchers](https://shields.io/github/watchers/netease-im/NIM_PC_UIKit?style=social)
- github.com/nmgwddj/Optimizer ![Github stars](https://shields.io/github/stars/nmgwddj/Optimizer?style=social) ![Github forks](https://shields.io/github/forks/nmgwddj/Optimizer?style=social) ![Github watchers](https://shields.io/github/watchers/nmgwddj/Optimizer?style=social)
- github.com/nmgwddj/BarPCMaster (netbar) ![Github stars](https://shields.io/github/stars/nmgwddj/BarPCMaster?style=social) ![Github forks](https://shields.io/github/forks/nmgwddj/BarPCMaster?style=social) ![Github watchers](https://shields.io/github/watchers/nmgwddj/BarPCMaster?style=social)

## chrome

- github.com/shuax/GreenChrome ![Github stars](https://shields.io/github/stars/shuax/GreenChrome?style=social) ![Github forks](https://shields.io/github/forks/shuax/GreenChrome?style=social) ![Github watchers](https://shields.io/github/watchers/shuax/GreenChrome?style=social)

## chrome Extension

- github.com/Tuhinshubhra/ExtAnalysis ![Github stars](https://shields.io/github/stars/Tuhinshubhra/ExtAnalysis?style=social) ![Github forks](https://shields.io/github/forks/Tuhinshubhra/ExtAnalysis?style=social) ![Github watchers](https://shields.io/github/watchers/Tuhinshubhra/ExtAnalysis?style=social)

## cef

- github.com/JelinYao/MyChrome ![Github stars](https://shields.io/github/stars/JelinYao/MyChrome?style=social) ![Github forks](https://shields.io/github/forks/JelinYao/MyChrome?style=social) ![Github watchers](https://shields.io/github/watchers/JelinYao/MyChrome?style=social)
- github.com/fanfeilong/cefutil ![Github stars](https://shields.io/github/stars/fanfeilong/cefutil?style=social) ![Github forks](https://shields.io/github/forks/fanfeilong/cefutil?style=social) ![Github watchers](https://shields.io/github/watchers/fanfeilong/cefutil?style=social)
- github.com/acristoffers/CEF3SimpleSample ![Github stars](https://shields.io/github/stars/acristoffers/CEF3SimpleSample?style=social) ![Github forks](https://shields.io/github/forks/acristoffers/CEF3SimpleSample?style=social) ![Github watchers](https://shields.io/github/watchers/acristoffers/CEF3SimpleSample?style=social)
- github.com/sanwer/Browser ![Github stars](https://shields.io/github/stars/sanwer/Browser?style=social) ![Github forks](https://shields.io/github/forks/sanwer/Browser?style=social) ![Github watchers](https://shields.io/github/watchers/sanwer/Browser?style=social)

## WebBrowser

- github.com/zhichao281/duilib-MiniBlinkBrowser ![Github stars](https://shields.io/github/stars/zhichao281/duilib-MiniBlinkBrowser?style=social) ![Github forks](https://shields.io/github/forks/zhichao281/duilib-MiniBlinkBrowser?style=social) ![Github watchers](https://shields.io/github/watchers/zhichao281/duilib-MiniBlinkBrowser?style=social)
- github.com/litehtml/litebrowser ![Github stars](https://shields.io/github/stars/litehtml/litebrowser?style=social) ![Github forks](https://shields.io/github/forks/litehtml/litebrowser?style=social) ![Github watchers](https://shields.io/github/watchers/litehtml/litebrowser?style=social)
- github.com/venam/Browser (lib) ![Github stars](https://shields.io/github/stars/venam/Browser?style=social) ![Github forks](https://shields.io/github/forks/venam/Browser?style=social) ![Github watchers](https://shields.io/github/watchers/venam/Browser?style=social)
- github.com/wanttobeno/Study_IWebBrowser2 ![Github stars](https://shields.io/github/stars/wanttobeno/Study_IWebBrowser2?style=social) ![Github forks](https://shields.io/github/forks/wanttobeno/Study_IWebBrowser2?style=social) ![Github watchers](https://shields.io/github/watchers/wanttobeno/Study_IWebBrowser2?style=social)

## d3d

- github.com/QianMo/Direct3D-Win32-Book-Src-Code ![Github stars](https://shields.io/github/stars/QianMo/Direct3D-Win32-Book-Src-Code?style=social) ![Github forks](https://shields.io/github/forks/QianMo/Direct3D-Win32-Book-Src-Code?style=social) ![Github watchers](https://shields.io/github/watchers/QianMo/Direct3D-Win32-Book-Src-Code?style=social)
- github.com/MKXJun/DirectX11-With-Windows-SDK ![Github stars](https://shields.io/github/stars/MKXJun/DirectX11-With-Windows-SDK?style=social) ![Github forks](https://shields.io/github/forks/MKXJun/DirectX11-With-Windows-SDK?style=social) ![Github watchers](https://shields.io/github/watchers/MKXJun/DirectX11-With-Windows-SDK?style=social)
- github.com/ThirteenAG/d3d9-wrapper ![Github stars](https://shields.io/github/stars/ThirteenAG/d3d9-wrapper?style=social) ![Github forks](https://shields.io/github/forks/ThirteenAG/d3d9-wrapper?style=social) ![Github watchers](https://shields.io/github/watchers/ThirteenAG/d3d9-wrapper?style=social)

## opencv

- github.com/JimmyHHua/opencv_tutorials ![Github stars](https://shields.io/github/stars/JimmyHHua/opencv_tutorials?style=social) ![Github forks](https://shields.io/github/forks/JimmyHHua/opencv_tutorials?style=social) ![Github watchers](https://shields.io/github/watchers/JimmyHHua/opencv_tutorials?style=social)

## bass

- github.com/r10s/BASS_VST ![Github stars](https://shields.io/github/stars/r10s/BASS_VST?style=social) ![Github forks](https://shields.io/github/forks/r10s/BASS_VST?style=social) ![Github watchers](https://shields.io/github/watchers/r10s/BASS_VST?style=social)

## lua

- github.com/vinniefalco/LuaBridge ![Github stars](https://shields.io/github/stars/vinniefalco/LuaBridge?style=social) ![Github forks](https://shields.io/github/forks/vinniefalco/LuaBridge?style=social) ![Github watchers](https://shields.io/github/watchers/vinniefalco/LuaBridge?style=social)

## c++ 11/14/17/20

- github.com/0voice/cpp_new_features ![Github stars](https://shields.io/github/stars/0voice/cpp_new_features?style=social) ![Github forks](https://shields.io/github/forks/0voice/cpp_new_features?style=social) ![Github watchers](https://shields.io/github/watchers/0voice/cpp_new_features?style=social)
- github.com/akkaze/ThreadPool ![Github stars](https://shields.io/github/stars/akkaze/ThreadPool?style=social) ![Github forks](https://shields.io/github/forks/akkaze/ThreadPool?style=social) ![Github watchers](https://shields.io/github/watchers/akkaze/ThreadPool?style=social)
- github.com/xiaoweiChen/CPP-Concurrency-In-Action-2ed-2019 ![Github stars](https://shields.io/github/stars/xiaoweiChen/CPP-Concurrency-In-Action-2ed-2019?style=social) ![Github forks](https://shields.io/github/forks/xiaoweiChen/CPP-Concurrency-In-Action-2ed-2019?style=social) ![Github watchers](https://shields.io/github/watchers/xiaoweiChen/CPP-Concurrency-In-Action-2ed-2019?style=social)
- github.com/xiaoweiChen/CPP-17-STL-cookbook ![Github stars](https://shields.io/github/stars/xiaoweiChen/CPP-17-STL-cookbook?style=social) ![Github forks](https://shields.io/github/forks/xiaoweiChen/CPP-17-STL-cookbook?style=social) ![Github watchers](https://shields.io/github/watchers/xiaoweiChen/CPP-17-STL-cookbook?style=social)
- github.com/changkun/modern-cpp-tutorial ![Github stars](https://shields.io/github/stars/changkun/modern-cpp-tutorial?style=social) ![Github forks](https://shields.io/github/forks/changkun/modern-cpp-tutorial?style=social) ![Github watchers](https://shields.io/github/watchers/changkun/modern-cpp-tutorial?style=social)

## cmake

- github.com/xiaoweiChen/CMake-Cookbook ![Github stars](https://shields.io/github/stars/xiaoweiChen/CMake-Cookbook?style=social) ![Github forks](https://shields.io/github/forks/xiaoweiChen/CMake-Cookbook?style=social) ![Github watchers](https://shields.io/github/watchers/xiaoweiChen/CMake-Cookbook?style=social)

## DesignPattern

- design-patterns.readthedocs.io/zh_CN/latest/index.html
- github.com/Waleon/DesignPatterns ![Github stars](https://shields.io/github/stars/Waleon/DesignPatterns?style=social) ![Github forks](https://shields.io/github/forks/Waleon/DesignPatterns?style=social) ![Github watchers](https://shields.io/github/watchers/Waleon/DesignPatterns?style=social)
- github.com/GoodmanTao/DesignPatternInC ![Github stars](https://shields.io/github/stars/GoodmanTao/DesignPatternInC?style=social) ![Github forks](https://shields.io/github/forks/GoodmanTao/DesignPatternInC?style=social) ![Github watchers](https://shields.io/github/watchers/GoodmanTao/DesignPatternInC?style=social)

## c++ & js

- github.com/xhawk18/promise-cpp ![Github stars](https://shields.io/github/stars/xhawk18/promise-cpp?style=social) ![Github forks](https://shields.io/github/forks/xhawk18/promise-cpp?style=social) ![Github watchers](https://shields.io/github/watchers/xhawk18/promise-cpp?style=social)
- github.com/panopticoncentral/jsrt-wrappers ![Github stars](https://shields.io/github/stars/panopticoncentral/jsrt-wrappers?style=social) ![Github forks](https://shields.io/github/forks/panopticoncentral/jsrt-wrappers?style=social) ![Github watchers](https://shields.io/github/watchers/panopticoncentral/jsrt-wrappers?style=social)
- github.com/wargio/WSH-Framework ![Github stars](https://shields.io/github/stars/wargio/WSH-Framework?style=social) ![Github forks](https://shields.io/github/forks/wargio/WSH-Framework?style=social) ![Github watchers](https://shields.io/github/watchers/wargio/WSH-Framework?style=social)
- github.com/ExpLife0011/WebBrowser ![Github stars](https://shields.io/github/stars/ExpLife0011/WebBrowser?style=social) ![Github forks](https://shields.io/github/forks/ExpLife0011/WebBrowser?style=social) ![Github watchers](https://shields.io/github/watchers/ExpLife0011/WebBrowser?style=social)
- github.com/wanttobeno/Study_mujs ![Github stars](https://shields.io/github/stars/wanttobeno/Study_mujs?style=social) ![Github forks](https://shields.io/github/forks/wanttobeno/Study_mujs?style=social) ![Github watchers](https://shields.io/github/watchers/wanttobeno/Study_mujs?style=social)

## gdi/gdi+

- www.mctrl.org/ (win32 control lib)
- github.com/wanttobeno/AlphaEditor ![Github stars](https://shields.io/github/stars/wanttobeno/AlphaEditor?style=social) ![Github forks](https://shields.io/github/forks/wanttobeno/AlphaEditor?style=social) ![Github watchers](https://shields.io/github/watchers/wanttobeno/AlphaEditor?style=social)
- github.com/wanttobeno/FastZoomDemo (zoom) ![Github stars](https://shields.io/github/stars/wanttobeno/FastZoomDemo?style=social) ![Github forks](https://shields.io/github/forks/wanttobeno/FastZoomDemo?style=social) ![Github watchers](https://shields.io/github/watchers/wanttobeno/FastZoomDemo?style=social)
- github.com/wanttobeno/GdiPlusTextEffect ![Github stars](https://shields.io/github/stars/wanttobeno/GdiPlusTextEffect?style=social) ![Github forks](https://shields.io/github/forks/wanttobeno/GdiPlusTextEffect?style=social) ![Github watchers](https://shields.io/github/watchers/wanttobeno/GdiPlusTextEffect?style=social)
- github.com/wanttobeno/GdiPlusString ![Github stars](https://shields.io/github/stars/wanttobeno/GdiPlusString?style=social) ![Github forks](https://shields.io/github/forks/wanttobeno/GdiPlusString?style=social) ![Github watchers](https://shields.io/github/watchers/wanttobeno/GdiPlusString?style=social)
- github.com/wanttobeno/WindowFinder ![Github stars](https://shields.io/github/stars/wanttobeno/WindowFinder?style=social) ![Github forks](https://shields.io/github/forks/wanttobeno/WindowFinder?style=social) ![Github watchers](https://shields.io/github/watchers/wanttobeno/WindowFinder?style=social)
- github.com/wanttobeno/ymagine ![Github stars](https://shields.io/github/stars/wanttobeno/ymagine?style=social) ![Github forks](https://shields.io/github/forks/wanttobeno/ymagine?style=social) ![Github watchers](https://shields.io/github/watchers/wanttobeno/ymagine?style=social)
- github.com/wanttobeno/levels-adjustment ![Github stars](https://shields.io/github/stars/wanttobeno/levels-adjustment?style=social) ![Github forks](https://shields.io/github/forks/wanttobeno/levels-adjustment?style=social) ![Github watchers](https://shields.io/github/watchers/wanttobeno/levels-adjustment?style=social)
- github.com/wanttobeno/ElipsePic ![Github stars](https://shields.io/github/stars/wanttobeno/ElipsePic?style=social) ![Github forks](https://shields.io/github/forks/wanttobeno/ElipsePic?style=social) ![Github watchers](https://shields.io/github/watchers/wanttobeno/ElipsePic?style=social)
- github.com/wanttobeno/windows-effect ![Github stars](https://shields.io/github/stars/wanttobeno/windows-effect?style=social) ![Github forks](https://shields.io/github/forks/wanttobeno/windows-effect?style=social) ![Github watchers](https://shields.io/github/watchers/wanttobeno/windows-effect?style=social)
- github.com/wanttobeno/Study_easing_animation ![Github stars](https://shields.io/github/stars/wanttobeno/Study_easing_animation?style=social) ![Github forks](https://shields.io/github/forks/wanttobeno/Study_easing_animation?style=social) ![Github watchers](https://shields.io/github/watchers/wanttobeno/Study_easing_animation?style=social)
- github.com/wanttobeno/Study_FindPicAlgorithm (find picture algorithm) ![Github stars](https://shields.io/github/stars/wanttobeno/Study_FindPicAlgorithm?style=social) ![Github forks](https://shields.io/github/forks/wanttobeno/Study_FindPicAlgorithm?style=social) ![Github watchers](https://shields.io/github/watchers/wanttobeno/Study_FindPicAlgorithm?style=social)
- github.com/wanttobeno/Window_GlassIntro_demo ![Github stars](https://shields.io/github/stars/wanttobeno/Window_GlassIntro_demo?style=social) ![Github forks](https://shields.io/github/forks/wanttobeno/Window_GlassIntro_demo?style=social) ![Github watchers](https://shields.io/github/watchers/wanttobeno/Window_GlassIntro_demo?style=social)

## QT

- github.com/ShowFL/Toou-2D ![Github stars](https://shields.io/github/stars/ShowFL/Toou-2D?style=social) ![Github forks](https://shields.io/github/forks/ShowFL/Toou-2D?style=social) ![Github watchers](https://shields.io/github/watchers/ShowFL/Toou-2D?style=social)
- github.com/jaredtao/TaoQuick ![Github stars](https://shields.io/github/stars/jaredtao/TaoQuick?style=social) ![Github forks](https://shields.io/github/forks/jaredtao/TaoQuick?style=social) ![Github watchers](https://shields.io/github/watchers/jaredtao/TaoQuick?style=social)
- github.com/feiyangqingyun/qucsdk ![Github stars](https://shields.io/github/stars/feiyangqingyun/qucsdk?style=social) ![Github forks](https://shields.io/github/forks/feiyangqingyun/qucsdk?style=social) ![Github watchers](https://shields.io/github/watchers/feiyangqingyun/qucsdk?style=social)
- github.com/feiyangqingyun/QWidgetDemo ![Github stars](https://shields.io/github/stars/feiyangqingyun/QWidgetDemo?style=social) ![Github forks](https://shields.io/github/forks/feiyangqingyun/QWidgetDemo?style=social) ![Github watchers](https://shields.io/github/watchers/feiyangqingyun/QWidgetDemo?style=social)
- github.com/feiyangqingyun/qtkaifajingyan ![Github stars](https://shields.io/github/stars/feiyangqingyun/qtkaifajingyan?style=social) ![Github forks](https://shields.io/github/forks/feiyangqingyun/qtkaifajingyan?style=social) ![Github watchers](https://shields.io/github/watchers/feiyangqingyun/qtkaifajingyan?style=social)
- github.com/feiyangqingyun/QWidgetExe ![Github stars](https://shields.io/github/stars/feiyangqingyun/QWidgetExe?style=social) ![Github forks](https://shields.io/github/forks/feiyangqingyun/QWidgetExe?style=social) ![Github watchers](https://shields.io/github/watchers/feiyangqingyun/QWidgetExe?style=social)

## computer vision & machine learning

- github.com/wanttobeno/sod ![Github stars](https://shields.io/github/stars/wanttobeno/sod?style=social) ![Github forks](https://shields.io/github/forks/wanttobeno/sod?style=social) ![Github watchers](https://shields.io/github/watchers/wanttobeno/sod?style=social)

## compress

- github.com/wanttobeno/snappy ![Github stars](https://shields.io/github/stars/wanttobeno/snappy?style=social) ![Github forks](https://shields.io/github/forks/wanttobeno/snappy?style=social) ![Github watchers](https://shields.io/github/watchers/wanttobeno/snappy?style=social)

## Dongle

- github.com/wanttobeno/Dongle ![Github stars](https://shields.io/github/stars/wanttobeno/Dongle?style=social) ![Github forks](https://shields.io/github/forks/wanttobeno/Dongle?style=social) ![Github watchers](https://shields.io/github/watchers/wanttobeno/Dongle?style=social)

## spy++

- github.com/wjx0912/MySpy ![Github stars](https://shields.io/github/stars/wjx0912/MySpy?style=social) ![Github forks](https://shields.io/github/forks/wjx0912/MySpy?style=social) ![Github watchers](https://shields.io/github/watchers/wjx0912/MySpy?style=social)

## Shell Extension for Windows Explorer

- github.com/derceg/explorerplusplus ![Github stars](https://shields.io/github/stars/derceg/explorerplusplus?style=social) ![Github forks](https://shields.io/github/forks/derceg/explorerplusplus?style=social) ![Github watchers](https://shields.io/github/watchers/derceg/explorerplusplus?style=social)
- github.com/XhmikosR/perfmonbar (perfmonbar) ![Github stars](https://shields.io/github/stars/XhmikosR/perfmonbar?style=social) ![Github forks](https://shields.io/github/forks/XhmikosR/perfmonbar?style=social) ![Github watchers](https://shields.io/github/watchers/XhmikosR/perfmonbar?style=social)
- github.com/abhimanyusirohi/ThumbFish (nice demo) ![Github stars](https://shields.io/github/stars/abhimanyusirohi/ThumbFish?style=social) ![Github forks](https://shields.io/github/forks/abhimanyusirohi/ThumbFish?style=social) ![Github watchers](https://shields.io/github/watchers/abhimanyusirohi/ThumbFish?style=social)
- github.com/matssigge/JASE ![Github stars](https://shields.io/github/stars/matssigge/JASE?style=social) ![Github forks](https://shields.io/github/forks/matssigge/JASE?style=social) ![Github watchers](https://shields.io/github/watchers/matssigge/JASE?style=social)
- github.com/Oeffner/MtzExtInfoTip ![Github stars](https://shields.io/github/stars/Oeffner/MtzExtInfoTip?style=social) ![Github forks](https://shields.io/github/forks/Oeffner/MtzExtInfoTip?style=social) ![Github watchers](https://shields.io/github/watchers/Oeffner/MtzExtInfoTip?style=social)
- github.com/danielgrigg/ContextMenuDemo ![Github stars](https://shields.io/github/stars/danielgrigg/ContextMenuDemo?style=social) ![Github forks](https://shields.io/github/forks/danielgrigg/ContextMenuDemo?style=social) ![Github watchers](https://shields.io/github/watchers/danielgrigg/ContextMenuDemo?style=social)
- github.com/monolithpl/stexbar ![Github stars](https://shields.io/github/stars/monolithpl/stexbar?style=social) ![Github forks](https://shields.io/github/forks/monolithpl/stexbar?style=social) ![Github watchers](https://shields.io/github/watchers/monolithpl/stexbar?style=social)
- github.com/CaSchmidt/csMenu ![Github stars](https://shields.io/github/stars/CaSchmidt/csMenu?style=social) ![Github forks](https://shields.io/github/forks/CaSchmidt/csMenu?style=social) ![Github watchers](https://shields.io/github/watchers/CaSchmidt/csMenu?style=social)
- github.com/blndev/ExplorerUtilitys ![Github stars](https://shields.io/github/stars/blndev/ExplorerUtilitys?style=social) ![Github forks](https://shields.io/github/forks/blndev/ExplorerUtilitys?style=social) ![Github watchers](https://shields.io/github/watchers/blndev/ExplorerUtilitys?style=social)
- github.com/pke/Windows-Explorer-OSGi-Shell-Extensions ![Github stars](https://shields.io/github/stars/pke/Windows-Explorer-OSGi-Shell-Extensions?style=social) ![Github forks](https://shields.io/github/forks/pke/Windows-Explorer-OSGi-Shell-Extensions?style=social) ![Github watchers](https://shields.io/github/watchers/pke/Windows-Explorer-OSGi-Shell-Extensions?style=social)
- github.com/Anton-V-K/MultiThumbExtension ![Github stars](https://shields.io/github/stars/Anton-V-K/MultiThumbExtension?style=social) ![Github forks](https://shields.io/github/forks/Anton-V-K/MultiThumbExtension?style=social) ![Github watchers](https://shields.io/github/watchers/Anton-V-K/MultiThumbExtension?style=social)
- github.com/0ffffffffh/ffmpegShellExtension ![Github stars](https://shields.io/github/stars/0ffffffffh/ffmpegShellExtension?style=social) ![Github forks](https://shields.io/github/forks/0ffffffffh/ffmpegShellExtension?style=social) ![Github watchers](https://shields.io/github/watchers/0ffffffffh/ffmpegShellExtension?style=social)
- github.com/Ralph-Lee/WinShellExt ![Github stars](https://shields.io/github/stars/Ralph-Lee/WinShellExt?style=social) ![Github forks](https://shields.io/github/forks/Ralph-Lee/WinShellExt?style=social) ![Github watchers](https://shields.io/github/watchers/Ralph-Lee/WinShellExt?style=social)
- github.com/slivermeteor/LockKeys ![Github stars](https://shields.io/github/stars/slivermeteor/LockKeys?style=social) ![Github forks](https://shields.io/github/forks/slivermeteor/LockKeys?style=social) ![Github watchers](https://shields.io/github/watchers/slivermeteor/LockKeys?style=social)
- github.com/alexandermenze/ShellExtensionInfoTip ![Github stars](https://shields.io/github/stars/alexandermenze/ShellExtensionInfoTip?style=social) ![Github forks](https://shields.io/github/forks/alexandermenze/ShellExtensionInfoTip?style=social) ![Github watchers](https://shields.io/github/watchers/alexandermenze/ShellExtensionInfoTip?style=social)
- github.com/jbrandwood/EditWith ![Github stars](https://shields.io/github/stars/jbrandwood/EditWith?style=social) ![Github forks](https://shields.io/github/forks/jbrandwood/EditWith?style=social) ![Github watchers](https://shields.io/github/watchers/jbrandwood/EditWith?style=social)
- github.com/calzakk/CyoHash ![Github stars](https://shields.io/github/stars/calzakk/CyoHash?style=social) ![Github forks](https://shields.io/github/forks/calzakk/CyoHash?style=social) ![Github watchers](https://shields.io/github/watchers/calzakk/CyoHash?style=social)
- github.com/asa75asa/ImageResizer ![Github stars](https://shields.io/github/stars/asa75asa/ImageResizer?style=social) ![Github forks](https://shields.io/github/forks/asa75asa/ImageResizer?style=social) ![Github watchers](https://shields.io/github/watchers/asa75asa/ImageResizer?style=social)
- github.com/tillig/JunctionShellExtensions ![Github stars](https://shields.io/github/stars/tillig/JunctionShellExtensions?style=social) ![Github forks](https://shields.io/github/forks/tillig/JunctionShellExtensions?style=social) ![Github watchers](https://shields.io/github/watchers/tillig/JunctionShellExtensions?style=social)
- github.com/keybase/KBShellExt ![Github stars](https://shields.io/github/stars/keybase/KBShellExt?style=social) ![Github forks](https://shields.io/github/forks/keybase/KBShellExt?style=social) ![Github watchers](https://shields.io/github/watchers/keybase/KBShellExt?style=social)
- github.com/T800G/StatusBar7 ![Github stars](https://shields.io/github/stars/T800G/StatusBar7?style=social) ![Github forks](https://shields.io/github/forks/T800G/StatusBar7?style=social) ![Github watchers](https://shields.io/github/watchers/T800G/StatusBar7?style=social)
- github.com/vladm3/ShellExtension ![Github stars](https://shields.io/github/stars/vladm3/ShellExtension?style=social) ![Github forks](https://shields.io/github/forks/vladm3/ShellExtension?style=social) ![Github watchers](https://shields.io/github/watchers/vladm3/ShellExtension?style=social)
- github.com/sop/cygextreg ![Github stars](https://shields.io/github/stars/sop/cygextreg?style=social) ![Github forks](https://shields.io/github/forks/sop/cygextreg?style=social) ![Github watchers](https://shields.io/github/watchers/sop/cygextreg?style=social)
- github.com/AndreasVerhoeven/HTMLPreviewShellExtension ![Github stars](https://shields.io/github/stars/AndreasVerhoeven/HTMLPreviewShellExtension?style=social) ![Github forks](https://shields.io/github/forks/AndreasVerhoeven/HTMLPreviewShellExtension?style=social) ![Github watchers](https://shields.io/github/watchers/AndreasVerhoeven/HTMLPreviewShellExtension?style=social)
- github.com/alvinhochun/KritaShellExtension ![Github stars](https://shields.io/github/stars/alvinhochun/KritaShellExtension?style=social) ![Github forks](https://shields.io/github/forks/alvinhochun/KritaShellExtension?style=social) ![Github watchers](https://shields.io/github/watchers/alvinhochun/KritaShellExtension?style=social)
- github.com/AUTOMATIC1111/3ds-shell ![Github stars](https://shields.io/github/stars/AUTOMATIC1111/3ds-shell?style=social) ![Github forks](https://shields.io/github/forks/AUTOMATIC1111/3ds-shell?style=social) ![Github watchers](https://shields.io/github/watchers/AUTOMATIC1111/3ds-shell?style=social)
- github.com/google/google-drive-shell-extension ![Github stars](https://shields.io/github/stars/google/google-drive-shell-extension?style=social) ![Github forks](https://shields.io/github/forks/google/google-drive-shell-extension?style=social) ![Github watchers](https://shields.io/github/watchers/google/google-drive-shell-extension?style=social)
- github.com/TortoiseGit/TortoiseGit ![Github stars](https://shields.io/github/stars/TortoiseGit/TortoiseGit?style=social) ![Github forks](https://shields.io/github/forks/TortoiseGit/TortoiseGit?style=social) ![Github watchers](https://shields.io/github/watchers/TortoiseGit/TortoiseGit?style=social)
- github.com/sanje2v/MantaPropertyExtension ![Github stars](https://shields.io/github/stars/sanje2v/MantaPropertyExtension?style=social) ![Github forks](https://shields.io/github/forks/sanje2v/MantaPropertyExtension?style=social) ![Github watchers](https://shields.io/github/watchers/sanje2v/MantaPropertyExtension?style=social)
- github.com/phwitti/cmdhere ![Github stars](https://shields.io/github/stars/phwitti/cmdhere?style=social) ![Github forks](https://shields.io/github/forks/phwitti/cmdhere?style=social) ![Github watchers](https://shields.io/github/watchers/phwitti/cmdhere?style=social)

## windows system programming

- github.com/dengqizhou30/AIAssistC ![Github stars](https://shields.io/github/stars/dengqizhou30/AIAssistC?style=social) ![Github forks](https://shields.io/github/forks/dengqizhou30/AIAssistC?style=social) ![Github watchers](https://shields.io/github/watchers/dengqizhou30/AIAssistC?style=social)
- github.com/solemnwarning/rehex (hex editor) ![Github stars](https://shields.io/github/stars/solemnwarning/rehex?style=social) ![Github forks](https://shields.io/github/forks/solemnwarning/rehex?style=social) ![Github watchers](https://shields.io/github/watchers/solemnwarning/rehex?style=social)
- github.com/progmboy/openprocmon (procmon) ![Github stars](https://shields.io/github/stars/progmboy/openprocmon?style=social) ![Github forks](https://shields.io/github/forks/progmboy/openprocmon?style=social) ![Github watchers](https://shields.io/github/watchers/progmboy/openprocmon?style=social)
- github.com/ezrealik/AI-Icarus (AI iflytek SDK) ![Github stars](https://shields.io/github/stars/ezrealik/AI-Icarus?style=social) ![Github forks](https://shields.io/github/forks/ezrealik/AI-Icarus?style=social) ![Github watchers](https://shields.io/github/watchers/ezrealik/AI-Icarus?style=social)
- rufus.ie/ (Create bootable USB drives the easy way)
- github.com/emmanuel-marty/em_inflate (Fast, small, in-memory inflate (zlib, deflate and gzip decompression)) ![Github stars](https://shields.io/github/stars/emmanuel-marty/em_inflate?style=social) ![Github forks](https://shields.io/github/forks/emmanuel-marty/em_inflate?style=social) ![Github watchers](https://shields.io/github/watchers/emmanuel-marty/em_inflate?style=social)
- github.com/skadro-official/skCrypter (string crypt) ![Github stars](https://shields.io/github/stars/skadro-official/skCrypter?style=social) ![Github forks](https://shields.io/github/forks/skadro-official/skCrypter?style=social) ![Github watchers](https://shields.io/github/watchers/skadro-official/skCrypter?style=social)
- github.com/hynninen/win-pbkdf2 ![Github stars](https://shields.io/github/stars/hynninen/win-pbkdf2?style=social) ![Github forks](https://shields.io/github/forks/hynninen/win-pbkdf2?style=social) ![Github watchers](https://shields.io/github/watchers/hynninen/win-pbkdf2?style=social)
- github.com/K0rz3n/PatchesTester (check system patch info) ![Github stars](https://shields.io/github/stars/K0rz3n/PatchesTester?style=social) ![Github forks](https://shields.io/github/forks/K0rz3n/PatchesTester?style=social) ![Github watchers](https://shields.io/github/watchers/K0rz3n/PatchesTester?style=social)
- github.com/nccgroup/WindowsJobLock (Windows Process Lockdown Tool using Job Objects) ![Github stars](https://shields.io/github/stars/nccgroup/WindowsJobLock?style=social) ![Github forks](https://shields.io/github/forks/nccgroup/WindowsJobLock?style=social) ![Github watchers](https://shields.io/github/watchers/nccgroup/WindowsJobLock?style=social)
- github.com/long123king/TokenInsight ![Github stars](https://shields.io/github/stars/long123king/TokenInsight?style=social) ![Github forks](https://shields.io/github/forks/long123king/TokenInsight?style=social) ![Github watchers](https://shields.io/github/watchers/long123king/TokenInsight?style=social)
- github.com/btbd/access (Access without a real handle) ![Github stars](https://shields.io/github/stars/btbd/access?style=social) ![Github forks](https://shields.io/github/forks/btbd/access?style=social) ![Github watchers](https://shields.io/github/watchers/btbd/access?style=social)
- github.com/CoatiSoftware/Sourcetrail (Source code explorer) ![Github stars](https://shields.io/github/stars/CoatiSoftware/Sourcetrail?style=social) ![Github forks](https://shields.io/github/forks/CoatiSoftware/Sourcetrail?style=social) ![Github watchers](https://shields.io/github/watchers/CoatiSoftware/Sourcetrail?style=social)
- github.com/DoubleLabyrinth/WindowsSudo ![Github stars](https://shields.io/github/stars/DoubleLabyrinth/WindowsSudo?style=social) ![Github forks](https://shields.io/github/forks/DoubleLabyrinth/WindowsSudo?style=social) ![Github watchers](https://shields.io/github/watchers/DoubleLabyrinth/WindowsSudo?style=social)
- github.com/AzureGreen/NetView ![Github stars](https://shields.io/github/stars/AzureGreen/NetView?style=social) ![Github forks](https://shields.io/github/forks/AzureGreen/NetView?style=social) ![Github watchers](https://shields.io/github/watchers/AzureGreen/NetView?style=social)
- github.com/MFCer/AutoUpdate ![Github stars](https://shields.io/github/stars/MFCer/AutoUpdate?style=social) ![Github forks](https://shields.io/github/forks/MFCer/AutoUpdate?style=social) ![Github watchers](https://shields.io/github/watchers/MFCer/AutoUpdate?style=social)
- github.com/ufrisk/LeechCore (Physical Memory Acquisition Library) ![Github stars](https://shields.io/github/stars/ufrisk/LeechCore?style=social) ![Github forks](https://shields.io/github/forks/ufrisk/LeechCore?style=social) ![Github watchers](https://shields.io/github/watchers/ufrisk/LeechCore?style=social)
- github.com/marcosd4h/sysmonx ![Github stars](https://shields.io/github/stars/marcosd4h/sysmonx?style=social) ![Github forks](https://shields.io/github/forks/marcosd4h/sysmonx?style=social) ![Github watchers](https://shields.io/github/watchers/marcosd4h/sysmonx?style=social)
- github.com/Dankirk/RegSLScan ![Github stars](https://shields.io/github/stars/Dankirk/RegSLScan?style=social) ![Github forks](https://shields.io/github/forks/Dankirk/RegSLScan?style=social) ![Github watchers](https://shields.io/github/watchers/Dankirk/RegSLScan?style=social)
- github.com/nogginware/mstscdump ![Github stars](https://shields.io/github/stars/nogginware/mstscdump?style=social) ![Github forks](https://shields.io/github/forks/nogginware/mstscdump?style=social) ![Github watchers](https://shields.io/github/watchers/nogginware/mstscdump?style=social)
- github.com/zodiacon/ApiSetView ![Github stars](https://shields.io/github/stars/zodiacon/ApiSetView?style=social) ![Github forks](https://shields.io/github/forks/zodiacon/ApiSetView?style=social) ![Github watchers](https://shields.io/github/watchers/zodiacon/ApiSetView?style=social)
- github.com/DOGSHITD/SciDetectorApp (SCI) ![Github stars](https://shields.io/github/stars/DOGSHITD/SciDetectorApp?style=social) ![Github forks](https://shields.io/github/forks/DOGSHITD/SciDetectorApp?style=social) ![Github watchers](https://shields.io/github/watchers/DOGSHITD/SciDetectorApp?style=social)
- github.com/DOGSHITD/AcpiTool (ACPI) ![Github stars](https://shields.io/github/stars/DOGSHITD/AcpiTool?style=social) ![Github forks](https://shields.io/github/forks/DOGSHITD/AcpiTool?style=social) ![Github watchers](https://shields.io/github/watchers/DOGSHITD/AcpiTool?style=social)
- github.com/VertexToEdge/WindowFunctionTracer ![Github stars](https://shields.io/github/stars/VertexToEdge/WindowFunctionTracer?style=social) ![Github forks](https://shields.io/github/forks/VertexToEdge/WindowFunctionTracer?style=social) ![Github watchers](https://shields.io/github/watchers/VertexToEdge/WindowFunctionTracer?style=social)
- github.com/sganis/golddrive ![Github stars](https://shields.io/github/stars/sganis/golddrive?style=social) ![Github forks](https://shields.io/github/forks/sganis/golddrive?style=social) ![Github watchers](https://shields.io/github/watchers/sganis/golddrive?style=social)
- github.com/yanncam/exe2powershell ![Github stars](https://shields.io/github/stars/yanncam/exe2powershell?style=social) ![Github forks](https://shields.io/github/forks/yanncam/exe2powershell?style=social) ![Github watchers](https://shields.io/github/watchers/yanncam/exe2powershell?style=social)
- github.com/owodelta/coilgun (Direct API Calling) ![Github stars](https://shields.io/github/stars/owodelta/coilgun?style=social) ![Github forks](https://shields.io/github/forks/owodelta/coilgun?style=social) ![Github watchers](https://shields.io/github/watchers/owodelta/coilgun?style=social)
- github.com/NYAN-x-CAT/Disable-Windows-Defender ![Github stars](https://shields.io/github/stars/NYAN-x-CAT/Disable-Windows-Defender?style=social) ![Github forks](https://shields.io/github/forks/NYAN-x-CAT/Disable-Windows-Defender?style=social) ![Github watchers](https://shields.io/github/watchers/NYAN-x-CAT/Disable-Windows-Defender?style=social)
- github.com/d35ha/CallObfuscator ![Github stars](https://shields.io/github/stars/d35ha/CallObfuscator?style=social) ![Github forks](https://shields.io/github/forks/d35ha/CallObfuscator?style=social) ![Github watchers](https://shields.io/github/watchers/d35ha/CallObfuscator?style=social)
- github.com/zodiacon/RegEditX ![Github stars](https://shields.io/github/stars/zodiacon/RegEditX?style=social) ![Github forks](https://shields.io/github/forks/zodiacon/RegEditX?style=social) ![Github watchers](https://shields.io/github/watchers/zodiacon/RegEditX?style=social)
- github.com/ZhanLang/jcfs (everything) ![Github stars](https://shields.io/github/stars/ZhanLang/jcfs?style=social) ![Github forks](https://shields.io/github/forks/ZhanLang/jcfs?style=social) ![Github watchers](https://shields.io/github/watchers/ZhanLang/jcfs?style=social)
- github.com/ZhanLang/msdk (sdk) ![Github stars](https://shields.io/github/stars/ZhanLang/msdk?style=social) ![Github forks](https://shields.io/github/forks/ZhanLang/msdk?style=social) ![Github watchers](https://shields.io/github/watchers/ZhanLang/msdk?style=social)
- github.com/MiroKaku/ConMon ![Github stars](https://shields.io/github/stars/MiroKaku/ConMon?style=social) ![Github forks](https://shields.io/github/forks/MiroKaku/ConMon?style=social) ![Github watchers](https://shields.io/github/watchers/MiroKaku/ConMon?style=social)
- github.com/SinaKarvandi/Process-Magics ![Github stars](https://shields.io/github/stars/SinaKarvandi/Process-Magics?style=social) ![Github forks](https://shields.io/github/forks/SinaKarvandi/Process-Magics?style=social) ![Github watchers](https://shields.io/github/watchers/SinaKarvandi/Process-Magics?style=social)
- github.com/LoukaMB/ExceptionSupervisor ![Github stars](https://shields.io/github/stars/LoukaMB/ExceptionSupervisor?style=social) ![Github forks](https://shields.io/github/forks/LoukaMB/ExceptionSupervisor?style=social) ![Github watchers](https://shields.io/github/watchers/LoukaMB/ExceptionSupervisor?style=social)
- github.com/zmrbak/PcWeChatHooK ![Github stars](https://shields.io/github/stars/zmrbak/PcWeChatHooK?style=social) ![Github forks](https://shields.io/github/forks/zmrbak/PcWeChatHooK?style=social) ![Github watchers](https://shields.io/github/watchers/zmrbak/PcWeChatHooK?style=social)
- github.com/not-matthias/Nemesis (process dumper) ![Github stars](https://shields.io/github/stars/not-matthias/Nemesis?style=social) ![Github forks](https://shields.io/github/forks/not-matthias/Nemesis?style=social) ![Github watchers](https://shields.io/github/watchers/not-matthias/Nemesis?style=social)
- github.com/QAX-A-Team/EventCleaner ![Github stars](https://shields.io/github/stars/QAX-A-Team/EventCleaner?style=social) ![Github forks](https://shields.io/github/forks/QAX-A-Team/EventCleaner?style=social) ![Github watchers](https://shields.io/github/watchers/QAX-A-Team/EventCleaner?style=social)
- github.com/BlackINT3/none (common lib) ![Github stars](https://shields.io/github/stars/BlackINT3/none?style=social) ![Github forks](https://shields.io/github/forks/BlackINT3/none?style=social) ![Github watchers](https://shields.io/github/watchers/BlackINT3/none?style=social)
- github.com/77Sera/BrowserSecurity ![Github stars](https://shields.io/github/stars/77Sera/BrowserSecurity?style=social) ![Github forks](https://shields.io/github/forks/77Sera/BrowserSecurity?style=social) ![Github watchers](https://shields.io/github/watchers/77Sera/BrowserSecurity?style=social)
- github.com/amitwaisel/Malproxy (Proxy system calls over an RPC channel) ![Github stars](https://shields.io/github/stars/amitwaisel/Malproxy?style=social) ![Github forks](https://shields.io/github/forks/amitwaisel/Malproxy?style=social) ![Github watchers](https://shields.io/github/watchers/amitwaisel/Malproxy?style=social)
- github.com/jnastarot/soul_eater (it can extract functions from .dll, .exe, .sys) ![Github stars](https://shields.io/github/stars/jnastarot/soul_eater?style=social) ![Github forks](https://shields.io/github/forks/jnastarot/soul_eater?style=social) ![Github watchers](https://shields.io/github/watchers/jnastarot/soul_eater?style=social)
- github.com/mtth-bfft/lsobj ![Github stars](https://shields.io/github/stars/mtth-bfft/lsobj?style=social) ![Github forks](https://shields.io/github/forks/mtth-bfft/lsobj?style=social) ![Github watchers](https://shields.io/github/watchers/mtth-bfft/lsobj?style=social)
- github.com/mtth-bfft/ntsec ![Github stars](https://shields.io/github/stars/mtth-bfft/ntsec?style=social) ![Github forks](https://shields.io/github/forks/mtth-bfft/ntsec?style=social) ![Github watchers](https://shields.io/github/watchers/mtth-bfft/ntsec?style=social)
- github.com/fritzone/obfy ![Github stars](https://shields.io/github/stars/fritzone/obfy?style=social) ![Github forks](https://shields.io/github/forks/fritzone/obfy?style=social) ![Github watchers](https://shields.io/github/watchers/fritzone/obfy?style=social)
- github.com/microsoft/NetworkDirect ![Github stars](https://shields.io/github/stars/microsoft/NetworkDirect?style=social) ![Github forks](https://shields.io/github/forks/microsoft/NetworkDirect?style=social) ![Github watchers](https://shields.io/github/watchers/microsoft/NetworkDirect?style=social)
- github.com/jay/gethooks ![Github stars](https://shields.io/github/stars/jay/gethooks?style=social) ![Github forks](https://shields.io/github/forks/jay/gethooks?style=social) ![Github watchers](https://shields.io/github/watchers/jay/gethooks?style=social)
- github.com/laxodev/RAII-WINAPI-Memory-Manager ![Github stars](https://shields.io/github/stars/laxodev/RAII-WINAPI-Memory-Manager?style=social) ![Github forks](https://shields.io/github/forks/laxodev/RAII-WINAPI-Memory-Manager?style=social) ![Github watchers](https://shields.io/github/watchers/laxodev/RAII-WINAPI-Memory-Manager?style=social)
- github.com/hfiref0x/WDExtract ![Github stars](https://shields.io/github/stars/hfiref0x/WDExtract?style=social) ![Github forks](https://shields.io/github/forks/hfiref0x/WDExtract?style=social) ![Github watchers](https://shields.io/github/watchers/hfiref0x/WDExtract?style=social)
- github.com/binbibi/libedge ![Github stars](https://shields.io/github/stars/binbibi/libedge?style=social) ![Github forks](https://shields.io/github/forks/binbibi/libedge?style=social) ![Github watchers](https://shields.io/github/watchers/binbibi/libedge?style=social)
- github.com/bb107/WinSudo ![Github stars](https://shields.io/github/stars/bb107/WinSudo?style=social) ![Github forks](https://shields.io/github/forks/bb107/WinSudo?style=social) ![Github watchers](https://shields.io/github/watchers/bb107/WinSudo?style=social)
- github.com/can1357/WinFaults ![Github stars](https://shields.io/github/stars/can1357/WinFaults?style=social) ![Github forks](https://shields.io/github/forks/can1357/WinFaults?style=social) ![Github watchers](https://shields.io/github/watchers/can1357/WinFaults?style=social)
- github.com/Silica/sandbox ![Github stars](https://shields.io/github/stars/Silica/sandbox?style=social) ![Github forks](https://shields.io/github/forks/Silica/sandbox?style=social) ![Github watchers](https://shields.io/github/watchers/Silica/sandbox?style=social)
- github.com/horsicq/Nauz-File-Detector ![Github stars](https://shields.io/github/stars/horsicq/Nauz-File-Detector?style=social) ![Github forks](https://shields.io/github/forks/horsicq/Nauz-File-Detector?style=social) ![Github watchers](https://shields.io/github/watchers/horsicq/Nauz-File-Detector?style=social)
- github.com/horsicq/xntsv (nt struct) ![Github stars](https://shields.io/github/stars/horsicq/xntsv?style=social) ![Github forks](https://shields.io/github/forks/horsicq/xntsv?style=social) ![Github watchers](https://shields.io/github/watchers/horsicq/xntsv?style=social)
- github.com/jnastarot/shibari (pe+) ![Github stars](https://shields.io/github/stars/jnastarot/shibari?style=social) ![Github forks](https://shields.io/github/forks/jnastarot/shibari?style=social) ![Github watchers](https://shields.io/github/watchers/jnastarot/shibari?style=social)
- github.com/NoMoreFood/WinPriv ![Github stars](https://shields.io/github/stars/NoMoreFood/WinPriv?style=social) ![Github forks](https://shields.io/github/forks/NoMoreFood/WinPriv?style=social) ![Github watchers](https://shields.io/github/watchers/NoMoreFood/WinPriv?style=social)
- github.com/yejiansnake/windows-sys-base ![Github stars](https://shields.io/github/stars/yejiansnake/windows-sys-base?style=social) ![Github forks](https://shields.io/github/forks/yejiansnake/windows-sys-base?style=social) ![Github watchers](https://shields.io/github/watchers/yejiansnake/windows-sys-base?style=social)
- github.com/lifenjoiner/pacdbger ![Github stars](https://shields.io/github/stars/lifenjoiner/pacdbger?style=social) ![Github forks](https://shields.io/github/forks/lifenjoiner/pacdbger?style=social) ![Github watchers](https://shields.io/github/watchers/lifenjoiner/pacdbger?style=social)
- github.com/lifenjoiner/sendto-plus ![Github stars](https://shields.io/github/stars/lifenjoiner/sendto-plus?style=social) ![Github forks](https://shields.io/github/forks/lifenjoiner/sendto-plus?style=social) ![Github watchers](https://shields.io/github/watchers/lifenjoiner/sendto-plus?style=social)
- github.com/billziss-gh/winspd ![Github stars](https://shields.io/github/stars/billziss-gh/winspd?style=social) ![Github forks](https://shields.io/github/forks/billziss-gh/winspd?style=social) ![Github watchers](https://shields.io/github/watchers/billziss-gh/winspd?style=social)
- github.com/ffiirree/Capturer ![Github stars](https://shields.io/github/stars/ffiirree/Capturer?style=social) ![Github forks](https://shields.io/github/forks/ffiirree/Capturer?style=social) ![Github watchers](https://shields.io/github/watchers/ffiirree/Capturer?style=social)
- github.com/Claybird/lhaforge ![Github stars](https://shields.io/github/stars/Claybird/lhaforge?style=social) ![Github forks](https://shields.io/github/forks/Claybird/lhaforge?style=social) ![Github watchers](https://shields.io/github/watchers/Claybird/lhaforge?style=social)
- github.com/jjzhang166/nargnos-WindowsUtil ![Github stars](https://shields.io/github/stars/jjzhang166/nargnos-WindowsUtil?style=social) ![Github forks](https://shields.io/github/forks/jjzhang166/nargnos-WindowsUtil?style=social) ![Github watchers](https://shields.io/github/watchers/jjzhang166/nargnos-WindowsUtil?style=social)
- github.com/cool2528/baiduCDP ![Github stars](https://shields.io/github/stars/cool2528/baiduCDP?style=social) ![Github forks](https://shields.io/github/forks/cool2528/baiduCDP?style=social) ![Github watchers](https://shields.io/github/watchers/cool2528/baiduCDP?style=social)
- github.com/anhkgg/SuperWeChatPC ![Github stars](https://shields.io/github/stars/anhkgg/SuperWeChatPC?style=social) ![Github forks](https://shields.io/github/forks/anhkgg/SuperWeChatPC?style=social) ![Github watchers](https://shields.io/github/watchers/anhkgg/SuperWeChatPC?style=social)
- github.com/Alex3434/GetHDDSerial ![Github stars](https://shields.io/github/stars/Alex3434/GetHDDSerial?style=social) ![Github forks](https://shields.io/github/forks/Alex3434/GetHDDSerial?style=social) ![Github watchers](https://shields.io/github/watchers/Alex3434/GetHDDSerial?style=social)
- github.com/TonyChen56/HackerTools ![Github stars](https://shields.io/github/stars/TonyChen56/HackerTools?style=social) ![Github forks](https://shields.io/github/forks/TonyChen56/HackerTools?style=social) ![Github watchers](https://shields.io/github/watchers/TonyChen56/HackerTools?style=social)
- github.com/libyal/liblnk ![Github stars](https://shields.io/github/stars/libyal/liblnk?style=social) ![Github forks](https://shields.io/github/forks/libyal/liblnk?style=social) ![Github watchers](https://shields.io/github/watchers/libyal/liblnk?style=social)
- github.com/NtRaiseHardError/Kaiser ![Github stars](https://shields.io/github/stars/NtRaiseHardError/Kaiser?style=social) ![Github forks](https://shields.io/github/forks/NtRaiseHardError/Kaiser?style=social) ![Github watchers](https://shields.io/github/watchers/NtRaiseHardError/Kaiser?style=social)
- github.com/mengskysama/V8 (chrome v8 engine) ![Github stars](https://shields.io/github/stars/mengskysama/V8?style=social) ![Github forks](https://shields.io/github/forks/mengskysama/V8?style=social) ![Github watchers](https://shields.io/github/watchers/mengskysama/V8?style=social)
- github.com/locustwei/WorkBack ![Github stars](https://shields.io/github/stars/locustwei/WorkBack?style=social) ![Github forks](https://shields.io/github/forks/locustwei/WorkBack?style=social) ![Github watchers](https://shields.io/github/watchers/locustwei/WorkBack?style=social)
- github.com/360-A-Team/EventCleaner ![Github stars](https://shields.io/github/stars/360-A-Team/EventCleaner?style=social) ![Github forks](https://shields.io/github/forks/360-A-Team/EventCleaner?style=social) ![Github watchers](https://shields.io/github/watchers/360-A-Team/EventCleaner?style=social)
- github.com/Microsoft/Windows-classic-samples ![Github stars](https://shields.io/github/stars/Microsoft/Windows-classic-samples?style=social) ![Github forks](https://shields.io/github/forks/Microsoft/Windows-classic-samples?style=social) ![Github watchers](https://shields.io/github/watchers/Microsoft/Windows-classic-samples?style=social)
- github.com/troldal/OpenXLSX (.xlsx format) ![Github stars](https://shields.io/github/stars/troldal/OpenXLSX?style=social) ![Github forks](https://shields.io/github/forks/troldal/OpenXLSX?style=social) ![Github watchers](https://shields.io/github/watchers/troldal/OpenXLSX?style=social)
- github.com/mity/windrawlib (GDI+ Helper) ![Github stars](https://shields.io/github/stars/mity/windrawlib?style=social) ![Github forks](https://shields.io/github/forks/mity/windrawlib?style=social) ![Github watchers](https://shields.io/github/watchers/mity/windrawlib?style=social)
- github.com/henrypp/errorlookup ![Github stars](https://shields.io/github/stars/henrypp/errorlookup?style=social) ![Github forks](https://shields.io/github/forks/henrypp/errorlookup?style=social) ![Github watchers](https://shields.io/github/watchers/henrypp/errorlookup?style=social)
- github.com/longmode/authzsec-mod-um (AppContainer and ACL) ![Github stars](https://shields.io/github/stars/longmode/authzsec-mod-um?style=social) ![Github forks](https://shields.io/github/forks/longmode/authzsec-mod-um?style=social) ![Github watchers](https://shields.io/github/watchers/longmode/authzsec-mod-um?style=social)
- github.com/henrypp/memreduct ![Github stars](https://shields.io/github/stars/henrypp/memreduct?style=social) ![Github forks](https://shields.io/github/forks/henrypp/memreduct?style=social) ![Github watchers](https://shields.io/github/watchers/henrypp/memreduct?style=social)
- github.com/thomaslaurenson/LiveDiff (live diff) ![Github stars](https://shields.io/github/stars/thomaslaurenson/LiveDiff?style=social) ![Github forks](https://shields.io/github/forks/thomaslaurenson/LiveDiff?style=social) ![Github watchers](https://shields.io/github/watchers/thomaslaurenson/LiveDiff?style=social)
- github.com/thomaslaurenson/CellXML-offreg (hive file parse) ![Github stars](https://shields.io/github/stars/thomaslaurenson/CellXML-offreg?style=social) ![Github forks](https://shields.io/github/forks/thomaslaurenson/CellXML-offreg?style=social) ![Github watchers](https://shields.io/github/watchers/thomaslaurenson/CellXML-offreg?style=social)
- github.com/zhaolong/libparser (static lib parse) ![Github stars](https://shields.io/github/stars/zhaolong/libparser?style=social) ![Github forks](https://shields.io/github/forks/zhaolong/libparser?style=social) ![Github watchers](https://shields.io/github/watchers/zhaolong/libparser?style=social)
- github.com/WildByDesign/Privexec ![Github stars](https://shields.io/github/stars/WildByDesign/Privexec?style=social) ![Github forks](https://shields.io/github/forks/WildByDesign/Privexec?style=social) ![Github watchers](https://shields.io/github/watchers/WildByDesign/Privexec?style=social)
- github.com/KangLin/RabbitIm ![Github stars](https://shields.io/github/stars/KangLin/RabbitIm?style=social) ![Github forks](https://shields.io/github/forks/KangLin/RabbitIm?style=social) ![Github watchers](https://shields.io/github/watchers/KangLin/RabbitIm?style=social)
- github.com/kingsunc/MiniDump ![Github stars](https://shields.io/github/stars/kingsunc/MiniDump?style=social) ![Github forks](https://shields.io/github/forks/kingsunc/MiniDump?style=social) ![Github watchers](https://shields.io/github/watchers/kingsunc/MiniDump?style=social)
- github.com/amdf/reparselib ![Github stars](https://shields.io/github/stars/amdf/reparselib?style=social) ![Github forks](https://shields.io/github/forks/amdf/reparselib?style=social) ![Github watchers](https://shields.io/github/watchers/amdf/reparselib?style=social)
- github.com/Zero3K/connectfusion (download manager) ![Github stars](https://shields.io/github/stars/Zero3K/connectfusion?style=social) ![Github forks](https://shields.io/github/forks/Zero3K/connectfusion?style=social) ![Github watchers](https://shields.io/github/watchers/Zero3K/connectfusion?style=social)
- github.com/Zero3K/ERAM (RAM Disk) ![Github stars](https://shields.io/github/stars/Zero3K/ERAM?style=social) ![Github forks](https://shields.io/github/forks/Zero3K/ERAM?style=social) ![Github watchers](https://shields.io/github/watchers/Zero3K/ERAM?style=social)
- github.com/bailey27/cppcryptfs  ( gocryptfs encrypted overlay filesystem) ![Github stars](https://shields.io/github/stars/bailey27/cppcryptfs?style=social) ![Github forks](https://shields.io/github/forks/bailey27/cppcryptfs?style=social) ![Github watchers](https://shields.io/github/watchers/bailey27/cppcryptfs?style=social)
- github.com/etsubu/MacroRecorder (recording keyboard and mouse macros) ![Github stars](https://shields.io/github/stars/etsubu/MacroRecorder?style=social) ![Github forks](https://shields.io/github/forks/etsubu/MacroRecorder?style=social) ![Github watchers](https://shields.io/github/watchers/etsubu/MacroRecorder?style=social)
- github.com/wyrover/CodeLib ![Github stars](https://shields.io/github/stars/wyrover/CodeLib?style=social) ![Github forks](https://shields.io/github/forks/wyrover/CodeLib?style=social) ![Github watchers](https://shields.io/github/watchers/wyrover/CodeLib?style=social)
- github.com/Rprop/CppDLL (dll to .h and lib) ![Github stars](https://shields.io/github/stars/Rprop/CppDLL?style=social) ![Github forks](https://shields.io/github/forks/Rprop/CppDLL?style=social) ![Github watchers](https://shields.io/github/watchers/Rprop/CppDLL?style=social)
- github.com/seledka/syslib ![Github stars](https://shields.io/github/stars/seledka/syslib?style=social) ![Github forks](https://shields.io/github/forks/seledka/syslib?style=social) ![Github watchers](https://shields.io/github/watchers/seledka/syslib?style=social)
- github.com/leecher1337/regremap ![Github stars](https://shields.io/github/stars/leecher1337/regremap?style=social) ![Github forks](https://shields.io/github/forks/leecher1337/regremap?style=social) ![Github watchers](https://shields.io/github/watchers/leecher1337/regremap?style=social)
- github.com/webees/ADkiller ![Github stars](https://shields.io/github/stars/webees/ADkiller?style=social) ![Github forks](https://shields.io/github/forks/webees/ADkiller?style=social) ![Github watchers](https://shields.io/github/watchers/webees/ADkiller?style=social)
- github.com/skysilent/coroutine_study (fiber) ![Github stars](https://shields.io/github/stars/skysilent/coroutine_study?style=social) ![Github forks](https://shields.io/github/forks/skysilent/coroutine_study?style=social) ![Github watchers](https://shields.io/github/watchers/skysilent/coroutine_study?style=social)
- github.com/ruusty/NAntMenu ![Github stars](https://shields.io/github/stars/ruusty/NAntMenu?style=social) ![Github forks](https://shields.io/github/forks/ruusty/NAntMenu?style=social) ![Github watchers](https://shields.io/github/watchers/ruusty/NAntMenu?style=social)
- github.com/chrdavis/PIFShellExtensions ![Github stars](https://shields.io/github/stars/chrdavis/PIFShellExtensions?style=social) ![Github forks](https://shields.io/github/forks/chrdavis/PIFShellExtensions?style=social) ![Github watchers](https://shields.io/github/watchers/chrdavis/PIFShellExtensions?style=social)
- github.com/codepongo/zshellext ![Github stars](https://shields.io/github/stars/codepongo/zshellext?style=social) ![Github forks](https://shields.io/github/forks/codepongo/zshellext?style=social) ![Github watchers](https://shields.io/github/watchers/codepongo/zshellext?style=social)
- github.com/lz77win/lz77win_sources ![Github stars](https://shields.io/github/stars/lz77win/lz77win_sources?style=social) ![Github forks](https://shields.io/github/forks/lz77win/lz77win_sources?style=social) ![Github watchers](https://shields.io/github/watchers/lz77win/lz77win_sources?style=social)
- github.com/Microsoft/perfview ![Github stars](https://shields.io/github/stars/Microsoft/perfview?style=social) ![Github forks](https://shields.io/github/forks/Microsoft/perfview?style=social) ![Github watchers](https://shields.io/github/watchers/Microsoft/perfview?style=social)
- github.com/GameTechDev/PresentMon ![Github stars](https://shields.io/github/stars/GameTechDev/PresentMon?style=social) ![Github forks](https://shields.io/github/forks/GameTechDev/PresentMon?style=social) ![Github watchers](https://shields.io/github/watchers/GameTechDev/PresentMon?style=social)
- github.com/hfiref0x/BSODScreen ![Github stars](https://shields.io/github/stars/hfiref0x/BSODScreen?style=social) ![Github forks](https://shields.io/github/forks/hfiref0x/BSODScreen?style=social) ![Github watchers](https://shields.io/github/watchers/hfiref0x/BSODScreen?style=social)
- github.com/CasualX/LibEx ![Github stars](https://shields.io/github/stars/CasualX/LibEx?style=social) ![Github forks](https://shields.io/github/forks/CasualX/LibEx?style=social) ![Github watchers](https://shields.io/github/watchers/CasualX/LibEx?style=social)
- github.com/syhyz1990/baiduyun ![Github stars](https://shields.io/github/stars/syhyz1990/baiduyun?style=social) ![Github forks](https://shields.io/github/forks/syhyz1990/baiduyun?style=social) ![Github watchers](https://shields.io/github/watchers/syhyz1990/baiduyun?style=social)
- github.com/WalkingCat/SymDiff ![Github stars](https://shields.io/github/stars/WalkingCat/SymDiff?style=social) ![Github forks](https://shields.io/github/forks/WalkingCat/SymDiff?style=social) ![Github watchers](https://shields.io/github/watchers/WalkingCat/SymDiff?style=social)
- github.com/libyal/libevtx ![Github stars](https://shields.io/github/stars/libyal/libevtx?style=social) ![Github forks](https://shields.io/github/forks/libyal/libevtx?style=social) ![Github watchers](https://shields.io/github/watchers/libyal/libevtx?style=social)
- github.com/wanttobeno/Screenshot ![Github stars](https://shields.io/github/stars/wanttobeno/Screenshot?style=social) ![Github forks](https://shields.io/github/forks/wanttobeno/Screenshot?style=social) ![Github watchers](https://shields.io/github/watchers/wanttobeno/Screenshot?style=social)
- github.com/scarsty/tinypot ![Github stars](https://shields.io/github/stars/scarsty/tinypot?style=social) ![Github forks](https://shields.io/github/forks/scarsty/tinypot?style=social) ![Github watchers](https://shields.io/github/watchers/scarsty/tinypot?style=social)
- github.com/jonasblunck/DynHook ![Github stars](https://shields.io/github/stars/jonasblunck/DynHook?style=social) ![Github forks](https://shields.io/github/forks/jonasblunck/DynHook?style=social) ![Github watchers](https://shields.io/github/watchers/jonasblunck/DynHook?style=social)
- github.com/y11en/PEBFake (PEB fake) ![Github stars](https://shields.io/github/stars/y11en/PEBFake?style=social) ![Github forks](https://shields.io/github/forks/y11en/PEBFake?style=social) ![Github watchers](https://shields.io/github/watchers/y11en/PEBFake?style=social)
- github.com/wanttobeno/mousehook (setwindowhook) ![Github stars](https://shields.io/github/stars/wanttobeno/mousehook?style=social) ![Github forks](https://shields.io/github/forks/wanttobeno/mousehook?style=social) ![Github watchers](https://shields.io/github/watchers/wanttobeno/mousehook?style=social)
- github.com/wanttobeno/DXF-Viewer ![Github stars](https://shields.io/github/stars/wanttobeno/DXF-Viewer?style=social) ![Github forks](https://shields.io/github/forks/wanttobeno/DXF-Viewer?style=social) ![Github watchers](https://shields.io/github/watchers/wanttobeno/DXF-Viewer?style=social)
- github.com/wanttobeno/XmlConfigDemo ![Github stars](https://shields.io/github/stars/wanttobeno/XmlConfigDemo?style=social) ![Github forks](https://shields.io/github/forks/wanttobeno/XmlConfigDemo?style=social) ![Github watchers](https://shields.io/github/watchers/wanttobeno/XmlConfigDemo?style=social)
- github.com/wanttobeno/GeneralHashFunctions ![Github stars](https://shields.io/github/stars/wanttobeno/GeneralHashFunctions?style=social) ![Github forks](https://shields.io/github/forks/wanttobeno/GeneralHashFunctions?style=social) ![Github watchers](https://shields.io/github/watchers/wanttobeno/GeneralHashFunctions?style=social)
- github.com/wanttobeno/Chrome-base-cpu ![Github stars](https://shields.io/github/stars/wanttobeno/Chrome-base-cpu?style=social) ![Github forks](https://shields.io/github/forks/wanttobeno/Chrome-base-cpu?style=social) ![Github watchers](https://shields.io/github/watchers/wanttobeno/Chrome-base-cpu?style=social)
- github.com/wanttobeno/stl_util ![Github stars](https://shields.io/github/stars/wanttobeno/stl_util?style=social) ![Github forks](https://shields.io/github/forks/wanttobeno/stl_util?style=social) ![Github watchers](https://shields.io/github/watchers/wanttobeno/stl_util?style=social)
- github.com/wanttobeno/LinkHelper ![Github stars](https://shields.io/github/stars/wanttobeno/LinkHelper?style=social) ![Github forks](https://shields.io/github/forks/wanttobeno/LinkHelper?style=social) ![Github watchers](https://shields.io/github/watchers/wanttobeno/LinkHelper?style=social)
- github.com/wanttobeno/Ring3GetProcessInfo ![Github stars](https://shields.io/github/stars/wanttobeno/Ring3GetProcessInfo?style=social) ![Github forks](https://shields.io/github/forks/wanttobeno/Ring3GetProcessInfo?style=social) ![Github watchers](https://shields.io/github/watchers/wanttobeno/Ring3GetProcessInfo?style=social)
- github.com/zsummer/breeze ![Github stars](https://shields.io/github/stars/zsummer/breeze?style=social) ![Github forks](https://shields.io/github/forks/zsummer/breeze?style=social) ![Github watchers](https://shields.io/github/watchers/zsummer/breeze?style=social)
- github.com/wanttobeno/SoftWareManager ![Github stars](https://shields.io/github/stars/wanttobeno/SoftWareManager?style=social) ![Github forks](https://shields.io/github/forks/wanttobeno/SoftWareManager?style=social) ![Github watchers](https://shields.io/github/watchers/wanttobeno/SoftWareManager?style=social)
- github.com/wanttobeno/GetMacAddress ![Github stars](https://shields.io/github/stars/wanttobeno/GetMacAddress?style=social) ![Github forks](https://shields.io/github/forks/wanttobeno/GetMacAddress?style=social) ![Github watchers](https://shields.io/github/watchers/wanttobeno/GetMacAddress?style=social)
- github.com/wanttobeno/HtmlViewer ![Github stars](https://shields.io/github/stars/wanttobeno/HtmlViewer?style=social) ![Github forks](https://shields.io/github/forks/wanttobeno/HtmlViewer?style=social) ![Github watchers](https://shields.io/github/watchers/wanttobeno/HtmlViewer?style=social)
- github.com/wanttobeno/AltServer ![Github stars](https://shields.io/github/stars/wanttobeno/AltServer?style=social) ![Github forks](https://shields.io/github/forks/wanttobeno/AltServer?style=social) ![Github watchers](https://shields.io/github/watchers/wanttobeno/AltServer?style=social)
- github.com/wanttobeno/GetPeInfo ![Github stars](https://shields.io/github/stars/wanttobeno/GetPeInfo?style=social) ![Github forks](https://shields.io/github/forks/wanttobeno/GetPeInfo?style=social) ![Github watchers](https://shields.io/github/watchers/wanttobeno/GetPeInfo?style=social)
- github.com/wanttobeno/notepad ![Github stars](https://shields.io/github/stars/wanttobeno/notepad?style=social) ![Github forks](https://shields.io/github/forks/wanttobeno/notepad?style=social) ![Github watchers](https://shields.io/github/watchers/wanttobeno/notepad?style=social)
- github.com/wanttobeno/PELearningMaterials ![Github stars](https://shields.io/github/stars/wanttobeno/PELearningMaterials?style=social) ![Github forks](https://shields.io/github/forks/wanttobeno/PELearningMaterials?style=social) ![Github watchers](https://shields.io/github/watchers/wanttobeno/PELearningMaterials?style=social)
- github.com/wanttobeno/Detours_4.0.1 ![Github stars](https://shields.io/github/stars/wanttobeno/Detours_4.0.1?style=social) ![Github forks](https://shields.io/github/forks/wanttobeno/Detours_4.0.1?style=social) ![Github watchers](https://shields.io/github/watchers/wanttobeno/Detours_4.0.1?style=social)
- github.com/wanttobeno/skinsb ![Github stars](https://shields.io/github/stars/wanttobeno/skinsb?style=social) ![Github forks](https://shields.io/github/forks/wanttobeno/skinsb?style=social) ![Github watchers](https://shields.io/github/watchers/wanttobeno/skinsb?style=social)
- github.com/wanttobeno/DLib-Attacher ![Github stars](https://shields.io/github/stars/wanttobeno/DLib-Attacher?style=social) ![Github forks](https://shields.io/github/forks/wanttobeno/DLib-Attacher?style=social) ![Github watchers](https://shields.io/github/watchers/wanttobeno/DLib-Attacher?style=social)
- github.com/wanttobeno/VmpHandle ![Github stars](https://shields.io/github/stars/wanttobeno/VmpHandle?style=social) ![Github forks](https://shields.io/github/forks/wanttobeno/VmpHandle?style=social) ![Github watchers](https://shields.io/github/watchers/wanttobeno/VmpHandle?style=social)
- github.com/wanttobeno/ScopeGuard (resource safe delete) ![Github stars](https://shields.io/github/stars/wanttobeno/ScopeGuard?style=social) ![Github forks](https://shields.io/github/forks/wanttobeno/ScopeGuard?style=social) ![Github watchers](https://shields.io/github/watchers/wanttobeno/ScopeGuard?style=social)
- github.com/wanttobeno/HashMapDemo ![Github stars](https://shields.io/github/stars/wanttobeno/HashMapDemo?style=social) ![Github forks](https://shields.io/github/forks/wanttobeno/HashMapDemo?style=social) ![Github watchers](https://shields.io/github/watchers/wanttobeno/HashMapDemo?style=social)
- github.com/wanttobeno/nanob (protobuf) ![Github stars](https://shields.io/github/stars/wanttobeno/nanob?style=social) ![Github forks](https://shields.io/github/forks/wanttobeno/nanob?style=social) ![Github watchers](https://shields.io/github/watchers/wanttobeno/nanob?style=social)
- github.com/wanttobeno/baidu-sofa-pbrpc-win (protobuf) ![Github stars](https://shields.io/github/stars/wanttobeno/baidu-sofa-pbrpc-win?style=social) ![Github forks](https://shields.io/github/forks/wanttobeno/baidu-sofa-pbrpc-win?style=social) ![Github watchers](https://shields.io/github/watchers/wanttobeno/baidu-sofa-pbrpc-win?style=social)
- github.com/xlet/UpdateClient ![Github stars](https://shields.io/github/stars/xlet/UpdateClient?style=social) ![Github forks](https://shields.io/github/forks/xlet/UpdateClient?style=social) ![Github watchers](https://shields.io/github/watchers/xlet/UpdateClient?style=social)
- github.com/wanttobeno/AesFileProtection ![Github stars](https://shields.io/github/stars/wanttobeno/AesFileProtection?style=social) ![Github forks](https://shields.io/github/forks/wanttobeno/AesFileProtection?style=social) ![Github watchers](https://shields.io/github/watchers/wanttobeno/AesFileProtection?style=social)
- github.com/wanttobeno/IeProxy ![Github stars](https://shields.io/github/stars/wanttobeno/IeProxy?style=social) ![Github forks](https://shields.io/github/forks/wanttobeno/IeProxy?style=social) ![Github watchers](https://shields.io/github/watchers/wanttobeno/IeProxy?style=social)
- github.com/wanttobeno/MyProtocol ![Github stars](https://shields.io/github/stars/wanttobeno/MyProtocol?style=social) ![Github forks](https://shields.io/github/forks/wanttobeno/MyProtocol?style=social) ![Github watchers](https://shields.io/github/watchers/wanttobeno/MyProtocol?style=social)
- github.com/wanttobeno/Window_KeyAndMouseHook ![Github stars](https://shields.io/github/stars/wanttobeno/Window_KeyAndMouseHook?style=social) ![Github forks](https://shields.io/github/forks/wanttobeno/Window_KeyAndMouseHook?style=social) ![Github watchers](https://shields.io/github/watchers/wanttobeno/Window_KeyAndMouseHook?style=social)
- github.com/wanttobeno/doublebufferedqueue (double buffered queue) ![Github stars](https://shields.io/github/stars/wanttobeno/doublebufferedqueue?style=social) ![Github forks](https://shields.io/github/forks/wanttobeno/doublebufferedqueue?style=social) ![Github watchers](https://shields.io/github/watchers/wanttobeno/doublebufferedqueue?style=social)
- github.com/DoubleLabyrinth/010Editor-keygen (keygen) ![Github stars](https://shields.io/github/stars/DoubleLabyrinth/010Editor-keygen?style=social) ![Github forks](https://shields.io/github/forks/DoubleLabyrinth/010Editor-keygen?style=social) ![Github watchers](https://shields.io/github/watchers/DoubleLabyrinth/010Editor-keygen?style=social)
- github.com/wanttobeno/Cpp11ThreadPool ![Github stars](https://shields.io/github/stars/wanttobeno/Cpp11ThreadPool?style=social) ![Github forks](https://shields.io/github/forks/wanttobeno/Cpp11ThreadPool?style=social) ![Github watchers](https://shields.io/github/watchers/wanttobeno/Cpp11ThreadPool?style=social)
- github.com/wanttobeno/Study_shellcode (shellcode) ![Github stars](https://shields.io/github/stars/wanttobeno/Study_shellcode?style=social) ![Github forks](https://shields.io/github/forks/wanttobeno/Study_shellcode?style=social) ![Github watchers](https://shields.io/github/watchers/wanttobeno/Study_shellcode?style=social)
- github.com/wanttobeno/Study_algorithm (data struct) ![Github stars](https://shields.io/github/stars/wanttobeno/Study_algorithm?style=social) ![Github forks](https://shields.io/github/forks/wanttobeno/Study_algorithm?style=social) ![Github watchers](https://shields.io/github/watchers/wanttobeno/Study_algorithm?style=social)
- github.com/wanttobeno/ThreadPool ![Github stars](https://shields.io/github/stars/wanttobeno/ThreadPool?style=social) ![Github forks](https://shields.io/github/forks/wanttobeno/ThreadPool?style=social) ![Github watchers](https://shields.io/github/watchers/wanttobeno/ThreadPool?style=social)
- github.com/wanttobeno/Study_threadpool (thread pool) ![Github stars](https://shields.io/github/stars/wanttobeno/Study_threadpool?style=social) ![Github forks](https://shields.io/github/forks/wanttobeno/Study_threadpool?style=social) ![Github watchers](https://shields.io/github/watchers/wanttobeno/Study_threadpool?style=social)
- github.com/wanttobeno/Study_Websocket (websocket) ![Github stars](https://shields.io/github/stars/wanttobeno/Study_Websocket?style=social) ![Github forks](https://shields.io/github/forks/wanttobeno/Study_Websocket?style=social) ![Github watchers](https://shields.io/github/watchers/wanttobeno/Study_Websocket?style=social)
- github.com/Amanieu/asyncplusplus ![Github stars](https://shields.io/github/stars/Amanieu/asyncplusplus?style=social) ![Github forks](https://shields.io/github/forks/Amanieu/asyncplusplus?style=social) ![Github watchers](https://shields.io/github/watchers/Amanieu/asyncplusplus?style=social)
- github.com/wanttobeno/Study_Socket ![Github stars](https://shields.io/github/stars/wanttobeno/Study_Socket?style=social) ![Github forks](https://shields.io/github/forks/wanttobeno/Study_Socket?style=social) ![Github watchers](https://shields.io/github/watchers/wanttobeno/Study_Socket?style=social)
- github.com/wanttobeno/DllProtect ![Github stars](https://shields.io/github/stars/wanttobeno/DllProtect?style=social) ![Github forks](https://shields.io/github/forks/wanttobeno/DllProtect?style=social) ![Github watchers](https://shields.io/github/watchers/wanttobeno/DllProtect?style=social)
- github.com/allenyllee/The-CPUID-Explorer ![Github stars](https://shields.io/github/stars/allenyllee/The-CPUID-Explorer?style=social) ![Github forks](https://shields.io/github/forks/allenyllee/The-CPUID-Explorer?style=social) ![Github watchers](https://shields.io/github/watchers/allenyllee/The-CPUID-Explorer?style=social)
- github.com/wanttobeno/SunDaySearchSignCode ![Github stars](https://shields.io/github/stars/wanttobeno/SunDaySearchSignCode?style=social) ![Github forks](https://shields.io/github/forks/wanttobeno/SunDaySearchSignCode?style=social) ![Github watchers](https://shields.io/github/watchers/wanttobeno/SunDaySearchSignCode?style=social)
- github.com/wanttobeno/x64_AOB_Search (fast search memory algorithm) ![Github stars](https://shields.io/github/stars/wanttobeno/x64_AOB_Search?style=social) ![Github forks](https://shields.io/github/forks/wanttobeno/x64_AOB_Search?style=social) ![Github watchers](https://shields.io/github/watchers/wanttobeno/x64_AOB_Search?style=social)
- github.com/wanttobeno/iQIYI_Web_Video_Upload (http simulate upload) ![Github stars](https://shields.io/github/stars/wanttobeno/iQIYI_Web_Video_Upload?style=social) ![Github forks](https://shields.io/github/forks/wanttobeno/iQIYI_Web_Video_Upload?style=social) ![Github watchers](https://shields.io/github/watchers/wanttobeno/iQIYI_Web_Video_Upload?style=social)
- github.com/wanttobeno/Study_XiaoMi_Login (https simulate login) ![Github stars](https://shields.io/github/stars/wanttobeno/Study_XiaoMi_Login?style=social) ![Github forks](https://shields.io/github/forks/wanttobeno/Study_XiaoMi_Login?style=social) ![Github watchers](https://shields.io/github/watchers/wanttobeno/Study_XiaoMi_Login?style=social)
- github.com/fawdlstty/NetToolbox ![Github stars](https://shields.io/github/stars/fawdlstty/NetToolbox?style=social) ![Github forks](https://shields.io/github/forks/fawdlstty/NetToolbox?style=social) ![Github watchers](https://shields.io/github/watchers/fawdlstty/NetToolbox?style=social)
- github.com/hzqst/FuckCertVerifyTimeValidity ![Github stars](https://shields.io/github/stars/hzqst/FuckCertVerifyTimeValidity?style=social) ![Github forks](https://shields.io/github/forks/hzqst/FuckCertVerifyTimeValidity?style=social) ![Github watchers](https://shields.io/github/watchers/hzqst/FuckCertVerifyTimeValidity?style=social)
- github.com/717021/PCMgr (task manager) ![Github stars](https://shields.io/github/stars/717021/PCMgr?style=social) ![Github forks](https://shields.io/github/forks/717021/PCMgr?style=social) ![Github watchers](https://shields.io/github/watchers/717021/PCMgr?style=social)
- github.com/silverf0x/RpcView (rpc) ![Github stars](https://shields.io/github/stars/silverf0x/RpcView?style=social) ![Github forks](https://shields.io/github/forks/silverf0x/RpcView?style=social) ![Github watchers](https://shields.io/github/watchers/silverf0x/RpcView?style=social)
- github.com/ez8-co/unlocker () ![Github stars](https://shields.io/github/stars/ez8-co/unlocker?style=social) ![Github forks](https://shields.io/github/forks/ez8-co/unlocker?style=social) ![Github watchers](https://shields.io/github/watchers/ez8-co/unlocker?style=social)
- github.com/nkga/self-updater (framework for secure self-update) ![Github stars](https://shields.io/github/stars/nkga/self-updater?style=social) ![Github forks](https://shields.io/github/forks/nkga/self-updater?style=social) ![Github watchers](https://shields.io/github/watchers/nkga/self-updater?style=social)
- github.com/liamkirton/sslcat (nc with ssl) ![Github stars](https://shields.io/github/stars/liamkirton/sslcat?style=social) ![Github forks](https://shields.io/github/forks/liamkirton/sslcat?style=social) ![Github watchers](https://shields.io/github/watchers/liamkirton/sslcat?style=social)
- github.com/Seineruo/RSA-Tool ![Github stars](https://shields.io/github/stars/Seineruo/RSA-Tool?style=social) ![Github forks](https://shields.io/github/forks/Seineruo/RSA-Tool?style=social) ![Github watchers](https://shields.io/github/watchers/Seineruo/RSA-Tool?style=social)
- github.com/PBfordev/wxAutoExcel ![Github stars](https://shields.io/github/stars/PBfordev/wxAutoExcel?style=social) ![Github forks](https://shields.io/github/forks/PBfordev/wxAutoExcel?style=social) ![Github watchers](https://shields.io/github/watchers/PBfordev/wxAutoExcel?style=social)
- github.com/ax330d/Symex ![Github stars](https://shields.io/github/stars/ax330d/Symex?style=social) ![Github forks](https://shields.io/github/forks/ax330d/Symex?style=social) ![Github watchers](https://shields.io/github/watchers/ax330d/Symex?style=social)
- github.com/Biswa96/PDBDownloader ![Github stars](https://shields.io/github/stars/Biswa96/PDBDownloader?style=social) ![Github forks](https://shields.io/github/forks/Biswa96/PDBDownloader?style=social) ![Github watchers](https://shields.io/github/watchers/Biswa96/PDBDownloader?style=social)
- github.com/Biswa96/TraceEvent ![Github stars](https://shields.io/github/stars/Biswa96/TraceEvent?style=social) ![Github forks](https://shields.io/github/forks/Biswa96/TraceEvent?style=social) ![Github watchers](https://shields.io/github/watchers/Biswa96/TraceEvent?style=social)
- github.com/hfiref0x/Misc ![Github stars](https://shields.io/github/stars/hfiref0x/Misc?style=social) ![Github forks](https://shields.io/github/forks/hfiref0x/Misc?style=social) ![Github watchers](https://shields.io/github/watchers/hfiref0x/Misc?style=social)
- github.com/SergioCalderonR/DelSvc ![Github stars](https://shields.io/github/stars/SergioCalderonR/DelSvc?style=social) ![Github forks](https://shields.io/github/forks/SergioCalderonR/DelSvc?style=social) ![Github watchers](https://shields.io/github/watchers/SergioCalderonR/DelSvc?style=social)
- github.com/wyrover/win-privileges-examples (DACL) ![Github stars](https://shields.io/github/stars/wyrover/win-privileges-examples?style=social) ![Github forks](https://shields.io/github/forks/wyrover/win-privileges-examples?style=social) ![Github watchers](https://shields.io/github/watchers/wyrover/win-privileges-examples?style=social)
- github.com/nccgroup/WindowsDACLEnumProject (DACL) ![Github stars](https://shields.io/github/stars/nccgroup/WindowsDACLEnumProject?style=social) ![Github forks](https://shields.io/github/forks/nccgroup/WindowsDACLEnumProject?style=social) ![Github watchers](https://shields.io/github/watchers/nccgroup/WindowsDACLEnumProject?style=social)
- github.com/xqymain/ServerLocker ![Github stars](https://shields.io/github/stars/xqymain/ServerLocker?style=social) ![Github forks](https://shields.io/github/forks/xqymain/ServerLocker?style=social) ![Github watchers](https://shields.io/github/watchers/xqymain/ServerLocker?style=social)
- github.com/wanttobeno/SunDaySearchSignCode (fast search memory) ![Github stars](https://shields.io/github/stars/wanttobeno/SunDaySearchSignCode?style=social) ![Github forks](https://shields.io/github/forks/wanttobeno/SunDaySearchSignCode?style=social) ![Github watchers](https://shields.io/github/watchers/wanttobeno/SunDaySearchSignCode?style=social)
- github.com/zhongyang219/SimpleNotePad ![Github stars](https://shields.io/github/stars/zhongyang219/SimpleNotePad?style=social) ![Github forks](https://shields.io/github/forks/zhongyang219/SimpleNotePad?style=social) ![Github watchers](https://shields.io/github/watchers/zhongyang219/SimpleNotePad?style=social)
- github.com/zhongyang219/TrafficMonitor ![Github stars](https://shields.io/github/stars/zhongyang219/TrafficMonitor?style=social) ![Github forks](https://shields.io/github/forks/zhongyang219/TrafficMonitor?style=social) ![Github watchers](https://shields.io/github/watchers/zhongyang219/TrafficMonitor?style=social)
- github.com/codereba/data_scrambler (scrambler) ![Github stars](https://shields.io/github/stars/codereba/data_scrambler?style=social) ![Github forks](https://shields.io/github/forks/codereba/data_scrambler?style=social) ![Github watchers](https://shields.io/github/watchers/codereba/data_scrambler?style=social)
- github.com/3gstudent/Catch-specified-file-s-handle (enum file handle) ![Github stars](https://shields.io/github/stars/3gstudent/Catch-specified-file-s-handle?style=social) ![Github forks](https://shields.io/github/forks/3gstudent/Catch-specified-file-s-handle?style=social) ![Github watchers](https://shields.io/github/watchers/3gstudent/Catch-specified-file-s-handle?style=social)
- github.com/intel/safestringlib ![Github stars](https://shields.io/github/stars/intel/safestringlib?style=social) ![Github forks](https://shields.io/github/forks/intel/safestringlib?style=social) ![Github watchers](https://shields.io/github/watchers/intel/safestringlib?style=social)
- github.com/eyusoft/asutlity ![Github stars](https://shields.io/github/stars/eyusoft/asutlity?style=social) ![Github forks](https://shields.io/github/forks/eyusoft/asutlity?style=social) ![Github watchers](https://shields.io/github/watchers/eyusoft/asutlity?style=social)
- github.com/ThomasThelen/BrowserLib ![Github stars](https://shields.io/github/stars/ThomasThelen/BrowserLib?style=social) ![Github forks](https://shields.io/github/forks/ThomasThelen/BrowserLib?style=social) ![Github watchers](https://shields.io/github/watchers/ThomasThelen/BrowserLib?style=social)
- github.com/OSRDrivers/dirchange ![Github stars](https://shields.io/github/stars/OSRDrivers/dirchange?style=social) ![Github forks](https://shields.io/github/forks/OSRDrivers/dirchange?style=social) ![Github watchers](https://shields.io/github/watchers/OSRDrivers/dirchange?style=social)
- github.com/OSRDrivers/deleteex (FileDispositionInfoEx) ![Github stars](https://shields.io/github/stars/OSRDrivers/deleteex?style=social) ![Github forks](https://shields.io/github/forks/OSRDrivers/deleteex?style=social) ![Github watchers](https://shields.io/github/watchers/OSRDrivers/deleteex?style=social)
- github.com/notscimmy/YASS (sig scanner) ![Github stars](https://shields.io/github/stars/notscimmy/YASS?style=social) ![Github forks](https://shields.io/github/forks/notscimmy/YASS?style=social) ![Github watchers](https://shields.io/github/watchers/notscimmy/YASS?style=social)
- github.com/942860759/BrowserHistory ![Github stars](https://shields.io/github/stars/942860759/BrowserHistory?style=social) ![Github forks](https://shields.io/github/forks/942860759/BrowserHistory?style=social) ![Github watchers](https://shields.io/github/watchers/942860759/BrowserHistory?style=social)
- github.com/NoMoreFood/putty-cac ![Github stars](https://shields.io/github/stars/NoMoreFood/putty-cac?style=social) ![Github forks](https://shields.io/github/forks/NoMoreFood/putty-cac?style=social) ![Github watchers](https://shields.io/github/watchers/NoMoreFood/putty-cac?style=social)
- github.com/NoMoreFood/Repacls ![Github stars](https://shields.io/github/stars/NoMoreFood/Repacls?style=social) ![Github forks](https://shields.io/github/forks/NoMoreFood/Repacls?style=social) ![Github watchers](https://shields.io/github/watchers/NoMoreFood/Repacls?style=social)
- github.com/NoMoreFood/WinPriv ![Github stars](https://shields.io/github/stars/NoMoreFood/WinPriv?style=social) ![Github forks](https://shields.io/github/forks/NoMoreFood/WinPriv?style=social) ![Github watchers](https://shields.io/github/watchers/NoMoreFood/WinPriv?style=social)
- github.com/NoMoreFood/Crypture ![Github stars](https://shields.io/github/stars/NoMoreFood/Crypture?style=social) ![Github forks](https://shields.io/github/forks/NoMoreFood/Crypture?style=social) ![Github watchers](https://shields.io/github/watchers/NoMoreFood/Crypture?style=social)
- github.com/Microsoft/winfile ![Github stars](https://shields.io/github/stars/Microsoft/winfile?style=social) ![Github forks](https://shields.io/github/forks/Microsoft/winfile?style=social) ![Github watchers](https://shields.io/github/watchers/Microsoft/winfile?style=social)
- github.com/mullvad/windows-libraries ![Github stars](https://shields.io/github/stars/mullvad/windows-libraries?style=social) ![Github forks](https://shields.io/github/forks/mullvad/windows-libraries?style=social) ![Github watchers](https://shields.io/github/watchers/mullvad/windows-libraries?style=social)
- github.com/wjcsharp/wintools ![Github stars](https://shields.io/github/stars/wjcsharp/wintools?style=social) ![Github forks](https://shields.io/github/forks/wjcsharp/wintools?style=social) ![Github watchers](https://shields.io/github/watchers/wjcsharp/wintools?style=social)
- github.com/nmgwddj/logs-monitor ![Github stars](https://shields.io/github/stars/nmgwddj/logs-monitor?style=social) ![Github forks](https://shields.io/github/forks/nmgwddj/logs-monitor?style=social) ![Github watchers](https://shields.io/github/watchers/nmgwddj/logs-monitor?style=social)
- github.com/nmgwddj/TaskbarTool ![Github stars](https://shields.io/github/stars/nmgwddj/TaskbarTool?style=social) ![Github forks](https://shields.io/github/forks/nmgwddj/TaskbarTool?style=social) ![Github watchers](https://shields.io/github/watchers/nmgwddj/TaskbarTool?style=social)
- github.com/nmgwddj/DevCon ![Github stars](https://shields.io/github/stars/nmgwddj/DevCon?style=social) ![Github forks](https://shields.io/github/forks/nmgwddj/DevCon?style=social) ![Github watchers](https://shields.io/github/watchers/nmgwddj/DevCon?style=social)
- github.com/nmgwddj/SystemProcessInfo ![Github stars](https://shields.io/github/stars/nmgwddj/SystemProcessInfo?style=social) ![Github forks](https://shields.io/github/forks/nmgwddj/SystemProcessInfo?style=social) ![Github watchers](https://shields.io/github/watchers/nmgwddj/SystemProcessInfo?style=social)
- github.com/nmgwddj/ServiceMgr ![Github stars](https://shields.io/github/stars/nmgwddj/ServiceMgr?style=social) ![Github forks](https://shields.io/github/forks/nmgwddj/ServiceMgr?style=social) ![Github watchers](https://shields.io/github/watchers/nmgwddj/ServiceMgr?style=social)

## etw

- github.com/pierricgimmig/orbitprofiler ![Github stars](https://shields.io/github/stars/pierricgimmig/orbitprofiler?style=social) ![Github forks](https://shields.io/github/forks/pierricgimmig/orbitprofiler?style=social) ![Github watchers](https://shields.io/github/watchers/pierricgimmig/orbitprofiler?style=social)

## wsl/unix

- github.com/Mermeze/wslam (wsl anti malware) ![Github stars](https://shields.io/github/stars/Mermeze/wslam?style=social) ![Github forks](https://shields.io/github/forks/Mermeze/wslam?style=social) ![Github watchers](https://shields.io/github/watchers/Mermeze/wslam?style=social)
- github.com/Biswa96/WSLInstall ![Github stars](https://shields.io/github/stars/Biswa96/WSLInstall?style=social) ![Github forks](https://shields.io/github/forks/Biswa96/WSLInstall?style=social) ![Github watchers](https://shields.io/github/watchers/Biswa96/WSLInstall?style=social)
- github.com/Biswa96/WslReverse ![Github stars](https://shields.io/github/stars/Biswa96/WslReverse?style=social) ![Github forks](https://shields.io/github/forks/Biswa96/WslReverse?style=social) ![Github watchers](https://shields.io/github/watchers/Biswa96/WslReverse?style=social)
- github.com/Biswa96/XConPty ![Github stars](https://shields.io/github/stars/Biswa96/XConPty?style=social) ![Github forks](https://shields.io/github/forks/Biswa96/XConPty?style=social) ![Github watchers](https://shields.io/github/watchers/Biswa96/XConPty?style=social)
- github.com/mintty/wsltty.appx ![Github stars](https://shields.io/github/stars/mintty/wsltty.appx?style=social) ![Github forks](https://shields.io/github/forks/mintty/wsltty.appx?style=social) ![Github watchers](https://shields.io/github/watchers/mintty/wsltty.appx?style=social)

## device tree

- github.com/MartinDrab/VrtuleTree ![Github stars](https://shields.io/github/stars/MartinDrab/VrtuleTree?style=social) ![Github forks](https://shields.io/github/forks/MartinDrab/VrtuleTree?style=social) ![Github watchers](https://shields.io/github/watchers/MartinDrab/VrtuleTree?style=social)

## irp monitor

- github.com/MartinDrab/IRPMon ![Github stars](https://shields.io/github/stars/MartinDrab/IRPMon?style=social) ![Github forks](https://shields.io/github/forks/MartinDrab/IRPMon?style=social) ![Github watchers](https://shields.io/github/watchers/MartinDrab/IRPMon?style=social)

## nt crucial modules

- github.com/MeeSong/Nt-Crucial-Modules ![Github stars](https://shields.io/github/stars/MeeSong/Nt-Crucial-Modules?style=social) ![Github forks](https://shields.io/github/forks/MeeSong/Nt-Crucial-Modules?style=social) ![Github watchers](https://shields.io/github/watchers/MeeSong/Nt-Crucial-Modules?style=social)

## windows kernel driver

- github.com/kkent030315/anycall (x64 Windows kernel code execution via user-mode, arbitrary syscall, vulnerable IOCTLs demonstration) ![Github stars](https://shields.io/github/stars/kkent030315/anycall?style=social) ![Github forks](https://shields.io/github/forks/kkent030315/anycall?style=social) ![Github watchers](https://shields.io/github/watchers/kkent030315/anycall?style=social)
- github.com/yardenshafir/DpcWait (DPC) ![Github stars](https://shields.io/github/stars/yardenshafir/DpcWait?style=social) ![Github forks](https://shields.io/github/forks/yardenshafir/DpcWait?style=social) ![Github watchers](https://shields.io/github/watchers/yardenshafir/DpcWait?style=social)
- github.com/can1357/NtLua (Lua in kernel) ![Github stars](https://shields.io/github/stars/can1357/NtLua?style=social) ![Github forks](https://shields.io/github/forks/can1357/NtLua?style=social) ![Github watchers](https://shields.io/github/watchers/can1357/NtLua?style=social)
- github.com/mrexodia/NtPhp (Php in kernel) ![Github stars](https://shields.io/github/stars/mrexodia/NtPhp?style=social) ![Github forks](https://shields.io/github/forks/mrexodia/NtPhp?style=social) ![Github watchers](https://shields.io/github/watchers/mrexodia/NtPhp?style=social)
- github.com/DownWithUp/CallMon ![Github stars](https://shields.io/github/stars/DownWithUp/CallMon?style=social) ![Github forks](https://shields.io/github/forks/DownWithUp/CallMon?style=social) ![Github watchers](https://shields.io/github/watchers/DownWithUp/CallMon?style=social)
- github.com/BadPlayer555/KernelGDIDraw (GDI) ![Github stars](https://shields.io/github/stars/BadPlayer555/KernelGDIDraw?style=social) ![Github forks](https://shields.io/github/forks/BadPlayer555/KernelGDIDraw?style=social) ![Github watchers](https://shields.io/github/watchers/BadPlayer555/KernelGDIDraw?style=social)
- github.com/alxbrn/km-um-communication ![Github stars](https://shields.io/github/stars/alxbrn/km-um-communication?style=social) ![Github forks](https://shields.io/github/forks/alxbrn/km-um-communication?style=social) ![Github watchers](https://shields.io/github/watchers/alxbrn/km-um-communication?style=social)
- github.com/DavidXanatos/IgnoreACLs ![Github stars](https://shields.io/github/stars/DavidXanatos/IgnoreACLs?style=social) ![Github forks](https://shields.io/github/forks/DavidXanatos/IgnoreACLs?style=social) ![Github watchers](https://shields.io/github/watchers/DavidXanatos/IgnoreACLs?style=social)
- github.com/hfiref0x/KDU (Kernel Driver Utility) ![Github stars](https://shields.io/github/stars/hfiref0x/KDU?style=social) ![Github forks](https://shields.io/github/forks/hfiref0x/KDU?style=social) ![Github watchers](https://shields.io/github/watchers/hfiref0x/KDU?style=social)
- github.com/zhuhuibeishadiao/JunkDriveOpenSource ![Github stars](https://shields.io/github/stars/zhuhuibeishadiao/JunkDriveOpenSource?style=social) ![Github forks](https://shields.io/github/forks/zhuhuibeishadiao/JunkDriveOpenSource?style=social) ![Github watchers](https://shields.io/github/watchers/zhuhuibeishadiao/JunkDriveOpenSource?style=social)
- github.com/dearfuture/DriverTutorial ![Github stars](https://shields.io/github/stars/dearfuture/DriverTutorial?style=social) ![Github forks](https://shields.io/github/forks/dearfuture/DriverTutorial?style=social) ![Github watchers](https://shields.io/github/watchers/dearfuture/DriverTutorial?style=social)
- github.com/G4rb3n/Windows-Driver ![Github stars](https://shields.io/github/stars/G4rb3n/Windows-Driver?style=social) ![Github forks](https://shields.io/github/forks/G4rb3n/Windows-Driver?style=social) ![Github watchers](https://shields.io/github/watchers/G4rb3n/Windows-Driver?style=social)
- github.com/btbd/wpp (Intercepting DeviceControl via WPP) ![Github stars](https://shields.io/github/stars/btbd/wpp?style=social) ![Github forks](https://shields.io/github/forks/btbd/wpp?style=social) ![Github watchers](https://shields.io/github/watchers/btbd/wpp?style=social)
- github.com/maharmstone/smbfs (SMB filesystem driver for Windows) ![Github stars](https://shields.io/github/stars/maharmstone/smbfs?style=social) ![Github forks](https://shields.io/github/forks/maharmstone/smbfs?style=social) ![Github watchers](https://shields.io/github/watchers/maharmstone/smbfs?style=social)
- github.com/maharmstone/btrfs (Windows driver for the next-generation Linux filesystem Btrfs) ![Github stars](https://shields.io/github/stars/maharmstone/btrfs?style=social) ![Github forks](https://shields.io/github/forks/maharmstone/btrfs?style=social) ![Github watchers](https://shields.io/github/watchers/maharmstone/btrfs?style=social)
- github.com/zodiacon/windowskernelprogrammingbook (sample) ![Github stars](https://shields.io/github/stars/zodiacon/windowskernelprogrammingbook?style=social) ![Github forks](https://shields.io/github/forks/zodiacon/windowskernelprogrammingbook?style=social) ![Github watchers](https://shields.io/github/watchers/zodiacon/windowskernelprogrammingbook?style=social)
- github.com/0xcpu/ExecutiveCallbackObjects ![Github stars](https://shields.io/github/stars/0xcpu/ExecutiveCallbackObjects?style=social) ![Github forks](https://shields.io/github/forks/0xcpu/ExecutiveCallbackObjects?style=social) ![Github watchers](https://shields.io/github/watchers/0xcpu/ExecutiveCallbackObjects?style=social)
- github.com/alxbrn/r6s-external-nuklear-socket ![Github stars](https://shields.io/github/stars/alxbrn/r6s-external-nuklear-socket?style=social) ![Github forks](https://shields.io/github/forks/alxbrn/r6s-external-nuklear-socket?style=social) ![Github watchers](https://shields.io/github/watchers/alxbrn/r6s-external-nuklear-socket?style=social)
- github.com/vmcall/dxgkrnl_hook ![Github stars](https://shields.io/github/stars/vmcall/dxgkrnl_hook?style=social) ![Github forks](https://shields.io/github/forks/vmcall/dxgkrnl_hook?style=social) ![Github watchers](https://shields.io/github/watchers/vmcall/dxgkrnl_hook?style=social)
- github.com/alxbrn/kdmapper-1803-1903 ![Github stars](https://shields.io/github/stars/alxbrn/kdmapper-1803-1903?style=social) ![Github forks](https://shields.io/github/forks/alxbrn/kdmapper-1803-1903?style=social) ![Github watchers](https://shields.io/github/watchers/alxbrn/kdmapper-1803-1903?style=social)
- github.com/juniorjacob/readwrite-kernel-stable ![Github stars](https://shields.io/github/stars/juniorjacob/readwrite-kernel-stable?style=social) ![Github forks](https://shields.io/github/forks/juniorjacob/readwrite-kernel-stable?style=social) ![Github watchers](https://shields.io/github/watchers/juniorjacob/readwrite-kernel-stable?style=social)
- github.com/mstefanowich/IsFileSigned ![Github stars](https://shields.io/github/stars/mstefanowich/IsFileSigned?style=social) ![Github forks](https://shields.io/github/forks/mstefanowich/IsFileSigned?style=social) ![Github watchers](https://shields.io/github/watchers/mstefanowich/IsFileSigned?style=social)
- github.com/apriorit/antirootkit-anti-splicer ![Github stars](https://shields.io/github/stars/apriorit/antirootkit-anti-splicer?style=social) ![Github forks](https://shields.io/github/forks/apriorit/antirootkit-anti-splicer?style=social) ![Github watchers](https://shields.io/github/watchers/apriorit/antirootkit-anti-splicer?style=social)
- github.com/Mouka-Yang/KernelDriverDemo ![Github stars](https://shields.io/github/stars/Mouka-Yang/KernelDriverDemo?style=social) ![Github forks](https://shields.io/github/forks/Mouka-Yang/KernelDriverDemo?style=social) ![Github watchers](https://shields.io/github/watchers/Mouka-Yang/KernelDriverDemo?style=social)
- github.com/tomLadder/WinLib ![Github stars](https://shields.io/github/stars/tomLadder/WinLib?style=social) ![Github forks](https://shields.io/github/forks/tomLadder/WinLib?style=social) ![Github watchers](https://shields.io/github/watchers/tomLadder/WinLib?style=social)
- github.com/coltonon/MoaRpm ![Github stars](https://shields.io/github/stars/coltonon/MoaRpm?style=social) ![Github forks](https://shields.io/github/forks/coltonon/MoaRpm?style=social) ![Github watchers](https://shields.io/github/watchers/coltonon/MoaRpm?style=social)
- github.com/wanttobeno/ProcessManager_Ring0 ![Github stars](https://shields.io/github/stars/wanttobeno/ProcessManager_Ring0?style=social) ![Github forks](https://shields.io/github/forks/wanttobeno/ProcessManager_Ring0?style=social) ![Github watchers](https://shields.io/github/watchers/wanttobeno/ProcessManager_Ring0?style=social)
- github.com/wanttobeno/Win_Driver_Mouse_And_Key ![Github stars](https://shields.io/github/stars/wanttobeno/Win_Driver_Mouse_And_Key?style=social) ![Github forks](https://shields.io/github/forks/wanttobeno/Win_Driver_Mouse_And_Key?style=social) ![Github watchers](https://shields.io/github/watchers/wanttobeno/Win_Driver_Mouse_And_Key?style=social)
- github.com/wanttobeno/Win64DriverStudy_Src ![Github stars](https://shields.io/github/stars/wanttobeno/Win64DriverStudy_Src?style=social) ![Github forks](https://shields.io/github/forks/wanttobeno/Win64DriverStudy_Src?style=social) ![Github watchers](https://shields.io/github/watchers/wanttobeno/Win64DriverStudy_Src?style=social)
- github.com/tdevuser/MalwFinder ![Github stars](https://shields.io/github/stars/tdevuser/MalwFinder?style=social) ![Github forks](https://shields.io/github/forks/tdevuser/MalwFinder?style=social) ![Github watchers](https://shields.io/github/watchers/tdevuser/MalwFinder?style=social)
- github.com/Sqdwr/WriteFile_IRP ![Github stars](https://shields.io/github/stars/Sqdwr/WriteFile_IRP?style=social) ![Github forks](https://shields.io/github/forks/Sqdwr/WriteFile_IRP?style=social) ![Github watchers](https://shields.io/github/watchers/Sqdwr/WriteFile_IRP?style=social)
- github.com/nmgwddj/learn-windows-drivers ![Github stars](https://shields.io/github/stars/nmgwddj/learn-windows-drivers?style=social) ![Github forks](https://shields.io/github/forks/nmgwddj/learn-windows-drivers?style=social) ![Github watchers](https://shields.io/github/watchers/nmgwddj/learn-windows-drivers?style=social)
- github.com/mq1n/EasyRing0 ![Github stars](https://shields.io/github/stars/mq1n/EasyRing0?style=social) ![Github forks](https://shields.io/github/forks/mq1n/EasyRing0?style=social) ![Github watchers](https://shields.io/github/watchers/mq1n/EasyRing0?style=social)

## windows kernel driver with c++ runtime

- github.com/MiroKaku/ucxxrt (R3 / R0 C++ Runtime Lib) ![Github stars](https://shields.io/github/stars/MiroKaku/ucxxrt?style=social) ![Github forks](https://shields.io/github/forks/MiroKaku/ucxxrt?style=social) ![Github watchers](https://shields.io/github/watchers/MiroKaku/ucxxrt?style=social)
- github.com/jxy-s/stlkrn (C++ STL in the Windows Kernel with C++ Exception Support) ![Github stars](https://shields.io/github/stars/jxy-s/stlkrn?style=social) ![Github forks](https://shields.io/github/forks/jxy-s/stlkrn?style=social) ![Github watchers](https://shields.io/github/watchers/jxy-s/stlkrn?style=social)
- github.com/r1cky33/kernel_gdi_renderer ![Github stars](https://shields.io/github/stars/r1cky33/kernel_gdi_renderer?style=social) ![Github forks](https://shields.io/github/forks/r1cky33/kernel_gdi_renderer?style=social) ![Github watchers](https://shields.io/github/watchers/r1cky33/kernel_gdi_renderer?style=social)
- github.com/haram/kernel_library ![Github stars](https://shields.io/github/stars/haram/kernel_library?style=social) ![Github forks](https://shields.io/github/forks/haram/kernel_library?style=social) ![Github watchers](https://shields.io/github/watchers/haram/kernel_library?style=social)
- github.com/avakar/vcrtl ![Github stars](https://shields.io/github/stars/avakar/vcrtl?style=social) ![Github forks](https://shields.io/github/forks/avakar/vcrtl?style=social) ![Github watchers](https://shields.io/github/watchers/avakar/vcrtl?style=social)
- github.com/ZhanLang/msddk ![Github stars](https://shields.io/github/stars/ZhanLang/msddk?style=social) ![Github forks](https://shields.io/github/forks/ZhanLang/msddk?style=social) ![Github watchers](https://shields.io/github/watchers/ZhanLang/msddk?style=social)
- github.com/DragonQuestHero/Kernel-Force-Delete (force delete file) ![Github stars](https://shields.io/github/stars/DragonQuestHero/Kernel-Force-Delete?style=social) ![Github forks](https://shields.io/github/forks/DragonQuestHero/Kernel-Force-Delete?style=social) ![Github watchers](https://shields.io/github/watchers/DragonQuestHero/Kernel-Force-Delete?style=social)
- github.com/MeeSong/WDKExt ![Github stars](https://shields.io/github/stars/MeeSong/WDKExt?style=social) ![Github forks](https://shields.io/github/forks/MeeSong/WDKExt?style=social) ![Github watchers](https://shields.io/github/watchers/MeeSong/WDKExt?style=social)
- github.com/HoShiMin/Kernel-Bridge (power) ![Github stars](https://shields.io/github/stars/HoShiMin/Kernel-Bridge?style=social) ![Github forks](https://shields.io/github/forks/HoShiMin/Kernel-Bridge?style=social) ![Github watchers](https://shields.io/github/watchers/HoShiMin/Kernel-Bridge?style=social)
- github.com/wjcsharp/Common ![Github stars](https://shields.io/github/stars/wjcsharp/Common?style=social) ![Github forks](https://shields.io/github/forks/wjcsharp/Common?style=social) ![Github watchers](https://shields.io/github/watchers/wjcsharp/Common?style=social)
- github.com/ExpLife/DriverSTL ![Github stars](https://shields.io/github/stars/ExpLife/DriverSTL?style=social) ![Github forks](https://shields.io/github/forks/ExpLife/DriverSTL?style=social) ![Github watchers](https://shields.io/github/watchers/ExpLife/DriverSTL?style=social)
- github.com/sysprogs/BazisLib ![Github stars](https://shields.io/github/stars/sysprogs/BazisLib?style=social) ![Github forks](https://shields.io/github/forks/sysprogs/BazisLib?style=social) ![Github watchers](https://shields.io/github/watchers/sysprogs/BazisLib?style=social)
- github.com/AmrThabet/winSRDF ![Github stars](https://shields.io/github/stars/AmrThabet/winSRDF?style=social) ![Github forks](https://shields.io/github/forks/AmrThabet/winSRDF?style=social) ![Github watchers](https://shields.io/github/watchers/AmrThabet/winSRDF?style=social)
- github.com/sidyhe/dxx ![Github stars](https://shields.io/github/stars/sidyhe/dxx?style=social) ![Github forks](https://shields.io/github/forks/sidyhe/dxx?style=social) ![Github watchers](https://shields.io/github/watchers/sidyhe/dxx?style=social)
- github.com/zer0mem/libc ![Github stars](https://shields.io/github/stars/zer0mem/libc?style=social) ![Github forks](https://shields.io/github/forks/zer0mem/libc?style=social) ![Github watchers](https://shields.io/github/watchers/zer0mem/libc?style=social)
- github.com/eladraz/XDK ![Github stars](https://shields.io/github/stars/eladraz/XDK?style=social) ![Github forks](https://shields.io/github/forks/eladraz/XDK?style=social) ![Github watchers](https://shields.io/github/watchers/eladraz/XDK?style=social)
- github.com/vic4key/Cat-Driver ![Github stars](https://shields.io/github/stars/vic4key/Cat-Driver?style=social) ![Github forks](https://shields.io/github/forks/vic4key/Cat-Driver?style=social) ![Github watchers](https://shields.io/github/watchers/vic4key/Cat-Driver?style=social)
- github.com/AndrewGaspar/km-stl ![Github stars](https://shields.io/github/stars/AndrewGaspar/km-stl?style=social) ![Github forks](https://shields.io/github/forks/AndrewGaspar/km-stl?style=social) ![Github watchers](https://shields.io/github/watchers/AndrewGaspar/km-stl?style=social)
- github.com/zer0mem/KernelProject ![Github stars](https://shields.io/github/stars/zer0mem/KernelProject?style=social) ![Github forks](https://shields.io/github/forks/zer0mem/KernelProject?style=social) ![Github watchers](https://shields.io/github/watchers/zer0mem/KernelProject?style=social)
- github.com/zer0mem/miniCommon ![Github stars](https://shields.io/github/stars/zer0mem/miniCommon?style=social) ![Github forks](https://shields.io/github/forks/zer0mem/miniCommon?style=social) ![Github watchers](https://shields.io/github/watchers/zer0mem/miniCommon?style=social)
- github.com/jackqk/mystudy ![Github stars](https://shields.io/github/stars/jackqk/mystudy?style=social) ![Github forks](https://shields.io/github/forks/jackqk/mystudy?style=social) ![Github watchers](https://shields.io/github/watchers/jackqk/mystudy?style=social)
- github.com/yogendersolanki91/Kernel-Driver-Example ![Github stars](https://shields.io/github/stars/yogendersolanki91/Kernel-Driver-Example?style=social) ![Github forks](https://shields.io/github/forks/yogendersolanki91/Kernel-Driver-Example?style=social) ![Github watchers](https://shields.io/github/watchers/yogendersolanki91/Kernel-Driver-Example?style=social)

## blackbone

- github.com/AbinMM/MemDllLoader_Blackbone ![Github stars](https://shields.io/github/stars/AbinMM/MemDllLoader_Blackbone?style=social) ![Github forks](https://shields.io/github/forks/AbinMM/MemDllLoader_Blackbone?style=social) ![Github watchers](https://shields.io/github/watchers/AbinMM/MemDllLoader_Blackbone?style=social)
- github.com/hzqst/unicorn_pe ![Github stars](https://shields.io/github/stars/hzqst/unicorn_pe?style=social) ![Github forks](https://shields.io/github/forks/hzqst/unicorn_pe?style=social) ![Github watchers](https://shields.io/github/watchers/hzqst/unicorn_pe?style=social)
- github.com/nofvcks/AimKit-Pasted-Driver ![Github stars](https://shields.io/github/stars/nofvcks/AimKit-Pasted-Driver?style=social) ![Github forks](https://shields.io/github/forks/nofvcks/AimKit-Pasted-Driver?style=social) ![Github watchers](https://shields.io/github/watchers/nofvcks/AimKit-Pasted-Driver?style=social)
- github.com/alexpsp00/x-elite-loader ![Github stars](https://shields.io/github/stars/alexpsp00/x-elite-loader?style=social) ![Github forks](https://shields.io/github/forks/alexpsp00/x-elite-loader?style=social) ![Github watchers](https://shields.io/github/watchers/alexpsp00/x-elite-loader?style=social)
- github.com/DarthTon/Xenos ![Github stars](https://shields.io/github/stars/DarthTon/Xenos?style=social) ![Github forks](https://shields.io/github/forks/DarthTon/Xenos?style=social) ![Github watchers](https://shields.io/github/watchers/DarthTon/Xenos?style=social)
- github.com/DarthTon/Blackbone ![Github stars](https://shields.io/github/stars/DarthTon/Blackbone?style=social) ![Github forks](https://shields.io/github/forks/DarthTon/Blackbone?style=social) ![Github watchers](https://shields.io/github/watchers/DarthTon/Blackbone?style=social)

## hidinput

- github.com/changeofpace/MouHidInputHook ![Github stars](https://shields.io/github/stars/changeofpace/MouHidInputHook?style=social) ![Github forks](https://shields.io/github/forks/changeofpace/MouHidInputHook?style=social) ![Github watchers](https://shields.io/github/watchers/changeofpace/MouHidInputHook?style=social)
- github.com/hawku/TabletDriver ![Github stars](https://shields.io/github/stars/hawku/TabletDriver?style=social) ![Github forks](https://shields.io/github/forks/hawku/TabletDriver?style=social) ![Github watchers](https://shields.io/github/watchers/hawku/TabletDriver?style=social)
- github.com/ViGEm/HidGuardian ![Github stars](https://shields.io/github/stars/ViGEm/HidGuardian?style=social) ![Github forks](https://shields.io/github/forks/ViGEm/HidGuardian?style=social) ![Github watchers](https://shields.io/github/watchers/ViGEm/HidGuardian?style=social)
- github.com/ecologylab/EcoTUIODriver ![Github stars](https://shields.io/github/stars/ecologylab/EcoTUIODriver?style=social) ![Github forks](https://shields.io/github/forks/ecologylab/EcoTUIODriver?style=social) ![Github watchers](https://shields.io/github/watchers/ecologylab/EcoTUIODriver?style=social)
- github.com/djpnewton/vmulti ![Github stars](https://shields.io/github/stars/djpnewton/vmulti?style=social) ![Github forks](https://shields.io/github/forks/djpnewton/vmulti?style=social) ![Github watchers](https://shields.io/github/watchers/djpnewton/vmulti?style=social)
- github.com/duzhi5368/FKHIDKeyboardSimTest (support usb) ![Github stars](https://shields.io/github/stars/duzhi5368/FKHIDKeyboardSimTest?style=social) ![Github forks](https://shields.io/github/forks/duzhi5368/FKHIDKeyboardSimTest?style=social) ![Github watchers](https://shields.io/github/watchers/duzhi5368/FKHIDKeyboardSimTest?style=social)
- github.com/Jehoash/WinIO3.0 ![Github stars](https://shields.io/github/stars/Jehoash/WinIO3.0?style=social) ![Github forks](https://shields.io/github/forks/Jehoash/WinIO3.0?style=social) ![Github watchers](https://shields.io/github/watchers/Jehoash/WinIO3.0?style=social)

## dkom

- github.com/alal4465/Win_Rootkit (Kernel RAT X86) ![Github stars](https://shields.io/github/stars/alal4465/Win_Rootkit?style=social) ![Github forks](https://shields.io/github/forks/alal4465/Win_Rootkit?style=social) ![Github watchers](https://shields.io/github/watchers/alal4465/Win_Rootkit?style=social)
- github.com/waryas/EUPMAccess ![Github stars](https://shields.io/github/stars/waryas/EUPMAccess?style=social) ![Github forks](https://shields.io/github/forks/waryas/EUPMAccess?style=social) ![Github watchers](https://shields.io/github/watchers/waryas/EUPMAccess?style=social)
- github.com/notscimmy/pplib ![Github stars](https://shields.io/github/stars/notscimmy/pplib?style=social) ![Github forks](https://shields.io/github/forks/notscimmy/pplib?style=social) ![Github watchers](https://shields.io/github/watchers/notscimmy/pplib?style=social)
- blog.csdn.net/zhuhuibeishadiao/article/details/51136650 (get process full path name)
- bbs.pediy.com/thread-96427.htm (modify process image name)
- github.com/ZhuHuiBeiShaDiao/PathModification ![Github stars](https://shields.io/github/stars/ZhuHuiBeiShaDiao/PathModification?style=social) ![Github forks](https://shields.io/github/forks/ZhuHuiBeiShaDiao/PathModification?style=social) ![Github watchers](https://shields.io/github/watchers/ZhuHuiBeiShaDiao/PathModification?style=social)
- github.com/ZhuHuiBeiShaDiao/NewHideDriverEx ![Github stars](https://shields.io/github/stars/ZhuHuiBeiShaDiao/NewHideDriverEx?style=social) ![Github forks](https://shields.io/github/forks/ZhuHuiBeiShaDiao/NewHideDriverEx?style=social) ![Github watchers](https://shields.io/github/watchers/ZhuHuiBeiShaDiao/NewHideDriverEx?style=social)
- github.com/Sqdwr/HideDriver ![Github stars](https://shields.io/github/stars/Sqdwr/HideDriver?style=social) ![Github forks](https://shields.io/github/forks/Sqdwr/HideDriver?style=social) ![Github watchers](https://shields.io/github/watchers/Sqdwr/HideDriver?style=social)
- github.com/nbqofficial/HideDriver ![Github stars](https://shields.io/github/stars/nbqofficial/HideDriver?style=social) ![Github forks](https://shields.io/github/forks/nbqofficial/HideDriver?style=social) ![Github watchers](https://shields.io/github/watchers/nbqofficial/HideDriver?style=social)
- github.com/landhb/HideProcess ![Github stars](https://shields.io/github/stars/landhb/HideProcess?style=social) ![Github forks](https://shields.io/github/forks/landhb/HideProcess?style=social) ![Github watchers](https://shields.io/github/watchers/landhb/HideProcess?style=social)
- github.com/tfairane/DKOM ![Github stars](https://shields.io/github/stars/tfairane/DKOM?style=social) ![Github forks](https://shields.io/github/forks/tfairane/DKOM?style=social) ![Github watchers](https://shields.io/github/watchers/tfairane/DKOM?style=social)

## ssdt hook

- github.com/crvvdev/MasterHide (x64) ![Github stars](https://shields.io/github/stars/crvvdev/MasterHide?style=social) ![Github forks](https://shields.io/github/forks/crvvdev/MasterHide?style=social) ![Github watchers](https://shields.io/github/watchers/crvvdev/MasterHide?style=social)
- github.com/iPower/KasperskyHook ![Github stars](https://shields.io/github/stars/iPower/KasperskyHook?style=social) ![Github forks](https://shields.io/github/forks/iPower/KasperskyHook?style=social) ![Github watchers](https://shields.io/github/watchers/iPower/KasperskyHook?style=social)
- github.com/Sqdwr/64-bits-inserthook ![Github stars](https://shields.io/github/stars/Sqdwr/64-bits-inserthook?style=social) ![Github forks](https://shields.io/github/forks/Sqdwr/64-bits-inserthook?style=social) ![Github watchers](https://shields.io/github/watchers/Sqdwr/64-bits-inserthook?style=social)
- github.com/int0/ProcessIsolator ![Github stars](https://shields.io/github/stars/int0/ProcessIsolator?style=social) ![Github forks](https://shields.io/github/forks/int0/ProcessIsolator?style=social) ![Github watchers](https://shields.io/github/watchers/int0/ProcessIsolator?style=social)
- github.com/mrexodia/TitanHide (x64dbg Plugin)-(DragonQuestHero Suggest) ![Github stars](https://shields.io/github/stars/mrexodia/TitanHide?style=social) ![Github forks](https://shields.io/github/forks/mrexodia/TitanHide?style=social) ![Github watchers](https://shields.io/github/watchers/mrexodia/TitanHide?style=social)
- github.com/papadp/shd ![Github stars](https://shields.io/github/stars/papadp/shd?style=social) ![Github forks](https://shields.io/github/forks/papadp/shd?style=social) ![Github watchers](https://shields.io/github/watchers/papadp/shd?style=social)
- github.com/bronzeMe/SSDT_Hook_x64 ![Github stars](https://shields.io/github/stars/bronzeMe/SSDT_Hook_x64?style=social) ![Github forks](https://shields.io/github/forks/bronzeMe/SSDT_Hook_x64?style=social) ![Github watchers](https://shields.io/github/watchers/bronzeMe/SSDT_Hook_x64?style=social)
- github.com/s18leoare/Hackshield-Driver-Bypass ![Github stars](https://shields.io/github/stars/s18leoare/Hackshield-Driver-Bypass?style=social) ![Github forks](https://shields.io/github/forks/s18leoare/Hackshield-Driver-Bypass?style=social) ![Github watchers](https://shields.io/github/watchers/s18leoare/Hackshield-Driver-Bypass?style=social)
- github.com/sincoder/hidedir ![Github stars](https://shields.io/github/stars/sincoder/hidedir?style=social) ![Github forks](https://shields.io/github/forks/sincoder/hidedir?style=social) ![Github watchers](https://shields.io/github/watchers/sincoder/hidedir?style=social)
- github.com/wyrover/HKkernelDbg ![Github stars](https://shields.io/github/stars/wyrover/HKkernelDbg?style=social) ![Github forks](https://shields.io/github/forks/wyrover/HKkernelDbg?style=social) ![Github watchers](https://shields.io/github/watchers/wyrover/HKkernelDbg?style=social)
- github.com/CherryZY/Process_Protect_Module ![Github stars](https://shields.io/github/stars/CherryZY/Process_Protect_Module?style=social) ![Github forks](https://shields.io/github/forks/CherryZY/Process_Protect_Module?style=social) ![Github watchers](https://shields.io/github/watchers/CherryZY/Process_Protect_Module?style=social)
- github.com/weixu8/RegistryMonitor ![Github stars](https://shields.io/github/stars/weixu8/RegistryMonitor?style=social) ![Github forks](https://shields.io/github/forks/weixu8/RegistryMonitor?style=social) ![Github watchers](https://shields.io/github/watchers/weixu8/RegistryMonitor?style=social)
- github.com/nmgwddj/Learn-Windows-Drivers ![Github stars](https://shields.io/github/stars/nmgwddj/Learn-Windows-Drivers?style=social) ![Github forks](https://shields.io/github/forks/nmgwddj/Learn-Windows-Drivers?style=social) ![Github watchers](https://shields.io/github/watchers/nmgwddj/Learn-Windows-Drivers?style=social)

## eat/iat/object/irp/iat hook

- github.com/jguo52/IOCTL-hook ![Github stars](https://shields.io/github/stars/jguo52/IOCTL-hook?style=social) ![Github forks](https://shields.io/github/forks/jguo52/IOCTL-hook?style=social) ![Github watchers](https://shields.io/github/watchers/jguo52/IOCTL-hook?style=social)
- github.com/hugsy/CFB (Irp Hook) ![Github stars](https://shields.io/github/stars/hugsy/CFB?style=social) ![Github forks](https://shields.io/github/forks/hugsy/CFB?style=social) ![Github watchers](https://shields.io/github/watchers/hugsy/CFB?style=social)
- github.com/Rat431/ColdKernel_KUSER ![Github stars](https://shields.io/github/stars/Rat431/ColdKernel_KUSER?style=social) ![Github forks](https://shields.io/github/forks/Rat431/ColdKernel_KUSER?style=social) ![Github watchers](https://shields.io/github/watchers/Rat431/ColdKernel_KUSER?style=social)
- github.com/hasherezade/IAT_patcher ![Github stars](https://shields.io/github/stars/hasherezade/IAT_patcher?style=social) ![Github forks](https://shields.io/github/forks/hasherezade/IAT_patcher?style=social) ![Github watchers](https://shields.io/github/watchers/hasherezade/IAT_patcher?style=social)
- github.com/Cyrex1337/hook.lib ![Github stars](https://shields.io/github/stars/Cyrex1337/hook.lib?style=social) ![Github forks](https://shields.io/github/forks/Cyrex1337/hook.lib?style=social) ![Github watchers](https://shields.io/github/watchers/Cyrex1337/hook.lib?style=social)
- github.com/hMihaiDavid/hooks ![Github stars](https://shields.io/github/stars/hMihaiDavid/hooks?style=social) ![Github forks](https://shields.io/github/forks/hMihaiDavid/hooks?style=social) ![Github watchers](https://shields.io/github/watchers/hMihaiDavid/hooks?style=social)
- github.com/Scorbutics/IATHook ![Github stars](https://shields.io/github/stars/Scorbutics/IATHook?style=social) ![Github forks](https://shields.io/github/forks/Scorbutics/IATHook?style=social) ![Github watchers](https://shields.io/github/watchers/Scorbutics/IATHook?style=social)
- github.com/amazadota/AFD-HOOK- ![Github stars](https://shields.io/github/stars/amazadota/AFD-HOOK-?style=social) ![Github forks](https://shields.io/github/forks/amazadota/AFD-HOOK-?style=social) ![Github watchers](https://shields.io/github/watchers/amazadota/AFD-HOOK-?style=social)
- github.com/wyyqyl/HookIAT ![Github stars](https://shields.io/github/stars/wyyqyl/HookIAT?style=social) ![Github forks](https://shields.io/github/forks/wyyqyl/HookIAT?style=social) ![Github watchers](https://shields.io/github/watchers/wyyqyl/HookIAT?style=social)
- github.com/smore007/remote-iat-hook ![Github stars](https://shields.io/github/stars/smore007/remote-iat-hook?style=social) ![Github forks](https://shields.io/github/forks/smore007/remote-iat-hook?style=social) ![Github watchers](https://shields.io/github/watchers/smore007/remote-iat-hook?style=social)
- github.com/m0n0ph1/IAT-Hooking-Revisited ![Github stars](https://shields.io/github/stars/m0n0ph1/IAT-Hooking-Revisited?style=social) ![Github forks](https://shields.io/github/forks/m0n0ph1/IAT-Hooking-Revisited?style=social) ![Github watchers](https://shields.io/github/watchers/m0n0ph1/IAT-Hooking-Revisited?style=social)
- github.com/xiaomagexiao/GameDll ![Github stars](https://shields.io/github/stars/xiaomagexiao/GameDll?style=social) ![Github forks](https://shields.io/github/forks/xiaomagexiao/GameDll?style=social) ![Github watchers](https://shields.io/github/watchers/xiaomagexiao/GameDll?style=social)
- github.com/HollyDi/Ring0Hook ![Github stars](https://shields.io/github/stars/HollyDi/Ring0Hook?style=social) ![Github forks](https://shields.io/github/forks/HollyDi/Ring0Hook?style=social) ![Github watchers](https://shields.io/github/watchers/HollyDi/Ring0Hook?style=social)
- github.com/mgeeky/prc_xchk ![Github stars](https://shields.io/github/stars/mgeeky/prc_xchk?style=social) ![Github forks](https://shields.io/github/forks/mgeeky/prc_xchk?style=social) ![Github watchers](https://shields.io/github/watchers/mgeeky/prc_xchk?style=social)
- github.com/tinysec/iathook ![Github stars](https://shields.io/github/stars/tinysec/iathook?style=social) ![Github forks](https://shields.io/github/forks/tinysec/iathook?style=social) ![Github watchers](https://shields.io/github/watchers/tinysec/iathook?style=social)

## InfinityHook

- github.com/FiYHer/InfinityHookPro ![Github stars](https://shields.io/github/stars/FiYHer/InfinityHookPro?style=social) ![Github forks](https://shields.io/github/forks/FiYHer/InfinityHookPro?style=social) ![Github watchers](https://shields.io/github/watchers/FiYHer/InfinityHookPro?style=social)
- github.com/huoji120/MakeInfinityHookGreatAgain ![Github stars](https://shields.io/github/stars/huoji120/MakeInfinityHookGreatAgain?style=social) ![Github forks](https://shields.io/github/forks/huoji120/MakeInfinityHookGreatAgain?style=social) ![Github watchers](https://shields.io/github/watchers/huoji120/MakeInfinityHookGreatAgain?style=social)
- github.com/p4xon/SyscallHook ![Github stars](https://shields.io/github/stars/p4xon/SyscallHook?style=social) ![Github forks](https://shields.io/github/forks/p4xon/SyscallHook?style=social) ![Github watchers](https://shields.io/github/watchers/p4xon/SyscallHook?style=social)
- yanjuan.xyz/2019/08/syscallhook/
- github.com/huoji120/huoji_debuger ![Github stars](https://shields.io/github/stars/huoji120/huoji_debuger?style=social) ![Github forks](https://shields.io/github/forks/huoji120/huoji_debuger?style=social) ![Github watchers](https://shields.io/github/watchers/huoji120/huoji_debuger?style=social)
- github.com/everdox/InfinityHook ![Github stars](https://shields.io/github/stars/everdox/InfinityHook?style=social) ![Github forks](https://shields.io/github/forks/everdox/InfinityHook?style=social) ![Github watchers](https://shields.io/github/watchers/everdox/InfinityHook?style=social)

## inline hook

- github.com/adrianyy/kernelhook ![Github stars](https://shields.io/github/stars/adrianyy/kernelhook?style=social) ![Github forks](https://shields.io/github/forks/adrianyy/kernelhook?style=social) ![Github watchers](https://shields.io/github/watchers/adrianyy/kernelhook?style=social)
- github.com/gfreivasc/VMTHook ![Github stars](https://shields.io/github/stars/gfreivasc/VMTHook?style=social) ![Github forks](https://shields.io/github/forks/gfreivasc/VMTHook?style=social) ![Github watchers](https://shields.io/github/watchers/gfreivasc/VMTHook?style=social)
- github.com/zhipeng515/MemberFunctionHook （member function hook） ![Github stars](https://shields.io/github/stars/zhipeng515/MemberFunctionHook?style=social) ![Github forks](https://shields.io/github/forks/zhipeng515/MemberFunctionHook?style=social) ![Github watchers](https://shields.io/github/watchers/zhipeng515/MemberFunctionHook?style=social)
- github.com/windy32/win32-console-hook-lib ![Github stars](https://shields.io/github/stars/windy32/win32-console-hook-lib?style=social) ![Github forks](https://shields.io/github/forks/windy32/win32-console-hook-lib?style=social) ![Github watchers](https://shields.io/github/watchers/windy32/win32-console-hook-lib?style=social)
- github.com/M0rtale/Universal-WndProc-Hook ![Github stars](https://shields.io/github/stars/M0rtale/Universal-WndProc-Hook?style=social) ![Github forks](https://shields.io/github/forks/M0rtale/Universal-WndProc-Hook?style=social) ![Github watchers](https://shields.io/github/watchers/M0rtale/Universal-WndProc-Hook?style=social)
- github.com/a7031x/HookApi ![Github stars](https://shields.io/github/stars/a7031x/HookApi?style=social) ![Github forks](https://shields.io/github/forks/a7031x/HookApi?style=social) ![Github watchers](https://shields.io/github/watchers/a7031x/HookApi?style=social)
- github.com/blaquee/APCHook ![Github stars](https://shields.io/github/stars/blaquee/APCHook?style=social) ![Github forks](https://shields.io/github/forks/blaquee/APCHook?style=social) ![Github watchers](https://shields.io/github/watchers/blaquee/APCHook?style=social)
- github.com/simonberson/ChromeURLSniffer ![Github stars](https://shields.io/github/stars/simonberson/ChromeURLSniffer?style=social) ![Github forks](https://shields.io/github/forks/simonberson/ChromeURLSniffer?style=social) ![Github watchers](https://shields.io/github/watchers/simonberson/ChromeURLSniffer?style=social)
- github.com/codereversing/sehveh_hook ![Github stars](https://shields.io/github/stars/codereversing/sehveh_hook?style=social) ![Github forks](https://shields.io/github/forks/codereversing/sehveh_hook?style=social) ![Github watchers](https://shields.io/github/watchers/codereversing/sehveh_hook?style=social)
- github.com/Matviy/LeagueReplayHook ![Github stars](https://shields.io/github/stars/Matviy/LeagueReplayHook?style=social) ![Github forks](https://shields.io/github/forks/Matviy/LeagueReplayHook?style=social) ![Github watchers](https://shields.io/github/watchers/Matviy/LeagueReplayHook?style=social)
- github.com/jonasblunck/DP ![Github stars](https://shields.io/github/stars/jonasblunck/DP?style=social) ![Github forks](https://shields.io/github/forks/jonasblunck/DP?style=social) ![Github watchers](https://shields.io/github/watchers/jonasblunck/DP?style=social)
- github.com/XBased/xhook ![Github stars](https://shields.io/github/stars/XBased/xhook?style=social) ![Github forks](https://shields.io/github/forks/XBased/xhook?style=social) ![Github watchers](https://shields.io/github/watchers/XBased/xhook?style=social)
- github.com/rokups/hooker ![Github stars](https://shields.io/github/stars/rokups/hooker?style=social) ![Github forks](https://shields.io/github/forks/rokups/hooker?style=social) ![Github watchers](https://shields.io/github/watchers/rokups/hooker?style=social)
- github.com/Ayuto/DynamicHooks ![Github stars](https://shields.io/github/stars/Ayuto/DynamicHooks?style=social) ![Github forks](https://shields.io/github/forks/Ayuto/DynamicHooks?style=social) ![Github watchers](https://shields.io/github/watchers/Ayuto/DynamicHooks?style=social)
- github.com/sincoder/wow64hook ![Github stars](https://shields.io/github/stars/sincoder/wow64hook?style=social) ![Github forks](https://shields.io/github/forks/sincoder/wow64hook?style=social) ![Github watchers](https://shields.io/github/watchers/sincoder/wow64hook?style=social)
- github.com/strobejb/sslhook ![Github stars](https://shields.io/github/stars/strobejb/sslhook?style=social) ![Github forks](https://shields.io/github/forks/strobejb/sslhook?style=social) ![Github watchers](https://shields.io/github/watchers/strobejb/sslhook?style=social)
- github.com/petrgeorgievsky/gtaRenderHook ![Github stars](https://shields.io/github/stars/petrgeorgievsky/gtaRenderHook?style=social) ![Github forks](https://shields.io/github/forks/petrgeorgievsky/gtaRenderHook?style=social) ![Github watchers](https://shields.io/github/watchers/petrgeorgievsky/gtaRenderHook?style=social)
- github.com/WopsS/RenHook ![Github stars](https://shields.io/github/stars/WopsS/RenHook?style=social) ![Github forks](https://shields.io/github/forks/WopsS/RenHook?style=social) ![Github watchers](https://shields.io/github/watchers/WopsS/RenHook?style=social)
- github.com/chinatiny/InlineHookLib (R3 & R0) ![Github stars](https://shields.io/github/stars/chinatiny/InlineHookLib?style=social) ![Github forks](https://shields.io/github/forks/chinatiny/InlineHookLib?style=social) ![Github watchers](https://shields.io/github/watchers/chinatiny/InlineHookLib?style=social)
- github.com/tongzeyu/HookSysenter ![Github stars](https://shields.io/github/stars/tongzeyu/HookSysenter?style=social) ![Github forks](https://shields.io/github/forks/tongzeyu/HookSysenter?style=social) ![Github watchers](https://shields.io/github/watchers/tongzeyu/HookSysenter?style=social)
- github.com/idkwim/frookSINATRA  (x64 sysenter hook) ![Github stars](https://shields.io/github/stars/idkwim/frookSINATRA?style=social) ![Github forks](https://shields.io/github/forks/idkwim/frookSINATRA?style=social) ![Github watchers](https://shields.io/github/watchers/idkwim/frookSINATRA?style=social)
- github.com/VideoCardGuy/HideProcessInTaskmgr ![Github stars](https://shields.io/github/stars/VideoCardGuy/HideProcessInTaskmgr?style=social) ![Github forks](https://shields.io/github/forks/VideoCardGuy/HideProcessInTaskmgr?style=social) ![Github watchers](https://shields.io/github/watchers/VideoCardGuy/HideProcessInTaskmgr?style=social)
- github.com/MalwareTech/FstHook ![Github stars](https://shields.io/github/stars/MalwareTech/FstHook?style=social) ![Github forks](https://shields.io/github/forks/MalwareTech/FstHook?style=social) ![Github watchers](https://shields.io/github/watchers/MalwareTech/FstHook?style=social)
- github.com/Menooker/FishHook ![Github stars](https://shields.io/github/stars/Menooker/FishHook?style=social) ![Github forks](https://shields.io/github/forks/Menooker/FishHook?style=social) ![Github watchers](https://shields.io/github/watchers/Menooker/FishHook?style=social)
- github.com/G-E-N-E-S-I-S/latebros ![Github stars](https://shields.io/github/stars/G-E-N-E-S-I-S/latebros?style=social) ![Github forks](https://shields.io/github/forks/G-E-N-E-S-I-S/latebros?style=social) ![Github watchers](https://shields.io/github/watchers/G-E-N-E-S-I-S/latebros?style=social)
- bbs.pediy.com/thread-214582.htm

## hook engine

- github.com/nektra/Deviare-InProc ![Github stars](https://shields.io/github/stars/nektra/Deviare-InProc?style=social) ![Github forks](https://shields.io/github/forks/nektra/Deviare-InProc?style=social) ![Github watchers](https://shields.io/github/watchers/nektra/Deviare-InProc?style=social)
- github.com/btbd/smap ![Github stars](https://shields.io/github/stars/btbd/smap?style=social) ![Github forks](https://shields.io/github/forks/btbd/smap?style=social) ![Github watchers](https://shields.io/github/watchers/btbd/smap?style=social)
- github.com/gdabah/distormx ![Github stars](https://shields.io/github/stars/gdabah/distormx?style=social) ![Github forks](https://shields.io/github/forks/gdabah/distormx?style=social) ![Github watchers](https://shields.io/github/watchers/gdabah/distormx?style=social)
- github.com/danielkrupinski/vac-hooks ![Github stars](https://shields.io/github/stars/danielkrupinski/vac-hooks?style=social) ![Github forks](https://shields.io/github/forks/danielkrupinski/vac-hooks?style=social) ![Github watchers](https://shields.io/github/watchers/danielkrupinski/vac-hooks?style=social)
- github.com/vol4ok/libsplice (r3 & r0) ![Github stars](https://shields.io/github/stars/vol4ok/libsplice?style=social) ![Github forks](https://shields.io/github/forks/vol4ok/libsplice?style=social) ![Github watchers](https://shields.io/github/watchers/vol4ok/libsplice?style=social)
- github.com/HoShiMin/HookLib (r3 & r0) ![Github stars](https://shields.io/github/stars/HoShiMin/HookLib?style=social) ![Github forks](https://shields.io/github/forks/HoShiMin/HookLib?style=social) ![Github watchers](https://shields.io/github/watchers/HoShiMin/HookLib?style=social)
- github.com/Rebzzel/kiero (d3d hook) ![Github stars](https://shields.io/github/stars/Rebzzel/kiero?style=social) ![Github forks](https://shields.io/github/forks/Rebzzel/kiero?style=social) ![Github watchers](https://shields.io/github/watchers/Rebzzel/kiero?style=social)
- github.com/aschrein/apiparse ![Github stars](https://shields.io/github/stars/aschrein/apiparse?style=social) ![Github forks](https://shields.io/github/forks/aschrein/apiparse?style=social) ![Github watchers](https://shields.io/github/watchers/aschrein/apiparse?style=social)
- github.com/zyantific/zyan-hook-engine ![Github stars](https://shields.io/github/stars/zyantific/zyan-hook-engine?style=social) ![Github forks](https://shields.io/github/forks/zyantific/zyan-hook-engine?style=social) ![Github watchers](https://shields.io/github/watchers/zyantific/zyan-hook-engine?style=social)
- github.com/jonasblunck/DP (com hook) ![Github stars](https://shields.io/github/stars/jonasblunck/DP?style=social) ![Github forks](https://shields.io/github/forks/jonasblunck/DP?style=social) ![Github watchers](https://shields.io/github/watchers/jonasblunck/DP?style=social)
- github.com/jonasblunck/DynHook ![Github stars](https://shields.io/github/stars/jonasblunck/DynHook?style=social) ![Github forks](https://shields.io/github/forks/jonasblunck/DynHook?style=social) ![Github watchers](https://shields.io/github/watchers/jonasblunck/DynHook?style=social)
- github.com/wanttobeno/ADE32_InlineHook ![Github stars](https://shields.io/github/stars/wanttobeno/ADE32_InlineHook?style=social) ![Github forks](https://shields.io/github/forks/wanttobeno/ADE32_InlineHook?style=social) ![Github watchers](https://shields.io/github/watchers/wanttobeno/ADE32_InlineHook?style=social)
- github.com/coltonon/RegHookEx (mid function) ![Github stars](https://shields.io/github/stars/coltonon/RegHookEx?style=social) ![Github forks](https://shields.io/github/forks/coltonon/RegHookEx?style=social) ![Github watchers](https://shields.io/github/watchers/coltonon/RegHookEx?style=social)
- github.com/Synestraa/ArchUltimate.HookLib ![Github stars](https://shields.io/github/stars/Synestraa/ArchUltimate.HookLib?style=social) ![Github forks](https://shields.io/github/forks/Synestraa/ArchUltimate.HookLib?style=social) ![Github watchers](https://shields.io/github/watchers/Synestraa/ArchUltimate.HookLib?style=social)
- github.com/DominicTobias/detourxs ![Github stars](https://shields.io/github/stars/DominicTobias/detourxs?style=social) ![Github forks](https://shields.io/github/forks/DominicTobias/detourxs?style=social) ![Github watchers](https://shields.io/github/watchers/DominicTobias/detourxs?style=social)
- github.com/Ilyatk/HookEngine ![Github stars](https://shields.io/github/stars/Ilyatk/HookEngine?style=social) ![Github forks](https://shields.io/github/forks/Ilyatk/HookEngine?style=social) ![Github watchers](https://shields.io/github/watchers/Ilyatk/HookEngine?style=social)
- github.com/zyantific/zyan-hook-engine ![Github stars](https://shields.io/github/stars/zyantific/zyan-hook-engine?style=social) ![Github forks](https://shields.io/github/forks/zyantific/zyan-hook-engine?style=social) ![Github watchers](https://shields.io/github/watchers/zyantific/zyan-hook-engine?style=social)
- github.com/martona/mhook ![Github stars](https://shields.io/github/stars/martona/mhook?style=social) ![Github forks](https://shields.io/github/forks/martona/mhook?style=social) ![Github watchers](https://shields.io/github/watchers/martona/mhook?style=social)
- github.com/EasyHook/EasyHook ![Github stars](https://shields.io/github/stars/EasyHook/EasyHook?style=social) ![Github forks](https://shields.io/github/forks/EasyHook/EasyHook?style=social) ![Github watchers](https://shields.io/github/watchers/EasyHook/EasyHook?style=social)
- github.com/RelicOfTesla/Detours ![Github stars](https://shields.io/github/stars/RelicOfTesla/Detours?style=social) ![Github forks](https://shields.io/github/forks/RelicOfTesla/Detours?style=social) ![Github watchers](https://shields.io/github/watchers/RelicOfTesla/Detours?style=social)
- github.com/stevemk14ebr/PolyHook ![Github stars](https://shields.io/github/stars/stevemk14ebr/PolyHook?style=social) ![Github forks](https://shields.io/github/forks/stevemk14ebr/PolyHook?style=social) ![Github watchers](https://shields.io/github/watchers/stevemk14ebr/PolyHook?style=social)
- github.com/TsudaKageyu/minhook ![Github stars](https://shields.io/github/stars/TsudaKageyu/minhook?style=social) ![Github forks](https://shields.io/github/forks/TsudaKageyu/minhook?style=social) ![Github watchers](https://shields.io/github/watchers/TsudaKageyu/minhook?style=social)
- github.com/Microsoft/Detours ![Github stars](https://shields.io/github/stars/Microsoft/Detours?style=social) ![Github forks](https://shields.io/github/forks/Microsoft/Detours?style=social) ![Github watchers](https://shields.io/github/watchers/Microsoft/Detours?style=social)
- github.com/Microwave89/ntapihook ![Github stars](https://shields.io/github/stars/Microwave89/ntapihook?style=social) ![Github forks](https://shields.io/github/forks/Microwave89/ntapihook?style=social) ![Github watchers](https://shields.io/github/watchers/Microwave89/ntapihook?style=social)

## anti hook

- github.com/outflanknl/Dumpert ![Github stars](https://shields.io/github/stars/outflanknl/Dumpert?style=social) ![Github forks](https://shields.io/github/forks/outflanknl/Dumpert?style=social) ![Github watchers](https://shields.io/github/watchers/outflanknl/Dumpert?style=social)
- github.com/nickcano/ReloadLibrary ![Github stars](https://shields.io/github/stars/nickcano/ReloadLibrary?style=social) ![Github forks](https://shields.io/github/forks/nickcano/ReloadLibrary?style=social) ![Github watchers](https://shields.io/github/watchers/nickcano/ReloadLibrary?style=social)

## inject technique (ring0)

- github.com/SDXT/MMInject (Kernel DLL Injector using NX Bit Swapping and VAD hide for hiding injected DLL) ![Github stars](https://shields.io/github/stars/SDXT/MMInject?style=social) ![Github forks](https://shields.io/github/forks/SDXT/MMInject?style=social) ![Github watchers](https://shields.io/github/watchers/SDXT/MMInject?style=social)
- github.com/Vicshann/GInjer ![Github stars](https://shields.io/github/stars/Vicshann/GInjer?style=social) ![Github forks](https://shields.io/github/forks/Vicshann/GInjer?style=social) ![Github watchers](https://shields.io/github/watchers/Vicshann/GInjer?style=social)
- github.com/r1cky33/Basic-GUI-Loader ![Github stars](https://shields.io/github/stars/r1cky33/Basic-GUI-Loader?style=social) ![Github forks](https://shields.io/github/forks/r1cky33/Basic-GUI-Loader?style=social) ![Github watchers](https://shields.io/github/watchers/r1cky33/Basic-GUI-Loader?style=social)
- github.com/alxbrn/kernel-injector ![Github stars](https://shields.io/github/stars/alxbrn/kernel-injector?style=social) ![Github forks](https://shields.io/github/forks/alxbrn/kernel-injector?style=social) ![Github watchers](https://shields.io/github/watchers/alxbrn/kernel-injector?style=social)
- github.com/btbd/modmap ![Github stars](https://shields.io/github/stars/btbd/modmap?style=social) ![Github forks](https://shields.io/github/forks/btbd/modmap?style=social) ![Github watchers](https://shields.io/github/watchers/btbd/modmap?style=social)
- github.com/Mecanik/MecanikProcessBreaker ![Github stars](https://shields.io/github/stars/Mecanik/MecanikProcessBreaker?style=social) ![Github forks](https://shields.io/github/forks/Mecanik/MecanikProcessBreaker?style=social) ![Github watchers](https://shields.io/github/watchers/Mecanik/MecanikProcessBreaker?style=social)
- github.com/mactec0/Kernelmode-manual-mapping-through-IAT ![Github stars](https://shields.io/github/stars/mactec0/Kernelmode-manual-mapping-through-IAT?style=social) ![Github forks](https://shields.io/github/forks/mactec0/Kernelmode-manual-mapping-through-IAT?style=social) ![Github watchers](https://shields.io/github/watchers/mactec0/Kernelmode-manual-mapping-through-IAT?style=social)
- github.com/adrianyy/KeInject ![Github stars](https://shields.io/github/stars/adrianyy/KeInject?style=social) ![Github forks](https://shields.io/github/forks/adrianyy/KeInject?style=social) ![Github watchers](https://shields.io/github/watchers/adrianyy/KeInject?style=social)
- github.com/Sqdwr/LoadImageInject ![Github stars](https://shields.io/github/stars/Sqdwr/LoadImageInject?style=social) ![Github forks](https://shields.io/github/forks/Sqdwr/LoadImageInject?style=social) ![Github watchers](https://shields.io/github/watchers/Sqdwr/LoadImageInject?style=social)
- github.com/haidragon/NewInjectDrv ![Github stars](https://shields.io/github/stars/haidragon/NewInjectDrv?style=social) ![Github forks](https://shields.io/github/forks/haidragon/NewInjectDrv?style=social) ![Github watchers](https://shields.io/github/watchers/haidragon/NewInjectDrv?style=social)
- github.com/alex9191/Kernel-dll-injector (DllInjectFromKernel) ![Github stars](https://shields.io/github/stars/alex9191/Kernel-dll-injector?style=social) ![Github forks](https://shields.io/github/forks/alex9191/Kernel-dll-injector?style=social) ![Github watchers](https://shields.io/github/watchers/alex9191/Kernel-dll-injector?style=social)
- github.com/wbenny/keinject (ApcInjectFromKernel) ![Github stars](https://shields.io/github/stars/wbenny/keinject?style=social) ![Github forks](https://shields.io/github/forks/wbenny/keinject?style=social) ![Github watchers](https://shields.io/github/watchers/wbenny/keinject?style=social)
- github.com/repnz/apc-research (APC) ![Github stars](https://shields.io/github/stars/repnz/apc-research?style=social) ![Github forks](https://shields.io/github/forks/repnz/apc-research?style=social) ![Github watchers](https://shields.io/github/watchers/repnz/apc-research?style=social)

## inject technique (ring3)

- github.com/Broihon/GH-Injector-Library ![Github stars](https://shields.io/github/stars/Broihon/GH-Injector-Library?style=social) ![Github forks](https://shields.io/github/forks/Broihon/GH-Injector-Library?style=social) ![Github watchers](https://shields.io/github/watchers/Broihon/GH-Injector-Library?style=social)
- github.com/antonioCoco/Mapping-Injection (MapViewOfFile2) ![Github stars](https://shields.io/github/stars/antonioCoco/Mapping-Injection?style=social) ![Github forks](https://shields.io/github/forks/antonioCoco/Mapping-Injection?style=social) ![Github watchers](https://shields.io/github/watchers/antonioCoco/Mapping-Injection?style=social)
- github.com/theevilbit/injection ![Github stars](https://shields.io/github/stars/theevilbit/injection?style=social) ![Github forks](https://shields.io/github/forks/theevilbit/injection?style=social) ![Github watchers](https://shields.io/github/watchers/theevilbit/injection?style=social)
- github.com/SafeBreach-Labs/pinjectra ![Github stars](https://shields.io/github/stars/SafeBreach-Labs/pinjectra?style=social) ![Github forks](https://shields.io/github/forks/SafeBreach-Labs/pinjectra?style=social) ![Github watchers](https://shields.io/github/watchers/SafeBreach-Labs/pinjectra?style=social)
- github.com/odzhan/injection ![Github stars](https://shields.io/github/stars/odzhan/injection?style=social) ![Github forks](https://shields.io/github/forks/odzhan/injection?style=social) ![Github watchers](https://shields.io/github/watchers/odzhan/injection?style=social)
- github.com/M-r-J-o-h-n/SWH-Injector ![Github stars](https://shields.io/github/stars/M-r-J-o-h-n/SWH-Injector?style=social) ![Github forks](https://shields.io/github/forks/M-r-J-o-h-n/SWH-Injector?style=social) ![Github watchers](https://shields.io/github/watchers/M-r-J-o-h-n/SWH-Injector?style=social)
- github.com/nccgroup/ncloader (A session-0 capable dll injection utility) ![Github stars](https://shields.io/github/stars/nccgroup/ncloader?style=social) ![Github forks](https://shields.io/github/forks/nccgroup/ncloader?style=social) ![Github watchers](https://shields.io/github/watchers/nccgroup/ncloader?style=social)
- github.com/vmcall/eye_mapper (BattlEye x64 usermode injector) ![Github stars](https://shields.io/github/stars/vmcall/eye_mapper?style=social) ![Github forks](https://shields.io/github/forks/vmcall/eye_mapper?style=social) ![Github watchers](https://shields.io/github/watchers/vmcall/eye_mapper?style=social)
- github.com/Shaxzy/VibranceInjector ![Github stars](https://shields.io/github/stars/Shaxzy/VibranceInjector?style=social) ![Github forks](https://shields.io/github/forks/Shaxzy/VibranceInjector?style=social) ![Github watchers](https://shields.io/github/watchers/Shaxzy/VibranceInjector?style=social)
- github.com/xiaobo93/UnModule_shellcode_Inject ![Github stars](https://shields.io/github/stars/xiaobo93/UnModule_shellcode_Inject?style=social) ![Github forks](https://shields.io/github/forks/xiaobo93/UnModule_shellcode_Inject?style=social) ![Github watchers](https://shields.io/github/watchers/xiaobo93/UnModule_shellcode_Inject?style=social)
- github.com/Cybellum/DoubleAgent ![Github stars](https://shields.io/github/stars/Cybellum/DoubleAgent?style=social) ![Github forks](https://shields.io/github/forks/Cybellum/DoubleAgent?style=social) ![Github watchers](https://shields.io/github/watchers/Cybellum/DoubleAgent?style=social)
- github.com/realoriginal/reflective-rewrite (InjectFromMemory) ![Github stars](https://shields.io/github/stars/realoriginal/reflective-rewrite?style=social) ![Github forks](https://shields.io/github/forks/realoriginal/reflective-rewrite?style=social) ![Github watchers](https://shields.io/github/watchers/realoriginal/reflective-rewrite?style=social)
- github.com/blaquee/APCHook  (apc inject) ![Github stars](https://shields.io/github/stars/blaquee/APCHook?style=social) ![Github forks](https://shields.io/github/forks/blaquee/APCHook?style=social) ![Github watchers](https://shields.io/github/watchers/blaquee/APCHook?style=social)
- github.com/secrary/InjectProc ![Github stars](https://shields.io/github/stars/secrary/InjectProc?style=social) ![Github forks](https://shields.io/github/forks/secrary/InjectProc?style=social) ![Github watchers](https://shields.io/github/watchers/secrary/InjectProc?style=social)
- github.com/ez8-co/yapi (Yet Another Process Injector) ![Github stars](https://shields.io/github/stars/ez8-co/yapi?style=social) ![Github forks](https://shields.io/github/forks/ez8-co/yapi?style=social) ![Github watchers](https://shields.io/github/watchers/ez8-co/yapi?style=social)
- github.com/UserExistsError/InjectDll  (InjectFromMemory) ![Github stars](https://shields.io/github/stars/UserExistsError/InjectDll?style=social) ![Github forks](https://shields.io/github/forks/UserExistsError/InjectDll?style=social) ![Github watchers](https://shields.io/github/watchers/UserExistsError/InjectDll?style=social)
- github.com/notscimmy/libinject ![Github stars](https://shields.io/github/stars/notscimmy/libinject?style=social) ![Github forks](https://shields.io/github/forks/notscimmy/libinject?style=social) ![Github watchers](https://shields.io/github/watchers/notscimmy/libinject?style=social)
- github.com/BorjaMerino/tlsInjector (tls) ![Github stars](https://shields.io/github/stars/BorjaMerino/tlsInjector?style=social) ![Github forks](https://shields.io/github/forks/BorjaMerino/tlsInjector?style=social) ![Github watchers](https://shields.io/github/watchers/BorjaMerino/tlsInjector?style=social)
- github.com/BorjaMerino/Pazuzu (InjectFromMemory) ![Github stars](https://shields.io/github/stars/BorjaMerino/Pazuzu?style=social) ![Github forks](https://shields.io/github/forks/BorjaMerino/Pazuzu?style=social) ![Github watchers](https://shields.io/github/watchers/BorjaMerino/Pazuzu?style=social)
- github.com/strobejb/injdll ![Github stars](https://shields.io/github/stars/strobejb/injdll?style=social) ![Github forks](https://shields.io/github/forks/strobejb/injdll?style=social) ![Github watchers](https://shields.io/github/watchers/strobejb/injdll?style=social)
- github.com/strivexjun/DriverInjectDll (MapInjectDll) ![Github stars](https://shields.io/github/stars/strivexjun/DriverInjectDll?style=social) ![Github forks](https://shields.io/github/forks/strivexjun/DriverInjectDll?style=social) ![Github watchers](https://shields.io/github/watchers/strivexjun/DriverInjectDll?style=social)
- github.com/sud0loo/ProcessInjection ![Github stars](https://shields.io/github/stars/sud0loo/ProcessInjection?style=social) ![Github forks](https://shields.io/github/forks/sud0loo/ProcessInjection?style=social) ![Github watchers](https://shields.io/github/watchers/sud0loo/ProcessInjection?style=social)
- github.com/apriorit/SvcHostDemo ![Github stars](https://shields.io/github/stars/apriorit/SvcHostDemo?style=social) ![Github forks](https://shields.io/github/forks/apriorit/SvcHostDemo?style=social) ![Github watchers](https://shields.io/github/watchers/apriorit/SvcHostDemo?style=social)
- github.com/can1357/ThePerfectInjector ![Github stars](https://shields.io/github/stars/can1357/ThePerfectInjector?style=social) ![Github forks](https://shields.io/github/forks/can1357/ThePerfectInjector?style=social) ![Github watchers](https://shields.io/github/watchers/can1357/ThePerfectInjector?style=social)
- github.com/VideoCardGuy/X64Injector ![Github stars](https://shields.io/github/stars/VideoCardGuy/X64Injector?style=social) ![Github forks](https://shields.io/github/forks/VideoCardGuy/X64Injector?style=social) ![Github watchers](https://shields.io/github/watchers/VideoCardGuy/X64Injector?style=social)
- github.com/papadp/reflective-injection-detection (InjectFromMemory) ![Github stars](https://shields.io/github/stars/papadp/reflective-injection-detection?style=social) ![Github forks](https://shields.io/github/forks/papadp/reflective-injection-detection?style=social) ![Github watchers](https://shields.io/github/watchers/papadp/reflective-injection-detection?style=social)
- github.com/psmitty7373/eif (InjectFromMemory) ![Github stars](https://shields.io/github/stars/psmitty7373/eif?style=social) ![Github forks](https://shields.io/github/forks/psmitty7373/eif?style=social) ![Github watchers](https://shields.io/github/watchers/psmitty7373/eif?style=social)
- github.com/rokups/ReflectiveLdr (InjectFromMemory) ![Github stars](https://shields.io/github/stars/rokups/ReflectiveLdr?style=social) ![Github forks](https://shields.io/github/forks/rokups/ReflectiveLdr?style=social) ![Github watchers](https://shields.io/github/watchers/rokups/ReflectiveLdr?style=social)
- github.com/BenjaminSoelberg/ReflectivePELoader (InjectFromMemory) ![Github stars](https://shields.io/github/stars/BenjaminSoelberg/ReflectivePELoader?style=social) ![Github forks](https://shields.io/github/forks/BenjaminSoelberg/ReflectivePELoader?style=social) ![Github watchers](https://shields.io/github/watchers/BenjaminSoelberg/ReflectivePELoader?style=social)
- github.com/NtRaiseHardError/Phage (InjectFromMemory) ![Github stars](https://shields.io/github/stars/NtRaiseHardError/Phage?style=social) ![Github forks](https://shields.io/github/forks/NtRaiseHardError/Phage?style=social) ![Github watchers](https://shields.io/github/watchers/NtRaiseHardError/Phage?style=social)
- github.com/dismantl/ImprovedReflectiveDLLInjection (InjectFromMemory) ![Github stars](https://shields.io/github/stars/dismantl/ImprovedReflectiveDLLInjection?style=social) ![Github forks](https://shields.io/github/forks/dismantl/ImprovedReflectiveDLLInjection?style=social) ![Github watchers](https://shields.io/github/watchers/dismantl/ImprovedReflectiveDLLInjection?style=social)
- github.com/CylanceVulnResearch/ReflectiveDLLRefresher (InjectFromMemory) ![Github stars](https://shields.io/github/stars/CylanceVulnResearch/ReflectiveDLLRefresher?style=social) ![Github forks](https://shields.io/github/forks/CylanceVulnResearch/ReflectiveDLLRefresher?style=social) ![Github watchers](https://shields.io/github/watchers/CylanceVulnResearch/ReflectiveDLLRefresher?style=social)
- github.com/amishsecurity/paythepony (InjectFromMemory) ![Github stars](https://shields.io/github/stars/amishsecurity/paythepony?style=social) ![Github forks](https://shields.io/github/forks/amishsecurity/paythepony?style=social) ![Github watchers](https://shields.io/github/watchers/amishsecurity/paythepony?style=social)
- github.com/deroko/activationcontexthook ![Github stars](https://shields.io/github/stars/deroko/activationcontexthook?style=social) ![Github forks](https://shields.io/github/forks/deroko/activationcontexthook?style=social) ![Github watchers](https://shields.io/github/watchers/deroko/activationcontexthook?style=social)
- github.com/ez8-co/yapi (Cross x86 & x64 injection) ![Github stars](https://shields.io/github/stars/ez8-co/yapi?style=social) ![Github forks](https://shields.io/github/forks/ez8-co/yapi?style=social) ![Github watchers](https://shields.io/github/watchers/ez8-co/yapi?style=social)
- github.com/georgenicolaou/HeavenInjector ![Github stars](https://shields.io/github/stars/georgenicolaou/HeavenInjector?style=social) ![Github forks](https://shields.io/github/forks/georgenicolaou/HeavenInjector?style=social) ![Github watchers](https://shields.io/github/watchers/georgenicolaou/HeavenInjector?style=social)
- github.com/tinysec/runwithdll ![Github stars](https://shields.io/github/stars/tinysec/runwithdll?style=social) ![Github forks](https://shields.io/github/forks/tinysec/runwithdll?style=social) ![Github watchers](https://shields.io/github/watchers/tinysec/runwithdll?style=social)
- github.com/NtOpcode/NT-APC-Injector ![Github stars](https://shields.io/github/stars/NtOpcode/NT-APC-Injector?style=social) ![Github forks](https://shields.io/github/forks/NtOpcode/NT-APC-Injector?style=social) ![Github watchers](https://shields.io/github/watchers/NtOpcode/NT-APC-Injector?style=social)
- github.com/caidongyun/WinCodeInjection ![Github stars](https://shields.io/github/stars/caidongyun/WinCodeInjection?style=social) ![Github forks](https://shields.io/github/forks/caidongyun/WinCodeInjection?style=social) ![Github watchers](https://shields.io/github/watchers/caidongyun/WinCodeInjection?style=social)
- github.com/countercept/doublepulsar-usermode-injector ![Github stars](https://shields.io/github/stars/countercept/doublepulsar-usermode-injector?style=social) ![Github forks](https://shields.io/github/forks/countercept/doublepulsar-usermode-injector?style=social) ![Github watchers](https://shields.io/github/watchers/countercept/doublepulsar-usermode-injector?style=social)
- github.com/mq1n/DLLThreadInjectionDetector ![Github stars](https://shields.io/github/stars/mq1n/DLLThreadInjectionDetector?style=social) ![Github forks](https://shields.io/github/forks/mq1n/DLLThreadInjectionDetector?style=social) ![Github watchers](https://shields.io/github/watchers/mq1n/DLLThreadInjectionDetector?style=social)
- github.com/hkhk366/Memory_Codes_Injection ![Github stars](https://shields.io/github/stars/hkhk366/Memory_Codes_Injection?style=social) ![Github forks](https://shields.io/github/forks/hkhk366/Memory_Codes_Injection?style=social) ![Github watchers](https://shields.io/github/watchers/hkhk366/Memory_Codes_Injection?style=social)
- github.com/chango77747/ShellCodeInjector_MsBuild ![Github stars](https://shields.io/github/stars/chango77747/ShellCodeInjector_MsBuild?style=social) ![Github forks](https://shields.io/github/forks/chango77747/ShellCodeInjector_MsBuild?style=social) ![Github watchers](https://shields.io/github/watchers/chango77747/ShellCodeInjector_MsBuild?style=social)
- github.com/Zer0Mem0ry/ManualMap ![Github stars](https://shields.io/github/stars/Zer0Mem0ry/ManualMap?style=social) ![Github forks](https://shields.io/github/forks/Zer0Mem0ry/ManualMap?style=social) ![Github watchers](https://shields.io/github/watchers/Zer0Mem0ry/ManualMap?style=social)
- github.com/secrary/InfectPE ![Github stars](https://shields.io/github/stars/secrary/InfectPE?style=social) ![Github forks](https://shields.io/github/forks/secrary/InfectPE?style=social) ![Github watchers](https://shields.io/github/watchers/secrary/InfectPE?style=social)
- github.com/zodiacon/DllInjectionWithThreadContext ![Github stars](https://shields.io/github/stars/zodiacon/DllInjectionWithThreadContext?style=social) ![Github forks](https://shields.io/github/forks/zodiacon/DllInjectionWithThreadContext?style=social) ![Github watchers](https://shields.io/github/watchers/zodiacon/DllInjectionWithThreadContext?style=social)
- github.com/NtOpcode/RtlCreateUserThread-DLL-Injection ![Github stars](https://shields.io/github/stars/NtOpcode/RtlCreateUserThread-DLL-Injection?style=social) ![Github forks](https://shields.io/github/forks/NtOpcode/RtlCreateUserThread-DLL-Injection?style=social) ![Github watchers](https://shields.io/github/watchers/NtOpcode/RtlCreateUserThread-DLL-Injection?style=social)
- github.com/hasherezade/chimera_loader ![Github stars](https://shields.io/github/stars/hasherezade/chimera_loader?style=social) ![Github forks](https://shields.io/github/forks/hasherezade/chimera_loader?style=social) ![Github watchers](https://shields.io/github/watchers/hasherezade/chimera_loader?style=social)
- github.com/Ciantic/RemoteThreader ![Github stars](https://shields.io/github/stars/Ciantic/RemoteThreader?style=social) ![Github forks](https://shields.io/github/forks/Ciantic/RemoteThreader?style=social) ![Github watchers](https://shields.io/github/watchers/Ciantic/RemoteThreader?style=social)
- github.com/OlSut/Kinject-x64 ![Github stars](https://shields.io/github/stars/OlSut/Kinject-x64?style=social) ![Github forks](https://shields.io/github/forks/OlSut/Kinject-x64?style=social) ![Github watchers](https://shields.io/github/watchers/OlSut/Kinject-x64?style=social)
- github.com/tandasat/RemoteWriteMonitor ![Github stars](https://shields.io/github/stars/tandasat/RemoteWriteMonitor?style=social) ![Github forks](https://shields.io/github/forks/tandasat/RemoteWriteMonitor?style=social) ![Github watchers](https://shields.io/github/watchers/tandasat/RemoteWriteMonitor?style=social)
- github.com/stormshield/Beholder-Win32 ![Github stars](https://shields.io/github/stars/stormshield/Beholder-Win32?style=social) ![Github forks](https://shields.io/github/forks/stormshield/Beholder-Win32?style=social) ![Github watchers](https://shields.io/github/watchers/stormshield/Beholder-Win32?style=social)
- github.com/secrary/InjectProc ![Github stars](https://shields.io/github/stars/secrary/InjectProc?style=social) ![Github forks](https://shields.io/github/forks/secrary/InjectProc?style=social) ![Github watchers](https://shields.io/github/watchers/secrary/InjectProc?style=social)
- github.com/AzureGreen/InjectCollection ![Github stars](https://shields.io/github/stars/AzureGreen/InjectCollection?style=social) ![Github forks](https://shields.io/github/forks/AzureGreen/InjectCollection?style=social) ![Github watchers](https://shields.io/github/watchers/AzureGreen/InjectCollection?style=social)
- github.com/uItra/Injectora ![Github stars](https://shields.io/github/stars/uItra/Injectora?style=social) ![Github forks](https://shields.io/github/forks/uItra/Injectora?style=social) ![Github watchers](https://shields.io/github/watchers/uItra/Injectora?style=social)
- github.com/rootm0s/Injectors ![Github stars](https://shields.io/github/stars/rootm0s/Injectors?style=social) ![Github forks](https://shields.io/github/forks/rootm0s/Injectors?style=social) ![Github watchers](https://shields.io/github/watchers/rootm0s/Injectors?style=social)
- github.com/Spajed/processrefund ![Github stars](https://shields.io/github/stars/Spajed/processrefund?style=social) ![Github forks](https://shields.io/github/forks/Spajed/processrefund?style=social) ![Github watchers](https://shields.io/github/watchers/Spajed/processrefund?style=social)
- github.com/al-homedawy/InjecTOR ![Github stars](https://shields.io/github/stars/al-homedawy/InjecTOR?style=social) ![Github forks](https://shields.io/github/forks/al-homedawy/InjecTOR?style=social) ![Github watchers](https://shields.io/github/watchers/al-homedawy/InjecTOR?style=social)
- github.com/OlSut/Kinject-x64 ![Github stars](https://shields.io/github/stars/OlSut/Kinject-x64?style=social) ![Github forks](https://shields.io/github/forks/OlSut/Kinject-x64?style=social) ![Github watchers](https://shields.io/github/watchers/OlSut/Kinject-x64?style=social)
- github.com/stormshield/Beholder-Win32 ![Github stars](https://shields.io/github/stars/stormshield/Beholder-Win32?style=social) ![Github forks](https://shields.io/github/forks/stormshield/Beholder-Win32?style=social) ![Github watchers](https://shields.io/github/watchers/stormshield/Beholder-Win32?style=social)
- github.com/yifiHeaven/MagicWall ![Github stars](https://shields.io/github/stars/yifiHeaven/MagicWall?style=social) ![Github forks](https://shields.io/github/forks/yifiHeaven/MagicWall?style=social) ![Github watchers](https://shields.io/github/watchers/yifiHeaven/MagicWall?style=social)

## WoW64 <-> x64

- github.com/wolk-1024/WoW64Utils ![Github stars](https://shields.io/github/stars/wolk-1024/WoW64Utils?style=social) ![Github forks](https://shields.io/github/forks/wolk-1024/WoW64Utils?style=social) ![Github watchers](https://shields.io/github/watchers/wolk-1024/WoW64Utils?style=social)
- github.com/dadas190/Heavens-Gate-2.0 ![Github stars](https://shields.io/github/stars/dadas190/Heavens-Gate-2.0?style=social) ![Github forks](https://shields.io/github/forks/dadas190/Heavens-Gate-2.0?style=social) ![Github watchers](https://shields.io/github/watchers/dadas190/Heavens-Gate-2.0?style=social)
- github.com/leecher1337/ntvdmx64 ![Github stars](https://shields.io/github/stars/leecher1337/ntvdmx64?style=social) ![Github forks](https://shields.io/github/forks/leecher1337/ntvdmx64?style=social) ![Github watchers](https://shields.io/github/watchers/leecher1337/ntvdmx64?style=social)
- github.com/hyzhangzhy/WindowX ![Github stars](https://shields.io/github/stars/hyzhangzhy/WindowX?style=social) ![Github forks](https://shields.io/github/forks/hyzhangzhy/WindowX?style=social) ![Github watchers](https://shields.io/github/watchers/hyzhangzhy/WindowX?style=social)
- github.com/georgenicolaou/HeavenInjector ![Github stars](https://shields.io/github/stars/georgenicolaou/HeavenInjector?style=social) ![Github forks](https://shields.io/github/forks/georgenicolaou/HeavenInjector?style=social) ![Github watchers](https://shields.io/github/watchers/georgenicolaou/HeavenInjector?style=social)
- github.com/georgenicolaou/W64oWoW64 ![Github stars](https://shields.io/github/stars/georgenicolaou/W64oWoW64?style=social) ![Github forks](https://shields.io/github/forks/georgenicolaou/W64oWoW64?style=social) ![Github watchers](https://shields.io/github/watchers/georgenicolaou/W64oWoW64?style=social)
- github.com/Rprop/X86Call ![Github stars](https://shields.io/github/stars/Rprop/X86Call?style=social) ![Github forks](https://shields.io/github/forks/Rprop/X86Call?style=social) ![Github watchers](https://shields.io/github/watchers/Rprop/X86Call?style=social)
- github.com/rwfpl/rewolf-wow64ext ![Github stars](https://shields.io/github/stars/rwfpl/rewolf-wow64ext?style=social) ![Github forks](https://shields.io/github/forks/rwfpl/rewolf-wow64ext?style=social) ![Github watchers](https://shields.io/github/watchers/rwfpl/rewolf-wow64ext?style=social)
- github.com/ovidiuvio/libntdbg ![Github stars](https://shields.io/github/stars/ovidiuvio/libntdbg?style=social) ![Github forks](https://shields.io/github/forks/ovidiuvio/libntdbg?style=social) ![Github watchers](https://shields.io/github/watchers/ovidiuvio/libntdbg?style=social)
- github.com/haidragon/x86tox64 ![Github stars](https://shields.io/github/stars/haidragon/x86tox64?style=social) ![Github forks](https://shields.io/github/forks/haidragon/x86tox64?style=social) ![Github watchers](https://shields.io/github/watchers/haidragon/x86tox64?style=social)
- github.com/3gstudent/CreateRemoteThread ![Github stars](https://shields.io/github/stars/3gstudent/CreateRemoteThread?style=social) ![Github forks](https://shields.io/github/forks/3gstudent/CreateRemoteThread?style=social) ![Github watchers](https://shields.io/github/watchers/3gstudent/CreateRemoteThread?style=social)
- github.com/RaMMicHaeL/Textify ![Github stars](https://shields.io/github/stars/RaMMicHaeL/Textify?style=social) ![Github forks](https://shields.io/github/forks/RaMMicHaeL/Textify?style=social) ![Github watchers](https://shields.io/github/watchers/RaMMicHaeL/Textify?style=social)

## anti autorun

- github.com/analyst004/autorun ![Github stars](https://shields.io/github/stars/analyst004/autorun?style=social) ![Github forks](https://shields.io/github/forks/analyst004/autorun?style=social) ![Github watchers](https://shields.io/github/watchers/analyst004/autorun?style=social)

## anti dll inject

- 0cch.com/2015/04/10/e998b2e6ada2global-windows-hookse6b3a8e585a5e79a84e4b880e4b8aae696b9e6b395/  (global hook)
- blog.csdn.net/songjinshi/article/details/7808561 (message hook)
- blog.csdn.net/songjinshi/article/details/7808624 (message hook)
- github.com/mq1n/DLLThreadInjectionDetector ![Github stars](https://shields.io/github/stars/mq1n/DLLThreadInjectionDetector?style=social) ![Github forks](https://shields.io/github/forks/mq1n/DLLThreadInjectionDetector?style=social) ![Github watchers](https://shields.io/github/watchers/mq1n/DLLThreadInjectionDetector?style=social)
- github.com/analyst004/antinject ![Github stars](https://shields.io/github/stars/analyst004/antinject?style=social) ![Github forks](https://shields.io/github/forks/analyst004/antinject?style=social) ![Github watchers](https://shields.io/github/watchers/analyst004/antinject?style=social)
- github.com/ExpLife/BotKiller ![Github stars](https://shields.io/github/stars/ExpLife/BotKiller?style=social) ![Github forks](https://shields.io/github/forks/ExpLife/BotKiller?style=social) ![Github watchers](https://shields.io/github/watchers/ExpLife/BotKiller?style=social)

## load Dll from memory

- github.com/hasherezade/module_overloading ![Github stars](https://shields.io/github/stars/hasherezade/module_overloading?style=social) ![Github forks](https://shields.io/github/forks/hasherezade/module_overloading?style=social) ![Github watchers](https://shields.io/github/watchers/hasherezade/module_overloading?style=social)
- github.com/UserExistsError/DllLoaderShellcode ![Github stars](https://shields.io/github/stars/UserExistsError/DllLoaderShellcode?style=social) ![Github forks](https://shields.io/github/forks/UserExistsError/DllLoaderShellcode?style=social) ![Github watchers](https://shields.io/github/watchers/UserExistsError/DllLoaderShellcode?style=social)
- github.com/jnastarot/native_peloader ![Github stars](https://shields.io/github/stars/jnastarot/native_peloader?style=social) ![Github forks](https://shields.io/github/forks/jnastarot/native_peloader?style=social) ![Github watchers](https://shields.io/github/watchers/jnastarot/native_peloader?style=social)
- github.com/fancycode/MemoryModule ![Github stars](https://shields.io/github/stars/fancycode/MemoryModule?style=social) ![Github forks](https://shields.io/github/forks/fancycode/MemoryModule?style=social) ![Github watchers](https://shields.io/github/watchers/fancycode/MemoryModule?style=social)
- github.com/strivexjun/MemoryModulePP ![Github stars](https://shields.io/github/stars/strivexjun/MemoryModulePP?style=social) ![Github forks](https://shields.io/github/forks/strivexjun/MemoryModulePP?style=social) ![Github watchers](https://shields.io/github/watchers/strivexjun/MemoryModulePP?style=social)

## Unpack dll load in runtime

- github.com/1ce0ear/DllLoaderUnpacker ![Github stars](https://shields.io/github/stars/1ce0ear/DllLoaderUnpacker?style=social) ![Github forks](https://shields.io/github/forks/1ce0ear/DllLoaderUnpacker?style=social) ![Github watchers](https://shields.io/github/watchers/1ce0ear/DllLoaderUnpacker?style=social)

## dll hijack

- github.com/itm4n/CDPSvcDllHijacking ![Github stars](https://shields.io/github/stars/itm4n/CDPSvcDllHijacking?style=social) ![Github forks](https://shields.io/github/forks/itm4n/CDPSvcDllHijacking?style=social) ![Github watchers](https://shields.io/github/watchers/itm4n/CDPSvcDllHijacking?style=social)
- github.com/Cybereason/siofra (identify and exploit) ![Github stars](https://shields.io/github/stars/Cybereason/siofra?style=social) ![Github forks](https://shields.io/github/forks/Cybereason/siofra?style=social) ![Github watchers](https://shields.io/github/watchers/Cybereason/siofra?style=social)
- github.com/anhkgg/SuperDllHijack ![Github stars](https://shields.io/github/stars/anhkgg/SuperDllHijack?style=social) ![Github forks](https://shields.io/github/forks/anhkgg/SuperDllHijack?style=social) ![Github watchers](https://shields.io/github/watchers/anhkgg/SuperDllHijack?style=social)
- github.com/strivexjun/AheadLib-x86-x64 ![Github stars](https://shields.io/github/stars/strivexjun/AheadLib-x86-x64?style=social) ![Github forks](https://shields.io/github/forks/strivexjun/AheadLib-x86-x64?style=social) ![Github watchers](https://shields.io/github/watchers/strivexjun/AheadLib-x86-x64?style=social)
- github.com/zeffy/proxydll_template ![Github stars](https://shields.io/github/stars/zeffy/proxydll_template?style=social) ![Github forks](https://shields.io/github/forks/zeffy/proxydll_template?style=social) ![Github watchers](https://shields.io/github/watchers/zeffy/proxydll_template?style=social)

## com hijack

- github.com/leoloobeek/COMProxy ![Github stars](https://shields.io/github/stars/leoloobeek/COMProxy?style=social) ![Github forks](https://shields.io/github/forks/leoloobeek/COMProxy?style=social) ![Github watchers](https://shields.io/github/watchers/leoloobeek/COMProxy?style=social)
- github.com/enigma0x3/MessageBox ![Github stars](https://shields.io/github/stars/enigma0x3/MessageBox?style=social) ![Github forks](https://shields.io/github/forks/enigma0x3/MessageBox?style=social) ![Github watchers](https://shields.io/github/watchers/enigma0x3/MessageBox?style=social)

## anti dll hijack

- github.com/fortiguard-lion/anti-dll-hijacking ![Github stars](https://shields.io/github/stars/fortiguard-lion/anti-dll-hijacking?style=social) ![Github forks](https://shields.io/github/forks/fortiguard-lion/anti-dll-hijacking?style=social) ![Github watchers](https://shields.io/github/watchers/fortiguard-lion/anti-dll-hijacking?style=social)

## process hollowing

- github.com/xfgryujk/InjectExe ![Github stars](https://shields.io/github/stars/xfgryujk/InjectExe?style=social) ![Github forks](https://shields.io/github/forks/xfgryujk/InjectExe?style=social) ![Github watchers](https://shields.io/github/watchers/xfgryujk/InjectExe?style=social)
- github.com/m0n0ph1/Basic-File-Crypter ![Github stars](https://shields.io/github/stars/m0n0ph1/Basic-File-Crypter?style=social) ![Github forks](https://shields.io/github/forks/m0n0ph1/Basic-File-Crypter?style=social) ![Github watchers](https://shields.io/github/watchers/m0n0ph1/Basic-File-Crypter?style=social)
- github.com/Spajed/processrefund ![Github stars](https://shields.io/github/stars/Spajed/processrefund?style=social) ![Github forks](https://shields.io/github/forks/Spajed/processrefund?style=social) ![Github watchers](https://shields.io/github/watchers/Spajed/processrefund?style=social)
- github.com/KernelMode/Process_Doppelganging ![Github stars](https://shields.io/github/stars/KernelMode/Process_Doppelganging?style=social) ![Github forks](https://shields.io/github/forks/KernelMode/Process_Doppelganging?style=social) ![Github watchers](https://shields.io/github/watchers/KernelMode/Process_Doppelganging?style=social)
- github.com/hasherezade/process_doppelganging ![Github stars](https://shields.io/github/stars/hasherezade/process_doppelganging?style=social) ![Github forks](https://shields.io/github/forks/hasherezade/process_doppelganging?style=social) ![Github watchers](https://shields.io/github/watchers/hasherezade/process_doppelganging?style=social)
- github.com/m0n0ph1/Process-Hollowing ![Github stars](https://shields.io/github/stars/m0n0ph1/Process-Hollowing?style=social) ![Github forks](https://shields.io/github/forks/m0n0ph1/Process-Hollowing?style=social) ![Github watchers](https://shields.io/github/watchers/m0n0ph1/Process-Hollowing?style=social)
- github.com/KernelMode/RunPE-ProcessHollowing ![Github stars](https://shields.io/github/stars/KernelMode/RunPE-ProcessHollowing?style=social) ![Github forks](https://shields.io/github/forks/KernelMode/RunPE-ProcessHollowing?style=social) ![Github watchers](https://shields.io/github/watchers/KernelMode/RunPE-ProcessHollowing?style=social)
- github.com/KernelMode/RunPE_Detecter ![Github stars](https://shields.io/github/stars/KernelMode/RunPE_Detecter?style=social) ![Github forks](https://shields.io/github/forks/KernelMode/RunPE_Detecter?style=social) ![Github watchers](https://shields.io/github/watchers/KernelMode/RunPE_Detecter?style=social)

## pe loader

- github.com/FrankStain/pe-loader ![Github stars](https://shields.io/github/stars/FrankStain/pe-loader?style=social) ![Github forks](https://shields.io/github/forks/FrankStain/pe-loader?style=social) ![Github watchers](https://shields.io/github/watchers/FrankStain/pe-loader?style=social)
- github.com/VideoCardGuy/PELoader ![Github stars](https://shields.io/github/stars/VideoCardGuy/PELoader?style=social) ![Github forks](https://shields.io/github/forks/VideoCardGuy/PELoader?style=social) ![Github watchers](https://shields.io/github/watchers/VideoCardGuy/PELoader?style=social)

## memory pe dumper

- github.com/glmcdona/Process-Dump ![Github stars](https://shields.io/github/stars/glmcdona/Process-Dump?style=social) ![Github forks](https://shields.io/github/forks/glmcdona/Process-Dump?style=social) ![Github watchers](https://shields.io/github/watchers/glmcdona/Process-Dump?style=social)

## dll map detection

- github.com/vmcall/MapDetection ![Github stars](https://shields.io/github/stars/vmcall/MapDetection?style=social) ![Github forks](https://shields.io/github/forks/vmcall/MapDetection?style=social) ![Github watchers](https://shields.io/github/watchers/vmcall/MapDetection?style=social)

## dll to shellcode

- github.com/w1nds/dll2shellcode ![Github stars](https://shields.io/github/stars/w1nds/dll2shellcode?style=social) ![Github forks](https://shields.io/github/forks/w1nds/dll2shellcode?style=social) ![Github watchers](https://shields.io/github/watchers/w1nds/dll2shellcode?style=social)

## dll to exe

- github.com/hasherezade/dll_to_exe ![Github stars](https://shields.io/github/stars/hasherezade/dll_to_exe?style=social) ![Github forks](https://shields.io/github/forks/hasherezade/dll_to_exe?style=social) ![Github watchers](https://shields.io/github/watchers/hasherezade/dll_to_exe?style=social)

## hide process

- github.com/M00nRise/ProcessHider ![Github stars](https://shields.io/github/stars/M00nRise/ProcessHider?style=social) ![Github forks](https://shields.io/github/forks/M00nRise/ProcessHider?style=social) ![Github watchers](https://shields.io/github/watchers/M00nRise/ProcessHider?style=social)

## hide & delete dll

- github.com/strivexjun/HideDll ![Github stars](https://shields.io/github/stars/strivexjun/HideDll?style=social) ![Github forks](https://shields.io/github/forks/strivexjun/HideDll?style=social) ![Github watchers](https://shields.io/github/watchers/strivexjun/HideDll?style=social)
- github.com/wyyqyl/HideModule ![Github stars](https://shields.io/github/stars/wyyqyl/HideModule?style=social) ![Github forks](https://shields.io/github/forks/wyyqyl/HideModule?style=social) ![Github watchers](https://shields.io/github/watchers/wyyqyl/HideModule?style=social)

## load driver from memory

- github.com/rogerxiii/kernel-codecave-poc ![Github stars](https://shields.io/github/stars/rogerxiii/kernel-codecave-poc?style=social) ![Github forks](https://shields.io/github/forks/rogerxiii/kernel-codecave-poc?style=social) ![Github watchers](https://shields.io/github/watchers/rogerxiii/kernel-codecave-poc?style=social)
- github.com/ZhuHuiBeiShaDiao/DriverMaper ![Github stars](https://shields.io/github/stars/ZhuHuiBeiShaDiao/DriverMaper?style=social) ![Github forks](https://shields.io/github/forks/ZhuHuiBeiShaDiao/DriverMaper?style=social) ![Github watchers](https://shields.io/github/watchers/ZhuHuiBeiShaDiao/DriverMaper?style=social)
- github.com/fadetrack/KernelMemoryModule (Enable Exception) ![Github stars](https://shields.io/github/stars/fadetrack/KernelMemoryModule?style=social) ![Github forks](https://shields.io/github/forks/fadetrack/KernelMemoryModule?style=social) ![Github watchers](https://shields.io/github/watchers/fadetrack/KernelMemoryModule?style=social)
- github.com/not-wlan/driver-hijack ![Github stars](https://shields.io/github/stars/not-wlan/driver-hijack?style=social) ![Github forks](https://shields.io/github/forks/not-wlan/driver-hijack?style=social) ![Github watchers](https://shields.io/github/watchers/not-wlan/driver-hijack?style=social)
- github.com/Professor-plum/Reflective-Driver-Loader ![Github stars](https://shields.io/github/stars/Professor-plum/Reflective-Driver-Loader?style=social) ![Github forks](https://shields.io/github/forks/Professor-plum/Reflective-Driver-Loader?style=social) ![Github watchers](https://shields.io/github/watchers/Professor-plum/Reflective-Driver-Loader?style=social)

## bypass memory scanner

- github.com/Microwave89/rtsectiontest ![Github stars](https://shields.io/github/stars/Microwave89/rtsectiontest?style=social) ![Github forks](https://shields.io/github/forks/Microwave89/rtsectiontest?style=social) ![Github watchers](https://shields.io/github/watchers/Microwave89/rtsectiontest?style=social)

## KeUserModeCallBack

- github.com/Sqdwr/KeUserModeCallBack ![Github stars](https://shields.io/github/stars/Sqdwr/KeUserModeCallBack?style=social) ![Github forks](https://shields.io/github/forks/Sqdwr/KeUserModeCallBack?style=social) ![Github watchers](https://shields.io/github/watchers/Sqdwr/KeUserModeCallBack?style=social)

## callback

- github.com/Vicshann/PEProtectDrv ![Github stars](https://shields.io/github/stars/Vicshann/PEProtectDrv?style=social) ![Github forks](https://shields.io/github/forks/Vicshann/PEProtectDrv?style=social) ![Github watchers](https://shields.io/github/watchers/Vicshann/PEProtectDrv?style=social)
- github.com/fdiskyou/windows-ps-callbacks-experiments ![Github stars](https://shields.io/github/stars/fdiskyou/windows-ps-callbacks-experiments?style=social) ![Github forks](https://shields.io/github/forks/fdiskyou/windows-ps-callbacks-experiments?style=social) ![Github watchers](https://shields.io/github/watchers/fdiskyou/windows-ps-callbacks-experiments?style=social)
- github.com/maxkray13/Cvc (Communication via callback) ![Github stars](https://shields.io/github/stars/maxkray13/Cvc?style=social) ![Github forks](https://shields.io/github/forks/maxkray13/Cvc?style=social) ![Github watchers](https://shields.io/github/watchers/maxkray13/Cvc?style=social)
- github.com/socjordi/sauron ![Github stars](https://shields.io/github/stars/socjordi/sauron?style=social) ![Github forks](https://shields.io/github/forks/socjordi/sauron?style=social) ![Github watchers](https://shields.io/github/watchers/socjordi/sauron?style=social)
- github.com/OSRDrivers/kmexts (callbacks) ![Github stars](https://shields.io/github/stars/OSRDrivers/kmexts?style=social) ![Github forks](https://shields.io/github/forks/OSRDrivers/kmexts?style=social) ![Github watchers](https://shields.io/github/watchers/OSRDrivers/kmexts?style=social)
- github.com/godaddy/procfilter (yara-integrated) ![Github stars](https://shields.io/github/stars/godaddy/procfilter?style=social) ![Github forks](https://shields.io/github/forks/godaddy/procfilter?style=social) ![Github watchers](https://shields.io/github/watchers/godaddy/procfilter?style=social)
- github.com/McSimp/unfairplay ![Github stars](https://shields.io/github/stars/McSimp/unfairplay?style=social) ![Github forks](https://shields.io/github/forks/McSimp/unfairplay?style=social) ![Github watchers](https://shields.io/github/watchers/McSimp/unfairplay?style=social)
- github.com/jjdredd/procsentinel (verify the address space of a process) ![Github stars](https://shields.io/github/stars/jjdredd/procsentinel?style=social) ![Github forks](https://shields.io/github/forks/jjdredd/procsentinel?style=social) ![Github watchers](https://shields.io/github/watchers/jjdredd/procsentinel?style=social)
- github.com/SanseoLab/simpleAVdriver ![Github stars](https://shields.io/github/stars/SanseoLab/simpleAVdriver?style=social) ![Github forks](https://shields.io/github/forks/SanseoLab/simpleAVdriver?style=social) ![Github watchers](https://shields.io/github/watchers/SanseoLab/simpleAVdriver?style=social)
- github.com/SanseoLab/ProcLogger ![Github stars](https://shields.io/github/stars/SanseoLab/ProcLogger?style=social) ![Github forks](https://shields.io/github/forks/SanseoLab/ProcLogger?style=social) ![Github watchers](https://shields.io/github/watchers/SanseoLab/ProcLogger?style=social)
- github.com/notscimmy/libelevate ![Github stars](https://shields.io/github/stars/notscimmy/libelevate?style=social) ![Github forks](https://shields.io/github/forks/notscimmy/libelevate?style=social) ![Github watchers](https://shields.io/github/watchers/notscimmy/libelevate?style=social)
- github.com/ZhuHuiBeiShaDiao/ObRegisterCallBacksByPass ![Github stars](https://shields.io/github/stars/ZhuHuiBeiShaDiao/ObRegisterCallBacksByPass?style=social) ![Github forks](https://shields.io/github/forks/ZhuHuiBeiShaDiao/ObRegisterCallBacksByPass?style=social) ![Github watchers](https://shields.io/github/watchers/ZhuHuiBeiShaDiao/ObRegisterCallBacksByPass?style=social)
- github.com/Sqdwr/RemoveCallBacks ![Github stars](https://shields.io/github/stars/Sqdwr/RemoveCallBacks?style=social) ![Github forks](https://shields.io/github/forks/Sqdwr/RemoveCallBacks?style=social) ![Github watchers](https://shields.io/github/watchers/Sqdwr/RemoveCallBacks?style=social)
- github.com/JKornev/hidden ![Github stars](https://shields.io/github/stars/JKornev/hidden?style=social) ![Github forks](https://shields.io/github/forks/JKornev/hidden?style=social) ![Github watchers](https://shields.io/github/watchers/JKornev/hidden?style=social)
- github.com/binbibi/CallbackEx ![Github stars](https://shields.io/github/stars/binbibi/CallbackEx?style=social) ![Github forks](https://shields.io/github/forks/binbibi/CallbackEx?style=social) ![Github watchers](https://shields.io/github/watchers/binbibi/CallbackEx?style=social)
- github.com/swwwolf/cbtest ![Github stars](https://shields.io/github/stars/swwwolf/cbtest?style=social) ![Github forks](https://shields.io/github/forks/swwwolf/cbtest?style=social) ![Github watchers](https://shields.io/github/watchers/swwwolf/cbtest?style=social)
- github.com/nmgwddj/Learn-Windows-Drivers ![Github stars](https://shields.io/github/stars/nmgwddj/Learn-Windows-Drivers?style=social) ![Github forks](https://shields.io/github/forks/nmgwddj/Learn-Windows-Drivers?style=social) ![Github watchers](https://shields.io/github/watchers/nmgwddj/Learn-Windows-Drivers?style=social)
- github.com/SamLarenN/CallbackDisabler ![Github stars](https://shields.io/github/stars/SamLarenN/CallbackDisabler?style=social) ![Github forks](https://shields.io/github/forks/SamLarenN/CallbackDisabler?style=social) ![Github watchers](https://shields.io/github/watchers/SamLarenN/CallbackDisabler?style=social)

## keyboard filter

- github.com/supermanc88/KeyboardEncrypt ![Github stars](https://shields.io/github/stars/supermanc88/KeyboardEncrypt?style=social) ![Github forks](https://shields.io/github/forks/supermanc88/KeyboardEncrypt?style=social) ![Github watchers](https://shields.io/github/watchers/supermanc88/KeyboardEncrypt?style=social)

## usb filter

- github.com/changeofpace/MouClassInputInjection ![Github stars](https://shields.io/github/stars/changeofpace/MouClassInputInjection?style=social) ![Github forks](https://shields.io/github/forks/changeofpace/MouClassInputInjection?style=social) ![Github watchers](https://shields.io/github/watchers/changeofpace/MouClassInputInjection?style=social)
- github.com/GoodstudyChina/USBlocker ![Github stars](https://shields.io/github/stars/GoodstudyChina/USBlocker?style=social) ![Github forks](https://shields.io/github/forks/GoodstudyChina/USBlocker?style=social) ![Github watchers](https://shields.io/github/watchers/GoodstudyChina/USBlocker?style=social)

## sfilter

- github.com/JokerRound/FlieSystemFilter ![Github stars](https://shields.io/github/stars/JokerRound/FlieSystemFilter?style=social) ![Github forks](https://shields.io/github/forks/JokerRound/FlieSystemFilter?style=social) ![Github watchers](https://shields.io/github/watchers/JokerRound/FlieSystemFilter?style=social)
- github.com/haidragon/sfilter ![Github stars](https://shields.io/github/stars/haidragon/sfilter?style=social) ![Github forks](https://shields.io/github/forks/haidragon/sfilter?style=social) ![Github watchers](https://shields.io/github/watchers/haidragon/sfilter?style=social)

## minifilter

- github.com/hkx3upper/FOKS-TROT (Transparent Encryption) ![Github stars](https://shields.io/github/stars/hkx3upper/FOKS-TROT?style=social) ![Github forks](https://shields.io/github/forks/hkx3upper/FOKS-TROT?style=social) ![Github watchers](https://shields.io/github/watchers/hkx3upper/FOKS-TROT?style=social)
- github.com/shubham0d/SymBlock  (prevent symbolic link exploits) ![Github stars](https://shields.io/github/stars/shubham0d/SymBlock?style=social) ![Github forks](https://shields.io/github/forks/shubham0d/SymBlock?style=social) ![Github watchers](https://shields.io/github/watchers/shubham0d/SymBlock?style=social)
- github.com/TimelifeCzy/HIPS-HIDS_CveMod (CVE HIPS) ![Github stars](https://shields.io/github/stars/TimelifeCzy/HIPS-HIDS_CveMod?style=social) ![Github forks](https://shields.io/github/forks/TimelifeCzy/HIPS-HIDS_CveMod?style=social) ![Github watchers](https://shields.io/github/watchers/TimelifeCzy/HIPS-HIDS_CveMod?style=social)
- github.com/roman-allen/FSFilterDriver ![Github stars](https://shields.io/github/stars/roman-allen/FSFilterDriver?style=social) ![Github forks](https://shields.io/github/forks/roman-allen/FSFilterDriver?style=social) ![Github watchers](https://shields.io/github/watchers/roman-allen/FSFilterDriver?style=social)
- github.com/jefrimustapa/detect-filename-block ![Github stars](https://shields.io/github/stars/jefrimustapa/detect-filename-block?style=social) ![Github forks](https://shields.io/github/forks/jefrimustapa/detect-filename-block?style=social) ![Github watchers](https://shields.io/github/watchers/jefrimustapa/detect-filename-block?style=social)
- github.com/lxt1045/FileLogger ![Github stars](https://shields.io/github/stars/lxt1045/FileLogger?style=social) ![Github forks](https://shields.io/github/forks/lxt1045/FileLogger?style=social) ![Github watchers](https://shields.io/github/watchers/lxt1045/FileLogger?style=social)
- github.com/vitalikpi/FileWall ![Github stars](https://shields.io/github/stars/vitalikpi/FileWall?style=social) ![Github forks](https://shields.io/github/forks/vitalikpi/FileWall?style=social) ![Github watchers](https://shields.io/github/watchers/vitalikpi/FileWall?style=social)
- github.com/Mermeze/System-Monitor ![Github stars](https://shields.io/github/stars/Mermeze/System-Monitor?style=social) ![Github forks](https://shields.io/github/forks/Mermeze/System-Monitor?style=social) ![Github watchers](https://shields.io/github/watchers/Mermeze/System-Monitor?style=social)
- github.com/cn505240/lightweight-reactive-snapshot-service ![Github stars](https://shields.io/github/stars/cn505240/lightweight-reactive-snapshot-service?style=social) ![Github forks](https://shields.io/github/forks/cn505240/lightweight-reactive-snapshot-service?style=social) ![Github watchers](https://shields.io/github/watchers/cn505240/lightweight-reactive-snapshot-service?style=social)
- github.com/aviadyifrah/NAGuard ![Github stars](https://shields.io/github/stars/aviadyifrah/NAGuard?style=social) ![Github forks](https://shields.io/github/forks/aviadyifrah/NAGuard?style=social) ![Github watchers](https://shields.io/github/watchers/aviadyifrah/NAGuard?style=social)
- github.com/y0n0622/DriversCode ![Github stars](https://shields.io/github/stars/y0n0622/DriversCode?style=social) ![Github forks](https://shields.io/github/forks/y0n0622/DriversCode?style=social) ![Github watchers](https://shields.io/github/watchers/y0n0622/DriversCode?style=social)
- github.com/NotSurprised/MiniLogger ![Github stars](https://shields.io/github/stars/NotSurprised/MiniLogger?style=social) ![Github forks](https://shields.io/github/forks/NotSurprised/MiniLogger?style=social) ![Github watchers](https://shields.io/github/watchers/NotSurprised/MiniLogger?style=social)
- github.com/hidd3ncod3s/hipara ![Github stars](https://shields.io/github/stars/hidd3ncod3s/hipara?style=social) ![Github forks](https://shields.io/github/forks/hidd3ncod3s/hipara?style=social) ![Github watchers](https://shields.io/github/watchers/hidd3ncod3s/hipara?style=social)
- github.com/NtRaiseHardError/Providence ![Github stars](https://shields.io/github/stars/NtRaiseHardError/Providence?style=social) ![Github forks](https://shields.io/github/forks/NtRaiseHardError/Providence?style=social) ![Github watchers](https://shields.io/github/watchers/NtRaiseHardError/Providence?style=social)
- github.com/maaaaz/mimicertz ![Github stars](https://shields.io/github/stars/maaaaz/mimicertz?style=social) ![Github forks](https://shields.io/github/forks/maaaaz/mimicertz?style=social) ![Github watchers](https://shields.io/github/watchers/maaaaz/mimicertz?style=social)
- github.com/MUmesha/SecureFile ![Github stars](https://shields.io/github/stars/MUmesha/SecureFile?style=social) ![Github forks](https://shields.io/github/forks/MUmesha/SecureFile?style=social) ![Github watchers](https://shields.io/github/watchers/MUmesha/SecureFile?style=social)
- github.com/anystayisjk/WordEncrypt ![Github stars](https://shields.io/github/stars/anystayisjk/WordEncrypt?style=social) ![Github forks](https://shields.io/github/forks/anystayisjk/WordEncrypt?style=social) ![Github watchers](https://shields.io/github/watchers/anystayisjk/WordEncrypt?style=social)
- github.com/anystayisjk/EncryptEngine ![Github stars](https://shields.io/github/stars/anystayisjk/EncryptEngine?style=social) ![Github forks](https://shields.io/github/forks/anystayisjk/EncryptEngine?style=social) ![Github watchers](https://shields.io/github/watchers/anystayisjk/EncryptEngine?style=social)
- github.com/yedushusheng/FileEncryption ![Github stars](https://shields.io/github/stars/yedushusheng/FileEncryption?style=social) ![Github forks](https://shields.io/github/forks/yedushusheng/FileEncryption?style=social) ![Github watchers](https://shields.io/github/watchers/yedushusheng/FileEncryption?style=social)
- github.com/JokerMars/engine ![Github stars](https://shields.io/github/stars/JokerMars/engine?style=social) ![Github forks](https://shields.io/github/forks/JokerMars/engine?style=social) ![Github watchers](https://shields.io/github/watchers/JokerMars/engine?style=social)
- github.com/icedxu/Monitor ![Github stars](https://shields.io/github/stars/icedxu/Monitor?style=social) ![Github forks](https://shields.io/github/forks/icedxu/Monitor?style=social) ![Github watchers](https://shields.io/github/watchers/icedxu/Monitor?style=social)
- github.com/smartinm/diskcryptor (disk encrypt) ![Github stars](https://shields.io/github/stars/smartinm/diskcryptor?style=social) ![Github forks](https://shields.io/github/forks/smartinm/diskcryptor?style=social) ![Github watchers](https://shields.io/github/watchers/smartinm/diskcryptor?style=social)
- github.com/hedgeh/SEWindows (HIPS) ![Github stars](https://shields.io/github/stars/hedgeh/SEWindows?style=social) ![Github forks](https://shields.io/github/forks/hedgeh/SEWindows?style=social) ![Github watchers](https://shields.io/github/watchers/hedgeh/SEWindows?style=social)
- github.com/474172261/DataProtector ![Github stars](https://shields.io/github/stars/474172261/DataProtector?style=social) ![Github forks](https://shields.io/github/forks/474172261/DataProtector?style=social) ![Github watchers](https://shields.io/github/watchers/474172261/DataProtector?style=social)
- github.com/CynicalApe/Minifilter-CSHARP-ConsoleApp ![Github stars](https://shields.io/github/stars/CynicalApe/Minifilter-CSHARP-ConsoleApp?style=social) ![Github forks](https://shields.io/github/forks/CynicalApe/Minifilter-CSHARP-ConsoleApp?style=social) ![Github watchers](https://shields.io/github/watchers/CynicalApe/Minifilter-CSHARP-ConsoleApp?style=social)
- github.com/NtRaiseHardError/Anti-Delete (File anti delete) ![Github stars](https://shields.io/github/stars/NtRaiseHardError/Anti-Delete?style=social) ![Github forks](https://shields.io/github/forks/NtRaiseHardError/Anti-Delete?style=social) ![Github watchers](https://shields.io/github/watchers/NtRaiseHardError/Anti-Delete?style=social)
- github.com/Randomize163/FSDefender ![Github stars](https://shields.io/github/stars/Randomize163/FSDefender?style=social) ![Github forks](https://shields.io/github/forks/Randomize163/FSDefender?style=social) ![Github watchers](https://shields.io/github/watchers/Randomize163/FSDefender?style=social)
- github.com/ETEFS/ETEFS_Mini ![Github stars](https://shields.io/github/stars/ETEFS/ETEFS_Mini?style=social) ![Github forks](https://shields.io/github/forks/ETEFS/ETEFS_Mini?style=social) ![Github watchers](https://shields.io/github/watchers/ETEFS/ETEFS_Mini?style=social)
- github.com/gfleury/ProtegeDados_ProjetoFinal ![Github stars](https://shields.io/github/stars/gfleury/ProtegeDados_ProjetoFinal?style=social) ![Github forks](https://shields.io/github/forks/gfleury/ProtegeDados_ProjetoFinal?style=social) ![Github watchers](https://shields.io/github/watchers/gfleury/ProtegeDados_ProjetoFinal?style=social)
- github.com/denisvieriu/Portable-Executable-Minifilter-Driver ![Github stars](https://shields.io/github/stars/denisvieriu/Portable-Executable-Minifilter-Driver?style=social) ![Github forks](https://shields.io/github/forks/denisvieriu/Portable-Executable-Minifilter-Driver?style=social) ![Github watchers](https://shields.io/github/watchers/denisvieriu/Portable-Executable-Minifilter-Driver?style=social)
- github.com/surajfale/passthrough-minifilter-driver ![Github stars](https://shields.io/github/stars/surajfale/passthrough-minifilter-driver?style=social) ![Github forks](https://shields.io/github/forks/surajfale/passthrough-minifilter-driver?style=social) ![Github watchers](https://shields.io/github/watchers/surajfale/passthrough-minifilter-driver?style=social)
- github.com/louk78/Virgo ![Github stars](https://shields.io/github/stars/louk78/Virgo?style=social) ![Github forks](https://shields.io/github/forks/louk78/Virgo?style=social) ![Github watchers](https://shields.io/github/watchers/louk78/Virgo?style=social)
- github.com/tandasat/Scavenger ![Github stars](https://shields.io/github/stars/tandasat/Scavenger?style=social) ![Github forks](https://shields.io/github/forks/tandasat/Scavenger?style=social) ![Github watchers](https://shields.io/github/watchers/tandasat/Scavenger?style=social)
- github.com/dubeyprateek/HideFiles ![Github stars](https://shields.io/github/stars/dubeyprateek/HideFiles?style=social) ![Github forks](https://shields.io/github/forks/dubeyprateek/HideFiles?style=social) ![Github watchers](https://shields.io/github/watchers/dubeyprateek/HideFiles?style=social)
- github.com/aleksk/LazyCopy ![Github stars](https://shields.io/github/stars/aleksk/LazyCopy?style=social) ![Github forks](https://shields.io/github/forks/aleksk/LazyCopy?style=social) ![Github watchers](https://shields.io/github/watchers/aleksk/LazyCopy?style=social)
- github.com/guidoreina/minivers ![Github stars](https://shields.io/github/stars/guidoreina/minivers?style=social) ![Github forks](https://shields.io/github/forks/guidoreina/minivers?style=social) ![Github watchers](https://shields.io/github/watchers/guidoreina/minivers?style=social)
- github.com/idkwim/mfd ![Github stars](https://shields.io/github/stars/idkwim/mfd?style=social) ![Github forks](https://shields.io/github/forks/idkwim/mfd?style=social) ![Github watchers](https://shields.io/github/watchers/idkwim/mfd?style=social)
- github.com/Coxious/Antinvader ![Github stars](https://shields.io/github/stars/Coxious/Antinvader?style=social) ![Github forks](https://shields.io/github/forks/Coxious/Antinvader?style=social) ![Github watchers](https://shields.io/github/watchers/Coxious/Antinvader?style=social)
- github.com/tandasat/Scavenger ![Github stars](https://shields.io/github/stars/tandasat/Scavenger?style=social) ![Github forks](https://shields.io/github/forks/tandasat/Scavenger?style=social) ![Github watchers](https://shields.io/github/watchers/tandasat/Scavenger?style=social)
- github.com/fishfly/X70FSD ![Github stars](https://shields.io/github/stars/fishfly/X70FSD?style=social) ![Github forks](https://shields.io/github/forks/fishfly/X70FSD?style=social) ![Github watchers](https://shields.io/github/watchers/fishfly/X70FSD?style=social)
- github.com/ExpLife/BKAV.Filter ![Github stars](https://shields.io/github/stars/ExpLife/BKAV.Filter?style=social) ![Github forks](https://shields.io/github/forks/ExpLife/BKAV.Filter?style=social) ![Github watchers](https://shields.io/github/watchers/ExpLife/BKAV.Filter?style=social)

## anti Ransomware

- github.com/NtRaiseHardError/Antimalware-Research ![Github stars](https://shields.io/github/stars/NtRaiseHardError/Antimalware-Research?style=social) ![Github forks](https://shields.io/github/forks/NtRaiseHardError/Antimalware-Research?style=social) ![Github watchers](https://shields.io/github/watchers/NtRaiseHardError/Antimalware-Research?style=social)
- github.com/clavis0x/AntiRansomware ![Github stars](https://shields.io/github/stars/clavis0x/AntiRansomware?style=social) ![Github forks](https://shields.io/github/forks/clavis0x/AntiRansomware?style=social) ![Github watchers](https://shields.io/github/watchers/clavis0x/AntiRansomware?style=social)
- github.com/DecryptoniteTeam/Decryptonite ![Github stars](https://shields.io/github/stars/DecryptoniteTeam/Decryptonite?style=social) ![Github forks](https://shields.io/github/forks/DecryptoniteTeam/Decryptonite?style=social) ![Github watchers](https://shields.io/github/watchers/DecryptoniteTeam/Decryptonite?style=social)
- github.com/ofercas/ransomware_begone ![Github stars](https://shields.io/github/stars/ofercas/ransomware_begone?style=social) ![Github forks](https://shields.io/github/forks/ofercas/ransomware_begone?style=social) ![Github watchers](https://shields.io/github/watchers/ofercas/ransomware_begone?style=social)

## virtual disk

- github.com/zhaozhongshu/winvblock_vs ![Github stars](https://shields.io/github/stars/zhaozhongshu/winvblock_vs?style=social) ![Github forks](https://shields.io/github/forks/zhaozhongshu/winvblock_vs?style=social) ![Github watchers](https://shields.io/github/watchers/zhaozhongshu/winvblock_vs?style=social)
- github.com/yogendersolanki91/Kernel-Driver-Example ![Github stars](https://shields.io/github/stars/yogendersolanki91/Kernel-Driver-Example?style=social) ![Github forks](https://shields.io/github/forks/yogendersolanki91/Kernel-Driver-Example?style=social) ![Github watchers](https://shields.io/github/watchers/yogendersolanki91/Kernel-Driver-Example?style=social)

## virtual file system

- github.com/ufrisk/MemProcFS (The Memory Process File System) ![Github stars](https://shields.io/github/stars/ufrisk/MemProcFS?style=social) ![Github forks](https://shields.io/github/forks/ufrisk/MemProcFS?style=social) ![Github watchers](https://shields.io/github/watchers/ufrisk/MemProcFS?style=social)
- github.com/TanninOne/usvfs ![Github stars](https://shields.io/github/stars/TanninOne/usvfs?style=social) ![Github forks](https://shields.io/github/forks/TanninOne/usvfs?style=social) ![Github watchers](https://shields.io/github/watchers/TanninOne/usvfs?style=social)
- github.com/ExpLife/CodeUMVFS ![Github stars](https://shields.io/github/stars/ExpLife/CodeUMVFS?style=social) ![Github forks](https://shields.io/github/forks/ExpLife/CodeUMVFS?style=social) ![Github watchers](https://shields.io/github/watchers/ExpLife/CodeUMVFS?style=social)
- github.com/yogendersolanki91/ProcessFileSystem ![Github stars](https://shields.io/github/stars/yogendersolanki91/ProcessFileSystem?style=social) ![Github forks](https://shields.io/github/forks/yogendersolanki91/ProcessFileSystem?style=social) ![Github watchers](https://shields.io/github/watchers/yogendersolanki91/ProcessFileSystem?style=social)
- github.com/BenjaminKim/dokanx ![Github stars](https://shields.io/github/stars/BenjaminKim/dokanx?style=social) ![Github forks](https://shields.io/github/forks/BenjaminKim/dokanx?style=social) ![Github watchers](https://shields.io/github/watchers/BenjaminKim/dokanx?style=social)

## lpc

- github.com/avalon1610/LPC ![Github stars](https://shields.io/github/stars/avalon1610/LPC?style=social) ![Github forks](https://shields.io/github/forks/avalon1610/LPC?style=social) ![Github watchers](https://shields.io/github/watchers/avalon1610/LPC?style=social)

## alpc

- github.com/LoukaMB/Beacon ![Github stars](https://shields.io/github/stars/LoukaMB/Beacon?style=social) ![Github forks](https://shields.io/github/forks/LoukaMB/Beacon?style=social) ![Github watchers](https://shields.io/github/watchers/LoukaMB/Beacon?style=social)
- github.com/avalon1610/ALPC ![Github stars](https://shields.io/github/stars/avalon1610/ALPC?style=social) ![Github forks](https://shields.io/github/forks/avalon1610/ALPC?style=social) ![Github watchers](https://shields.io/github/watchers/avalon1610/ALPC?style=social)

## lsp/spi

- github.com/TinkerBravo/SPIRemove ![Github stars](https://shields.io/github/stars/TinkerBravo/SPIRemove?style=social) ![Github forks](https://shields.io/github/forks/TinkerBravo/SPIRemove?style=social) ![Github watchers](https://shields.io/github/watchers/TinkerBravo/SPIRemove?style=social)
- github.com/AnwarMohamed/Packetyzer ![Github stars](https://shields.io/github/stars/AnwarMohamed/Packetyzer?style=social) ![Github forks](https://shields.io/github/forks/AnwarMohamed/Packetyzer?style=social) ![Github watchers](https://shields.io/github/watchers/AnwarMohamed/Packetyzer?style=social)

## afd

- github.com/batteryshark/AfdProxy ![Github stars](https://shields.io/github/stars/batteryshark/AfdProxy?style=social) ![Github forks](https://shields.io/github/forks/batteryshark/AfdProxy?style=social) ![Github watchers](https://shields.io/github/watchers/batteryshark/AfdProxy?style=social)
- github.com/xiaomagexiao/GameDll ![Github stars](https://shields.io/github/stars/xiaomagexiao/GameDll?style=social) ![Github forks](https://shields.io/github/forks/xiaomagexiao/GameDll?style=social) ![Github watchers](https://shields.io/github/watchers/xiaomagexiao/GameDll?style=social)
- github.com/DeDf/afd ![Github stars](https://shields.io/github/stars/DeDf/afd?style=social) ![Github forks](https://shields.io/github/forks/DeDf/afd?style=social) ![Github watchers](https://shields.io/github/watchers/DeDf/afd?style=social)
- github.com/a252293079/NProxy ![Github stars](https://shields.io/github/stars/a252293079/NProxy?style=social) ![Github forks](https://shields.io/github/forks/a252293079/NProxy?style=social) ![Github watchers](https://shields.io/github/watchers/a252293079/NProxy?style=social)

## tdi

- github.com/wanttobeno/wmifilter ![Github stars](https://shields.io/github/stars/wanttobeno/wmifilter?style=social) ![Github forks](https://shields.io/github/forks/wanttobeno/wmifilter?style=social) ![Github watchers](https://shields.io/github/watchers/wanttobeno/wmifilter?style=social)
- github.com/xue-blood/adfilter ![Github stars](https://shields.io/github/stars/xue-blood/adfilter?style=social) ![Github forks](https://shields.io/github/forks/xue-blood/adfilter?style=social) ![Github watchers](https://shields.io/github/watchers/xue-blood/adfilter?style=social)
- github.com/alex9191/NetDriver (send & receive HTTP requests) ![Github stars](https://shields.io/github/stars/alex9191/NetDriver?style=social) ![Github forks](https://shields.io/github/forks/alex9191/NetDriver?style=social) ![Github watchers](https://shields.io/github/watchers/alex9191/NetDriver?style=social)
- github.com/alex9191/ZeroBank-ring0-bundle ![Github stars](https://shields.io/github/stars/alex9191/ZeroBank-ring0-bundle?style=social) ![Github forks](https://shields.io/github/forks/alex9191/ZeroBank-ring0-bundle?style=social) ![Github watchers](https://shields.io/github/watchers/alex9191/ZeroBank-ring0-bundle?style=social)
- github.com/Sha0/winvblock ![Github stars](https://shields.io/github/stars/Sha0/winvblock?style=social) ![Github forks](https://shields.io/github/forks/Sha0/winvblock?style=social) ![Github watchers](https://shields.io/github/watchers/Sha0/winvblock?style=social)
- github.com/michael4338/TDI ![Github stars](https://shields.io/github/stars/michael4338/TDI?style=social) ![Github forks](https://shields.io/github/forks/michael4338/TDI?style=social) ![Github watchers](https://shields.io/github/watchers/michael4338/TDI?style=social)
- github.com/cullengao/tdi_monitor ![Github stars](https://shields.io/github/stars/cullengao/tdi_monitor?style=social) ![Github forks](https://shields.io/github/forks/cullengao/tdi_monitor?style=social) ![Github watchers](https://shields.io/github/watchers/cullengao/tdi_monitor?style=social)
- github.com/uniking/TDI-Demo ![Github stars](https://shields.io/github/stars/uniking/TDI-Demo?style=social) ![Github forks](https://shields.io/github/forks/uniking/TDI-Demo?style=social) ![Github watchers](https://shields.io/github/watchers/uniking/TDI-Demo?style=social)
- github.com/codereba/netmon ![Github stars](https://shields.io/github/stars/codereba/netmon?style=social) ![Github forks](https://shields.io/github/forks/codereba/netmon?style=social) ![Github watchers](https://shields.io/github/watchers/codereba/netmon?style=social)

## wfp

- github.com/jellever/StreamDivert ![Github stars](https://shields.io/github/stars/jellever/StreamDivert?style=social) ![Github forks](https://shields.io/github/forks/jellever/StreamDivert?style=social) ![Github watchers](https://shields.io/github/watchers/jellever/StreamDivert?style=social)
- github.com/gifur/NetworkMnt ![Github stars](https://shields.io/github/stars/gifur/NetworkMnt?style=social) ![Github forks](https://shields.io/github/forks/gifur/NetworkMnt?style=social) ![Github watchers](https://shields.io/github/watchers/gifur/NetworkMnt?style=social)
- github.com/guidoreina/http_inspect ![Github stars](https://shields.io/github/stars/guidoreina/http_inspect?style=social) ![Github forks](https://shields.io/github/forks/guidoreina/http_inspect?style=social) ![Github watchers](https://shields.io/github/watchers/guidoreina/http_inspect?style=social)
- github.com/ZhanLang/netmonsys ![Github stars](https://shields.io/github/stars/ZhanLang/netmonsys?style=social) ![Github forks](https://shields.io/github/forks/ZhanLang/netmonsys?style=social) ![Github watchers](https://shields.io/github/watchers/ZhanLang/netmonsys?style=social)
- github.com/reinhardvz/enumwfp ![Github stars](https://shields.io/github/stars/reinhardvz/enumwfp?style=social) ![Github forks](https://shields.io/github/forks/reinhardvz/enumwfp?style=social) ![Github watchers](https://shields.io/github/watchers/reinhardvz/enumwfp?style=social)
- github.com/BOT-Man-JL/WFP-Traffic-Redirection-Driver ![Github stars](https://shields.io/github/stars/BOT-Man-JL/WFP-Traffic-Redirection-Driver?style=social) ![Github forks](https://shields.io/github/forks/BOT-Man-JL/WFP-Traffic-Redirection-Driver?style=social) ![Github watchers](https://shields.io/github/watchers/BOT-Man-JL/WFP-Traffic-Redirection-Driver?style=social)
- github.com/henrypp/simplewall ![Github stars](https://shields.io/github/stars/henrypp/simplewall?style=social) ![Github forks](https://shields.io/github/forks/henrypp/simplewall?style=social) ![Github watchers](https://shields.io/github/watchers/henrypp/simplewall?style=social)
- github.com/dfct/PortMapper (Port Map) ![Github stars](https://shields.io/github/stars/dfct/PortMapper?style=social) ![Github forks](https://shields.io/github/forks/dfct/PortMapper?style=social) ![Github watchers](https://shields.io/github/watchers/dfct/PortMapper?style=social)
- github.com/TinkerBravo/WFPKit ![Github stars](https://shields.io/github/stars/TinkerBravo/WFPKit?style=social) ![Github forks](https://shields.io/github/forks/TinkerBravo/WFPKit?style=social) ![Github watchers](https://shields.io/github/watchers/TinkerBravo/WFPKit?style=social)
- github.com/Arno0x/DivertTCPconn ![Github stars](https://shields.io/github/stars/Arno0x/DivertTCPconn?style=social) ![Github forks](https://shields.io/github/forks/Arno0x/DivertTCPconn?style=social) ![Github watchers](https://shields.io/github/watchers/Arno0x/DivertTCPconn?style=social)
- github.com/mullvad/libwfp ![Github stars](https://shields.io/github/stars/mullvad/libwfp?style=social) ![Github forks](https://shields.io/github/forks/mullvad/libwfp?style=social) ![Github watchers](https://shields.io/github/watchers/mullvad/libwfp?style=social)
- github.com/gifur/NetworkMnt ![Github stars](https://shields.io/github/stars/gifur/NetworkMnt?style=social) ![Github forks](https://shields.io/github/forks/gifur/NetworkMnt?style=social) ![Github watchers](https://shields.io/github/watchers/gifur/NetworkMnt?style=social)
- github.com/ss-abramchuk/OpenVPNAdapter/blob/f016614ed3dec30672e4f1821344b7992825a98d/OpenVPN%20Adapter/Vendors/openvpn/openvpn/tun/win/wfp.hpp ![Github stars](https://shields.io/github/stars/ss-abramchuk/OpenVPNAdapter?style=social) ![Github forks](https://shields.io/github/forks/ss-abramchuk/OpenVPNAdapter?style=social) ![Github watchers](https://shields.io/github/watchers/ss-abramchuk/OpenVPNAdapter?style=social)
- github.com/itari/vapu ![Github stars](https://shields.io/github/stars/itari/vapu?style=social) ![Github forks](https://shields.io/github/forks/itari/vapu?style=social) ![Github watchers](https://shields.io/github/watchers/itari/vapu?style=social)
- github.com/ValdikSS/GoodbyeDPI ![Github stars](https://shields.io/github/stars/ValdikSS/GoodbyeDPI?style=social) ![Github forks](https://shields.io/github/forks/ValdikSS/GoodbyeDPI?style=social) ![Github watchers](https://shields.io/github/watchers/ValdikSS/GoodbyeDPI?style=social)
- github.com/basil00/Divert ![Github stars](https://shields.io/github/stars/basil00/Divert?style=social) ![Github forks](https://shields.io/github/forks/basil00/Divert?style=social) ![Github watchers](https://shields.io/github/watchers/basil00/Divert?style=social)
- github.com/WPO-Foundation/win-shaper ![Github stars](https://shields.io/github/stars/WPO-Foundation/win-shaper?style=social) ![Github forks](https://shields.io/github/forks/WPO-Foundation/win-shaper?style=social) ![Github watchers](https://shields.io/github/watchers/WPO-Foundation/win-shaper?style=social)
- github.com/raymon-tian/WFPFirewall ![Github stars](https://shields.io/github/stars/raymon-tian/WFPFirewall?style=social) ![Github forks](https://shields.io/github/forks/raymon-tian/WFPFirewall?style=social) ![Github watchers](https://shields.io/github/watchers/raymon-tian/WFPFirewall?style=social)
- github.com/killbug2004/HashFilter ![Github stars](https://shields.io/github/stars/killbug2004/HashFilter?style=social) ![Github forks](https://shields.io/github/forks/killbug2004/HashFilter?style=social) ![Github watchers](https://shields.io/github/watchers/killbug2004/HashFilter?style=social)
- github.com/henrypp/simplewall ![Github stars](https://shields.io/github/stars/henrypp/simplewall?style=social) ![Github forks](https://shields.io/github/forks/henrypp/simplewall?style=social) ![Github watchers](https://shields.io/github/watchers/henrypp/simplewall?style=social)
- docs.microsoft.com/zh-cn/windows-hardware/drivers/network/porting-packet-processing-drivers-and-apps-to-wfp
- github.com/thecybermind/ipredir ![Github stars](https://shields.io/github/stars/thecybermind/ipredir?style=social) ![Github forks](https://shields.io/github/forks/thecybermind/ipredir?style=social) ![Github watchers](https://shields.io/github/watchers/thecybermind/ipredir?style=social)

## ndis

- github.com/pr0v3rbs/MalSiteBlocker ![Github stars](https://shields.io/github/stars/pr0v3rbs/MalSiteBlocker?style=social) ![Github forks](https://shields.io/github/forks/pr0v3rbs/MalSiteBlocker?style=social) ![Github watchers](https://shields.io/github/watchers/pr0v3rbs/MalSiteBlocker?style=social)
- github.com/Beamer-LB/netmap/tree/stable/WINDOWS ![Github stars](https://shields.io/github/stars/Beamer-LB/netmap?style=social) ![Github forks](https://shields.io/github/forks/Beamer-LB/netmap?style=social) ![Github watchers](https://shields.io/github/watchers/Beamer-LB/netmap?style=social)
- github.com/ndemarinis/ovs/tree/22a1ba42f8137cd3532b54880b19b51d4b87440d/datapath-windows/ovsext ![Github stars](https://shields.io/github/stars/ndemarinis/ovs?style=social) ![Github forks](https://shields.io/github/forks/ndemarinis/ovs?style=social) ![Github watchers](https://shields.io/github/watchers/ndemarinis/ovs?style=social)
- github.com/markjandrews/CodeMachineCourse/tree/5473d4ea808791c2a048f2c8c9c86f011a6da5e8/source/kerrkt.labs/labs/NdisLwf ![Github stars](https://shields.io/github/stars/markjandrews/CodeMachineCourse?style=social) ![Github forks](https://shields.io/github/forks/markjandrews/CodeMachineCourse?style=social) ![Github watchers](https://shields.io/github/watchers/markjandrews/CodeMachineCourse?style=social)
- github.com/openthread/openthread/tree/master/examples/drivers/windows ![Github stars](https://shields.io/github/stars/openthread/openthread?style=social) ![Github forks](https://shields.io/github/forks/openthread/openthread?style=social) ![Github watchers](https://shields.io/github/watchers/openthread/openthread?style=social)
- github.com/Hartigan/Firewall ![Github stars](https://shields.io/github/stars/Hartigan/Firewall?style=social) ![Github forks](https://shields.io/github/forks/Hartigan/Firewall?style=social) ![Github watchers](https://shields.io/github/watchers/Hartigan/Firewall?style=social)
- github.com/zy520321/ndis-filter ![Github stars](https://shields.io/github/stars/zy520321/ndis-filter?style=social) ![Github forks](https://shields.io/github/forks/zy520321/ndis-filter?style=social) ![Github watchers](https://shields.io/github/watchers/zy520321/ndis-filter?style=social)
- github.com/yuanmaomao/NDIS_Firewall ![Github stars](https://shields.io/github/stars/yuanmaomao/NDIS_Firewall?style=social) ![Github forks](https://shields.io/github/forks/yuanmaomao/NDIS_Firewall?style=social) ![Github watchers](https://shields.io/github/watchers/yuanmaomao/NDIS_Firewall?style=social)
- github.com/SoftEtherVPN/Win10Pcap ![Github stars](https://shields.io/github/stars/SoftEtherVPN/Win10Pcap?style=social) ![Github forks](https://shields.io/github/forks/SoftEtherVPN/Win10Pcap?style=social) ![Github watchers](https://shields.io/github/watchers/SoftEtherVPN/Win10Pcap?style=social)
- github.com/IsoGrid/NdisProtocol ![Github stars](https://shields.io/github/stars/IsoGrid/NdisProtocol?style=social) ![Github forks](https://shields.io/github/forks/IsoGrid/NdisProtocol?style=social) ![Github watchers](https://shields.io/github/watchers/IsoGrid/NdisProtocol?style=social)
- github.com/lcxl/lcxl-net-loader ![Github stars](https://shields.io/github/stars/lcxl/lcxl-net-loader?style=social) ![Github forks](https://shields.io/github/forks/lcxl/lcxl-net-loader?style=social) ![Github watchers](https://shields.io/github/watchers/lcxl/lcxl-net-loader?style=social)
- www.ntkernel.com/windows-packet-filter/
- github.com/michael4338/NDIS ![Github stars](https://shields.io/github/stars/michael4338/NDIS?style=social) ![Github forks](https://shields.io/github/forks/michael4338/NDIS?style=social) ![Github watchers](https://shields.io/github/watchers/michael4338/NDIS?style=social)
- github.com/IAmAnubhavSaini/ndislwf ![Github stars](https://shields.io/github/stars/IAmAnubhavSaini/ndislwf?style=social) ![Github forks](https://shields.io/github/forks/IAmAnubhavSaini/ndislwf?style=social) ![Github watchers](https://shields.io/github/watchers/IAmAnubhavSaini/ndislwf?style=social)
- github.com/OpenVPN/tap-windows6 ![Github stars](https://shields.io/github/stars/OpenVPN/tap-windows6?style=social) ![Github forks](https://shields.io/github/forks/OpenVPN/tap-windows6?style=social) ![Github watchers](https://shields.io/github/watchers/OpenVPN/tap-windows6?style=social)
- github.com/SageAxcess/pcap-ndis6 ![Github stars](https://shields.io/github/stars/SageAxcess/pcap-ndis6?style=social) ![Github forks](https://shields.io/github/forks/SageAxcess/pcap-ndis6?style=social) ![Github watchers](https://shields.io/github/watchers/SageAxcess/pcap-ndis6?style=social)
- github.com/uniking/NDIS-Demo ![Github stars](https://shields.io/github/stars/uniking/NDIS-Demo?style=social) ![Github forks](https://shields.io/github/forks/uniking/NDIS-Demo?style=social) ![Github watchers](https://shields.io/github/watchers/uniking/NDIS-Demo?style=social)
- github.com/mkdym/NDISDriverInst ![Github stars](https://shields.io/github/stars/mkdym/NDISDriverInst?style=social) ![Github forks](https://shields.io/github/forks/mkdym/NDISDriverInst?style=social) ![Github watchers](https://shields.io/github/watchers/mkdym/NDISDriverInst?style=social)
- github.com/debugfan/packetprot ![Github stars](https://shields.io/github/stars/debugfan/packetprot?style=social) ![Github forks](https://shields.io/github/forks/debugfan/packetprot?style=social) ![Github watchers](https://shields.io/github/watchers/debugfan/packetprot?style=social)
- github.com/Iamgublin/NDIS6.30-NetMonitor ![Github stars](https://shields.io/github/stars/Iamgublin/NDIS6.30-NetMonitor?style=social) ![Github forks](https://shields.io/github/forks/Iamgublin/NDIS6.30-NetMonitor?style=social) ![Github watchers](https://shields.io/github/watchers/Iamgublin/NDIS6.30-NetMonitor?style=social)
- github.com/nmap/npcap ![Github stars](https://shields.io/github/stars/nmap/npcap?style=social) ![Github forks](https://shields.io/github/forks/nmap/npcap?style=social) ![Github watchers](https://shields.io/github/watchers/nmap/npcap?style=social)
- github.com/Ltangjian/FireWall ![Github stars](https://shields.io/github/stars/Ltangjian/FireWall?style=social) ![Github forks](https://shields.io/github/forks/Ltangjian/FireWall?style=social) ![Github watchers](https://shields.io/github/watchers/Ltangjian/FireWall?style=social)
- github.com/Microsoft/Windows-driver-samples/tree/master/network/config/bindview ![Github stars](https://shields.io/github/stars/Microsoft/Windows-driver-samples?style=social) ![Github forks](https://shields.io/github/forks/Microsoft/Windows-driver-samples?style=social) ![Github watchers](https://shields.io/github/watchers/Microsoft/Windows-driver-samples?style=social)
- github.com/brorica/http_inject (winpcap) ![Github stars](https://shields.io/github/stars/brorica/http_inject?style=social) ![Github forks](https://shields.io/github/forks/brorica/http_inject?style=social) ![Github watchers](https://shields.io/github/watchers/brorica/http_inject?style=social)

## game accelerator
  
- github.com/NetchX/Netch ![Github stars](https://shields.io/github/stars/NetchX/Netch?style=social) ![Github forks](https://shields.io/github/forks/NetchX/Netch?style=social) ![Github watchers](https://shields.io/github/watchers/NetchX/Netch?style=social)

## wsk

- github.com/Deputation/kernel_sockets_memory ![Github stars](https://shields.io/github/stars/Deputation/kernel_sockets_memory?style=social) ![Github forks](https://shields.io/github/forks/Deputation/kernel_sockets_memory?style=social) ![Github watchers](https://shields.io/github/watchers/Deputation/kernel_sockets_memory?style=social)
- github.com/adrianyy/rw_socket_driver ![Github stars](https://shields.io/github/stars/adrianyy/rw_socket_driver?style=social) ![Github forks](https://shields.io/github/forks/adrianyy/rw_socket_driver?style=social) ![Github watchers](https://shields.io/github/watchers/adrianyy/rw_socket_driver?style=social)
- github.com/wbenny/KSOCKET ![Github stars](https://shields.io/github/stars/wbenny/KSOCKET?style=social) ![Github forks](https://shields.io/github/forks/wbenny/KSOCKET?style=social) ![Github watchers](https://shields.io/github/watchers/wbenny/KSOCKET?style=social)
- github.com/xalley/WskHttp ![Github stars](https://shields.io/github/stars/xalley/WskHttp?style=social) ![Github forks](https://shields.io/github/forks/xalley/WskHttp?style=social) ![Github watchers](https://shields.io/github/watchers/xalley/WskHttp?style=social)
- github.com/reinhardvz/wsk ![Github stars](https://shields.io/github/stars/reinhardvz/wsk?style=social) ![Github forks](https://shields.io/github/forks/reinhardvz/wsk?style=social) ![Github watchers](https://shields.io/github/watchers/reinhardvz/wsk?style=social)
- github.com/akayn/kbMon ![Github stars](https://shields.io/github/stars/akayn/kbMon?style=social) ![Github forks](https://shields.io/github/forks/akayn/kbMon?style=social) ![Github watchers](https://shields.io/github/watchers/akayn/kbMon?style=social)
- github.com/02strich/audionet ![Github stars](https://shields.io/github/stars/02strich/audionet?style=social) ![Github forks](https://shields.io/github/forks/02strich/audionet?style=social) ![Github watchers](https://shields.io/github/watchers/02strich/audionet?style=social)
- github.com/mestefy/securityplus ![Github stars](https://shields.io/github/stars/mestefy/securityplus?style=social) ![Github forks](https://shields.io/github/forks/mestefy/securityplus?style=social) ![Github watchers](https://shields.io/github/watchers/mestefy/securityplus?style=social)
- github.com/skycipher/CNGProvider ![Github stars](https://shields.io/github/stars/skycipher/CNGProvider?style=social) ![Github forks](https://shields.io/github/forks/skycipher/CNGProvider?style=social) ![Github watchers](https://shields.io/github/watchers/skycipher/CNGProvider?style=social)

## rootkits

- github.com/FiYHer/kernel_window_hide (hide window from kernel) ![Github stars](https://shields.io/github/stars/FiYHer/kernel_window_hide?style=social) ![Github forks](https://shields.io/github/forks/FiYHer/kernel_window_hide?style=social) ![Github watchers](https://shields.io/github/watchers/FiYHer/kernel_window_hide?style=social)
- github.com/KANKOSHEV/NoScreen (hide window from kernel) ![Github stars](https://shields.io/github/stars/KANKOSHEV/NoScreen?style=social) ![Github forks](https://shields.io/github/forks/KANKOSHEV/NoScreen?style=social) ![Github watchers](https://shields.io/github/watchers/KANKOSHEV/NoScreen?style=social)
- github.com/FiYHer/EASY-HWID-SPOOFER ![Github stars](https://shields.io/github/stars/FiYHer/EASY-HWID-SPOOFER?style=social) ![Github forks](https://shields.io/github/forks/FiYHer/EASY-HWID-SPOOFER?style=social) ![Github watchers](https://shields.io/github/watchers/FiYHer/EASY-HWID-SPOOFER?style=social)
- github.com/jguo52/NtCompareSigningLevel-hook (NtCompareSigningLevels) ![Github stars](https://shields.io/github/stars/jguo52/NtCompareSigningLevel-hook?style=social) ![Github forks](https://shields.io/github/forks/jguo52/NtCompareSigningLevel-hook?style=social) ![Github watchers](https://shields.io/github/watchers/jguo52/NtCompareSigningLevel-hook?style=social)
- github.com/bytecode77/living-off-the-land (fileless) ![Github stars](https://shields.io/github/stars/bytecode77/living-off-the-land?style=social) ![Github forks](https://shields.io/github/forks/bytecode77/living-off-the-land?style=social) ![Github watchers](https://shields.io/github/watchers/bytecode77/living-off-the-land?style=social)
- github.com/D4stiny/spectre ![Github stars](https://shields.io/github/stars/D4stiny/spectre?style=social) ![Github forks](https://shields.io/github/forks/D4stiny/spectre?style=social) ![Github watchers](https://shields.io/github/watchers/D4stiny/spectre?style=social)
- github.com/thesecretclub/window_hijack ![Github stars](https://shields.io/github/stars/thesecretclub/window_hijack?style=social) ![Github forks](https://shields.io/github/forks/thesecretclub/window_hijack?style=social) ![Github watchers](https://shields.io/github/watchers/thesecretclub/window_hijack?style=social)
- github.com/Mr-Un1k0d3r/SCShell ![Github stars](https://shields.io/github/stars/Mr-Un1k0d3r/SCShell?style=social) ![Github forks](https://shields.io/github/forks/Mr-Un1k0d3r/SCShell?style=social) ![Github watchers](https://shields.io/github/watchers/Mr-Un1k0d3r/SCShell?style=social)
- github.com/realoriginal/doublepulsar-poc ![Github stars](https://shields.io/github/stars/realoriginal/doublepulsar-poc?style=social) ![Github forks](https://shields.io/github/forks/realoriginal/doublepulsar-poc?style=social) ![Github watchers](https://shields.io/github/watchers/realoriginal/doublepulsar-poc?style=social)
- github.com/zouxianyu/PhysicalMemoryRW ![Github stars](https://shields.io/github/stars/zouxianyu/PhysicalMemoryRW?style=social) ![Github forks](https://shields.io/github/forks/zouxianyu/PhysicalMemoryRW?style=social) ![Github watchers](https://shields.io/github/watchers/zouxianyu/PhysicalMemoryRW?style=social)
- github.com/zouxianyu/KernelHiddenExecute ![Github stars](https://shields.io/github/stars/zouxianyu/KernelHiddenExecute?style=social) ![Github forks](https://shields.io/github/forks/zouxianyu/KernelHiddenExecute?style=social) ![Github watchers](https://shields.io/github/watchers/zouxianyu/KernelHiddenExecute?style=social)
- github.com/isoadam/gina_public ![Github stars](https://shields.io/github/stars/isoadam/gina_public?style=social) ![Github forks](https://shields.io/github/forks/isoadam/gina_public?style=social) ![Github watchers](https://shields.io/github/watchers/isoadam/gina_public?style=social)
- github.com/GayPig/driverless-basic-driver ![Github stars](https://shields.io/github/stars/GayPig/driverless-basic-driver?style=social) ![Github forks](https://shields.io/github/forks/GayPig/driverless-basic-driver?style=social) ![Github watchers](https://shields.io/github/watchers/GayPig/driverless-basic-driver?style=social)
- github.com/zerosum0x0/smbdoor ![Github stars](https://shields.io/github/stars/zerosum0x0/smbdoor?style=social) ![Github forks](https://shields.io/github/forks/zerosum0x0/smbdoor?style=social) ![Github watchers](https://shields.io/github/watchers/zerosum0x0/smbdoor?style=social)
- github.com/Alex3434/wmi-static-spoofer ![Github stars](https://shields.io/github/stars/Alex3434/wmi-static-spoofer?style=social) ![Github forks](https://shields.io/github/forks/Alex3434/wmi-static-spoofer?style=social) ![Github watchers](https://shields.io/github/watchers/Alex3434/wmi-static-spoofer?style=social)
- github.com/KIDofot/BypassDriverDetection_And_Kill360Process ![Github stars](https://shields.io/github/stars/KIDofot/BypassDriverDetection_And_Kill360Process?style=social) ![Github forks](https://shields.io/github/forks/KIDofot/BypassDriverDetection_And_Kill360Process?style=social) ![Github watchers](https://shields.io/github/watchers/KIDofot/BypassDriverDetection_And_Kill360Process?style=social)
- github.com/longmode/UTKModule ![Github stars](https://shields.io/github/stars/longmode/UTKModule?style=social) ![Github forks](https://shields.io/github/forks/longmode/UTKModule?style=social) ![Github watchers](https://shields.io/github/watchers/longmode/UTKModule?style=social)
- github.com/nkga/cheat-driver (read/write memory of arbitrary processes) ![Github stars](https://shields.io/github/stars/nkga/cheat-driver?style=social) ![Github forks](https://shields.io/github/forks/nkga/cheat-driver?style=social) ![Github watchers](https://shields.io/github/watchers/nkga/cheat-driver?style=social)
- github.com/lantaoxu/HWIDFaker (hwid fake) ![Github stars](https://shields.io/github/stars/lantaoxu/HWIDFaker?style=social) ![Github forks](https://shields.io/github/forks/lantaoxu/HWIDFaker?style=social) ![Github watchers](https://shields.io/github/watchers/lantaoxu/HWIDFaker?style=social)
- github.com/zerosum0x0/puppetstrings ![Github stars](https://shields.io/github/stars/zerosum0x0/puppetstrings?style=social) ![Github forks](https://shields.io/github/forks/zerosum0x0/puppetstrings?style=social) ![Github watchers](https://shields.io/github/watchers/zerosum0x0/puppetstrings?style=social)
- github.com/Synestraa/Highcall-Library (Highcall) ![Github stars](https://shields.io/github/stars/Synestraa/Highcall-Library?style=social) ![Github forks](https://shields.io/github/forks/Synestraa/Highcall-Library?style=social) ![Github watchers](https://shields.io/github/watchers/Synestraa/Highcall-Library?style=social)
- github.com/Microwave89/drvtricks ![Github stars](https://shields.io/github/stars/Microwave89/drvtricks?style=social) ![Github forks](https://shields.io/github/forks/Microwave89/drvtricks?style=social) ![Github watchers](https://shields.io/github/watchers/Microwave89/drvtricks?style=social)
- github.com/Psychotropos/xhunter1_privesc (XIGNCODE3) ![Github stars](https://shields.io/github/stars/Psychotropos/xhunter1_privesc?style=social) ![Github forks](https://shields.io/github/forks/Psychotropos/xhunter1_privesc?style=social) ![Github watchers](https://shields.io/github/watchers/Psychotropos/xhunter1_privesc?style=social)
- github.com/ionescu007/r0ak (RWE) ![Github stars](https://shields.io/github/stars/ionescu007/r0ak?style=social) ![Github forks](https://shields.io/github/forks/ionescu007/r0ak?style=social) ![Github watchers](https://shields.io/github/watchers/ionescu007/r0ak?style=social)
- github.com/cyberweapons/cyberweapons ![Github stars](https://shields.io/github/stars/cyberweapons/cyberweapons?style=social) ![Github forks](https://shields.io/github/forks/cyberweapons/cyberweapons?style=social) ![Github watchers](https://shields.io/github/watchers/cyberweapons/cyberweapons?style=social)
- github.com/huoji120/AV-Killer ![Github stars](https://shields.io/github/stars/huoji120/AV-Killer?style=social) ![Github forks](https://shields.io/github/forks/huoji120/AV-Killer?style=social) ![Github watchers](https://shields.io/github/watchers/huoji120/AV-Killer?style=social)
- github.com/Sqdwr/DeleteFile ![Github stars](https://shields.io/github/stars/Sqdwr/DeleteFile?style=social) ![Github forks](https://shields.io/github/forks/Sqdwr/DeleteFile?style=social) ![Github watchers](https://shields.io/github/watchers/Sqdwr/DeleteFile?style=social)
- github.com/Sqdwr/DeleteFileByCreateIrp ![Github stars](https://shields.io/github/stars/Sqdwr/DeleteFileByCreateIrp?style=social) ![Github forks](https://shields.io/github/forks/Sqdwr/DeleteFileByCreateIrp?style=social) ![Github watchers](https://shields.io/github/watchers/Sqdwr/DeleteFileByCreateIrp?style=social)
- github.com/Mattiwatti/PPLKiller ![Github stars](https://shields.io/github/stars/Mattiwatti/PPLKiller?style=social) ![Github forks](https://shields.io/github/forks/Mattiwatti/PPLKiller?style=social) ![Github watchers](https://shields.io/github/watchers/Mattiwatti/PPLKiller?style=social)
- github.com/bfosterjr/ci_mod ![Github stars](https://shields.io/github/stars/bfosterjr/ci_mod?style=social) ![Github forks](https://shields.io/github/forks/bfosterjr/ci_mod?style=social) ![Github watchers](https://shields.io/github/watchers/bfosterjr/ci_mod?style=social)
- github.com/HoShiMin/EnjoyTheRing0 ![Github stars](https://shields.io/github/stars/HoShiMin/EnjoyTheRing0?style=social) ![Github forks](https://shields.io/github/forks/HoShiMin/EnjoyTheRing0?style=social) ![Github watchers](https://shields.io/github/watchers/HoShiMin/EnjoyTheRing0?style=social)
- github.com/hfiref0x/ZeroAccess ![Github stars](https://shields.io/github/stars/hfiref0x/ZeroAccess?style=social) ![Github forks](https://shields.io/github/forks/hfiref0x/ZeroAccess?style=social) ![Github watchers](https://shields.io/github/watchers/hfiref0x/ZeroAccess?style=social)
- github.com/hackedteam/driver-win32 ![Github stars](https://shields.io/github/stars/hackedteam/driver-win32?style=social) ![Github forks](https://shields.io/github/forks/hackedteam/driver-win32?style=social) ![Github watchers](https://shields.io/github/watchers/hackedteam/driver-win32?style=social)
- github.com/hackedteam/driver-win64 ![Github stars](https://shields.io/github/stars/hackedteam/driver-win64?style=social) ![Github forks](https://shields.io/github/forks/hackedteam/driver-win64?style=social) ![Github watchers](https://shields.io/github/watchers/hackedteam/driver-win64?style=social)
- github.com/csurage/Rootkit ![Github stars](https://shields.io/github/stars/csurage/Rootkit?style=social) ![Github forks](https://shields.io/github/forks/csurage/Rootkit?style=social) ![Github watchers](https://shields.io/github/watchers/csurage/Rootkit?style=social)
- github.com/bowlofstew/rootkit.com ![Github stars](https://shields.io/github/stars/bowlofstew/rootkit.com?style=social) ![Github forks](https://shields.io/github/forks/bowlofstew/rootkit.com?style=social) ![Github watchers](https://shields.io/github/watchers/bowlofstew/rootkit.com?style=social)
- github.com/Nervous/GreenKit-Rootkit ![Github stars](https://shields.io/github/stars/Nervous/GreenKit-Rootkit?style=social) ![Github forks](https://shields.io/github/forks/Nervous/GreenKit-Rootkit?style=social) ![Github watchers](https://shields.io/github/watchers/Nervous/GreenKit-Rootkit?style=social)
- github.com/bytecode-77/r77-rootkit ![Github stars](https://shields.io/github/stars/bytecode-77/r77-rootkit?style=social) ![Github forks](https://shields.io/github/forks/bytecode-77/r77-rootkit?style=social) ![Github watchers](https://shields.io/github/watchers/bytecode-77/r77-rootkit?style=social)
- github.com/Cr4sh/WindowsRegistryRootkit ![Github stars](https://shields.io/github/stars/Cr4sh/WindowsRegistryRootkit?style=social) ![Github forks](https://shields.io/github/forks/Cr4sh/WindowsRegistryRootkit?style=social) ![Github watchers](https://shields.io/github/watchers/Cr4sh/WindowsRegistryRootkit?style=social)
- github.com/Alifcccccc/Windows-Rootkits ![Github stars](https://shields.io/github/stars/Alifcccccc/Windows-Rootkits?style=social) ![Github forks](https://shields.io/github/forks/Alifcccccc/Windows-Rootkits?style=social) ![Github watchers](https://shields.io/github/watchers/Alifcccccc/Windows-Rootkits?style=social)
- github.com/Schnocker/NoEye ![Github stars](https://shields.io/github/stars/Schnocker/NoEye?style=social) ![Github forks](https://shields.io/github/forks/Schnocker/NoEye?style=social) ![Github watchers](https://shields.io/github/watchers/Schnocker/NoEye?style=social)
- github.com/christian-roggia/open-myrtus ![Github stars](https://shields.io/github/stars/christian-roggia/open-myrtus?style=social) ![Github forks](https://shields.io/github/forks/christian-roggia/open-myrtus?style=social) ![Github watchers](https://shields.io/github/watchers/christian-roggia/open-myrtus?style=social)
- github.com/Cr4sh/DrvHide-PoC ![Github stars](https://shields.io/github/stars/Cr4sh/DrvHide-PoC?style=social) ![Github forks](https://shields.io/github/forks/Cr4sh/DrvHide-PoC?style=social) ![Github watchers](https://shields.io/github/watchers/Cr4sh/DrvHide-PoC?style=social)
- github.com/mstefanowich/SquiddlyDiddly2 ![Github stars](https://shields.io/github/stars/mstefanowich/SquiddlyDiddly2?style=social) ![Github forks](https://shields.io/github/forks/mstefanowich/SquiddlyDiddly2?style=social) ![Github watchers](https://shields.io/github/watchers/mstefanowich/SquiddlyDiddly2?style=social)
- github.com/MalwareTech/FakeMBR ![Github stars](https://shields.io/github/stars/MalwareTech/FakeMBR?style=social) ![Github forks](https://shields.io/github/forks/MalwareTech/FakeMBR?style=social) ![Github watchers](https://shields.io/github/watchers/MalwareTech/FakeMBR?style=social)
- github.com/Cr4sh/PTBypass-PoC ![Github stars](https://shields.io/github/stars/Cr4sh/PTBypass-PoC?style=social) ![Github forks](https://shields.io/github/forks/Cr4sh/PTBypass-PoC?style=social) ![Github watchers](https://shields.io/github/watchers/Cr4sh/PTBypass-PoC?style=social)
- github.com/psaneme/Kung-Fu-Malware ![Github stars](https://shields.io/github/stars/psaneme/Kung-Fu-Malware?style=social) ![Github forks](https://shields.io/github/forks/psaneme/Kung-Fu-Malware?style=social) ![Github watchers](https://shields.io/github/watchers/psaneme/Kung-Fu-Malware?style=social)
- github.com/hasherezade/persistence_demos ![Github stars](https://shields.io/github/stars/hasherezade/persistence_demos?style=social) ![Github forks](https://shields.io/github/forks/hasherezade/persistence_demos?style=social) ![Github watchers](https://shields.io/github/watchers/hasherezade/persistence_demos?style=social)
- github.com/MinhasKamal/TrojanCockroach ![Github stars](https://shields.io/github/stars/MinhasKamal/TrojanCockroach?style=social) ![Github forks](https://shields.io/github/forks/MinhasKamal/TrojanCockroach?style=social) ![Github watchers](https://shields.io/github/watchers/MinhasKamal/TrojanCockroach?style=social)
- github.com/akayn/kbMon ![Github stars](https://shields.io/github/stars/akayn/kbMon?style=social) ![Github forks](https://shields.io/github/forks/akayn/kbMon?style=social) ![Github watchers](https://shields.io/github/watchers/akayn/kbMon?style=social)

## mbr

- github.com/Cisco-Talos/MBRFilter ![Github stars](https://shields.io/github/stars/Cisco-Talos/MBRFilter?style=social) ![Github forks](https://shields.io/github/forks/Cisco-Talos/MBRFilter?style=social) ![Github watchers](https://shields.io/github/watchers/Cisco-Talos/MBRFilter?style=social)

## bootkits

- github.com/btbd/umap ![Github stars](https://shields.io/github/stars/btbd/umap?style=social) ![Github forks](https://shields.io/github/forks/btbd/umap?style=social) ![Github watchers](https://shields.io/github/watchers/btbd/umap?style=social)
- github.com/DeviceObject/rk2017 ![Github stars](https://shields.io/github/stars/DeviceObject/rk2017?style=social) ![Github forks](https://shields.io/github/forks/DeviceObject/rk2017?style=social) ![Github watchers](https://shields.io/github/watchers/DeviceObject/rk2017?style=social)
- github.com/DeviceObject/ChangeDiskSector ![Github stars](https://shields.io/github/stars/DeviceObject/ChangeDiskSector?style=social) ![Github forks](https://shields.io/github/forks/DeviceObject/ChangeDiskSector?style=social) ![Github watchers](https://shields.io/github/watchers/DeviceObject/ChangeDiskSector?style=social)
- github.com/DeviceObject/Uefi_HelloWorld ![Github stars](https://shields.io/github/stars/DeviceObject/Uefi_HelloWorld?style=social) ![Github forks](https://shields.io/github/forks/DeviceObject/Uefi_HelloWorld?style=social) ![Github watchers](https://shields.io/github/watchers/DeviceObject/Uefi_HelloWorld?style=social)
- github.com/DeviceObject/ShitDrv ![Github stars](https://shields.io/github/stars/DeviceObject/ShitDrv?style=social) ![Github forks](https://shields.io/github/forks/DeviceObject/ShitDrv?style=social) ![Github watchers](https://shields.io/github/watchers/DeviceObject/ShitDrv?style=social)
- github.com/DeviceObject/DarkCloud ![Github stars](https://shields.io/github/stars/DeviceObject/DarkCloud?style=social) ![Github forks](https://shields.io/github/forks/DeviceObject/DarkCloud?style=social) ![Github watchers](https://shields.io/github/watchers/DeviceObject/DarkCloud?style=social)
- github.com/nyx0/Rovnix ![Github stars](https://shields.io/github/stars/nyx0/Rovnix?style=social) ![Github forks](https://shields.io/github/forks/nyx0/Rovnix?style=social) ![Github watchers](https://shields.io/github/watchers/nyx0/Rovnix?style=social)
- github.com/MalwareTech/TinyXPB ![Github stars](https://shields.io/github/stars/MalwareTech/TinyXPB?style=social) ![Github forks](https://shields.io/github/forks/MalwareTech/TinyXPB?style=social) ![Github watchers](https://shields.io/github/watchers/MalwareTech/TinyXPB?style=social)
- github.com/m0n0ph1/Win64-Rovnix-VBR-Bootkit ![Github stars](https://shields.io/github/stars/m0n0ph1/Win64-Rovnix-VBR-Bootkit?style=social) ![Github forks](https://shields.io/github/forks/m0n0ph1/Win64-Rovnix-VBR-Bootkit?style=social) ![Github watchers](https://shields.io/github/watchers/m0n0ph1/Win64-Rovnix-VBR-Bootkit?style=social)
- github.com/NextSecurity/Gozi-MBR-rootkit ![Github stars](https://shields.io/github/stars/NextSecurity/Gozi-MBR-rootkit?style=social) ![Github forks](https://shields.io/github/forks/NextSecurity/Gozi-MBR-rootkit?style=social) ![Github watchers](https://shields.io/github/watchers/NextSecurity/Gozi-MBR-rootkit?style=social)
- github.com/NextSecurity/vector-edk ![Github stars](https://shields.io/github/stars/NextSecurity/vector-edk?style=social) ![Github forks](https://shields.io/github/forks/NextSecurity/vector-edk?style=social) ![Github watchers](https://shields.io/github/watchers/NextSecurity/vector-edk?style=social)
- github.com/ahixon/booty ![Github stars](https://shields.io/github/stars/ahixon/booty?style=social) ![Github forks](https://shields.io/github/forks/ahixon/booty?style=social) ![Github watchers](https://shields.io/github/watchers/ahixon/booty?style=social)

## uefi/smm

- github.com/SunnyKi/bareBoot ![Github stars](https://shields.io/github/stars/SunnyKi/bareBoot?style=social) ![Github forks](https://shields.io/github/forks/SunnyKi/bareBoot?style=social) ![Github watchers](https://shields.io/github/watchers/SunnyKi/bareBoot?style=social)
- github.com/DeviceObject/Uefi_HelloWorld ![Github stars](https://shields.io/github/stars/DeviceObject/Uefi_HelloWorld?style=social) ![Github forks](https://shields.io/github/forks/DeviceObject/Uefi_HelloWorld?style=social) ![Github watchers](https://shields.io/github/watchers/DeviceObject/Uefi_HelloWorld?style=social)
- github.com/LongSoft/UEFITool ![Github stars](https://shields.io/github/stars/LongSoft/UEFITool?style=social) ![Github forks](https://shields.io/github/forks/LongSoft/UEFITool?style=social) ![Github watchers](https://shields.io/github/watchers/LongSoft/UEFITool?style=social)
- github.com/dude719/UEFI-Bootkit ![Github stars](https://shields.io/github/stars/dude719/UEFI-Bootkit?style=social) ![Github forks](https://shields.io/github/forks/dude719/UEFI-Bootkit?style=social) ![Github watchers](https://shields.io/github/watchers/dude719/UEFI-Bootkit?style=social)
- github.com/quarkslab/dreamboot ![Github stars](https://shields.io/github/stars/quarkslab/dreamboot?style=social) ![Github forks](https://shields.io/github/forks/quarkslab/dreamboot?style=social) ![Github watchers](https://shields.io/github/watchers/quarkslab/dreamboot?style=social)
- github.com/gyje/BIOS_Rootkit ![Github stars](https://shields.io/github/stars/gyje/BIOS_Rootkit?style=social) ![Github forks](https://shields.io/github/forks/gyje/BIOS_Rootkit?style=social) ![Github watchers](https://shields.io/github/watchers/gyje/BIOS_Rootkit?style=social)
- github.com/scumjr/the-sea-watcher ![Github stars](https://shields.io/github/stars/scumjr/the-sea-watcher?style=social) ![Github forks](https://shields.io/github/forks/scumjr/the-sea-watcher?style=social) ![Github watchers](https://shields.io/github/watchers/scumjr/the-sea-watcher?style=social)
- github.com/zhuyue1314/stoned-UEFI-bootkit ![Github stars](https://shields.io/github/stars/zhuyue1314/stoned-UEFI-bootkit?style=social) ![Github forks](https://shields.io/github/forks/zhuyue1314/stoned-UEFI-bootkit?style=social) ![Github watchers](https://shields.io/github/watchers/zhuyue1314/stoned-UEFI-bootkit?style=social)
- github.com/hackedteam/vector-edk ![Github stars](https://shields.io/github/stars/hackedteam/vector-edk?style=social) ![Github forks](https://shields.io/github/forks/hackedteam/vector-edk?style=social) ![Github watchers](https://shields.io/github/watchers/hackedteam/vector-edk?style=social)
- github.com/Cr4sh/SmmBackdoor ![Github stars](https://shields.io/github/stars/Cr4sh/SmmBackdoor?style=social) ![Github forks](https://shields.io/github/forks/Cr4sh/SmmBackdoor?style=social) ![Github watchers](https://shields.io/github/watchers/Cr4sh/SmmBackdoor?style=social)
- github.com/Cr4sh/PeiBackdoor ![Github stars](https://shields.io/github/stars/Cr4sh/PeiBackdoor?style=social) ![Github forks](https://shields.io/github/forks/Cr4sh/PeiBackdoor?style=social) ![Github watchers](https://shields.io/github/watchers/Cr4sh/PeiBackdoor?style=social)
- github.com/Cr4sh/fwexpl ![Github stars](https://shields.io/github/stars/Cr4sh/fwexpl?style=social) ![Github forks](https://shields.io/github/forks/Cr4sh/fwexpl?style=social) ![Github watchers](https://shields.io/github/watchers/Cr4sh/fwexpl?style=social)

## bootloader

- github.com/apriorit/custom-bootloader ![Github stars](https://shields.io/github/stars/apriorit/custom-bootloader?style=social) ![Github forks](https://shields.io/github/forks/apriorit/custom-bootloader?style=social) ![Github watchers](https://shields.io/github/watchers/apriorit/custom-bootloader?style=social)

## smc

- github.com/marcusbotacin/Self-Modifying-Code ![Github stars](https://shields.io/github/stars/marcusbotacin/Self-Modifying-Code?style=social) ![Github forks](https://shields.io/github/forks/marcusbotacin/Self-Modifying-Code?style=social) ![Github watchers](https://shields.io/github/watchers/marcusbotacin/Self-Modifying-Code?style=social)

## anti debug

- github.com/sharepub/CheckVM-Sandbox ![Github stars](https://shields.io/github/stars/sharepub/CheckVM-Sandbox?style=social) ![Github forks](https://shields.io/github/forks/sharepub/CheckVM-Sandbox?style=social) ![Github watchers](https://shields.io/github/watchers/sharepub/CheckVM-Sandbox?style=social)
- github.com/nihilboy/anti ![Github stars](https://shields.io/github/stars/nihilboy/anti?style=social) ![Github forks](https://shields.io/github/forks/nihilboy/anti?style=social) ![Github watchers](https://shields.io/github/watchers/nihilboy/anti?style=social)
- github.com/atlantis2013/Evasion-Tools ![Github stars](https://shields.io/github/stars/atlantis2013/Evasion-Tools?style=social) ![Github forks](https://shields.io/github/forks/atlantis2013/Evasion-Tools?style=social) ![Github watchers](https://shields.io/github/watchers/atlantis2013/Evasion-Tools?style=social)
- github.com/AlicanAkyol/sems ![Github stars](https://shields.io/github/stars/AlicanAkyol/sems?style=social) ![Github forks](https://shields.io/github/forks/AlicanAkyol/sems?style=social) ![Github watchers](https://shields.io/github/watchers/AlicanAkyol/sems?style=social)
- github.com/strivexjun/XAntiDebug ![Github stars](https://shields.io/github/stars/strivexjun/XAntiDebug?style=social) ![Github forks](https://shields.io/github/forks/strivexjun/XAntiDebug?style=social) ![Github watchers](https://shields.io/github/watchers/strivexjun/XAntiDebug?style=social)
- github.com/marcusbotacin/Anti.Analysis ![Github stars](https://shields.io/github/stars/marcusbotacin/Anti.Analysis?style=social) ![Github forks](https://shields.io/github/forks/marcusbotacin/Anti.Analysis?style=social) ![Github watchers](https://shields.io/github/watchers/marcusbotacin/Anti.Analysis?style=social)
- github.com/LordNoteworthy/al-khaser ![Github stars](https://shields.io/github/stars/LordNoteworthy/al-khaser?style=social) ![Github forks](https://shields.io/github/forks/LordNoteworthy/al-khaser?style=social) ![Github watchers](https://shields.io/github/watchers/LordNoteworthy/al-khaser?style=social)
- github.com/eschweiler/ProReversing ![Github stars](https://shields.io/github/stars/eschweiler/ProReversing?style=social) ![Github forks](https://shields.io/github/forks/eschweiler/ProReversing?style=social) ![Github watchers](https://shields.io/github/watchers/eschweiler/ProReversing?style=social)

## crypters

- github.com/m0n0ph1/FileCrypter ![Github stars](https://shields.io/github/stars/m0n0ph1/FileCrypter?style=social) ![Github forks](https://shields.io/github/forks/m0n0ph1/FileCrypter?style=social) ![Github watchers](https://shields.io/github/watchers/m0n0ph1/FileCrypter?style=social)
- github.com/iGh0st/Crypters ![Github stars](https://shields.io/github/stars/iGh0st/Crypters?style=social) ![Github forks](https://shields.io/github/forks/iGh0st/Crypters?style=social) ![Github watchers](https://shields.io/github/watchers/iGh0st/Crypters?style=social)

## malware

- github.com/Freakboy/CobaltStrike ![Github stars](https://shields.io/github/stars/Freakboy/CobaltStrike?style=social) ![Github forks](https://shields.io/github/forks/Freakboy/CobaltStrike?style=social) ![Github watchers](https://shields.io/github/watchers/Freakboy/CobaltStrike?style=social)
- github.com/vxunderground/Vx-Engines ![Github stars](https://shields.io/github/stars/vxunderground/Vx-Engines?style=social) ![Github forks](https://shields.io/github/forks/vxunderground/Vx-Engines?style=social) ![Github watchers](https://shields.io/github/watchers/vxunderground/Vx-Engines?style=social)
- github.com/rokups/virtual-reality (backdoor) ![Github stars](https://shields.io/github/stars/rokups/virtual-reality?style=social) ![Github forks](https://shields.io/github/forks/rokups/virtual-reality?style=social) ![Github watchers](https://shields.io/github/watchers/rokups/virtual-reality?style=social)
- github.com/InQuest/malware-samples ![Github stars](https://shields.io/github/stars/InQuest/malware-samples?style=social) ![Github forks](https://shields.io/github/forks/InQuest/malware-samples?style=social) ![Github watchers](https://shields.io/github/watchers/InQuest/malware-samples?style=social)
- github.com/mstfknn/malware-sample-library ![Github stars](https://shields.io/github/stars/mstfknn/malware-sample-library?style=social) ![Github forks](https://shields.io/github/forks/mstfknn/malware-sample-library?style=social) ![Github watchers](https://shields.io/github/watchers/mstfknn/malware-sample-library?style=social)
- github.com/Darkabode/possessor ![Github stars](https://shields.io/github/stars/Darkabode/possessor?style=social) ![Github forks](https://shields.io/github/forks/Darkabode/possessor?style=social) ![Github watchers](https://shields.io/github/watchers/Darkabode/possessor?style=social)
- github.com/Darkabode/zerokit ![Github stars](https://shields.io/github/stars/Darkabode/zerokit?style=social) ![Github forks](https://shields.io/github/forks/Darkabode/zerokit?style=social) ![Github watchers](https://shields.io/github/watchers/Darkabode/zerokit?style=social)
- github.com/NYAN-x-CAT/AsyncRAT-C-Sharp (C#) ![Github stars](https://shields.io/github/stars/NYAN-x-CAT/AsyncRAT-C-Sharp?style=social) ![Github forks](https://shields.io/github/forks/NYAN-x-CAT/AsyncRAT-C-Sharp?style=social) ![Github watchers](https://shields.io/github/watchers/NYAN-x-CAT/AsyncRAT-C-Sharp?style=social)
- github.com/zerosum0x0/koadic (JScript RAT) ![Github stars](https://shields.io/github/stars/zerosum0x0/koadic?style=social) ![Github forks](https://shields.io/github/forks/zerosum0x0/koadic?style=social) ![Github watchers](https://shields.io/github/watchers/zerosum0x0/koadic?style=social)
- github.com/malwaredllc/bamf ![Github stars](https://shields.io/github/stars/malwaredllc/bamf?style=social) ![Github forks](https://shields.io/github/forks/malwaredllc/bamf?style=social) ![Github watchers](https://shields.io/github/watchers/malwaredllc/bamf?style=social)
- github.com/malwaredllc/byob (py) ![Github stars](https://shields.io/github/stars/malwaredllc/byob?style=social) ![Github forks](https://shields.io/github/forks/malwaredllc/byob?style=social) ![Github watchers](https://shields.io/github/watchers/malwaredllc/byob?style=social)
- github.com/fereh/tacekit ![Github stars](https://shields.io/github/stars/fereh/tacekit?style=social) ![Github forks](https://shields.io/github/forks/fereh/tacekit?style=social) ![Github watchers](https://shields.io/github/watchers/fereh/tacekit?style=social)
- github.com/eset/malware-ioc ![Github stars](https://shields.io/github/stars/eset/malware-ioc?style=social) ![Github forks](https://shields.io/github/forks/eset/malware-ioc?style=social) ![Github watchers](https://shields.io/github/watchers/eset/malware-ioc?style=social)
- github.com/lianglixin/RemoteControl-X3 ![Github stars](https://shields.io/github/stars/lianglixin/RemoteControl-X3?style=social) ![Github forks](https://shields.io/github/forks/lianglixin/RemoteControl-X3?style=social) ![Github watchers](https://shields.io/github/watchers/lianglixin/RemoteControl-X3?style=social)
- github.com/Souhardya/UBoat (HTTP) ![Github stars](https://shields.io/github/stars/Souhardya/UBoat?style=social) ![Github forks](https://shields.io/github/forks/Souhardya/UBoat?style=social) ![Github watchers](https://shields.io/github/watchers/Souhardya/UBoat?style=social)
- github.com/malwares/Botnet ![Github stars](https://shields.io/github/stars/malwares/Botnet?style=social) ![Github forks](https://shields.io/github/forks/malwares/Botnet?style=social) ![Github watchers](https://shields.io/github/watchers/malwares/Botnet?style=social)
- github.com/RafaelGSS/HyzMall ![Github stars](https://shields.io/github/stars/RafaelGSS/HyzMall?style=social) ![Github forks](https://shields.io/github/forks/RafaelGSS/HyzMall?style=social) ![Github watchers](https://shields.io/github/watchers/RafaelGSS/HyzMall?style=social)
- github.com/DeadNumbers/Pegasus ![Github stars](https://shields.io/github/stars/DeadNumbers/Pegasus?style=social) ![Github forks](https://shields.io/github/forks/DeadNumbers/Pegasus?style=social) ![Github watchers](https://shields.io/github/watchers/DeadNumbers/Pegasus?style=social)
- github.com/mdsecactivebreach/SharpShooter ![Github stars](https://shields.io/github/stars/mdsecactivebreach/SharpShooter?style=social) ![Github forks](https://shields.io/github/forks/mdsecactivebreach/SharpShooter?style=social) ![Github watchers](https://shields.io/github/watchers/mdsecactivebreach/SharpShooter?style=social)
- github.com/mwsrc/XtremeRAT ![Github stars](https://shields.io/github/stars/mwsrc/XtremeRAT?style=social) ![Github forks](https://shields.io/github/forks/mwsrc/XtremeRAT?style=social) ![Github watchers](https://shields.io/github/watchers/mwsrc/XtremeRAT?style=social)
- github.com/mwsrc/Schwarze-Sonne-RAT (delphi) ![Github stars](https://shields.io/github/stars/mwsrc/Schwarze-Sonne-RAT?style=social) ![Github forks](https://shields.io/github/forks/mwsrc/Schwarze-Sonne-RAT?style=social) ![Github watchers](https://shields.io/github/watchers/mwsrc/Schwarze-Sonne-RAT?style=social)
- github.com/Mr-Un1k0d3r/ThunderShell (powershell) ![Github stars](https://shields.io/github/stars/Mr-Un1k0d3r/ThunderShell?style=social) ![Github forks](https://shields.io/github/forks/Mr-Un1k0d3r/ThunderShell?style=social) ![Github watchers](https://shields.io/github/watchers/Mr-Un1k0d3r/ThunderShell?style=social)
- github.com/DimChris0/LoRa ![Github stars](https://shields.io/github/stars/DimChris0/LoRa?style=social) ![Github forks](https://shields.io/github/forks/DimChris0/LoRa?style=social) ![Github watchers](https://shields.io/github/watchers/DimChris0/LoRa?style=social)
- github.com/marcusbotacin/Malware.Multicore ![Github stars](https://shields.io/github/stars/marcusbotacin/Malware.Multicore?style=social) ![Github forks](https://shields.io/github/forks/marcusbotacin/Malware.Multicore?style=social) ![Github watchers](https://shields.io/github/watchers/marcusbotacin/Malware.Multicore?style=social)
- github.com/bxlcity/malware ![Github stars](https://shields.io/github/stars/bxlcity/malware?style=social) ![Github forks](https://shields.io/github/forks/bxlcity/malware?style=social) ![Github watchers](https://shields.io/github/watchers/bxlcity/malware?style=social)
- github.com/grcasanova/SuperVirus ![Github stars](https://shields.io/github/stars/grcasanova/SuperVirus?style=social) ![Github forks](https://shields.io/github/forks/grcasanova/SuperVirus?style=social) ![Github watchers](https://shields.io/github/watchers/grcasanova/SuperVirus?style=social)
- github.com/hackedteam/core-win32 ![Github stars](https://shields.io/github/stars/hackedteam/core-win32?style=social) ![Github forks](https://shields.io/github/forks/hackedteam/core-win32?style=social) ![Github watchers](https://shields.io/github/watchers/hackedteam/core-win32?style=social)
- github.com/hackedteam/scout-win ![Github stars](https://shields.io/github/stars/hackedteam/scout-win?style=social) ![Github forks](https://shields.io/github/forks/hackedteam/scout-win?style=social) ![Github watchers](https://shields.io/github/watchers/hackedteam/scout-win?style=social)
- github.com/hackedteam/vector-dropper ![Github stars](https://shields.io/github/stars/hackedteam/vector-dropper?style=social) ![Github forks](https://shields.io/github/forks/hackedteam/vector-dropper?style=social) ![Github watchers](https://shields.io/github/watchers/hackedteam/vector-dropper?style=social)

## EternalBlue && Doublepulsar && Mine

- github.com/xmrig/xmrig ![Github stars](https://shields.io/github/stars/xmrig/xmrig?style=social) ![Github forks](https://shields.io/github/forks/xmrig/xmrig?style=social) ![Github watchers](https://shields.io/github/watchers/xmrig/xmrig?style=social)
- github.com/TolgaSEZER/EternalPulse ![Github stars](https://shields.io/github/stars/TolgaSEZER/EternalPulse?style=social) ![Github forks](https://shields.io/github/forks/TolgaSEZER/EternalPulse?style=social) ![Github watchers](https://shields.io/github/watchers/TolgaSEZER/EternalPulse?style=social)

## shellcode analysis

- github.com/OALabs/BlobRunner ![Github stars](https://shields.io/github/stars/OALabs/BlobRunner?style=social) ![Github forks](https://shields.io/github/forks/OALabs/BlobRunner?style=social) ![Github watchers](https://shields.io/github/watchers/OALabs/BlobRunner?style=social)

## malware analysis

- github.com/huoji120/DuckMemoryScan ![Github stars](https://shields.io/github/stars/huoji120/DuckMemoryScan?style=social) ![Github forks](https://shields.io/github/forks/huoji120/DuckMemoryScan?style=social) ![Github watchers](https://shields.io/github/watchers/huoji120/DuckMemoryScan?style=social)
- github.com/JPCERTCC/EmoCheck ![Github stars](https://shields.io/github/stars/JPCERTCC/EmoCheck?style=social) ![Github forks](https://shields.io/github/forks/JPCERTCC/EmoCheck?style=social) ![Github watchers](https://shields.io/github/watchers/JPCERTCC/EmoCheck?style=social)
- github.com/G4rb3n/Malware-Killer ![Github stars](https://shields.io/github/stars/G4rb3n/Malware-Killer?style=social) ![Github forks](https://shields.io/github/forks/G4rb3n/Malware-Killer?style=social) ![Github watchers](https://shields.io/github/watchers/G4rb3n/Malware-Killer?style=social)
- github.com/G4rb3n/Malware-Picture ![Github stars](https://shields.io/github/stars/G4rb3n/Malware-Picture?style=social) ![Github forks](https://shields.io/github/forks/G4rb3n/Malware-Picture?style=social) ![Github watchers](https://shields.io/github/watchers/G4rb3n/Malware-Picture?style=social)
- github.com/a232319779/mmdt ![Github stars](https://shields.io/github/stars/a232319779/mmdt?style=social) ![Github forks](https://shields.io/github/forks/a232319779/mmdt?style=social) ![Github watchers](https://shields.io/github/watchers/a232319779/mmdt?style=social)
- github.com/Formyown/Alesense-Antivirus (nice demo) ![Github stars](https://shields.io/github/stars/Formyown/Alesense-Antivirus?style=social) ![Github forks](https://shields.io/github/forks/Formyown/Alesense-Antivirus?style=social) ![Github watchers](https://shields.io/github/watchers/Formyown/Alesense-Antivirus?style=social)
- github.com/ctxis/capemon (Config And Payload Extraction) ![Github stars](https://shields.io/github/stars/ctxis/capemon?style=social) ![Github forks](https://shields.io/github/forks/ctxis/capemon?style=social) ![Github watchers](https://shields.io/github/watchers/ctxis/capemon?style=social)
- github.com/tdevuser/MalwFinder ![Github stars](https://shields.io/github/stars/tdevuser/MalwFinder?style=social) ![Github forks](https://shields.io/github/forks/tdevuser/MalwFinder?style=social) ![Github watchers](https://shields.io/github/watchers/tdevuser/MalwFinder?style=social)
- github.com/MalwareCantFly/Vba2Graph ![Github stars](https://shields.io/github/stars/MalwareCantFly/Vba2Graph?style=social) ![Github forks](https://shields.io/github/forks/MalwareCantFly/Vba2Graph?style=social) ![Github watchers](https://shields.io/github/watchers/MalwareCantFly/Vba2Graph?style=social)
- github.com/unexpectedBy/Automated-Malware-Analysis-List ![Github stars](https://shields.io/github/stars/unexpectedBy/Automated-Malware-Analysis-List?style=social) ![Github forks](https://shields.io/github/forks/unexpectedBy/Automated-Malware-Analysis-List?style=social) ![Github watchers](https://shields.io/github/watchers/unexpectedBy/Automated-Malware-Analysis-List?style=social)
- github.com/wchen-r7/amsiscanner (Microsoft's Antimalware Scan Interface) ![Github stars](https://shields.io/github/stars/wchen-r7/amsiscanner?style=social) ![Github forks](https://shields.io/github/forks/wchen-r7/amsiscanner?style=social) ![Github watchers](https://shields.io/github/watchers/wchen-r7/amsiscanner?style=social)
- github.com/ctxis/capemon ![Github stars](https://shields.io/github/stars/ctxis/capemon?style=social) ![Github forks](https://shields.io/github/forks/ctxis/capemon?style=social) ![Github watchers](https://shields.io/github/watchers/ctxis/capemon?style=social)
- github.com/kevthehermit/RATDecoders ![Github stars](https://shields.io/github/stars/kevthehermit/RATDecoders?style=social) ![Github forks](https://shields.io/github/forks/kevthehermit/RATDecoders?style=social) ![Github watchers](https://shields.io/github/watchers/kevthehermit/RATDecoders?style=social)
- github.com/marcusbotacin/Malware.Variants ![Github stars](https://shields.io/github/stars/marcusbotacin/Malware.Variants?style=social) ![Github forks](https://shields.io/github/forks/marcusbotacin/Malware.Variants?style=social) ![Github watchers](https://shields.io/github/watchers/marcusbotacin/Malware.Variants?style=social)
- github.com/marcusbotacin/Hardware-Assisted-AV ![Github stars](https://shields.io/github/stars/marcusbotacin/Hardware-Assisted-AV?style=social) ![Github forks](https://shields.io/github/forks/marcusbotacin/Hardware-Assisted-AV?style=social) ![Github watchers](https://shields.io/github/watchers/marcusbotacin/Hardware-Assisted-AV?style=social)
- github.com/gentilkiwi/spectre_meltdown ![Github stars](https://shields.io/github/stars/gentilkiwi/spectre_meltdown?style=social) ![Github forks](https://shields.io/github/forks/gentilkiwi/spectre_meltdown?style=social) ![Github watchers](https://shields.io/github/watchers/gentilkiwi/spectre_meltdown?style=social)
- github.com/gentilkiwi/wanadecrypt ![Github stars](https://shields.io/github/stars/gentilkiwi/wanadecrypt?style=social) ![Github forks](https://shields.io/github/forks/gentilkiwi/wanadecrypt?style=social) ![Github watchers](https://shields.io/github/watchers/gentilkiwi/wanadecrypt?style=social)
- github.com/bloomer1016
- github.com/CHEF-KOCH/malware-research ![Github stars](https://shields.io/github/stars/CHEF-KOCH/malware-research?style=social) ![Github forks](https://shields.io/github/forks/CHEF-KOCH/malware-research?style=social) ![Github watchers](https://shields.io/github/watchers/CHEF-KOCH/malware-research?style=social)
- github.com/gentilkiwi/wanakiwi ![Github stars](https://shields.io/github/stars/gentilkiwi/wanakiwi?style=social) ![Github forks](https://shields.io/github/forks/gentilkiwi/wanakiwi?style=social) ![Github watchers](https://shields.io/github/watchers/gentilkiwi/wanakiwi?style=social)

## av evasion

- github.com/sv3nbeast/ImgLoaderShellCode ![Github stars](https://shields.io/github/stars/sv3nbeast/ImgLoaderShellCode?style=social) ![Github forks](https://shields.io/github/forks/sv3nbeast/ImgLoaderShellCode?style=social) ![Github watchers](https://shields.io/github/watchers/sv3nbeast/ImgLoaderShellCode?style=social)
- github.com/ReddyyZ/GhostShell ![Github stars](https://shields.io/github/stars/ReddyyZ/GhostShell?style=social) ![Github forks](https://shields.io/github/forks/ReddyyZ/GhostShell?style=social) ![Github watchers](https://shields.io/github/watchers/ReddyyZ/GhostShell?style=social)
- github.com/nccgroup/Winpayloads ![Github stars](https://shields.io/github/stars/nccgroup/Winpayloads?style=social) ![Github forks](https://shields.io/github/forks/nccgroup/Winpayloads?style=social) ![Github watchers](https://shields.io/github/watchers/nccgroup/Winpayloads?style=social)
- github.com/TideSec/BypassAntiVirus ![Github stars](https://shields.io/github/stars/TideSec/BypassAntiVirus?style=social) ![Github forks](https://shields.io/github/forks/TideSec/BypassAntiVirus?style=social) ![Github watchers](https://shields.io/github/watchers/TideSec/BypassAntiVirus?style=social)
- github.com/jthuraisamy/SysWhispers ![Github stars](https://shields.io/github/stars/jthuraisamy/SysWhispers?style=social) ![Github forks](https://shields.io/github/forks/jthuraisamy/SysWhispers?style=social) ![Github watchers](https://shields.io/github/watchers/jthuraisamy/SysWhispers?style=social)
- github.com/huoji120/Antivirus_R3_bypass_demo ![Github stars](https://shields.io/github/stars/huoji120/Antivirus_R3_bypass_demo?style=social) ![Github forks](https://shields.io/github/forks/huoji120/Antivirus_R3_bypass_demo?style=social) ![Github watchers](https://shields.io/github/watchers/huoji120/Antivirus_R3_bypass_demo?style=social)
- github.com/paranoidninja/CarbonCopy ![Github stars](https://shields.io/github/stars/paranoidninja/CarbonCopy?style=social) ![Github forks](https://shields.io/github/forks/paranoidninja/CarbonCopy?style=social) ![Github watchers](https://shields.io/github/watchers/paranoidninja/CarbonCopy?style=social)

## arktools

- github.com/D4stiny/PeaceMaker  (detects advanced techniques used by malware) ![Github stars](https://shields.io/github/stars/D4stiny/PeaceMaker?style=social) ![Github forks](https://shields.io/github/forks/D4stiny/PeaceMaker?style=social) ![Github watchers](https://shields.io/github/watchers/D4stiny/PeaceMaker?style=social)
- github.com/MHaggis/sysmon-dfir (sysmon) ![Github stars](https://shields.io/github/stars/MHaggis/sysmon-dfir?style=social) ![Github forks](https://shields.io/github/forks/MHaggis/sysmon-dfir?style=social) ![Github watchers](https://shields.io/github/watchers/MHaggis/sysmon-dfir?style=social)
- github.com/antiwar3/py ![Github stars](https://shields.io/github/stars/antiwar3/py?style=social) ![Github forks](https://shields.io/github/forks/antiwar3/py?style=social) ![Github watchers](https://shields.io/github/watchers/antiwar3/py?style=social)
- github.com/weixu8/pcmonitor (kpolarssl) ![Github stars](https://shields.io/github/stars/weixu8/pcmonitor?style=social) ![Github forks](https://shields.io/github/forks/weixu8/pcmonitor?style=social) ![Github watchers](https://shields.io/github/watchers/weixu8/pcmonitor?style=social)
- github.com/mohuihui/antispy ![Github stars](https://shields.io/github/stars/mohuihui/antispy?style=social) ![Github forks](https://shields.io/github/forks/mohuihui/antispy?style=social) ![Github watchers](https://shields.io/github/watchers/mohuihui/antispy?style=social)
- github.com/DavidXanatos/TaskExplorer ![Github stars](https://shields.io/github/stars/DavidXanatos/TaskExplorer?style=social) ![Github forks](https://shields.io/github/forks/DavidXanatos/TaskExplorer?style=social) ![Github watchers](https://shields.io/github/watchers/DavidXanatos/TaskExplorer?style=social)
- github.com/BlackINT3/OpenArk ![Github stars](https://shields.io/github/stars/BlackINT3/OpenArk?style=social) ![Github forks](https://shields.io/github/forks/BlackINT3/OpenArk?style=social) ![Github watchers](https://shields.io/github/watchers/BlackINT3/OpenArk?style=social)
- github.com/basketwill/Sysmon_reverse ![Github stars](https://shields.io/github/stars/basketwill/Sysmon_reverse?style=social) ![Github forks](https://shields.io/github/forks/basketwill/Sysmon_reverse?style=social) ![Github watchers](https://shields.io/github/watchers/basketwill/Sysmon_reverse?style=social)
- github.com/ZhuHuiBeiShaDiao/KernelHooksDetection_x64 ![Github stars](https://shields.io/github/stars/ZhuHuiBeiShaDiao/KernelHooksDetection_x64?style=social) ![Github forks](https://shields.io/github/forks/ZhuHuiBeiShaDiao/KernelHooksDetection_x64?style=social) ![Github watchers](https://shields.io/github/watchers/ZhuHuiBeiShaDiao/KernelHooksDetection_x64?style=social)
- github.com/AxtMueller/Windows-Kernel-Explorer ![Github stars](https://shields.io/github/stars/AxtMueller/Windows-Kernel-Explorer?style=social) ![Github forks](https://shields.io/github/forks/AxtMueller/Windows-Kernel-Explorer?style=social) ![Github watchers](https://shields.io/github/watchers/AxtMueller/Windows-Kernel-Explorer?style=social)
- github.com/hedgeh/SEWindows (doc:hedgeh.github.io/startup.html) ![Github stars](https://shields.io/github/stars/hedgeh/SEWindows?style=social) ![Github forks](https://shields.io/github/forks/hedgeh/SEWindows?style=social) ![Github watchers](https://shields.io/github/watchers/hedgeh/SEWindows?style=social)
- github.com/glmcdona/MALM ![Github stars](https://shields.io/github/stars/glmcdona/MALM?style=social) ![Github forks](https://shields.io/github/forks/glmcdona/MALM?style=social) ![Github watchers](https://shields.io/github/watchers/glmcdona/MALM?style=social)
- github.com/ahmad-siavashi/Ana-Process-Explorer ![Github stars](https://shields.io/github/stars/ahmad-siavashi/Ana-Process-Explorer?style=social) ![Github forks](https://shields.io/github/forks/ahmad-siavashi/Ana-Process-Explorer?style=social) ![Github watchers](https://shields.io/github/watchers/ahmad-siavashi/Ana-Process-Explorer?style=social)
- github.com/alex9191/KernelModeMonitor ![Github stars](https://shields.io/github/stars/alex9191/KernelModeMonitor?style=social) ![Github forks](https://shields.io/github/forks/alex9191/KernelModeMonitor?style=social) ![Github watchers](https://shields.io/github/watchers/alex9191/KernelModeMonitor?style=social)
- github.com/marcosd4h/memhunter ![Github stars](https://shields.io/github/stars/marcosd4h/memhunter?style=social) ![Github forks](https://shields.io/github/forks/marcosd4h/memhunter?style=social) ![Github watchers](https://shields.io/github/watchers/marcosd4h/memhunter?style=social)
- github.com/gleeda/memtriage ![Github stars](https://shields.io/github/stars/gleeda/memtriage?style=social) ![Github forks](https://shields.io/github/forks/gleeda/memtriage?style=social) ![Github watchers](https://shields.io/github/watchers/gleeda/memtriage?style=social)
- github.com/KernelMode/Process_Dop ![Github stars](https://shields.io/github/stars/KernelMode/Process_Dop?style=social) ![Github forks](https://shields.io/github/forks/KernelMode/Process_Dop?style=social) ![Github watchers](https://shields.io/github/watchers/KernelMode/Process_Dop?style=social)
- github.com/hm200958/kmdf--analyse ![Github stars](https://shields.io/github/stars/hm200958/kmdf--analyse?style=social) ![Github forks](https://shields.io/github/forks/hm200958/kmdf--analyse?style=social) ![Github watchers](https://shields.io/github/watchers/hm200958/kmdf--analyse?style=social)
- github.com/AzureGreen/WinNT-Learning ![Github stars](https://shields.io/github/stars/AzureGreen/WinNT-Learning?style=social) ![Github forks](https://shields.io/github/forks/AzureGreen/WinNT-Learning?style=social) ![Github watchers](https://shields.io/github/watchers/AzureGreen/WinNT-Learning?style=social)
- github.com/marcusbotacin/BranchMonitoringProject ![Github stars](https://shields.io/github/stars/marcusbotacin/BranchMonitoringProject?style=social) ![Github forks](https://shields.io/github/forks/marcusbotacin/BranchMonitoringProject?style=social) ![Github watchers](https://shields.io/github/watchers/marcusbotacin/BranchMonitoringProject?style=social)
- github.com/AzureGreen/ArkProtect ![Github stars](https://shields.io/github/stars/AzureGreen/ArkProtect?style=social) ![Github forks](https://shields.io/github/forks/AzureGreen/ArkProtect?style=social) ![Github watchers](https://shields.io/github/watchers/AzureGreen/ArkProtect?style=social)
- github.com/AzureGreen/ArkToolDrv ![Github stars](https://shields.io/github/stars/AzureGreen/ArkToolDrv?style=social) ![Github forks](https://shields.io/github/forks/AzureGreen/ArkToolDrv?style=social) ![Github watchers](https://shields.io/github/watchers/AzureGreen/ArkToolDrv?style=social)
- github.com/HollyDi/PCAssistant ![Github stars](https://shields.io/github/stars/HollyDi/PCAssistant?style=social) ![Github forks](https://shields.io/github/forks/HollyDi/PCAssistant?style=social) ![Github watchers](https://shields.io/github/watchers/HollyDi/PCAssistant?style=social)
- github.com/ChengChengCC/Ark-tools ![Github stars](https://shields.io/github/stars/ChengChengCC/Ark-tools?style=social) ![Github forks](https://shields.io/github/forks/ChengChengCC/Ark-tools?style=social) ![Github watchers](https://shields.io/github/watchers/ChengChengCC/Ark-tools?style=social)
- github.com/swatkat/arkitlib ![Github stars](https://shields.io/github/stars/swatkat/arkitlib?style=social) ![Github forks](https://shields.io/github/forks/swatkat/arkitlib?style=social) ![Github watchers](https://shields.io/github/watchers/swatkat/arkitlib?style=social)
- github.com/swwwolf/wdbgark ![Github stars](https://shields.io/github/stars/swwwolf/wdbgark?style=social) ![Github forks](https://shields.io/github/forks/swwwolf/wdbgark?style=social) ![Github watchers](https://shields.io/github/watchers/swwwolf/wdbgark?style=social)
- github.com/zibility/Anti-Rootkits ![Github stars](https://shields.io/github/stars/zibility/Anti-Rootkits?style=social) ![Github forks](https://shields.io/github/forks/zibility/Anti-Rootkits?style=social) ![Github watchers](https://shields.io/github/watchers/zibility/Anti-Rootkits?style=social)
- github.com/SLAUC91/AntiCheat ![Github stars](https://shields.io/github/stars/SLAUC91/AntiCheat?style=social) ![Github forks](https://shields.io/github/forks/SLAUC91/AntiCheat?style=social) ![Github watchers](https://shields.io/github/watchers/SLAUC91/AntiCheat?style=social)
- github.com/sincoder/A-Protect ![Github stars](https://shields.io/github/stars/sincoder/A-Protect?style=social) ![Github forks](https://shields.io/github/forks/sincoder/A-Protect?style=social) ![Github watchers](https://shields.io/github/watchers/sincoder/A-Protect?style=social)
- github.com/apriorit/antirootkit-anti-splicer ![Github stars](https://shields.io/github/stars/apriorit/antirootkit-anti-splicer?style=social) ![Github forks](https://shields.io/github/forks/apriorit/antirootkit-anti-splicer?style=social) ![Github watchers](https://shields.io/github/watchers/apriorit/antirootkit-anti-splicer?style=social)
- github.com/kedebug/ScDetective ![Github stars](https://shields.io/github/stars/kedebug/ScDetective?style=social) ![Github forks](https://shields.io/github/forks/kedebug/ScDetective?style=social) ![Github watchers](https://shields.io/github/watchers/kedebug/ScDetective?style=social)
- github.com/PKRoma/ProcessHacker ![Github stars](https://shields.io/github/stars/PKRoma/ProcessHacker?style=social) ![Github forks](https://shields.io/github/forks/PKRoma/ProcessHacker?style=social) ![Github watchers](https://shields.io/github/watchers/PKRoma/ProcessHacker?style=social)
- github.com/AndreyBazhan/DbgExt ![Github stars](https://shields.io/github/stars/AndreyBazhan/DbgExt?style=social) ![Github forks](https://shields.io/github/forks/AndreyBazhan/DbgExt?style=social) ![Github watchers](https://shields.io/github/watchers/AndreyBazhan/DbgExt?style=social)
- github.com/comaeio/SwishDbgExt ![Github stars](https://shields.io/github/stars/comaeio/SwishDbgExt?style=social) ![Github forks](https://shields.io/github/forks/comaeio/SwishDbgExt?style=social) ![Github watchers](https://shields.io/github/watchers/comaeio/SwishDbgExt?style=social)
- github.com/ExpLife/atomic-red-team ![Github stars](https://shields.io/github/stars/ExpLife/atomic-red-team?style=social) ![Github forks](https://shields.io/github/forks/ExpLife/atomic-red-team?style=social) ![Github watchers](https://shields.io/github/watchers/ExpLife/atomic-red-team?style=social)
- github.com/shenghe/pcmanager ![Github stars](https://shields.io/github/stars/shenghe/pcmanager?style=social) ![Github forks](https://shields.io/github/forks/shenghe/pcmanager?style=social) ![Github watchers](https://shields.io/github/watchers/shenghe/pcmanager?style=social)
- github.com/lj1987new/guardlite ![Github stars](https://shields.io/github/stars/lj1987new/guardlite?style=social) ![Github forks](https://shields.io/github/forks/lj1987new/guardlite?style=social) ![Github watchers](https://shields.io/github/watchers/lj1987new/guardlite?style=social)
- github.com/hackshields/antivirus/ ![Github stars](https://shields.io/github/stars/hackshields/antivirus?style=social) ![Github forks](https://shields.io/github/forks/hackshields/antivirus?style=social) ![Github watchers](https://shields.io/github/watchers/hackshields/antivirus?style=social)
- github.com/AntiRootkit/BDArkit ![Github stars](https://shields.io/github/stars/AntiRootkit/BDArkit?style=social) ![Github forks](https://shields.io/github/forks/AntiRootkit/BDArkit?style=social) ![Github watchers](https://shields.io/github/watchers/AntiRootkit/BDArkit?style=social)

## EDR

- github.com/jthuraisamy/TelemetrySourcerer ![Github stars](https://shields.io/github/stars/jthuraisamy/TelemetrySourcerer?style=social) ![Github forks](https://shields.io/github/forks/jthuraisamy/TelemetrySourcerer?style=social) ![Github watchers](https://shields.io/github/watchers/jthuraisamy/TelemetrySourcerer?style=social)
- github.com/ION28/BLUESPAWN ![Github stars](https://shields.io/github/stars/ION28/BLUESPAWN?style=social) ![Github forks](https://shields.io/github/forks/ION28/BLUESPAWN?style=social) ![Github watchers](https://shields.io/github/watchers/ION28/BLUESPAWN?style=social)
- github.com/ComodoSecurity/openedr ![Github stars](https://shields.io/github/stars/ComodoSecurity/openedr?style=social) ![Github forks](https://shields.io/github/forks/ComodoSecurity/openedr?style=social) ![Github watchers](https://shields.io/github/watchers/ComodoSecurity/openedr?style=social)

## bypass patchguard

- github.com/zhuhuibeishadiao/PatchGuardResearch ![Github stars](https://shields.io/github/stars/zhuhuibeishadiao/PatchGuardResearch?style=social) ![Github forks](https://shields.io/github/forks/zhuhuibeishadiao/PatchGuardResearch?style=social) ![Github watchers](https://shields.io/github/watchers/zhuhuibeishadiao/PatchGuardResearch?style=social)
- github.com/can1357/ByePg ![Github stars](https://shields.io/github/stars/can1357/ByePg?style=social) ![Github forks](https://shields.io/github/forks/can1357/ByePg?style=social) ![Github watchers](https://shields.io/github/watchers/can1357/ByePg?style=social)
- github.com/zzhouhe/PG1903 ![Github stars](https://shields.io/github/stars/zzhouhe/PG1903?style=social) ![Github forks](https://shields.io/github/forks/zzhouhe/PG1903?style=social) ![Github watchers](https://shields.io/github/watchers/zzhouhe/PG1903?style=social)
- github.com/9176324/Shark ![Github stars](https://shields.io/github/stars/9176324/Shark?style=social) ![Github forks](https://shields.io/github/forks/9176324/Shark?style=social) ![Github watchers](https://shields.io/github/watchers/9176324/Shark?style=social)
- github.com/hfiref0x/UPGDSED ![Github stars](https://shields.io/github/stars/hfiref0x/UPGDSED?style=social) ![Github forks](https://shields.io/github/forks/hfiref0x/UPGDSED?style=social) ![Github watchers](https://shields.io/github/watchers/hfiref0x/UPGDSED?style=social)
- github.com/tandasat/PgResarch ![Github stars](https://shields.io/github/stars/tandasat/PgResarch?style=social) ![Github forks](https://shields.io/github/forks/tandasat/PgResarch?style=social) ![Github watchers](https://shields.io/github/watchers/tandasat/PgResarch?style=social)
- github.com/killvxk/DisableWin10PatchguardPoc ![Github stars](https://shields.io/github/stars/killvxk/DisableWin10PatchguardPoc?style=social) ![Github forks](https://shields.io/github/forks/killvxk/DisableWin10PatchguardPoc?style=social) ![Github watchers](https://shields.io/github/watchers/killvxk/DisableWin10PatchguardPoc?style=social)
- github.com/tandasat/findpg ![Github stars](https://shields.io/github/stars/tandasat/findpg?style=social) ![Github forks](https://shields.io/github/forks/tandasat/findpg?style=social) ![Github watchers](https://shields.io/github/watchers/tandasat/findpg?style=social)
- github.com/zer0mem/HowToBoostPatchGuard ![Github stars](https://shields.io/github/stars/zer0mem/HowToBoostPatchGuard?style=social) ![Github forks](https://shields.io/github/forks/zer0mem/HowToBoostPatchGuard?style=social) ![Github watchers](https://shields.io/github/watchers/zer0mem/HowToBoostPatchGuard?style=social)
- bbs.pediy.com/thread-214582.htm

## bypass dse

- github.com/alxbrn/gdrv-loader ![Github stars](https://shields.io/github/stars/alxbrn/gdrv-loader?style=social) ![Github forks](https://shields.io/github/forks/alxbrn/gdrv-loader?style=social) ![Github watchers](https://shields.io/github/watchers/alxbrn/gdrv-loader?style=social)
- github.com/Mattiwatti/EfiGuard ![Github stars](https://shields.io/github/stars/Mattiwatti/EfiGuard?style=social) ![Github forks](https://shields.io/github/forks/Mattiwatti/EfiGuard?style=social) ![Github watchers](https://shields.io/github/watchers/Mattiwatti/EfiGuard?style=social)
- github.com/hfiref0x/TDL ![Github stars](https://shields.io/github/stars/hfiref0x/TDL?style=social) ![Github forks](https://shields.io/github/forks/hfiref0x/TDL?style=social) ![Github watchers](https://shields.io/github/watchers/hfiref0x/TDL?style=social)
- github.com/hfiref0x/DSEFix ![Github stars](https://shields.io/github/stars/hfiref0x/DSEFix?style=social) ![Github forks](https://shields.io/github/forks/hfiref0x/DSEFix?style=social) ![Github watchers](https://shields.io/github/watchers/hfiref0x/DSEFix?style=social)

## HackSysExtremeVulnerableDriver

- github.com/redogwu/windows_kernel_exploit ![Github stars](https://shields.io/github/stars/redogwu/windows_kernel_exploit?style=social) ![Github forks](https://shields.io/github/forks/redogwu/windows_kernel_exploit?style=social) ![Github watchers](https://shields.io/github/watchers/redogwu/windows_kernel_exploit?style=social)
- github.com/mgeeky/HEVD_Kernel_Exploit ![Github stars](https://shields.io/github/stars/mgeeky/HEVD_Kernel_Exploit?style=social) ![Github forks](https://shields.io/github/forks/mgeeky/HEVD_Kernel_Exploit?style=social) ![Github watchers](https://shields.io/github/watchers/mgeeky/HEVD_Kernel_Exploit?style=social)
- www.fuzzysecurity.com/tutorials.html
- rootkits.xyz/blog/
- github.com/hacksysteam/HackSysExtremeVulnerableDriver ![Github stars](https://shields.io/github/stars/hacksysteam/HackSysExtremeVulnerableDriver?style=social) ![Github forks](https://shields.io/github/forks/hacksysteam/HackSysExtremeVulnerableDriver?style=social) ![Github watchers](https://shields.io/github/watchers/hacksysteam/HackSysExtremeVulnerableDriver?style=social)
- github.com/k0keoyo/HEVD-Double-Free-PoC ![Github stars](https://shields.io/github/stars/k0keoyo/HEVD-Double-Free-PoC?style=social) ![Github forks](https://shields.io/github/forks/k0keoyo/HEVD-Double-Free-PoC?style=social) ![Github watchers](https://shields.io/github/watchers/k0keoyo/HEVD-Double-Free-PoC?style=social)
- github.com/k0keoyo/HEVD-Arbitrary-Overwrite-Exploit-Win10-rs3 ![Github stars](https://shields.io/github/stars/k0keoyo/HEVD-Arbitrary-Overwrite-Exploit-Win10-rs3?style=social) ![Github forks](https://shields.io/github/forks/k0keoyo/HEVD-Arbitrary-Overwrite-Exploit-Win10-rs3?style=social) ![Github watchers](https://shields.io/github/watchers/k0keoyo/HEVD-Arbitrary-Overwrite-Exploit-Win10-rs3?style=social)
- github.com/tekwizz123/HEVD-Exploit-Solutions ![Github stars](https://shields.io/github/stars/tekwizz123/HEVD-Exploit-Solutions?style=social) ![Github forks](https://shields.io/github/forks/tekwizz123/HEVD-Exploit-Solutions?style=social) ![Github watchers](https://shields.io/github/watchers/tekwizz123/HEVD-Exploit-Solutions?style=social)
- github.com/k0keoyo/try_exploit ![Github stars](https://shields.io/github/stars/k0keoyo/try_exploit?style=social) ![Github forks](https://shields.io/github/forks/k0keoyo/try_exploit?style=social) ![Github watchers](https://shields.io/github/watchers/k0keoyo/try_exploit?style=social)
- github.com/Cn33liz/HSEVD-VariousExploits ![Github stars](https://shields.io/github/stars/Cn33liz/HSEVD-VariousExploits?style=social) ![Github forks](https://shields.io/github/forks/Cn33liz/HSEVD-VariousExploits?style=social) ![Github watchers](https://shields.io/github/watchers/Cn33liz/HSEVD-VariousExploits?style=social)
- github.com/Cn33liz/HSEVD-StackOverflow ![Github stars](https://shields.io/github/stars/Cn33liz/HSEVD-StackOverflow?style=social) ![Github forks](https://shields.io/github/forks/Cn33liz/HSEVD-StackOverflow?style=social) ![Github watchers](https://shields.io/github/watchers/Cn33liz/HSEVD-StackOverflow?style=social)
- github.com/Cn33liz/HSEVD-StackOverflowX64 ![Github stars](https://shields.io/github/stars/Cn33liz/HSEVD-StackOverflowX64?style=social) ![Github forks](https://shields.io/github/forks/Cn33liz/HSEVD-StackOverflowX64?style=social) ![Github watchers](https://shields.io/github/watchers/Cn33liz/HSEVD-StackOverflowX64?style=social)
- github.com/Cn33liz/HSEVD-StackCookieBypass ![Github stars](https://shields.io/github/stars/Cn33liz/HSEVD-StackCookieBypass?style=social) ![Github forks](https://shields.io/github/forks/Cn33liz/HSEVD-StackCookieBypass?style=social) ![Github watchers](https://shields.io/github/watchers/Cn33liz/HSEVD-StackCookieBypass?style=social)
- github.com/Cn33liz/HSEVD-ArbitraryOverwriteGDI ![Github stars](https://shields.io/github/stars/Cn33liz/HSEVD-ArbitraryOverwriteGDI?style=social) ![Github forks](https://shields.io/github/forks/Cn33liz/HSEVD-ArbitraryOverwriteGDI?style=social) ![Github watchers](https://shields.io/github/watchers/Cn33liz/HSEVD-ArbitraryOverwriteGDI?style=social)
- github.com/Cn33liz/HSEVD-StackOverflowGDI ![Github stars](https://shields.io/github/stars/Cn33liz/HSEVD-StackOverflowGDI?style=social) ![Github forks](https://shields.io/github/forks/Cn33liz/HSEVD-StackOverflowGDI?style=social) ![Github watchers](https://shields.io/github/watchers/Cn33liz/HSEVD-StackOverflowGDI?style=social)
- github.com/Cn33liz/HSEVD-ArbitraryOverwriteLowIL ![Github stars](https://shields.io/github/stars/Cn33liz/HSEVD-ArbitraryOverwriteLowIL?style=social) ![Github forks](https://shields.io/github/forks/Cn33liz/HSEVD-ArbitraryOverwriteLowIL?style=social) ![Github watchers](https://shields.io/github/watchers/Cn33liz/HSEVD-ArbitraryOverwriteLowIL?style=social)
- github.com/Cn33liz/HSEVD-ArbitraryOverwrite ![Github stars](https://shields.io/github/stars/Cn33liz/HSEVD-ArbitraryOverwrite?style=social) ![Github forks](https://shields.io/github/forks/Cn33liz/HSEVD-ArbitraryOverwrite?style=social) ![Github watchers](https://shields.io/github/watchers/Cn33liz/HSEVD-ArbitraryOverwrite?style=social)
- github.com/akayn/demos ![Github stars](https://shields.io/github/stars/akayn/demos?style=social) ![Github forks](https://shields.io/github/forks/akayn/demos?style=social) ![Github watchers](https://shields.io/github/watchers/akayn/demos?style=social)

## windows exploits

- github.com/peleghd/Windows-10-Exploitation ![Github stars](https://shields.io/github/stars/peleghd/Windows-10-Exploitation?style=social) ![Github forks](https://shields.io/github/forks/peleghd/Windows-10-Exploitation?style=social) ![Github watchers](https://shields.io/github/watchers/peleghd/Windows-10-Exploitation?style=social)
- github.com/NAXG/cve_2019_0708_bluekeep_rce (RDP) ![Github stars](https://shields.io/github/stars/NAXG/cve_2019_0708_bluekeep_rce?style=social) ![Github forks](https://shields.io/github/forks/NAXG/cve_2019_0708_bluekeep_rce?style=social) ![Github watchers](https://shields.io/github/watchers/NAXG/cve_2019_0708_bluekeep_rce?style=social)
- github.com/wchen-r7/VulnCases (cases) ![Github stars](https://shields.io/github/stars/wchen-r7/VulnCases?style=social) ![Github forks](https://shields.io/github/forks/wchen-r7/VulnCases?style=social) ![Github watchers](https://shields.io/github/watchers/wchen-r7/VulnCases?style=social)
- github.com/rockmelodies/CVE-2019-0708-Exploit (RDP) ![Github stars](https://shields.io/github/stars/rockmelodies/CVE-2019-0708-Exploit?style=social) ![Github forks](https://shields.io/github/forks/rockmelodies/CVE-2019-0708-Exploit?style=social) ![Github watchers](https://shields.io/github/watchers/rockmelodies/CVE-2019-0708-Exploit?style=social)
- github.com/admintony/svnExploit ![Github stars](https://shields.io/github/stars/admintony/svnExploit?style=social) ![Github forks](https://shields.io/github/forks/admintony/svnExploit?style=social) ![Github watchers](https://shields.io/github/watchers/admintony/svnExploit?style=social)
- github.com/smgorelik/Windows-RCE-exploits ![Github stars](https://shields.io/github/stars/smgorelik/Windows-RCE-exploits?style=social) ![Github forks](https://shields.io/github/forks/smgorelik/Windows-RCE-exploits?style=social) ![Github watchers](https://shields.io/github/watchers/smgorelik/Windows-RCE-exploits?style=social)
- github.com/WindowsExploits/Exploits ![Github stars](https://shields.io/github/stars/WindowsExploits/Exploits?style=social) ![Github forks](https://shields.io/github/forks/WindowsExploits/Exploits?style=social) ![Github watchers](https://shields.io/github/watchers/WindowsExploits/Exploits?style=social)
- github.com/codewhitesec/UnmarshalPwn ![Github stars](https://shields.io/github/stars/codewhitesec/UnmarshalPwn?style=social) ![Github forks](https://shields.io/github/forks/codewhitesec/UnmarshalPwn?style=social) ![Github watchers](https://shields.io/github/watchers/codewhitesec/UnmarshalPwn?style=social)
- github.com/shellphish/how2heap ![Github stars](https://shields.io/github/stars/shellphish/how2heap?style=social) ![Github forks](https://shields.io/github/forks/shellphish/how2heap?style=social) ![Github watchers](https://shields.io/github/watchers/shellphish/how2heap?style=social)
- github.com/externalist/exploit_playground ![Github stars](https://shields.io/github/stars/externalist/exploit_playground?style=social) ![Github forks](https://shields.io/github/forks/externalist/exploit_playground?style=social) ![Github watchers](https://shields.io/github/watchers/externalist/exploit_playground?style=social)
- github.com/cervoise/Abuse-bash-for-windows ![Github stars](https://shields.io/github/stars/cervoise/Abuse-bash-for-windows?style=social) ![Github forks](https://shields.io/github/forks/cervoise/Abuse-bash-for-windows?style=social) ![Github watchers](https://shields.io/github/watchers/cervoise/Abuse-bash-for-windows?style=social)

## linux exploits

- github.com/ylcangel/exploits ![Github stars](https://shields.io/github/stars/ylcangel/exploits?style=social) ![Github forks](https://shields.io/github/forks/ylcangel/exploits?style=social) ![Github watchers](https://shields.io/github/watchers/ylcangel/exploits?style=social)

## windows kernel exploits

- github.com/bluefrostsecurity/Meltdown-KVA-Shadow-Leak (Meltdown Reloaded: Breaking Windows KASLR by Leaking KVA Shadow Mappings) ![Github stars](https://shields.io/github/stars/bluefrostsecurity/Meltdown-KVA-Shadow-Leak?style=social) ![Github forks](https://shields.io/github/forks/bluefrostsecurity/Meltdown-KVA-Shadow-Leak?style=social) ![Github watchers](https://shields.io/github/watchers/bluefrostsecurity/Meltdown-KVA-Shadow-Leak?style=social)
- github.com/synacktiv/Windows-kernel-SegmentHeap-Aligned-Chunk-Confusion ![Github stars](https://shields.io/github/stars/synacktiv/Windows-kernel-SegmentHeap-Aligned-Chunk-Confusion?style=social) ![Github forks](https://shields.io/github/forks/synacktiv/Windows-kernel-SegmentHeap-Aligned-Chunk-Confusion?style=social) ![Github watchers](https://shields.io/github/watchers/synacktiv/Windows-kernel-SegmentHeap-Aligned-Chunk-Confusion?style=social)
- github.com/gdabah/win32k-bugs ![Github stars](https://shields.io/github/stars/gdabah/win32k-bugs?style=social) ![Github forks](https://shields.io/github/forks/gdabah/win32k-bugs?style=social) ![Github watchers](https://shields.io/github/watchers/gdabah/win32k-bugs?style=social)
- github.com/SouhailHammou/Drivers (ATP bypass) ![Github stars](https://shields.io/github/stars/SouhailHammou/Drivers?style=social) ![Github forks](https://shields.io/github/forks/SouhailHammou/Drivers?style=social) ![Github watchers](https://shields.io/github/watchers/SouhailHammou/Drivers?style=social)
- www.unknowncheats.me/forum/anti-cheat-bypass/334557-vulnerable-driver-megathread.html?nsukey=CkSGplDUMAWaGbr8btXXDeNqNyzCau83773dZHbUgTD2KbfFsN4ReqwwjwB1TE2jjUz0HHSUQSrvX7JZ%2BtA0RPQFg5pWsGwlyCVT6EW1cF8Y%2BDfa%2Fd8KHdi%2FFG5mj6oTcKaCfR%2BQmUANoXeWHbzursQ68JQdcT5zfCKwgR7ZutAla5N%2FHH8448BpwB4nKJuBB0ns7Ex0vVB7O8j%2BkcFaug%3D%3D
- github.com/n3k/EKOParty2015_Windows_SMEP_Bypass (SEMP bypass) ![Github stars](https://shields.io/github/stars/n3k/EKOParty2015_Windows_SMEP_Bypass?style=social) ![Github forks](https://shields.io/github/forks/n3k/EKOParty2015_Windows_SMEP_Bypass?style=social) ![Github watchers](https://shields.io/github/watchers/n3k/EKOParty2015_Windows_SMEP_Bypass?style=social)
- github.com/saaramar/execve_exploit (WSL) ![Github stars](https://shields.io/github/stars/saaramar/execve_exploit?style=social) ![Github forks](https://shields.io/github/forks/saaramar/execve_exploit?style=social) ![Github watchers](https://shields.io/github/watchers/saaramar/execve_exploit?style=social)
- github.com/siberas/CVE-2016-3309_Reloaded ![Github stars](https://shields.io/github/stars/siberas/CVE-2016-3309_Reloaded?style=social) ![Github forks](https://shields.io/github/forks/siberas/CVE-2016-3309_Reloaded?style=social) ![Github watchers](https://shields.io/github/watchers/siberas/CVE-2016-3309_Reloaded?style=social)
- github.com/moccajoghurt/drvmap_secure ![Github stars](https://shields.io/github/stars/moccajoghurt/drvmap_secure?style=social) ![Github forks](https://shields.io/github/forks/moccajoghurt/drvmap_secure?style=social) ![Github watchers](https://shields.io/github/watchers/moccajoghurt/drvmap_secure?style=social)
- github.com/fishstiqz/poolinfo ![Github stars](https://shields.io/github/stars/fishstiqz/poolinfo?style=social) ![Github forks](https://shields.io/github/forks/fishstiqz/poolinfo?style=social) ![Github watchers](https://shields.io/github/watchers/fishstiqz/poolinfo?style=social)
- github.com/cbayet/Exploit-CVE-2017-6008 ![Github stars](https://shields.io/github/stars/cbayet/Exploit-CVE-2017-6008?style=social) ![Github forks](https://shields.io/github/forks/cbayet/Exploit-CVE-2017-6008?style=social) ![Github watchers](https://shields.io/github/watchers/cbayet/Exploit-CVE-2017-6008?style=social)
- github.com/cbayet/PoolSprayer (pool spray) ![Github stars](https://shields.io/github/stars/cbayet/PoolSprayer?style=social) ![Github forks](https://shields.io/github/forks/cbayet/PoolSprayer?style=social) ![Github watchers](https://shields.io/github/watchers/cbayet/PoolSprayer?style=social)
- github.com/DownWithUp/CVE-2018-15499 (race condition) ![Github stars](https://shields.io/github/stars/DownWithUp/CVE-2018-15499?style=social) ![Github forks](https://shields.io/github/forks/DownWithUp/CVE-2018-15499?style=social) ![Github watchers](https://shields.io/github/watchers/DownWithUp/CVE-2018-15499?style=social)
- github.com/SandboxEscaper/randomrepo (win10 LPE) ![Github stars](https://shields.io/github/stars/SandboxEscaper/randomrepo?style=social) ![Github forks](https://shields.io/github/forks/SandboxEscaper/randomrepo?style=social) ![Github watchers](https://shields.io/github/watchers/SandboxEscaper/randomrepo?style=social)
- github.com/jackson5-sec/TaskSchedLPE (LPE) ![Github stars](https://shields.io/github/stars/jackson5-sec/TaskSchedLPE?style=social) ![Github forks](https://shields.io/github/forks/jackson5-sec/TaskSchedLPE?style=social) ![Github watchers](https://shields.io/github/watchers/jackson5-sec/TaskSchedLPE?style=social)
- github.com/HarsaroopDhillon/AHNLab-0day(LPE) ![Github stars](https://shields.io/github/stars/HarsaroopDhillon/AHNLab-0day(LPE)?style=social) ![Github forks](https://shields.io/github/forks/HarsaroopDhillon/AHNLab-0day(LPE)?style=social) ![Github watchers](https://shields.io/github/watchers/HarsaroopDhillon/AHNLab-0day(LPE)?style=social)
- github.com/paranoidninja/Pandoras-Box ![Github stars](https://shields.io/github/stars/paranoidninja/Pandoras-Box?style=social) ![Github forks](https://shields.io/github/forks/paranoidninja/Pandoras-Box?style=social) ![Github watchers](https://shields.io/github/watchers/paranoidninja/Pandoras-Box?style=social)
- github.com/MarkHC/HandleMaster ![Github stars](https://shields.io/github/stars/MarkHC/HandleMaster?style=social) ![Github forks](https://shields.io/github/forks/MarkHC/HandleMaster?style=social) ![Github watchers](https://shields.io/github/watchers/MarkHC/HandleMaster?style=social)
- github.com/can1357/physical_mem_controller ![Github stars](https://shields.io/github/stars/can1357/physical_mem_controller?style=social) ![Github forks](https://shields.io/github/forks/can1357/physical_mem_controller?style=social) ![Github watchers](https://shields.io/github/watchers/can1357/physical_mem_controller?style=social)
- github.com/can1357/safe_capcom ![Github stars](https://shields.io/github/stars/can1357/safe_capcom?style=social) ![Github forks](https://shields.io/github/forks/can1357/safe_capcom?style=social) ![Github watchers](https://shields.io/github/watchers/can1357/safe_capcom?style=social)
- github.com/can1357/CVE-2018-8897 ![Github stars](https://shields.io/github/stars/can1357/CVE-2018-8897?style=social) ![Github forks](https://shields.io/github/forks/can1357/CVE-2018-8897?style=social) ![Github watchers](https://shields.io/github/watchers/can1357/CVE-2018-8897?style=social)
- github.com/JeremyFetiveau/Exploits ![Github stars](https://shields.io/github/stars/JeremyFetiveau/Exploits?style=social) ![Github forks](https://shields.io/github/forks/JeremyFetiveau/Exploits?style=social) ![Github watchers](https://shields.io/github/watchers/JeremyFetiveau/Exploits?style=social)
- github.com/hfiref0x/Stryker ![Github stars](https://shields.io/github/stars/hfiref0x/Stryker?style=social) ![Github forks](https://shields.io/github/forks/hfiref0x/Stryker?style=social) ![Github watchers](https://shields.io/github/watchers/hfiref0x/Stryker?style=social)
- github.com/swwwolf/obderef ![Github stars](https://shields.io/github/stars/swwwolf/obderef?style=social) ![Github forks](https://shields.io/github/forks/swwwolf/obderef?style=social) ![Github watchers](https://shields.io/github/watchers/swwwolf/obderef?style=social)
- github.com/k0keoyo/CVE-2017-0038-EXP-C-JS ![Github stars](https://shields.io/github/stars/k0keoyo/CVE-2017-0038-EXP-C-JS?style=social) ![Github forks](https://shields.io/github/forks/k0keoyo/CVE-2017-0038-EXP-C-JS?style=social) ![Github watchers](https://shields.io/github/watchers/k0keoyo/CVE-2017-0038-EXP-C-JS?style=social)
- github.com/cbayet/PoolSprayer ![Github stars](https://shields.io/github/stars/cbayet/PoolSprayer?style=social) ![Github forks](https://shields.io/github/forks/cbayet/PoolSprayer?style=social) ![Github watchers](https://shields.io/github/watchers/cbayet/PoolSprayer?style=social)
- github.com/k0keoyo/Vir.IT-explorer-Anti-Virus-Null-Pointer-Reference-PoC ![Github stars](https://shields.io/github/stars/k0keoyo/Vir.IT-explorer-Anti-Virus-Null-Pointer-Reference-PoC?style=social) ![Github forks](https://shields.io/github/forks/k0keoyo/Vir.IT-explorer-Anti-Virus-Null-Pointer-Reference-PoC?style=social) ![Github watchers](https://shields.io/github/watchers/k0keoyo/Vir.IT-explorer-Anti-Virus-Null-Pointer-Reference-PoC?style=social)
- github.com/k0keoyo/Driver-Loaded-PoC ![Github stars](https://shields.io/github/stars/k0keoyo/Driver-Loaded-PoC?style=social) ![Github forks](https://shields.io/github/forks/k0keoyo/Driver-Loaded-PoC?style=social) ![Github watchers](https://shields.io/github/watchers/k0keoyo/Driver-Loaded-PoC?style=social)
- github.com/k0keoyo/try_exploit ![Github stars](https://shields.io/github/stars/k0keoyo/try_exploit?style=social) ![Github forks](https://shields.io/github/forks/k0keoyo/try_exploit?style=social) ![Github watchers](https://shields.io/github/watchers/k0keoyo/try_exploit?style=social)
- github.com/k0keoyo/CVE-2015-2546-Exploit ![Github stars](https://shields.io/github/stars/k0keoyo/CVE-2015-2546-Exploit?style=social) ![Github forks](https://shields.io/github/forks/k0keoyo/CVE-2015-2546-Exploit?style=social) ![Github watchers](https://shields.io/github/watchers/k0keoyo/CVE-2015-2546-Exploit?style=social)
- github.com/k0keoyo/Dark_Composition_case_study_Integer_Overflow ![Github stars](https://shields.io/github/stars/k0keoyo/Dark_Composition_case_study_Integer_Overflow?style=social) ![Github forks](https://shields.io/github/forks/k0keoyo/Dark_Composition_case_study_Integer_Overflow?style=social) ![Github watchers](https://shields.io/github/watchers/k0keoyo/Dark_Composition_case_study_Integer_Overflow?style=social)
- github.com/tinysec/vulnerability ![Github stars](https://shields.io/github/stars/tinysec/vulnerability?style=social) ![Github forks](https://shields.io/github/forks/tinysec/vulnerability?style=social) ![Github watchers](https://shields.io/github/watchers/tinysec/vulnerability?style=social)
- github.com/akayn/demos ![Github stars](https://shields.io/github/stars/akayn/demos?style=social) ![Github forks](https://shields.io/github/forks/akayn/demos?style=social) ![Github watchers](https://shields.io/github/watchers/akayn/demos?style=social)
- github.com/abatchy17/WindowsExploits ![Github stars](https://shields.io/github/stars/abatchy17/WindowsExploits?style=social) ![Github forks](https://shields.io/github/forks/abatchy17/WindowsExploits?style=social) ![Github watchers](https://shields.io/github/watchers/abatchy17/WindowsExploits?style=social)
- github.com/recodeking/WindowsExploitation ![Github stars](https://shields.io/github/stars/recodeking/WindowsExploitation?style=social) ![Github forks](https://shields.io/github/forks/recodeking/WindowsExploitation?style=social) ![Github watchers](https://shields.io/github/watchers/recodeking/WindowsExploitation?style=social)
- github.com/GDSSecurity/Windows-Exploit-Suggester ![Github stars](https://shields.io/github/stars/GDSSecurity/Windows-Exploit-Suggester?style=social) ![Github forks](https://shields.io/github/forks/GDSSecurity/Windows-Exploit-Suggester?style=social) ![Github watchers](https://shields.io/github/watchers/GDSSecurity/Windows-Exploit-Suggester?style=social)
- github.com/rwfpl/rewolf-pcausa-exploit ![Github stars](https://shields.io/github/stars/rwfpl/rewolf-pcausa-exploit?style=social) ![Github forks](https://shields.io/github/forks/rwfpl/rewolf-pcausa-exploit?style=social) ![Github watchers](https://shields.io/github/watchers/rwfpl/rewolf-pcausa-exploit?style=social)
- github.com/ratty3697/HackSpy-Trojan-Exploit ![Github stars](https://shields.io/github/stars/ratty3697/HackSpy-Trojan-Exploit?style=social) ![Github forks](https://shields.io/github/forks/ratty3697/HackSpy-Trojan-Exploit?style=social) ![Github watchers](https://shields.io/github/watchers/ratty3697/HackSpy-Trojan-Exploit?style=social)
- github.com/SecWiki/windows-kernel-exploits ![Github stars](https://shields.io/github/stars/SecWiki/windows-kernel-exploits?style=social) ![Github forks](https://shields.io/github/forks/SecWiki/windows-kernel-exploits?style=social) ![Github watchers](https://shields.io/github/watchers/SecWiki/windows-kernel-exploits?style=social)
- github.com/sensepost/ms16-098 ![Github stars](https://shields.io/github/stars/sensepost/ms16-098?style=social) ![Github forks](https://shields.io/github/forks/sensepost/ms16-098?style=social) ![Github watchers](https://shields.io/github/watchers/sensepost/ms16-098?style=social)
- github.com/shjalayeri/sysret ![Github stars](https://shields.io/github/stars/shjalayeri/sysret?style=social) ![Github forks](https://shields.io/github/forks/shjalayeri/sysret?style=social) ![Github watchers](https://shields.io/github/watchers/shjalayeri/sysret?style=social)
- github.com/sam-b/windows_kernel_resources ![Github stars](https://shields.io/github/stars/sam-b/windows_kernel_resources?style=social) ![Github forks](https://shields.io/github/forks/sam-b/windows_kernel_resources?style=social) ![Github watchers](https://shields.io/github/watchers/sam-b/windows_kernel_resources?style=social)
- github.com/sensepost/gdi-palettes-exp ![Github stars](https://shields.io/github/stars/sensepost/gdi-palettes-exp?style=social) ![Github forks](https://shields.io/github/forks/sensepost/gdi-palettes-exp?style=social) ![Github watchers](https://shields.io/github/watchers/sensepost/gdi-palettes-exp?style=social)
- github.com/ExpLife/ByPassCfg ![Github stars](https://shields.io/github/stars/ExpLife/ByPassCfg?style=social) ![Github forks](https://shields.io/github/forks/ExpLife/ByPassCfg?style=social) ![Github watchers](https://shields.io/github/watchers/ExpLife/ByPassCfg?style=social)
- github.com/Rootkitsmm/WinIo-Vidix ![Github stars](https://shields.io/github/stars/Rootkitsmm/WinIo-Vidix?style=social) ![Github forks](https://shields.io/github/forks/Rootkitsmm/WinIo-Vidix?style=social) ![Github watchers](https://shields.io/github/watchers/Rootkitsmm/WinIo-Vidix?style=social)
- github.com/andrewkabai/vulnwindrv ![Github stars](https://shields.io/github/stars/andrewkabai/vulnwindrv?style=social) ![Github forks](https://shields.io/github/forks/andrewkabai/vulnwindrv?style=social) ![Github watchers](https://shields.io/github/watchers/andrewkabai/vulnwindrv?style=social)
- github.com/mwrlabs/CVE-2016-7255 ![Github stars](https://shields.io/github/stars/mwrlabs/CVE-2016-7255?style=social) ![Github forks](https://shields.io/github/forks/mwrlabs/CVE-2016-7255?style=social) ![Github watchers](https://shields.io/github/watchers/mwrlabs/CVE-2016-7255?style=social)
- github.com/MarkHC/HandleMaster ![Github stars](https://shields.io/github/stars/MarkHC/HandleMaster?style=social) ![Github forks](https://shields.io/github/forks/MarkHC/HandleMaster?style=social) ![Github watchers](https://shields.io/github/watchers/MarkHC/HandleMaster?style=social)
- github.com/SamLarenN/CapcomDKOM ![Github stars](https://shields.io/github/stars/SamLarenN/CapcomDKOM?style=social) ![Github forks](https://shields.io/github/forks/SamLarenN/CapcomDKOM?style=social) ![Github watchers](https://shields.io/github/watchers/SamLarenN/CapcomDKOM?style=social)
- github.com/zerosum0x0/puppetstrings ![Github stars](https://shields.io/github/stars/zerosum0x0/puppetstrings?style=social) ![Github forks](https://shields.io/github/forks/zerosum0x0/puppetstrings?style=social) ![Github watchers](https://shields.io/github/watchers/zerosum0x0/puppetstrings?style=social)
- github.com/zerosum0x0/ShellcodeDriver ![Github stars](https://shields.io/github/stars/zerosum0x0/ShellcodeDriver?style=social) ![Github forks](https://shields.io/github/forks/zerosum0x0/ShellcodeDriver?style=social) ![Github watchers](https://shields.io/github/watchers/zerosum0x0/ShellcodeDriver?style=social)
- github.com/Rootkitsmm/WinIo-Vidix ![Github stars](https://shields.io/github/stars/Rootkitsmm/WinIo-Vidix?style=social) ![Github forks](https://shields.io/github/forks/Rootkitsmm/WinIo-Vidix?style=social) ![Github watchers](https://shields.io/github/watchers/Rootkitsmm/WinIo-Vidix?style=social)
- github.com/progmboy/kernel_vul_poc ![Github stars](https://shields.io/github/stars/progmboy/kernel_vul_poc?style=social) ![Github forks](https://shields.io/github/forks/progmboy/kernel_vul_poc?style=social) ![Github watchers](https://shields.io/github/watchers/progmboy/kernel_vul_poc?style=social)
- github.com/rwfpl/rewolf-msi-exploit ![Github stars](https://shields.io/github/stars/rwfpl/rewolf-msi-exploit?style=social) ![Github forks](https://shields.io/github/forks/rwfpl/rewolf-msi-exploit?style=social) ![Github watchers](https://shields.io/github/watchers/rwfpl/rewolf-msi-exploit?style=social)
- github.com/rwfpl/rewolf-pcausa-exploit ![Github stars](https://shields.io/github/stars/rwfpl/rewolf-pcausa-exploit?style=social) ![Github forks](https://shields.io/github/forks/rwfpl/rewolf-pcausa-exploit?style=social) ![Github watchers](https://shields.io/github/watchers/rwfpl/rewolf-pcausa-exploit?style=social)
- github.com/Rootkitsmm/Win10Pcap-Exploit ![Github stars](https://shields.io/github/stars/Rootkitsmm/Win10Pcap-Exploit?style=social) ![Github forks](https://shields.io/github/forks/Rootkitsmm/Win10Pcap-Exploit?style=social) ![Github watchers](https://shields.io/github/watchers/Rootkitsmm/Win10Pcap-Exploit?style=social)
- github.com/Rootkitsmm/MS15-061 ![Github stars](https://shields.io/github/stars/Rootkitsmm/MS15-061?style=social) ![Github forks](https://shields.io/github/forks/Rootkitsmm/MS15-061?style=social) ![Github watchers](https://shields.io/github/watchers/Rootkitsmm/MS15-061?style=social)
- github.com/Rootkitsmm/cve-2016-0040 ![Github stars](https://shields.io/github/stars/Rootkitsmm/cve-2016-0040?style=social) ![Github forks](https://shields.io/github/forks/Rootkitsmm/cve-2016-0040?style=social) ![Github watchers](https://shields.io/github/watchers/Rootkitsmm/cve-2016-0040?style=social)
- github.com/Rootkitsmm/CVEXX-XX ![Github stars](https://shields.io/github/stars/Rootkitsmm/CVEXX-XX?style=social) ![Github forks](https://shields.io/github/forks/Rootkitsmm/CVEXX-XX?style=social) ![Github watchers](https://shields.io/github/watchers/Rootkitsmm/CVEXX-XX?style=social)
- github.com/sensepost/ms16-098 ![Github stars](https://shields.io/github/stars/sensepost/ms16-098?style=social) ![Github forks](https://shields.io/github/forks/sensepost/ms16-098?style=social) ![Github watchers](https://shields.io/github/watchers/sensepost/ms16-098?style=social)
- github.com/Trietptm-on-Security/bug-free-adventure ![Github stars](https://shields.io/github/stars/Trietptm-on-Security/bug-free-adventure?style=social) ![Github forks](https://shields.io/github/forks/Trietptm-on-Security/bug-free-adventure?style=social) ![Github watchers](https://shields.io/github/watchers/Trietptm-on-Security/bug-free-adventure?style=social)
- github.com/sam-b/CVE-2014-4113 ![Github stars](https://shields.io/github/stars/sam-b/CVE-2014-4113?style=social) ![Github forks](https://shields.io/github/forks/sam-b/CVE-2014-4113?style=social) ![Github watchers](https://shields.io/github/watchers/sam-b/CVE-2014-4113?style=social)
- github.com/Rootkitsmm/OpenVpn-Pool-Overflow ![Github stars](https://shields.io/github/stars/Rootkitsmm/OpenVpn-Pool-Overflow?style=social) ![Github forks](https://shields.io/github/forks/Rootkitsmm/OpenVpn-Pool-Overflow?style=social) ![Github watchers](https://shields.io/github/watchers/Rootkitsmm/OpenVpn-Pool-Overflow?style=social)
- github.com/Rootkitsmm/UnThreatAVDriver-DOS ![Github stars](https://shields.io/github/stars/Rootkitsmm/UnThreatAVDriver-DOS?style=social) ![Github forks](https://shields.io/github/forks/Rootkitsmm/UnThreatAVDriver-DOS?style=social) ![Github watchers](https://shields.io/github/watchers/Rootkitsmm/UnThreatAVDriver-DOS?style=social)
- github.com/Cr4sh/ThinkPwn ![Github stars](https://shields.io/github/stars/Cr4sh/ThinkPwn?style=social) ![Github forks](https://shields.io/github/forks/Cr4sh/ThinkPwn?style=social) ![Github watchers](https://shields.io/github/watchers/Cr4sh/ThinkPwn?style=social)
- github.com/hfiref0x/CVE-2015-1701 ![Github stars](https://shields.io/github/stars/hfiref0x/CVE-2015-1701?style=social) ![Github forks](https://shields.io/github/forks/hfiref0x/CVE-2015-1701?style=social) ![Github watchers](https://shields.io/github/watchers/hfiref0x/CVE-2015-1701?style=social)
- github.com/tyranid/windows-logical-eop-workshop ![Github stars](https://shields.io/github/stars/tyranid/windows-logical-eop-workshop?style=social) ![Github forks](https://shields.io/github/forks/tyranid/windows-logical-eop-workshop?style=social) ![Github watchers](https://shields.io/github/watchers/tyranid/windows-logical-eop-workshop?style=social)
- github.com/google/sandbox-attacksurface-analysis-tools ![Github stars](https://shields.io/github/stars/google/sandbox-attacksurface-analysis-tools?style=social) ![Github forks](https://shields.io/github/forks/google/sandbox-attacksurface-analysis-tools?style=social) ![Github watchers](https://shields.io/github/watchers/google/sandbox-attacksurface-analysis-tools?style=social)
- github.com/tyranid/ExploitRemotingService ![Github stars](https://shields.io/github/stars/tyranid/ExploitRemotingService?style=social) ![Github forks](https://shields.io/github/forks/tyranid/ExploitRemotingService?style=social) ![Github watchers](https://shields.io/github/watchers/tyranid/ExploitRemotingService?style=social)
- github.com/tyranid/DeviceGuardBypasses ![Github stars](https://shields.io/github/stars/tyranid/DeviceGuardBypasses?style=social) ![Github forks](https://shields.io/github/forks/tyranid/DeviceGuardBypasses?style=social) ![Github watchers](https://shields.io/github/watchers/tyranid/DeviceGuardBypasses?style=social)
- github.com/tyranid/ExploitDotNetDCOM ![Github stars](https://shields.io/github/stars/tyranid/ExploitDotNetDCOM?style=social) ![Github forks](https://shields.io/github/forks/tyranid/ExploitDotNetDCOM?style=social) ![Github watchers](https://shields.io/github/watchers/tyranid/ExploitDotNetDCOM?style=social)
- github.com/hatRiot/token-priv(EOP) ![Github stars](https://shields.io/github/stars/hatRiot/token-priv(EOP)?style=social) ![Github forks](https://shields.io/github/forks/hatRiot/token-priv(EOP)?style=social) ![Github watchers](https://shields.io/github/watchers/hatRiot/token-priv(EOP)?style=social)
- github.com/weizn11/MS17010_AllInOne ![Github stars](https://shields.io/github/stars/weizn11/MS17010_AllInOne?style=social) ![Github forks](https://shields.io/github/forks/weizn11/MS17010_AllInOne?style=social) ![Github watchers](https://shields.io/github/watchers/weizn11/MS17010_AllInOne?style=social)
- github.com/TeskeVirtualSystem/MS17010Test ![Github stars](https://shields.io/github/stars/TeskeVirtualSystem/MS17010Test?style=social) ![Github forks](https://shields.io/github/forks/TeskeVirtualSystem/MS17010Test?style=social) ![Github watchers](https://shields.io/github/watchers/TeskeVirtualSystem/MS17010Test?style=social)

## race condition

- github.com/0xcpu/dijuno ![Github stars](https://shields.io/github/stars/0xcpu/dijuno?style=social) ![Github forks](https://shields.io/github/forks/0xcpu/dijuno?style=social) ![Github watchers](https://shields.io/github/watchers/0xcpu/dijuno?style=social)

## LPE

- github.com/ly4k/CallbackHell ![Github stars](https://shields.io/github/stars/ly4k/CallbackHell?style=social) ![Github forks](https://shields.io/github/forks/ly4k/CallbackHell?style=social) ![Github watchers](https://shields.io/github/watchers/ly4k/CallbackHell?style=social)
- github.com/itm4n/PrintSpoofer ![Github stars](https://shields.io/github/stars/itm4n/PrintSpoofer?style=social) ![Github forks](https://shields.io/github/forks/itm4n/PrintSpoofer?style=social) ![Github watchers](https://shields.io/github/watchers/itm4n/PrintSpoofer?style=social)
- github.com/yusufqk/SystemToken ![Github stars](https://shields.io/github/stars/yusufqk/SystemToken?style=social) ![Github forks](https://shields.io/github/forks/yusufqk/SystemToken?style=social) ![Github watchers](https://shields.io/github/watchers/yusufqk/SystemToken?style=social)
- github.com/itm4n/UsoDllLoader ![Github stars](https://shields.io/github/stars/itm4n/UsoDllLoader?style=social) ![Github forks](https://shields.io/github/forks/itm4n/UsoDllLoader?style=social) ![Github watchers](https://shields.io/github/watchers/itm4n/UsoDllLoader?style=social)
- github.com/DoubleLabyrinth/SdoKeyCrypt-sys-local-privilege-elevation ![Github stars](https://shields.io/github/stars/DoubleLabyrinth/SdoKeyCrypt-sys-local-privilege-elevation?style=social) ![Github forks](https://shields.io/github/forks/DoubleLabyrinth/SdoKeyCrypt-sys-local-privilege-elevation?style=social) ![Github watchers](https://shields.io/github/watchers/DoubleLabyrinth/SdoKeyCrypt-sys-local-privilege-elevation?style=social)
- github.com/AlessandroZ/BeRoot ![Github stars](https://shields.io/github/stars/AlessandroZ/BeRoot?style=social) ![Github forks](https://shields.io/github/forks/AlessandroZ/BeRoot?style=social) ![Github watchers](https://shields.io/github/watchers/AlessandroZ/BeRoot?style=social)
- github.com/HackerPide/The-Division-Bypass (division bypass) ![Github stars](https://shields.io/github/stars/HackerPide/The-Division-Bypass?style=social) ![Github forks](https://shields.io/github/forks/HackerPide/The-Division-Bypass?style=social) ![Github watchers](https://shields.io/github/watchers/HackerPide/The-Division-Bypass?style=social)
- github.com/khr0x40sh/WhiteListEvasion ![Github stars](https://shields.io/github/stars/khr0x40sh/WhiteListEvasion?style=social) ![Github forks](https://shields.io/github/forks/khr0x40sh/WhiteListEvasion?style=social) ![Github watchers](https://shields.io/github/watchers/khr0x40sh/WhiteListEvasion?style=social)
- github.com/ohpe/juicy-potato ![Github stars](https://shields.io/github/stars/ohpe/juicy-potato?style=social) ![Github forks](https://shields.io/github/forks/ohpe/juicy-potato?style=social) ![Github watchers](https://shields.io/github/watchers/ohpe/juicy-potato?style=social)
- github.com/nmulasmajic/syscall_exploit_CVE-2018-8897 ![Github stars](https://shields.io/github/stars/nmulasmajic/syscall_exploit_CVE-2018-8897?style=social) ![Github forks](https://shields.io/github/forks/nmulasmajic/syscall_exploit_CVE-2018-8897?style=social) ![Github watchers](https://shields.io/github/watchers/nmulasmajic/syscall_exploit_CVE-2018-8897?style=social)
- github.com/codewhitesec/UnmarshalPwn ![Github stars](https://shields.io/github/stars/codewhitesec/UnmarshalPwn?style=social) ![Github forks](https://shields.io/github/forks/codewhitesec/UnmarshalPwn?style=social) ![Github watchers](https://shields.io/github/watchers/codewhitesec/UnmarshalPwn?style=social)
- ohpe.github.io/juicy-potato/

## linux exploit

- github.com/Lazenca/Exploit-tech ![Github stars](https://shields.io/github/stars/Lazenca/Exploit-tech?style=social) ![Github forks](https://shields.io/github/forks/Lazenca/Exploit-tech?style=social) ![Github watchers](https://shields.io/github/watchers/Lazenca/Exploit-tech?style=social)
- github.com/Lazenca/Kernel-exploit-tech ![Github stars](https://shields.io/github/stars/Lazenca/Kernel-exploit-tech?style=social) ![Github forks](https://shields.io/github/forks/Lazenca/Kernel-exploit-tech?style=social) ![Github watchers](https://shields.io/github/watchers/Lazenca/Kernel-exploit-tech?style=social)

## office exploit

- github.com/houjingyi233/office-exploit-case-study ![Github stars](https://shields.io/github/stars/houjingyi233/office-exploit-case-study?style=social) ![Github forks](https://shields.io/github/forks/houjingyi233/office-exploit-case-study?style=social) ![Github watchers](https://shields.io/github/watchers/houjingyi233/office-exploit-case-study?style=social)
- github.com/rxwx/CVE-2017-8570 ![Github stars](https://shields.io/github/stars/rxwx/CVE-2017-8570?style=social) ![Github forks](https://shields.io/github/forks/rxwx/CVE-2017-8570?style=social) ![Github watchers](https://shields.io/github/watchers/rxwx/CVE-2017-8570?style=social)

## flash exploit

- github.com/brianwrf/CVE-2017-4878-Samples ![Github stars](https://shields.io/github/stars/brianwrf/CVE-2017-4878-Samples?style=social) ![Github forks](https://shields.io/github/forks/brianwrf/CVE-2017-4878-Samples?style=social) ![Github watchers](https://shields.io/github/watchers/brianwrf/CVE-2017-4878-Samples?style=social)

## sandbox

- github.com/Cisco-Talos/pyrebox ![Github stars](https://shields.io/github/stars/Cisco-Talos/pyrebox?style=social) ![Github forks](https://shields.io/github/forks/Cisco-Talos/pyrebox?style=social) ![Github watchers](https://shields.io/github/watchers/Cisco-Talos/pyrebox?style=social)
- github.com/taiFansou/Proteibox ![Github stars](https://shields.io/github/stars/taiFansou/Proteibox?style=social) ![Github forks](https://shields.io/github/forks/taiFansou/Proteibox?style=social) ![Github watchers](https://shields.io/github/watchers/taiFansou/Proteibox?style=social)

## sandbox escape

- github.com/b4rtik/ATPMiniDump ![Github stars](https://shields.io/github/stars/b4rtik/ATPMiniDump?style=social) ![Github forks](https://shields.io/github/forks/b4rtik/ATPMiniDump?style=social) ![Github watchers](https://shields.io/github/watchers/b4rtik/ATPMiniDump?style=social)
- github.com/ray-cp/vm-escape ![Github stars](https://shields.io/github/stars/ray-cp/vm-escape?style=social) ![Github forks](https://shields.io/github/forks/ray-cp/vm-escape?style=social) ![Github watchers](https://shields.io/github/watchers/ray-cp/vm-escape?style=social)
- github.com/xairy/vmware-exploitation ![Github stars](https://shields.io/github/stars/xairy/vmware-exploitation?style=social) ![Github forks](https://shields.io/github/forks/xairy/vmware-exploitation?style=social) ![Github watchers](https://shields.io/github/watchers/xairy/vmware-exploitation?style=social)
- github.com/649/Chrome-Sandbox-Exploit ![Github stars](https://shields.io/github/stars/649/Chrome-Sandbox-Exploit?style=social) ![Github forks](https://shields.io/github/forks/649/Chrome-Sandbox-Exploit?style=social) ![Github watchers](https://shields.io/github/watchers/649/Chrome-Sandbox-Exploit?style=social)
- github.com/SilverMoonSecurity/SandboxEvasion ![Github stars](https://shields.io/github/stars/SilverMoonSecurity/SandboxEvasion?style=social) ![Github forks](https://shields.io/github/forks/SilverMoonSecurity/SandboxEvasion?style=social) ![Github watchers](https://shields.io/github/watchers/SilverMoonSecurity/SandboxEvasion?style=social)
- github.com/exAphex/SandboxEscape ![Github stars](https://shields.io/github/stars/exAphex/SandboxEscape?style=social) ![Github forks](https://shields.io/github/forks/exAphex/SandboxEscape?style=social) ![Github watchers](https://shields.io/github/watchers/exAphex/SandboxEscape?style=social)
- github.com/Fel0ny/Sandbox-Detection ![Github stars](https://shields.io/github/stars/Fel0ny/Sandbox-Detection?style=social) ![Github forks](https://shields.io/github/forks/Fel0ny/Sandbox-Detection?style=social) ![Github watchers](https://shields.io/github/watchers/Fel0ny/Sandbox-Detection?style=social)
- github.com/CheckPointSW/InviZzzible ![Github stars](https://shields.io/github/stars/CheckPointSW/InviZzzible?style=social) ![Github forks](https://shields.io/github/forks/CheckPointSW/InviZzzible?style=social) ![Github watchers](https://shields.io/github/watchers/CheckPointSW/InviZzzible?style=social)
- github.com/MalwareTech/AppContainerSandbox ![Github stars](https://shields.io/github/stars/MalwareTech/AppContainerSandbox?style=social) ![Github forks](https://shields.io/github/forks/MalwareTech/AppContainerSandbox?style=social) ![Github watchers](https://shields.io/github/watchers/MalwareTech/AppContainerSandbox?style=social)
- github.com/tyranid/IE11SandboxEscapes ![Github stars](https://shields.io/github/stars/tyranid/IE11SandboxEscapes?style=social) ![Github forks](https://shields.io/github/forks/tyranid/IE11SandboxEscapes?style=social) ![Github watchers](https://shields.io/github/watchers/tyranid/IE11SandboxEscapes?style=social)
- github.com/649/Chrome-Sandbox-Exploit ![Github stars](https://shields.io/github/stars/649/Chrome-Sandbox-Exploit?style=social) ![Github forks](https://shields.io/github/forks/649/Chrome-Sandbox-Exploit?style=social) ![Github watchers](https://shields.io/github/watchers/649/Chrome-Sandbox-Exploit?style=social)
- github.com/google/sandbox-attacksurface-analysis-tools ![Github stars](https://shields.io/github/stars/google/sandbox-attacksurface-analysis-tools?style=social) ![Github forks](https://shields.io/github/forks/google/sandbox-attacksurface-analysis-tools?style=social) ![Github watchers](https://shields.io/github/watchers/google/sandbox-attacksurface-analysis-tools?style=social)
- github.com/conix-security/zer0m0n ![Github stars](https://shields.io/github/stars/conix-security/zer0m0n?style=social) ![Github forks](https://shields.io/github/forks/conix-security/zer0m0n?style=social) ![Github watchers](https://shields.io/github/watchers/conix-security/zer0m0n?style=social)
- github.com/iceb0y/windows-container ![Github stars](https://shields.io/github/stars/iceb0y/windows-container?style=social) ![Github forks](https://shields.io/github/forks/iceb0y/windows-container?style=social) ![Github watchers](https://shields.io/github/watchers/iceb0y/windows-container?style=social)
- github.com/s7ephen/SandKit ![Github stars](https://shields.io/github/stars/s7ephen/SandKit?style=social) ![Github forks](https://shields.io/github/forks/s7ephen/SandKit?style=social) ![Github watchers](https://shields.io/github/watchers/s7ephen/SandKit?style=social)
- github.com/D4Vinci/Dr0p1t-Framework ![Github stars](https://shields.io/github/stars/D4Vinci/Dr0p1t-Framework?style=social) ![Github forks](https://shields.io/github/forks/D4Vinci/Dr0p1t-Framework?style=social) ![Github watchers](https://shields.io/github/watchers/D4Vinci/Dr0p1t-Framework?style=social)
- github.com/cryptolok/MorphAES ![Github stars](https://shields.io/github/stars/cryptolok/MorphAES?style=social) ![Github forks](https://shields.io/github/forks/cryptolok/MorphAES?style=social) ![Github watchers](https://shields.io/github/watchers/cryptolok/MorphAES?style=social)
- github.com/mtalbi/vm_escape ![Github stars](https://shields.io/github/stars/mtalbi/vm_escape?style=social) ![Github forks](https://shields.io/github/forks/mtalbi/vm_escape?style=social) ![Github watchers](https://shields.io/github/watchers/mtalbi/vm_escape?style=social)
- github.com/unamer/vmware_escape ![Github stars](https://shields.io/github/stars/unamer/vmware_escape?style=social) ![Github forks](https://shields.io/github/forks/unamer/vmware_escape?style=social) ![Github watchers](https://shields.io/github/watchers/unamer/vmware_escape?style=social)
- github.com/erezto/lua-sandbox-escape ![Github stars](https://shields.io/github/stars/erezto/lua-sandbox-escape?style=social) ![Github forks](https://shields.io/github/forks/erezto/lua-sandbox-escape?style=social) ![Github watchers](https://shields.io/github/watchers/erezto/lua-sandbox-escape?style=social)
- github.com/brownbelt/Edge-sandbox-escape ![Github stars](https://shields.io/github/stars/brownbelt/Edge-sandbox-escape?style=social) ![Github forks](https://shields.io/github/forks/brownbelt/Edge-sandbox-escape?style=social) ![Github watchers](https://shields.io/github/watchers/brownbelt/Edge-sandbox-escape?style=social)
- github.com/shakenetwork/vmware_escape ![Github stars](https://shields.io/github/stars/shakenetwork/vmware_escape?style=social) ![Github forks](https://shields.io/github/forks/shakenetwork/vmware_escape?style=social) ![Github watchers](https://shields.io/github/watchers/shakenetwork/vmware_escape?style=social)
- github.com/Cr4sh/prl_guest_to_host ![Github stars](https://shields.io/github/stars/Cr4sh/prl_guest_to_host?style=social) ![Github forks](https://shields.io/github/forks/Cr4sh/prl_guest_to_host?style=social) ![Github watchers](https://shields.io/github/watchers/Cr4sh/prl_guest_to_host?style=social)

## anti exploit

- github.com/shjalayeri/Pwnypot ![Github stars](https://shields.io/github/stars/shjalayeri/Pwnypot?style=social) ![Github forks](https://shields.io/github/forks/shjalayeri/Pwnypot?style=social) ![Github watchers](https://shields.io/github/watchers/shjalayeri/Pwnypot?style=social)
- github.com/shjalayeri/MCEDP ![Github stars](https://shields.io/github/stars/shjalayeri/MCEDP?style=social) ![Github forks](https://shields.io/github/forks/shjalayeri/MCEDP?style=social) ![Github watchers](https://shields.io/github/watchers/shjalayeri/MCEDP?style=social)
- github.com/Empier/Anti-Exploit ![Github stars](https://shields.io/github/stars/Empier/Anti-Exploit?style=social) ![Github forks](https://shields.io/github/forks/Empier/Anti-Exploit?style=social) ![Github watchers](https://shields.io/github/watchers/Empier/Anti-Exploit?style=social)

## cve

- github.com/r0eXpeR/supplier () ![Github stars](https://shields.io/github/stars/r0eXpeR/supplier?style=social) ![Github forks](https://shields.io/github/forks/r0eXpeR/supplier?style=social) ![Github watchers](https://shields.io/github/watchers/r0eXpeR/supplier?style=social)
- github.com/stong/CVE-2020-15368 ![Github stars](https://shields.io/github/stars/stong/CVE-2020-15368?style=social) ![Github forks](https://shields.io/github/forks/stong/CVE-2020-15368?style=social) ![Github watchers](https://shields.io/github/watchers/stong/CVE-2020-15368?style=social)
- github.com/yardenshafir/CVE-2020-1034 ![Github stars](https://shields.io/github/stars/yardenshafir/CVE-2020-1034?style=social) ![Github forks](https://shields.io/github/forks/yardenshafir/CVE-2020-1034?style=social) ![Github watchers](https://shields.io/github/watchers/yardenshafir/CVE-2020-1034?style=social)
- github.com/ioncodes/CVE-2020-16938 ![Github stars](https://shields.io/github/stars/ioncodes/CVE-2020-16938?style=social) ![Github forks](https://shields.io/github/forks/ioncodes/CVE-2020-16938?style=social) ![Github watchers](https://shields.io/github/watchers/ioncodes/CVE-2020-16938?style=social)
- github.com/Ascotbe/Kernelhub ![Github stars](https://shields.io/github/stars/Ascotbe/Kernelhub?style=social) ![Github forks](https://shields.io/github/forks/Ascotbe/Kernelhub?style=social) ![Github watchers](https://shields.io/github/watchers/Ascotbe/Kernelhub?style=social)
- github.com/DownWithUp/CVE-Stockpile ![Github stars](https://shields.io/github/stars/DownWithUp/CVE-Stockpile?style=social) ![Github forks](https://shields.io/github/forks/DownWithUp/CVE-Stockpile?style=social) ![Github watchers](https://shields.io/github/watchers/DownWithUp/CVE-Stockpile?style=social)
- github.com/ollypwn/CVE-2020-0601 ![Github stars](https://shields.io/github/stars/ollypwn/CVE-2020-0601?style=social) ![Github forks](https://shields.io/github/forks/ollypwn/CVE-2020-0601?style=social) ![Github watchers](https://shields.io/github/watchers/ollypwn/CVE-2020-0601?style=social)
- github.com/bluefrostsecurity/CVE-2019-1215 (LPE) ![Github stars](https://shields.io/github/stars/bluefrostsecurity/CVE-2019-1215?style=social) ![Github forks](https://shields.io/github/forks/bluefrostsecurity/CVE-2019-1215?style=social) ![Github watchers](https://shields.io/github/watchers/bluefrostsecurity/CVE-2019-1215?style=social)
- github.com/apt69/COMahawk ![Github stars](https://shields.io/github/stars/apt69/COMahawk?style=social) ![Github forks](https://shields.io/github/forks/apt69/COMahawk?style=social) ![Github watchers](https://shields.io/github/watchers/apt69/COMahawk?style=social)
- github.com/DownWithUp/CVE-Stockpile ![Github stars](https://shields.io/github/stars/DownWithUp/CVE-Stockpile?style=social) ![Github forks](https://shields.io/github/forks/DownWithUp/CVE-Stockpile?style=social) ![Github watchers](https://shields.io/github/watchers/DownWithUp/CVE-Stockpile?style=social)
- github.com/badd1e/Disclosures ![Github stars](https://shields.io/github/stars/badd1e/Disclosures?style=social) ![Github forks](https://shields.io/github/forks/badd1e/Disclosures?style=social) ![Github watchers](https://shields.io/github/watchers/badd1e/Disclosures?style=social)
- github.com/Barakat/CVE-2019-16098 (LPE) ![Github stars](https://shields.io/github/stars/Barakat/CVE-2019-16098?style=social) ![Github forks](https://shields.io/github/forks/Barakat/CVE-2019-16098?style=social) ![Github watchers](https://shields.io/github/watchers/Barakat/CVE-2019-16098?style=social)
- github.com/qazbnm456/awesome-cve-poc#cve-2016-3088 ![Github stars](https://shields.io/github/stars/qazbnm456/awesome-cve-poc#cve-2016-3088?style=social) ![Github forks](https://shields.io/github/forks/qazbnm456/awesome-cve-poc#cve-2016-3088?style=social) ![Github watchers](https://shields.io/github/watchers/qazbnm456/awesome-cve-poc#cve-2016-3088?style=social)
- github.com/Vlad-tri/CVE-2019-1132 ![Github stars](https://shields.io/github/stars/Vlad-tri/CVE-2019-1132?style=social) ![Github forks](https://shields.io/github/forks/Vlad-tri/CVE-2019-1132?style=social) ![Github watchers](https://shields.io/github/watchers/Vlad-tri/CVE-2019-1132?style=social)
- github.com/RingLcy/VulnerabilityAnalysisAndExploit ![Github stars](https://shields.io/github/stars/RingLcy/VulnerabilityAnalysisAndExploit?style=social) ![Github forks](https://shields.io/github/forks/RingLcy/VulnerabilityAnalysisAndExploit?style=social) ![Github watchers](https://shields.io/github/watchers/RingLcy/VulnerabilityAnalysisAndExploit?style=social)
- github.com/thepwnrip/leHACK-Analysis-of-CVE-2018-8453 ![Github stars](https://shields.io/github/stars/thepwnrip/leHACK-Analysis-of-CVE-2018-8453?style=social) ![Github forks](https://shields.io/github/forks/thepwnrip/leHACK-Analysis-of-CVE-2018-8453?style=social) ![Github watchers](https://shields.io/github/watchers/thepwnrip/leHACK-Analysis-of-CVE-2018-8453?style=social)
- github.com/o0xmuhe/RealWorldPwn ![Github stars](https://shields.io/github/stars/o0xmuhe/RealWorldPwn?style=social) ![Github forks](https://shields.io/github/forks/o0xmuhe/RealWorldPwn?style=social) ![Github watchers](https://shields.io/github/watchers/o0xmuhe/RealWorldPwn?style=social)
- github.com/sophoslabs/CVE-2019-0888 (ADO UAF) ![Github stars](https://shields.io/github/stars/sophoslabs/CVE-2019-0888?style=social) ![Github forks](https://shields.io/github/forks/sophoslabs/CVE-2019-0888?style=social) ![Github watchers](https://shields.io/github/watchers/sophoslabs/CVE-2019-0888?style=social)
- github.com/Iamgublin/CVE-2019-0803 (LPE) ![Github stars](https://shields.io/github/stars/Iamgublin/CVE-2019-0803?style=social) ![Github forks](https://shields.io/github/forks/Iamgublin/CVE-2019-0803?style=social) ![Github watchers](https://shields.io/github/watchers/Iamgublin/CVE-2019-0803?style=social)
- github.com/ze0r/cve-2019-0808-poc ![Github stars](https://shields.io/github/stars/ze0r/cve-2019-0808-poc?style=social) ![Github forks](https://shields.io/github/forks/ze0r/cve-2019-0808-poc?style=social) ![Github watchers](https://shields.io/github/watchers/ze0r/cve-2019-0808-poc?style=social)
- github.com/Ridter/acefile ![Github stars](https://shields.io/github/stars/Ridter/acefile?style=social) ![Github forks](https://shields.io/github/forks/Ridter/acefile?style=social) ![Github watchers](https://shields.io/github/watchers/Ridter/acefile?style=social)
- github.com/Ridter/Exchange2domain ![Github stars](https://shields.io/github/stars/Ridter/Exchange2domain?style=social) ![Github forks](https://shields.io/github/forks/Ridter/Exchange2domain?style=social) ![Github watchers](https://shields.io/github/watchers/Ridter/Exchange2domain?style=social)
- github.com/ze0r/cve-2018-8453-exp ![Github stars](https://shields.io/github/stars/ze0r/cve-2018-8453-exp?style=social) ![Github forks](https://shields.io/github/forks/ze0r/cve-2018-8453-exp?style=social) ![Github watchers](https://shields.io/github/watchers/ze0r/cve-2018-8453-exp?style=social)
- github.com/gravitational/cve-2018-1002105 ![Github stars](https://shields.io/github/stars/gravitational/cve-2018-1002105?style=social) ![Github forks](https://shields.io/github/forks/gravitational/cve-2018-1002105?style=social) ![Github watchers](https://shields.io/github/watchers/gravitational/cve-2018-1002105?style=social)
- github.com/LyleMi/dom-vuln-db ![Github stars](https://shields.io/github/stars/LyleMi/dom-vuln-db?style=social) ![Github forks](https://shields.io/github/forks/LyleMi/dom-vuln-db?style=social) ![Github watchers](https://shields.io/github/watchers/LyleMi/dom-vuln-db?style=social)
- github.com/renorobert/virtualbox-cve-2018-2844 ![Github stars](https://shields.io/github/stars/renorobert/virtualbox-cve-2018-2844?style=social) ![Github forks](https://shields.io/github/forks/renorobert/virtualbox-cve-2018-2844?style=social) ![Github watchers](https://shields.io/github/watchers/renorobert/virtualbox-cve-2018-2844?style=social)
- github.com/LiuCan01/cve-list-pro ![Github stars](https://shields.io/github/stars/LiuCan01/cve-list-pro?style=social) ![Github forks](https://shields.io/github/forks/LiuCan01/cve-list-pro?style=social) ![Github watchers](https://shields.io/github/watchers/LiuCan01/cve-list-pro?style=social)
- github.com/CVEProject/cvelist ![Github stars](https://shields.io/github/stars/CVEProject/cvelist?style=social) ![Github forks](https://shields.io/github/forks/CVEProject/cvelist?style=social) ![Github watchers](https://shields.io/github/watchers/CVEProject/cvelist?style=social)

## hips

- github.com/daterlove/ActiveDefense ![Github stars](https://shields.io/github/stars/daterlove/ActiveDefense?style=social) ![Github forks](https://shields.io/github/forks/daterlove/ActiveDefense?style=social) ![Github watchers](https://shields.io/github/watchers/daterlove/ActiveDefense?style=social)
- github.com/secrary/DrSemu ![Github stars](https://shields.io/github/stars/secrary/DrSemu?style=social) ![Github forks](https://shields.io/github/forks/secrary/DrSemu?style=social) ![Github watchers](https://shields.io/github/watchers/secrary/DrSemu?style=social)
- github.com/godaddy/procfilter ![Github stars](https://shields.io/github/stars/godaddy/procfilter?style=social) ![Github forks](https://shields.io/github/forks/godaddy/procfilter?style=social) ![Github watchers](https://shields.io/github/watchers/godaddy/procfilter?style=social)
- github.com/BrunoMCBraga/Kernel-Whisperer ![Github stars](https://shields.io/github/stars/BrunoMCBraga/Kernel-Whisperer?style=social) ![Github forks](https://shields.io/github/forks/BrunoMCBraga/Kernel-Whisperer?style=social) ![Github watchers](https://shields.io/github/watchers/BrunoMCBraga/Kernel-Whisperer?style=social)
- malwaretips.com/threads/av-self-protection-process-c-c.66200/
- github.com/zareprj/JAV-AV-Engine ![Github stars](https://shields.io/github/stars/zareprj/JAV-AV-Engine?style=social) ![Github forks](https://shields.io/github/forks/zareprj/JAV-AV-Engine?style=social) ![Github watchers](https://shields.io/github/watchers/zareprj/JAV-AV-Engine?style=social)
- github.com/0xdabbad00/OpenHIPS ![Github stars](https://shields.io/github/stars/0xdabbad00/OpenHIPS?style=social) ![Github forks](https://shields.io/github/forks/0xdabbad00/OpenHIPS?style=social) ![Github watchers](https://shields.io/github/watchers/0xdabbad00/OpenHIPS?style=social)
- github.com/ExpLife/Norton_AntiVirus_SourceCode ![Github stars](https://shields.io/github/stars/ExpLife/Norton_AntiVirus_SourceCode?style=social) ![Github forks](https://shields.io/github/forks/ExpLife/Norton_AntiVirus_SourceCode?style=social) ![Github watchers](https://shields.io/github/watchers/ExpLife/Norton_AntiVirus_SourceCode?style=social)
- github.com/majian55555/MJAntiVirusEngine ![Github stars](https://shields.io/github/stars/majian55555/MJAntiVirusEngine?style=social) ![Github forks](https://shields.io/github/forks/majian55555/MJAntiVirusEngine?style=social) ![Github watchers](https://shields.io/github/watchers/majian55555/MJAntiVirusEngine?style=social)
- github.com/develbranch/TinyAntivirus ![Github stars](https://shields.io/github/stars/develbranch/TinyAntivirus?style=social) ![Github forks](https://shields.io/github/forks/develbranch/TinyAntivirus?style=social) ![Github watchers](https://shields.io/github/watchers/develbranch/TinyAntivirus?style=social)
- github.com/tandasat/EopMon ![Github stars](https://shields.io/github/stars/tandasat/EopMon?style=social) ![Github forks](https://shields.io/github/forks/tandasat/EopMon?style=social) ![Github watchers](https://shields.io/github/watchers/tandasat/EopMon?style=social)
- github.com/tandasat/MemoryMon ![Github stars](https://shields.io/github/stars/tandasat/MemoryMon?style=social) ![Github forks](https://shields.io/github/forks/tandasat/MemoryMon?style=social) ![Github watchers](https://shields.io/github/watchers/tandasat/MemoryMon?style=social)

## windows hypervisor

- github.com/FoxHex0ne/HyperViper ![Github stars](https://shields.io/github/stars/FoxHex0ne/HyperViper?style=social) ![Github forks](https://shields.io/github/forks/FoxHex0ne/HyperViper?style=social) ![Github watchers](https://shields.io/github/watchers/FoxHex0ne/HyperViper?style=social)
- github.com/comaeio/LiveCloudKd ![Github stars](https://shields.io/github/stars/comaeio/LiveCloudKd?style=social) ![Github forks](https://shields.io/github/forks/comaeio/LiveCloudKd?style=social) ![Github watchers](https://shields.io/github/watchers/comaeio/LiveCloudKd?style=social)
- github.com/0vercl0k/pywinhv ![Github stars](https://shields.io/github/stars/0vercl0k/pywinhv?style=social) ![Github forks](https://shields.io/github/forks/0vercl0k/pywinhv?style=social) ![Github watchers](https://shields.io/github/watchers/0vercl0k/pywinhv?style=social)
- github.com/gamozolabs/falkervisor_grilled_cheese ![Github stars](https://shields.io/github/stars/gamozolabs/falkervisor_grilled_cheese?style=social) ![Github forks](https://shields.io/github/forks/gamozolabs/falkervisor_grilled_cheese?style=social) ![Github watchers](https://shields.io/github/watchers/gamozolabs/falkervisor_grilled_cheese?style=social)
- github.com/redogwu/hyper-v ![Github stars](https://shields.io/github/stars/redogwu/hyper-v?style=social) ![Github forks](https://shields.io/github/forks/redogwu/hyper-v?style=social) ![Github watchers](https://shields.io/github/watchers/redogwu/hyper-v?style=social)
- github.com/Ekrte/hithithit ![Github stars](https://shields.io/github/stars/Ekrte/hithithit?style=social) ![Github forks](https://shields.io/github/forks/Ekrte/hithithit?style=social) ![Github watchers](https://shields.io/github/watchers/Ekrte/hithithit?style=social)
- github.com/Microsoft/FirewallEventMonitor ![Github stars](https://shields.io/github/stars/Microsoft/FirewallEventMonitor?style=social) ![Github forks](https://shields.io/github/forks/Microsoft/FirewallEventMonitor?style=social) ![Github watchers](https://shields.io/github/watchers/Microsoft/FirewallEventMonitor?style=social)
- github.com/ionescu007/Simpleator ![Github stars](https://shields.io/github/stars/ionescu007/Simpleator?style=social) ![Github forks](https://shields.io/github/forks/ionescu007/Simpleator?style=social) ![Github watchers](https://shields.io/github/watchers/ionescu007/Simpleator?style=social)
- github.com/StrikerX3/whvpclient ![Github stars](https://shields.io/github/stars/StrikerX3/whvpclient?style=social) ![Github forks](https://shields.io/github/forks/StrikerX3/whvpclient?style=social) ![Github watchers](https://shields.io/github/watchers/StrikerX3/whvpclient?style=social)

## kvm

- github.com/david942j/kvm-kernel-example ![Github stars](https://shields.io/github/stars/david942j/kvm-kernel-example?style=social) ![Github forks](https://shields.io/github/forks/david942j/kvm-kernel-example?style=social) ![Github watchers](https://shields.io/github/watchers/david942j/kvm-kernel-example?style=social)

## vt

- github.com/qq1045551070/ShotHv ![Github stars](https://shields.io/github/stars/qq1045551070/ShotHv?style=social) ![Github forks](https://shields.io/github/forks/qq1045551070/ShotHv?style=social) ![Github watchers](https://shields.io/github/watchers/qq1045551070/ShotHv?style=social)
- github.com/Air14/HyperHide (anti anti debug & x64dbg plugin) ![Github stars](https://shields.io/github/stars/Air14/HyperHide?style=social) ![Github forks](https://shields.io/github/forks/Air14/HyperHide?style=social) ![Github watchers](https://shields.io/github/watchers/Air14/HyperHide?style=social)
- github.com/amiryeshurun/HyperWin ![Github stars](https://shields.io/github/stars/amiryeshurun/HyperWin?style=social) ![Github forks](https://shields.io/github/forks/amiryeshurun/HyperWin?style=social) ![Github watchers](https://shields.io/github/watchers/amiryeshurun/HyperWin?style=social)
- github.com/sooqua/VanderLeague (hack lol) ![Github stars](https://shields.io/github/stars/sooqua/VanderLeague?style=social) ![Github forks](https://shields.io/github/forks/sooqua/VanderLeague?style=social) ![Github watchers](https://shields.io/github/watchers/sooqua/VanderLeague?style=social)
- github.com/cyberus-technology/hedron.git ![Github stars](https://shields.io/github/stars/cyberus-technology/hedron.git?style=social) ![Github forks](https://shields.io/github/forks/cyberus-technology/hedron.git?style=social) ![Github watchers](https://shields.io/github/watchers/cyberus-technology/hedron.git?style=social)
- github.com/kukrimate/grr ![Github stars](https://shields.io/github/stars/kukrimate/grr?style=social) ![Github forks](https://shields.io/github/forks/kukrimate/grr?style=social) ![Github watchers](https://shields.io/github/watchers/kukrimate/grr?style=social)
- github.com/hvmi/hvmi ![Github stars](https://shields.io/github/stars/hvmi/hvmi?style=social) ![Github forks](https://shields.io/github/forks/hvmi/hvmi?style=social) ![Github watchers](https://shields.io/github/watchers/hvmi/hvmi?style=social)
- github.com/napocahv/napoca ![Github stars](https://shields.io/github/stars/napocahv/napoca?style=social) ![Github forks](https://shields.io/github/forks/napocahv/napoca?style=social) ![Github watchers](https://shields.io/github/watchers/napocahv/napoca?style=social)
- github.com/SinaKarvandi/HyperDbg ![Github stars](https://shields.io/github/stars/SinaKarvandi/HyperDbg?style=social) ![Github forks](https://shields.io/github/forks/SinaKarvandi/HyperDbg?style=social) ![Github watchers](https://shields.io/github/watchers/SinaKarvandi/HyperDbg?style=social)
- github.com/jonomango/mango-library (🥭windows memory library aimed towards game hacking) ![Github stars](https://shields.io/github/stars/jonomango/mango-library?style=social) ![Github forks](https://shields.io/github/forks/jonomango/mango-library?style=social) ![Github watchers](https://shields.io/github/watchers/jonomango/mango-library?style=social)
- github.com/chillancezen/ZeldaOS.x86_64 ![Github stars](https://shields.io/github/stars/chillancezen/ZeldaOS.x86_64?style=social) ![Github forks](https://shields.io/github/forks/chillancezen/ZeldaOS.x86_64?style=social) ![Github watchers](https://shields.io/github/watchers/chillancezen/ZeldaOS.x86_64?style=social)
- github.com/9176324/Daat ![Github stars](https://shields.io/github/stars/9176324/Daat?style=social) ![Github forks](https://shields.io/github/forks/9176324/Daat?style=social) ![Github watchers](https://shields.io/github/watchers/9176324/Daat?style=social)
- github.com/eyalz800/zpp_hypervisor ![Github stars](https://shields.io/github/stars/eyalz800/zpp_hypervisor?style=social) ![Github forks](https://shields.io/github/forks/eyalz800/zpp_hypervisor?style=social) ![Github watchers](https://shields.io/github/watchers/eyalz800/zpp_hypervisor?style=social)
- github.com/stonedreamforest/Mirage ![Github stars](https://shields.io/github/stars/stonedreamforest/Mirage?style=social) ![Github forks](https://shields.io/github/forks/stonedreamforest/Mirage?style=social) ![Github watchers](https://shields.io/github/watchers/stonedreamforest/Mirage?style=social)
- github.com/IgorKorkin/MemoryRanger ![Github stars](https://shields.io/github/stars/IgorKorkin/MemoryRanger?style=social) ![Github forks](https://shields.io/github/forks/IgorKorkin/MemoryRanger?style=social) ![Github watchers](https://shields.io/github/watchers/IgorKorkin/MemoryRanger?style=social)
- github.com/hrbust86/SvmNest ![Github stars](https://shields.io/github/stars/hrbust86/SvmNest?style=social) ![Github forks](https://shields.io/github/forks/hrbust86/SvmNest?style=social) ![Github watchers](https://shields.io/github/watchers/hrbust86/SvmNest?style=social)
- github.com/Kelvinhack/DeviceMon ![Github stars](https://shields.io/github/stars/Kelvinhack/DeviceMon?style=social) ![Github forks](https://shields.io/github/forks/Kelvinhack/DeviceMon?style=social) ![Github watchers](https://shields.io/github/watchers/Kelvinhack/DeviceMon?style=social)
- github.com/Kelvinhack/NoTruth ![Github stars](https://shields.io/github/stars/Kelvinhack/NoTruth?style=social) ![Github forks](https://shields.io/github/forks/Kelvinhack/NoTruth?style=social) ![Github watchers](https://shields.io/github/watchers/Kelvinhack/NoTruth?style=social)
- github.com/udosteinberg/NOVA ![Github stars](https://shields.io/github/stars/udosteinberg/NOVA?style=social) ![Github forks](https://shields.io/github/forks/udosteinberg/NOVA?style=social) ![Github watchers](https://shields.io/github/watchers/udosteinberg/NOVA?style=social)
- github.com/changeofpace/VivienneVMM (stealthy debugging framework) ![Github stars](https://shields.io/github/stars/changeofpace/VivienneVMM?style=social) ![Github forks](https://shields.io/github/forks/changeofpace/VivienneVMM?style=social) ![Github watchers](https://shields.io/github/watchers/changeofpace/VivienneVMM?style=social)
- github.com/tklengyel/drakvuf ![Github stars](https://shields.io/github/stars/tklengyel/drakvuf?style=social) ![Github forks](https://shields.io/github/forks/tklengyel/drakvuf?style=social) ![Github watchers](https://shields.io/github/watchers/tklengyel/drakvuf?style=social)
- github.com/gamozolabs/applepie ![Github stars](https://shields.io/github/stars/gamozolabs/applepie?style=social) ![Github forks](https://shields.io/github/forks/gamozolabs/applepie?style=social) ![Github watchers](https://shields.io/github/watchers/gamozolabs/applepie?style=social)
- github.com/haidragon/newbluepill ![Github stars](https://shields.io/github/stars/haidragon/newbluepill?style=social) ![Github forks](https://shields.io/github/forks/haidragon/newbluepill?style=social) ![Github watchers](https://shields.io/github/watchers/haidragon/newbluepill?style=social)
- github.com/Gbps/gbhv ![Github stars](https://shields.io/github/stars/Gbps/gbhv?style=social) ![Github forks](https://shields.io/github/forks/Gbps/gbhv?style=social) ![Github watchers](https://shields.io/github/watchers/Gbps/gbhv?style=social)
- github.com/ionescu007/SimpleVisor ![Github stars](https://shields.io/github/stars/ionescu007/SimpleVisor?style=social) ![Github forks](https://shields.io/github/forks/ionescu007/SimpleVisor?style=social) ![Github watchers](https://shields.io/github/watchers/ionescu007/SimpleVisor?style=social)
- github.com/xdel/bluepillstudy ![Github stars](https://shields.io/github/stars/xdel/bluepillstudy?style=social) ![Github forks](https://shields.io/github/forks/xdel/bluepillstudy?style=social) ![Github watchers](https://shields.io/github/watchers/xdel/bluepillstudy?style=social)
- github.com/SinaKarvandi/Hypervisor-From-Scratch ![Github stars](https://shields.io/github/stars/SinaKarvandi/Hypervisor-From-Scratch?style=social) ![Github forks](https://shields.io/github/forks/SinaKarvandi/Hypervisor-From-Scratch?style=social) ![Github watchers](https://shields.io/github/watchers/SinaKarvandi/Hypervisor-From-Scratch?style=social)
- github.com/wbenny/hvpp ![Github stars](https://shields.io/github/stars/wbenny/hvpp?style=social) ![Github forks](https://shields.io/github/forks/wbenny/hvpp?style=social) ![Github watchers](https://shields.io/github/watchers/wbenny/hvpp?style=social)
- github.com/Sqdwr/Multi_CPU_VtBase ![Github stars](https://shields.io/github/stars/Sqdwr/Multi_CPU_VtBase?style=social) ![Github forks](https://shields.io/github/forks/Sqdwr/Multi_CPU_VtBase?style=social) ![Github watchers](https://shields.io/github/watchers/Sqdwr/Multi_CPU_VtBase?style=social)
- github.com/marche147/IoctlMon ![Github stars](https://shields.io/github/stars/marche147/IoctlMon?style=social) ![Github forks](https://shields.io/github/forks/marche147/IoctlMon?style=social) ![Github watchers](https://shields.io/github/watchers/marche147/IoctlMon?style=social)
- github.com/ionescu007/SimpleVisor ![Github stars](https://shields.io/github/stars/ionescu007/SimpleVisor?style=social) ![Github forks](https://shields.io/github/forks/ionescu007/SimpleVisor?style=social) ![Github watchers](https://shields.io/github/watchers/ionescu007/SimpleVisor?style=social)
- github.com/zer0mem/MiniHyperVisorProject ![Github stars](https://shields.io/github/stars/zer0mem/MiniHyperVisorProject?style=social) ![Github forks](https://shields.io/github/forks/zer0mem/MiniHyperVisorProject?style=social) ![Github watchers](https://shields.io/github/watchers/zer0mem/MiniHyperVisorProject?style=social)
- github.com/zer0mem/ShowMeYourGongFu ![Github stars](https://shields.io/github/stars/zer0mem/ShowMeYourGongFu?style=social) ![Github forks](https://shields.io/github/forks/zer0mem/ShowMeYourGongFu?style=social) ![Github watchers](https://shields.io/github/watchers/zer0mem/ShowMeYourGongFu?style=social)
- github.com/zer0mem/HyperVisor ![Github stars](https://shields.io/github/stars/zer0mem/HyperVisor?style=social) ![Github forks](https://shields.io/github/forks/zer0mem/HyperVisor?style=social) ![Github watchers](https://shields.io/github/watchers/zer0mem/HyperVisor?style=social)
- github.com/marche147/SimpleVT ![Github stars](https://shields.io/github/stars/marche147/SimpleVT?style=social) ![Github forks](https://shields.io/github/forks/marche147/SimpleVT?style=social) ![Github watchers](https://shields.io/github/watchers/marche147/SimpleVT?style=social)
- github.com/DarthTon/HyperBone ![Github stars](https://shields.io/github/stars/DarthTon/HyperBone?style=social) ![Github forks](https://shields.io/github/forks/DarthTon/HyperBone?style=social) ![Github watchers](https://shields.io/github/watchers/DarthTon/HyperBone?style=social)
- github.com/nick-kvmhv/splittlb ![Github stars](https://shields.io/github/stars/nick-kvmhv/splittlb?style=social) ![Github forks](https://shields.io/github/forks/nick-kvmhv/splittlb?style=social) ![Github watchers](https://shields.io/github/watchers/nick-kvmhv/splittlb?style=social)
- github.com/zareprj/Vmx_Prj ![Github stars](https://shields.io/github/stars/zareprj/Vmx_Prj?style=social) ![Github forks](https://shields.io/github/forks/zareprj/Vmx_Prj?style=social) ![Github watchers](https://shields.io/github/watchers/zareprj/Vmx_Prj?style=social)
- github.com/ZhuHuiBeiShaDiao/MiniVTx64 ![Github stars](https://shields.io/github/stars/ZhuHuiBeiShaDiao/MiniVTx64?style=social) ![Github forks](https://shields.io/github/forks/ZhuHuiBeiShaDiao/MiniVTx64?style=social) ![Github watchers](https://shields.io/github/watchers/ZhuHuiBeiShaDiao/MiniVTx64?style=social)
- github.com/tandasat/HyperPlatform ![Github stars](https://shields.io/github/stars/tandasat/HyperPlatform?style=social) ![Github forks](https://shields.io/github/forks/tandasat/HyperPlatform?style=social) ![Github watchers](https://shields.io/github/watchers/tandasat/HyperPlatform?style=social)
- github.com/hzqst/Syscall-Monitor ![Github stars](https://shields.io/github/stars/hzqst/Syscall-Monitor?style=social) ![Github forks](https://shields.io/github/forks/hzqst/Syscall-Monitor?style=social) ![Github watchers](https://shields.io/github/watchers/hzqst/Syscall-Monitor?style=social)
- github.com/asamy/ksm ![Github stars](https://shields.io/github/stars/asamy/ksm?style=social) ![Github forks](https://shields.io/github/forks/asamy/ksm?style=social) ![Github watchers](https://shields.io/github/watchers/asamy/ksm?style=social)
- github.com/in12hacker/VT_64_EPT ![Github stars](https://shields.io/github/stars/in12hacker/VT_64_EPT?style=social) ![Github forks](https://shields.io/github/forks/in12hacker/VT_64_EPT?style=social) ![Github watchers](https://shields.io/github/watchers/in12hacker/VT_64_EPT?style=social)
- github.com/ZhuHuiBeiShaDiao/PFHook ![Github stars](https://shields.io/github/stars/ZhuHuiBeiShaDiao/PFHook?style=social) ![Github forks](https://shields.io/github/forks/ZhuHuiBeiShaDiao/PFHook?style=social) ![Github watchers](https://shields.io/github/watchers/ZhuHuiBeiShaDiao/PFHook?style=social)
- github.com/tandasat/FU_Hypervisor ![Github stars](https://shields.io/github/stars/tandasat/FU_Hypervisor?style=social) ![Github forks](https://shields.io/github/forks/tandasat/FU_Hypervisor?style=social) ![Github watchers](https://shields.io/github/watchers/tandasat/FU_Hypervisor?style=social)
- github.com/tandasat/DdiMon ![Github stars](https://shields.io/github/stars/tandasat/DdiMon?style=social) ![Github forks](https://shields.io/github/forks/tandasat/DdiMon?style=social) ![Github watchers](https://shields.io/github/watchers/tandasat/DdiMon?style=social)
- github.com/tandasat/GuardMon ![Github stars](https://shields.io/github/stars/tandasat/GuardMon?style=social) ![Github forks](https://shields.io/github/forks/tandasat/GuardMon?style=social) ![Github watchers](https://shields.io/github/watchers/tandasat/GuardMon?style=social)
- github.com/yqsy/VT_demo ![Github stars](https://shields.io/github/stars/yqsy/VT_demo?style=social) ![Github forks](https://shields.io/github/forks/yqsy/VT_demo?style=social) ![Github watchers](https://shields.io/github/watchers/yqsy/VT_demo?style=social)
- github.com/OkazakiNagisa/VTbasedDebuggerWin7 ![Github stars](https://shields.io/github/stars/OkazakiNagisa/VTbasedDebuggerWin7?style=social) ![Github forks](https://shields.io/github/forks/OkazakiNagisa/VTbasedDebuggerWin7?style=social) ![Github watchers](https://shields.io/github/watchers/OkazakiNagisa/VTbasedDebuggerWin7?style=social)
- github.com/Ouroboros/JuusanKoubou ![Github stars](https://shields.io/github/stars/Ouroboros/JuusanKoubou?style=social) ![Github forks](https://shields.io/github/forks/Ouroboros/JuusanKoubou?style=social) ![Github watchers](https://shields.io/github/watchers/Ouroboros/JuusanKoubou?style=social)
- github.com/aaa1616/Hypervisor ![Github stars](https://shields.io/github/stars/aaa1616/Hypervisor?style=social) ![Github forks](https://shields.io/github/forks/aaa1616/Hypervisor?style=social) ![Github watchers](https://shields.io/github/watchers/aaa1616/Hypervisor?style=social)
- github.com/Nukem9/VirtualDbg ![Github stars](https://shields.io/github/stars/Nukem9/VirtualDbg?style=social) ![Github forks](https://shields.io/github/forks/Nukem9/VirtualDbg?style=social) ![Github watchers](https://shields.io/github/watchers/Nukem9/VirtualDbg?style=social)
- github.com/Nukem9/VirtualDbgHide ![Github stars](https://shields.io/github/stars/Nukem9/VirtualDbgHide?style=social) ![Github forks](https://shields.io/github/forks/Nukem9/VirtualDbgHide?style=social) ![Github watchers](https://shields.io/github/watchers/Nukem9/VirtualDbgHide?style=social)
- github.com/cheat-engine/cheat-engine ![Github stars](https://shields.io/github/stars/cheat-engine/cheat-engine?style=social) ![Github forks](https://shields.io/github/forks/cheat-engine/cheat-engine?style=social) ![Github watchers](https://shields.io/github/watchers/cheat-engine/cheat-engine?style=social)
- github.com/Kelvinhack/kHypervisor ![Github stars](https://shields.io/github/stars/Kelvinhack/kHypervisor?style=social) ![Github forks](https://shields.io/github/forks/Kelvinhack/kHypervisor?style=social) ![Github watchers](https://shields.io/github/watchers/Kelvinhack/kHypervisor?style=social)

## firmware

- github.com/platomav/MEAnalyzer ![Github stars](https://shields.io/github/stars/platomav/MEAnalyzer?style=social) ![Github forks](https://shields.io/github/forks/platomav/MEAnalyzer?style=social) ![Github watchers](https://shields.io/github/watchers/platomav/MEAnalyzer?style=social)

## fuzzer

- github.com/math1as/Windows-GDI-fuzzer ![Github stars](https://shields.io/github/stars/math1as/Windows-GDI-fuzzer?style=social) ![Github forks](https://shields.io/github/forks/math1as/Windows-GDI-fuzzer?style=social) ![Github watchers](https://shields.io/github/watchers/math1as/Windows-GDI-fuzzer?style=social)
- github.com/strongcourage/uafuzz ![Github stars](https://shields.io/github/stars/strongcourage/uafuzz?style=social) ![Github forks](https://shields.io/github/forks/strongcourage/uafuzz?style=social) ![Github watchers](https://shields.io/github/watchers/strongcourage/uafuzz?style=social)
- github.com/HyperDbg/HyperDbg (An x86-64 VT-x based Windows Debugger) ![Github stars](https://shields.io/github/stars/HyperDbg/HyperDbg?style=social) ![Github forks](https://shields.io/github/forks/HyperDbg/HyperDbg?style=social) ![Github watchers](https://shields.io/github/watchers/HyperDbg/HyperDbg?style=social)
- www.youtube.com/user/gamozolabs/videos (great fuzz courses)
- github.com/aflsmart/aflsmart ![Github stars](https://shields.io/github/stars/aflsmart/aflsmart?style=social) ![Github forks](https://shields.io/github/forks/aflsmart/aflsmart?style=social) ![Github watchers](https://shields.io/github/watchers/aflsmart/aflsmart?style=social)
- github.com/FoxHex0ne/DocParseFuzzingResources ![Github stars](https://shields.io/github/stars/FoxHex0ne/DocParseFuzzingResources?style=social) ![Github forks](https://shields.io/github/forks/FoxHex0ne/DocParseFuzzingResources?style=social) ![Github watchers](https://shields.io/github/watchers/FoxHex0ne/DocParseFuzzingResources?style=social)
- github.com/vanhauser-thc/AFLplusplus (AFLPlusPlus) ![Github stars](https://shields.io/github/stars/vanhauser-thc/AFLplusplus?style=social) ![Github forks](https://shields.io/github/forks/vanhauser-thc/AFLplusplus?style=social) ![Github watchers](https://shields.io/github/watchers/vanhauser-thc/AFLplusplus?style=social)
- github.com/zhunki/Superion ![Github stars](https://shields.io/github/stars/zhunki/Superion?style=social) ![Github forks](https://shields.io/github/forks/zhunki/Superion?style=social) ![Github watchers](https://shields.io/github/watchers/zhunki/Superion?style=social)
- github.com/uds-se/fuzzingbook ![Github stars](https://shields.io/github/stars/uds-se/fuzzingbook?style=social) ![Github forks](https://shields.io/github/forks/uds-se/fuzzingbook?style=social) ![Github watchers](https://shields.io/github/watchers/uds-se/fuzzingbook?style=social)
- github.com/wcventure/WasmFuzz ![Github stars](https://shields.io/github/stars/wcventure/WasmFuzz?style=social) ![Github forks](https://shields.io/github/forks/wcventure/WasmFuzz?style=social) ![Github watchers](https://shields.io/github/watchers/wcventure/WasmFuzz?style=social)
- github.com/wcventure/FuzzingPaper (paper) ![Github stars](https://shields.io/github/stars/wcventure/FuzzingPaper?style=social) ![Github forks](https://shields.io/github/forks/wcventure/FuzzingPaper?style=social) ![Github watchers](https://shields.io/github/watchers/wcventure/FuzzingPaper?style=social)
- github.com/FoxHex0ne/Silfen ![Github stars](https://shields.io/github/stars/FoxHex0ne/Silfen?style=social) ![Github forks](https://shields.io/github/forks/FoxHex0ne/Silfen?style=social) ![Github watchers](https://shields.io/github/watchers/FoxHex0ne/Silfen?style=social)
- bbs.pediy.com/thread-255544.htm
- bbs.pediy.com/thread-255162.htm (winafl)
- github.com/bin2415/fuzzing_paper ![Github stars](https://shields.io/github/stars/bin2415/fuzzing_paper?style=social) ![Github forks](https://shields.io/github/forks/bin2415/fuzzing_paper?style=social) ![Github watchers](https://shields.io/github/watchers/bin2415/fuzzing_paper?style=social)
- github.com/mxmssh/manul ![Github stars](https://shields.io/github/stars/mxmssh/manul?style=social) ![Github forks](https://shields.io/github/forks/mxmssh/manul?style=social) ![Github watchers](https://shields.io/github/watchers/mxmssh/manul?style=social)
- github.com/nccgroup/fuzzowski ![Github stars](https://shields.io/github/stars/nccgroup/fuzzowski?style=social) ![Github forks](https://shields.io/github/forks/nccgroup/fuzzowski?style=social) ![Github watchers](https://shields.io/github/watchers/nccgroup/fuzzowski?style=social)
- github.com/rk700/uniFuzzer (closed-source binaries fuzzer) ![Github stars](https://shields.io/github/stars/rk700/uniFuzzer?style=social) ![Github forks](https://shields.io/github/forks/rk700/uniFuzzer?style=social) ![Github watchers](https://shields.io/github/watchers/rk700/uniFuzzer?style=social)
- github.com/trailofbits/sienna-locomotive ![Github stars](https://shields.io/github/stars/trailofbits/sienna-locomotive?style=social) ![Github forks](https://shields.io/github/forks/trailofbits/sienna-locomotive?style=social) ![Github watchers](https://shields.io/github/watchers/trailofbits/sienna-locomotive?style=social)
- github.com/compsec-snu/razzer ![Github stars](https://shields.io/github/stars/compsec-snu/razzer?style=social) ![Github forks](https://shields.io/github/forks/compsec-snu/razzer?style=social) ![Github watchers](https://shields.io/github/watchers/compsec-snu/razzer?style=social)
- github.com/wcventure/FuzzingPaper ![Github stars](https://shields.io/github/stars/wcventure/FuzzingPaper?style=social) ![Github forks](https://shields.io/github/forks/wcventure/FuzzingPaper?style=social) ![Github watchers](https://shields.io/github/watchers/wcventure/FuzzingPaper?style=social)
- github.com/mwrlabs/ViridianFuzzer (fuzz Hyper-V hypercalls) ![Github stars](https://shields.io/github/stars/mwrlabs/ViridianFuzzer?style=social) ![Github forks](https://shields.io/github/forks/mwrlabs/ViridianFuzzer?style=social) ![Github watchers](https://shields.io/github/watchers/mwrlabs/ViridianFuzzer?style=social)
- github.com/GoSSIP-SJTU/TripleDoggy ![Github stars](https://shields.io/github/stars/GoSSIP-SJTU/TripleDoggy?style=social) ![Github forks](https://shields.io/github/forks/GoSSIP-SJTU/TripleDoggy?style=social) ![Github watchers](https://shields.io/github/watchers/GoSSIP-SJTU/TripleDoggy?style=social)
- github.com/payatu/EMFFuzzer ![Github stars](https://shields.io/github/stars/payatu/EMFFuzzer?style=social) ![Github forks](https://shields.io/github/forks/payatu/EMFFuzzer?style=social) ![Github watchers](https://shields.io/github/watchers/payatu/EMFFuzzer?style=social)
- github.com/googleprojectzero/bochspwn-reloaded ![Github stars](https://shields.io/github/stars/googleprojectzero/bochspwn-reloaded?style=social) ![Github forks](https://shields.io/github/forks/googleprojectzero/bochspwn-reloaded?style=social) ![Github watchers](https://shields.io/github/watchers/googleprojectzero/bochspwn-reloaded?style=social)
- github.com/googleprojectzero/p0tools ![Github stars](https://shields.io/github/stars/googleprojectzero/p0tools?style=social) ![Github forks](https://shields.io/github/forks/googleprojectzero/p0tools?style=social) ![Github watchers](https://shields.io/github/watchers/googleprojectzero/p0tools?style=social)
- github.com/wnagzihxa1n/BrowserSecurity ![Github stars](https://shields.io/github/stars/wnagzihxa1n/BrowserSecurity?style=social) ![Github forks](https://shields.io/github/forks/wnagzihxa1n/BrowserSecurity?style=social) ![Github watchers](https://shields.io/github/watchers/wnagzihxa1n/BrowserSecurity?style=social)
- github.com/Dongdongshe/neuzz ![Github stars](https://shields.io/github/stars/Dongdongshe/neuzz?style=social) ![Github forks](https://shields.io/github/forks/Dongdongshe/neuzz?style=social) ![Github watchers](https://shields.io/github/watchers/Dongdongshe/neuzz?style=social)
- github.com/nickjackson2011/study-TTF_format ![Github stars](https://shields.io/github/stars/nickjackson2011/study-TTF_format?style=social) ![Github forks](https://shields.io/github/forks/nickjackson2011/study-TTF_format?style=social) ![Github watchers](https://shields.io/github/watchers/nickjackson2011/study-TTF_format?style=social)
- github.com/oxagast/ansvif ![Github stars](https://shields.io/github/stars/oxagast/ansvif?style=social) ![Github forks](https://shields.io/github/forks/oxagast/ansvif?style=social) ![Github watchers](https://shields.io/github/watchers/oxagast/ansvif?style=social)
- github.com/hfiref0x/ROCALL ![Github stars](https://shields.io/github/stars/hfiref0x/ROCALL?style=social) ![Github forks](https://shields.io/github/forks/hfiref0x/ROCALL?style=social) ![Github watchers](https://shields.io/github/watchers/hfiref0x/ROCALL?style=social)
- github.com/bin2415/fuzzing_paper ![Github stars](https://shields.io/github/stars/bin2415/fuzzing_paper?style=social) ![Github forks](https://shields.io/github/forks/bin2415/fuzzing_paper?style=social) ![Github watchers](https://shields.io/github/watchers/bin2415/fuzzing_paper?style=social)
- github.com/CERTCC/dranzer (activex/com) ![Github stars](https://shields.io/github/stars/CERTCC/dranzer?style=social) ![Github forks](https://shields.io/github/forks/CERTCC/dranzer?style=social) ![Github watchers](https://shields.io/github/watchers/CERTCC/dranzer?style=social)
- github.com/lcatro/How-to-Read-Source-and-Fuzzing (learn fuzzer) ![Github stars](https://shields.io/github/stars/lcatro/How-to-Read-Source-and-Fuzzing?style=social) ![Github forks](https://shields.io/github/forks/lcatro/How-to-Read-Source-and-Fuzzing?style=social) ![Github watchers](https://shields.io/github/watchers/lcatro/How-to-Read-Source-and-Fuzzing?style=social)
- github.com/sogeti-esec-lab/RPCForge ![Github stars](https://shields.io/github/stars/sogeti-esec-lab/RPCForge?style=social) ![Github forks](https://shields.io/github/forks/sogeti-esec-lab/RPCForge?style=social) ![Github watchers](https://shields.io/github/watchers/sogeti-esec-lab/RPCForge?style=social)
- github.com/RootUp/BFuzz ![Github stars](https://shields.io/github/stars/RootUp/BFuzz?style=social) ![Github forks](https://shields.io/github/forks/RootUp/BFuzz?style=social) ![Github watchers](https://shields.io/github/watchers/RootUp/BFuzz?style=social)
- github.com/necst/crave ![Github stars](https://shields.io/github/stars/necst/crave?style=social) ![Github forks](https://shields.io/github/forks/necst/crave?style=social) ![Github watchers](https://shields.io/github/watchers/necst/crave?style=social)
- github.com/IOActive/FuzzNDIS ![Github stars](https://shields.io/github/stars/IOActive/FuzzNDIS?style=social) ![Github forks](https://shields.io/github/forks/IOActive/FuzzNDIS?style=social) ![Github watchers](https://shields.io/github/watchers/IOActive/FuzzNDIS?style=social)
- github.com/bee13oy/AV_Kernel_Vulns/tree/master/Zer0Con2017 ![Github stars](https://shields.io/github/stars/bee13oy/AV_Kernel_Vulns?style=social) ![Github forks](https://shields.io/github/forks/bee13oy/AV_Kernel_Vulns?style=social) ![Github watchers](https://shields.io/github/watchers/bee13oy/AV_Kernel_Vulns?style=social)
- github.com/k0keoyo/kDriver-Fuzzer (whereisk0shl.top/post/2018-01-30) ![Github stars](https://shields.io/github/stars/k0keoyo/kDriver-Fuzzer?style=social) ![Github forks](https://shields.io/github/forks/k0keoyo/kDriver-Fuzzer?style=social) ![Github watchers](https://shields.io/github/watchers/k0keoyo/kDriver-Fuzzer?style=social)
- github.com/koutto/ioctlbf ![Github stars](https://shields.io/github/stars/koutto/ioctlbf?style=social) ![Github forks](https://shields.io/github/forks/koutto/ioctlbf?style=social) ![Github watchers](https://shields.io/github/watchers/koutto/ioctlbf?style=social)
- github.com/Cr4sh/ioctlfuzzer ![Github stars](https://shields.io/github/stars/Cr4sh/ioctlfuzzer?style=social) ![Github forks](https://shields.io/github/forks/Cr4sh/ioctlfuzzer?style=social) ![Github watchers](https://shields.io/github/watchers/Cr4sh/ioctlfuzzer?style=social)
- github.com/Cr4sh/MsFontsFuzz ![Github stars](https://shields.io/github/stars/Cr4sh/MsFontsFuzz?style=social) ![Github forks](https://shields.io/github/forks/Cr4sh/MsFontsFuzz?style=social) ![Github watchers](https://shields.io/github/watchers/Cr4sh/MsFontsFuzz?style=social)
- github.com/hfiref0x/NtCall64 ![Github stars](https://shields.io/github/stars/hfiref0x/NtCall64?style=social) ![Github forks](https://shields.io/github/forks/hfiref0x/NtCall64?style=social) ![Github watchers](https://shields.io/github/watchers/hfiref0x/NtCall64?style=social)
- github.com/Rootkitsmm/Win32k-Fuzzer ![Github stars](https://shields.io/github/stars/Rootkitsmm/Win32k-Fuzzer?style=social) ![Github forks](https://shields.io/github/forks/Rootkitsmm/Win32k-Fuzzer?style=social) ![Github watchers](https://shields.io/github/watchers/Rootkitsmm/Win32k-Fuzzer?style=social)
- github.com/mwrlabs/KernelFuzzer ![Github stars](https://shields.io/github/stars/mwrlabs/KernelFuzzer?style=social) ![Github forks](https://shields.io/github/forks/mwrlabs/KernelFuzzer?style=social) ![Github watchers](https://shields.io/github/watchers/mwrlabs/KernelFuzzer?style=social)
- github.com/SignalSEC/kirlangic-ttf-fuzzer ![Github stars](https://shields.io/github/stars/SignalSEC/kirlangic-ttf-fuzzer?style=social) ![Github forks](https://shields.io/github/forks/SignalSEC/kirlangic-ttf-fuzzer?style=social) ![Github watchers](https://shields.io/github/watchers/SignalSEC/kirlangic-ttf-fuzzer?style=social)
- github.com/demi6od/Smashing_The_Browser ![Github stars](https://shields.io/github/stars/demi6od/Smashing_The_Browser?style=social) ![Github forks](https://shields.io/github/forks/demi6od/Smashing_The_Browser?style=social) ![Github watchers](https://shields.io/github/watchers/demi6od/Smashing_The_Browser?style=social)
- github.com/marche147/IoctlMon ![Github stars](https://shields.io/github/stars/marche147/IoctlMon?style=social) ![Github forks](https://shields.io/github/forks/marche147/IoctlMon?style=social) ![Github watchers](https://shields.io/github/watchers/marche147/IoctlMon?style=social)
- github.com/k0keoyo/Some-Kernel-Fuzzing-Paper ![Github stars](https://shields.io/github/stars/k0keoyo/Some-Kernel-Fuzzing-Paper?style=social) ![Github forks](https://shields.io/github/forks/k0keoyo/Some-Kernel-Fuzzing-Paper?style=social) ![Github watchers](https://shields.io/github/watchers/k0keoyo/Some-Kernel-Fuzzing-Paper?style=social)

## fuzz & vulnerability discovery learn

- github.com/Kiprey/Skr_Learning ![Github stars](https://shields.io/github/stars/Kiprey/Skr_Learning?style=social) ![Github forks](https://shields.io/github/forks/Kiprey/Skr_Learning?style=social) ![Github watchers](https://shields.io/github/watchers/Kiprey/Skr_Learning?style=social)
- kiprey.github.io/categories/

## emet

- github.com/codingtest/EMET ![Github stars](https://shields.io/github/stars/codingtest/EMET?style=social) ![Github forks](https://shields.io/github/forks/codingtest/EMET?style=social) ![Github watchers](https://shields.io/github/watchers/codingtest/EMET?style=social)

## hotpatch

- github.com/codingtest/windows_hotpatch ![Github stars](https://shields.io/github/stars/codingtest/windows_hotpatch?style=social) ![Github forks](https://shields.io/github/forks/codingtest/windows_hotpatch?style=social) ![Github watchers](https://shields.io/github/watchers/codingtest/windows_hotpatch?style=social)

## memory hack

- github.com/Empier/MemoryEditor ![Github stars](https://shields.io/github/stars/Empier/MemoryEditor?style=social) ![Github forks](https://shields.io/github/forks/Empier/MemoryEditor?style=social) ![Github watchers](https://shields.io/github/watchers/Empier/MemoryEditor?style=social)

## game

- github.com/scarsty/kys-cpp ![Github stars](https://shields.io/github/stars/scarsty/kys-cpp?style=social) ![Github forks](https://shields.io/github/forks/scarsty/kys-cpp?style=social) ![Github watchers](https://shields.io/github/watchers/scarsty/kys-cpp?style=social)

## game network accelerator

- github.com/csharpHub/aiocloud ![Github stars](https://shields.io/github/stars/csharpHub/aiocloud?style=social) ![Github forks](https://shields.io/github/forks/csharpHub/aiocloud?style=social) ![Github watchers](https://shields.io/github/watchers/csharpHub/aiocloud?style=social)

## game hack

- github.com/BeneficialCode/Game-Cheating-Tutorial ![Github stars](https://shields.io/github/stars/BeneficialCode/Game-Cheating-Tutorial?style=social) ![Github forks](https://shields.io/github/forks/BeneficialCode/Game-Cheating-Tutorial?style=social) ![Github watchers](https://shields.io/github/watchers/BeneficialCode/Game-Cheating-Tutorial?style=social)
- github.com/khang06/mhynot2.git ![Github stars](https://shields.io/github/stars/khang06/mhynot2.git?style=social) ![Github forks](https://shields.io/github/forks/khang06/mhynot2.git?style=social) ![Github watchers](https://shields.io/github/watchers/khang06/mhynot2.git?style=social)
- github.com/sooqua/VanderLeague (LOL) ![Github stars](https://shields.io/github/stars/sooqua/VanderLeague?style=social) ![Github forks](https://shields.io/github/forks/sooqua/VanderLeague?style=social) ![Github watchers](https://shields.io/github/watchers/sooqua/VanderLeague?style=social)
- github.com/Speedi13/ROP-COMPILER (VAC / PB) ![Github stars](https://shields.io/github/stars/Speedi13/ROP-COMPILER?style=social) ![Github forks](https://shields.io/github/forks/Speedi13/ROP-COMPILER?style=social) ![Github watchers](https://shields.io/github/watchers/Speedi13/ROP-COMPILER?style=social)
- github.com/Aki2k/BEDaisy(battleyes kernel driver) ![Github stars](https://shields.io/github/stars/Aki2k/BEDaisy(battleyes?style=social) ![Github forks](https://shields.io/github/forks/Aki2k/BEDaisy(battleyes?style=social) ![Github watchers](https://shields.io/github/watchers/Aki2k/BEDaisy(battleyes?style=social)
- github.com/dretax/GarHal_CSGO (csgo) ![Github stars](https://shields.io/github/stars/dretax/GarHal_CSGO?style=social) ![Github forks](https://shields.io/github/forks/dretax/GarHal_CSGO?style=social) ![Github watchers](https://shields.io/github/watchers/dretax/GarHal_CSGO?style=social)
- github.com/nbqofficial/kernel-csgo (csgo) ![Github stars](https://shields.io/github/stars/nbqofficial/kernel-csgo?style=social) ![Github forks](https://shields.io/github/forks/nbqofficial/kernel-csgo?style=social) ![Github watchers](https://shields.io/github/watchers/nbqofficial/kernel-csgo?style=social)
- www.youtube.com/playlist?list=PL8TEddGT5w_j80QNqkFwl3stUTxlHol_h (LOL)
- github.com/mq1n/BadEye (BattlEye) ![Github stars](https://shields.io/github/stars/mq1n/BadEye?style=social) ![Github forks](https://shields.io/github/forks/mq1n/BadEye?style=social) ![Github watchers](https://shields.io/github/watchers/mq1n/BadEye?style=social)
- github.com/NMan1/Rainbow-Six-Cheat ![Github stars](https://shields.io/github/stars/NMan1/Rainbow-Six-Cheat?style=social) ![Github forks](https://shields.io/github/forks/NMan1/Rainbow-Six-Cheat?style=social) ![Github watchers](https://shields.io/github/watchers/NMan1/Rainbow-Six-Cheat?style=social)
- github.com/FiYHer/How-to-create-a-csgo-cheating-program ![Github stars](https://shields.io/github/stars/FiYHer/How-to-create-a-csgo-cheating-program?style=social) ![Github forks](https://shields.io/github/forks/FiYHer/How-to-create-a-csgo-cheating-program?style=social) ![Github watchers](https://shields.io/github/watchers/FiYHer/How-to-create-a-csgo-cheating-program?style=social)
- github.com/NMan1/Internal-Rainbow-Six-Cheat ![Github stars](https://shields.io/github/stars/NMan1/Internal-Rainbow-Six-Cheat?style=social) ![Github forks](https://shields.io/github/forks/NMan1/Internal-Rainbow-Six-Cheat?style=social) ![Github watchers](https://shields.io/github/watchers/NMan1/Internal-Rainbow-Six-Cheat?style=social)
- github.com/Vaseliinikives/Fortnite-External ![Github stars](https://shields.io/github/stars/Vaseliinikives/Fortnite-External?style=social) ![Github forks](https://shields.io/github/forks/Vaseliinikives/Fortnite-External?style=social) ![Github watchers](https://shields.io/github/watchers/Vaseliinikives/Fortnite-External?style=social)
- github.com/Joona70/fortnite-cheat-source-public ![Github stars](https://shields.io/github/stars/Joona70/fortnite-cheat-source-public?style=social) ![Github forks](https://shields.io/github/forks/Joona70/fortnite-cheat-source-public?style=social) ![Github watchers](https://shields.io/github/watchers/Joona70/fortnite-cheat-source-public?style=social)
- github.com/qofeharaf/IGodsEye ![Github stars](https://shields.io/github/stars/qofeharaf/IGodsEye?style=social) ![Github forks](https://shields.io/github/forks/qofeharaf/IGodsEye?style=social) ![Github watchers](https://shields.io/github/watchers/qofeharaf/IGodsEye?style=social)
- github.com/Wando1423/Antario ![Github stars](https://shields.io/github/stars/Wando1423/Antario?style=social) ![Github forks](https://shields.io/github/forks/Wando1423/Antario?style=social) ![Github watchers](https://shields.io/github/watchers/Wando1423/Antario?style=social)
- github.com/zH4x/SoT-DLL (esp) ![Github stars](https://shields.io/github/stars/zH4x/SoT-DLL?style=social) ![Github forks](https://shields.io/github/forks/zH4x/SoT-DLL?style=social) ![Github watchers](https://shields.io/github/watchers/zH4x/SoT-DLL?style=social)
- github.com/huoji120/apex_full_cheat ![Github stars](https://shields.io/github/stars/huoji120/apex_full_cheat?style=social) ![Github forks](https://shields.io/github/forks/huoji120/apex_full_cheat?style=social) ![Github watchers](https://shields.io/github/watchers/huoji120/apex_full_cheat?style=social)
- github.com/CasualX/apexbot ![Github stars](https://shields.io/github/stars/CasualX/apexbot?style=social) ![Github forks](https://shields.io/github/forks/CasualX/apexbot?style=social) ![Github watchers](https://shields.io/github/watchers/CasualX/apexbot?style=social)
- github.com/tomLadder/Call-of-Duty-Black-Ops-III-Cheat ![Github stars](https://shields.io/github/stars/tomLadder/Call-of-Duty-Black-Ops-III-Cheat?style=social) ![Github forks](https://shields.io/github/forks/tomLadder/Call-of-Duty-Black-Ops-III-Cheat?style=social) ![Github watchers](https://shields.io/github/watchers/tomLadder/Call-of-Duty-Black-Ops-III-Cheat?style=social)
- github.com/vmcall/battleye_emulation ![Github stars](https://shields.io/github/stars/vmcall/battleye_emulation?style=social) ![Github forks](https://shields.io/github/forks/vmcall/battleye_emulation?style=social) ![Github watchers](https://shields.io/github/watchers/vmcall/battleye_emulation?style=social)
- github.com/JakeDahl/ApexStuff ![Github stars](https://shields.io/github/stars/JakeDahl/ApexStuff?style=social) ![Github forks](https://shields.io/github/forks/JakeDahl/ApexStuff?style=social) ![Github watchers](https://shields.io/github/watchers/JakeDahl/ApexStuff?style=social)
- github.com/luciouskami/LOL-CN-Anti-AntCheat ![Github stars](https://shields.io/github/stars/luciouskami/LOL-CN-Anti-AntCheat?style=social) ![Github forks](https://shields.io/github/forks/luciouskami/LOL-CN-Anti-AntCheat?style=social) ![Github watchers](https://shields.io/github/watchers/luciouskami/LOL-CN-Anti-AntCheat?style=social)
- github.com/danielkrupinski/Osiris ![Github stars](https://shields.io/github/stars/danielkrupinski/Osiris?style=social) ![Github forks](https://shields.io/github/forks/danielkrupinski/Osiris?style=social) ![Github watchers](https://shields.io/github/watchers/danielkrupinski/Osiris?style=social)
- github.com/ApexLegendsUC/anti-cheat-emulator ![Github stars](https://shields.io/github/stars/ApexLegendsUC/anti-cheat-emulator?style=social) ![Github forks](https://shields.io/github/forks/ApexLegendsUC/anti-cheat-emulator?style=social) ![Github watchers](https://shields.io/github/watchers/ApexLegendsUC/anti-cheat-emulator?style=social)
- github.com/EternityX/DEADCELL-CSGO ![Github stars](https://shields.io/github/stars/EternityX/DEADCELL-CSGO?style=social) ![Github forks](https://shields.io/github/forks/EternityX/DEADCELL-CSGO?style=social) ![Github watchers](https://shields.io/github/watchers/EternityX/DEADCELL-CSGO?style=social)
- github.com/adrianyy/EACReversing （EAC） ![Github stars](https://shields.io/github/stars/adrianyy/EACReversing?style=social) ![Github forks](https://shields.io/github/forks/adrianyy/EACReversing?style=social) ![Github watchers](https://shields.io/github/watchers/adrianyy/EACReversing?style=social)
- github.com/EquiFox/KsDumper (process dump from kernel space) ![Github stars](https://shields.io/github/stars/EquiFox/KsDumper?style=social) ![Github forks](https://shields.io/github/forks/EquiFox/KsDumper?style=social) ![Github watchers](https://shields.io/github/watchers/EquiFox/KsDumper?style=social)
- github.com/EternityX/DEADCELL-CSGO ![Github stars](https://shields.io/github/stars/EternityX/DEADCELL-CSGO?style=social) ![Github forks](https://shields.io/github/forks/EternityX/DEADCELL-CSGO?style=social) ![Github watchers](https://shields.io/github/watchers/EternityX/DEADCELL-CSGO?style=social)
- github.com/M-T3K/GameHacking ![Github stars](https://shields.io/github/stars/M-T3K/GameHacking?style=social) ![Github forks](https://shields.io/github/forks/M-T3K/GameHacking?style=social) ![Github watchers](https://shields.io/github/watchers/M-T3K/GameHacking?style=social)
- github.com/nanoric/pkn ![Github stars](https://shields.io/github/stars/nanoric/pkn?style=social) ![Github forks](https://shields.io/github/forks/nanoric/pkn?style=social) ![Github watchers](https://shields.io/github/watchers/nanoric/pkn?style=social)
- github.com/luciouskami/APEX-EACBypass ![Github stars](https://shields.io/github/stars/luciouskami/APEX-EACBypass?style=social) ![Github forks](https://shields.io/github/forks/luciouskami/APEX-EACBypass?style=social) ![Github watchers](https://shields.io/github/watchers/luciouskami/APEX-EACBypass?style=social)
- github.com/fenix01/cheatengine-library  (cheatengine library wrapper) ![Github stars](https://shields.io/github/stars/fenix01/cheatengine-library?style=social) ![Github forks](https://shields.io/github/forks/fenix01/cheatengine-library?style=social) ![Github watchers](https://shields.io/github/watchers/fenix01/cheatengine-library?style=social)
- github.com/GoodstudyChina/CSGO-Cheat ![Github stars](https://shields.io/github/stars/GoodstudyChina/CSGO-Cheat?style=social) ![Github forks](https://shields.io/github/forks/GoodstudyChina/CSGO-Cheat?style=social) ![Github watchers](https://shields.io/github/watchers/GoodstudyChina/CSGO-Cheat?style=social)
- github.com/Nixer1337/Nixware-GMOD ![Github stars](https://shields.io/github/stars/Nixer1337/Nixware-GMOD?style=social) ![Github forks](https://shields.io/github/forks/Nixer1337/Nixware-GMOD?style=social) ![Github watchers](https://shields.io/github/watchers/Nixer1337/Nixware-GMOD?style=social)
- github.com/DragonQuestHero/PUBG-PAK-Hacker (BattlEye) ![Github stars](https://shields.io/github/stars/DragonQuestHero/PUBG-PAK-Hacker?style=social) ![Github forks](https://shields.io/github/forks/DragonQuestHero/PUBG-PAK-Hacker?style=social) ![Github watchers](https://shields.io/github/watchers/DragonQuestHero/PUBG-PAK-Hacker?style=social)
- github.com/GameHackingBook/GameHackingCode ![Github stars](https://shields.io/github/stars/GameHackingBook/GameHackingCode?style=social) ![Github forks](https://shields.io/github/forks/GameHackingBook/GameHackingCode?style=social) ![Github watchers](https://shields.io/github/watchers/GameHackingBook/GameHackingCode?style=social)
- github.com/danielkrupinski/Osiris (Counter-Strike) ![Github stars](https://shields.io/github/stars/danielkrupinski/Osiris?style=social) ![Github forks](https://shields.io/github/forks/danielkrupinski/Osiris?style=social) ![Github watchers](https://shields.io/github/watchers/danielkrupinski/Osiris?style=social)
- github.com/moccajoghurt/MemWars ![Github stars](https://shields.io/github/stars/moccajoghurt/MemWars?style=social) ![Github forks](https://shields.io/github/forks/moccajoghurt/MemWars?style=social) ![Github watchers](https://shields.io/github/watchers/moccajoghurt/MemWars?style=social)
- github.com/dsasmblr/hacking-online-games ![Github stars](https://shields.io/github/stars/dsasmblr/hacking-online-games?style=social) ![Github forks](https://shields.io/github/forks/dsasmblr/hacking-online-games?style=social) ![Github watchers](https://shields.io/github/watchers/dsasmblr/hacking-online-games?style=social)
- github.com/dsasmblr/game-hacking ![Github stars](https://shields.io/github/stars/dsasmblr/game-hacking?style=social) ![Github forks](https://shields.io/github/forks/dsasmblr/game-hacking?style=social) ![Github watchers](https://shields.io/github/watchers/dsasmblr/game-hacking?style=social)
- github.com/daswareinfach/Battleye-VAC-EAC-Kernel-Bypass (BattlEye) ![Github stars](https://shields.io/github/stars/daswareinfach/Battleye-VAC-EAC-Kernel-Bypass?style=social) ![Github forks](https://shields.io/github/forks/daswareinfach/Battleye-VAC-EAC-Kernel-Bypass?style=social) ![Github watchers](https://shields.io/github/watchers/daswareinfach/Battleye-VAC-EAC-Kernel-Bypass?style=social)
- blog.his.cat/a/fuck_battleye.cat (BattlEye)
- github.com/Tai7sy/BE_Fuck (Battleye) ![Github stars](https://shields.io/github/stars/Tai7sy/BE_Fuck?style=social) ![Github forks](https://shields.io/github/forks/Tai7sy/BE_Fuck?style=social) ![Github watchers](https://shields.io/github/watchers/Tai7sy/BE_Fuck?style=social)
- github.com/Synestraa/Highcall-Library ![Github stars](https://shields.io/github/stars/Synestraa/Highcall-Library?style=social) ![Github forks](https://shields.io/github/forks/Synestraa/Highcall-Library?style=social) ![Github watchers](https://shields.io/github/watchers/Synestraa/Highcall-Library?style=social)
- github.com/cheat-engine/cheat-engine ![Github stars](https://shields.io/github/stars/cheat-engine/cheat-engine?style=social) ![Github forks](https://shields.io/github/forks/cheat-engine/cheat-engine?style=social) ![Github watchers](https://shields.io/github/watchers/cheat-engine/cheat-engine?style=social)
- github.com/DreamHacks/dreamdota ![Github stars](https://shields.io/github/stars/DreamHacks/dreamdota?style=social) ![Github forks](https://shields.io/github/forks/DreamHacks/dreamdota?style=social) ![Github watchers](https://shields.io/github/watchers/DreamHacks/dreamdota?style=social)
- github.com/yoie/NGPlug-in ![Github stars](https://shields.io/github/stars/yoie/NGPlug-in?style=social) ![Github forks](https://shields.io/github/forks/yoie/NGPlug-in?style=social) ![Github watchers](https://shields.io/github/watchers/yoie/NGPlug-in?style=social)
- github.com/DevelopKits/proj ![Github stars](https://shields.io/github/stars/DevelopKits/proj?style=social) ![Github forks](https://shields.io/github/forks/DevelopKits/proj?style=social) ![Github watchers](https://shields.io/github/watchers/DevelopKits/proj?style=social)
- github.com/VideoCardGuy/ExpTool_GUI ![Github stars](https://shields.io/github/stars/VideoCardGuy/ExpTool_GUI?style=social) ![Github forks](https://shields.io/github/forks/VideoCardGuy/ExpTool_GUI?style=social) ![Github watchers](https://shields.io/github/watchers/VideoCardGuy/ExpTool_GUI?style=social)
- github.com/VideoCardGuy/Zhihu_SimpleLog ![Github stars](https://shields.io/github/stars/VideoCardGuy/Zhihu_SimpleLog?style=social) ![Github forks](https://shields.io/github/forks/VideoCardGuy/Zhihu_SimpleLog?style=social) ![Github watchers](https://shields.io/github/watchers/VideoCardGuy/Zhihu_SimpleLog?style=social)
- github.com/VideoCardGuy/NewYuGiOh_CheatDLL_x64 ![Github stars](https://shields.io/github/stars/VideoCardGuy/NewYuGiOh_CheatDLL_x64?style=social) ![Github forks](https://shields.io/github/forks/VideoCardGuy/NewYuGiOh_CheatDLL_x64?style=social) ![Github watchers](https://shields.io/github/watchers/VideoCardGuy/NewYuGiOh_CheatDLL_x64?style=social)
- github.com/VideoCardGuy/Tetris ![Github stars](https://shields.io/github/stars/VideoCardGuy/Tetris?style=social) ![Github forks](https://shields.io/github/forks/VideoCardGuy/Tetris?style=social) ![Github watchers](https://shields.io/github/watchers/VideoCardGuy/Tetris?style=social)
- github.com/VideoCardGuy/YuGiOh ![Github stars](https://shields.io/github/stars/VideoCardGuy/YuGiOh?style=social) ![Github forks](https://shields.io/github/forks/VideoCardGuy/YuGiOh?style=social) ![Github watchers](https://shields.io/github/watchers/VideoCardGuy/YuGiOh?style=social)
- github.com/VideoCardGuy/SnakeAI ![Github stars](https://shields.io/github/stars/VideoCardGuy/SnakeAI?style=social) ![Github forks](https://shields.io/github/forks/VideoCardGuy/SnakeAI?style=social) ![Github watchers](https://shields.io/github/watchers/VideoCardGuy/SnakeAI?style=social)
- github.com/VideoCardGuy/gitAsktao ![Github stars](https://shields.io/github/stars/VideoCardGuy/gitAsktao?style=social) ![Github forks](https://shields.io/github/forks/VideoCardGuy/gitAsktao?style=social) ![Github watchers](https://shields.io/github/watchers/VideoCardGuy/gitAsktao?style=social)
- github.com/VideoCardGuy/War3Cheat ![Github stars](https://shields.io/github/stars/VideoCardGuy/War3Cheat?style=social) ![Github forks](https://shields.io/github/forks/VideoCardGuy/War3Cheat?style=social) ![Github watchers](https://shields.io/github/watchers/VideoCardGuy/War3Cheat?style=social)
- github.com/VideoCardGuy/AStar_Study ![Github stars](https://shields.io/github/stars/VideoCardGuy/AStar_Study?style=social) ![Github forks](https://shields.io/github/forks/VideoCardGuy/AStar_Study?style=social) ![Github watchers](https://shields.io/github/watchers/VideoCardGuy/AStar_Study?style=social)
- github.com/VideoCardGuy/BnsChina_SetSpeed ![Github stars](https://shields.io/github/stars/VideoCardGuy/BnsChina_SetSpeed?style=social) ![Github forks](https://shields.io/github/forks/VideoCardGuy/BnsChina_SetSpeed?style=social) ![Github watchers](https://shields.io/github/watchers/VideoCardGuy/BnsChina_SetSpeed?style=social)
- github.com/VideoCardGuy/LOLProjects ![Github stars](https://shields.io/github/stars/VideoCardGuy/LOLProjects?style=social) ![Github forks](https://shields.io/github/forks/VideoCardGuy/LOLProjects?style=social) ![Github watchers](https://shields.io/github/watchers/VideoCardGuy/LOLProjects?style=social)
- github.com/VideoCardGuy/NewYuGiOh_CheatDLL_x64 ![Github stars](https://shields.io/github/stars/VideoCardGuy/NewYuGiOh_CheatDLL_x64?style=social) ![Github forks](https://shields.io/github/forks/VideoCardGuy/NewYuGiOh_CheatDLL_x64?style=social) ![Github watchers](https://shields.io/github/watchers/VideoCardGuy/NewYuGiOh_CheatDLL_x64?style=social)
- github.com/VideoCardGuy/PictureMatchGame ![Github stars](https://shields.io/github/stars/VideoCardGuy/PictureMatchGame?style=social) ![Github forks](https://shields.io/github/forks/VideoCardGuy/PictureMatchGame?style=social) ![Github watchers](https://shields.io/github/watchers/VideoCardGuy/PictureMatchGame?style=social)
- github.com/VideoCardGuy/AutoLoginByBnsChina ![Github stars](https://shields.io/github/stars/VideoCardGuy/AutoLoginByBnsChina?style=social) ![Github forks](https://shields.io/github/forks/VideoCardGuy/AutoLoginByBnsChina?style=social) ![Github watchers](https://shields.io/github/watchers/VideoCardGuy/AutoLoginByBnsChina?style=social)
- github.com/VideoCardGuy/MemoryWatchTool ![Github stars](https://shields.io/github/stars/VideoCardGuy/MemoryWatchTool?style=social) ![Github forks](https://shields.io/github/forks/VideoCardGuy/MemoryWatchTool?style=social) ![Github watchers](https://shields.io/github/watchers/VideoCardGuy/MemoryWatchTool?style=social)
- github.com/VideoCardGuy/LOL_China ![Github stars](https://shields.io/github/stars/VideoCardGuy/LOL_China?style=social) ![Github forks](https://shields.io/github/forks/VideoCardGuy/LOL_China?style=social) ![Github watchers](https://shields.io/github/watchers/VideoCardGuy/LOL_China?style=social)
- github.com/mlghuskie/NoBastian ![Github stars](https://shields.io/github/stars/mlghuskie/NoBastian?style=social) ![Github forks](https://shields.io/github/forks/mlghuskie/NoBastian?style=social) ![Github watchers](https://shields.io/github/watchers/mlghuskie/NoBastian?style=social)
- github.com/G-E-N-E-S-I-S/BattlegroundsChams ![Github stars](https://shields.io/github/stars/G-E-N-E-S-I-S/BattlegroundsChams?style=social) ![Github forks](https://shields.io/github/forks/G-E-N-E-S-I-S/BattlegroundsChams?style=social) ![Github watchers](https://shields.io/github/watchers/G-E-N-E-S-I-S/BattlegroundsChams?style=social)
- github.com/luciouskami/XignCode3Bypass ![Github stars](https://shields.io/github/stars/luciouskami/XignCode3Bypass?style=social) ![Github forks](https://shields.io/github/forks/luciouskami/XignCode3Bypass?style=social) ![Github watchers](https://shields.io/github/watchers/luciouskami/XignCode3Bypass?style=social)
- github.com/luciouskami/CS-GO-Simple-Hack ![Github stars](https://shields.io/github/stars/luciouskami/CS-GO-Simple-Hack?style=social) ![Github forks](https://shields.io/github/forks/luciouskami/CS-GO-Simple-Hack?style=social) ![Github watchers](https://shields.io/github/watchers/luciouskami/CS-GO-Simple-Hack?style=social)
- github.com/luciouskami/load-self-mix ![Github stars](https://shields.io/github/stars/luciouskami/load-self-mix?style=social) ![Github forks](https://shields.io/github/forks/luciouskami/load-self-mix?style=social) ![Github watchers](https://shields.io/github/watchers/luciouskami/load-self-mix?style=social)
- github.com/Karaulov/WarcraftIII_DLL_126-127 ![Github stars](https://shields.io/github/stars/Karaulov/WarcraftIII_DLL_126-127?style=social) ![Github forks](https://shields.io/github/forks/Karaulov/WarcraftIII_DLL_126-127?style=social) ![Github watchers](https://shields.io/github/watchers/Karaulov/WarcraftIII_DLL_126-127?style=social)
- github.com/TonyZesto/PubgPrivXcode85 ![Github stars](https://shields.io/github/stars/TonyZesto/PubgPrivXcode85?style=social) ![Github forks](https://shields.io/github/forks/TonyZesto/PubgPrivXcode85?style=social) ![Github watchers](https://shields.io/github/watchers/TonyZesto/PubgPrivXcode85?style=social)
- github.com/luciouskami/gameguard-for-war3 ![Github stars](https://shields.io/github/stars/luciouskami/gameguard-for-war3?style=social) ![Github forks](https://shields.io/github/forks/luciouskami/gameguard-for-war3?style=social) ![Github watchers](https://shields.io/github/watchers/luciouskami/gameguard-for-war3?style=social)
- github.com/PopcornEgg/LOLChangeSkin ![Github stars](https://shields.io/github/stars/PopcornEgg/LOLChangeSkin?style=social) ![Github forks](https://shields.io/github/forks/PopcornEgg/LOLChangeSkin?style=social) ![Github watchers](https://shields.io/github/watchers/PopcornEgg/LOLChangeSkin?style=social)
- github.com/ValveSoftware/ToGL ![Github stars](https://shields.io/github/stars/ValveSoftware/ToGL?style=social) ![Github forks](https://shields.io/github/forks/ValveSoftware/ToGL?style=social) ![Github watchers](https://shields.io/github/watchers/ValveSoftware/ToGL?style=social)
- github.com/Karaulov/War3-SizeLimit-Bypass ![Github stars](https://shields.io/github/stars/Karaulov/War3-SizeLimit-Bypass?style=social) ![Github forks](https://shields.io/github/forks/Karaulov/War3-SizeLimit-Bypass?style=social) ![Github watchers](https://shields.io/github/watchers/Karaulov/War3-SizeLimit-Bypass?style=social)
- github.com/F7eak/Xenon ![Github stars](https://shields.io/github/stars/F7eak/Xenon?style=social) ![Github forks](https://shields.io/github/forks/F7eak/Xenon?style=social) ![Github watchers](https://shields.io/github/watchers/F7eak/Xenon?style=social)
- github.com/syj2010syj/All-Star-Battle-2 ![Github stars](https://shields.io/github/stars/syj2010syj/All-Star-Battle-2?style=social) ![Github forks](https://shields.io/github/forks/syj2010syj/All-Star-Battle-2?style=social) ![Github watchers](https://shields.io/github/watchers/syj2010syj/All-Star-Battle-2?style=social)

## anti cheat

- github.com/zyhp/vac3_inhibitor ![Github stars](https://shields.io/github/stars/zyhp/vac3_inhibitor?style=social) ![Github forks](https://shields.io/github/forks/zyhp/vac3_inhibitor?style=social) ![Github watchers](https://shields.io/github/watchers/zyhp/vac3_inhibitor?style=social)
- github.com/thesecretclub/CVEAC-2020 ![Github stars](https://shields.io/github/stars/thesecretclub/CVEAC-2020?style=social) ![Github forks](https://shields.io/github/forks/thesecretclub/CVEAC-2020?style=social) ![Github watchers](https://shields.io/github/watchers/thesecretclub/CVEAC-2020?style=social)
- github.com/huoji120/CSGO_CrowAntiCheat ![Github stars](https://shields.io/github/stars/huoji120/CSGO_CrowAntiCheat?style=social) ![Github forks](https://shields.io/github/forks/huoji120/CSGO_CrowAntiCheat?style=social) ![Github watchers](https://shields.io/github/watchers/huoji120/CSGO_CrowAntiCheat?style=social)
- github.com/niemand-sec/Reversing-XignCode3-Driver ![Github stars](https://shields.io/github/stars/niemand-sec/Reversing-XignCode3-Driver?style=social) ![Github forks](https://shields.io/github/forks/niemand-sec/Reversing-XignCode3-Driver?style=social) ![Github watchers](https://shields.io/github/watchers/niemand-sec/Reversing-XignCode3-Driver?style=social)
- github.com/niemand-sec/AntiCheat-Testing-Framework ![Github stars](https://shields.io/github/stars/niemand-sec/AntiCheat-Testing-Framework?style=social) ![Github forks](https://shields.io/github/forks/niemand-sec/AntiCheat-Testing-Framework?style=social) ![Github watchers](https://shields.io/github/watchers/niemand-sec/AntiCheat-Testing-Framework?style=social)
- github.com/GravitLauncher/Avanguard ![Github stars](https://shields.io/github/stars/GravitLauncher/Avanguard?style=social) ![Github forks](https://shields.io/github/forks/GravitLauncher/Avanguard?style=social) ![Github watchers](https://shields.io/github/watchers/GravitLauncher/Avanguard?style=social)
- github.com/Mouka-Yang/AntiCheatProtector ![Github stars](https://shields.io/github/stars/Mouka-Yang/AntiCheatProtector?style=social) ![Github forks](https://shields.io/github/forks/Mouka-Yang/AntiCheatProtector?style=social) ![Github watchers](https://shields.io/github/watchers/Mouka-Yang/AntiCheatProtector?style=social)
- github.com/mq1n/NoMercy ![Github stars](https://shields.io/github/stars/mq1n/NoMercy?style=social) ![Github forks](https://shields.io/github/forks/mq1n/NoMercy?style=social) ![Github watchers](https://shields.io/github/watchers/mq1n/NoMercy?style=social)
- github.com/SagaanTheEpic/Sagaan-AntiCheat-V2.0 ![Github stars](https://shields.io/github/stars/SagaanTheEpic/Sagaan-AntiCheat-V2.0?style=social) ![Github forks](https://shields.io/github/forks/SagaanTheEpic/Sagaan-AntiCheat-V2.0?style=social) ![Github watchers](https://shields.io/github/watchers/SagaanTheEpic/Sagaan-AntiCheat-V2.0?style=social)
- github.com/SagaanTheEpic/SAC-Sagaan-AntiCheat-Module- ![Github stars](https://shields.io/github/stars/SagaanTheEpic/SAC-Sagaan-AntiCheat-Module-?style=social) ![Github forks](https://shields.io/github/forks/SagaanTheEpic/SAC-Sagaan-AntiCheat-Module-?style=social) ![Github watchers](https://shields.io/github/watchers/SagaanTheEpic/SAC-Sagaan-AntiCheat-Module-?style=social)
- github.com/SagaanTheEpic/SAC-Anti-Debug ![Github stars](https://shields.io/github/stars/SagaanTheEpic/SAC-Anti-Debug?style=social) ![Github forks](https://shields.io/github/forks/SagaanTheEpic/SAC-Anti-Debug?style=social) ![Github watchers](https://shields.io/github/watchers/SagaanTheEpic/SAC-Anti-Debug?style=social)
- github.com/SagaanTheEpic/SAC-Sagaan-AntiCheat-ModuleThread ![Github stars](https://shields.io/github/stars/SagaanTheEpic/SAC-Sagaan-AntiCheat-ModuleThread?style=social) ![Github forks](https://shields.io/github/forks/SagaanTheEpic/SAC-Sagaan-AntiCheat-ModuleThread?style=social) ![Github watchers](https://shields.io/github/watchers/SagaanTheEpic/SAC-Sagaan-AntiCheat-ModuleThread?style=social)
- github.com/SagaanTheEpic/SAC-Sagaan-AntiCheat-OverlayDetector- ![Github stars](https://shields.io/github/stars/SagaanTheEpic/SAC-Sagaan-AntiCheat-OverlayDetector-?style=social) ![Github forks](https://shields.io/github/forks/SagaanTheEpic/SAC-Sagaan-AntiCheat-OverlayDetector-?style=social) ![Github watchers](https://shields.io/github/watchers/SagaanTheEpic/SAC-Sagaan-AntiCheat-OverlayDetector-?style=social)
- github.com/SagaanTheEpic/Mega-Bypasss ![Github stars](https://shields.io/github/stars/SagaanTheEpic/Mega-Bypasss?style=social) ![Github forks](https://shields.io/github/forks/SagaanTheEpic/Mega-Bypasss?style=social) ![Github watchers](https://shields.io/github/watchers/SagaanTheEpic/Mega-Bypasss?style=social)
- github.com/SagaanTheEpic/SAC-Sagaan-AntiCheat-UserMode- ![Github stars](https://shields.io/github/stars/SagaanTheEpic/SAC-Sagaan-AntiCheat-UserMode-?style=social) ![Github forks](https://shields.io/github/forks/SagaanTheEpic/SAC-Sagaan-AntiCheat-UserMode-?style=social) ![Github watchers](https://shields.io/github/watchers/SagaanTheEpic/SAC-Sagaan-AntiCheat-UserMode-?style=social)
- github.com/SagaanTheEpic/SAC-Sagaan-AntiCheat-Driver- ![Github stars](https://shields.io/github/stars/SagaanTheEpic/SAC-Sagaan-AntiCheat-Driver-?style=social) ![Github forks](https://shields.io/github/forks/SagaanTheEpic/SAC-Sagaan-AntiCheat-Driver-?style=social) ![Github watchers](https://shields.io/github/watchers/SagaanTheEpic/SAC-Sagaan-AntiCheat-Driver-?style=social)
- github.com/SagaanTheEpic/SagaanTheEpic-Millin-Hack-SMH-Kernel ![Github stars](https://shields.io/github/stars/SagaanTheEpic/SagaanTheEpic-Millin-Hack-SMH-Kernel?style=social) ![Github forks](https://shields.io/github/forks/SagaanTheEpic/SagaanTheEpic-Millin-Hack-SMH-Kernel?style=social) ![Github watchers](https://shields.io/github/watchers/SagaanTheEpic/SagaanTheEpic-Millin-Hack-SMH-Kernel?style=social)
- github.com/SagaanTheEpic/LSASS-Usermode-Bypass ![Github stars](https://shields.io/github/stars/SagaanTheEpic/LSASS-Usermode-Bypass?style=social) ![Github forks](https://shields.io/github/forks/SagaanTheEpic/LSASS-Usermode-Bypass?style=social) ![Github watchers](https://shields.io/github/watchers/SagaanTheEpic/LSASS-Usermode-Bypass?style=social)
- github.com/SagaanTheEpic/KernelMode-Bypass ![Github stars](https://shields.io/github/stars/SagaanTheEpic/KernelMode-Bypass?style=social) ![Github forks](https://shields.io/github/forks/SagaanTheEpic/KernelMode-Bypass?style=social) ![Github watchers](https://shields.io/github/watchers/SagaanTheEpic/KernelMode-Bypass?style=social)
- github.com/chinatiny/GameAntiCheat ![Github stars](https://shields.io/github/stars/chinatiny/GameAntiCheat?style=social) ![Github forks](https://shields.io/github/forks/chinatiny/GameAntiCheat?style=social) ![Github watchers](https://shields.io/github/watchers/chinatiny/GameAntiCheat?style=social)
- github.com/jnastarot/anti-cheat ![Github stars](https://shields.io/github/stars/jnastarot/anti-cheat?style=social) ![Github forks](https://shields.io/github/forks/jnastarot/anti-cheat?style=social) ![Github watchers](https://shields.io/github/watchers/jnastarot/anti-cheat?style=social)
- github.com/jnastarot/ice9 ![Github stars](https://shields.io/github/stars/jnastarot/ice9?style=social) ![Github forks](https://shields.io/github/forks/jnastarot/ice9?style=social) ![Github watchers](https://shields.io/github/watchers/jnastarot/ice9?style=social)

## software reverse

- github.com/stonedreamforest/re_avkmgr ![Github stars](https://shields.io/github/stars/stonedreamforest/re_avkmgr?style=social) ![Github forks](https://shields.io/github/forks/stonedreamforest/re_avkmgr?style=social) ![Github watchers](https://shields.io/github/watchers/stonedreamforest/re_avkmgr?style=social)
- github.com/stonedreamforest/re_sysdiag ![Github stars](https://shields.io/github/stars/stonedreamforest/re_sysdiag?style=social) ![Github forks](https://shields.io/github/forks/stonedreamforest/re_sysdiag?style=social) ![Github watchers](https://shields.io/github/watchers/stonedreamforest/re_sysdiag?style=social)

## pe protector

- github.com/TimelifeCzy/Shell_Protect (vm) ![Github stars](https://shields.io/github/stars/TimelifeCzy/Shell_Protect?style=social) ![Github forks](https://shields.io/github/forks/TimelifeCzy/Shell_Protect?style=social) ![Github watchers](https://shields.io/github/watchers/TimelifeCzy/Shell_Protect?style=social)
- github.com/93aef0ce4dd141ece6f5/Packer ![Github stars](https://shields.io/github/stars/93aef0ce4dd141ece6f5/Packer?style=social) ![Github forks](https://shields.io/github/forks/93aef0ce4dd141ece6f5/Packer?style=social) ![Github watchers](https://shields.io/github/watchers/93aef0ce4dd141ece6f5/Packer?style=social)
- github.com/devilogic/xvirus ![Github stars](https://shields.io/github/stars/devilogic/xvirus?style=social) ![Github forks](https://shields.io/github/forks/devilogic/xvirus?style=social) ![Github watchers](https://shields.io/github/watchers/devilogic/xvirus?style=social)
- github.com/nickcano/RelocBonus ![Github stars](https://shields.io/github/stars/nickcano/RelocBonus?style=social) ![Github forks](https://shields.io/github/forks/nickcano/RelocBonus?style=social) ![Github watchers](https://shields.io/github/watchers/nickcano/RelocBonus?style=social)
- github.com/jnastarot/furikuri ![Github stars](https://shields.io/github/stars/jnastarot/furikuri?style=social) ![Github forks](https://shields.io/github/forks/jnastarot/furikuri?style=social) ![Github watchers](https://shields.io/github/watchers/jnastarot/furikuri?style=social)

## unpacker

- github.com/Phat3/PINdemonium (pin) ![Github stars](https://shields.io/github/stars/Phat3/PINdemonium?style=social) ![Github forks](https://shields.io/github/forks/Phat3/PINdemonium?style=social) ![Github watchers](https://shields.io/github/watchers/Phat3/PINdemonium?style=social)
- github.com/BromiumLabs/PackerAttacker ![Github stars](https://shields.io/github/stars/BromiumLabs/PackerAttacker?style=social) ![Github forks](https://shields.io/github/forks/BromiumLabs/PackerAttacker?style=social) ![Github watchers](https://shields.io/github/watchers/BromiumLabs/PackerAttacker?style=social)
- n10info.blogspot.com/2018/03/xvolkolak-010.html

## emulate code execution

- github.com/sycurelab
- github.com/hzqst/unicorn_pe ![Github stars](https://shields.io/github/stars/hzqst/unicorn_pe?style=social) ![Github forks](https://shields.io/github/forks/hzqst/unicorn_pe?style=social) ![Github watchers](https://shields.io/github/watchers/hzqst/unicorn_pe?style=social)
- github.com/inaz2/Unico ![Github stars](https://shields.io/github/stars/inaz2/Unico?style=social) ![Github forks](https://shields.io/github/forks/inaz2/Unico?style=social) ![Github watchers](https://shields.io/github/watchers/inaz2/Unico?style=social)
- github.com/Coldzer0/Cmulator ![Github stars](https://shields.io/github/stars/Coldzer0/Cmulator?style=social) ![Github forks](https://shields.io/github/forks/Coldzer0/Cmulator?style=social) ![Github watchers](https://shields.io/github/watchers/Coldzer0/Cmulator?style=social)

## pin

- github.com/thalium/icebox ![Github stars](https://shields.io/github/stars/thalium/icebox?style=social) ![Github forks](https://shields.io/github/forks/thalium/icebox?style=social) ![Github watchers](https://shields.io/github/watchers/thalium/icebox?style=social)
- github.com/season-lab/bluepill/ ![Github stars](https://shields.io/github/stars/season-lab/bluepill?style=social) ![Github forks](https://shields.io/github/forks/season-lab/bluepill?style=social) ![Github watchers](https://shields.io/github/watchers/season-lab/bluepill?style=social)
- github.com/long123king/PE-Replay ![Github stars](https://shields.io/github/stars/long123king/PE-Replay?style=social) ![Github forks](https://shields.io/github/forks/long123king/PE-Replay?style=social) ![Github watchers](https://shields.io/github/watchers/long123king/PE-Replay?style=social)
- github.com/Fare9/ANBU ![Github stars](https://shields.io/github/stars/Fare9/ANBU?style=social) ![Github forks](https://shields.io/github/forks/Fare9/ANBU?style=social) ![Github watchers](https://shields.io/github/watchers/Fare9/ANBU?style=social)
- github.com/BreakingMalware/Selfie ![Github stars](https://shields.io/github/stars/BreakingMalware/Selfie?style=social) ![Github forks](https://shields.io/github/forks/BreakingMalware/Selfie?style=social) ![Github watchers](https://shields.io/github/watchers/BreakingMalware/Selfie?style=social)
- github.com/BreakingMalware/AVulnerabilityChecker ![Github stars](https://shields.io/github/stars/BreakingMalware/AVulnerabilityChecker?style=social) ![Github forks](https://shields.io/github/forks/BreakingMalware/AVulnerabilityChecker?style=social) ![Github watchers](https://shields.io/github/watchers/BreakingMalware/AVulnerabilityChecker?style=social)
- github.com/hasherezade/MyPinTools ![Github stars](https://shields.io/github/stars/hasherezade/MyPinTools?style=social) ![Github forks](https://shields.io/github/forks/hasherezade/MyPinTools?style=social) ![Github watchers](https://shields.io/github/watchers/hasherezade/MyPinTools?style=social)
- github.com/hasherezade/tiny_tracer ![Github stars](https://shields.io/github/stars/hasherezade/tiny_tracer?style=social) ![Github forks](https://shields.io/github/forks/hasherezade/tiny_tracer?style=social) ![Github watchers](https://shields.io/github/watchers/hasherezade/tiny_tracer?style=social)
- github.com/dyninst/dyninst ![Github stars](https://shields.io/github/stars/dyninst/dyninst?style=social) ![Github forks](https://shields.io/github/forks/dyninst/dyninst?style=social) ![Github watchers](https://shields.io/github/watchers/dyninst/dyninst?style=social)

## symbolic execution

- github.com/cea-sec/miasm ![Github stars](https://shields.io/github/stars/cea-sec/miasm?style=social) ![Github forks](https://shields.io/github/forks/cea-sec/miasm?style=social) ![Github watchers](https://shields.io/github/watchers/cea-sec/miasm?style=social)
- github.com/illera88/Ponce ![Github stars](https://shields.io/github/stars/illera88/Ponce?style=social) ![Github forks](https://shields.io/github/forks/illera88/Ponce?style=social) ![Github watchers](https://shields.io/github/watchers/illera88/Ponce?style=social)
- github.com/gaasedelen/lighthouse ![Github stars](https://shields.io/github/stars/gaasedelen/lighthouse?style=social) ![Github forks](https://shields.io/github/forks/gaasedelen/lighthouse?style=social) ![Github watchers](https://shields.io/github/watchers/gaasedelen/lighthouse?style=social)

## obfuscation

- github.com/DoctorLai/VBScript_Obfuscator ![Github stars](https://shields.io/github/stars/DoctorLai/VBScript_Obfuscator?style=social) ![Github forks](https://shields.io/github/forks/DoctorLai/VBScript_Obfuscator?style=social) ![Github watchers](https://shields.io/github/watchers/DoctorLai/VBScript_Obfuscator?style=social)

## deobfuscation

- github.com/nblog/Vm2Import ![Github stars](https://shields.io/github/stars/nblog/Vm2Import?style=social) ![Github forks](https://shields.io/github/forks/nblog/Vm2Import?style=social) ![Github watchers](https://shields.io/github/watchers/nblog/Vm2Import?style=social)
- github.com/zodiacddos/BattleEye-EasyAntiCheat-Bypasses ![Github stars](https://shields.io/github/stars/zodiacddos/BattleEye-EasyAntiCheat-Bypasses?style=social) ![Github forks](https://shields.io/github/forks/zodiacddos/BattleEye-EasyAntiCheat-Bypasses?style=social) ![Github watchers](https://shields.io/github/watchers/zodiacddos/BattleEye-EasyAntiCheat-Bypasses?style=social)
- github.com/amimo/ollvm-breaker ![Github stars](https://shields.io/github/stars/amimo/ollvm-breaker?style=social) ![Github forks](https://shields.io/github/forks/amimo/ollvm-breaker?style=social) ![Github watchers](https://shields.io/github/watchers/amimo/ollvm-breaker?style=social)
- github.com/JonathanSalwan/Tigress_protection ![Github stars](https://shields.io/github/stars/JonathanSalwan/Tigress_protection?style=social) ![Github forks](https://shields.io/github/forks/JonathanSalwan/Tigress_protection?style=social) ![Github watchers](https://shields.io/github/watchers/JonathanSalwan/Tigress_protection?style=social)
- github.com/1111joe1111/tuts (vmprotect 3+) ![Github stars](https://shields.io/github/stars/1111joe1111/tuts?style=social) ![Github forks](https://shields.io/github/forks/1111joe1111/tuts?style=social) ![Github watchers](https://shields.io/github/watchers/1111joe1111/tuts?style=social)
- github.com/F8LEFT/DecLLVM ![Github stars](https://shields.io/github/stars/F8LEFT/DecLLVM?style=social) ![Github forks](https://shields.io/github/forks/F8LEFT/DecLLVM?style=social) ![Github watchers](https://shields.io/github/watchers/F8LEFT/DecLLVM?style=social)
- github.com/mmyydd/relative-pattern ![Github stars](https://shields.io/github/stars/mmyydd/relative-pattern?style=social) ![Github forks](https://shields.io/github/forks/mmyydd/relative-pattern?style=social) ![Github watchers](https://shields.io/github/watchers/mmyydd/relative-pattern?style=social)
- github.com/SCUBSRGroup/OLLVM_Deobfuscation ![Github stars](https://shields.io/github/stars/SCUBSRGroup/OLLVM_Deobfuscation?style=social) ![Github forks](https://shields.io/github/forks/SCUBSRGroup/OLLVM_Deobfuscation?style=social) ![Github watchers](https://shields.io/github/watchers/SCUBSRGroup/OLLVM_Deobfuscation?style=social)

## taint analyse

- github.com/cea-sec/miasm (blackhat 2018) ![Github stars](https://shields.io/github/stars/cea-sec/miasm?style=social) ![Github forks](https://shields.io/github/forks/cea-sec/miasm?style=social) ![Github watchers](https://shields.io/github/watchers/cea-sec/miasm?style=social)
- bbs.pediy.com/thread-230299.htm
- bbs.pediy.com/thread-230105.htm
- bbs.pediy.com/thread-226603.htm
- bbs.pediy.com/thread-224353.htm
- bbs.pediy.com/thread-223849.htm
- github.com/airbus-seclab/bincat ![Github stars](https://shields.io/github/stars/airbus-seclab/bincat?style=social) ![Github forks](https://shields.io/github/forks/airbus-seclab/bincat?style=social) ![Github watchers](https://shields.io/github/watchers/airbus-seclab/bincat?style=social)
- github.com/SCUBSRGroup/Taint-Analyse ![Github stars](https://shields.io/github/stars/SCUBSRGroup/Taint-Analyse?style=social) ![Github forks](https://shields.io/github/forks/SCUBSRGroup/Taint-Analyse?style=social) ![Github watchers](https://shields.io/github/watchers/SCUBSRGroup/Taint-Analyse?style=social)
- github.com/airbus-seclab/bincat ![Github stars](https://shields.io/github/stars/airbus-seclab/bincat?style=social) ![Github forks](https://shields.io/github/forks/airbus-seclab/bincat?style=social) ![Github watchers](https://shields.io/github/watchers/airbus-seclab/bincat?style=social)
- github.com/SCUBSRGroup/Taint-Analyse ![Github stars](https://shields.io/github/stars/SCUBSRGroup/Taint-Analyse?style=social) ![Github forks](https://shields.io/github/forks/SCUBSRGroup/Taint-Analyse?style=social) ![Github watchers](https://shields.io/github/watchers/SCUBSRGroup/Taint-Analyse?style=social)
- github.com/piscou/FuzzWin ![Github stars](https://shields.io/github/stars/piscou/FuzzWin?style=social) ![Github forks](https://shields.io/github/forks/piscou/FuzzWin?style=social) ![Github watchers](https://shields.io/github/watchers/piscou/FuzzWin?style=social)

## bin diff

- github.com/joxeankoret/pigaios ![Github stars](https://shields.io/github/stars/joxeankoret/pigaios?style=social) ![Github forks](https://shields.io/github/forks/joxeankoret/pigaios?style=social) ![Github watchers](https://shields.io/github/watchers/joxeankoret/pigaios?style=social)
- www.zynamics.com/bindiff.html
- github.com/joxeankoret/diaphora ![Github stars](https://shields.io/github/stars/joxeankoret/diaphora?style=social) ![Github forks](https://shields.io/github/forks/joxeankoret/diaphora?style=social) ![Github watchers](https://shields.io/github/watchers/joxeankoret/diaphora?style=social)
- github.com/ExpLife/binarydiffer ![Github stars](https://shields.io/github/stars/ExpLife/binarydiffer?style=social) ![Github forks](https://shields.io/github/forks/ExpLife/binarydiffer?style=social) ![Github watchers](https://shields.io/github/watchers/ExpLife/binarydiffer?style=social)
- github.com/ExpLife/patchdiff2_ida6 ![Github stars](https://shields.io/github/stars/ExpLife/patchdiff2_ida6?style=social) ![Github forks](https://shields.io/github/forks/ExpLife/patchdiff2_ida6?style=social) ![Github watchers](https://shields.io/github/watchers/ExpLife/patchdiff2_ida6?style=social)
- github.com/ExpLife/patchdiff2 ![Github stars](https://shields.io/github/stars/ExpLife/patchdiff2?style=social) ![Github forks](https://shields.io/github/forks/ExpLife/patchdiff2?style=social) ![Github watchers](https://shields.io/github/watchers/ExpLife/patchdiff2?style=social)

## debugger

- github.com/marakew/syser ![Github stars](https://shields.io/github/stars/marakew/syser?style=social) ![Github forks](https://shields.io/github/forks/marakew/syser?style=social) ![Github watchers](https://shields.io/github/watchers/marakew/syser?style=social)

## x64dbg plugin

- github.com/horsicq
- github.com/Ahmadmansoor/AdvancedScript ![Github stars](https://shields.io/github/stars/Ahmadmansoor/AdvancedScript?style=social) ![Github forks](https://shields.io/github/forks/Ahmadmansoor/AdvancedScript?style=social) ![Github watchers](https://shields.io/github/watchers/Ahmadmansoor/AdvancedScript?style=social)
- github.com/changeofpace/Force-Page-Protection ![Github stars](https://shields.io/github/stars/changeofpace/Force-Page-Protection?style=social) ![Github forks](https://shields.io/github/forks/changeofpace/Force-Page-Protection?style=social) ![Github watchers](https://shields.io/github/watchers/changeofpace/Force-Page-Protection?style=social)
- github.com/secrary/idenLib ![Github stars](https://shields.io/github/stars/secrary/idenLib?style=social) ![Github forks](https://shields.io/github/forks/secrary/idenLib?style=social) ![Github watchers](https://shields.io/github/watchers/secrary/idenLib?style=social)
- github.com/Gbps/x64dbg-consonance-theme ![Github stars](https://shields.io/github/stars/Gbps/x64dbg-consonance-theme?style=social) ![Github forks](https://shields.io/github/forks/Gbps/x64dbg-consonance-theme?style=social) ![Github watchers](https://shields.io/github/watchers/Gbps/x64dbg-consonance-theme?style=social)
- github.com/ThunderCls/xAnalyzer ![Github stars](https://shields.io/github/stars/ThunderCls/xAnalyzer?style=social) ![Github forks](https://shields.io/github/forks/ThunderCls/xAnalyzer?style=social) ![Github watchers](https://shields.io/github/watchers/ThunderCls/xAnalyzer?style=social)
- github.com/mrexodia/TitanHide ![Github stars](https://shields.io/github/stars/mrexodia/TitanHide?style=social) ![Github forks](https://shields.io/github/forks/mrexodia/TitanHide?style=social) ![Github watchers](https://shields.io/github/watchers/mrexodia/TitanHide?style=social)
- github.com/x64dbg/InterObfu ![Github stars](https://shields.io/github/stars/x64dbg/InterObfu?style=social) ![Github forks](https://shields.io/github/forks/x64dbg/InterObfu?style=social) ![Github watchers](https://shields.io/github/watchers/x64dbg/InterObfu?style=social)
- github.com/x64dbg/ScyllaHide ![Github stars](https://shields.io/github/stars/x64dbg/ScyllaHide?style=social) ![Github forks](https://shields.io/github/forks/x64dbg/ScyllaHide?style=social) ![Github watchers](https://shields.io/github/watchers/x64dbg/ScyllaHide?style=social)
- github.com/Nukem9/SwissArmyKnife ![Github stars](https://shields.io/github/stars/Nukem9/SwissArmyKnife?style=social) ![Github forks](https://shields.io/github/forks/Nukem9/SwissArmyKnife?style=social) ![Github watchers](https://shields.io/github/watchers/Nukem9/SwissArmyKnife?style=social)
- github.com/x64dbg/x64dbg/wiki/Plugins ![Github stars](https://shields.io/github/stars/x64dbg/x64dbg?style=social) ![Github forks](https://shields.io/github/forks/x64dbg/x64dbg?style=social) ![Github watchers](https://shields.io/github/watchers/x64dbg/x64dbg?style=social)

## live kernel debug

- samsclass.info/126/proj/p12-kernel-debug-win10.htm?tdsourcetag=s_pctim_aiomsg
- gds89.wordpress.com/2010/05/19/windows-7-x64-local-and-live-kernel-debugging/

## windbg plugin

- github.com/0cch/luadbg (lua ext) ![Github stars](https://shields.io/github/stars/0cch/luadbg?style=social) ![Github forks](https://shields.io/github/forks/0cch/luadbg?style=social) ![Github watchers](https://shields.io/github/watchers/0cch/luadbg?style=social)
- github.com/repnz/windbg-cheat-sheet ![Github stars](https://shields.io/github/stars/repnz/windbg-cheat-sheet?style=social) ![Github forks](https://shields.io/github/forks/repnz/windbg-cheat-sheet?style=social) ![Github watchers](https://shields.io/github/watchers/repnz/windbg-cheat-sheet?style=social)
- github.com/long123king/tokenext ![Github stars](https://shields.io/github/stars/long123king/tokenext?style=social) ![Github forks](https://shields.io/github/forks/long123king/tokenext?style=social) ![Github watchers](https://shields.io/github/watchers/long123king/tokenext?style=social)
- github.com/long123king/grep (regular expression) ![Github stars](https://shields.io/github/stars/long123king/grep?style=social) ![Github forks](https://shields.io/github/forks/long123king/grep?style=social) ![Github watchers](https://shields.io/github/watchers/long123king/grep?style=social)
- github.com/fdiskyou/iris ![Github stars](https://shields.io/github/stars/fdiskyou/iris?style=social) ![Github forks](https://shields.io/github/forks/fdiskyou/iris?style=social) ![Github watchers](https://shields.io/github/watchers/fdiskyou/iris?style=social)
- github.com/pstolarz/dumpext (pe unpack) ![Github stars](https://shields.io/github/stars/pstolarz/dumpext?style=social) ![Github forks](https://shields.io/github/forks/pstolarz/dumpext?style=social) ![Github watchers](https://shields.io/github/watchers/pstolarz/dumpext?style=social)
- www.andreybazhan.com/debugging.html
- github.com/vallejocc/Reverse-Engineering-Arsenal/ (anti-anti_debugging winDbg scripts) ![Github stars](https://shields.io/github/stars/vallejocc/Reverse-Engineering-Arsenal?style=social) ![Github forks](https://shields.io/github/forks/vallejocc/Reverse-Engineering-Arsenal?style=social) ![Github watchers](https://shields.io/github/watchers/vallejocc/Reverse-Engineering-Arsenal?style=social)
- github.com/vagnerpilar/windbgtree (nice plugin) ![Github stars](https://shields.io/github/stars/vagnerpilar/windbgtree?style=social) ![Github forks](https://shields.io/github/forks/vagnerpilar/windbgtree?style=social) ![Github watchers](https://shields.io/github/watchers/vagnerpilar/windbgtree?style=social)
- github.com/hugsy/windbg_js_scripts (js) ![Github stars](https://shields.io/github/stars/hugsy/windbg_js_scripts?style=social) ![Github forks](https://shields.io/github/forks/hugsy/windbg_js_scripts?style=social) ![Github watchers](https://shields.io/github/watchers/hugsy/windbg_js_scripts?style=social)
- github.com/0vercl0k/windbg-scripts (js) ![Github stars](https://shields.io/github/stars/0vercl0k/windbg-scripts?style=social) ![Github forks](https://shields.io/github/forks/0vercl0k/windbg-scripts?style=social) ![Github watchers](https://shields.io/github/watchers/0vercl0k/windbg-scripts?style=social)
- github.com/REhints/WinDbg ![Github stars](https://shields.io/github/stars/REhints/WinDbg?style=social) ![Github forks](https://shields.io/github/forks/REhints/WinDbg?style=social) ![Github watchers](https://shields.io/github/watchers/REhints/WinDbg?style=social)
- github.com/jthuraisamy/DIRT ![Github stars](https://shields.io/github/stars/jthuraisamy/DIRT?style=social) ![Github forks](https://shields.io/github/forks/jthuraisamy/DIRT?style=social) ![Github watchers](https://shields.io/github/watchers/jthuraisamy/DIRT?style=social)
- github.com/OSRDrivers/penter ![Github stars](https://shields.io/github/stars/OSRDrivers/penter?style=social) ![Github forks](https://shields.io/github/forks/OSRDrivers/penter?style=social) ![Github watchers](https://shields.io/github/watchers/OSRDrivers/penter?style=social)
- github.com/OSRDrivers/windbg-exts ![Github stars](https://shields.io/github/stars/OSRDrivers/windbg-exts?style=social) ![Github forks](https://shields.io/github/forks/OSRDrivers/windbg-exts?style=social) ![Github watchers](https://shields.io/github/watchers/OSRDrivers/windbg-exts?style=social)
- github.com/panoramixor/GDIObjDump ![Github stars](https://shields.io/github/stars/panoramixor/GDIObjDump?style=social) ![Github forks](https://shields.io/github/forks/panoramixor/GDIObjDump?style=social) ![Github watchers](https://shields.io/github/watchers/panoramixor/GDIObjDump?style=social)
- codeday.me/bug/20171003/80216.html
- virtualkd.sysprogs.org/
- github.com/VincentSe/WatchTrees ![Github stars](https://shields.io/github/stars/VincentSe/WatchTrees?style=social) ![Github forks](https://shields.io/github/forks/VincentSe/WatchTrees?style=social) ![Github watchers](https://shields.io/github/watchers/VincentSe/WatchTrees?style=social)

## virtualkd

- github.com/4d61726b/VirtualKD-Redux ![Github stars](https://shields.io/github/stars/4d61726b/VirtualKD-Redux?style=social) ![Github forks](https://shields.io/github/forks/4d61726b/VirtualKD-Redux?style=social) ![Github watchers](https://shields.io/github/watchers/4d61726b/VirtualKD-Redux?style=social)

## ida script & plugin

- github.com/fireeye/FIDL ![Github stars](https://shields.io/github/stars/fireeye/FIDL?style=social) ![Github forks](https://shields.io/github/forks/fireeye/FIDL?style=social) ![Github watchers](https://shields.io/github/watchers/fireeye/FIDL?style=social)
- github.com/mefistotelis/ida-pro-loadmap ![Github stars](https://shields.io/github/stars/mefistotelis/ida-pro-loadmap?style=social) ![Github forks](https://shields.io/github/forks/mefistotelis/ida-pro-loadmap?style=social) ![Github watchers](https://shields.io/github/watchers/mefistotelis/ida-pro-loadmap?style=social)
- github.com/ampotos/dynStruct ![Github stars](https://shields.io/github/stars/ampotos/dynStruct?style=social) ![Github forks](https://shields.io/github/forks/ampotos/dynStruct?style=social) ![Github watchers](https://shields.io/github/watchers/ampotos/dynStruct?style=social)
- github.com/patois/HRDevHelper ![Github stars](https://shields.io/github/stars/patois/HRDevHelper?style=social) ![Github forks](https://shields.io/github/forks/patois/HRDevHelper?style=social) ![Github watchers](https://shields.io/github/watchers/patois/HRDevHelper?style=social)
- github.com/0xeb/ida-qscripts (easy developing script) ![Github stars](https://shields.io/github/stars/0xeb/ida-qscripts?style=social) ![Github forks](https://shields.io/github/forks/0xeb/ida-qscripts?style=social) ![Github watchers](https://shields.io/github/watchers/0xeb/ida-qscripts?style=social)
- github.com/google/binexport ![Github stars](https://shields.io/github/stars/google/binexport?style=social) ![Github forks](https://shields.io/github/forks/google/binexport?style=social) ![Github watchers](https://shields.io/github/watchers/google/binexport?style=social)
- github.com/nihilus/ida-pro-swf ![Github stars](https://shields.io/github/stars/nihilus/ida-pro-swf?style=social) ![Github forks](https://shields.io/github/forks/nihilus/ida-pro-swf?style=social) ![Github watchers](https://shields.io/github/watchers/nihilus/ida-pro-swf?style=social)
- github.com/ax330d/hrdev ![Github stars](https://shields.io/github/stars/ax330d/hrdev?style=social) ![Github forks](https://shields.io/github/forks/ax330d/hrdev?style=social) ![Github watchers](https://shields.io/github/watchers/ax330d/hrdev?style=social)
- github.com/ax330d/ida_pdb_loader ![Github stars](https://shields.io/github/stars/ax330d/ida_pdb_loader?style=social) ![Github forks](https://shields.io/github/forks/ax330d/ida_pdb_loader?style=social) ![Github watchers](https://shields.io/github/watchers/ax330d/ida_pdb_loader?style=social)
- github.com/ax330d/functions-plus ![Github stars](https://shields.io/github/stars/ax330d/functions-plus?style=social) ![Github forks](https://shields.io/github/forks/ax330d/functions-plus?style=social) ![Github watchers](https://shields.io/github/watchers/ax330d/functions-plus?style=social)
- github.com/ecx86/classinformer-ida7 ![Github stars](https://shields.io/github/stars/ecx86/classinformer-ida7?style=social) ![Github forks](https://shields.io/github/forks/ecx86/classinformer-ida7?style=social) ![Github watchers](https://shields.io/github/watchers/ecx86/classinformer-ida7?style=social)
- github.com/IOActive/kmdf_re ![Github stars](https://shields.io/github/stars/IOActive/kmdf_re?style=social) ![Github forks](https://shields.io/github/forks/IOActive/kmdf_re?style=social) ![Github watchers](https://shields.io/github/watchers/IOActive/kmdf_re?style=social)
- github.com/a1ext/labeless ![Github stars](https://shields.io/github/stars/a1ext/labeless?style=social) ![Github forks](https://shields.io/github/forks/a1ext/labeless?style=social) ![Github watchers](https://shields.io/github/watchers/a1ext/labeless?style=social)
- github.com/kkHAIKE/tinyidb ![Github stars](https://shields.io/github/stars/kkHAIKE/tinyidb?style=social) ![Github forks](https://shields.io/github/forks/kkHAIKE/tinyidb?style=social) ![Github watchers](https://shields.io/github/watchers/kkHAIKE/tinyidb?style=social)
- github.com/RolfRolles/HexRaysDeob (deobfuscate) ![Github stars](https://shields.io/github/stars/RolfRolles/HexRaysDeob?style=social) ![Github forks](https://shields.io/github/forks/RolfRolles/HexRaysDeob?style=social) ![Github watchers](https://shields.io/github/watchers/RolfRolles/HexRaysDeob?style=social)
- github.com/icewall/BinDiffFilter ![Github stars](https://shields.io/github/stars/icewall/BinDiffFilter?style=social) ![Github forks](https://shields.io/github/forks/icewall/BinDiffFilter?style=social) ![Github watchers](https://shields.io/github/watchers/icewall/BinDiffFilter?style=social)
- github.com/devttys0/ida/ ![Github stars](https://shields.io/github/stars/devttys0/ida?style=social) ![Github forks](https://shields.io/github/forks/devttys0/ida?style=social) ![Github watchers](https://shields.io/github/watchers/devttys0/ida?style=social)
- github.com/dude719/SigMaker-x64 (pat2sig) ![Github stars](https://shields.io/github/stars/dude719/SigMaker-x64?style=social) ![Github forks](https://shields.io/github/forks/dude719/SigMaker-x64?style=social) ![Github watchers](https://shields.io/github/watchers/dude719/SigMaker-x64?style=social)
- github.com/fireeye/flare-ida    (idb2pat) ![Github stars](https://shields.io/github/stars/fireeye/flare-ida?style=social) ![Github forks](https://shields.io/github/forks/fireeye/flare-ida?style=social) ![Github watchers](https://shields.io/github/watchers/fireeye/flare-ida?style=social)
- zznop.github.io/bnida/
- github.com/zyantific/IDASkins ![Github stars](https://shields.io/github/stars/zyantific/IDASkins?style=social) ![Github forks](https://shields.io/github/forks/zyantific/IDASkins?style=social) ![Github watchers](https://shields.io/github/watchers/zyantific/IDASkins?style=social)
- github.com/eugeii/ida-consonance ![Github stars](https://shields.io/github/stars/eugeii/ida-consonance?style=social) ![Github forks](https://shields.io/github/forks/eugeii/ida-consonance?style=social) ![Github watchers](https://shields.io/github/watchers/eugeii/ida-consonance?style=social)
- github.com/mwrlabs/win_driver_plugin ![Github stars](https://shields.io/github/stars/mwrlabs/win_driver_plugin?style=social) ![Github forks](https://shields.io/github/forks/mwrlabs/win_driver_plugin?style=social) ![Github watchers](https://shields.io/github/watchers/mwrlabs/win_driver_plugin?style=social)
- github.com/igogo-x86/HexRaysPyTools ![Github stars](https://shields.io/github/stars/igogo-x86/HexRaysPyTools?style=social) ![Github forks](https://shields.io/github/forks/igogo-x86/HexRaysPyTools?style=social) ![Github watchers](https://shields.io/github/watchers/igogo-x86/HexRaysPyTools?style=social)
- github.com/techbliss/Python_editor ![Github stars](https://shields.io/github/stars/techbliss/Python_editor?style=social) ![Github forks](https://shields.io/github/forks/techbliss/Python_editor?style=social) ![Github watchers](https://shields.io/github/watchers/techbliss/Python_editor?style=social)
- github.com/tmr232/Sark ![Github stars](https://shields.io/github/stars/tmr232/Sark?style=social) ![Github forks](https://shields.io/github/forks/tmr232/Sark?style=social) ![Github watchers](https://shields.io/github/watchers/tmr232/Sark?style=social)
- sark.readthedocs.io/en/latest/debugging.html
- bbs.pediy.com/thread-224627.htm (wing debugging idapython script)

## ida sig maker

- github.com/wanttobeno/IDASignMaker ![Github stars](https://shields.io/github/stars/wanttobeno/IDASignMaker?style=social) ![Github forks](https://shields.io/github/forks/wanttobeno/IDASignMaker?style=social) ![Github watchers](https://shields.io/github/watchers/wanttobeno/IDASignMaker?style=social)
- blog.csdn.net/lixiangminghate/article/details/81352205

## idapython

- github.com/Chordp/PatternGen (Pattern) ![Github stars](https://shields.io/github/stars/Chordp/PatternGen?style=social) ![Github forks](https://shields.io/github/forks/Chordp/PatternGen?style=social) ![Github watchers](https://shields.io/github/watchers/Chordp/PatternGen?style=social)
- github.com/inforion/idapython-cheatsheet ![Github stars](https://shields.io/github/stars/inforion/idapython-cheatsheet?style=social) ![Github forks](https://shields.io/github/forks/inforion/idapython-cheatsheet?style=social) ![Github watchers](https://shields.io/github/watchers/inforion/idapython-cheatsheet?style=social)
- github.com/thalium/idatag ![Github stars](https://shields.io/github/stars/thalium/idatag?style=social) ![Github forks](https://shields.io/github/forks/thalium/idatag?style=social) ![Github watchers](https://shields.io/github/watchers/thalium/idatag?style=social)
- github.com/sophoslabs/WebAssembly ![Github stars](https://shields.io/github/stars/sophoslabs/WebAssembly?style=social) ![Github forks](https://shields.io/github/forks/sophoslabs/WebAssembly?style=social) ![Github watchers](https://shields.io/github/watchers/sophoslabs/WebAssembly?style=social)
- github.com/howmp/COMFinder ![Github stars](https://shields.io/github/stars/howmp/COMFinder?style=social) ![Github forks](https://shields.io/github/forks/howmp/COMFinder?style=social) ![Github watchers](https://shields.io/github/watchers/howmp/COMFinder?style=social)
- github.com/maddiestone/IDAPythonEmbeddedToolkit ![Github stars](https://shields.io/github/stars/maddiestone/IDAPythonEmbeddedToolkit?style=social) ![Github forks](https://shields.io/github/forks/maddiestone/IDAPythonEmbeddedToolkit?style=social) ![Github watchers](https://shields.io/github/watchers/maddiestone/IDAPythonEmbeddedToolkit?style=social)
- github.com/zyantific/IDASkins ![Github stars](https://shields.io/github/stars/zyantific/IDASkins?style=social) ![Github forks](https://shields.io/github/forks/zyantific/IDASkins?style=social) ![Github watchers](https://shields.io/github/watchers/zyantific/IDASkins?style=social)
- github.com/ynvb/DIE ![Github stars](https://shields.io/github/stars/ynvb/DIE?style=social) ![Github forks](https://shields.io/github/forks/ynvb/DIE?style=social) ![Github watchers](https://shields.io/github/watchers/ynvb/DIE?style=social)
- github.com/nologic/idaref ![Github stars](https://shields.io/github/stars/nologic/idaref?style=social) ![Github forks](https://shields.io/github/forks/nologic/idaref?style=social) ![Github watchers](https://shields.io/github/watchers/nologic/idaref?style=social)
- github.com/anatolikalysch/VMAttack ![Github stars](https://shields.io/github/stars/anatolikalysch/VMAttack?style=social) ![Github forks](https://shields.io/github/forks/anatolikalysch/VMAttack?style=social) ![Github watchers](https://shields.io/github/watchers/anatolikalysch/VMAttack?style=social)
- github.com/36hours/idaemu ![Github stars](https://shields.io/github/stars/36hours/idaemu?style=social) ![Github forks](https://shields.io/github/forks/36hours/idaemu?style=social) ![Github watchers](https://shields.io/github/watchers/36hours/idaemu?style=social)
- github.com/gaasedelen/lighthouse ![Github stars](https://shields.io/github/stars/gaasedelen/lighthouse?style=social) ![Github forks](https://shields.io/github/forks/gaasedelen/lighthouse?style=social) ![Github watchers](https://shields.io/github/watchers/gaasedelen/lighthouse?style=social)
- github.com/avast-tl/retdec-idaplugin ![Github stars](https://shields.io/github/stars/avast-tl/retdec-idaplugin?style=social) ![Github forks](https://shields.io/github/forks/avast-tl/retdec-idaplugin?style=social) ![Github watchers](https://shields.io/github/watchers/avast-tl/retdec-idaplugin?style=social)
- github.com/1111joe1111/ida_ea ![Github stars](https://shields.io/github/stars/1111joe1111/ida_ea?style=social) ![Github forks](https://shields.io/github/forks/1111joe1111/ida_ea?style=social) ![Github watchers](https://shields.io/github/watchers/1111joe1111/ida_ea?style=social)
- github.com/eugeii/ida-consonance ![Github stars](https://shields.io/github/stars/eugeii/ida-consonance?style=social) ![Github forks](https://shields.io/github/forks/eugeii/ida-consonance?style=social) ![Github watchers](https://shields.io/github/watchers/eugeii/ida-consonance?style=social)
- github.com/IDArlingTeam/IDArling ![Github stars](https://shields.io/github/stars/IDArlingTeam/IDArling?style=social) ![Github forks](https://shields.io/github/forks/IDArlingTeam/IDArling?style=social) ![Github watchers](https://shields.io/github/watchers/IDArlingTeam/IDArling?style=social)
- github.com/aaronportnoy/toolbag ![Github stars](https://shields.io/github/stars/aaronportnoy/toolbag?style=social) ![Github forks](https://shields.io/github/forks/aaronportnoy/toolbag?style=social) ![Github watchers](https://shields.io/github/watchers/aaronportnoy/toolbag?style=social)
- github.com/L4ys/LazyIDA ![Github stars](https://shields.io/github/stars/L4ys/LazyIDA?style=social) ![Github forks](https://shields.io/github/forks/L4ys/LazyIDA?style=social) ![Github watchers](https://shields.io/github/watchers/L4ys/LazyIDA?style=social)
- github.com/push0ebp/sig-database ![Github stars](https://shields.io/github/stars/push0ebp/sig-database?style=social) ![Github forks](https://shields.io/github/forks/push0ebp/sig-database?style=social) ![Github watchers](https://shields.io/github/watchers/push0ebp/sig-database?style=social)
- github.com/igogo-x86/HexRaysPyTools ![Github stars](https://shields.io/github/stars/igogo-x86/HexRaysPyTools?style=social) ![Github forks](https://shields.io/github/forks/igogo-x86/HexRaysPyTools?style=social) ![Github watchers](https://shields.io/github/watchers/igogo-x86/HexRaysPyTools?style=social)
- github.com/intezer/docker-ida ![Github stars](https://shields.io/github/stars/intezer/docker-ida?style=social) ![Github forks](https://shields.io/github/forks/intezer/docker-ida?style=social) ![Github watchers](https://shields.io/github/watchers/intezer/docker-ida?style=social)
- github.com/keystone-engine/keypatch ![Github stars](https://shields.io/github/stars/keystone-engine/keypatch?style=social) ![Github forks](https://shields.io/github/forks/keystone-engine/keypatch?style=social) ![Github watchers](https://shields.io/github/watchers/keystone-engine/keypatch?style=social)
- github.com/dzzie/IDACompare ![Github stars](https://shields.io/github/stars/dzzie/IDACompare?style=social) ![Github forks](https://shields.io/github/forks/dzzie/IDACompare?style=social) ![Github watchers](https://shields.io/github/watchers/dzzie/IDACompare?style=social)
- github.com/snare/ida-efiutils ![Github stars](https://shields.io/github/stars/snare/ida-efiutils?style=social) ![Github forks](https://shields.io/github/forks/snare/ida-efiutils?style=social) ![Github watchers](https://shields.io/github/watchers/snare/ida-efiutils?style=social)
- github.com/zachriggle/ida-splode ![Github stars](https://shields.io/github/stars/zachriggle/ida-splode?style=social) ![Github forks](https://shields.io/github/forks/zachriggle/ida-splode?style=social) ![Github watchers](https://shields.io/github/watchers/zachriggle/ida-splode?style=social)
- github.com/nccgroup/idahunt ![Github stars](https://shields.io/github/stars/nccgroup/idahunt?style=social) ![Github forks](https://shields.io/github/forks/nccgroup/idahunt?style=social) ![Github watchers](https://shields.io/github/watchers/nccgroup/idahunt?style=social)
- github.com/iphelix/ida-sploiter ![Github stars](https://shields.io/github/stars/iphelix/ida-sploiter?style=social) ![Github forks](https://shields.io/github/forks/iphelix/ida-sploiter?style=social) ![Github watchers](https://shields.io/github/watchers/iphelix/ida-sploiter?style=social)
- github.com/ALSchwalm/dwarfexport ![Github stars](https://shields.io/github/stars/ALSchwalm/dwarfexport?style=social) ![Github forks](https://shields.io/github/forks/ALSchwalm/dwarfexport?style=social) ![Github watchers](https://shields.io/github/watchers/ALSchwalm/dwarfexport?style=social)
- github.com/Maktm/FLIRTDB ![Github stars](https://shields.io/github/stars/Maktm/FLIRTDB?style=social) ![Github forks](https://shields.io/github/forks/Maktm/FLIRTDB?style=social) ![Github watchers](https://shields.io/github/watchers/Maktm/FLIRTDB?style=social)
- github.com/strazzere/golang_loader_assist ![Github stars](https://shields.io/github/stars/strazzere/golang_loader_assist?style=social) ![Github forks](https://shields.io/github/forks/strazzere/golang_loader_assist?style=social) ![Github watchers](https://shields.io/github/watchers/strazzere/golang_loader_assist?style=social)
- github.com/Ga-ryo/IDAFuzzy ![Github stars](https://shields.io/github/stars/Ga-ryo/IDAFuzzy?style=social) ![Github forks](https://shields.io/github/forks/Ga-ryo/IDAFuzzy?style=social) ![Github watchers](https://shields.io/github/watchers/Ga-ryo/IDAFuzzy?style=social)
- github.com/duo-labs/idapython ![Github stars](https://shields.io/github/stars/duo-labs/idapython?style=social) ![Github forks](https://shields.io/github/forks/duo-labs/idapython?style=social) ![Github watchers](https://shields.io/github/watchers/duo-labs/idapython?style=social)
- github.com/polymorf/findcrypt-yara ![Github stars](https://shields.io/github/stars/polymorf/findcrypt-yara?style=social) ![Github forks](https://shields.io/github/forks/polymorf/findcrypt-yara?style=social) ![Github watchers](https://shields.io/github/watchers/polymorf/findcrypt-yara?style=social)
- github.com/patois/IDACyber ![Github stars](https://shields.io/github/stars/patois/IDACyber?style=social) ![Github forks](https://shields.io/github/forks/patois/IDACyber?style=social) ![Github watchers](https://shields.io/github/watchers/patois/IDACyber?style=social)
- github.com/F8LEFT/DecLLVM ![Github stars](https://shields.io/github/stars/F8LEFT/DecLLVM?style=social) ![Github forks](https://shields.io/github/forks/F8LEFT/DecLLVM?style=social) ![Github watchers](https://shields.io/github/watchers/F8LEFT/DecLLVM?style=social)
- github.com/RobinDavid/idasec ![Github stars](https://shields.io/github/stars/RobinDavid/idasec?style=social) ![Github forks](https://shields.io/github/forks/RobinDavid/idasec?style=social) ![Github watchers](https://shields.io/github/watchers/RobinDavid/idasec?style=social)
- github.com/tboox/vm86 ![Github stars](https://shields.io/github/stars/tboox/vm86?style=social) ![Github forks](https://shields.io/github/forks/tboox/vm86?style=social) ![Github watchers](https://shields.io/github/watchers/tboox/vm86?style=social)
- github.com/siberas/IDA2Sym ![Github stars](https://shields.io/github/stars/siberas/IDA2Sym?style=social) ![Github forks](https://shields.io/github/forks/siberas/IDA2Sym?style=social) ![Github watchers](https://shields.io/github/watchers/siberas/IDA2Sym?style=social)
- github.com/sibears/IDAGolangHelper ![Github stars](https://shields.io/github/stars/sibears/IDAGolangHelper?style=social) ![Github forks](https://shields.io/github/forks/sibears/IDAGolangHelper?style=social) ![Github watchers](https://shields.io/github/watchers/sibears/IDAGolangHelper?style=social)
- github.com/tmr232/IDABuddy ![Github stars](https://shields.io/github/stars/tmr232/IDABuddy?style=social) ![Github forks](https://shields.io/github/forks/tmr232/IDABuddy?style=social) ![Github watchers](https://shields.io/github/watchers/tmr232/IDABuddy?style=social)
- github.com/zyantific/REtypedef ![Github stars](https://shields.io/github/stars/zyantific/REtypedef?style=social) ![Github forks](https://shields.io/github/forks/zyantific/REtypedef?style=social) ![Github watchers](https://shields.io/github/watchers/zyantific/REtypedef?style=social)
- github.com/nihilus/IDA_Signsrch ![Github stars](https://shields.io/github/stars/nihilus/IDA_Signsrch?style=social) ![Github forks](https://shields.io/github/forks/nihilus/IDA_Signsrch?style=social) ![Github watchers](https://shields.io/github/watchers/nihilus/IDA_Signsrch?style=social)
- github.com/ax330d/ida_pdb_loader ![Github stars](https://shields.io/github/stars/ax330d/ida_pdb_loader?style=social) ![Github forks](https://shields.io/github/forks/ax330d/ida_pdb_loader?style=social) ![Github watchers](https://shields.io/github/watchers/ax330d/ida_pdb_loader?style=social)
- github.com/alexander-hanel/idapython6to7 ![Github stars](https://shields.io/github/stars/alexander-hanel/idapython6to7?style=social) ![Github forks](https://shields.io/github/forks/alexander-hanel/idapython6to7?style=social) ![Github watchers](https://shields.io/github/watchers/alexander-hanel/idapython6to7?style=social)
- github.com/nektra/vtbl-ida-pro-plugin ![Github stars](https://shields.io/github/stars/nektra/vtbl-ida-pro-plugin?style=social) ![Github forks](https://shields.io/github/forks/nektra/vtbl-ida-pro-plugin?style=social) ![Github watchers](https://shields.io/github/watchers/nektra/vtbl-ida-pro-plugin?style=social)
- github.com/wirepair/IDAPinLogger ![Github stars](https://shields.io/github/stars/wirepair/IDAPinLogger?style=social) ![Github forks](https://shields.io/github/forks/wirepair/IDAPinLogger?style=social) ![Github watchers](https://shields.io/github/watchers/wirepair/IDAPinLogger?style=social)
- github.com/BinaryAnalysisPlatform/bap-ida-python ![Github stars](https://shields.io/github/stars/BinaryAnalysisPlatform/bap-ida-python?style=social) ![Github forks](https://shields.io/github/forks/BinaryAnalysisPlatform/bap-ida-python?style=social) ![Github watchers](https://shields.io/github/watchers/BinaryAnalysisPlatform/bap-ida-python?style=social)
- github.com/alexander-pick/patchdiff2_ida6 ![Github stars](https://shields.io/github/stars/alexander-pick/patchdiff2_ida6?style=social) ![Github forks](https://shields.io/github/forks/alexander-pick/patchdiff2_ida6?style=social) ![Github watchers](https://shields.io/github/watchers/alexander-pick/patchdiff2_ida6?style=social)
- github.com/ecx86/classinformer-ida7 ![Github stars](https://shields.io/github/stars/ecx86/classinformer-ida7?style=social) ![Github forks](https://shields.io/github/forks/ecx86/classinformer-ida7?style=social) ![Github watchers](https://shields.io/github/watchers/ecx86/classinformer-ida7?style=social)
- github.com/nccgroup/SusanRTTI ![Github stars](https://shields.io/github/stars/nccgroup/SusanRTTI?style=social) ![Github forks](https://shields.io/github/forks/nccgroup/SusanRTTI?style=social) ![Github watchers](https://shields.io/github/watchers/nccgroup/SusanRTTI?style=social)
- github.com/gaasedelen/prefix ![Github stars](https://shields.io/github/stars/gaasedelen/prefix?style=social) ![Github forks](https://shields.io/github/forks/gaasedelen/prefix?style=social) ![Github watchers](https://shields.io/github/watchers/gaasedelen/prefix?style=social)
- github.com/andreafioraldi/IDAngr ![Github stars](https://shields.io/github/stars/andreafioraldi/IDAngr?style=social) ![Github forks](https://shields.io/github/forks/andreafioraldi/IDAngr?style=social) ![Github watchers](https://shields.io/github/watchers/andreafioraldi/IDAngr?style=social)
- github.com/Cr4sh/IDA-VMware-GDB ![Github stars](https://shields.io/github/stars/Cr4sh/IDA-VMware-GDB?style=social) ![Github forks](https://shields.io/github/forks/Cr4sh/IDA-VMware-GDB?style=social) ![Github watchers](https://shields.io/github/watchers/Cr4sh/IDA-VMware-GDB?style=social)
- github.com/Comsecuris/ida_strcluster ![Github stars](https://shields.io/github/stars/Comsecuris/ida_strcluster?style=social) ![Github forks](https://shields.io/github/forks/Comsecuris/ida_strcluster?style=social) ![Github watchers](https://shields.io/github/watchers/Comsecuris/ida_strcluster?style=social)
- github.com/airbus-seclab/bincat ![Github stars](https://shields.io/github/stars/airbus-seclab/bincat?style=social) ![Github forks](https://shields.io/github/forks/airbus-seclab/bincat?style=social) ![Github watchers](https://shields.io/github/watchers/airbus-seclab/bincat?style=social)
- github.com/a1ext/auto_re ![Github stars](https://shields.io/github/stars/a1ext/auto_re?style=social) ![Github forks](https://shields.io/github/forks/a1ext/auto_re?style=social) ![Github watchers](https://shields.io/github/watchers/a1ext/auto_re?style=social)
- github.com/gynophage/solarized_ida ![Github stars](https://shields.io/github/stars/gynophage/solarized_ida?style=social) ![Github forks](https://shields.io/github/forks/gynophage/solarized_ida?style=social) ![Github watchers](https://shields.io/github/watchers/gynophage/solarized_ida?style=social)
- github.com/luorui110120/IDAplugins ![Github stars](https://shields.io/github/stars/luorui110120/IDAplugins?style=social) ![Github forks](https://shields.io/github/forks/luorui110120/IDAplugins?style=social) ![Github watchers](https://shields.io/github/watchers/luorui110120/IDAplugins?style=social)
- github.com/0xItx/ida_nightfall ![Github stars](https://shields.io/github/stars/0xItx/ida_nightfall?style=social) ![Github forks](https://shields.io/github/forks/0xItx/ida_nightfall?style=social) ![Github watchers](https://shields.io/github/watchers/0xItx/ida_nightfall?style=social)
- github.com/xorpd/idsearch ![Github stars](https://shields.io/github/stars/xorpd/idsearch?style=social) ![Github forks](https://shields.io/github/forks/xorpd/idsearch?style=social) ![Github watchers](https://shields.io/github/watchers/xorpd/idsearch?style=social)
- github.com/nihilus/IDASimulator ![Github stars](https://shields.io/github/stars/nihilus/IDASimulator?style=social) ![Github forks](https://shields.io/github/forks/nihilus/IDASimulator?style=social) ![Github watchers](https://shields.io/github/watchers/nihilus/IDASimulator?style=social)
- github.com/dude719/SigMaker-x64 ![Github stars](https://shields.io/github/stars/dude719/SigMaker-x64?style=social) ![Github forks](https://shields.io/github/forks/dude719/SigMaker-x64?style=social) ![Github watchers](https://shields.io/github/watchers/dude719/SigMaker-x64?style=social)
- github.com/fireeye/SimplifyGraph ![Github stars](https://shields.io/github/stars/fireeye/SimplifyGraph?style=social) ![Github forks](https://shields.io/github/forks/fireeye/SimplifyGraph?style=social) ![Github watchers](https://shields.io/github/watchers/fireeye/SimplifyGraph?style=social)
- github.com/google/binexport ![Github stars](https://shields.io/github/stars/google/binexport?style=social) ![Github forks](https://shields.io/github/forks/google/binexport?style=social) ![Github watchers](https://shields.io/github/watchers/google/binexport?style=social)
- github.com/deresz/funcap ![Github stars](https://shields.io/github/stars/deresz/funcap?style=social) ![Github forks](https://shields.io/github/forks/deresz/funcap?style=social) ![Github watchers](https://shields.io/github/watchers/deresz/funcap?style=social)
- github.com/IOActive/kmdf_re ![Github stars](https://shields.io/github/stars/IOActive/kmdf_re?style=social) ![Github forks](https://shields.io/github/forks/IOActive/kmdf_re?style=social) ![Github watchers](https://shields.io/github/watchers/IOActive/kmdf_re?style=social)
- www.h4ck.org.cn/2011/07/ida-pe6-dll-unpack/
- www.anquanke.com/post/id/151898
- www.anquanke.com/post/id/85890
- www.cnblogs.com/17bdw/p/7785469.html
- 4hou.win/wordpress/?cat=1178 (pin & ida)
- wizardforcel.gitbooks.io/grey-hat-python/
- spd.dropsec.xyz/2016/10/05/IDAPython%E5%AE%89%E8%A3%85/
- spd.dropsec.xyz/2017/04/09/%E7%AC%A6%E5%8F%B7%E6%89%A7%E8%A1%8C-%E5%9F%BA%E4%BA%8Epython%E7%9A%84%E4%BA%8C%E8%BF%9B%E5%88%B6%E5%88%86%E6%9E%90%E6%A1%86%E6%9E%B6angr/
- spd.dropsec.xyz/2016/10/16/IDAPython%E8%84%9A%E6%9C%AC%E4%B9%8B%E6%94%B6%E9%9B%86%E5%87%BD%E6%95%B0%E7%9A%84%E8%B0%83%E7%94%A8%E4%BF%A1%E6%81%AF/
- www.freebuf.com/sectool/92107.html
- www.freebuf.com/sectool/92168.html
- www.freebuf.com/articles/system/92488.html
- www.freebuf.com/articles/system/92505.html
- www.freebuf.com/articles/system/93440.html
- www.fortinet.com/blog/threat-research/rewriting-idapython-script-objc2-xrefs-helper-py-for-hopper.html
- sark.readthedocs.io/en/latest/debugging.html
- cartermgj.github.io/2017/10/10/ida-python/
- security.tencent.com/index.php/blog/msg/4
- wingware.com/doc/howtos/idapython
- www.somersetrecon.com/blog/2018/7/6/introduction-to-idapython-for-vulnerability-hunting
- 0xeb.net/2018/02/writing-a-simple-x86-emulator-with-idapython/
- 0xeb.net/2018/02/writing-a-simple-x86-emulator-with-idapython/
- resources.infosecinstitute.com/saving-time-effort-idapython/#gref
- www.thezdi.com/blog/2018/5/21/mindshare-walking-the-windows-kernel-with-ida-python
- www.thezdi.com/blog/2018/7/19/mindshare-an-introduction-to-pykd
- www.thezdi.com/blog/2018/6/26/mindshare-variant-hunting-with-ida-python
- www.mopsled.com/2016/add-shortcut-for-idapython-script-ida-pro/
- blog.sina.com.cn/s/blog_9f5e368a0102wnmm.html
- www.nccgroup.trust/us/about-us/newsroom-and-events/blog/2017/october/python-class-informer-an-idapython-plugin-for-viewing-run-time-type-information-rtti/
- www.pydoc.io/pypi/python-idb-0.4.0/autoapi/analysis/index.html
- securityxploded.com/api-call-tracing-with-pefile-pydbg-and-idapython.php
- www.cnblogs.com/0xJDchen/p/7527236.html
- www.williballenthin.com/blog/2015/09/04/idapython-synchronization-decorator/
- www.fireeye.com/blog/threat-research/2015/01/flare_ida_pro_script.html
- bbs.pediy.com/thread-226983.htm
- www.trustwave.com/Resources/SpiderLabs-Blog/Defeating-Flame-String-Obfuscation-with-IDAPython/
- www.anquanke.com/post/id/151898
- edoc.site/idapython-bookpdf-pdf-free.html
- serializethoughts.com/tag/idapython/
- exploiting.wordpress.com/2011/12/06/quickpost-idapython-script-to-identify-unrecognized-functions/
- barbie.uta.edu/~xlren/Diaphora/diaphora_help.pdf
- www.jianshu.com/p/ee789e8acb03
- blog.51cto.com/watertoeast/2084700
- blog.51cto.com/watertoeast/1352787
- blog.clamav.net/2014/02/generating-clamav-signatures-with.html
- www.mnin.org/write/2006_extract_xor.pdf
- www.hexacorn.com/blog/2015/12/21/idapython-making-strings-decompiler-friendly/
- standa-note.blogspot.com/2015/01/arm-exception-handling-and-idapython.html
- codegist.net/code/idapython-script/
- reverseengineering.stackexchange.com/questions/16055/idapython-get-xrefs-to-a-stack-variable

## pykd & FAQ

- github.com/sogeti-esec-lab/LKD ![Github stars](https://shields.io/github/stars/sogeti-esec-lab/LKD?style=social) ![Github forks](https://shields.io/github/forks/sogeti-esec-lab/LKD?style=social) ![Github watchers](https://shields.io/github/watchers/sogeti-esec-lab/LKD?style=social)
- www.anquanke.com/post/id/86909
- www.anquanke.com/post/id/86896
- www.anquanke.com/post/id/83205
- blog.csdn.net/jimoguilai/article/details/25286029
- blog.csdn.net/jimoguilai/article/details/29827283
- blog.csdn.net/jimoguilai/article/details/38122863
- blog.csdn.net/linux_vae/article/details/77532758
- blog.csdn.net/linux_vae/article/details/77532758
- blog.csdn.net/ambihan/article/details/35775933
- www.zerodayinitiative.com/blog/2018/7/19/mindshare-an-introduction-to-pykd
- www.cnblogs.com/fanzi2009/archive/2012/12/10/2811543.html
- cloud.tencent.com/developer/article/1005628
- eternalsakura13.com/2018/07/03/firefox_env/
- binvoke.com/inline-assembly-in-x64/
- webstersprodigy.net/2014/01/06/soft-function-hooking-with-windbg-and-pykd/
- rayanfam.com/topics/pykd-tutorial-part1/
- rayanfam.com/topics/pykd-tutorial-part2/
- labs.mwrinfosecurity.com/blog/heap-tracing-with-windbg-and-python/
- www.miguelventura.pt/scripting-windbg-with-pykd.html
- labs.nettitude.com/blog/windbg-using-pykd-to-dump-private-symbols/
- webstersprodigy.net/2014/01/06/soft-function-hooking-with-windbg-and-pykd/
- www.cnblogs.com/fanzi2009/archive/2012/12/10/2811543.html
- www.freebuf.com/articles/system/103816.html
- bbs.pediy.com/thread-224904.htm
- theevilbit.blogspot.com/2017/09/pool-spraying-fun-part-1.html
- theevilbit.blogspot.com/2017/09/windows-kernel-pool-spraying-fun-part-2.html
- theevilbit.blogspot.com/2017/09/windows-kernel-pool-spraying-fun-part-3.html
- theevilbit.blogspot.com/2017/09/windows-kernel-pool-spraying-fun-part-4.html
- githomelab.ru/pykd/pykd/-/issues/3

## rpc

- github.com/gentilkiwi/basic_rpc ![Github stars](https://shields.io/github/stars/gentilkiwi/basic_rpc?style=social) ![Github forks](https://shields.io/github/forks/gentilkiwi/basic_rpc?style=social) ![Github watchers](https://shields.io/github/watchers/gentilkiwi/basic_rpc?style=social)

## hash dump

- github.com/AlessandroZ/LaZagneForensic ![Github stars](https://shields.io/github/stars/AlessandroZ/LaZagneForensic?style=social) ![Github forks](https://shields.io/github/forks/AlessandroZ/LaZagneForensic?style=social) ![Github watchers](https://shields.io/github/watchers/AlessandroZ/LaZagneForensic?style=social)
- github.com/AlessandroZ/LaZagne (browser credentials recovery) ![Github stars](https://shields.io/github/stars/AlessandroZ/LaZagne?style=social) ![Github forks](https://shields.io/github/forks/AlessandroZ/LaZagne?style=social) ![Github watchers](https://shields.io/github/watchers/AlessandroZ/LaZagne?style=social)
- github.com/gentilkiwi/mimikatz ![Github stars](https://shields.io/github/stars/gentilkiwi/mimikatz?style=social) ![Github forks](https://shields.io/github/forks/gentilkiwi/mimikatz?style=social) ![Github watchers](https://shields.io/github/watchers/gentilkiwi/mimikatz?style=social)

## auxiliary lib

- github.com/David-Reguera-Garcia-Dreg/auxlib ![Github stars](https://shields.io/github/stars/David-Reguera-Garcia-Dreg/auxlib?style=social) ![Github forks](https://shields.io/github/forks/David-Reguera-Garcia-Dreg/auxlib?style=social) ![Github watchers](https://shields.io/github/watchers/David-Reguera-Garcia-Dreg/auxlib?style=social)

## ring3 nt api

- github.com/adrianyy/x64-syscall ![Github stars](https://shields.io/github/stars/adrianyy/x64-syscall?style=social) ![Github forks](https://shields.io/github/forks/adrianyy/x64-syscall?style=social) ![Github watchers](https://shields.io/github/watchers/adrianyy/x64-syscall?style=social)
- github.com/icestudent/ontl ![Github stars](https://shields.io/github/stars/icestudent/ontl?style=social) ![Github forks](https://shields.io/github/forks/icestudent/ontl?style=social) ![Github watchers](https://shields.io/github/watchers/icestudent/ontl?style=social)
- www.vergiliusproject.com/kernels
- github.com/DissectMalware/WinNativeIO ![Github stars](https://shields.io/github/stars/DissectMalware/WinNativeIO?style=social) ![Github forks](https://shields.io/github/forks/DissectMalware/WinNativeIO?style=social) ![Github watchers](https://shields.io/github/watchers/DissectMalware/WinNativeIO?style=social)
- github.com/zodiacon/WindowsInternals/tree/master/MemLimit/ndk ![Github stars](https://shields.io/github/stars/zodiacon/WindowsInternals?style=social) ![Github forks](https://shields.io/github/forks/zodiacon/WindowsInternals?style=social) ![Github watchers](https://shields.io/github/watchers/zodiacon/WindowsInternals?style=social)
- github.com/codereversing/wow64syscall ![Github stars](https://shields.io/github/stars/codereversing/wow64syscall?style=social) ![Github forks](https://shields.io/github/forks/codereversing/wow64syscall?style=social) ![Github watchers](https://shields.io/github/watchers/codereversing/wow64syscall?style=social)
- github.com/processhacker/phnt ![Github stars](https://shields.io/github/stars/processhacker/phnt?style=social) ![Github forks](https://shields.io/github/forks/processhacker/phnt?style=social) ![Github watchers](https://shields.io/github/watchers/processhacker/phnt?style=social)
- github.com/ntdiff/ntdiff ![Github stars](https://shields.io/github/stars/ntdiff/ntdiff?style=social) ![Github forks](https://shields.io/github/forks/ntdiff/ntdiff?style=social) ![Github watchers](https://shields.io/github/watchers/ntdiff/ntdiff?style=social)
- ntdiff.github.io
- github.com/ntdiff/headers ![Github stars](https://shields.io/github/stars/ntdiff/headers?style=social) ![Github forks](https://shields.io/github/forks/ntdiff/headers?style=social) ![Github watchers](https://shields.io/github/watchers/ntdiff/headers?style=social)
- github.com/Chuyu-Team/NativeLib ![Github stars](https://shields.io/github/stars/Chuyu-Team/NativeLib?style=social) ![Github forks](https://shields.io/github/forks/Chuyu-Team/NativeLib?style=social) ![Github watchers](https://shields.io/github/watchers/Chuyu-Team/NativeLib?style=social)

## winpcap

- libtins.github.io/tutorial/
- github.com/abapat/DNSPoison ![Github stars](https://shields.io/github/stars/abapat/DNSPoison?style=social) ![Github forks](https://shields.io/github/forks/abapat/DNSPoison?style=social) ![Github watchers](https://shields.io/github/watchers/abapat/DNSPoison?style=social)
- www.ferrisxu.com/WinPcap/html/index.html
- github.com/wqqhit/DNSHijack ![Github stars](https://shields.io/github/stars/wqqhit/DNSHijack?style=social) ![Github forks](https://shields.io/github/forks/wqqhit/DNSHijack?style=social) ![Github watchers](https://shields.io/github/watchers/wqqhit/DNSHijack?style=social)
- github.com/klemenb/fiddly ![Github stars](https://shields.io/github/stars/klemenb/fiddly?style=social) ![Github forks](https://shields.io/github/forks/klemenb/fiddly?style=social) ![Github watchers](https://shields.io/github/watchers/klemenb/fiddly?style=social)
- blog.csdn.net/Ni9htMar3/article/details/54612394
- www.cnblogs.com/xcj26/articles/6073411.html
- www.freebuf.com/articles/system/103526.html
- github.com/illahaha/zxarps (arpcheat) ![Github stars](https://shields.io/github/stars/illahaha/zxarps?style=social) ![Github forks](https://shields.io/github/forks/illahaha/zxarps?style=social) ![Github watchers](https://shields.io/github/watchers/illahaha/zxarps?style=social)
- github.com/sincoder/zxarps (arpcheat) ![Github stars](https://shields.io/github/stars/sincoder/zxarps?style=social) ![Github forks](https://shields.io/github/forks/sincoder/zxarps?style=social) ![Github watchers](https://shields.io/github/watchers/sincoder/zxarps?style=social)

## metasploit

- github.com/entynetproject/entypreter ![Github stars](https://shields.io/github/stars/entynetproject/entypreter?style=social) ![Github forks](https://shields.io/github/forks/entynetproject/entypreter?style=social) ![Github watchers](https://shields.io/github/watchers/entynetproject/entypreter?style=social)
- github.com/dr0op/MsfRpcApi ![Github stars](https://shields.io/github/stars/dr0op/MsfRpcApi?style=social) ![Github forks](https://shields.io/github/forks/dr0op/MsfRpcApi?style=social) ![Github watchers](https://shields.io/github/watchers/dr0op/MsfRpcApi?style=social)
- github.com/phackt/stager.dll ![Github stars](https://shields.io/github/stars/phackt/stager.dll?style=social) ![Github forks](https://shields.io/github/forks/phackt/stager.dll?style=social) ![Github watchers](https://shields.io/github/watchers/phackt/stager.dll?style=social)
- github.com/ExpLife/metasploit-framework ![Github stars](https://shields.io/github/stars/ExpLife/metasploit-framework?style=social) ![Github forks](https://shields.io/github/forks/ExpLife/metasploit-framework?style=social) ![Github watchers](https://shields.io/github/watchers/ExpLife/metasploit-framework?style=social)
- github.com/NytroRST/NetRipper ![Github stars](https://shields.io/github/stars/NytroRST/NetRipper?style=social) ![Github forks](https://shields.io/github/forks/NytroRST/NetRipper?style=social) ![Github watchers](https://shields.io/github/watchers/NytroRST/NetRipper?style=social)
- github.com/breenmachine/RottenPotatoNG ![Github stars](https://shields.io/github/stars/breenmachine/RottenPotatoNG?style=social) ![Github forks](https://shields.io/github/forks/breenmachine/RottenPotatoNG?style=social) ![Github watchers](https://shields.io/github/watchers/breenmachine/RottenPotatoNG?style=social)

## shellcode generator

- github.com/DownWithUp/DynamicKernelShellcode ![Github stars](https://shields.io/github/stars/DownWithUp/DynamicKernelShellcode?style=social) ![Github forks](https://shields.io/github/forks/DownWithUp/DynamicKernelShellcode?style=social) ![Github watchers](https://shields.io/github/watchers/DownWithUp/DynamicKernelShellcode?style=social)
- github.com/TheWover/donut ![Github stars](https://shields.io/github/stars/TheWover/donut?style=social) ![Github forks](https://shields.io/github/forks/TheWover/donut?style=social) ![Github watchers](https://shields.io/github/watchers/TheWover/donut?style=social)

## shellcode encoder

- github.com/ecx86/shellcode_encoder ![Github stars](https://shields.io/github/stars/ecx86/shellcode_encoder?style=social) ![Github forks](https://shields.io/github/forks/ecx86/shellcode_encoder?style=social) ![Github watchers](https://shields.io/github/watchers/ecx86/shellcode_encoder?style=social)

## shadow

- github.com/lcxl/lcxl-shadow ![Github stars](https://shields.io/github/stars/lcxl/lcxl-shadow?style=social) ![Github forks](https://shields.io/github/forks/lcxl/lcxl-shadow?style=social) ![Github watchers](https://shields.io/github/watchers/lcxl/lcxl-shadow?style=social)

## network lib

- github.com/zhllxt/asio2 ![Github stars](https://shields.io/github/stars/zhllxt/asio2?style=social) ![Github forks](https://shields.io/github/forks/zhllxt/asio2?style=social) ![Github watchers](https://shields.io/github/watchers/zhllxt/asio2?style=social)

## http

- github.com/elnormous/HTTPRequest ![Github stars](https://shields.io/github/stars/elnormous/HTTPRequest?style=social) ![Github forks](https://shields.io/github/forks/elnormous/HTTPRequest?style=social) ![Github watchers](https://shields.io/github/watchers/elnormous/HTTPRequest?style=social)
- github.com/vlinhd11/WinHttpClass ![Github stars](https://shields.io/github/stars/vlinhd11/WinHttpClass?style=social) ![Github forks](https://shields.io/github/forks/vlinhd11/WinHttpClass?style=social) ![Github watchers](https://shields.io/github/watchers/vlinhd11/WinHttpClass?style=social)
- github.com/hpsocket/restclient-cpp ![Github stars](https://shields.io/github/stars/hpsocket/restclient-cpp?style=social) ![Github forks](https://shields.io/github/forks/hpsocket/restclient-cpp?style=social) ![Github watchers](https://shields.io/github/watchers/hpsocket/restclient-cpp?style=social)
- github.com/farawaaay/http2 (http/2) ![Github stars](https://shields.io/github/stars/farawaaay/http2?style=social) ![Github forks](https://shields.io/github/forks/farawaaay/http2?style=social) ![Github watchers](https://shields.io/github/watchers/farawaaay/http2?style=social)
- github.com/OlehKulykov/libnhr ![Github stars](https://shields.io/github/stars/OlehKulykov/libnhr?style=social) ![Github forks](https://shields.io/github/forks/OlehKulykov/libnhr?style=social) ![Github watchers](https://shields.io/github/watchers/OlehKulykov/libnhr?style=social)
- github.com/erickutcher/httpdownloader ![Github stars](https://shields.io/github/stars/erickutcher/httpdownloader?style=social) ![Github forks](https://shields.io/github/forks/erickutcher/httpdownloader?style=social) ![Github watchers](https://shields.io/github/watchers/erickutcher/httpdownloader?style=social)

## https proxy

- github.com/justcoding121/Titanium-Web-Proxy ![Github stars](https://shields.io/github/stars/justcoding121/Titanium-Web-Proxy?style=social) ![Github forks](https://shields.io/github/forks/justcoding121/Titanium-Web-Proxy?style=social) ![Github watchers](https://shields.io/github/watchers/justcoding121/Titanium-Web-Proxy?style=social)
- anyproxy.io/cn/
- github.com/killbug2004/HttpsProxy ![Github stars](https://shields.io/github/stars/killbug2004/HttpsProxy?style=social) ![Github forks](https://shields.io/github/forks/killbug2004/HttpsProxy?style=social) ![Github watchers](https://shields.io/github/watchers/killbug2004/HttpsProxy?style=social)
- github.com/erickutcher/httpproxy ![Github stars](https://shields.io/github/stars/erickutcher/httpproxy?style=social) ![Github forks](https://shields.io/github/forks/erickutcher/httpproxy?style=social) ![Github watchers](https://shields.io/github/watchers/erickutcher/httpproxy?style=social)

## sock proxy

- github.com/liulilittle/PaperAirplane ![Github stars](https://shields.io/github/stars/liulilittle/PaperAirplane?style=social) ![Github forks](https://shields.io/github/forks/liulilittle/PaperAirplane?style=social) ![Github watchers](https://shields.io/github/watchers/liulilittle/PaperAirplane?style=social)

## reverse proxy

- github.com/fatedier/frp/ ![Github stars](https://shields.io/github/stars/fatedier/frp?style=social) ![Github forks](https://shields.io/github/forks/fatedier/frp?style=social) ![Github watchers](https://shields.io/github/watchers/fatedier/frp?style=social)

## mitm

- github.com/zliu-fd/WinDivertProxy ![Github stars](https://shields.io/github/stars/zliu-fd/WinDivertProxy?style=social) ![Github forks](https://shields.io/github/forks/zliu-fd/WinDivertProxy?style=social) ![Github watchers](https://shields.io/github/watchers/zliu-fd/WinDivertProxy?style=social)
- github.com/sipt/shuttle (GO) ![Github stars](https://shields.io/github/stars/sipt/shuttle?style=social) ![Github forks](https://shields.io/github/forks/sipt/shuttle?style=social) ![Github watchers](https://shields.io/github/watchers/sipt/shuttle?style=social)
- github.com/conorpp/MiTM-HTTP-Proxy ![Github stars](https://shields.io/github/stars/conorpp/MiTM-HTTP-Proxy?style=social) ![Github forks](https://shields.io/github/forks/conorpp/MiTM-HTTP-Proxy?style=social) ![Github watchers](https://shields.io/github/watchers/conorpp/MiTM-HTTP-Proxy?style=social)
- github.com/moxie0/sslsniff ![Github stars](https://shields.io/github/stars/moxie0/sslsniff?style=social) ![Github forks](https://shields.io/github/forks/moxie0/sslsniff?style=social) ![Github watchers](https://shields.io/github/watchers/moxie0/sslsniff?style=social)
- github.com/wuchangming/node-mitmproxy ![Github stars](https://shields.io/github/stars/wuchangming/node-mitmproxy?style=social) ![Github forks](https://shields.io/github/forks/wuchangming/node-mitmproxy?style=social) ![Github watchers](https://shields.io/github/watchers/wuchangming/node-mitmproxy?style=social)
- github.com/hostilefork/flatworm ![Github stars](https://shields.io/github/stars/hostilefork/flatworm?style=social) ![Github forks](https://shields.io/github/forks/hostilefork/flatworm?style=social) ![Github watchers](https://shields.io/github/watchers/hostilefork/flatworm?style=social)
- github.com/progtramder/webproxy ![Github stars](https://shields.io/github/stars/progtramder/webproxy?style=social) ![Github forks](https://shields.io/github/forks/progtramder/webproxy?style=social) ![Github watchers](https://shields.io/github/watchers/progtramder/webproxy?style=social)
- github.com/empijei/wapty ![Github stars](https://shields.io/github/stars/empijei/wapty?style=social) ![Github forks](https://shields.io/github/forks/empijei/wapty?style=social) ![Github watchers](https://shields.io/github/watchers/empijei/wapty?style=social)
- github.com/xxxxnnxxxx/HttpProxy ![Github stars](https://shields.io/github/stars/xxxxnnxxxx/HttpProxy?style=social) ![Github forks](https://shields.io/github/forks/xxxxnnxxxx/HttpProxy?style=social) ![Github watchers](https://shields.io/github/watchers/xxxxnnxxxx/HttpProxy?style=social)
- github.com/astibal/smithproxy ![Github stars](https://shields.io/github/stars/astibal/smithproxy?style=social) ![Github forks](https://shields.io/github/forks/astibal/smithproxy?style=social) ![Github watchers](https://shields.io/github/watchers/astibal/smithproxy?style=social)
- github.com/TechnikEmpire/CitadelCore ![Github stars](https://shields.io/github/stars/TechnikEmpire/CitadelCore?style=social) ![Github forks](https://shields.io/github/forks/TechnikEmpire/CitadelCore?style=social) ![Github watchers](https://shields.io/github/watchers/TechnikEmpire/CitadelCore?style=social)
- github.com/TechnikEmpire/HttpFilteringEngine ![Github stars](https://shields.io/github/stars/TechnikEmpire/HttpFilteringEngine?style=social) ![Github forks](https://shields.io/github/forks/TechnikEmpire/HttpFilteringEngine?style=social) ![Github watchers](https://shields.io/github/watchers/TechnikEmpire/HttpFilteringEngine?style=social)
- blog.csdn.net/kunyus/article/details/78679717
- github.com/liuyufei/SSLKiller ![Github stars](https://shields.io/github/stars/liuyufei/SSLKiller?style=social) ![Github forks](https://shields.io/github/forks/liuyufei/SSLKiller?style=social) ![Github watchers](https://shields.io/github/watchers/liuyufei/SSLKiller?style=social)
- blog.csdn.net/Tencent_Bugly/article/details/72626127
- github.com/pfussell/pivotal ![Github stars](https://shields.io/github/stars/pfussell/pivotal?style=social) ![Github forks](https://shields.io/github/forks/pfussell/pivotal?style=social) ![Github watchers](https://shields.io/github/watchers/pfussell/pivotal?style=social)

## ssl

- github.com/edwig/SSLSocket ![Github stars](https://shields.io/github/stars/edwig/SSLSocket?style=social) ![Github forks](https://shields.io/github/forks/edwig/SSLSocket?style=social) ![Github watchers](https://shields.io/github/watchers/edwig/SSLSocket?style=social)

## json

- github.com/ez8-co/xpjson ![Github stars](https://shields.io/github/stars/ez8-co/xpjson?style=social) ![Github forks](https://shields.io/github/forks/ez8-co/xpjson?style=social) ![Github watchers](https://shields.io/github/watchers/ez8-co/xpjson?style=social)
- github.com/marcusbotacin/MyJSON ![Github stars](https://shields.io/github/stars/marcusbotacin/MyJSON?style=social) ![Github forks](https://shields.io/github/forks/marcusbotacin/MyJSON?style=social) ![Github watchers](https://shields.io/github/watchers/marcusbotacin/MyJSON?style=social)

## serialization

- github.com/ez8-co/es11n ![Github stars](https://shields.io/github/stars/ez8-co/es11n?style=social) ![Github forks](https://shields.io/github/forks/ez8-co/es11n?style=social) ![Github watchers](https://shields.io/github/watchers/ez8-co/es11n?style=social)

## awesome

- github.com/FULLSHADE/WindowsExploitationResources ![Github stars](https://shields.io/github/stars/FULLSHADE/WindowsExploitationResources?style=social) ![Github forks](https://shields.io/github/forks/FULLSHADE/WindowsExploitationResources?style=social) ![Github watchers](https://shields.io/github/watchers/FULLSHADE/WindowsExploitationResources?style=social)
- github.com/Wenzel/awesome-virtualization ![Github stars](https://shields.io/github/stars/Wenzel/awesome-virtualization?style=social) ![Github forks](https://shields.io/github/forks/Wenzel/awesome-virtualization?style=social) ![Github watchers](https://shields.io/github/watchers/Wenzel/awesome-virtualization?style=social)
- github.com/alphaSeclab/anti-av ![Github stars](https://shields.io/github/stars/alphaSeclab/anti-av?style=social) ![Github forks](https://shields.io/github/forks/alphaSeclab/anti-av?style=social) ![Github watchers](https://shields.io/github/watchers/alphaSeclab/anti-av?style=social)
- github.com/kevingo/coding-interview-university-zh-tw/blob/master/translations/README-cn.md ![Github stars](https://shields.io/github/stars/kevingo/coding-interview-university-zh-tw?style=social) ![Github forks](https://shields.io/github/forks/kevingo/coding-interview-university-zh-tw?style=social) ![Github watchers](https://shields.io/github/watchers/kevingo/coding-interview-university-zh-tw?style=social)
- websec.readthedocs.io/zh/latest/ (web sec)
- ctf-wiki.github.io/ctf-wiki/pwn/readme-zh/
- chybeta.github.io/2017/08/19/Software-Security-Learning/
- github.com/alphaSeclab/awesome-reverse-engineering ![Github stars](https://shields.io/github/stars/alphaSeclab/awesome-reverse-engineering?style=social) ![Github forks](https://shields.io/github/forks/alphaSeclab/awesome-reverse-engineering?style=social) ![Github watchers](https://shields.io/github/watchers/alphaSeclab/awesome-reverse-engineering?style=social)
- github.com/enovella/TEE-reversing ![Github stars](https://shields.io/github/stars/enovella/TEE-reversing?style=social) ![Github forks](https://shields.io/github/forks/enovella/TEE-reversing?style=social) ![Github watchers](https://shields.io/github/watchers/enovella/TEE-reversing?style=social)
- github.com/1c7/chinese-independent-developer ![Github stars](https://shields.io/github/stars/1c7/chinese-independent-developer?style=social) ![Github forks](https://shields.io/github/forks/1c7/chinese-independent-developer?style=social) ![Github watchers](https://shields.io/github/watchers/1c7/chinese-independent-developer?style=social)
- github.com/theLSA/CS-checklist ![Github stars](https://shields.io/github/stars/theLSA/CS-checklist?style=social) ![Github forks](https://shields.io/github/forks/theLSA/CS-checklist?style=social) ![Github watchers](https://shields.io/github/watchers/theLSA/CS-checklist?style=social)
- github.com/wcventure/FuzzingPaper ![Github stars](https://shields.io/github/stars/wcventure/FuzzingPaper?style=social) ![Github forks](https://shields.io/github/forks/wcventure/FuzzingPaper?style=social) ![Github watchers](https://shields.io/github/watchers/wcventure/FuzzingPaper?style=social)
- github.com/wcventure/BugDetectionPaper ![Github stars](https://shields.io/github/stars/wcventure/BugDetectionPaper?style=social) ![Github forks](https://shields.io/github/forks/wcventure/BugDetectionPaper?style=social) ![Github watchers](https://shields.io/github/watchers/wcventure/BugDetectionPaper?style=social)
- github.com/xrkk/awesome-ida ![Github stars](https://shields.io/github/stars/xrkk/awesome-ida?style=social) ![Github forks](https://shields.io/github/forks/xrkk/awesome-ida?style=social) ![Github watchers](https://shields.io/github/watchers/xrkk/awesome-ida?style=social)
- github.com/SecWiki/sec-chart ![Github stars](https://shields.io/github/stars/SecWiki/sec-chart?style=social) ![Github forks](https://shields.io/github/forks/SecWiki/sec-chart?style=social) ![Github watchers](https://shields.io/github/watchers/SecWiki/sec-chart?style=social)
- github.com/skywind3000/awesome-cheatsheets (cheatsheets) ![Github stars](https://shields.io/github/stars/skywind3000/awesome-cheatsheets?style=social) ![Github forks](https://shields.io/github/forks/skywind3000/awesome-cheatsheets?style=social) ![Github watchers](https://shields.io/github/watchers/skywind3000/awesome-cheatsheets?style=social)
- github.com/toutiaoio/awesome-architecture ![Github stars](https://shields.io/github/stars/toutiaoio/awesome-architecture?style=social) ![Github forks](https://shields.io/github/forks/toutiaoio/awesome-architecture?style=social) ![Github watchers](https://shields.io/github/watchers/toutiaoio/awesome-architecture?style=social)
- github.com/streetleague/0xbird.github.io ![Github stars](https://shields.io/github/stars/streetleague/0xbird.github.io?style=social) ![Github forks](https://shields.io/github/forks/streetleague/0xbird.github.io?style=social) ![Github watchers](https://shields.io/github/watchers/streetleague/0xbird.github.io?style=social)
- github.com/BlackINT3/awesome-debugging ![Github stars](https://shields.io/github/stars/BlackINT3/awesome-debugging?style=social) ![Github forks](https://shields.io/github/forks/BlackINT3/awesome-debugging?style=social) ![Github watchers](https://shields.io/github/watchers/BlackINT3/awesome-debugging?style=social)
- github.com/yeyintminthuhtut/Awesome-Advanced-Windows-Exploitation-References ![Github stars](https://shields.io/github/stars/yeyintminthuhtut/Awesome-Advanced-Windows-Exploitation-References?style=social) ![Github forks](https://shields.io/github/forks/yeyintminthuhtut/Awesome-Advanced-Windows-Exploitation-References?style=social) ![Github watchers](https://shields.io/github/watchers/yeyintminthuhtut/Awesome-Advanced-Windows-Exploitation-References?style=social)
- github.com/jobbole/awesome-design-cn ![Github stars](https://shields.io/github/stars/jobbole/awesome-design-cn?style=social) ![Github forks](https://shields.io/github/forks/jobbole/awesome-design-cn?style=social) ![Github watchers](https://shields.io/github/watchers/jobbole/awesome-design-cn?style=social)
- github.com/xuanhun/HackingResource ![Github stars](https://shields.io/github/stars/xuanhun/HackingResource?style=social) ![Github forks](https://shields.io/github/forks/xuanhun/HackingResource?style=social) ![Github watchers](https://shields.io/github/watchers/xuanhun/HackingResource?style=social)
- github.com/yeyintminthuhtut/Awesome-Windows-Exploitation-Study-References ![Github stars](https://shields.io/github/stars/yeyintminthuhtut/Awesome-Windows-Exploitation-Study-References?style=social) ![Github forks](https://shields.io/github/forks/yeyintminthuhtut/Awesome-Windows-Exploitation-Study-References?style=social) ![Github watchers](https://shields.io/github/watchers/yeyintminthuhtut/Awesome-Windows-Exploitation-Study-References?style=social)
- github.com/anhkgg/awesome-windbg-extensions ![Github stars](https://shields.io/github/stars/anhkgg/awesome-windbg-extensions?style=social) ![Github forks](https://shields.io/github/forks/anhkgg/awesome-windbg-extensions?style=social) ![Github watchers](https://shields.io/github/watchers/anhkgg/awesome-windbg-extensions?style=social)
- github.com/wcventure/FuzzingPaper ![Github stars](https://shields.io/github/stars/wcventure/FuzzingPaper?style=social) ![Github forks](https://shields.io/github/forks/wcventure/FuzzingPaper?style=social) ![Github watchers](https://shields.io/github/watchers/wcventure/FuzzingPaper?style=social)
- github.com/fr0gger/awesome-ida-x64-olly-plugin ![Github stars](https://shields.io/github/stars/fr0gger/awesome-ida-x64-olly-plugin?style=social) ![Github forks](https://shields.io/github/forks/fr0gger/awesome-ida-x64-olly-plugin?style=social) ![Github watchers](https://shields.io/github/watchers/fr0gger/awesome-ida-x64-olly-plugin?style=social)
- github.com/Ridter/Intranet_Penetration_Tips ![Github stars](https://shields.io/github/stars/Ridter/Intranet_Penetration_Tips?style=social) ![Github forks](https://shields.io/github/forks/Ridter/Intranet_Penetration_Tips?style=social) ![Github watchers](https://shields.io/github/watchers/Ridter/Intranet_Penetration_Tips?style=social)
- github.com/danielmiessler/SecLists ![Github stars](https://shields.io/github/stars/danielmiessler/SecLists?style=social) ![Github forks](https://shields.io/github/forks/danielmiessler/SecLists?style=social) ![Github watchers](https://shields.io/github/watchers/danielmiessler/SecLists?style=social)
- github.com/yeyintminthuhtut/Awesome-Red-Teaming ![Github stars](https://shields.io/github/stars/yeyintminthuhtut/Awesome-Red-Teaming?style=social) ![Github forks](https://shields.io/github/forks/yeyintminthuhtut/Awesome-Red-Teaming?style=social) ![Github watchers](https://shields.io/github/watchers/yeyintminthuhtut/Awesome-Red-Teaming?style=social)
- github.com/REMath/literature_review ![Github stars](https://shields.io/github/stars/REMath/literature_review?style=social) ![Github forks](https://shields.io/github/forks/REMath/literature_review?style=social) ![Github watchers](https://shields.io/github/watchers/REMath/literature_review?style=social)
- github.com/phith0n/Mind-Map ![Github stars](https://shields.io/github/stars/phith0n/Mind-Map?style=social) ![Github forks](https://shields.io/github/forks/phith0n/Mind-Map?style=social) ![Github watchers](https://shields.io/github/watchers/phith0n/Mind-Map?style=social)
- github.com/CHYbeta/Software-Security-Learning ![Github stars](https://shields.io/github/stars/CHYbeta/Software-Security-Learning?style=social) ![Github forks](https://shields.io/github/forks/CHYbeta/Software-Security-Learning?style=social) ![Github watchers](https://shields.io/github/watchers/CHYbeta/Software-Security-Learning?style=social)
- github.com/0x4D31/awesome-threat-detection ![Github stars](https://shields.io/github/stars/0x4D31/awesome-threat-detection?style=social) ![Github forks](https://shields.io/github/forks/0x4D31/awesome-threat-detection?style=social) ![Github watchers](https://shields.io/github/watchers/0x4D31/awesome-threat-detection?style=social)
- github.com/Escapingbug/awesome-browser-exploit ![Github stars](https://shields.io/github/stars/Escapingbug/awesome-browser-exploit?style=social) ![Github forks](https://shields.io/github/forks/Escapingbug/awesome-browser-exploit?style=social) ![Github watchers](https://shields.io/github/watchers/Escapingbug/awesome-browser-exploit?style=social)
- github.com/CaledoniaProject/awesome-opensource-security ![Github stars](https://shields.io/github/stars/CaledoniaProject/awesome-opensource-security?style=social) ![Github forks](https://shields.io/github/forks/CaledoniaProject/awesome-opensource-security?style=social) ![Github watchers](https://shields.io/github/watchers/CaledoniaProject/awesome-opensource-security?style=social)
- github.com/rshipp/awesome-malware-analysis ![Github stars](https://shields.io/github/stars/rshipp/awesome-malware-analysis?style=social) ![Github forks](https://shields.io/github/forks/rshipp/awesome-malware-analysis?style=social) ![Github watchers](https://shields.io/github/watchers/rshipp/awesome-malware-analysis?style=social)
- github.com/lmy375/awesome-vmp ![Github stars](https://shields.io/github/stars/lmy375/awesome-vmp?style=social) ![Github forks](https://shields.io/github/forks/lmy375/awesome-vmp?style=social) ![Github watchers](https://shields.io/github/watchers/lmy375/awesome-vmp?style=social)
- github.com/ksluckow/awesome-symbolic-execution ![Github stars](https://shields.io/github/stars/ksluckow/awesome-symbolic-execution?style=social) ![Github forks](https://shields.io/github/forks/ksluckow/awesome-symbolic-execution?style=social) ![Github watchers](https://shields.io/github/watchers/ksluckow/awesome-symbolic-execution?style=social)
- github.com/szysec/ctftest ![Github stars](https://shields.io/github/stars/szysec/ctftest?style=social) ![Github forks](https://shields.io/github/forks/szysec/ctftest?style=social) ![Github watchers](https://shields.io/github/watchers/szysec/ctftest?style=social)
- stackoverflow.com/questions/4946685/good-tutorial-for-windbg
- github.com/rmusser01/Infosec_Reference ![Github stars](https://shields.io/github/stars/rmusser01/Infosec_Reference?style=social) ![Github forks](https://shields.io/github/forks/rmusser01/Infosec_Reference?style=social) ![Github watchers](https://shields.io/github/watchers/rmusser01/Infosec_Reference?style=social)
- github.com/sam-b/windows_kernel_resources ![Github stars](https://shields.io/github/stars/sam-b/windows_kernel_resources?style=social) ![Github forks](https://shields.io/github/forks/sam-b/windows_kernel_resources?style=social) ![Github watchers](https://shields.io/github/watchers/sam-b/windows_kernel_resources?style=social)
- github.com/EbookFoundation/free-programming-books ![Github stars](https://shields.io/github/stars/EbookFoundation/free-programming-books?style=social) ![Github forks](https://shields.io/github/forks/EbookFoundation/free-programming-books?style=social) ![Github watchers](https://shields.io/github/watchers/EbookFoundation/free-programming-books?style=social)
- github.com/justjavac/free-programming-books-zh_CN ![Github stars](https://shields.io/github/stars/justjavac/free-programming-books-zh_CN?style=social) ![Github forks](https://shields.io/github/forks/justjavac/free-programming-books-zh_CN?style=social) ![Github watchers](https://shields.io/github/watchers/justjavac/free-programming-books-zh_CN?style=social)
- github.com/rmusser01/Infosec_Reference/ ![Github stars](https://shields.io/github/stars/rmusser01/Infosec_Reference?style=social) ![Github forks](https://shields.io/github/forks/rmusser01/Infosec_Reference?style=social) ![Github watchers](https://shields.io/github/watchers/rmusser01/Infosec_Reference?style=social)
- github.com/jshaw87/Cheatsheets ![Github stars](https://shields.io/github/stars/jshaw87/Cheatsheets?style=social) ![Github forks](https://shields.io/github/forks/jshaw87/Cheatsheets?style=social) ![Github watchers](https://shields.io/github/watchers/jshaw87/Cheatsheets?style=social)
- github.com/RPISEC/MBE ![Github stars](https://shields.io/github/stars/RPISEC/MBE?style=social) ![Github forks](https://shields.io/github/forks/RPISEC/MBE?style=social) ![Github watchers](https://shields.io/github/watchers/RPISEC/MBE?style=social)

## windows Driver Kit ddi (device driver interface) documentation

- docs.microsoft.com/zh-cn/windows-hardware/drivers/install/
- docs.microsoft.com/zh-cn/windows-hardware/drivers/kernel/
- docs.microsoft.com/zh-cn/windows-hardware/drivers/network/
- docs.microsoft.com/zh-cn/windows-hardware/drivers/ddi/
- docs.microsoft.com/zh-cn/windows-hardware/drivers/driversecurity
- docs.microsoft.com/zh-cn/windows-hardware/drivers/wdf/
- docs.microsoft.com/zh-cn/windows-hardware/drivers/samples/
- docs.microsoft.com/zh-cn/windows-hardware/drivers/debugger/
- docs.microsoft.com/zh-cn/previous-versions/windows/embedded/gg157655(v=winembedded.80)
- docs.microsoft.com/zh-cn/windows-hardware/drivers/debugger/time-travel-debugging-overview
- docs.microsoft.com/zh-cn/previous-versions/visualstudio/visual-studio-2010/aa983363(v=vs.100) (vmx)

## windbg preview & jsprovider

- github.com/benoitsevens/applying-ttd-to-malware-analysis ![Github stars](https://shields.io/github/stars/benoitsevens/applying-ttd-to-malware-analysis?style=social) ![Github forks](https://shields.io/github/forks/benoitsevens/applying-ttd-to-malware-analysis?style=social) ![Github watchers](https://shields.io/github/watchers/benoitsevens/applying-ttd-to-malware-analysis?style=social)
- github.com/Microsoft/WinDbg-Samples ![Github stars](https://shields.io/github/stars/Microsoft/WinDbg-Samples?style=social) ![Github forks](https://shields.io/github/forks/Microsoft/WinDbg-Samples?style=social) ![Github watchers](https://shields.io/github/watchers/Microsoft/WinDbg-Samples?style=social)
- bbs.pediy.com/thread-246449.htm
- doar-e.github.io/blog/2017/12/01/debugger-data-model/

## anti-anti-vm

- github.com/hzqst/VmwareHardenedLoader ![Github stars](https://shields.io/github/stars/hzqst/VmwareHardenedLoader?style=social) ![Github forks](https://shields.io/github/forks/hzqst/VmwareHardenedLoader?style=social) ![Github watchers](https://shields.io/github/watchers/hzqst/VmwareHardenedLoader?style=social)

## vm

- github.com/nblog/Vm2Import ![Github stars](https://shields.io/github/stars/nblog/Vm2Import?style=social) ![Github forks](https://shields.io/github/forks/nblog/Vm2Import?style=social) ![Github watchers](https://shields.io/github/watchers/nblog/Vm2Import?style=social)
- github.com/can1357/NoVmp ![Github stars](https://shields.io/github/stars/can1357/NoVmp?style=social) ![Github forks](https://shields.io/github/forks/can1357/NoVmp?style=social) ![Github watchers](https://shields.io/github/watchers/can1357/NoVmp?style=social)
- github.com/etsubu/NanoVM (x64) ![Github stars](https://shields.io/github/stars/etsubu/NanoVM?style=social) ![Github forks](https://shields.io/github/forks/etsubu/NanoVM?style=social) ![Github watchers](https://shields.io/github/watchers/etsubu/NanoVM?style=social)
- github.com/tboox/vm86 ![Github stars](https://shields.io/github/stars/tboox/vm86?style=social) ![Github forks](https://shields.io/github/forks/tboox/vm86?style=social) ![Github watchers](https://shields.io/github/watchers/tboox/vm86?style=social)

## pe tool

- github.com/jovibor/Pepper ![Github stars](https://shields.io/github/stars/jovibor/Pepper?style=social) ![Github forks](https://shields.io/github/forks/jovibor/Pepper?style=social) ![Github watchers](https://shields.io/github/watchers/jovibor/Pepper?style=social)
- github.com/Darkabode/amte ![Github stars](https://shields.io/github/stars/Darkabode/amte?style=social) ![Github forks](https://shields.io/github/forks/Darkabode/amte?style=social) ![Github watchers](https://shields.io/github/watchers/Darkabode/amte?style=social)
- www.pelock.com/products/string-encrypt
- www.pelock.com/products/obfuscator
- github.com/hasherezade/funky_malware_formats ![Github stars](https://shields.io/github/stars/hasherezade/funky_malware_formats?style=social) ![Github forks](https://shields.io/github/forks/hasherezade/funky_malware_formats?style=social) ![Github watchers](https://shields.io/github/watchers/hasherezade/funky_malware_formats?style=social)
- github.com/hasherezade/hollows_hunter  (scan hook) ![Github stars](https://shields.io/github/stars/hasherezade/hollows_hunter?style=social) ![Github forks](https://shields.io/github/forks/hasherezade/hollows_hunter?style=social) ![Github watchers](https://shields.io/github/watchers/hasherezade/hollows_hunter?style=social)
- github.com/hasherezade/pe-sieve ![Github stars](https://shields.io/github/stars/hasherezade/pe-sieve?style=social) ![Github forks](https://shields.io/github/forks/hasherezade/pe-sieve?style=social) ![Github watchers](https://shields.io/github/watchers/hasherezade/pe-sieve?style=social)
- github.com/hasherezade/bearparser ![Github stars](https://shields.io/github/stars/hasherezade/bearparser?style=social) ![Github forks](https://shields.io/github/forks/hasherezade/bearparser?style=social) ![Github watchers](https://shields.io/github/watchers/hasherezade/bearparser?style=social)
- github.com/hasherezade/libpeconv ![Github stars](https://shields.io/github/stars/hasherezade/libpeconv?style=social) ![Github forks](https://shields.io/github/forks/hasherezade/libpeconv?style=social) ![Github watchers](https://shields.io/github/watchers/hasherezade/libpeconv?style=social)
- github.com/hasherezade/malware_analysis ![Github stars](https://shields.io/github/stars/hasherezade/malware_analysis?style=social) ![Github forks](https://shields.io/github/forks/hasherezade/malware_analysis?style=social) ![Github watchers](https://shields.io/github/watchers/hasherezade/malware_analysis?style=social)
- github.com/hasherezade/libpeconv_project_template ![Github stars](https://shields.io/github/stars/hasherezade/libpeconv_project_template?style=social) ![Github forks](https://shields.io/github/forks/hasherezade/libpeconv_project_template?style=social) ![Github watchers](https://shields.io/github/watchers/hasherezade/libpeconv_project_template?style=social)
- github.com/hasherezade/libpeconv_wrappers ![Github stars](https://shields.io/github/stars/hasherezade/libpeconv_wrappers?style=social) ![Github forks](https://shields.io/github/forks/hasherezade/libpeconv_wrappers?style=social) ![Github watchers](https://shields.io/github/watchers/hasherezade/libpeconv_wrappers?style=social)
- github.com/hasherezade/process_doppelganging ![Github stars](https://shields.io/github/stars/hasherezade/process_doppelganging?style=social) ![Github forks](https://shields.io/github/forks/hasherezade/process_doppelganging?style=social) ![Github watchers](https://shields.io/github/watchers/hasherezade/process_doppelganging?style=social)
- github.com/hasherezade/bee_parser ![Github stars](https://shields.io/github/stars/hasherezade/bee_parser?style=social) ![Github forks](https://shields.io/github/forks/hasherezade/bee_parser?style=social) ![Github watchers](https://shields.io/github/watchers/hasherezade/bee_parser?style=social)
- github.com/hasherezade/pe_to_shellcode ![Github stars](https://shields.io/github/stars/hasherezade/pe_to_shellcode?style=social) ![Github forks](https://shields.io/github/forks/hasherezade/pe_to_shellcode?style=social) ![Github watchers](https://shields.io/github/watchers/hasherezade/pe_to_shellcode?style=social)
- github.com/hasherezade/mal_unpack ![Github stars](https://shields.io/github/stars/hasherezade/mal_unpack?style=social) ![Github forks](https://shields.io/github/forks/hasherezade/mal_unpack?style=social) ![Github watchers](https://shields.io/github/watchers/hasherezade/mal_unpack?style=social)
- github.com/hasherezade/process_chameleon (modify exe path) ![Github stars](https://shields.io/github/stars/hasherezade/process_chameleon?style=social) ![Github forks](https://shields.io/github/forks/hasherezade/process_chameleon?style=social) ![Github watchers](https://shields.io/github/watchers/hasherezade/process_chameleon?style=social)
- github.com/hasherezade/loaderine ![Github stars](https://shields.io/github/stars/hasherezade/loaderine?style=social) ![Github forks](https://shields.io/github/forks/hasherezade/loaderine?style=social) ![Github watchers](https://shields.io/github/watchers/hasherezade/loaderine?style=social)
- github.com/hasherezade/chimera_loader ![Github stars](https://shields.io/github/stars/hasherezade/chimera_loader?style=social) ![Github forks](https://shields.io/github/forks/hasherezade/chimera_loader?style=social) ![Github watchers](https://shields.io/github/watchers/hasherezade/chimera_loader?style=social)
- github.com/YajS/NikPEViewer ![Github stars](https://shields.io/github/stars/YajS/NikPEViewer?style=social) ![Github forks](https://shields.io/github/forks/YajS/NikPEViewer?style=social) ![Github watchers](https://shields.io/github/watchers/YajS/NikPEViewer?style=social)

## tools

- github.com/codilime/veles ![Github stars](https://shields.io/github/stars/codilime/veles?style=social) ![Github forks](https://shields.io/github/forks/codilime/veles?style=social) ![Github watchers](https://shields.io/github/watchers/codilime/veles?style=social)
- github.com/glmcdona/strings2 ![Github stars](https://shields.io/github/stars/glmcdona/strings2?style=social) ![Github forks](https://shields.io/github/forks/glmcdona/strings2?style=social) ![Github watchers](https://shields.io/github/watchers/glmcdona/strings2?style=social)
- bytepointer.com/tools/index.htm#peupdate
- github.com/endgameinc/xori (Dissasemblers blackhat 2018) ![Github stars](https://shields.io/github/stars/endgameinc/xori?style=social) ![Github forks](https://shields.io/github/forks/endgameinc/xori?style=social) ![Github watchers](https://shields.io/github/watchers/endgameinc/xori?style=social)
- www.softpedia.com/get/Programming/Debuggers-Decompilers-Dissasemblers/

## post-exploitation

- github.com/S1ckB0y1337/Active-Directory-Exploitation-Cheat-Sheet ![Github stars](https://shields.io/github/stars/S1ckB0y1337/Active-Directory-Exploitation-Cheat-Sheet?style=social) ![Github forks](https://shields.io/github/forks/S1ckB0y1337/Active-Directory-Exploitation-Cheat-Sheet?style=social) ![Github watchers](https://shields.io/github/watchers/S1ckB0y1337/Active-Directory-Exploitation-Cheat-Sheet?style=social)
- github.com/0x09AL/DNS-Persist (DNS C&C) ![Github stars](https://shields.io/github/stars/0x09AL/DNS-Persist?style=social) ![Github forks](https://shields.io/github/forks/0x09AL/DNS-Persist?style=social) ![Github watchers](https://shields.io/github/watchers/0x09AL/DNS-Persist?style=social)
- github.com/francisck/DanderSpritz_lab ![Github stars](https://shields.io/github/stars/francisck/DanderSpritz_lab?style=social) ![Github forks](https://shields.io/github/forks/francisck/DanderSpritz_lab?style=social) ![Github watchers](https://shields.io/github/watchers/francisck/DanderSpritz_lab?style=social)
- github.com/francisck/DanderSpritz_docs ![Github stars](https://shields.io/github/stars/francisck/DanderSpritz_docs?style=social) ![Github forks](https://shields.io/github/forks/francisck/DanderSpritz_docs?style=social) ![Github watchers](https://shields.io/github/watchers/francisck/DanderSpritz_docs?style=social)

## nsa security tools

- github.com/exploitx3/FUZZBUNCH ![Github stars](https://shields.io/github/stars/exploitx3/FUZZBUNCH?style=social) ![Github forks](https://shields.io/github/forks/exploitx3/FUZZBUNCH?style=social) ![Github watchers](https://shields.io/github/watchers/exploitx3/FUZZBUNCH?style=social)
- github.com/fuzzbunch/fuzzbunch ![Github stars](https://shields.io/github/stars/fuzzbunch/fuzzbunch?style=social) ![Github forks](https://shields.io/github/forks/fuzzbunch/fuzzbunch?style=social) ![Github watchers](https://shields.io/github/watchers/fuzzbunch/fuzzbunch?style=social)
- github.com/peterpt/fuzzbunch ![Github stars](https://shields.io/github/stars/peterpt/fuzzbunch?style=social) ![Github forks](https://shields.io/github/forks/peterpt/fuzzbunch?style=social) ![Github watchers](https://shields.io/github/watchers/peterpt/fuzzbunch?style=social)

## apt

- github.com/Yeti-791/APT-Guide ![Github stars](https://shields.io/github/stars/Yeti-791/APT-Guide?style=social) ![Github forks](https://shields.io/github/forks/Yeti-791/APT-Guide?style=social) ![Github watchers](https://shields.io/github/watchers/Yeti-791/APT-Guide?style=social)
- github.com/RedDrip7/APT_Digital_Weapon ![Github stars](https://shields.io/github/stars/RedDrip7/APT_Digital_Weapon?style=social) ![Github forks](https://shields.io/github/forks/RedDrip7/APT_Digital_Weapon?style=social) ![Github watchers](https://shields.io/github/watchers/RedDrip7/APT_Digital_Weapon?style=social)
- github.com/CyberMonitor/APT_CyberCriminal_Campagin_Collections ![Github stars](https://shields.io/github/stars/CyberMonitor/APT_CyberCriminal_Campagin_Collections?style=social) ![Github forks](https://shields.io/github/forks/CyberMonitor/APT_CyberCriminal_Campagin_Collections?style=social) ![Github watchers](https://shields.io/github/watchers/CyberMonitor/APT_CyberCriminal_Campagin_Collections?style=social)
- github.com/kbandla/APTnotes ![Github stars](https://shields.io/github/stars/kbandla/APTnotes?style=social) ![Github forks](https://shields.io/github/forks/kbandla/APTnotes?style=social) ![Github watchers](https://shields.io/github/watchers/kbandla/APTnotes?style=social)
- attack.mitre.org/wiki/Groups
- github.com/fdiskyou/threat-INTel ![Github stars](https://shields.io/github/stars/fdiskyou/threat-INTel?style=social) ![Github forks](https://shields.io/github/forks/fdiskyou/threat-INTel?style=social) ![Github watchers](https://shields.io/github/watchers/fdiskyou/threat-INTel?style=social)

## 3rd party library

- github.com/ez8-co/ezpp ![Github stars](https://shields.io/github/stars/ez8-co/ezpp?style=social) ![Github forks](https://shields.io/github/forks/ez8-co/ezpp?style=social) ![Github watchers](https://shields.io/github/watchers/ez8-co/ezpp?style=social)
- github.com/ez8-co/emock ![Github stars](https://shields.io/github/stars/ez8-co/emock?style=social) ![Github forks](https://shields.io/github/forks/ez8-co/emock?style=social) ![Github watchers](https://shields.io/github/watchers/ez8-co/emock?style=social)
- github.com/ez8-co/atomic ![Github stars](https://shields.io/github/stars/ez8-co/atomic?style=social) ![Github forks](https://shields.io/github/forks/ez8-co/atomic?style=social) ![Github watchers](https://shields.io/github/watchers/ez8-co/atomic?style=social)
- github.com/ez8-co/linked_hash ![Github stars](https://shields.io/github/stars/ez8-co/linked_hash?style=social) ![Github forks](https://shields.io/github/forks/ez8-co/linked_hash?style=social) ![Github watchers](https://shields.io/github/watchers/ez8-co/linked_hash?style=social)
- github.com/asmjit/asmjit (jit) ![Github stars](https://shields.io/github/stars/asmjit/asmjit?style=social) ![Github forks](https://shields.io/github/forks/asmjit/asmjit?style=social) ![Github watchers](https://shields.io/github/watchers/asmjit/asmjit?style=social)
- github.com/acl-dev/acl ![Github stars](https://shields.io/github/stars/acl-dev/acl?style=social) ![Github forks](https://shields.io/github/forks/acl-dev/acl?style=social) ![Github watchers](https://shields.io/github/watchers/acl-dev/acl?style=social)
- github.com/kingsamchen/WinAntHttp ![Github stars](https://shields.io/github/stars/kingsamchen/WinAntHttp?style=social) ![Github forks](https://shields.io/github/forks/kingsamchen/WinAntHttp?style=social) ![Github watchers](https://shields.io/github/watchers/kingsamchen/WinAntHttp?style=social)
- github.com/kingsamchen/KAdBlockEngine ![Github stars](https://shields.io/github/stars/kingsamchen/KAdBlockEngine?style=social) ![Github forks](https://shields.io/github/forks/kingsamchen/KAdBlockEngine?style=social) ![Github watchers](https://shields.io/github/watchers/kingsamchen/KAdBlockEngine?style=social)
- github.com/kingsamchen/KLog ![Github stars](https://shields.io/github/stars/kingsamchen/KLog?style=social) ![Github forks](https://shields.io/github/forks/kingsamchen/KLog?style=social) ![Github watchers](https://shields.io/github/watchers/kingsamchen/KLog?style=social)
- github.com/kingsamchen/Eureka ![Github stars](https://shields.io/github/stars/kingsamchen/Eureka?style=social) ![Github forks](https://shields.io/github/forks/kingsamchen/Eureka?style=social) ![Github watchers](https://shields.io/github/watchers/kingsamchen/Eureka?style=social)
- zh-cn.libreoffice.org/
- github.com/GiovanniDicanio/WinReg ![Github stars](https://shields.io/github/stars/GiovanniDicanio/WinReg?style=social) ![Github forks](https://shields.io/github/forks/GiovanniDicanio/WinReg?style=social) ![Github watchers](https://shields.io/github/watchers/GiovanniDicanio/WinReg?style=social)
- github.com/GiovanniDicanio/StopwatchWin32 ![Github stars](https://shields.io/github/stars/GiovanniDicanio/StopwatchWin32?style=social) ![Github forks](https://shields.io/github/forks/GiovanniDicanio/StopwatchWin32?style=social) ![Github watchers](https://shields.io/github/watchers/GiovanniDicanio/StopwatchWin32?style=social)
- github.com/Wintellect/ProcMonDebugOutput ![Github stars](https://shields.io/github/stars/Wintellect/ProcMonDebugOutput?style=social) ![Github forks](https://shields.io/github/forks/Wintellect/ProcMonDebugOutput?style=social) ![Github watchers](https://shields.io/github/watchers/Wintellect/ProcMonDebugOutput?style=social)
- github.com/GiovanniDicanio/ReadStringsFromRegistry ![Github stars](https://shields.io/github/stars/GiovanniDicanio/ReadStringsFromRegistry?style=social) ![Github forks](https://shields.io/github/forks/GiovanniDicanio/ReadStringsFromRegistry?style=social) ![Github watchers](https://shields.io/github/watchers/GiovanniDicanio/ReadStringsFromRegistry?style=social)
- github.com/GiovanniDicanio/Utf8ConvAtlStl ![Github stars](https://shields.io/github/stars/GiovanniDicanio/Utf8ConvAtlStl?style=social) ![Github forks](https://shields.io/github/forks/GiovanniDicanio/Utf8ConvAtlStl?style=social) ![Github watchers](https://shields.io/github/watchers/GiovanniDicanio/Utf8ConvAtlStl?style=social)
- github.com/GiovanniDicanio/StringPool ![Github stars](https://shields.io/github/stars/GiovanniDicanio/StringPool?style=social) ![Github forks](https://shields.io/github/forks/GiovanniDicanio/StringPool?style=social) ![Github watchers](https://shields.io/github/watchers/GiovanniDicanio/StringPool?style=social)
- github.com/GiovanniDicanio/MapWithCaseInsensitiveStringKey ![Github stars](https://shields.io/github/stars/GiovanniDicanio/MapWithCaseInsensitiveStringKey?style=social) ![Github forks](https://shields.io/github/forks/GiovanniDicanio/MapWithCaseInsensitiveStringKey?style=social) ![Github watchers](https://shields.io/github/watchers/GiovanniDicanio/MapWithCaseInsensitiveStringKey?style=social)
- github.com/GiovanniDicanio/SafeArraySamples ![Github stars](https://shields.io/github/stars/GiovanniDicanio/SafeArraySamples?style=social) ![Github forks](https://shields.io/github/forks/GiovanniDicanio/SafeArraySamples?style=social) ![Github watchers](https://shields.io/github/watchers/GiovanniDicanio/SafeArraySamples?style=social)
- github.com/GiovanniDicanio/TestSSO ![Github stars](https://shields.io/github/stars/GiovanniDicanio/TestSSO?style=social) ![Github forks](https://shields.io/github/forks/GiovanniDicanio/TestSSO?style=social) ![Github watchers](https://shields.io/github/watchers/GiovanniDicanio/TestSSO?style=social)
- github.com/GiovanniDicanio/DoubleNulTerminatedString ![Github stars](https://shields.io/github/stars/GiovanniDicanio/DoubleNulTerminatedString?style=social) ![Github forks](https://shields.io/github/forks/GiovanniDicanio/DoubleNulTerminatedString?style=social) ![Github watchers](https://shields.io/github/watchers/GiovanniDicanio/DoubleNulTerminatedString?style=social)
- github.com/GiovanniDicanio/LoadingCedictBenchmarkCpp ![Github stars](https://shields.io/github/stars/GiovanniDicanio/LoadingCedictBenchmarkCpp?style=social) ![Github forks](https://shields.io/github/forks/GiovanniDicanio/LoadingCedictBenchmarkCpp?style=social) ![Github watchers](https://shields.io/github/watchers/GiovanniDicanio/LoadingCedictBenchmarkCpp?style=social)
- github.com/GiovanniDicanio/TestStringSorting ![Github stars](https://shields.io/github/stars/GiovanniDicanio/TestStringSorting?style=social) ![Github forks](https://shields.io/github/forks/GiovanniDicanio/TestStringSorting?style=social) ![Github watchers](https://shields.io/github/watchers/GiovanniDicanio/TestStringSorting?style=social)
- github.com/GiovanniDicanio/UnicodeConversions ![Github stars](https://shields.io/github/stars/GiovanniDicanio/UnicodeConversions?style=social) ![Github forks](https://shields.io/github/forks/GiovanniDicanio/UnicodeConversions?style=social) ![Github watchers](https://shields.io/github/watchers/GiovanniDicanio/UnicodeConversions?style=social)
- github.com/GiovanniDicanio/TestStringsAtlVsStl ![Github stars](https://shields.io/github/stars/GiovanniDicanio/TestStringsAtlVsStl?style=social) ![Github forks](https://shields.io/github/forks/GiovanniDicanio/TestStringsAtlVsStl?style=social) ![Github watchers](https://shields.io/github/watchers/GiovanniDicanio/TestStringsAtlVsStl?style=social)
- github.com/GiovanniDicanio/UnicodeConversionAtl ![Github stars](https://shields.io/github/stars/GiovanniDicanio/UnicodeConversionAtl?style=social) ![Github forks](https://shields.io/github/forks/GiovanniDicanio/UnicodeConversionAtl?style=social) ![Github watchers](https://shields.io/github/watchers/GiovanniDicanio/UnicodeConversionAtl?style=social)
- github.com/GiovanniDicanio/StlVectorVsListPerformance ![Github stars](https://shields.io/github/stars/GiovanniDicanio/StlVectorVsListPerformance?style=social) ![Github forks](https://shields.io/github/forks/GiovanniDicanio/StlVectorVsListPerformance?style=social) ![Github watchers](https://shields.io/github/watchers/GiovanniDicanio/StlVectorVsListPerformance?style=social)

## adblock

- github.com/adblockplus/adblockplusie ![Github stars](https://shields.io/github/stars/adblockplus/adblockplusie?style=social) ![Github forks](https://shields.io/github/forks/adblockplus/adblockplusie?style=social) ![Github watchers](https://shields.io/github/watchers/adblockplus/adblockplusie?style=social)
- github.com/adblockplus/adblockpluscore ![Github stars](https://shields.io/github/stars/adblockplus/adblockpluscore?style=social) ![Github forks](https://shields.io/github/forks/adblockplus/adblockpluscore?style=social) ![Github watchers](https://shields.io/github/watchers/adblockplus/adblockpluscore?style=social)
- github.com/adblockplus/libadblockplus ![Github stars](https://shields.io/github/stars/adblockplus/libadblockplus?style=social) ![Github forks](https://shields.io/github/forks/adblockplus/libadblockplus?style=social) ![Github watchers](https://shields.io/github/watchers/adblockplus/libadblockplus?style=social)

## bypass uac

- github.com/AzAgarampur/byeintegrity3-uac ![Github stars](https://shields.io/github/stars/AzAgarampur/byeintegrity3-uac?style=social) ![Github forks](https://shields.io/github/forks/AzAgarampur/byeintegrity3-uac?style=social) ![Github watchers](https://shields.io/github/watchers/AzAgarampur/byeintegrity3-uac?style=social)
- github.com/AzAgarampur/byeintegrity2-uac ![Github stars](https://shields.io/github/stars/AzAgarampur/byeintegrity2-uac?style=social) ![Github forks](https://shields.io/github/forks/AzAgarampur/byeintegrity2-uac?style=social) ![Github watchers](https://shields.io/github/watchers/AzAgarampur/byeintegrity2-uac?style=social)
- github.com/AzAgarampur/byeintegrity-uac ![Github stars](https://shields.io/github/stars/AzAgarampur/byeintegrity-uac?style=social) ![Github forks](https://shields.io/github/forks/AzAgarampur/byeintegrity-uac?style=social) ![Github watchers](https://shields.io/github/watchers/AzAgarampur/byeintegrity-uac?style=social)
- github.com/sailay1996/UAC_Bypass_In_The_Wild ![Github stars](https://shields.io/github/stars/sailay1996/UAC_Bypass_In_The_Wild?style=social) ![Github forks](https://shields.io/github/forks/sailay1996/UAC_Bypass_In_The_Wild?style=social) ![Github watchers](https://shields.io/github/watchers/sailay1996/UAC_Bypass_In_The_Wild?style=social)
- github.com/hfiref0x/UACME ![Github stars](https://shields.io/github/stars/hfiref0x/UACME?style=social) ![Github forks](https://shields.io/github/forks/hfiref0x/UACME?style=social) ![Github watchers](https://shields.io/github/watchers/hfiref0x/UACME?style=social)

## miscellaneous

- github.com/forrest-orr/artifacts-kit ![Github stars](https://shields.io/github/stars/forrest-orr/artifacts-kit?style=social) ![Github forks](https://shields.io/github/forks/forrest-orr/artifacts-kit?style=social) ![Github watchers](https://shields.io/github/watchers/forrest-orr/artifacts-kit?style=social)
- github.com/sailay1996/awesome_windows_logical_bugs ![Github stars](https://shields.io/github/stars/sailay1996/awesome_windows_logical_bugs?style=social) ![Github forks](https://shields.io/github/forks/sailay1996/awesome_windows_logical_bugs?style=social) ![Github watchers](https://shields.io/github/watchers/sailay1996/awesome_windows_logical_bugs?style=social)
- github.com/rabbitstack/fibratus (github.com/rabbitstack/fibratus) ![Github stars](https://shields.io/github/stars/rabbitstack/fibratus?style=social) ![Github forks](https://shields.io/github/forks/rabbitstack/fibratus?style=social) ![Github watchers](https://shields.io/github/watchers/rabbitstack/fibratus?style=social)
- github.com/theopolis/uefi-firmware-parser ![Github stars](https://shields.io/github/stars/theopolis/uefi-firmware-parser?style=social) ![Github forks](https://shields.io/github/forks/theopolis/uefi-firmware-parser?style=social) ![Github watchers](https://shields.io/github/watchers/theopolis/uefi-firmware-parser?style=social)
- github.com/z175/kdmapper ![Github stars](https://shields.io/github/stars/z175/kdmapper?style=social) ![Github forks](https://shields.io/github/forks/z175/kdmapper?style=social) ![Github watchers](https://shields.io/github/watchers/z175/kdmapper?style=social)
- github.com/heckerli/netshield ![Github stars](https://shields.io/github/stars/heckerli/netshield?style=social) ![Github forks](https://shields.io/github/forks/heckerli/netshield?style=social) ![Github watchers](https://shields.io/github/watchers/heckerli/netshield?style=social)
- github.com/TalAloni/SMBLibrary ![Github stars](https://shields.io/github/stars/TalAloni/SMBLibrary?style=social) ![Github forks](https://shields.io/github/forks/TalAloni/SMBLibrary?style=social) ![Github watchers](https://shields.io/github/watchers/TalAloni/SMBLibrary?style=social)
- www.unknowncheats.me/forum/c-and-c-/179852-ring0-random-string-generator-kernel-driver.html
- github.com/gztss/SerialTool (serial debug tool) ![Github stars](https://shields.io/github/stars/gztss/SerialTool?style=social) ![Github forks](https://shields.io/github/forks/gztss/SerialTool?style=social) ![Github watchers](https://shields.io/github/watchers/gztss/SerialTool?style=social)
- github.com/platomav/CPUMicrocodes ![Github stars](https://shields.io/github/stars/platomav/CPUMicrocodes?style=social) ![Github forks](https://shields.io/github/forks/platomav/CPUMicrocodes?style=social) ![Github watchers](https://shields.io/github/watchers/platomav/CPUMicrocodes?style=social)
- github.com/DavexPro/PocHunter ![Github stars](https://shields.io/github/stars/DavexPro/PocHunter?style=social) ![Github forks](https://shields.io/github/forks/DavexPro/PocHunter?style=social) ![Github watchers](https://shields.io/github/watchers/DavexPro/PocHunter?style=social)
- github.com/Microsoft/Windows-universal-samples ![Github stars](https://shields.io/github/stars/Microsoft/Windows-universal-samples?style=social) ![Github forks](https://shields.io/github/forks/Microsoft/Windows-universal-samples?style=social) ![Github watchers](https://shields.io/github/watchers/Microsoft/Windows-universal-samples?style=social)
- github.com/ionescu007/wnfun ![Github stars](https://shields.io/github/stars/ionescu007/wnfun?style=social) ![Github forks](https://shields.io/github/forks/ionescu007/wnfun?style=social) ![Github watchers](https://shields.io/github/watchers/ionescu007/wnfun?style=social)
- github.com/waryas/UMPMLib ![Github stars](https://shields.io/github/stars/waryas/UMPMLib?style=social) ![Github forks](https://shields.io/github/forks/waryas/UMPMLib?style=social) ![Github watchers](https://shields.io/github/watchers/waryas/UMPMLib?style=social)
- github.com/MeeSong/Windows_OS_Internals_Curriculum_Resource_Kit-ACADEMIC ![Github stars](https://shields.io/github/stars/MeeSong/Windows_OS_Internals_Curriculum_Resource_Kit-ACADEMIC?style=social) ![Github forks](https://shields.io/github/forks/MeeSong/Windows_OS_Internals_Curriculum_Resource_Kit-ACADEMIC?style=social) ![Github watchers](https://shields.io/github/watchers/MeeSong/Windows_OS_Internals_Curriculum_Resource_Kit-ACADEMIC?style=social)
- github.com/piaoyunsoft/WebRedemption ![Github stars](https://shields.io/github/stars/piaoyunsoft/WebRedemption?style=social) ![Github forks](https://shields.io/github/forks/piaoyunsoft/WebRedemption?style=social) ![Github watchers](https://shields.io/github/watchers/piaoyunsoft/WebRedemption?style=social)
- github.com/sudoconf/http_encode ![Github stars](https://shields.io/github/stars/sudoconf/http_encode?style=social) ![Github forks](https://shields.io/github/forks/sudoconf/http_encode?style=social) ![Github watchers](https://shields.io/github/watchers/sudoconf/http_encode?style=social)
- github.com/wjcsharp/wintools ![Github stars](https://shields.io/github/stars/wjcsharp/wintools?style=social) ![Github forks](https://shields.io/github/forks/wjcsharp/wintools?style=social) ![Github watchers](https://shields.io/github/watchers/wjcsharp/wintools?style=social)
- github.com/nmgwddj/HttpSourceViewer ![Github stars](https://shields.io/github/stars/nmgwddj/HttpSourceViewer?style=social) ![Github forks](https://shields.io/github/forks/nmgwddj/HttpSourceViewer?style=social) ![Github watchers](https://shields.io/github/watchers/nmgwddj/HttpSourceViewer?style=social)
- github.com/nmgwddj/nvapi-example (Digital Vibrance Controls) ![Github stars](https://shields.io/github/stars/nmgwddj/nvapi-example?style=social) ![Github forks](https://shields.io/github/forks/nmgwddj/nvapi-example?style=social) ![Github watchers](https://shields.io/github/watchers/nmgwddj/nvapi-example?style=social)
- github.com/n1nj4sec/memorpy ![Github stars](https://shields.io/github/stars/n1nj4sec/memorpy?style=social) ![Github forks](https://shields.io/github/forks/n1nj4sec/memorpy?style=social) ![Github watchers](https://shields.io/github/watchers/n1nj4sec/memorpy?style=social)
- github.com/TinyCC/tinycc ![Github stars](https://shields.io/github/stars/TinyCC/tinycc?style=social) ![Github forks](https://shields.io/github/forks/TinyCC/tinycc?style=social) ![Github watchers](https://shields.io/github/watchers/TinyCC/tinycc?style=social)
- github.com/msuhanov/regf (reg formats) ![Github stars](https://shields.io/github/stars/msuhanov/regf?style=social) ![Github forks](https://shields.io/github/forks/msuhanov/regf?style=social) ![Github watchers](https://shields.io/github/watchers/msuhanov/regf?style=social)
- github.com/beader/tianchi-3rd_security ![Github stars](https://shields.io/github/stars/beader/tianchi-3rd_security?style=social) ![Github forks](https://shields.io/github/forks/beader/tianchi-3rd_security?style=social) ![Github watchers](https://shields.io/github/watchers/beader/tianchi-3rd_security?style=social)
- github.com/Schnocker/HLeaker ![Github stars](https://shields.io/github/stars/Schnocker/HLeaker?style=social) ![Github forks](https://shields.io/github/forks/Schnocker/HLeaker?style=social) ![Github watchers](https://shields.io/github/watchers/Schnocker/HLeaker?style=social)
- www.geoffchappell.com/studies/windows/km/index.htm (reverse)
- github.com/AntiRootkit/HandleSpy ![Github stars](https://shields.io/github/stars/AntiRootkit/HandleSpy?style=social) ![Github forks](https://shields.io/github/forks/AntiRootkit/HandleSpy?style=social) ![Github watchers](https://shields.io/github/watchers/AntiRootkit/HandleSpy?style=social)
- github.com/securifera/HeapMonitor ![Github stars](https://shields.io/github/stars/securifera/HeapMonitor?style=social) ![Github forks](https://shields.io/github/forks/securifera/HeapMonitor?style=social) ![Github watchers](https://shields.io/github/watchers/securifera/HeapMonitor?style=social)
- github.com/securifera/serviceFu ![Github stars](https://shields.io/github/stars/securifera/serviceFu?style=social) ![Github forks](https://shields.io/github/forks/securifera/serviceFu?style=social) ![Github watchers](https://shields.io/github/watchers/securifera/serviceFu?style=social)
- github.com/mq1n/WSWatcher ![Github stars](https://shields.io/github/stars/mq1n/WSWatcher?style=social) ![Github forks](https://shields.io/github/forks/mq1n/WSWatcher?style=social) ![Github watchers](https://shields.io/github/watchers/mq1n/WSWatcher?style=social)
- github.com/imagemlt/EasyKnife (CKnife) ![Github stars](https://shields.io/github/stars/imagemlt/EasyKnife?style=social) ![Github forks](https://shields.io/github/forks/imagemlt/EasyKnife?style=social) ![Github watchers](https://shields.io/github/watchers/imagemlt/EasyKnife?style=social)
- github.com/didi/kemon (macOS Kernel Monitoring Callback Framework) ![Github stars](https://shields.io/github/stars/didi/kemon?style=social) ![Github forks](https://shields.io/github/forks/didi/kemon?style=social) ![Github watchers](https://shields.io/github/watchers/didi/kemon?style=social)
- github.com/Microsoft/microsoft-pdb (pdb format) ![Github stars](https://shields.io/github/stars/Microsoft/microsoft-pdb?style=social) ![Github forks](https://shields.io/github/forks/Microsoft/microsoft-pdb?style=social) ![Github watchers](https://shields.io/github/watchers/Microsoft/microsoft-pdb?style=social)
- github.com/Darm64/XNU ![Github stars](https://shields.io/github/stars/Darm64/XNU?style=social) ![Github forks](https://shields.io/github/forks/Darm64/XNU?style=social) ![Github watchers](https://shields.io/github/watchers/Darm64/XNU?style=social)
- github.com/netromdk/bmod ![Github stars](https://shields.io/github/stars/netromdk/bmod?style=social) ![Github forks](https://shields.io/github/forks/netromdk/bmod?style=social) ![Github watchers](https://shields.io/github/watchers/netromdk/bmod?style=social)
- github.com/rgl/windows-domain-controller-vagrant ![Github stars](https://shields.io/github/stars/rgl/windows-domain-controller-vagrant?style=social) ![Github forks](https://shields.io/github/forks/rgl/windows-domain-controller-vagrant?style=social) ![Github watchers](https://shields.io/github/watchers/rgl/windows-domain-controller-vagrant?style=social)
- github.com/panda-re/panda ![Github stars](https://shields.io/github/stars/panda-re/panda?style=social) ![Github forks](https://shields.io/github/forks/panda-re/panda?style=social) ![Github watchers](https://shields.io/github/watchers/panda-re/panda?style=social)
- github.com/DarkSpiritz/DarkSpiritz ![Github stars](https://shields.io/github/stars/DarkSpiritz/DarkSpiritz?style=social) ![Github forks](https://shields.io/github/forks/DarkSpiritz/DarkSpiritz?style=social) ![Github watchers](https://shields.io/github/watchers/DarkSpiritz/DarkSpiritz?style=social)
- rayanfam.com/topics/inline-assembly-in-x64/  (x64 inline asm)
- www.jianshu.com/p/15be72d919ff (traversing the icon on the desktop)
- github.com/nshalabi/SysmonTools ![Github stars](https://shields.io/github/stars/nshalabi/SysmonTools?style=social) ![Github forks](https://shields.io/github/forks/nshalabi/SysmonTools?style=social) ![Github watchers](https://shields.io/github/watchers/nshalabi/SysmonTools?style=social)
- github.com/nshalabi/ATTACK-Tools ![Github stars](https://shields.io/github/stars/nshalabi/ATTACK-Tools?style=social) ![Github forks](https://shields.io/github/forks/nshalabi/ATTACK-Tools?style=social) ![Github watchers](https://shields.io/github/watchers/nshalabi/ATTACK-Tools?style=social)
- github.com/ExpLife0011/hf-2012 ![Github stars](https://shields.io/github/stars/ExpLife0011/hf-2012?style=social) ![Github forks](https://shields.io/github/forks/ExpLife0011/hf-2012?style=social) ![Github watchers](https://shields.io/github/watchers/ExpLife0011/hf-2012?style=social)
- github.com/tyranid/windows-attacksurface-workshop/ (2018) ![Github stars](https://shields.io/github/stars/tyranid/windows-attacksurface-workshop?style=social) ![Github forks](https://shields.io/github/forks/tyranid/windows-attacksurface-workshop?style=social) ![Github watchers](https://shields.io/github/watchers/tyranid/windows-attacksurface-workshop?style=social)
- github.com/CherryPill/system_info ![Github stars](https://shields.io/github/stars/CherryPill/system_info?style=social) ![Github forks](https://shields.io/github/forks/CherryPill/system_info?style=social) ![Github watchers](https://shields.io/github/watchers/CherryPill/system_info?style=social)
- github.com/muxq/DPAPI ![Github stars](https://shields.io/github/stars/muxq/DPAPI?style=social) ![Github forks](https://shields.io/github/forks/muxq/DPAPI?style=social) ![Github watchers](https://shields.io/github/watchers/muxq/DPAPI?style=social)
- github.com/ExpLife/directntapi ![Github stars](https://shields.io/github/stars/ExpLife/directntapi?style=social) ![Github forks](https://shields.io/github/forks/ExpLife/directntapi?style=social) ![Github watchers](https://shields.io/github/watchers/ExpLife/directntapi?style=social)
- github.com/gaozan198912/myproject ![Github stars](https://shields.io/github/stars/gaozan198912/myproject?style=social) ![Github forks](https://shields.io/github/forks/gaozan198912/myproject?style=social) ![Github watchers](https://shields.io/github/watchers/gaozan198912/myproject?style=social)
- github.com/k0keoyo/ntoskrnl-symbol-pdb-and-undocument-structures ![Github stars](https://shields.io/github/stars/k0keoyo/ntoskrnl-symbol-pdb-and-undocument-structures?style=social) ![Github forks](https://shields.io/github/forks/k0keoyo/ntoskrnl-symbol-pdb-and-undocument-structures?style=social) ![Github watchers](https://shields.io/github/watchers/k0keoyo/ntoskrnl-symbol-pdb-and-undocument-structures?style=social)
- github.com/gentilkiwi/p11proxy ![Github stars](https://shields.io/github/stars/gentilkiwi/p11proxy?style=social) ![Github forks](https://shields.io/github/forks/gentilkiwi/p11proxy?style=social) ![Github watchers](https://shields.io/github/watchers/gentilkiwi/p11proxy?style=social)
- github.com/gentilkiwi/kekeo ![Github stars](https://shields.io/github/stars/gentilkiwi/kekeo?style=social) ![Github forks](https://shields.io/github/forks/gentilkiwi/kekeo?style=social) ![Github watchers](https://shields.io/github/watchers/gentilkiwi/kekeo?style=social)
- github.com/ExpLife/ByPassCfg ![Github stars](https://shields.io/github/stars/ExpLife/ByPassCfg?style=social) ![Github forks](https://shields.io/github/forks/ExpLife/ByPassCfg?style=social) ![Github watchers](https://shields.io/github/watchers/ExpLife/ByPassCfg?style=social)
- github.com/hfiref0x/SXSEXP ![Github stars](https://shields.io/github/stars/hfiref0x/SXSEXP?style=social) ![Github forks](https://shields.io/github/forks/hfiref0x/SXSEXP?style=social) ![Github watchers](https://shields.io/github/watchers/hfiref0x/SXSEXP?style=social)
- github.com/hfiref0x/VBoxHardenedLoader ![Github stars](https://shields.io/github/stars/hfiref0x/VBoxHardenedLoader?style=social) ![Github forks](https://shields.io/github/forks/hfiref0x/VBoxHardenedLoader?style=social) ![Github watchers](https://shields.io/github/watchers/hfiref0x/VBoxHardenedLoader?style=social)
- github.com/hfiref0x/SyscallTables ![Github stars](https://shields.io/github/stars/hfiref0x/SyscallTables?style=social) ![Github forks](https://shields.io/github/forks/hfiref0x/SyscallTables?style=social) ![Github watchers](https://shields.io/github/watchers/hfiref0x/SyscallTables?style=social)
- github.com/hfiref0x/WinObjEx64 ![Github stars](https://shields.io/github/stars/hfiref0x/WinObjEx64?style=social) ![Github forks](https://shields.io/github/forks/hfiref0x/WinObjEx64?style=social) ![Github watchers](https://shields.io/github/watchers/hfiref0x/WinObjEx64?style=social)
- github.com/Cr4sh/DbgCb ![Github stars](https://shields.io/github/stars/Cr4sh/DbgCb?style=social) ![Github forks](https://shields.io/github/forks/Cr4sh/DbgCb?style=social) ![Github watchers](https://shields.io/github/watchers/Cr4sh/DbgCb?style=social)
- github.com/Cr4sh/s6_pcie_microblaze ![Github stars](https://shields.io/github/stars/Cr4sh/s6_pcie_microblaze?style=social) ![Github forks](https://shields.io/github/forks/Cr4sh/s6_pcie_microblaze?style=social) ![Github watchers](https://shields.io/github/watchers/Cr4sh/s6_pcie_microblaze?style=social)
- github.com/ionescu007/SpecuCheck ![Github stars](https://shields.io/github/stars/ionescu007/SpecuCheck?style=social) ![Github forks](https://shields.io/github/forks/ionescu007/SpecuCheck?style=social) ![Github watchers](https://shields.io/github/watchers/ionescu007/SpecuCheck?style=social)
- github.com/ionescu007/lxss ![Github stars](https://shields.io/github/stars/ionescu007/lxss?style=social) ![Github forks](https://shields.io/github/forks/ionescu007/lxss?style=social) ![Github watchers](https://shields.io/github/watchers/ionescu007/lxss?style=social)
- github.com/intel/haxm ![Github stars](https://shields.io/github/stars/intel/haxm?style=social) ![Github forks](https://shields.io/github/forks/intel/haxm?style=social) ![Github watchers](https://shields.io/github/watchers/intel/haxm?style=social)
- github.com/akayn/Resources ![Github stars](https://shields.io/github/stars/akayn/Resources?style=social) ![Github forks](https://shields.io/github/forks/akayn/Resources?style=social) ![Github watchers](https://shields.io/github/watchers/akayn/Resources?style=social)
- github.com/DarthTon/SecureEraseWin ![Github stars](https://shields.io/github/stars/DarthTon/SecureEraseWin?style=social) ![Github forks](https://shields.io/github/forks/DarthTon/SecureEraseWin?style=social) ![Github watchers](https://shields.io/github/watchers/DarthTon/SecureEraseWin?style=social)
- github.com/tinysec/windows-syscall-table ![Github stars](https://shields.io/github/stars/tinysec/windows-syscall-table?style=social) ![Github forks](https://shields.io/github/forks/tinysec/windows-syscall-table?style=social) ![Github watchers](https://shields.io/github/watchers/tinysec/windows-syscall-table?style=social)
- github.com/tinysec/jsrt ![Github stars](https://shields.io/github/stars/tinysec/jsrt?style=social) ![Github forks](https://shields.io/github/forks/tinysec/jsrt?style=social) ![Github watchers](https://shields.io/github/watchers/tinysec/jsrt?style=social)
- github.com/zodiacon/DriverMon ![Github stars](https://shields.io/github/stars/zodiacon/DriverMon?style=social) ![Github forks](https://shields.io/github/forks/zodiacon/DriverMon?style=social) ![Github watchers](https://shields.io/github/watchers/zodiacon/DriverMon?style=social)
- github.com/zodiacon/GflagsX ![Github stars](https://shields.io/github/stars/zodiacon/GflagsX?style=social) ![Github forks](https://shields.io/github/forks/zodiacon/GflagsX?style=social) ![Github watchers](https://shields.io/github/watchers/zodiacon/GflagsX?style=social)
- github.com/zodiacon/PEExplorer ![Github stars](https://shields.io/github/stars/zodiacon/PEExplorer?style=social) ![Github forks](https://shields.io/github/forks/zodiacon/PEExplorer?style=social) ![Github watchers](https://shields.io/github/watchers/zodiacon/PEExplorer?style=social)
- github.com/zodiacon/KernelExplorer ![Github stars](https://shields.io/github/stars/zodiacon/KernelExplorer?style=social) ![Github forks](https://shields.io/github/forks/zodiacon/KernelExplorer?style=social) ![Github watchers](https://shields.io/github/watchers/zodiacon/KernelExplorer?style=social)
- github.com/zodiacon/AllTools ![Github stars](https://shields.io/github/stars/zodiacon/AllTools?style=social) ![Github forks](https://shields.io/github/forks/zodiacon/AllTools?style=social) ![Github watchers](https://shields.io/github/watchers/zodiacon/AllTools?style=social)
- github.com/zodiacon/WindowsInternals ![Github stars](https://shields.io/github/stars/zodiacon/WindowsInternals?style=social) ![Github forks](https://shields.io/github/forks/zodiacon/WindowsInternals?style=social) ![Github watchers](https://shields.io/github/watchers/zodiacon/WindowsInternals?style=social)
- github.com/hackedteam/vector-silent ![Github stars](https://shields.io/github/stars/hackedteam/vector-silent?style=social) ![Github forks](https://shields.io/github/forks/hackedteam/vector-silent?style=social) ![Github watchers](https://shields.io/github/watchers/hackedteam/vector-silent?style=social)
- github.com/hackedteam/core-packer ![Github stars](https://shields.io/github/stars/hackedteam/core-packer?style=social) ![Github forks](https://shields.io/github/forks/hackedteam/core-packer?style=social) ![Github watchers](https://shields.io/github/watchers/hackedteam/core-packer?style=social)
- github.com/hackedteam/vector-recover ![Github stars](https://shields.io/github/stars/hackedteam/vector-recover?style=social) ![Github forks](https://shields.io/github/forks/hackedteam/vector-recover?style=social) ![Github watchers](https://shields.io/github/watchers/hackedteam/vector-recover?style=social)
- github.com/k33nteam/cc-shellcoding ![Github stars](https://shields.io/github/stars/k33nteam/cc-shellcoding?style=social) ![Github forks](https://shields.io/github/forks/k33nteam/cc-shellcoding?style=social) ![Github watchers](https://shields.io/github/watchers/k33nteam/cc-shellcoding?style=social)
- github.com/rwfpl/rewolf-wow64ext ![Github stars](https://shields.io/github/stars/rwfpl/rewolf-wow64ext?style=social) ![Github forks](https://shields.io/github/forks/rwfpl/rewolf-wow64ext?style=social) ![Github watchers](https://shields.io/github/watchers/rwfpl/rewolf-wow64ext?style=social)
- github.com/rwfpl/rewolf-x86-virtualizer ![Github stars](https://shields.io/github/stars/rwfpl/rewolf-x86-virtualizer?style=social) ![Github forks](https://shields.io/github/forks/rwfpl/rewolf-x86-virtualizer?style=social) ![Github watchers](https://shields.io/github/watchers/rwfpl/rewolf-x86-virtualizer?style=social)
- github.com/rwfpl/rewolf-gogogadget ![Github stars](https://shields.io/github/stars/rwfpl/rewolf-gogogadget?style=social) ![Github forks](https://shields.io/github/forks/rwfpl/rewolf-gogogadget?style=social) ![Github watchers](https://shields.io/github/watchers/rwfpl/rewolf-gogogadget?style=social)
- github.com/rwfpl/rewolf-dllpackager ![Github stars](https://shields.io/github/stars/rwfpl/rewolf-dllpackager?style=social) ![Github forks](https://shields.io/github/forks/rwfpl/rewolf-dllpackager?style=social) ![Github watchers](https://shields.io/github/watchers/rwfpl/rewolf-dllpackager?style=social)
- github.com/Microsoft/ChakraCore ![Github stars](https://shields.io/github/stars/Microsoft/ChakraCore?style=social) ![Github forks](https://shields.io/github/forks/Microsoft/ChakraCore?style=social) ![Github watchers](https://shields.io/github/watchers/Microsoft/ChakraCore?style=social)
- github.com/google/symboliclink-testing-tools ![Github stars](https://shields.io/github/stars/google/symboliclink-testing-tools?style=social) ![Github forks](https://shields.io/github/forks/google/symboliclink-testing-tools?style=social) ![Github watchers](https://shields.io/github/watchers/google/symboliclink-testing-tools?style=social)
- github.com/ptresearch/IntelME-JTAG ![Github stars](https://shields.io/github/stars/ptresearch/IntelME-JTAG?style=social) ![Github forks](https://shields.io/github/forks/ptresearch/IntelME-JTAG?style=social) ![Github watchers](https://shields.io/github/watchers/ptresearch/IntelME-JTAG?style=social)
- github.com/smourier/TraceSpy ![Github stars](https://shields.io/github/stars/smourier/TraceSpy?style=social) ![Github forks](https://shields.io/github/forks/smourier/TraceSpy?style=social) ![Github watchers](https://shields.io/github/watchers/smourier/TraceSpy?style=social)
- github.com/G-E-N-E-S-I-S/tasklist-brutus ![Github stars](https://shields.io/github/stars/G-E-N-E-S-I-S/tasklist-brutus?style=social) ![Github forks](https://shields.io/github/forks/G-E-N-E-S-I-S/tasklist-brutus?style=social) ![Github watchers](https://shields.io/github/watchers/G-E-N-E-S-I-S/tasklist-brutus?style=social)
- github.com/G-E-N-E-S-I-S/token_manipulation ![Github stars](https://shields.io/github/stars/G-E-N-E-S-I-S/token_manipulation?style=social) ![Github forks](https://shields.io/github/forks/G-E-N-E-S-I-S/token_manipulation?style=social) ![Github watchers](https://shields.io/github/watchers/G-E-N-E-S-I-S/token_manipulation?style=social)
- github.com/jjzhang166/sdk ![Github stars](https://shields.io/github/stars/jjzhang166/sdk?style=social) ![Github forks](https://shields.io/github/forks/jjzhang166/sdk?style=social) ![Github watchers](https://shields.io/github/watchers/jjzhang166/sdk?style=social)
- github.com/killswitch-GUI/HotLoad-Driver ![Github stars](https://shields.io/github/stars/killswitch-GUI/HotLoad-Driver?style=social) ![Github forks](https://shields.io/github/forks/killswitch-GUI/HotLoad-Driver?style=social) ![Github watchers](https://shields.io/github/watchers/killswitch-GUI/HotLoad-Driver?style=social)
- github.com/killswitch-GUI/minidump-lib ![Github stars](https://shields.io/github/stars/killswitch-GUI/minidump-lib?style=social) ![Github forks](https://shields.io/github/forks/killswitch-GUI/minidump-lib?style=social) ![Github watchers](https://shields.io/github/watchers/killswitch-GUI/minidump-lib?style=social)
- github.com/killswitch-GUI/win32-named-pipes-example ![Github stars](https://shields.io/github/stars/killswitch-GUI/win32-named-pipes-example?style=social) ![Github forks](https://shields.io/github/forks/killswitch-GUI/win32-named-pipes-example?style=social) ![Github watchers](https://shields.io/github/watchers/killswitch-GUI/win32-named-pipes-example?style=social)
- github.com/Kelvinhack/ScreenCapAttack ![Github stars](https://shields.io/github/stars/Kelvinhack/ScreenCapAttack?style=social) ![Github forks](https://shields.io/github/forks/Kelvinhack/ScreenCapAttack?style=social) ![Github watchers](https://shields.io/github/watchers/Kelvinhack/ScreenCapAttack?style=social)
- github.com/tyranid/oleviewdotnet ![Github stars](https://shields.io/github/stars/tyranid/oleviewdotnet?style=social) ![Github forks](https://shields.io/github/forks/tyranid/oleviewdotnet?style=social) ![Github watchers](https://shields.io/github/watchers/tyranid/oleviewdotnet?style=social)
- github.com/tyranid/CANAPE.Core ![Github stars](https://shields.io/github/stars/tyranid/CANAPE.Core?style=social) ![Github forks](https://shields.io/github/forks/tyranid/CANAPE.Core?style=social) ![Github watchers](https://shields.io/github/watchers/tyranid/CANAPE.Core?style=social)
- github.com/tyranid/DotNetToJScript ![Github stars](https://shields.io/github/stars/tyranid/DotNetToJScript?style=social) ![Github forks](https://shields.io/github/forks/tyranid/DotNetToJScript?style=social) ![Github watchers](https://shields.io/github/watchers/tyranid/DotNetToJScript?style=social)

## slides

- security.cs.rpi.edu/courses/binexp-spring2015
- rmusser.net/docs/
- keenlab.tencent.com/zh

## blogs

- voidsec.com/category/blog/ (windows kernel fuzz & exploit)
- www.anquanke.com/subject/id/221009 (windows debug)
- www.cnblogs.com/theseventhson/default.html?page=10 (web/binary sec)
- redogwu.github.io (kernel exp)
- docs.microsoft.com/zh-cn/windows-hardware/drivers/debugger/debug-universal-drivers--kernel-mode-#kernelmodedebuggingcommandsandtechniques (windbg help)
- www.dbgtech.net (windbg help)
- blog.csdn.net/hgy413/article/details/7054870 (windbg  usage)
- guidedhacking.com (game hack)
- kdext.com/links.html
- www.reconstructer.org/papers/Hunting%20rootkits%20with%20Windbg.pdf
- www.slideshare.net/MSbluehat/bluehat-v18-memory-resident-implants-code-injection-is-alive-and-well
- www.sekoia.fr/blog
- docs.microsoft.com/en-us/windows-hardware/drivers/kernel/single-binary-opt-in-pool-nx-optin (VS WDK Config)
- blog.csdn.net/qq_18218335/article/details/77480475 (VS WDK Config)
- docs.microsoft.com/zh-cn/previous-versions//jj572863(v=vs.85) (VS WDK Config)
- blog.csdn.net/lpwstr/article/details/81190171 (VS WDK Config)
- www.yiiyee.cn/Blog/win8-driver/
- blog.csdn.net/liwen930723
- ktkitty.github.io/ (vul)
- secrary.com/RandomPosts
- www.mycode.net.cn
- split-code.com
- eternalsakura13.com
- xiaodaozhi.com
- blog.vicayang.cc/
- www.fwhibbit.es/sysmon-the-big-brother-of-windows-and-the-super-sysmonview
- dedbg.com/
- leguanyuan.blogspot.com
- www.geoffchappell.com/studies/windows/km/ntoskrnl/api/ex/profile/bugdemo.htm
- blog.can.ac
- b33t1e.github.io/2018/01/03/About-VMProtect/
- www.diting0x.com/
- lotabout.me/archives/ (write a c interpreter)
- 2997ms.com/2016/10/09/2016/2016-9%E6%9C%88-%E5%90%AD%E5%93%A7%E5%92%94%E5%93%A7/
- www.trueai.cn/
- whereisk0shl.top
- www.anquanke.com/post/id/97245
- lifeinhex.com
- vallejo.cc/2017/11/18/installation-and-first-contact-with-the-new-windbg/
- www.vxjump.net/
- channel9.msdn.com/Shows/Defrag-Tools
- windbg.info/
- windbg.org/
- msdn.microsoft.com/en-us/library/windows/hardware/ff553217(v=vs.85).aspx
- www.andreybazhan.com/
- blogs.technet.microsoft.com/markrussinovich/
- undocumented.ntinternals.net/
- j00ru.vexillium.org/
- sysprogs.com/
- www.rohitab.com/
- sww-it.ru/
- blogs.microsoft.co.il/pavely/
- www.corelan.be/
- tombkeeper.blog.techweb.com.cn/
- www.zer0mem.sk/
- blog.rewolf.pl/blog/
- www.alex-ionescu.com/
- blog.cr4.sh/
- rootkits.xyz/
- ixyzero.com/blog/archives/3543.html
- whereisk0shl.top/
- www.triplefault.io/2017/09/enumerating-process-thread-and-image.html
- doar-e.github.io/blog/2017/12/01/debugger-data-model/
- docs.microsoft.com/en-us/windows-hardware/drivers/debugger/debugging-using-windbg-preview
- blog.xpnsec.com/
- www.fireeye.com/blog/threat-research/2018/01/simplifying-graphs-in-ida.html
- gosecure.net/2018/01/10/vmware-horizon-v4h-v4pa-desktop-agent-privilege-escalation-vulnerability-cve-2017-4946/
- www.msreverseengineering.com/blog/2018/1/23/a-walk-through-tutorial-with-code-on-statically-unpacking-the-finspy-vm-part-one-x86-deobfuscation

## sec tools

- securityxploded.com

## waf

- github.com/SpiderLabs/ModSecurity ![Github stars](https://shields.io/github/stars/SpiderLabs/ModSecurity?style=social) ![Github forks](https://shields.io/github/forks/SpiderLabs/ModSecurity?style=social) ![Github watchers](https://shields.io/github/watchers/SpiderLabs/ModSecurity?style=social)

## web security research site

- pagedout.institute/
- github.com/frizb/Bypassing-Web-Application-Firewalls (bypass waf) ![Github stars](https://shields.io/github/stars/frizb/Bypassing-Web-Application-Firewalls?style=social) ![Github forks](https://shields.io/github/forks/frizb/Bypassing-Web-Application-Firewalls?style=social) ![Github watchers](https://shields.io/github/watchers/frizb/Bypassing-Web-Application-Firewalls?style=social)
- malware-traffic-analysis.net
- malwaretips.com/
- www.sec-wiki.com
- www.anquanke.com/
- xuanwulab.github.io/cn/secnews/2018/02/08/index.html
- www.vxjump.net/
- www.pediy.com/
- navisec.it/
- www.secbang.com/

## development documents

- devdocs.io/
- zealdocs.org/

## browser automated test

- github.com/florentbr/SeleniumBasic ![Github stars](https://shields.io/github/stars/florentbr/SeleniumBasic?style=social) ![Github forks](https://shields.io/github/forks/florentbr/SeleniumBasic?style=social) ![Github watchers](https://shields.io/github/watchers/florentbr/SeleniumBasic?style=social)

## docker

- dockone.io/search/q-RG9ja09uZeaKgOacr+WIhuS6qw==#articles

## leaked source code

- github.com/cocus/openmsvbvm ![Github stars](https://shields.io/github/stars/cocus/openmsvbvm?style=social) ![Github forks](https://shields.io/github/forks/cocus/openmsvbvm?style=social) ![Github watchers](https://shields.io/github/watchers/cocus/openmsvbvm?style=social)
- github.com/misterch0c/shadowbroker (NSA) ![Github stars](https://shields.io/github/stars/misterch0c/shadowbroker?style=social) ![Github forks](https://shields.io/github/forks/misterch0c/shadowbroker?style=social) ![Github watchers](https://shields.io/github/watchers/misterch0c/shadowbroker?style=social)
- github.com/pustladi/Windows-2000 ![Github stars](https://shields.io/github/stars/pustladi/Windows-2000?style=social) ![Github forks](https://shields.io/github/forks/pustladi/Windows-2000?style=social) ![Github watchers](https://shields.io/github/watchers/pustladi/Windows-2000?style=social)
- github.com/killbug2004/NT_4.0_SourceCode ![Github stars](https://shields.io/github/stars/killbug2004/NT_4.0_SourceCode?style=social) ![Github forks](https://shields.io/github/forks/killbug2004/NT_4.0_SourceCode?style=social) ![Github watchers](https://shields.io/github/watchers/killbug2004/NT_4.0_SourceCode?style=social)
- github.com/pustladi/TrueCrypt-7.2 ![Github stars](https://shields.io/github/stars/pustladi/TrueCrypt-7.2?style=social) ![Github forks](https://shields.io/github/forks/pustladi/TrueCrypt-7.2?style=social) ![Github watchers](https://shields.io/github/watchers/pustladi/TrueCrypt-7.2?style=social)
- github.com/pustladi/MS-DOS-v.1.1 ![Github stars](https://shields.io/github/stars/pustladi/MS-DOS-v.1.1?style=social) ![Github forks](https://shields.io/github/forks/pustladi/MS-DOS-v.1.1?style=social) ![Github watchers](https://shields.io/github/watchers/pustladi/MS-DOS-v.1.1?style=social)
- github.com/pustladi/MS-DOS-v.2.0 ![Github stars](https://shields.io/github/stars/pustladi/MS-DOS-v.2.0?style=social) ![Github forks](https://shields.io/github/forks/pustladi/MS-DOS-v.2.0?style=social) ![Github watchers](https://shields.io/github/watchers/pustladi/MS-DOS-v.2.0?style=social)

## sspi

- github.com/deemru/msspi ![Github stars](https://shields.io/github/stars/deemru/msspi?style=social) ![Github forks](https://shields.io/github/forks/deemru/msspi?style=social) ![Github watchers](https://shields.io/github/watchers/deemru/msspi?style=social)
- github.com/vletoux/DetectPasswordViaNTLMInFlow ![Github stars](https://shields.io/github/stars/vletoux/DetectPasswordViaNTLMInFlow?style=social) ![Github forks](https://shields.io/github/forks/vletoux/DetectPasswordViaNTLMInFlow?style=social) ![Github watchers](https://shields.io/github/watchers/vletoux/DetectPasswordViaNTLMInFlow?style=social)
- github.com/judek/sspiauthenticate ![Github stars](https://shields.io/github/stars/judek/sspiauthenticate?style=social) ![Github forks](https://shields.io/github/forks/judek/sspiauthenticate?style=social) ![Github watchers](https://shields.io/github/watchers/judek/sspiauthenticate?style=social)
- github.com/BobCatC/xSspi ![Github stars](https://shields.io/github/stars/BobCatC/xSspi?style=social) ![Github forks](https://shields.io/github/forks/BobCatC/xSspi?style=social) ![Github watchers](https://shields.io/github/watchers/BobCatC/xSspi?style=social)
- github.com/sishtiaq/SampleSSPICode ![Github stars](https://shields.io/github/stars/sishtiaq/SampleSSPICode?style=social) ![Github forks](https://shields.io/github/forks/sishtiaq/SampleSSPICode?style=social) ![Github watchers](https://shields.io/github/watchers/sishtiaq/SampleSSPICode?style=social)
- github.com/liamkirton/sslpyfilter ![Github stars](https://shields.io/github/stars/liamkirton/sslpyfilter?style=social) ![Github forks](https://shields.io/github/forks/liamkirton/sslpyfilter?style=social) ![Github watchers](https://shields.io/github/watchers/liamkirton/sslpyfilter?style=social)
- github.com/bschlenk/gsspp ![Github stars](https://shields.io/github/stars/bschlenk/gsspp?style=social) ![Github forks](https://shields.io/github/forks/bschlenk/gsspp?style=social) ![Github watchers](https://shields.io/github/watchers/bschlenk/gsspp?style=social)

## openssl

- github.com/square/certstrap (go) ![Github stars](https://shields.io/github/stars/square/certstrap?style=social) ![Github forks](https://shields.io/github/forks/square/certstrap?style=social) ![Github watchers](https://shields.io/github/watchers/square/certstrap?style=social)
- github.com/hioa-cs/IncludeOS/blob/fd92a5394b493b5b645b2123966d38c1576df250/src/net/https/openssl_server.cpp#L72 ![Github stars](https://shields.io/github/stars/hioa-cs/IncludeOS?style=social) ![Github forks](https://shields.io/github/forks/hioa-cs/IncludeOS?style=social) ![Github watchers](https://shields.io/github/watchers/hioa-cs/IncludeOS?style=social)
- github.com/robertblackwell/marvincpp ![Github stars](https://shields.io/github/stars/robertblackwell/marvincpp?style=social) ![Github forks](https://shields.io/github/forks/robertblackwell/marvincpp?style=social) ![Github watchers](https://shields.io/github/watchers/robertblackwell/marvincpp?style=social)
- github.com/equalitie/ouinet ![Github stars](https://shields.io/github/stars/equalitie/ouinet?style=social) ![Github forks](https://shields.io/github/forks/equalitie/ouinet?style=social) ![Github watchers](https://shields.io/github/watchers/equalitie/ouinet?style=social)
- github.com/LiTianjue/mite-note ![Github stars](https://shields.io/github/stars/LiTianjue/mite-note?style=social) ![Github forks](https://shields.io/github/forks/LiTianjue/mite-note?style=social) ![Github watchers](https://shields.io/github/watchers/LiTianjue/mite-note?style=social)
- blog.csdn.net/dotalee/article/details/78041691
- www.cnblogs.com/kennyhr/p/3746048.html

## pdb

- github.com/wbenny/pdbex ![Github stars](https://shields.io/github/stars/wbenny/pdbex?style=social) ![Github forks](https://shields.io/github/forks/wbenny/pdbex?style=social) ![Github watchers](https://shields.io/github/watchers/wbenny/pdbex?style=social)

## gpu

- github.com/Volkanite/Push ![Github stars](https://shields.io/github/stars/Volkanite/Push?style=social) ![Github forks](https://shields.io/github/forks/Volkanite/Push?style=social) ![Github watchers](https://shields.io/github/watchers/Volkanite/Push?style=social)

## crypto api

- github.com/tplgy/cppcodec (c++11 base64) ![Github stars](https://shields.io/github/stars/tplgy/cppcodec?style=social) ![Github forks](https://shields.io/github/forks/tplgy/cppcodec?style=social) ![Github watchers](https://shields.io/github/watchers/tplgy/cppcodec?style=social)
- github.com/maldevel/AES256 ![Github stars](https://shields.io/github/stars/maldevel/AES256?style=social) ![Github forks](https://shields.io/github/forks/maldevel/AES256?style=social) ![Github watchers](https://shields.io/github/watchers/maldevel/AES256?style=social)
- github.com/wbenny/mini-tor ![Github stars](https://shields.io/github/stars/wbenny/mini-tor?style=social) ![Github forks](https://shields.io/github/forks/wbenny/mini-tor?style=social) ![Github watchers](https://shields.io/github/watchers/wbenny/mini-tor?style=social)
- github.com/wyrover/CryptoAPI-examples ![Github stars](https://shields.io/github/stars/wyrover/CryptoAPI-examples?style=social) ![Github forks](https://shields.io/github/forks/wyrover/CryptoAPI-examples?style=social) ![Github watchers](https://shields.io/github/watchers/wyrover/CryptoAPI-examples?style=social)
- github.com/fmuecke/CryptoApi ![Github stars](https://shields.io/github/stars/fmuecke/CryptoApi?style=social) ![Github forks](https://shields.io/github/forks/fmuecke/CryptoApi?style=social) ![Github watchers](https://shields.io/github/watchers/fmuecke/CryptoApi?style=social)
- github.com/ViartX/CacheCrypto ![Github stars](https://shields.io/github/stars/ViartX/CacheCrypto?style=social) ![Github forks](https://shields.io/github/forks/ViartX/CacheCrypto?style=social) ![Github watchers](https://shields.io/github/watchers/ViartX/CacheCrypto?style=social)
- github.com/Deerenaros/CryptoAPIWrapper ![Github stars](https://shields.io/github/stars/Deerenaros/CryptoAPIWrapper?style=social) ![Github forks](https://shields.io/github/forks/Deerenaros/CryptoAPIWrapper?style=social) ![Github watchers](https://shields.io/github/watchers/Deerenaros/CryptoAPIWrapper?style=social)
- github.com/maldevel/SHA256 ![Github stars](https://shields.io/github/stars/maldevel/SHA256?style=social) ![Github forks](https://shields.io/github/forks/maldevel/SHA256?style=social) ![Github watchers](https://shields.io/github/watchers/maldevel/SHA256?style=social)
- github.com/13g10n/crypto ![Github stars](https://shields.io/github/stars/13g10n/crypto?style=social) ![Github forks](https://shields.io/github/forks/13g10n/crypto?style=social) ![Github watchers](https://shields.io/github/watchers/13g10n/crypto?style=social)

## ipc

- github.com/fangqing/PipeLink ![Github stars](https://shields.io/github/stars/fangqing/PipeLink?style=social) ![Github forks](https://shields.io/github/forks/fangqing/PipeLink?style=social) ![Github watchers](https://shields.io/github/watchers/fangqing/PipeLink?style=social)
- github.com/e3ntity/windows_named_pipe_ipc ![Github stars](https://shields.io/github/stars/e3ntity/windows_named_pipe_ipc?style=social) ![Github forks](https://shields.io/github/forks/e3ntity/windows_named_pipe_ipc?style=social) ![Github watchers](https://shields.io/github/watchers/e3ntity/windows_named_pipe_ipc?style=social)

## iot sec

- iot.sec-wiki.com/

## ascii banner

- www.network-science.de/ascii/
- www.degraeve.com/img2txt.php

## book code

- github.com/yifengyou/32to64 ![Github stars](https://shields.io/github/stars/yifengyou/32to64?style=social) ![Github forks](https://shields.io/github/forks/yifengyou/32to64?style=social) ![Github watchers](https://shields.io/github/watchers/yifengyou/32to64?style=social)
- github.com/elephantos/elephant ![Github stars](https://shields.io/github/stars/elephantos/elephant?style=social) ![Github forks](https://shields.io/github/forks/elephantos/elephant?style=social) ![Github watchers](https://shields.io/github/watchers/elephantos/elephant?style=social)
- github.com/yifengyou/Android-software-security-and-reverse-analysis ![Github stars](https://shields.io/github/stars/yifengyou/Android-software-security-and-reverse-analysis?style=social) ![Github forks](https://shields.io/github/forks/yifengyou/Android-software-security-and-reverse-analysis?style=social) ![Github watchers](https://shields.io/github/watchers/yifengyou/Android-software-security-and-reverse-analysis?style=social)
- github.com/yifengyou/Code-virtualization-and-automation-analysis ![Github stars](https://shields.io/github/stars/yifengyou/Code-virtualization-and-automation-analysis?style=social) ![Github forks](https://shields.io/github/forks/yifengyou/Code-virtualization-and-automation-analysis?style=social) ![Github watchers](https://shields.io/github/watchers/yifengyou/Code-virtualization-and-automation-analysis?style=social)
- github.com/yifengyou/Software-protection-and-analysis-techniques---principles-and-practices ![Github stars](https://shields.io/github/stars/yifengyou/Software-protection-and-analysis-techniques---principles-and-practices?style=social) ![Github forks](https://shields.io/github/forks/yifengyou/Software-protection-and-analysis-techniques---principles-and-practices?style=social) ![Github watchers](https://shields.io/github/watchers/yifengyou/Software-protection-and-analysis-techniques---principles-and-practices?style=social)
- github.com/yifengyou/X86-assembly-language-from-real-mode-to-protection-mode ![Github stars](https://shields.io/github/stars/yifengyou/X86-assembly-language-from-real-mode-to-protection-mode?style=social) ![Github forks](https://shields.io/github/forks/yifengyou/X86-assembly-language-from-real-mode-to-protection-mode?style=social) ![Github watchers](https://shields.io/github/watchers/yifengyou/X86-assembly-language-from-real-mode-to-protection-mode?style=social)

## regex

- github.com/zeeshanu/learn-regex ![Github stars](https://shields.io/github/stars/zeeshanu/learn-regex?style=social) ![Github forks](https://shields.io/github/forks/zeeshanu/learn-regex?style=social) ![Github watchers](https://shields.io/github/watchers/zeeshanu/learn-regex?style=social)

## paper

- github.com/wcventure/PC-Malware-Sklearner ![Github stars](https://shields.io/github/stars/wcventure/PC-Malware-Sklearner?style=social) ![Github forks](https://shields.io/github/forks/wcventure/PC-Malware-Sklearner?style=social) ![Github watchers](https://shields.io/github/watchers/wcventure/PC-Malware-Sklearner?style=social)
- www.virusbulletin.com/uploads/pdf/conference_slides/2018/Svajcer-VB2018-KernelModeAnalysis.pdf (windbg usage)
- hitcon.org/2018/CMT/slide-files/d1_s5_r0.pdf?v=2 (game cheat)
- github.com/tyranid/WindowsRuntimeSecurityDemos ![Github stars](https://shields.io/github/stars/tyranid/WindowsRuntimeSecurityDemos?style=social) ![Github forks](https://shields.io/github/forks/tyranid/WindowsRuntimeSecurityDemos?style=social) ![Github watchers](https://shields.io/github/watchers/tyranid/WindowsRuntimeSecurityDemos?style=social)
- translation-zh-cn.readthedocs.io/zh_CN/
- speakerdeck.com

## ebook

- github.com/Bypass007/Emergency-Response-Notes ![Github stars](https://shields.io/github/stars/Bypass007/Emergency-Response-Notes?style=social) ![Github forks](https://shields.io/github/forks/Bypass007/Emergency-Response-Notes?style=social) ![Github watchers](https://shields.io/github/watchers/Bypass007/Emergency-Response-Notes?style=social)
- github.com/yifengyou/The-design-and-implementation-of-a-64-bit-operating-system ![Github stars](https://shields.io/github/stars/yifengyou/The-design-and-implementation-of-a-64-bit-operating-system?style=social) ![Github forks](https://shields.io/github/forks/yifengyou/The-design-and-implementation-of-a-64-bit-operating-system?style=social) ![Github watchers](https://shields.io/github/watchers/yifengyou/The-design-and-implementation-of-a-64-bit-operating-system?style=social)
- github.com/firmianay/CTF-All-In-One ![Github stars](https://shields.io/github/stars/firmianay/CTF-All-In-One?style=social) ![Github forks](https://shields.io/github/forks/firmianay/CTF-All-In-One?style=social) ![Github watchers](https://shields.io/github/watchers/firmianay/CTF-All-In-One?style=social)
- github.com/cfenollosa/os-tutorial ![Github stars](https://shields.io/github/stars/cfenollosa/os-tutorial?style=social) ![Github forks](https://shields.io/github/forks/cfenollosa/os-tutorial?style=social) ![Github watchers](https://shields.io/github/watchers/cfenollosa/os-tutorial?style=social)
- github.com/Snowming04/The-Hacker-Playbook-3-Translation ![Github stars](https://shields.io/github/stars/Snowming04/The-Hacker-Playbook-3-Translation?style=social) ![Github forks](https://shields.io/github/forks/Snowming04/The-Hacker-Playbook-3-Translation?style=social) ![Github watchers](https://shields.io/github/watchers/Snowming04/The-Hacker-Playbook-3-Translation?style=social)
- github.com/xuanhun/PythonHackingBook1 ![Github stars](https://shields.io/github/stars/xuanhun/PythonHackingBook1?style=social) ![Github forks](https://shields.io/github/forks/xuanhun/PythonHackingBook1?style=social) ![Github watchers](https://shields.io/github/watchers/xuanhun/PythonHackingBook1?style=social)
- github.com/xapax/security ![Github stars](https://shields.io/github/stars/xapax/security?style=social) ![Github forks](https://shields.io/github/forks/xapax/security?style=social) ![Github watchers](https://shields.io/github/watchers/xapax/security?style=social)
- github.com/chryzsh/DarthSidious (AD Domain hack) ![Github stars](https://shields.io/github/stars/chryzsh/DarthSidious?style=social) ![Github forks](https://shields.io/github/forks/chryzsh/DarthSidious?style=social) ![Github watchers](https://shields.io/github/watchers/chryzsh/DarthSidious?style=social)
- github.com/chryzsh/practical-hacking ![Github stars](https://shields.io/github/stars/chryzsh/practical-hacking?style=social) ![Github forks](https://shields.io/github/forks/chryzsh/practical-hacking?style=social) ![Github watchers](https://shields.io/github/watchers/chryzsh/practical-hacking?style=social)
- www.foxebook.net/

## ctf

- github.com/boogy/ctfbox ![Github stars](https://shields.io/github/stars/boogy/ctfbox?style=social) ![Github forks](https://shields.io/github/forks/boogy/ctfbox?style=social) ![Github watchers](https://shields.io/github/watchers/boogy/ctfbox?style=social)
- github.com/Ignitetechnologies/Privilege-Escalation ![Github stars](https://shields.io/github/stars/Ignitetechnologies/Privilege-Escalation?style=social) ![Github forks](https://shields.io/github/forks/Ignitetechnologies/Privilege-Escalation?style=social) ![Github watchers](https://shields.io/github/watchers/Ignitetechnologies/Privilege-Escalation?style=social)
- github.com/ktecv2000/How-to-play-CTF ![Github stars](https://shields.io/github/stars/ktecv2000/How-to-play-CTF?style=social) ![Github forks](https://shields.io/github/forks/ktecv2000/How-to-play-CTF?style=social) ![Github watchers](https://shields.io/github/watchers/ktecv2000/How-to-play-CTF?style=social)

## pentest

- zhuanlan.zhihu.com/p/147374260
- github.com/2hu2huxia/how-to-hack-like-a-god ![Github stars](https://shields.io/github/stars/2hu2huxia/how-to-hack-like-a-god?style=social) ![Github forks](https://shields.io/github/forks/2hu2huxia/how-to-hack-like-a-god?style=social) ![Github watchers](https://shields.io/github/watchers/2hu2huxia/how-to-hack-like-a-god?style=social)
- github.com/ngadminq/Bei-Gai-penetration-test-guide ![Github stars](https://shields.io/github/stars/ngadminq/Bei-Gai-penetration-test-guide?style=social) ![Github forks](https://shields.io/github/forks/ngadminq/Bei-Gai-penetration-test-guide?style=social) ![Github watchers](https://shields.io/github/watchers/ngadminq/Bei-Gai-penetration-test-guide?style=social)
- github.com/ReAbout/web-sec ![Github stars](https://shields.io/github/stars/ReAbout/web-sec?style=social) ![Github forks](https://shields.io/github/forks/ReAbout/web-sec?style=social) ![Github watchers](https://shields.io/github/watchers/ReAbout/web-sec?style=social)
- github.com/Paper-Pen/GatherInfo ![Github stars](https://shields.io/github/stars/Paper-Pen/GatherInfo?style=social) ![Github forks](https://shields.io/github/forks/Paper-Pen/GatherInfo?style=social) ![Github watchers](https://shields.io/github/watchers/Paper-Pen/GatherInfo?style=social)
- github.com/Power7089/PenetrationTest-Tips ![Github stars](https://shields.io/github/stars/Power7089/PenetrationTest-Tips?style=social) ![Github forks](https://shields.io/github/forks/Power7089/PenetrationTest-Tips?style=social) ![Github watchers](https://shields.io/github/watchers/Power7089/PenetrationTest-Tips?style=social)
- github.com/theLSA/CS-checklist ![Github stars](https://shields.io/github/stars/theLSA/CS-checklist?style=social) ![Github forks](https://shields.io/github/forks/theLSA/CS-checklist?style=social) ![Github watchers](https://shields.io/github/watchers/theLSA/CS-checklist?style=social)
- github.com/kelvinBen/AppInfoScanner ![Github stars](https://shields.io/github/stars/kelvinBen/AppInfoScanner?style=social) ![Github forks](https://shields.io/github/forks/kelvinBen/AppInfoScanner?style=social) ![Github watchers](https://shields.io/github/watchers/kelvinBen/AppInfoScanner?style=social)
- github.com/Leezj9671/Pentest_Interview ![Github stars](https://shields.io/github/stars/Leezj9671/Pentest_Interview?style=social) ![Github forks](https://shields.io/github/forks/Leezj9671/Pentest_Interview?style=social) ![Github watchers](https://shields.io/github/watchers/Leezj9671/Pentest_Interview?style=social)
- github.com/iSafeBlue/TrackRay ![Github stars](https://shields.io/github/stars/iSafeBlue/TrackRay?style=social) ![Github forks](https://shields.io/github/forks/iSafeBlue/TrackRay?style=social) ![Github watchers](https://shields.io/github/watchers/iSafeBlue/TrackRay?style=social)
- github.com/TophantTechnology/ARL ![Github stars](https://shields.io/github/stars/TophantTechnology/ARL?style=social) ![Github forks](https://shields.io/github/forks/TophantTechnology/ARL?style=social) ![Github watchers](https://shields.io/github/watchers/TophantTechnology/ARL?style=social)
- github.com/Mr-xn/Penetration_Testing_POC ![Github stars](https://shields.io/github/stars/Mr-xn/Penetration_Testing_POC?style=social) ![Github forks](https://shields.io/github/forks/Mr-xn/Penetration_Testing_POC?style=social) ![Github watchers](https://shields.io/github/watchers/Mr-xn/Penetration_Testing_POC?style=social)
- github.com/hudunkey/Red-Team-links ![Github stars](https://shields.io/github/stars/hudunkey/Red-Team-links?style=social) ![Github forks](https://shields.io/github/forks/hudunkey/Red-Team-links?style=social) ![Github watchers](https://shields.io/github/watchers/hudunkey/Red-Team-links?style=social)
- github.com/xiaoy-sec/Pentest_Note ![Github stars](https://shields.io/github/stars/xiaoy-sec/Pentest_Note?style=social) ![Github forks](https://shields.io/github/forks/xiaoy-sec/Pentest_Note?style=social) ![Github watchers](https://shields.io/github/watchers/xiaoy-sec/Pentest_Note?style=social)
- github.com/taielab/Taie-Bugbounty-killer ![Github stars](https://shields.io/github/stars/taielab/Taie-Bugbounty-killer?style=social) ![Github forks](https://shields.io/github/forks/taielab/Taie-Bugbounty-killer?style=social) ![Github watchers](https://shields.io/github/watchers/taielab/Taie-Bugbounty-killer?style=social)
- github.com/Dm2333/ATTCK-PenTester-Book ![Github stars](https://shields.io/github/stars/Dm2333/ATTCK-PenTester-Book?style=social) ![Github forks](https://shields.io/github/forks/Dm2333/ATTCK-PenTester-Book?style=social) ![Github watchers](https://shields.io/github/watchers/Dm2333/ATTCK-PenTester-Book?style=social)
- github.com/hongriSec/Web-Security-Attack ![Github stars](https://shields.io/github/stars/hongriSec/Web-Security-Attack?style=social) ![Github forks](https://shields.io/github/forks/hongriSec/Web-Security-Attack?style=social) ![Github watchers](https://shields.io/github/watchers/hongriSec/Web-Security-Attack?style=social)
- github.com/jiansiting/Kali-Windows ![Github stars](https://shields.io/github/stars/jiansiting/Kali-Windows?style=social) ![Github forks](https://shields.io/github/forks/jiansiting/Kali-Windows?style=social) ![Github watchers](https://shields.io/github/watchers/jiansiting/Kali-Windows?style=social)
- github.com/uknowsec/Active-Directory-Pentest-Notes ![Github stars](https://shields.io/github/stars/uknowsec/Active-Directory-Pentest-Notes?style=social) ![Github forks](https://shields.io/github/forks/uknowsec/Active-Directory-Pentest-Notes?style=social) ![Github watchers](https://shields.io/github/watchers/uknowsec/Active-Directory-Pentest-Notes?style=social)
- micro8.gitbook.io/micro8/
- github.com/aleenzz/Cobalt_Strike_wiki ![Github stars](https://shields.io/github/stars/aleenzz/Cobalt_Strike_wiki?style=social) ![Github forks](https://shields.io/github/forks/aleenzz/Cobalt_Strike_wiki?style=social) ![Github watchers](https://shields.io/github/watchers/aleenzz/Cobalt_Strike_wiki?style=social)
- github.com/l3m0n/pentest_study ![Github stars](https://shields.io/github/stars/l3m0n/pentest_study?style=social) ![Github forks](https://shields.io/github/forks/l3m0n/pentest_study?style=social) ![Github watchers](https://shields.io/github/watchers/l3m0n/pentest_study?style=social)
- github.com/l3m0n/pentest_tools ![Github stars](https://shields.io/github/stars/l3m0n/pentest_tools?style=social) ![Github forks](https://shields.io/github/forks/l3m0n/pentest_tools?style=social) ![Github watchers](https://shields.io/github/watchers/l3m0n/pentest_tools?style=social)
- github.com/l3m0n/linux_information ![Github stars](https://shields.io/github/stars/l3m0n/linux_information?style=social) ![Github forks](https://shields.io/github/forks/l3m0n/linux_information?style=social) ![Github watchers](https://shields.io/github/watchers/l3m0n/linux_information?style=social)

## wpad/pac

- github.com/marx-yu/ProxyParser ![Github stars](https://shields.io/github/stars/marx-yu/ProxyParser?style=social) ![Github forks](https://shields.io/github/forks/marx-yu/ProxyParser?style=social) ![Github watchers](https://shields.io/github/watchers/marx-yu/ProxyParser?style=social)
- www.devnotes.in/2014/11/08/auto-proxy-settings-with-PAC.html
- www.lybbn.cn/data/datas.php?yw=76
- blog.huzhifeng.com/2017/07/16/PAC/
- github.com/manugarg/pacparser ![Github stars](https://shields.io/github/stars/manugarg/pacparser?style=social) ![Github forks](https://shields.io/github/forks/manugarg/pacparser?style=social) ![Github watchers](https://shields.io/github/watchers/manugarg/pacparser?style=social)

## javascript

- github.com/qianguyihao/Web ![Github stars](https://shields.io/github/stars/qianguyihao/Web?style=social) ![Github forks](https://shields.io/github/forks/qianguyihao/Web?style=social) ![Github watchers](https://shields.io/github/watchers/qianguyihao/Web?style=social)
- github.com/Daotin/front-end-self-study-notes ![Github stars](https://shields.io/github/stars/Daotin/front-end-self-study-notes?style=social) ![Github forks](https://shields.io/github/forks/Daotin/front-end-self-study-notes?style=social) ![Github watchers](https://shields.io/github/watchers/Daotin/front-end-self-study-notes?style=social)

## typescript

-- www.dengwb.com/typescript/

## js obfuscator/deobfuscator

- beautifier.io/
- tool.lu/js/
- www.52pojie.cn/thread-128803-1-1.html
- www.kahusecurity.com/2011/javascript-deobfuscation-tools-part-1/
- www.kahusecurity.com/2011/javascript-deobfucation-tools-part-2/
- deobfuscatejavascript.com/
- js.pnote.net/#/js

## js reverse engine

- blog.csdn.net/weixin_43189702/article/details/103171967
- github.com/xianyucoder/Crack-JS ![Github stars](https://shields.io/github/stars/xianyucoder/Crack-JS?style=social) ![Github forks](https://shields.io/github/forks/xianyucoder/Crack-JS?style=social) ![Github watchers](https://shields.io/github/watchers/xianyucoder/Crack-JS?style=social)
- github.com/freedom-wy/js-reverse ![Github stars](https://shields.io/github/stars/freedom-wy/js-reverse?style=social) ![Github forks](https://shields.io/github/forks/freedom-wy/js-reverse?style=social) ![Github watchers](https://shields.io/github/watchers/freedom-wy/js-reverse?style=social)
- github.com/maxnoodles/js_decrypt ![Github stars](https://shields.io/github/stars/maxnoodles/js_decrypt?style=social) ![Github forks](https://shields.io/github/forks/maxnoodles/js_decrypt?style=social) ![Github watchers](https://shields.io/github/watchers/maxnoodles/js_decrypt?style=social)
- github.com/DingZaiHub/PythonSpider ![Github stars](https://shields.io/github/stars/DingZaiHub/PythonSpider?style=social) ![Github forks](https://shields.io/github/forks/DingZaiHub/PythonSpider?style=social) ![Github watchers](https://shields.io/github/watchers/DingZaiHub/PythonSpider?style=social)

## decompiler

- github.com/herumi/xbyak ![Github stars](https://shields.io/github/stars/herumi/xbyak?style=social) ![Github forks](https://shields.io/github/forks/herumi/xbyak?style=social) ![Github watchers](https://shields.io/github/watchers/herumi/xbyak?style=social)
- github.com/wargio/r2dec-js (asm to c) ![Github stars](https://shields.io/github/stars/wargio/r2dec-js?style=social) ![Github forks](https://shields.io/github/forks/wargio/r2dec-js?style=social) ![Github watchers](https://shields.io/github/watchers/wargio/r2dec-js?style=social)

## encryption/decryption tools

- www.devglan.com

## english

- github.com/yujiangshui/An-English-Guide-for-Programmers ![Github stars](https://shields.io/github/stars/yujiangshui/An-English-Guide-for-Programmers?style=social) ![Github forks](https://shields.io/github/forks/yujiangshui/An-English-Guide-for-Programmers?style=social) ![Github watchers](https://shields.io/github/watchers/yujiangshui/An-English-Guide-for-Programmers?style=social)

## downloader

- github.com/alanzhangzm/Photon ![Github stars](https://shields.io/github/stars/alanzhangzm/Photon?style=social) ![Github forks](https://shields.io/github/forks/alanzhangzm/Photon?style=social) ![Github watchers](https://shields.io/github/watchers/alanzhangzm/Photon?style=social)

## python

- github.com/wistbean/learn_python3_spider ![Github stars](https://shields.io/github/stars/wistbean/learn_python3_spider?style=social) ![Github forks](https://shields.io/github/forks/wistbean/learn_python3_spider?style=social) ![Github watchers](https://shields.io/github/watchers/wistbean/learn_python3_spider?style=social)
- github.com/Kr1s77/awesome-python-login-model ![Github stars](https://shields.io/github/stars/Kr1s77/awesome-python-login-model?style=social) ![Github forks](https://shields.io/github/forks/Kr1s77/awesome-python-login-model?style=social) ![Github watchers](https://shields.io/github/watchers/Kr1s77/awesome-python-login-model?style=social)
- github.com/Kr1s77/Python-crawler-tutorial-starts-from-zero ![Github stars](https://shields.io/github/stars/Kr1s77/Python-crawler-tutorial-starts-from-zero?style=social) ![Github forks](https://shields.io/github/forks/Kr1s77/Python-crawler-tutorial-starts-from-zero?style=social) ![Github watchers](https://shields.io/github/watchers/Kr1s77/Python-crawler-tutorial-starts-from-zero?style=social)
- github.com/jackfrued/Python-100-Days ![Github stars](https://shields.io/github/stars/jackfrued/Python-100-Days?style=social) ![Github forks](https://shields.io/github/forks/jackfrued/Python-100-Days?style=social) ![Github watchers](https://shields.io/github/watchers/jackfrued/Python-100-Days?style=social)

## golang

- github.com/yifengyou/Golang-100-Days ![Github stars](https://shields.io/github/stars/yifengyou/Golang-100-Days?style=social) ![Github forks](https://shields.io/github/forks/yifengyou/Golang-100-Days?style=social) ![Github watchers](https://shields.io/github/watchers/yifengyou/Golang-100-Days?style=social)

## puppeteer

- github.com/GoogleChrome/puppeteer/blob/v1.20.0/docs/api.md ![Github stars](https://shields.io/github/stars/GoogleChrome/puppeteer?style=social) ![Github forks](https://shields.io/github/forks/GoogleChrome/puppeteer?style=social) ![Github watchers](https://shields.io/github/watchers/GoogleChrome/puppeteer?style=social)
- zhaoqize.github.io/puppeteer-api-zh_CN
- github.com/csbun/thal ![Github stars](https://shields.io/github/stars/csbun/thal?style=social) ![Github forks](https://shields.io/github/forks/csbun/thal?style=social) ![Github watchers](https://shields.io/github/watchers/csbun/thal?style=social)
- www.yuque.com/imhelloworld/share-day/no8xoc
- blog.csdn.net/qupan1993/article/details/85371556
- www.php.cn/js-tutorial-399252.html

## java

- www.52im.net/thread-28-1-1.html (beautyeye GUI)
- github.com/JackJiang2011/beautyeye (beautyeye GUI) ![Github stars](https://shields.io/github/stars/JackJiang2011/beautyeye?style=social) ![Github forks](https://shields.io/github/forks/JackJiang2011/beautyeye?style=social) ![Github watchers](https://shields.io/github/watchers/JackJiang2011/beautyeye?style=social)
- blog.csdn.net/pinlantu/article/details/83957672

## android

- qmuiteam.com/android
- github.com/FadedYu/Framework_Android ![Github stars](https://shields.io/github/stars/FadedYu/Framework_Android?style=social) ![Github forks](https://shields.io/github/forks/FadedYu/Framework_Android?style=social) ![Github watchers](https://shields.io/github/watchers/FadedYu/Framework_Android?style=social)
- blog.csdn.net/aqi00/article/details/50012511
- github.com/xuexiangjys/XUI (UI) ![Github stars](https://shields.io/github/stars/xuexiangjys/XUI?style=social) ![Github forks](https://shields.io/github/forks/xuexiangjys/XUI?style=social) ![Github watchers](https://shields.io/github/watchers/xuexiangjys/XUI?style=social)
- github.com/joinAero/AndroidWebServ ![Github stars](https://shields.io/github/stars/joinAero/AndroidWebServ?style=social) ![Github forks](https://shields.io/github/forks/joinAero/AndroidWebServ?style=social) ![Github watchers](https://shields.io/github/watchers/joinAero/AndroidWebServ?style=social)
- github.com/lopspower/AndroidWebServer ![Github stars](https://shields.io/github/stars/lopspower/AndroidWebServer?style=social) ![Github forks](https://shields.io/github/forks/lopspower/AndroidWebServer?style=social) ![Github watchers](https://shields.io/github/watchers/lopspower/AndroidWebServer?style=social)
- clean-apps.github.io/CleanSCAN/
- github.com/devinhu/androidone ![Github stars](https://shields.io/github/stars/devinhu/androidone?style=social) ![Github forks](https://shields.io/github/forks/devinhu/androidone?style=social) ![Github watchers](https://shields.io/github/watchers/devinhu/androidone?style=social)
- github.com/shishuo365/PinyinIME ![Github stars](https://shields.io/github/stars/shishuo365/PinyinIME?style=social) ![Github forks](https://shields.io/github/forks/shishuo365/PinyinIME?style=social) ![Github watchers](https://shields.io/github/watchers/shishuo365/PinyinIME?style=social)
- github.com/angcyo/RJcenter (Common lib) ![Github stars](https://shields.io/github/stars/angcyo/RJcenter?style=social) ![Github forks](https://shields.io/github/forks/angcyo/RJcenter?style=social) ![Github watchers](https://shields.io/github/watchers/angcyo/RJcenter?style=social)
- github.com/ChenLittlePing/LearningVideo (FFmpeg) ![Github stars](https://shields.io/github/stars/ChenLittlePing/LearningVideo?style=social) ![Github forks](https://shields.io/github/forks/ChenLittlePing/LearningVideo?style=social) ![Github watchers](https://shields.io/github/watchers/ChenLittlePing/LearningVideo?style=social)
- github.com/AriesHoo/FastLib ![Github stars](https://shields.io/github/stars/AriesHoo/FastLib?style=social) ![Github forks](https://shields.io/github/forks/AriesHoo/FastLib?style=social) ![Github watchers](https://shields.io/github/watchers/AriesHoo/FastLib?style=social)
- github.com/devinhu/androidone ![Github stars](https://shields.io/github/stars/devinhu/androidone?style=social) ![Github forks](https://shields.io/github/forks/devinhu/androidone?style=social) ![Github watchers](https://shields.io/github/watchers/devinhu/androidone?style=social)
- github.com/afkT/DevUtils ![Github stars](https://shields.io/github/stars/afkT/DevUtils?style=social) ![Github forks](https://shields.io/github/forks/afkT/DevUtils?style=social) ![Github watchers](https://shields.io/github/watchers/afkT/DevUtils?style=social)
- github.com/smuyyh/CommonLibary ![Github stars](https://shields.io/github/stars/smuyyh/CommonLibary?style=social) ![Github forks](https://shields.io/github/forks/smuyyh/CommonLibary?style=social) ![Github watchers](https://shields.io/github/watchers/smuyyh/CommonLibary?style=social)
- github.com/frodoking/App-Architecture ![Github stars](https://shields.io/github/stars/frodoking/App-Architecture?style=social) ![Github forks](https://shields.io/github/forks/frodoking/App-Architecture?style=social) ![Github watchers](https://shields.io/github/watchers/frodoking/App-Architecture?style=social)
- github.com/ddnosh/AndroidQuick ![Github stars](https://shields.io/github/stars/ddnosh/AndroidQuick?style=social) ![Github forks](https://shields.io/github/forks/ddnosh/AndroidQuick?style=social) ![Github watchers](https://shields.io/github/watchers/ddnosh/AndroidQuick?style=social)
- github.com/fly803/BaseProject ![Github stars](https://shields.io/github/stars/fly803/BaseProject?style=social) ![Github forks](https://shields.io/github/forks/fly803/BaseProject?style=social) ![Github watchers](https://shields.io/github/watchers/fly803/BaseProject?style=social)
- blog.csdn.net/fukaimei/category_7160796.html
- github.com/chenyufeng1991/BaiduMap-TrafficAssistant ![Github stars](https://shields.io/github/stars/chenyufeng1991/BaiduMap-TrafficAssistant?style=social) ![Github forks](https://shields.io/github/forks/chenyufeng1991/BaiduMap-TrafficAssistant?style=social) ![Github watchers](https://shields.io/github/watchers/chenyufeng1991/BaiduMap-TrafficAssistant?style=social)
- github.com/naivor/naivorapp ![Github stars](https://shields.io/github/stars/naivor/naivorapp?style=social) ![Github forks](https://shields.io/github/forks/naivor/naivorapp?style=social) ![Github watchers](https://shields.io/github/watchers/naivor/naivorapp?style=social)
- github.com/u014427391/elemeimitate (ele) ![Github stars](https://shields.io/github/stars/u014427391/elemeimitate?style=social) ![Github forks](https://shields.io/github/forks/u014427391/elemeimitate?style=social) ![Github watchers](https://shields.io/github/watchers/u014427391/elemeimitate?style=social)
- github.com/leavesC/AndroidAllGuide ![Github stars](https://shields.io/github/stars/leavesC/AndroidAllGuide?style=social) ![Github forks](https://shields.io/github/forks/leavesC/AndroidAllGuide?style=social) ![Github watchers](https://shields.io/github/watchers/leavesC/AndroidAllGuide?style=social)
- github.com/lzan13/VMChat ![Github stars](https://shields.io/github/stars/lzan13/VMChat?style=social) ![Github forks](https://shields.io/github/forks/lzan13/VMChat?style=social) ![Github watchers](https://shields.io/github/watchers/lzan13/VMChat?style=social)
- github.com/open-android/hellocharts-android ![Github stars](https://shields.io/github/stars/open-android/hellocharts-android?style=social) ![Github forks](https://shields.io/github/forks/open-android/hellocharts-android?style=social) ![Github watchers](https://shields.io/github/watchers/open-android/hellocharts-android?style=social)
- github.com/sps135/wechatbysimple ![Github stars](https://shields.io/github/stars/sps135/wechatbysimple?style=social) ![Github forks](https://shields.io/github/forks/sps135/wechatbysimple?style=social) ![Github watchers](https://shields.io/github/watchers/sps135/wechatbysimple?style=social)
- github.com/smart005/okandroid ![Github stars](https://shields.io/github/stars/smart005/okandroid?style=social) ![Github forks](https://shields.io/github/forks/smart005/okandroid?style=social) ![Github watchers](https://shields.io/github/watchers/smart005/okandroid?style=social)
- github.com/decadezuo/DZAgile ![Github stars](https://shields.io/github/stars/decadezuo/DZAgile?style=social) ![Github forks](https://shields.io/github/forks/decadezuo/DZAgile?style=social) ![Github watchers](https://shields.io/github/watchers/decadezuo/DZAgile?style=social)
- github.com/jiankian/AnnZone ![Github stars](https://shields.io/github/stars/jiankian/AnnZone?style=social) ![Github forks](https://shields.io/github/forks/jiankian/AnnZone?style=social) ![Github watchers](https://shields.io/github/watchers/jiankian/AnnZone?style=social)
- github.com/xiaojigou/XJGARSDKDemoApp-Android ![Github stars](https://shields.io/github/stars/xiaojigou/XJGARSDKDemoApp-Android?style=social) ![Github forks](https://shields.io/github/forks/xiaojigou/XJGARSDKDemoApp-Android?style=social) ![Github watchers](https://shields.io/github/watchers/xiaojigou/XJGARSDKDemoApp-Android?style=social)
- github.com/mCyp/Orient-Ui ![Github stars](https://shields.io/github/stars/mCyp/Orient-Ui?style=social) ![Github forks](https://shields.io/github/forks/mCyp/Orient-Ui?style=social) ![Github watchers](https://shields.io/github/watchers/mCyp/Orient-Ui?style=social)
- github.com/xuexiangjys/XUpdate (Update) ![Github stars](https://shields.io/github/stars/xuexiangjys/XUpdate?style=social) ![Github forks](https://shields.io/github/forks/xuexiangjys/XUpdate?style=social) ![Github watchers](https://shields.io/github/watchers/xuexiangjys/XUpdate?style=social)
- github.com/onestravel/playSound (fmod) ![Github stars](https://shields.io/github/stars/onestravel/playSound?style=social) ![Github forks](https://shields.io/github/forks/onestravel/playSound?style=social) ![Github watchers](https://shields.io/github/watchers/onestravel/playSound?style=social)
- github.com/onestravel/QQVoiceChange (fmod) ![Github stars](https://shields.io/github/stars/onestravel/QQVoiceChange?style=social) ![Github forks](https://shields.io/github/forks/onestravel/QQVoiceChange?style=social) ![Github watchers](https://shields.io/github/watchers/onestravel/QQVoiceChange?style=social)
- github.com/virjar/zelda ![Github stars](https://shields.io/github/stars/virjar/zelda?style=social) ![Github forks](https://shields.io/github/forks/virjar/zelda?style=social) ![Github watchers](https://shields.io/github/watchers/virjar/zelda?style=social)

## android reverse engine

- github.com/Efaker/FakerAndroid ![Github stars](https://shields.io/github/stars/Efaker/FakerAndroid?style=social) ![Github forks](https://shields.io/github/forks/Efaker/FakerAndroid?style=social) ![Github watchers](https://shields.io/github/watchers/Efaker/FakerAndroid?style=social)
- github.com/zhangke3016/VirtualUETool ![Github stars](https://shields.io/github/stars/zhangke3016/VirtualUETool?style=social) ![Github forks](https://shields.io/github/forks/zhangke3016/VirtualUETool?style=social) ![Github watchers](https://shields.io/github/watchers/zhangke3016/VirtualUETool?style=social)
- github.com/r0ysue/AndroidSecurityStudy ![Github stars](https://shields.io/github/stars/r0ysue/AndroidSecurityStudy?style=social) ![Github forks](https://shields.io/github/forks/r0ysue/AndroidSecurityStudy?style=social) ![Github watchers](https://shields.io/github/watchers/r0ysue/AndroidSecurityStudy?style=social)
- github.com/JesusFreke/smali ![Github stars](https://shields.io/github/stars/JesusFreke/smali?style=social) ![Github forks](https://shields.io/github/forks/JesusFreke/smali?style=social) ![Github watchers](https://shields.io/github/watchers/JesusFreke/smali?style=social)
- bitbucket.org/JesusFreke/smali
- github.com/pxb1988/dex2jar ![Github stars](https://shields.io/github/stars/pxb1988/dex2jar?style=social) ![Github forks](https://shields.io/github/forks/pxb1988/dex2jar?style=social) ![Github watchers](https://shields.io/github/watchers/pxb1988/dex2jar?style=social)
- github.com/java-decompiler/jd-gui ![Github stars](https://shields.io/github/stars/java-decompiler/jd-gui?style=social) ![Github forks](https://shields.io/github/forks/java-decompiler/jd-gui?style=social) ![Github watchers](https://shields.io/github/watchers/java-decompiler/jd-gui?style=social)
- github.com/skylot/jadx ![Github stars](https://shields.io/github/stars/skylot/jadx?style=social) ![Github forks](https://shields.io/github/forks/skylot/jadx?style=social) ![Github watchers](https://shields.io/github/watchers/skylot/jadx?style=social)
- github.com/Konloch/bytecode-viewer ![Github stars](https://shields.io/github/stars/Konloch/bytecode-viewer?style=social) ![Github forks](https://shields.io/github/forks/Konloch/bytecode-viewer?style=social) ![Github watchers](https://shields.io/github/watchers/Konloch/bytecode-viewer?style=social)
- github.com/MobSF/Mobile-Security-Framework-MobSF ![Github stars](https://shields.io/github/stars/MobSF/Mobile-Security-Framework-MobSF?style=social) ![Github forks](https://shields.io/github/forks/MobSF/Mobile-Security-Framework-MobSF?style=social) ![Github watchers](https://shields.io/github/watchers/MobSF/Mobile-Security-Framework-MobSF?style=social)
- github.com/FeJQ/AUPK ![Github stars](https://shields.io/github/stars/FeJQ/AUPK?style=social) ![Github forks](https://shields.io/github/forks/FeJQ/AUPK?style=social) ![Github watchers](https://shields.io/github/watchers/FeJQ/AUPK?style=social)
- github.com/ItReadHub/20210124-192651-347 (unpack) ![Github stars](https://shields.io/github/stars/ItReadHub/20210124-192651-347?style=social) ![Github forks](https://shields.io/github/forks/ItReadHub/20210124-192651-347?style=social) ![Github watchers](https://shields.io/github/watchers/ItReadHub/20210124-192651-347?style=social)
- github.com/AlienwareHe/RDex (unpack) ![Github stars](https://shields.io/github/stars/AlienwareHe/RDex?style=social) ![Github forks](https://shields.io/github/forks/AlienwareHe/RDex?style=social) ![Github watchers](https://shields.io/github/watchers/AlienwareHe/RDex?style=social)
- github.com/OakChen/ApkShelling (unpack) ![Github stars](https://shields.io/github/stars/OakChen/ApkShelling?style=social) ![Github forks](https://shields.io/github/forks/OakChen/ApkShelling?style=social) ![Github watchers](https://shields.io/github/watchers/OakChen/ApkShelling?style=social)
- github.com/WrBug/DeveloperHelper (unpack) ![Github stars](https://shields.io/github/stars/WrBug/DeveloperHelper?style=social) ![Github forks](https://shields.io/github/forks/WrBug/DeveloperHelper?style=social) ![Github watchers](https://shields.io/github/watchers/WrBug/DeveloperHelper?style=social)
- github.com/CodingGay/BlackDex (unpack) ![Github stars](https://shields.io/github/stars/CodingGay/BlackDex?style=social) ![Github forks](https://shields.io/github/forks/CodingGay/BlackDex?style=social) ![Github watchers](https://shields.io/github/watchers/CodingGay/BlackDex?style=social)

## xposed

- github.com/fatal0/XVoiceChanger ![Github stars](https://shields.io/github/stars/fatal0/XVoiceChanger?style=social) ![Github forks](https://shields.io/github/forks/fatal0/XVoiceChanger?style=social) ![Github watchers](https://shields.io/github/watchers/fatal0/XVoiceChanger?style=social)
- github.com/dirname/AppDebuggable ![Github stars](https://shields.io/github/stars/dirname/AppDebuggable?style=social) ![Github forks](https://shields.io/github/forks/dirname/AppDebuggable?style=social) ![Github watchers](https://shields.io/github/watchers/dirname/AppDebuggable?style=social)

## Frida

- github.com/langgithub/RxAppEncryptionProtocol ![Github stars](https://shields.io/github/stars/langgithub/RxAppEncryptionProtocol?style=social) ![Github forks](https://shields.io/github/forks/langgithub/RxAppEncryptionProtocol?style=social) ![Github watchers](https://shields.io/github/watchers/langgithub/RxAppEncryptionProtocol?style=social)
- github.com/dstmath/frida-unpack ![Github stars](https://shields.io/github/stars/dstmath/frida-unpack?style=social) ![Github forks](https://shields.io/github/forks/dstmath/frida-unpack?style=social) ![Github watchers](https://shields.io/github/watchers/dstmath/frida-unpack?style=social)
- github.com/CreditTone/hooker ![Github stars](https://shields.io/github/stars/CreditTone/hooker?style=social) ![Github forks](https://shields.io/github/forks/CreditTone/hooker?style=social) ![Github watchers](https://shields.io/github/watchers/CreditTone/hooker?style=social)

## library

- github.com/myfreeer/cppreference2mshelp/ ![Github stars](https://shields.io/github/stars/myfreeer/cppreference2mshelp?style=social) ![Github forks](https://shields.io/github/forks/myfreeer/cppreference2mshelp?style=social) ![Github watchers](https://shields.io/github/watchers/myfreeer/cppreference2mshelp?style=social)
- www.ctolib.com/

## software collections

- www.softpedia.com/
