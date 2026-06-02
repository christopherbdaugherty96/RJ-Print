# RJ Print Contact And Custom Request Form Spec

Status: planning baseline

## Purpose

Define the first version of the website form so RJ Print can receive useful customer inquiries without needing a complex backend.

## Recommended v1 approach

Use one simple contact/custom request form.

The form should support:

- general questions
- product inquiries
- custom print requests
- business/bulk order inquiries

## Required fields

- Name
- Email
- Request type
- Message / project details

## Recommended fields

- Phone optional
- Product or category interested in
- Quantity
- Preferred color/material if known
- Size or measurements if relevant
- Deadline if relevant
- Pickup or shipping preference
- Budget range optional
- Reference image/file link optional

## Request type options

- General question
- Ready-made product inquiry
- Made-to-order product inquiry
- Custom print request
- Business / bulk order

## File upload note

Do not add a complex file upload system unless the tool/platform is confirmed.

Simpler v1 options:

1. Ask customers to paste a link to reference images/files.
2. Have the form send the inquiry first, then reply by email for photos/files.
3. Use a third-party form tool with upload support only after testing.

## Form success message

Thank you. Your request has been sent to RJ Print. Custom print requests are reviewed before price and timeline are confirmed.

## Form fallback message

If the form does not work, contact RJ Print directly at the confirmed business email.

## Email notification content

Form submissions should include:

- customer name
- customer email
- request type
- product/category
- quantity
- size/measurement notes
- color/material preference
- deadline
- pickup/shipping preference
- message/details
- reference link if provided

## Anti-overpromise note

The form should not imply every request is automatically accepted. Use language like:

- We will review your request.
- Custom prints are quoted before production.
- Some requests may require follow-up questions.

## Privacy note

Only ask for information needed to respond to the request. Do not ask for payment information through a basic contact form.

## Testing checklist

- [ ] Submit test form from desktop.
- [ ] Submit test form from phone.
- [ ] Confirm notification arrives.
- [ ] Confirm reply-to email works.
- [ ] Confirm required fields work.
- [ ] Confirm success message appears.
- [ ] Confirm fallback contact info is visible.

## Later improvements

- File upload
- Separate product inquiry and custom quote forms
- CRM tracking
- Automated email response
- Shopify draft order creation
- Customer approval workflow
