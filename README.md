Heroku Buildpack for AWS X-Ray
===

Installation
---

Add it to your app:

```
heroku buildpacks:add https://github.com/urbandictionary/heroku-buildpack-xray
```

Configuration
---

The AWS X-Ray daemon (https://github.com/aws/aws-xray-daemon/tree/master/daemon) will pick up environment variables like `AWS_ACCESS_KEY_ID`, `AWS_SECRET_ACCESS_KEY` and `AWS_REGION` to configure itself.
