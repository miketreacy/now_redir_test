# TO REPRODUCE
## LOCAL TEST
this works for me
```bash
npm run build
now dev
curl http://localhost:3000/feedback
# should output this:
#Redirecting to https://docs.google.com/forms/d/e/1FAIpQLScxcXxFPoyuHPBXrRnTVK19zFRnpMXW5A_mLzhLaOekccxoOg/viewform (308)
```
## PROD TEST
this does not work for me
```bash
curl https://now-redir-test.now.sh/feedback
# should output this:
#Redirecting to https://docs.google.com/forms/d/e/1FAIpQLScxcXxFPoyuHPBXrRnTVK19zFRnpMXW5A_mLzhLaOekccxoOg/viewform (308)
```
