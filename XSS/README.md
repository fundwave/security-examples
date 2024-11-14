# Best Practices to prevent XSS attacks

    - Use Output Encoding: Apply context-sensitive output encoding (HTML,JavaScript, and URL encoding) before displaying data in web pages. Prevents scripts from executing within the browser

    - Validate Input: Perform input validation for all untrusted data and allow only specific characters or patterns to prevent the injection of malicious scripts.

    - Content Security Policy (CSP): Implement a strict Content Security Policy to prevent JavaScript from loading from unauthorized domains.

    - Escaping Data: Escape data properly before inserting it into HTML attributes, URLs, or JavaScript

    - Use Trusted Libraries: Use well-established libraries for encoding, like OWASP Java Encoder or Microsoft AntiXSS, to ensure consistent and safe encoding.
