## WA clone
**User discovery** :  whenever user logs in it will be shown in the left chat screen -> all the users will be visible 

### Routes
* Login -> `/login` 
* Protected Route  Home -> `/`  & if not loggedIN-> redirect to login 
* Chat  -> /uniqueId
* 404 -> if not the above url -> take the user to 404 page not found

### Views : these are the screens / views visible to user at a given point of time 
* login screen
* Home Page 
* 404 Page
* Profile
* Chat view




## Firebase deployemnt 
* Enable hosting by going to your firebase console's project
* go to the place where you run the react file
```bash
npm install -g firebase-tools
npm run build
```

* if deploying for first time

```bash
firebase login
```
* always
```bash
firebase init 
```
from the options 
- hosting ->
        -  optional github action : no
        - public dir : dist
        - rewrites -> no ,
        - overwrite -> no
        - single page aplication : yes

```bash
firebase deploy
```
