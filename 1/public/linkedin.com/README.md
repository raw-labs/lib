# linkedin.com
# LinkedIn API mapping

Check API documentation at https://docs.microsoft.com/en-us/linkedin/marketing/getting-started

Needs registration to get OAuth credentials

## Organization follower count lookup
https://api.linkedin.com/v2/networkSizes/urn:li:organization:1234567?edgeType=CompanyFollowedByMember<p>
`retrieve_organization_follower_count(client_id: string, client_secret: string, token_url: string,organization: string)`<p>

## 