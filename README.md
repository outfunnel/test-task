# Test Task for Outfunnel Software Engineer candidate

User has contacts in Pipedrive and Mailchimp and we want to know the difference between the two sets.
Which contacts are present in a Mailchimp list and not in Pipedrive and which contacts are present in Pipedrive and not in a particular Mailchimp list?

1. Create a trial account in Pipedrive and add 10-20 contacts
2. Create a trial account in Mailchimp, create a list, and add 10-20 contacts (some of them different from Pipedrive)
3. Create a service with REST API endpoint which returns:
1. List of contacts in Mailchimp list which are not in Pipedrive
2. List of contacts in Pipedrive which are not in Mailchimp list
4. Bonus
1. Think about the extensibility, how can we support other CRMs besides Pipedrive (Capsule, for example) and other marketing tools besides Mailchimp (GetResponse, for example)

## Additional comments
Mailchimp and Pipedrive APIs can be easily accessed with their API keys. The service should be testable by inserting our own API keys and Mailchimp list ID.
