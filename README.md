What this GPT does

PodcastSearchGPT helps you discover podcasts and podcast episodes by querying public podcast data from PodcastIndex.org through an Azure Function proxy.

Data you provide

When you use this GPT, you may provide:

Search queries (topics, podcast titles, names of people)

Optional filters (language, categories)

Podcast identifiers (feed ID, feed URL, GUID) if you paste them

How your data is used

Your input is used only to perform the requested podcast search and return results.
Requests are sent to:

An Azure proxy (the GPT owner’s service)

PodcastIndex.org (the upstream data provider)

Data sharing

Your query parameters are forwarded to PodcastIndex to fulfill your request.
No additional third parties are used for analytics, advertising, or tracking by this GPT.

Data storage and logging

This GPT does not intentionally store your personal data.

The Azure proxy may temporarily log basic technical information needed to operate and debug the service (for example: timestamp, endpoint called, and HTTP status code).

The proxy should not store full conversation transcripts unless explicitly enabled by the service owner.

If the service owner enables additional logging in the future, this policy should be updated accordingly.

Authentication / secrets

The Azure proxy is protected with an API key (sent as an HTTP header).
This key is used only to authorize the proxy call and is not visible to users.

Personal data

This GPT is designed for podcast discovery and does not request sensitive personal data (such as passwords, payment details, government IDs, or health data).
If you include personal data in your search query, it will be sent to PodcastIndex as part of the request.

User controls

You can avoid sharing personal information by using generic queries (e.g., topics instead of names).

You can stop using the GPT at any time.

Security

Reasonable measures are used to protect the proxy endpoint (API key authorization and allowlisted endpoints). However, no system can guarantee absolute security.

Changes to this policy

This policy may be updated if the GPT’s functionality changes (for example, if logging, storage, or new providers are added). The “Last updated” date will be revised.
