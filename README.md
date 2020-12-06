# Tricky Susan website (backend)

This is the original repo for a promotional website for the band Tricky Susan, of which I am a part.

Coded in JavaScript, Vue, HTML and CSS. Deployed in a semi complete state at trickysusan.herokuapp.com, where most of the development took place. 

When it was time to deploy for production, I realised my hosting package did not include Node.js code, so I had to remove it. I preserve it here for posterity, and in the hope that I eventually get round to reinstating it in the project. Specifically there is code here for:

* A Contact Form that sends an email to the band email account via the Sendgrid API.
* A password protected admin page, providing the ability to update the News database.
