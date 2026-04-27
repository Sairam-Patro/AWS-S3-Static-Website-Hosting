<img width="1919" height="1079" alt="Screenshot 2026-04-27 162857" src="https://github.com/user-attachments/assets/767648ee-df6d-4075-8e89-cfb47d6dc340" /># 🌐 AWS S3 Static Website Hosting with Versioning & Lifecycle Management

## 👤 Name

Sairam Patro

## 🆔 Registration Number

12306775

---

## 🎯 Assignment Objective

In this assignment, I worked with Amazon Web Services S3 to understand object storage, static website hosting, version control, and lifecycle management for cost optimization.

---

## 🛠️ Steps Performed

### 1. Created S3 Bucket

* Created a bucket named **sairam-static-website-2026**
* Disabled block public access to allow public hosting

---

### 2. Enabled Versioning

* Enabled versioning in bucket properties
* Uploaded `index.html` file
* Modified and uploaded the file again
* Successfully created multiple versions of the same file

---

### 3. Deployed Static Website

* Enabled static website hosting
* Set `index.html` as index document
* Website is accessible using S3 endpoint

---

### 4. Configured Lifecycle Rules

#### 🔹 Rule 1: Transition Rule

* Name: MoveToIA
* Transition current objects to **Standard-IA after 30 days**

#### 🔹 Rule 2: Delete Old Versions

* Name: DeleteOldVersions
* Permanently delete noncurrent versions after **7 days**

---

## 🌐 Deployed Website Link

http://sairam-static-website-2026.s3-website.us-east-2.amazonaws.com 

---

## 📸 Screenshots

### 1. S3 Bucket Objects

<img width="1640" height="864" alt="Screenshot 2026-04-27 162945" src="https://github.com/user-attachments/assets/a895b165-195d-45ed-ae92-b35403ee186e" />


### 2. Versioning (Multiple Versions)

<img width="1919" height="955" alt="Screenshot 2026-04-27 162125" src="https://github.com/user-attachments/assets/0fb966af-7d8f-4891-b399-6ee74b89303a" />


### 3. Lifecycle Rules

<img width="1919" height="960" alt="Screenshot 2026-04-27 162702" src="https://github.com/user-attachments/assets/f39d00ed-215b-458c-9875-1c59afddc248" />


### 4. Static Website Output

<img width="1919" height="1079" alt="Screenshot 2026-04-27 162857" src="https://github.com/user-attachments/assets/9a408ec5-03eb-4601-b7b8-68efe15d342e" />


---

## ⚠️ Challenges Faced

* Faced issues with public access initially
* Required correct bucket policy configuration
* Understanding lifecycle rules took some time

---

## ✅ Conclusion

This assignment helped me understand:

* Object storage in AWS S3
* Static website deployment
* Version control using S3 versioning
* Cost optimization using lifecycle rules

---
