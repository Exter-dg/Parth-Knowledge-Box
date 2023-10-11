- ==Access-Control-Allow-Crendentials== must be set to <u><b>true</b></u> in response when sending cookies.
- ==Server== sends this header in response to the preflight request.
- This header is part of the [[CORS]].
- Refer [MDN - Access-Control-Allow-Credentials](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/Access-Control-Allow-Credentials)

> [!info] Cookies of one domain CANNOT be access by other domain

> [!example]+ What happens when two separate servers set cookies, do both of them receive each others' cookies?
> 
> TBC

## Express + Fetch

- Fetch Request (credentials must be set to include). Refer [MDN - Fetch with Credentials](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API/Using_Fetch#sending_a_request_with_credentials_included)
```js
fetch("http://127.0.0.1:5000/", {
	credentials: "include"
})
```

- Express Server (Must return the Access-Control-Allow-Credentials)
```js
app.use(cors({
	origin: "http://127.0.0.1:5500",
	credentials: true
}));
```