---
layout: post  
title: Parental Controls - How to setup Safe Browsing for Kids 
date: 2025-03-16 23:34:00 +0300  
categories: [blog]  
tags: [learning, parenting control, kids safe browsing]  
# excerpt: A warm welcome to my corner of the internet — a space for learning, creating, reflecting, and growing across disciplines.  
---
# How to Block Inappropriate Content and Malware at Your Home or Office Wi-Fi connected devices

Whether you are managing a home for your family, or any small space, an unfiltered internet connection can be a liability. From malicious phishing links to inappropriate content, the digital world requires proactive "guardrails."

For working parents, the internet is a vital tool for our children’s education, but leaving them home with an open connection can be stressful. We can't always be vigilant, and we shouldn't have to be. The goal is to build a home environment where "bad turns" are blocked automatically, allowing kids to focus on their online classes while you focus on your work.

Here is a simple strategy list to protect your home, ordered from the easiest daily habits to the most powerful "hidden" protections.

---
 ## 1. **If you wish to block Youtube from your home pc or any specific website altogether, do the following:**
 So to completely block YouTube on your Windows PC, you can use a system-level block that prevents access across all web browsers and applications.  
**Method 1:** Editing the Hosts File (Hardest to Bypass)  
The most effective free way to block YouTube system-wide is by editing the Windows "hosts" file. This method redirects all requests for YouTube to your own computer, effectively killing the connection.  

   1. Open Notepad as Administrator: Press the Windows Key, type Notepad, right-click it, and select Run as administrator.
   2. Open the Hosts File: In Notepad, go to File > Open and navigate to:
   C:\Windows\System32\drivers\etc
   Change the file type filter in the bottom-right from "Text Documents (.txt)" to All Files to see the hosts file*.
   3. Add Block Lines: Scroll to the bottom and add these lines on new rows:
   
   127.0.0.1 youtube.com
   127.0.0.1 www.youtube.com
   127.0.0.1 m.youtube.com
   
   4. Save and Refresh: Save the file (Ctrl + S). To make it take effect immediately, open Command Prompt as administrator and type ipconfig /flushdns, then press Enter.  

**Method 2:** Router-Level Blocking (Network-Wide)
If you want to block YouTube on every device in your home (PCs, tablets, and phones), you can do it through your Wi-Fi router. 

   1. Log in to your router's admin panel (usually by typing 192.168.1.1 or 192.168.0.1 in your browser).
   2. Look for Parental Controls, Access Control, or URL Filtering.
   3. Add youtube.com to the blocked list or blacklist. 
---
Although blocking YouTube solves the root cause problems ariving from it but, blocking it, is always not an option, since YouTube is often their primary source of information and entertainment. You can lock it into a safer mode that filters out mature content and—crucially—**hides the comments section** to prevent interaction with strangers.

## 2. Level One: The Clean Video 
*Best for: Managing entertainment and school research during the day.*

* **On a Smartphone/Tablet:** Open YouTube > Tap **Profile Picture** > **Settings** > **General** > Toggle **Restricted Mode** to **ON**.
* **On a Computer:** Go to YouTube.com > Click your **Profile Picture** > Click **Restricted Mode** at the bottom > Toggle to **ON**.
  
## 3. Level Two: Browser-Level Safe Search
*Best for: Ensuring school research doesn't lead to accidental adult results.*

Even innocent searches can sometimes show explicit images. You can force the browser to only show age-appropriate results.

* **Google SafeSearch:** Go to [google.com/safesearch](https://www.google.com/safesearch) and select **Filter**.
* **Secure Browser Settings:** In Chrome or Edge, go to **Settings** > **Privacy & Security** > **Security**. Under "Use Secure DNS," select "Choose a provider" and use a family-safe option (like `https://family.cloudflare-dns.com/dns-query`).
---

## 4. Level Four: The Whole House Shield (Router Method)
*Best for: Protecting everything at once—Smart TVs, Gaming Consoles, and Laptops.*

This is the most efficient method for a working parent. By changing this one setting on your home router, every single device in your house is automatically safe. You don't have to check their phones every day; the "rules" are built into the Wi-Fi itself.

**For Etisalat eLife (and similar) users:**
1.  **Access your Router:** Open your browser and go to `192.168.1.1`.
2.  **Find the Network Settings:** Click **Interface Mgmt** (top) then **BRouted Interfaces** (left).
3.  **Update the Safety Numbers:** Find your active connection (like **brvlan9**) and change the **DNS Relay Source** to **User Defined**.
4.  **Enter these Addresses:**
    * **Primary DNS:** `1.1.1.3`
    * **Secondary DNS:** `1.0.0.3`
5.  **Apply & Save:** Once saved, your home network is officially a "Safe Zone."

*You settings may vary slightly based on your Router and Internet provider*
---

## Peace of Mind Checklist
Before you head to work, you can verify if your "guardrails" are active by visiting these test sites on any home device. If they **do not load**, your family is protected:
* **Malware Test:** [https://malware.testcategory.com/](https://malware.testcategory.com/)
* **Adult Content Test:** [https://nudity.testcategory.com/](https://nudity.testcategory.com/)

*Stay safe, stay secure, and let the technology do the supervising for you!*
