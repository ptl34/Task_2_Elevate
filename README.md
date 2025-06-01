# Phishing Email Analysis Task

##  Sample Phishing Email

This task focuses on analyzing a suspicious phishing email claiming to be from Binance, promoting an ARB token airdrop. The goal is to identify common phishing indicators and analyze its contents thoroughly.

---

## 🔍 Analysis Steps

### 1. Examine Sender's Email Address for Spoofing
- **Sender**: `BinanceMail <BinanceMail2@onmailcloud.onmicrosoft.com>`
- This email is not from an official Binance domain (e.g., `@binance.com`), indicating spoofing or a fake source.

---

### 2. Check Email Headers for Discrepancies
- The email headers were analyzed using **[MXToolbox Email Header Analyzer](https://mxtoolbox.com/EmailHeaders.aspx)**.
- The analysis revealed inconsistencies in mail routing and sender authentication.
- 📷 **Refer to the image below for the header analysis screenshot:**

![Email Header Analysis](header-analysis.png)

---

### 3. Identify Suspicious Links or Attachments
- The message contains phrases like:
  > "Follow the instructions on our website to check your eligibility. Join Airdrop."
- However, the actual URL is hidden or not shown, which is a red flag.
- No attachments were present in the email, but it still attempts to lure users into clicking suspicious links.

---

### 4. Look for Urgent or Threatening Language
- **Urgent phrases include:**
  - "Limited-time ARB airdrop..."
  - "First 2500 to apply can receive up to 80,000 ARB..."
  - "Ends on July 29, 2023..."
  - "Limited supply... first come, first served."
- These create a sense of urgency to trick users into acting quickly.
- No threatening language was found.

---

### 5. Verify Spelling or Grammar Errors
- Uses **Greek characters** to disguise English letters (e.g., “Β” for “B”).
- Some **text is written in reverse** (e.g., “completely free!”).
- **Numerical formatting is incorrect**, such as “50,00,000” instead of “5,000,000.”
- These are common signs of phishing emails.

---

### 6. Summary of Phishing Traits
- Fake sender address.
- Obfuscated and backward-written text.
- Sense of urgency and hidden URLs.
- Multiple grammar and formatting errors.
- Suspicious calls to action without legitimate verification.

---

##  Tools Used

- **[MXToolbox Email Header Analyzer](https://mxtoolbox.com/EmailHeaders.aspx)** – for checking email header discrepancies.

---

##  Note

Always be cautious with emails promising high rewards, asking for urgent action, or using obfuscated text. Never click unknown links or enter sensitive information unless you're 100% sure of the source.
