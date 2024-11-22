# Password Reset Flow with Email Verification
This project implements a secure password reset flow with email verification using React for the front-end, Node.js for the back-end, and Bootstrap for the UI framework.

# Postman API Documentation Link
https://web.postman.co/workspace/87ff17a0-e7e0-4064-87ca-1d9a2f74a0d2/documentation/39168683-ebc537a4-bb53-4ccd-be5d-954114a7d24b

# Features
Forget Password Page: Users can request a password reset by entering their email address.
Email Verification: A reset link containing a unique token is sent to the user's email.
Secure Token Validation: The unique token is stored and verified in the database.
Password Reset Form: Users can set a new password after verifying the reset token.
Token Expiry: The reset token is cleared from the database once the password is successfully updated.
Responsive UI: The front-end uses Bootstrap for a clean and responsive design.

