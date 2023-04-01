---
description: Update the backend url to connect.
---

# 📝 Editing environment.ts

## Edit file

This is the [configuration file](https://github.com/arunjayarajan/Group2\_Nausicaa/blob/main/Code/Nausicaa.Green.Initiative.UI/global-green-initiative/src/environments/environment.ts) of the application. The below code block shows the different config settings in it:

```json
// Some code
export const environment = {
  production: false,
  apiUrl: 'https://backend.techminal.com/',

  cognito:{
    userPoolId:"us-east-1_SFE478EFSs",
    userPoolWebClientId:"4c64XXXXXXjkevXXXqr7aXXXXXX"
  }
};
```
