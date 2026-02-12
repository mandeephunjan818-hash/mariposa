# Domain Setup Guide for Mariposa SaaS Platform

This guide walks you through the complete process of adding and configuring a custom domain for email services on the Mariposa platform. By the end of this documentation, you will have a verified, dedicated email domain ready to send and receive messages through your Mariposa inbox.

---

## Prerequisites

- Access to the Mariposa platform at [https://app.gpomariposa.com/](https://app.gpomariposa.com/)
- Administrator privileges on the account you intend to use
- A domain name already registered with a supported domain provider
- Ability to modify DNS records (or use the auto‑configure feature)

---

## Step 1: Switch to Your Account

<img src="images/settings.png">

1. Open the Mariposa application in your browser.  
2. On the **vertical navigation bar** (left side), locate and click the **Click here** button – it is the very first button at the top of the navbar.  
3. A list of available accounts will appear. Select the account **you own** (or the one you wish to work on).  
4. You are now successfully switched from the main account to your own account.

---

## Step 2: Add a Branded Domain in Business Profile

1. In the same left vertical navbar, scroll to the **bottom** and click **Settings**.  
2. You will be taken to your profile settings dashboard.  
3. From the settings navigation bar (left side), click **BusinessProfile**.  
4. On the Business Profile page, locate the **Branded Domain** input field.  
5. Enter the domain you intend to use for mail services (e.g., `yourcompany.com`).  
6. Click the **Add** button.  
7. The system will display your domain provider’s name and automatically initiate a connection to the domain hosting server.  
   - *Mariposa will attempt to establish a connection with your provider automatically.*  
   - You may be temporarily redirected to your domain provider’s interface; this is normal.

---

## Step 3: Update Information

1. Return to the **BusinessProfile** page (if you were redirected).  
2. In the **Branded Domain** input card, locate the **Update information** button at the end of the card.  
3. Click **Update information** to ensure your domain details are synchronised with the platform.

---

## Step 4: Create and Verify a Dedicated Email Domain

1. Still in the profile settings dashboard, go to the left navigation bar and click **Email services**.  
2. An automatic pop‑up will appear. At the bottom of this pop‑up, click **Create a dedicated domain**.  
3. On the next page, you will see an **Enter domain Name** field.  
   - **Important:** This domain (or subdomain) should be specifically reserved for email operations, e.g., `mail.yourcompany.com` or `emails.yourcompany.com`. It is **not** the same as the Branded Domain added in Step 2.  
4. Enter your chosen dedicated email domain and click **Add**.  
5. You will be redirected to a page showing multiple cards – each card represents a dedicated email domain along with its verification status and DNS configuration state.  
6. Find the card corresponding to the domain you just added. At the bottom of the card, click the **Verify domain** link.

---

## Step 5: Configure DNS Records (Auto‑Configure Recommended)

1. The verification page displays all required DNS records (e.g., TXT, MX, CNAME) that must be set on your **dedicated email domain**.  
   - **These records must be configured on the domain you entered in Step 4 – not on the Business Profile Branded Domain.**  
2. To simplify the process, Mariposa offers an **Auto‑configure DNS record** feature.  
   - Scroll to the bottom of the page and click **Auto‑configure DNS record**.  
   - The platform will attempt to automatically add the necessary DNS records through your domain provider.  
3. After a moment, refresh the page.  
4. Click the **Verify** button (located next to the Auto‑configure button).  
5. Once verification succeeds, the card for your domain will show **Verified** and all DNS checks will be marked as complete.

> **Note:** If your domain provider does not support auto‑configuration, you must manually add the displayed DNS records in your provider’s control panel. After adding them, return to Mariposa and click **Verify**.

---

## Step 6: Access the Inbox and Send Email

1. Exit the profile settings dashboard by clicking the **backward navigation** button located at the top of the settings navbar.  
2. You are now in the main profile dashboard.  
3. Navigate to the **Conversations** page (also referred to as the **Mailbox**).  
   - This interface provides a rich set of features for managing contacts, conversations, and emails.  
4. Click on any **contact name** to open the email composer.  
5. The composer will now allow you to send emails **using your custom, verified domain**.  
   - Congratulations! Your domain is fully set up and ready for email services.

---

## Conclusion

You have successfully added a branded domain, created a dedicated email domain, configured the required DNS records, and verified everything – all within the Mariposa SaaS platform. Your organisation can now send and receive emails using your own domain, enhancing brand consistency and deliverability.

For further assistance with contact management, automation, or advanced email features, refer to the subsequent documentation sections.
