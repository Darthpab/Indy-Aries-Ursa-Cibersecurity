# Indy-Aries-Ursa-Cibersecurity
Our main motivation behind this project is being able to study and analyze how we can make use of decentralized systems to create an architecture capable of sustaining Self-Sovereign identity and contemplate whether or not these systems are able to keep our information safe.

This TFM implements a self-sovereign identity use case. In particular, it implements the system of exchange of credentials between student, university and company, as shown in figure

![37](https://github.com/Darthpab/Indy-Aries-Ursa-Cibersecurity/assets/50524690/61546c81-3943-430e-825c-782423f0cd09)

Analyzing the core parts of the system independently, we can represent each generic core part in a specific role in our prototype and define the objectives each part needs to accomplish:

* The university plays the role of the issuer, defining the schema and issuing credentials using the aforementioned schema.
* The student plays the role of the holder, he will store the credentials the university issued and use them as they see fit, changing the presentation of the credential as he wants to keep private information safe.
* The company will act as a verifier, it will receive the credential the student presented and check its veracity.
* The credentials we will be using will be the certificates an university emits, such as degrees, masters and doctorates.
