<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [sip.js](./sip.js.md) &gt; [Body](./sip.js.body.md) &gt; [contentType](./sip.js.body.contenttype.md)

## Body.contentType property

The Content-Type header field indicates the media type of the message-body sent to the recipient. The Content-Type header field MUST be present if the body is not empty. If the body is empty, and a Content-Type header field is present, it indicates that the body of the specific type has zero length (for example, an empty audio file). https://tools.ietf.org/html/rfc3261\#section-20.15

<b>Signature:</b>

```typescript
contentType: string;
```
