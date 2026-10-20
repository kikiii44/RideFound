RideFound — Vehicle Marketplace Platform
A modern, responsive vehicle marketplace designed to simplify vehicle discovery and listing management.
RideFound is a web-based platform designed to help users explore vehicles through an intuitive browsing experience while allowing 
an administrator to manage vehicle listings from a centralized interface.
The project focuses on usability, structured data management, secure administration, and a responsive interface.

Key Features
Vehicle Catalogue: Browse available vehicles with images, descriptions, prices, and seller contact information.
Search & Filtering: Find vehicles more easily using search and filtering options.
Vehicle Details: View relevant information about each listing.
Responsive Interface: Designed to provide a convenient browsing experience across different screen sizes.
Bilingual Interface: Supports Arabic and English for a broader audience.
Admin Dashboard: Manage vehicle listings, including adding, editing, and removing vehicles.
Image Management: Upload vehicle photos with validation and file-size restrictions.


Security & Reliability
Security is an important part of the application's administrative workflow.
Admin Authentication: Administrative access is configured using environment variables.
Password Protection: Administrator passwords are stored as hashes rather than plaintext passwords.
Session Security: HTTP-only session cookies help prevent client-side JavaScript from reading session credentials.
Access Control: Administrative operations are intended to be restricted to authenticated administrators.
Upload Validation: Image uploads are subject to validation and size restrictions.
Rate Limiting: Helps reduce excessive requests to protected endpoints.


