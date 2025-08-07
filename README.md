🧠 OCR Automation on AWS with Lambda + Textract + S3 + SNS
Automatically extract text from uploaded documents or images using AWS Textract, and notify users with a pre-signed download link via email. This serverless pipeline runs on AWS Lambda, triggered by S3 events.

📌 Features
🗂 S3 Trigger: Uploading a file to input-bucket triggers the Lambda.

🧠 OCR with Textract: Detects text using DetectDocumentText API.

💾 Text Storage: Extracted text saved as .txt in output-bucket/results/.

🔗 Presigned URL: Generates a secure link to the result file.

📬 Email Notification: Sends the link to a pre-configured email via SNS.

⚙️ AWS Services Used
Amazon S3 – For storing input images and output text files

AWS Lambda – Serverless compute to run the OCR logic

Amazon Textract – For extracting text from documents

Amazon SNS – To email the pre-signed link

IAM – Permissions for Lambda to access all required services
