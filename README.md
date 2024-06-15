# Donation-Website-with-Payment-Integration
This is a simple yet effective donation website built using HTML and CSS for responsive design. It allows users to support a cause through a secure payment gateway integration with Razorpay. Upon successful donation, an invoice is emailed to the provided address for transparency.

# Features 
Responsive Design: The website adapts seamlessly to various screen sizes (desktop, mobile, tablet) for a user-friendly experience.         Razorpay Integration: Secure and reliable online payment processing through Razorpay.
Email Invoicing: Automatic invoice generation and delivery via email after a successful donation.

# Getting Started:

 Prerequisites:
   - Basic understanding of HTML, CSS, and JavaScript (for Razorpay integration).
   - A Razorpay account ([https://razorpay.com/](https://razorpay.com/)).
   - A functional email server or service to send invoices.

 Configuration:

Razorpay:
     - Create a Razorpay account and obtain your API Key and ID from the dashboard.
     - Update the config.js file with your obtained API Key and ID
     - for creation of payment button we need to go the Razorpay Dashboard and find payment button creation 
     - after successfully creating the button you need to add that link to the code like
     <form><script src="https://checkout.razorpay.com/v1/payment-button.js" data-payment_button_id="pl_OMiFzFGptrHQi5" async> </script> </form>
