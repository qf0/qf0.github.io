---
layout: post
title: "MFA for Amazon and Bank Accounts"
date: 2023-04-26
---

I recently noticed that Amazon now allows for consumers to enable TOTP MFA. For a while, I put off adding my phone number to force Amazon to send me email OTPs instead of SMS OTP, because of the fear of SIM swapping.
Email OTPs are not that great either, but since I have a strong password and Google's Advance Security, it's better than SMS OTP IMO. Amazon doesn't allow for adding a support phrase password like Charles Schwab does sadly.

Charles Schwab offers MFA via Symatec's VIP mobile application, but there's a GitHub repo to generate a TOTP key instead.
Chase only offers SMS MFA, but allows U2F MFA for Buisness accounts, and presumably for their high net worth clients/JP Morgan Private Clients. I talked to the Chase CISO, and he stated that they are working on Chase app auth pushes similar to Duo Mobile, but it's only available for certain people currently.
I have Google Fi and since I have Google's Advance Security, I feel a bit more confident against SIM swapping. However, the SMS could still be intercepted. Chase claims to offer support based password/phrase, but I haven't been asked for it whenever I called their support in the past multiple times. Charles Schwab always asks for my support phrase/password, though.
