# linkedin.com
# LinkedIn API mapping

Check API documentation at https://docs.microsoft.com/en-us/linkedin/marketing/getting-started

Needs registration to get OAuth credentials

## Organization follower count lookup
https://api.linkedin.com/v2/networkSizes/urn:li:organization:1234567?edgeType=CompanyFollowedByMember<p>
`retrieve_organization_follower_count(client_id: string, client_secret: string, token_url: string,organization: string)`<p>

## Statistics on organization's page
https://docs.microsoft.com/en-us/linkedin/marketing/integrations/community-management/organizations/page-statistics?tabs=http<p>
`page_statistics( auth_cred_name: string, organization: string, `timeIntervals.timeRange.start`: long null := null, `timeIntervals.timeRange.end`: long null := null,`timeIntervals.timeGranularityType`: string null := null)`