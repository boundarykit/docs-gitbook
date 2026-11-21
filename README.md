---
cover: .gitbook/assets/images/cards/card-policies.svg
---

# BoundaryKit

Enforce tool permissions at dispatch and audit each decision.

{% hint style="info" %}
Set BKIT_KEY and BKIT_ORG for your test workspace.
{% endhint %}

{% content-ref url="quickstart.md" %}
[Quickstart](quickstart.md)
{% endcontent-ref %}

{% content-ref url="documentation/core-concepts.md" %}
[Policies](documentation/core-concepts.md)
{% endcontent-ref %}

{% content-ref url="api-reference.md" %}
[API](api-reference.md)
{% endcontent-ref %}

{% content-ref url="mcp.md" %}
[MCP](mcp.md)
{% endcontent-ref %}

{% content-ref url="bac.md" %}
[Bac](bac.md)
{% endcontent-ref %}

{% content-ref url="administration/security-compliance.md" %}
[Security](administration/security-compliance.md)
{% endcontent-ref %}

{% tabs %}
{% tab title="TypeScript" %}
```typescript
await fetch("https://api.boundarykit.com/v2/policies", {headers: {"X-API-Key": process.env.BKIT_KEY!, "X-Organization-Id": process.env.BKIT_ORG!}})
```
{% endtab %}
{% tab title="Python" %}
```python
import os, requests
requests.get("https://api.boundarykit.com/v2/policies", headers={"X-API-Key": os.environ["BKIT_KEY"], "X-Organization-Id": os.environ["BKIT_ORG"]}).raise_for_status()
```
{% endtab %}
{% tab title="curl" %}
```curl
curl https://api.boundarykit.com/v2/policies -H "X-API-Key: $BKIT_KEY" -H "X-Organization-Id: $BKIT_ORG"
```
{% endtab %}
{% endtabs %}

[7f4a9c2e8b1d0f3a6c5e](.gitbook/assets/downloads/7f4a9c2e8b1d0f3a6c5e.pdf)

[BoundaryKit Enterprise Architecture Guide](.gitbook/assets/downloads/BoundaryKit%20Enterprise%20Architecture%20Guide.pdf)
