<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [puppeteer](./puppeteer.md) &gt; [Protocol](./puppeteer.protocol.md) &gt; [Fetch](./puppeteer.protocol.fetch.md) &gt; [AuthChallengeResponse](./puppeteer.protocol.fetch.authchallengeresponse.md) &gt; [response](./puppeteer.protocol.fetch.authchallengeresponse.response.md)

## Protocol.Fetch.AuthChallengeResponse.response property

The decision on what to do in response to the authorization challenge. Default means deferring to the default behavior of the net stack, which will likely either the Cancel authentication or display a popup dialog box. (AuthChallengeResponseResponse enum)

<b>Signature:</b>

```typescript
response: ('Default' | 'CancelAuth' | 'ProvideCredentials');
```
