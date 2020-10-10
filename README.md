# python-snippets






### make a dict double qouted string and remove spaces inbetween
```python
    def get_data(data):
        '''
        remove all whitespace characters (space, tab, newline, and so on)
        and return object
        return format '{"event":"getportinfo"}' => without any spaces in sigle qoutes key value in double qoutes
        '''
        sdata = str(json.dumps(data))
        rdata = ''.join(sdata.split())
        # print("data after conversion",rdata)
        return rdata
```
