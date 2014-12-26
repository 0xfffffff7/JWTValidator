JWTValidator
============

JSON Web Token Validator for C#

* How to

Validation Method.  
 bool JWTValidator.Validation(string idToken, string jwksJsonString) 

* idToken parameter 
 JWT String

* jwksJsonString parameter 

 JWKURL Response 

 Example  
 https://www.googleapis.com/oauth2/v2/certs  
`
{
 "keys": [
  {
   "kty": "RSA",
   "alg": "RS256",
   "use": "sig",
   "kid": "0a150691dc0793440e70dba11824feb9911d648a",
   "n": "4uZjoVq3tUy4cmZ7fsnGt_lJ46OtW4fhb1DVupmd8Ig8EaWHsUMD5HXBGXvJIX3R9eSVUQ4TmxNl7Qf2umfqm_K61XTdR036WZfeceKcldE81G62u20ZnAkFZ07uz4n1xqFahD5wBhY-BO6RX8L9o-gKjNdRzPTW1VMR0xTrTgk=",
   "e": "AQAB"
  },
  {
   "kty": "RSA",
   "alg": "RS256",
   "use": "sig",
   "kid": "a5ad294f7a97316195ed7b25ef91fee80ac1e099",
   "n": "tNITfFAeA8QrEh3C-9p8xMPG39yAiPCOyAzv7uCK7j3vM2wQCvY1XBZ0Xm8WCSgM5DLWvpqeDLvAC7dqTtbw2ww04vE0K36gBmzCY5Rz3l0zQP5xGTFS2j6jRIsBaOv-9cWpA2HCCPtoz5K6Ixu0d2KHOsk7L0B2jSxJlKr8hYk=",
   "e": "AQAB"
  }
 ]
}
`

