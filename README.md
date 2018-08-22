# Email Validation
Regular Expression to validate email. 

```javascript
function ValidateEmail(mail){
  if (/^\w+([\.-]?\w+)*@\w+([\.-]?\w+)*(\.\w{2,3})+$/.test(mail))
    return true
  else
    return false
} 
```
