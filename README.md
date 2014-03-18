apex-wsfederation
=================

ws-federation implementation in Apex

To get started:

1. Create the Controllers found in the Apex directory
2. Create the visualforce pages in the Pages directory
3. Adjust CRUD and FLS 
4. Generate encoded keys / certs, follow the cryptocommands in the Keys directory.   When asked for a password, use something consistent for each answer.   Run the 5 commands and you'll end up with key.pem, which is your encodedPrivateKey ( protect this!! ), wsfed.crt which is your public certificate, and your modulus / exponent
5. Go to /apex/WSFederationManagement and create a Realm

Now, you can authorize access to the WSFederation page via Profiles or Permsets and it will speak WSFed Passive profile

Consult this wiki for example intructions with Sharepoint: 