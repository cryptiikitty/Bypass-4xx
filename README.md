# Bypass-4xx

# Description
Bypass 4xx codes

## Usage
```bash
python3 4xx.py -u http://example.com/test/forbidden.html
```

### Use custom cookie
```bash
--cookies "cookie1=blah"
-c "cookie1=blah; cookie2=blah"
```

### Use proxy
```bash
--proxy http://localhost:8080
```

### Hide responses
```bash
-hc 403,404,400  # Hide response codes
-hl 638  # Hide response lengths of 638
```

