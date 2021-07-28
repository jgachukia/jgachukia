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
**jgachukia/jgachukia** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
