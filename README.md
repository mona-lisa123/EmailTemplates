# EmailTemplates
Responsive Email Templates
This Email Templates helps everyone who are struggling
 to code their templates.
 How to code for Email Templates?
 1)The design plays major role to build an email template.
 2)If it needs to be responsive then u need to code in table format.
 3)Don't add to many images to email.
 4)Keep it as simple as possible
 5)The CSS should be inline.
 Any HTML template is made of two parts:

    Header section: Any code placed between <head> and </head> is considered, by the rendering engine of an email client, to be the header section. Any media queries, styling and CSS animations are specified in this section.
    Body: Any code placed between <body> and </body> is the body section and the rendering engine uses the code to create the structure of your email.

Step 1: How to Prepare your HTML <head> template:
 <!DOCTYPE html>
<html lang="en" xmlns="http://www.w3.org/1999/xhtml" xmlns:v="urn:schemas-microsoft-com:vml"
    xmlns:o="urn:schemas-microsoft-com:office:office">

<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="x-apple-disable-message-reformatting">
    <title>Reminder Mail</title>
  </head>
  <style>
  1)Here we add the style to remove the spaces around the email
  2)Stops email clients resizing small text.
  3)Centers email on Android 4.4 
  4)Stops Outlook from adding extra spacing to tables.
  5)Fixes webkit padding issue.
  6)Uses a better rendering method when resizing images in IE.
  7)Prevents Windows 10 Mail from underlining links despite inline CSS. Styles for underlined links should be inline.
  8)A work-around for email clients meddling in triggered links. 
  9)Prevents Gmail from changing the text color in conversation threads.
  10)Prevents Gmail from displaying a download button on large, non-linked images.
  11)Add themedia queries at the end
  </style>
  <body>
  The Email Content
  </body>
 
