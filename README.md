# bPanel

bPanel is a marching band management web app I built in partnership with the CSUS Marching Band. Built with jQuery and a mini MVC framework I developed in PHP.

As a self-educational exercise in web security, I also attempted to develop a secure user login system in PHP. Security features include hashed and salted passwords, session IDs with a message authentication code (MAC or tag) to detect tampered cookies, session tokens derived from a secret key, user agent, and IP address to help prevent session hijacking, and a CSRF token to prevent cross-site request forgeries. Session information is stored in a MySQL database instead of the file system to prevent snooping in shared hosting environments.

Features include:

- Member registration form that collects email, instrument type, and other profile information
- Admin panel to view member profiles
- Uniform finder tool to determine the best-fitting uniform from inventory based on their measurements
- Uniform inventory management, tracking checkouts/check-ins
- Printing receipts for checked-out items
- Bulk emailing of band members
- Printing member rosters
