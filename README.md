### URL shortening API service 

As  a user, I want to share a long URL as a short URL so it's easier to copy/paste in emails.
As a user, sometimes I will want to customize the short URL so that I can recall what URL it is referencing or give it a cool name
As a user, I will want to see a report of my short URLs, when I created it, and how many times it was clicked.
Here are its specifications:
A user can submit a URL /submit without a shortcode proposed, and receive automatically allocated unique shortcode in response.
A user can submit a URL with the desired shortcode and will receive the chosen shortcode if it is available.
A user can access a /<shortcode> endpoint and be redirected to the URL associated with that shortcode, if it exists.
All shortcodes can contain digits, upper case letters, and lowercase letters. It is case sensitive.
Automatically allocated shortcodes are exactly 6 characters long.
User submitted shortcodes must be at least 4 characters long.
A user can access a /<shortcode>/stats endpoint in order to see when the shortcode was registered, when it was last accessed, and how many times it was accessed.


<!--
**jgachukia/jgachukia** is a āØ _special_ āØ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- š­ Iām currently working on ...
- š± Iām currently learning ...
- šÆ Iām looking to collaborate on ...
- š¤ Iām looking for help with ...
- š¬ Ask me about ...
- š« How to reach me: ...
- š Pronouns: ...
- ā” Fun fact: ...
-->
