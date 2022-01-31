# exchangeratesapi.io
# Exchange rates

Based on https://exchangeratesapi.io/
which provides up to 1.000 free calls per month

Requires a registeration to get your own API key

Check documentation at https://exchangeratesapi.io/documentation/

Implemented Endpoints:

`convert(access_key: string, `from`: string, `to`: string, `amount`: double, `date`: string null := null)`<p>
`historical(access_key: string, `date`:string, base: string null:=null, symbols: string null:=null)`<p>
`latest(access_key: string, base: string null:=null, symbols: string null:=null)`<p>

