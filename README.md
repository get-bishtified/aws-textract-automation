# 🧠 OCR Automation on AWS with Lambda + Textract + S3 + SNS

This project automatically extracts text from uploaded images/documents using **Amazon Textract**, stores the output in **S3**, and sends a **pre-signed download link via email** using **SNS**.

---

## ✅ Features

- 🔁 Automatically triggered by S3 uploads
- 🧠 Uses `Textract` to extract text from documents
- 💾 Stores `.txt` output in `results/` folder of another S3 bucket
- 🔗 Generates secure pre-signed URLs
- 📧 Sends OCR results via SNS email notifications

---

## 🛠️ Technologies Used

- **AWS Lambda** – Serverless OCR handler
- **Amazon S3** – Storage for input & output
- **Amazon Textract** – Text extraction engine
- **Amazon SNS** – Email notification with download link
- **Python (boto3)** – AWS SDK

---

## 🎥 Learn With YouTube Tutorials

Each project is **explained step-by-step** on YouTube with visuals and walkthroughs:

🔗 [📺 Bishtify - Build Skills, Not Just Resumes](https://www.youtube.com/@getbishtified) 
🧠 Subscribe for weekly ML + CloudOps demos.

---

📩 **Contact:**  
📧 `support@bishtify.com`

🤝 Connect With Me - 📧 [Click here](https://topmate.io/pradeep_singh_bisht)
🔗 Get Bishtified with:
Bishtify - Let’s build skills — not just resumes! 🚀
