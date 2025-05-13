This Project focuses on Sending Emails periodically Using Scheduled Events. It reads an HTML email template and a contact list from S3, and sends out the emails using Amazon SES — all triggered without lifting a finger.
Here are the five AWS services we’ll use:
  Amazon SES for sending the actual emails.
  Amazon S3 to store email templates and recipient lists (CSV or JSON).
  AWS Lambda to run the code that sends emails.
  Amazon EventBridge to schedule email campaigns.
  IAM to give permissions to our services securely.
