---
description: "Automatically generated file. DO NOT MODIFY"
---

```javascript

const options = {
	authProvider,
};

const client = Client.init(options);

const onenoteOperation = {
  groupId: 'groupId-value',
  renameAs: 'renameAs-value'
};

await client.api('/me/onenote/notebooks/{id}/copyNotebook')
	.version('beta')
	.post(onenoteOperation);

```