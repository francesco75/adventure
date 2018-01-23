Todo:

- [medium]fix the vote counter on the ticket detail page to reflect the correct number of votes (see notes) Done
- [easy] replace the "about" and "contact" links in the header with a "login"/"logout" button Done
- [difficult/critical] **deploy the project to Heroku**
- [easy/critical] **create the readme/documentation** Done

---

Potential fixes:

- [difficult] when you create a new vote on a feature, it should NOT be marked "complete". When you make the payment, paypal should
  "callback" to the app so that we can mark the payment as complete. This prevents users creating a new payment but not actually
   following through with the payment. You need to use the IPN system to call your application when the payment has been complete
- [medium] if the above is issue is fixed, then you can also filter out all incomplete payments from the data or listings

---

Potential features:

- [difficult] allow users to add comments to the ticket detail page (see notes) done
- [easy] add a status to the ticket Done