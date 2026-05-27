# Code With Lasa — React reCAPTCHA v2

## Video Tutorial
Paste YouTube Link Here

## GitHub Repository
Paste GitHub Repo Link Here

## Install
```bash
npm install react-google-recaptcha
```

## Import
```javascript
import ReCAPTCHA from "react-google-recaptcha";
```

## State
```javascript
const [captchaValue, setCaptchaValue] = useState(null);
```

## Add Component
```jsx
<ReCAPTCHA
  sitekey="PASTE_YOUR_SITE_KEY"
  onChange={(value) => setCaptchaValue(value)}
/>
```

## Validate
```javascript
if (!captchaValue) {
  alert("Please verify captcha");
  return;
}
```

Subscribe to Code With Lasa and follow GitHub.
