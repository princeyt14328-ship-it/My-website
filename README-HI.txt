PRINCE YT STORE — UPGRADE FILES

GitHub par upload:
1) Repository My-website kholo.
2) Purani index.html ko replace karo (ya pehle backup/download kar lo).
3) manifest.json, sw.js, icon.svg ko bhi repository ke root mein upload karo.
4) Commit changes karo; GitHub Pages ko 1-3 minute do.
5) Website reload karo. App install option supported browser mein dikh sakta hai.

IMPORTANT SETUP:
- index.html mein STORE ke default values placeholders hain: yourname@upi aur your_username.
- Real payments lene se pehle apni valid UPI ID, payee name, Telegram username set karo.
- Better: config.js banao aur is format mein store settings/products set karo:
  window.STORE_CONFIG = {
    store: { name: "Prince YT", upiId: "YOUR_UPI_ID", payeeName: "YOUR_PAYEE_NAME", telegram: "YOUR_TELEGRAM_USERNAME" },
    products: [
      { id:"thumb", tag:"Thumbnails", icon:"🎮", name:"Product name", price:99, desc:"Accurate description", meta:"File type / delivery" }
    ]
  };
- config.js ko index.html ke saath same root mein upload karo. UPI/Telegram details public webpage code mein visible hoti hain; sirf woh business contact/payment details publish karo jo share karna safe hai.
- This site does not verify payments automatically. Verify payments yourself and never ask buyers for UPI PIN or OTP.
- Products shown by default are demo listings; replace them with products you actually own and can deliver.
