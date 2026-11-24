MAHIN AZAM — PERSONAL WEBSITE
================================

Chosen domain: https://mahinazam.com/
Hosting recommendation: GitHub Pages (free for public repositories)
Threads: intentionally omitted until the exact Threads profile URL is known.

PACKAGE CONTENTS
----------------
- index.html   The personal website, with canonical URL and social-profile structured data.
- CNAME       Custom domain for GitHub Pages.
- robots.txt  Allows public crawling and points crawlers to the sitemap.
- sitemap.xml Sitemap containing the homepage.

IMPORTANT COST NOTE
-------------------
GitHub Pages hosting can be free for a public repository on GitHub Free. The
custom .com domain is a separate registration and renewal cost. This package
does not register, purchase, or verify availability of mahinazam.com.

PUBLISH WITH GITHUB PAGES
-------------------------
1. Register mahinazam.com with a domain registrar if you do not already own it.
   Keep access to the registrar's DNS management panel.
2. Create or sign in to a GitHub account at https://github.com/.
3. Create a NEW PUBLIC repository, for example: mahin-personal-site.
4. Upload all four files in this package to the repository's ROOT folder:
   index.html, CNAME, robots.txt, and sitemap.xml.
5. In the repository, open Settings > Pages.
6. Under Build and deployment, choose "Deploy from a branch".
7. Select branch "main" and folder "/ (root)", then Save.
8. In the Custom domain field, enter mahinazam.com and save. If GitHub asks
   you to confirm/update the CNAME file, keep its content exactly:
   mahinazam.com

DNS RECORDS AT YOUR DOMAIN REGISTRAR
------------------------------------
Add these records in the DNS panel for mahinazam.com:

Type: A       Host/Name: @       Value: 185.199.108.153
Type: A       Host/Name: @       Value: 185.199.109.153
Type: A       Host/Name: @       Value: 185.199.110.153
Type: A       Host/Name: @       Value: 185.199.111.153
Type: CNAME   Host/Name: www     Value: YOUR-GITHUB-USERNAME.github.io

Replace YOUR-GITHUB-USERNAME with your actual GitHub username. If the DNS
provider automatically appends the domain name, enter only the host/target
portion it asks for. Remove conflicting old A/AAAA records for @ and any
conflicting www record before saving. Do not delete email-related MX/TXT
records unless you know what they do.

GitHub recommends configuring both the apex domain and www variant. Once DNS
has propagated, return to repository Settings > Pages and turn on "Enforce
HTTPS" when the option becomes available. DNS propagation and certificate
issuance can take time; this package cannot make them happen instantly.

GOOGLE SEARCH DISCOVERY
-----------------------
1. After https://mahinazam.com/ loads securely, open:
   https://search.google.com/search-console/about
2. Add a Domain property for mahinazam.com.
3. Google will show a DNS TXT verification value. Copy that exact value into
   your registrar's DNS panel as a TXT record, then verify in Search Console.
   Do not share the verification token publicly.
4. In Search Console, open Sitemaps and submit:
   https://mahinazam.com/sitemap.xml
5. Open URL Inspection, enter https://mahinazam.com/, test the live URL, then
   select Request indexing if available.
6. Add https://mahinazam.com/ to the website/links field on your social
   profiles. Make sure your public profiles link back to each other where
   the platform permits.

Google may take days or weeks to crawl a new website. A sitemap or indexing
request is only a discovery hint; neither guarantees indexing or ranking.

THREADS
-------
Threads has not been added because no username/profile URL was supplied.
When you have it, add its exact URL as a social link in index.html and as one
more entry in the Person.sameAs array inside the JSON-LD structured data.

PRIVACY
-------
This site contains only the social profiles you supplied. Do not add your
home address, phone number, private email, school details, daily routine, or
other sensitive information just to improve search visibility.

OFFICIAL GUIDES
---------------
GitHub Pages custom domains:
https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site
GitHub Pages publishing source:
https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
Google sitemap guidance:
https://developers.google.com/search/docs/crawling-indexing/sitemaps/build-sitemap
Google recrawl guidance:
https://developers.google.com/search/docs/crawling-indexing/ask-google-to-recrawl
