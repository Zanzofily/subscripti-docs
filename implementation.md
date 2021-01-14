# Implementation

> Subscripti can be intgreated using JS only or Using the Rest API

## JS & HTML Simple implementation

You can use the admin panel to genereate a subscription button code for each plan.

1. From sidebar click on `Subscription plans`.
2. From the dropdown list click `List`
3. On the `action` column for the desired plan click the three dots then `get code`
4. Copy the output code and place it anywehere and you'll have your purchase button.

### Important Notes

- You can use the customer_email data attriburte to pre define the customer's email.
- If you're adding multiple plan buttons inside the same page don't duplicate the JS Library code `<script src="http://localhost:8000/api/payment/js"></script>`
- You can modify the styles of any element using css to match what you want.
- Error and success elements can be placed anywhere in the page.

## Backend Implementation

Sometimes you've a content or certain pages that you want to allow only subscriped users to see or visit. Through our `Rest API` [payment status](https://documenter.getpostman.com/view/1772068/TVzUDweA#41e1d113-baa0-4185-a988-070503fdb30e) request you can verify that the logged in user has purchased a plan.
