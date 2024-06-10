# authorization-server-demo

**Iniciar el authorization-server**

Obtención del token : utilizando el client_id "user" y password "secret"

```
$ curl --location --request POST '127.0.0.1:8080/oauth2/token' --header 'Content-Type: application/x-www-form-urlencoded' --header 'Authorization: Basic Y2xpZW50OnNlY3JldA==' --data-urlencode 'grant_type=client_credentials'
```
```json
{
  "access_token":"eyJraWQiOiJmOTY0MThhMi0xODM2LTRjMzUtOWQ2Ny1kZGY4ZTkyYWQ3MWQiLCJhbGciOiJSUzI1NiJ9.eyJzdWIiOiJjbGllbnQiLCJhdWQiOiJjbGllbnQiLCJuYmYiOjE3MTgwMzQxOTUsImlzcyI6Imh0dHA6Ly8xMjcuMC4wLjE6ODA4MCIsImV4cCI6MTcxODAzNDQ5NSwiaWF0IjoxNzE4MDM0MTk1fQ.GqS7rWnEuEfGiRwyP8v_Dl69JRUI74RFf7wNspph8QNFs17EyG3u-GzK7PAIXlf_ptw6teA0SRhqTHA93NNLTirCiSDECVnAiAtSn3xYVDSD_wphkAEcJJ5qPbC6MLstv3VRrSzWEZoUpfnYAFflMm-y_LAhvrE038LaMVL4_Y8XpO0GdgAIVs1YWRCFojRBM83WgM5ADPJtNmuckOdTIEC6vvHd29F5aqIcnlZY3grP2qyhqT0KNeExHpSBYXCbYXTTXyGAtNkT1x7QX85WRoFefYqJQXMM-SpiK2hBDbC5ELTmiQQze_QoijjFLQnl71lXlUi3T7O5aPozsrkqHw",
  "token_type":"Bearer",
  "expires_in":299
}
```



