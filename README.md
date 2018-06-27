# ng-proxy-config :shipit:
Proxy configuration ready to use with Angular CLI (ng serve), useful when API CORS is not configured to use in your development environment.

### How to use
- Download [proxy.config.json](https://github.com/micheldpcarlos/ng-proxy-config/blob/master/proxy.config.json)
- Configure "https://YOUR-DISABLED-CORS-API/" to your api adress 
- Place the file inside your project folder.

Now you can serve your project using the following command:
```
$ ng serve --proxy-config proxy.config.json
```
Your api will be reached by "/api" via proxy and you will no longer have CORS errors.

:heart:
