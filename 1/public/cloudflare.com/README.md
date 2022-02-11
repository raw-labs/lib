## cloudflare Workers & KV mapping


Based on https://api.cloudflare.com/  
Currently V4  
With this mapping you can put and get KV, get a list of KV based on a prefix and update a worker.  
<br>
Implemented Endpoints:
<br>
Writing a KV  
https://api.cloudflare.com/#workers-kv-namespace-write-key-value-pair  
`putvalue(x_auth_key: string, x_auth_email: string, account_id: string, namespace: string, key: string, value: string, expiration: int null := null,expiration_ttl: int null := null )`  
<br>
Reading a KV  
https://api.cloudflare.com/#workers-kv-namespace-read-key-value-pair  
returns the string containing the value if existing  
`getvalue( x_auth_key: string, x_auth_email: string, account_id: string, namespace: string, key: string)` 
<br><br>
https://api.cloudflare.com/#workers-kv-namespace-list-a-namespace-s-keys  
Returns a collection of strings containing all key values from a Namespace up to 1.000 by default  
`list_namespace_keys(x_auth_key: string, x_auth_email: string, account_id: string, namespace: string, `limit`: int null := null, cursor: string null := null, prefix: string null := null)` 
