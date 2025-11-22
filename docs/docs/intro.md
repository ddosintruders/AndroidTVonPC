---
sidebar_position: 1
---

# Intro to installing Android TV on a PC

Android TVs are becomming common as a platform to stream media like YouTube and various other apps, but on wider and bigger screens. There's no native way by Google to add Android TV to a digital TV/Screen as these do not have an environment to host OSes like bootloaders, BIOS, firmware etc.. That is why we use PCs to boot Android TV.

I usually prefer individuals avoid buying Smart TV Boxes such as [these](https://www.amazon.com/Upgrade-10-0-Allwinner-Quad-core-Bluetooth/dp/B08CRV62C4?dib=eyJ2IjoiMSJ9.wUa_OOr8gCX-pp0LGcGUqGILEP2e4Djqi9iq1_Qzfjcug0jZ4lvFUIGTzU0QlgAqOfpajvP22Lm9AfVxB9WKCYMR80d3mG3tNVFVFqzL9KlupfBQkpoUrSNDRLNtHP_OfTWGvGg4UggcC2vDW_dD8VlyjRaj9e6Xx0cZZlyAkz7Qv0FgehUuAqPAgmIjeUtgYvQWSWxEd2WCP6tUOlNnaAOCDobuMTgI_Hx-tLFI66A.DH9d1l59Jebnyb3R8Muh3UxAJu9yBK7OBJnWRMp3xAk&dib_tag=se&keywords=android+tv+box&qid=1763795959&sr=8-5) because they have nefarious network monitoring settings baked into the core to provide telemetry data to unknown Chinese servers, causing your accounts to be compromised. For an in-depth explanation, watch this:

<iframe width="400" height="200" src="https://www.youtube.com/watch?v=1vpepaQ-VQQ&t=498s" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

To circumvent this, and enjoy Android TV, hmtheboy154 decided to fork builds from LineageOS and LMODroid to create bootable ISO Images for PCs to boot Android TV from PCs.


:::warning[Take Note]
This project will overwrite data from your USB storage devices that you'll use in the next steps. Please make sure to do a full backup of your data before you proceed if you have any content stored on the USB Storage Device
:::

<div align="center">
  <p>If this guide helps you, consider donating on Ko-Fi to maintain these tutorials and add improvements.</p>
  [![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/I2I51O7J3E)  
</div>