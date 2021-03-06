<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [sip.js](./sip.js.md) &gt; [UserAgentOptions](./sip.js.useragentoptions.md) &gt; [uri](./sip.js.useragentoptions.uri.md)

## UserAgentOptions.uri property

SIP Addresses-of-Record URI associated with the user agent.

<b>Signature:</b>

```typescript
uri?: URI;
```

## Remarks

This is a SIP address given to you by your provider. If the user agent registers, it is the address-of-record which the user agent registers a contact for. An address-of-record represents an identity of the user, generally a long-term identity, and it does not have a dependency on any device; users can move between devices or even be associated with multiple devices at one time while retaining the same address-of-record. A simple URI, generally of the form `sip:egdar@example.com`<!-- -->, is used for an address-of-record.

