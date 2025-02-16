# Pinterest Listicle Automation

## 1. Project Title
**Pinterest Listicle Automation**  
A streamlined workflow to generate and publish listicle-style blog posts for Pinterest, combining Instagram image downloads, AI-powered metadata generation, and automated WordPress uploads.

## 2. Introduction
Creating engaging, SEO-optimized listicle blog posts can be time-consuming, especially when manually curating content and crafting descriptions. This project simplifies and automates the workflow, allowing users to:
- Download images from Instagram using a CSV file of links.
- Use AI to generate metadata, including image descriptions, Pinterest titles, and blog content.
- Rename images for improved SEO and Pinterest discoverability.
- Upload images and structured HTML content to WordPress via API.
- Automate Pinterest pin publishing using **Make.com** integration.

By combining manual image curation with AI-powered processing, this project accelerates content creation while maintaining creative control over image selection.

## 3. Features
✅ **Automated Image Downloads** – Fetch images from Instagram using a CSV file of post links.  
✅ **AI-Generated Image Metadata** – Extracts relevant descriptions, titles, and SEO-friendly content for each image.  
✅ **SEO-Friendly Image Renaming** – Renames images with descriptive filenames for better Pinterest ranking.  
✅ **WordPress Integration** – Uploads images and structured HTML content automatically via API.  
✅ **Pinterest Automation Support** – Designed to work seamlessly with **Make.com** for scheduled Pinterest pin publishing.  
✅ **Flexible Configuration** – Customize folder paths, API keys, and other settings to fit your workflow.  

## 4. How It Works (Step-by-Step)

This project follows a structured workflow to automate the creation of listicle-style blog posts for Pinterest. Below is an overview of each step:

### **Step 0: Setup Paths**
- Configures folder paths for images, CSV files, JSON metadata, and HTML output.
- Ensures that all required directories exist before processing begins.

### **Step 1: Download Images from Instagram**
- Reads a **CSV file** containing Instagram post URLs.
- Uses **Instaloader** to fetch images from public Instagram posts.
- Saves downloaded images in the specified folder for further processing.

### **Step 2: Generate AI-Powered Metadata**
- Uses **ChatGPT (GPT-4 Vision)** to analyze images and generate:
  - **Image Titles** – Descriptive and SEO-optimized.
  - **Blog Post Descriptions** – Engaging text for blog content.
  - **Pinterest Titles & Descriptions** – Optimized for search and user engagement.
  - **SEO Metadata** – Includes a blog title, meta description, and an introduction.

### **Step 3: Rename Images for SEO**
- Assigns a **descriptive filename** to each image based on AI-generated metadata.
- Uses **SEO-friendly naming conventions** to improve discoverability on Pinterest.
- Ensures filenames are unique and properly formatted.

### **Step 4: Upload Content to WordPress**
- Uploads images to **WordPress Media Library** via API.
- Generates an **HTML-formatted listicle blog post** containing:
  - Image elements
  - AI-generated descriptions and metadata
- Automatically publishes or saves the post as a draft on WordPress.

This structured process **reduces manual effort** while maintaining high-quality, curated content optimized for **Pinterest SEO and user engagement**.

## 4. What's next

Once you have your article finished you can publish the images in the listicle as pins on Pinterest. I could not do this by connecting with the Pinterest API. I'm currently using a Make.com template that allows you to publish on pinterest based on data in a google sheets, so that's what I do. Transform the metadata in json to csv, then to sheets, then run the scenario on Make.

## 5. License

This project is licensed under the **MIT License**.

You are free to use, modify, and distribute this project as long as the original license is included.  
The software is provided "as-is" without any warranties or guarantees.

For full details, see the [LICENSE](LICENSE) file.

