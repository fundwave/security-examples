# Best Practices to prevent XSS attacks

    - JSON Prefixing: Prefix JSON responses with non-executable code, such as while(1); or )]}',, to prevent JSON responses from being parsed by scripts in an unintended context.

    - Use X-Content-Type-Options Header: Set the X-Content-Type-Options: nosniff header to prevent browsers from interpreting responses as JavaScript.

    - Avoid Sensitive Data in JavaScript Responses: Keep sensitive data out of any JavaScript-based responses to avoid accidental exposure through XSSI.

    - Limit Cross-Origin Access: Use CORS to control which domains can access your APIs and data, ensuring only trusted origins can fetch data
