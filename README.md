# Clear Books

Clear Books is UK cloud accounting software with a REST API for managing invoices, expenses, bank transactions, contacts, reports, and tax submissions for small businesses.

## API

The Clear Books REST API allows third-party applications to integrate with Clear Books accounting data. Key capabilities include:

- Adding sales and purchase invoices
- Voiding previously added invoices
- Recording and allocating payments to invoices
- Adding, updating, and deleting customers and suppliers
- Bank transaction management
- Expense tracking

**API Documentation:** https://api-docs.clearbooks.co.uk/

**Authentication:** OAuth 2.0 — https://oauth-helper.clearbooks.co.uk/

**Developer Contact:** api@clearbooks.co.uk

## Rate Limits

- 5 requests per second sustained limit
- HTTP 429 returned when rate limited
- Retry using exponential backoff
- Limits may change without prior notice
- One active OAuth access token per user per application

## Plans

API access is included with the Small (£16/month), Medium (£34/month), and Large (£44/month) business plans. A 30-day free trial is available, and introductory pricing offers 50% off for the first 3 months.

## Resources

- Website: https://www.clearbooks.co.uk/
- Documentation: https://api-docs.clearbooks.co.uk/
- GitHub: https://github.com/clearbooks
- Status: https://status.clearbooks.co.uk/
- Blog: https://www.clearbooks.co.uk/blog/
- Pricing: https://www.clearbooks.co.uk/pricing/
- LinkedIn: https://www.linkedin.com/company/clear-books
- X (Twitter): https://twitter.com/ClearBooks
