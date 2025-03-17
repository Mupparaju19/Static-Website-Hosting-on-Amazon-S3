
# 🌐 Hosting a Static Website on AWS S3 🚀  

![AWS S3 Static Website](https://img.shields.io/badge/AWS-S3-orange?style=flat-square&logo=amazonaws)  
 


🎯 **This repository provides a complete guide to hosting a static website on AWS S3** with public access enabled.  
📌 **Perfect for portfolios, blogs, business landing pages, or learning AWS!**  

---

## 📂 Repository Structure


📁 **Source Code** – HTML, CSS, JavaScript, and assets.  
📄 **Configuration Files** – AWS S3 settings and bucket policies.  
📜 **Supporting Documentation** – Guides, FAQs, and troubleshooting help.  


---

## 🚀 How to Use This Repository

1️⃣ **Browse the Repository**  
   🔍 Find the folder that matches the tutorial or topic you're interested in.  

2️⃣ **Follow Along**  
   📜 Use the provided code and instructions to **build, deploy, and experiment** with AWS S3 hosting.  

3️⃣ **Customize & Deploy**  
   🎨 Modify the HTML/CSS files to create your own **personal or business website**.  

---

## 🌍 What is a Static Website?

A **static website** means that its content does not change dynamically (e.g., no databases or backend servers).  

✨ **Benefits of a Static Website**:  
✅ **Fast Loading** – No server-side processing required.  
✅ **Secure** – No backend vulnerabilities, making it safer.  
✅ **Scalable** – Easily handles high traffic.  
✅ **Low Cost** – Pay only for storage and bandwidth.  

🔹 **Common Use Cases:**  
- Personal portfolios  
- Blogs & documentation sites  
- Business landing pages  
- Simple web applications  

Make sure your website includes **HTML, CSS, JavaScript, and images** before deploying.  

---

## 🔐 S3 Bucket Policy for Public Access

To make your static website publicly accessible, use the following **AWS S3 bucket policy**:

```json
{
    "Version": "2012-10-17",
    "Statement": [
        {
            "Sid": "PublicReadGetObject",
            "Effect": "Allow",
            "Principal": "*",
            "Action": "s3:GetObject",
            "Resource": "arn:aws:s3:::muppraju/*"
        }
    ]
}
```

### 📌 Steps to Apply the Policy:
1️⃣ Go to **AWS S3 Console** → Select your **S3 bucket**.  
2️⃣ Navigate to the **Permissions** tab.  
3️⃣ Scroll down to **Bucket Policy**.  
4️⃣ Paste the above policy (**Replace `muppraju` with your actual bucket name**).  
5️⃣ Click **Save** ✅  

---

## 💡 Contribution

💻 Want to improve this project? Your contributions are welcome!  

📌 **How to Contribute:**  
- Submit **Pull Requests** for feature improvements or fixes.  
- Open **Issues** if you find bugs or have suggestions.  
- Share ideas to enhance the project!  



