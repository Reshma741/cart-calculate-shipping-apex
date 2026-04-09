Build a custom Shipping Cost Calculator in Salesforce using Apex and integrate it into the checkout flow. This extension allows users to select from multiple shipping methods, applying different pricing logic per method.
Supported Shipping Methods
o	Standard Shipping
	Lower cost (e.g., 0)
	Delivery in ~3–5 business days
o	Express Shipping
	Higher cost (e.g., 500)
	Delivery in ~1 business day

2.	Dynamically calculates delivery dates
o	Skips weekends
o	Adds estimated delivery date in method label:
	Example:
“Standard Shipping — Est. Delivery: Apr 10, 2026”
