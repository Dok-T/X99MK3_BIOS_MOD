# DokT BIOS Mod for Asrock X99M KILLER 3.1

 - PLATOFORM NAME: X99M KILLER 3.1
- BRAND: ASROCK
- UEFI TYPE: AMI
- UEFI VERSION: APTIO V
- BIOS BASED VERSION: Beta 4.0.1 2019/1/2 https://download.asrock.com/BIOS/2011/X99M%20Killer3.1(4.01)ROM.zip
- OEM Release: 5.11

> The goal of this BIOS Mod is made to be futureproof and patch security issues and add features (at my level of skill).
> The roadmap is to release a stable, reliable, patched (security issues, such as Intel ME or CPU uCode) and adding PCIe Bifurcation menu. Some features esthetics features might be upgraded or changed to get a "fresh" look.

    0.1 03/15/23 [ALPHA]

 1. Unlocked Hidden Menus
 2. Updated Intel Microcode
 3. <code>╔════════════════════════════════════════════════════════════════════════╗
║                                 Intel                                  ║
╟─┬─────┬──────────────────┬────────┬──────────┬────┬──────┬────────┬────╢
║#│CPUID│     Platform     │Revision│   Date   │Type│ Size │ Offset │Last║
╟─┼─────┼──────────────────┼────────┼──────────┼────┼──────┼────────┼────╢
║1│406F1│EF (0,1,2,3,5,6,7)│B00002E │2018-04-19│PRD │0x7000│0xEEEF50│ No ║
╟─┼─────┼──────────────────┼────────┼──────────┼────┼──────┼────────┼────╢
║2│406F0│EF (0,1,2,3,5,6,7)│   10   │2015-05-01│PRD │0x6800│0xEF5F50│ No ║
╟─┼─────┼──────────────────┼────────┼──────────┼────┼──────┼────────┼────╢
║3│306F2│ 6F (0,1,2,3,5,6) │   3D   │2018-04-20│PRD │0x8400│0xEFC750│ No ║
╟─┼─────┼──────────────────┼────────┼──────────┼────┼──────┼────────┼────╢
║4│306F1│EF (0,1,2,3,5,6,7)│80000013│2013-10-02│PRE │0x8800│0xF04B50│ No ║
╚═╧═════╧══════════════════╧════════╧══════════╧════╧══════╧════════╧════╝
============================ Updated To =================================
╔═══════════════════════════════════════════════════════════════════════╗
║                                 Intel                                 ║
╟─┬─────┬──────────────────┬────────┬──────────┬────┬──────┬───────┬────╢
║#│CPUID│     Platform     │Revision│   Date   │Type│ Size │ Offset│Last║
╟─┼─────┼──────────────────┼────────┼──────────┼────┼──────┼───────┼────╢
║1│406F1│EF (0,1,2,3,5,6,7)│B00003E │2021-02-06│PRD │0x7C00│  0x18 │Yes ║
╟─┼─────┼──────────────────┼────────┼──────────┼────┼──────┼───────┼────╢
║2│406F0│EF (0,1,2,3,5,6,7)│   14   │2015-07-02│PRD │0x7C00│ 0x7C18│Yes ║
╟─┼─────┼──────────────────┼────────┼──────────┼────┼──────┼───────┼────╢
║3│306F2│ 6F (0,1,2,3,5,6) │   46   │2021-01-27│PRD │0x8800│ 0xF818│Yes ║
╟─┼─────┼──────────────────┼────────┼──────────┼────┼──────┼───────┼────╢
║4│306F1│EF (0,1,2,3,5,6,7)│   14   │2014-01-10│PRD │0x8800│0x18018│Yes ║
╚═╧═════╧══════════════════╧════════╧══════════╧════╧══════╧═══════╧════╝
</code>

4. Upgraded network firmware
	- Killer E2200 EFI Lx Killer Undi 1.1.0.4 -> 1.1.0.13
	- EFI Intel PRO1000 UNDI      - 6.1.14 -> 6.6.04
	- OROM Intel Boot Agent GE    - 1.5.50 -> 1.5.62

5. Changed some strings (useless strings, just for research)



