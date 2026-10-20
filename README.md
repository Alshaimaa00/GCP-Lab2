# Static Website on Google Cloud Storage ☁️

## 📍 About
A hands-on lab where I hosted a static website on **Google Cloud Storage** by creating a bucket, uploading my `index.html`, and making it publicly accessible through a URL.

## 🚀 Steps
1. **Create a bucket** in Cloud Storage with a globally unique name, a region (`me-central1`), the Standard storage class, and fine-grained access control.
2. **Remove public access prevention** from the bucket permissions so it can be shared.
3. **Upload** `index.html` to the bucket.
4. **Make it public:** in the bucket's Permissions tab, grant access to `allUsers` with the **Storage Legacy Object Reader** role.
5. **Open the site:** copy the object's public URL and paste it in the browser:
   ```
   https://storage.googleapis.com/<bucket-name>/index.html
   ```

## 📂 Files
- `Google cloud platform lab2.pdf`: the full lab report with screenshots

**Tools:** Google Cloud Storage · IAM Permissions · HTML
