# Email Validation
Regular Expression to validate email. Can be used with any language. 

```javascript
function ValidateEmail(mail){
  if (/^\w+([\.-]?\w+)*@\w+([\.-]?\w+)*(\.\w{2,3})+$/.test(mail))
    return true
  else
    return false
} 
```
