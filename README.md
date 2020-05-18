# Shopify Guide
This is a guide for Shopify Conversion

## Table of Contents

- [Uploading Template Files](#uploading-template-files)
- [Sending Feedback](#edit-template-files)

## Uploading Template Files

##### 1. Go to "Themes" page on your shopify website
![alt text](https://github.com/prospkarl/shopifytemplate/blob/master/images/themes_page.png?raw=true)

##### 2. Scroll down and Click "Upload Theme" button
![alt text](https://github.com/prospkarl/shopifytemplate/blob/master/images/upload_btn.png?raw=true)

##### 3. Upload the template files (.zip file from our /template folder)
![alt text](https://github.com/prospkarl/shopifytemplate/blob/master/images/upload_template.png?raw=true)

##### 4. Preview Website
Click on the "Eye" icon from the sidebar.

The website must look like this:
![alt text](https://github.com/prospkarl/shopifytemplate/blob/master/images/done_upload.png?raw=true)

## Edit Template files

Make sure you've installed "Theme Kit". Install theme kit here: https://shopify.github.io/themekit/

##### 1. Create a blank folder and create a file named as "config.yml"
![alt text](https://github.com/prospkarl/shopifytemplate/blob/master/images/createconfig.png?raw=true)

##### 2. Edit file using "Notepad" and copy paste the code below:

```
development:
  password: [ADMIN API > PASSWORD]
  theme_id: [Click themes > Actions > Edit Code > Get the last key of the url /admin/themes/0128042 <--]
  store: [samplewebsite.myshopify.com]
```

**Note:** _To get these credentials go to your account and get to Sidebar > Apps. And click "Manage private apps". Create an app, and get credentials from there._
