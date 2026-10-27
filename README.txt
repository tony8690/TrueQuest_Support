TrueQuest public website
======================

Three static pages, ready to upload to an HTTPS web host:

  index.html        Marketing / app information
  support.html      Support FAQs and developer contact
  privacy.html      Privacy policy and privacy choices
  assets/           Shared styles, icon and real app screenshots

Developer: Tony Ashton
Support and privacy contact: tony-dev86@outlook.com

No build step, backend, JavaScript, external fonts, analytics or cookies.
The site works from local files as well as a web host. Keep the files and
assets folder together. All internal URLs are relative, so hosting under
a subfolder also works.

PREVIEW

Open index.html directly, or from the repository root run:

  python3 -m http.server 8765 --bind 127.0.0.1 --directory website

Then visit http://127.0.0.1:8765

PUBLISHING

Upload index.html, support.html, privacy.html and the complete assets/
folder to your chosen host. No domain or host has been assumed, and
these files have not been published.

Once the site is hosted, use these paths in App Store Connect:

  Marketing URL:             <your site base URL>/index.html
  Support URL:               <your site base URL>/support.html
  Privacy Policy URL:        <your site base URL>/privacy.html
  User Privacy Choices URL:  <your site base URL>/privacy.html#your-choices

Replace <your site base URL> with the actual HTTPS location, including
any subfolder. It is an instruction here, not a placeholder in the pages.

When you have the actual App Store product URL, a download link can be
added to index.html. The current page uses working section links rather
than inventing an App Store URL or implying the app is already available.

CONTENT MAINTENANCE

Privacy content reflects the source implementation on 27 October 2026.
Keep it aligned with the shipped app and your App Store privacy answers.
Update website privacy information if your chosen host adds tracking or
has additional relevant data practices. Support enquiries are delivered
to your email; there is no online ticketing system or data-request form.

Screenshots are resized versions of the real app release captures.
No production app code, signing or CloudKit configuration is changed.

REFERENCE SOURCES

Apple App Store Connect URL fields:
https://developer.apple.com/help/app-store-connect/reference/app-information/platform-version-information/

Apple privacy policy requirements:
https://developer.apple.com/help/app-store-connect/reference/app-information/app-privacy/

ICO privacy notice guidance:
https://ico.org.uk/for-organisations/advice-for-small-organisations/privacy-notices-and-cookies/how-to-write-a-privacy-notice-and-what-goes-in-it

Apple refund guidance:
https://support.apple.com/en-gb/118223
