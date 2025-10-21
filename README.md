# Patient Intake Form - EmailJS Setup Guide

This guide will help you set up the email functionality for your patient intake form.

## Step 1: Get Your EmailJS Credentials

### 1.1 Create an EmailJS Account

1. Go to [https://www.emailjs.com](https://www.emailjs.com)
2. Sign up for a free account
3. Verify your email address

### 1.2 Get Your Public Key

1. Log in to your EmailJS dashboard
2. Go to **Account** → **General**
3. Find your **Public Key** (it looks like: `x124YZPrGaddavBqI`)
4. Copy this key

### 1.3 Create an Email Service

1. Go to **Email Services** in the dashboard
2. Click **Add New Service**
3. Choose your email provider (Gmail, Outlook, etc.)
4. Follow the connection steps
5. After setup, copy your **Service ID** (it looks like: `service_468aggq`)

### 1.4 Create an Email Template

1. Go to **Email Templates** in the dashboard
2. Click **Create New Template**
3. Copy and paste the HTML template code provided separately
4. Set the **Subject** to: `New Patient Intake - {{firstName}} {{lastName}}`
5. Save the template
6. Copy your **Template ID** (it looks like: `template_sab5nd21`)

---

## Step 2: Update Your JavaScript File

Open your JavaScript file and find these lines at the top:

```javascript
// EmailJS Configuration
const EMAILJS_PUBLIC_KEY = "YOUR_PUBLIC_KEY_HERE";
const EMAILJS_SERVICE_ID = "YOUR_SERVICE_ID_HERE";
const EMAILJS_TEMPLATE_ID = "YOUR_TEMPLATE_ID_HERE";
```

**Replace the values** with your own credentials:

1. Replace `"YOUR_PUBLIC_KEY_HERE"` with your **Public Key**
2. Replace `"YOUR_SERVICE_ID_HERE"` with your **Service ID**
3. Replace `"YOUR_TEMPLATE_ID_HERE"` with your **Template ID**

---

## Step 3: Test Your Form

1. Save your JavaScript file
2. Open your website in a browser
3. Fill out the patient intake form
4. Click **Submit Information**
5. Check your email inbox (the one you configured in EmailJS)
6. You should receive the patient intake form data

---

## Troubleshooting

### Email not sending?

- ✅ Double-check all three credentials are correct
- ✅ Make sure there are no extra spaces in the credentials
- ✅ Verify your EmailJS service is connected properly
- ✅ Check the browser console for error messages (Press F12)
- ✅ Make sure you're not exceeding EmailJS free tier limits (200 emails/month)

### Form submits but no email received?

- ✅ Check your spam/junk folder
- ✅ Verify the email address in your EmailJS service settings
- ✅ Test with a different email address

### Need Help?

- EmailJS Documentation: [https://www.emailjs.com/docs](https://www.emailjs.com/docs)
- EmailJS Support: Contact through their dashboard

---

## Free Tier Limits

EmailJS free plan includes:

- 200 emails per month
- 2 email templates
- 1 email service

If you need more, consider upgrading to a paid plan.

---

**That's it! Your patient intake form should now send emails successfully.** 🎉# Patient Intake Form - EmailJS Setup Guide

This guide will help you set up the email functionality for your patient intake form.

## Step 1: Get Your EmailJS Credentials

### 1.1 Create an EmailJS Account

1. Go to [https://www.emailjs.com](https://www.emailjs.com)
2. Sign up for a free account
3. Verify your email address

### 1.2 Get Your Public Key

1. Log in to your EmailJS dashboard
2. Go to **Account** → **General**
3. Find your **Public Key** (it looks like: `x186YZPrGmxdavBqI`)
4. Copy this key

### 1.3 Create an Email Service

1. Go to **Email Services** in the dashboard
2. Click **Add New Service**
3. Choose your email provider (Gmail, Outlook, etc.)
4. Follow the connection steps
5. After setup, copy your **Service ID** (it looks like: `service_837evgq`)

### 1.4 Create an Email Template

1. Go to **Email Templates** in the dashboard
2. Click **Create New Template**
3. Copy and paste the HTML template code provided separately
4. Set the **Subject** to: `New Patient Intake - {{firstName}} {{lastName}}`
5. Save the template
6. Copy your **Template ID** (it looks like: `template_sy5ng29`)

---

## Step 2: Update Your JavaScript File

Open your JavaScript file and find these lines at the top:

```javascript
// EmailJS Configuration
const EMAILJS_PUBLIC_KEY = "x186YZPrGmxdavBqI";
const EMAILJS_SERVICE_ID = "service_837evgq";
const EMAILJS_TEMPLATE_ID = "template_sy5ng29";
```

**Replace the values** with your own credentials:

1. Replace `"x186YZPrGmxdavBqI"` with your **Public Key**
2. Replace `"service_837evgq"` with your **Service ID**
3. Replace `"template_sy5ng29"` with your **Template ID**

### Example:

```javascript
// EmailJS Configuration
const EMAILJS_PUBLIC_KEY = "YOUR_PUBLIC_KEY_HERE";
const EMAILJS_SERVICE_ID = "YOUR_SERVICE_ID_HERE";
const EMAILJS_TEMPLATE_ID = "YOUR_TEMPLATE_ID_HERE";
```

---

## Step 3: Test Your Form

1. Save your JavaScript file
2. Open your website in a browser
3. Fill out the patient intake form
4. Click **Submit Information**
5. Check your email inbox (the one you configured in EmailJS)
6. You should receive the patient intake form data

---

## Troubleshooting

### Email not sending?

- ✅ Double-check all three credentials are correct
- ✅ Make sure there are no extra spaces in the credentials
- ✅ Verify your EmailJS service is connected properly
- ✅ Check the browser console for error messages (Press F12)
- ✅ Make sure you're not exceeding EmailJS free tier limits (200 emails/month)

### Form submits but no email received?

- ✅ Check your spam/junk folder
- ✅ Verify the email address in your EmailJS service settings
- ✅ Test with a different email address

### Need Help?

- EmailJS Documentation: [https://www.emailjs.com/docs](https://www.emailjs.com/docs)
- EmailJS Support: Contact through their dashboard

---

## Free Tier Limits

EmailJS free plan includes:

- 200 emails per month
- 2 email templates
- 1 email service

If you need more, consider upgrading to a paid plan.

---

**That's it! Your patient intake form should now send emails successfully.** 🎉

```javascript
// EmailJS Configuration
const EMAILJS_PUBLIC_KEY = "YOUR_PUBLIC_KEY_HERE";
const EMAILJS_SERVICE_ID = "YOUR_SERVICE_ID_HERE";
const EMAILJS_TEMPLATE_ID = "YOUR_TEMPLATE_ID_HERE";
```

---

## Step 3: Test Your Form

1. Save your JavaScript file
2. Open your website in a browser
3. Fill out the patient intake form
4. Click **Submit Information**
5. Check your email inbox (the one you configured in EmailJS)
6. You should receive the patient intake form data

---

## Troubleshooting

### Email not sending?

- ✅ Double-check all three credentials are correct
- ✅ Make sure there are no extra spaces in the credentials
- ✅ Verify your EmailJS service is connected properly
- ✅ Check the browser console for error messages (Press F12)
- ✅ Make sure you're not exceeding EmailJS free tier limits (200 emails/month)

### Form submits but no email received?

- ✅ Check your spam/junk folder
- ✅ Verify the email address in your EmailJS service settings
- ✅ Test with a different email address

---

## Free Tier Limits

EmailJS free plan includes:

- 200 emails per month
- 2 email templates
- 1 email service

If you need more, consider upgrading to a paid plan.

---

**That's it! Your patient intake form should now send emails successfully.** 🎉
