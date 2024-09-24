# Setup Twilio + Sendgrid email sending
### 1) Sign in or Signup to SendGrid.
### 2) Create a new sender in Marketing > Senders > Create new sender.
### 3) Repeat the next step for each template
  - Create dynamic template for OTP in Email API > Dynamic templates > Create dynamic template
  - You can use already-made templates in the repository's [TWILIO_EMAIL_TEMPLATES](/TWILIO_EMAIL_TEMPLATES) directory.

### 4) Create Sendgrid API key in Settings > API keys > Create API key.
### 5) Sign in or Sign Up to Twilio.
### 6) Go to verify > settings > Email integration.
<br><br>

### Repeat all steps from Step #7 to Step #12 for each dynamic template

<br><br>
### 7) Click on "Create new integration"
### 8) Blank a form:
  - Integration name
  - “From” email address - email you've specified in senders
  - “From” name - use name that you specified in senders
  - SendGrid API key - API key created in the SendGrid
  - Template ID - dynamic template ID (Open Sendgrid > Email API > Dynamic templates > dropdown dynamic template's name and you'll see the template ID)
### 9) Go to verify/services
### 10) Click on "Create new"
### 11) Blank a form:
  - Friendly name
  - Verification channels - choose email
### 12) In service details click on "Email" and choose email integration you've created before

### 13) Copy the ID of each Twilio service you've created.
### 14) Copy the Account SID and Auth token on the dashboard page.

### 15) Use all services' identifiers, Account SID, and Auth Token in the [User microservice](https://github.com/GhostMEn20034/SM1L3_SAL3S_user_microservice).
