PrivWindoze (Private Windows) is a Microsoft Windows tool, which aims to quickly turn off all telemetry and remove known problematic software that either uses too many system resources, or has been difficult to remove for a considerable amount of users.

Below is a list of what is currently removed:

    Microsoft Bing
    Microsoft Copilot
    Microsoft Cortana
    Microsoft Recall
    Microsoft Zune
    Acer User Experience Improvement Program
    HP Touchpoint Analytics Client
    Intel Analytics / Telemetry
    Lenovo Vantage
    Slate Digital Connect SDACollector
    Tobii Help Center / Experience

PrivWindoze also does some other nuanced things, such as clearing caches and temporary internet files that tend to pile up over time. It does not delete cookies, but it will clear caches belonging to Discord, DirectX, and Fonts. It also clears some logs from the Event Viewer, and it removes orphaned Windows Registry entries belonging to the Windows Firewall. The revocation list address cache[[8](https://www.gradenegger.eu/en/view-and-clear-the-address-cache-for-blacklists-crl-url-cache/)] is also cleared.

Additional Information:

PrivWindoze is compatible with Windows 10 and 11 and is updated daily as of November 2024. The project originates from my [GitHub](https://github.com/thisisu) and is considered [freeware](https://en.wikipedia.org/wiki/Freeware). To report issues, visit this [page](https://github.com/thisisu/PrivWindoze/issues). Lastly, please keep in mind that even software with an entire team working on them often contain bugs and / or undesired results[[6](https://en.wikipedia.org/wiki/2024_CrowdStrike-related_IT_outages)][[7](https://www.bleepingcomputer.com/news/technology/malwarebytes-mistakenly-blocks-google-youtube-for-malware/)]. I try my best as a one man army :)

The primary purpose of the PrivWindoze is to stop and remove any nag screens[[4](https://www.elevenforum.com/t/enable-or-disable-lets-finish-setting-up-your-device-in-windows-11.5205/)], pop ups[[2](https://www.theverge.com/2023/8/30/23851902/microsoft-bing-popups-windows-11-malware)], high CPU usage issues, data collection and transmission[[5](https://www.pcmag.com/news/hp-accused-of-quietly-installing-spyware-on-windows-pcs)] -- also known as telemetry and analytics, as well as removing programs which are difficult to locate and remove or lack an 'Uninstall' button[[1](https://www.wintips.org/fix-cannot-uninstall-microsoft-edge-uninstall-is-greyed-out/)][[3](https://www.reddit.com/r/Hewlett_Packard/comments/lpxcwv/uninstall_hp_touchpoint_analytics_client/)]. Before the tool begins its scan, it will attempt to create a System Restore point. Please refer to this if there are any undesired results on your end. Or... just wait for Microsoft to send the software back to you in a couple of days via Windows Update. After the tool completes its scan, a report entitled 'PrivWindoze.txt' can be found on the User Desktop for review.

[Direct Download Link](https://furtivex.net/PrivWindozeLite.exe) – v2.6.9 [[VT](https://www.virustotal.com/gui/file/032d4046ca3bd32cfb7f14e3b201fb64641bc4f55446a5d4297ca78f85365f1e/detection)]


[![donate_paypal](https://github.com/user-attachments/assets/aadd1f47-fe6a-4f61-97d4-5f30ff29fc33)](https://www.paypal.com/donate/?hosted_button_id=E68FUAQG2758N)  [![donate_amz](https://github.com/user-attachments/assets/10476e9c-92f3-4271-8410-6f38624c94b8)](https://www.amazon.com/hz/wishlist/ls/C2QC509ZM1BG?ref_=wl_share)

![privwindozerun](https://github.com/user-attachments/assets/a6424388-50d1-4305-995c-120c4c30ce21)

Windows Explorer may close during the course of the scan -- This is expected behavior

Log created on the Desktop after execution:

![privwindozelog](https://github.com/user-attachments/assets/f1a9fc24-c3af-44c4-bf3d-fd4d72c108e1)
