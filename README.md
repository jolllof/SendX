# SendX - XRP-Based Money Transfer App  
💸 **Fast, Secure, and Low-Cost International Money Transfers with XRP**  

SendX is a blockchain-powered remittance platform that allows users to send money **instantly** and **cheaply** using the XRP Ledger. Say goodbye to high fees and slow transactions—SendX leverages **XRP's fast settlement times** to move money across borders seamlessly.  

---

## 🌍 Why Use SendX?  
✅ **Instant Transactions** – Settle payments in **seconds**, not days.  
✅ **Ultra-Low Fees** – No high remittance costs or hidden fees.  
✅ **Decentralized & Secure** – Powered by the **XRP Ledger**, ensuring transparency.  
✅ **Multi-Currency Support** – Send and receive in **XRP, USD, GHS, EUR, NGN, etc.**  
✅ **Mobile Money & Bank Integration** – Convert XRP into MoMo (MTN, Vodafone Cash, etc.) and bank deposits.  

---

## 🚀 How It Works  
1. **Deposit Funds**: Load your SendX wallet with XRP or fiat currency.  
2. **Send Money**: Enter the recipient’s details and amount.  
3. **Fast Settlement**: The recipient gets XRP instantly or converted to local currency.  
4. **Withdraw**: Convert XRP to cash via **MoMo, bank transfer, or crypto wallet**.  

---

## 🛠️ Tech Stack  
- **Backend**: Python (Flask) + `xrpl-py` (XRP Ledger API)  
- **Frontend**: React / Next.js  
- **Database**: PostgreSQL / Firebase  
- **Cloud Hosting**: AWS Lambda / Digital Ocean  
- **Payment Integration**: Mobile Money (MTN MoMo, Vodafone Cash), Bank APIs  

---

## 💻 API Endpoints  

### 1️⃣ Check Balance  
**GET** `/balance?address=<XRP_WALLET_ADDRESS>`  
#### Response:  
```json
{
  "address": "rPT1Sjq2YGrBMTttX4GZHjKu9dyfzbpz1S",
  "balance": 50.75
}
