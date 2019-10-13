# A small React and Redux application to show logged in or logged out users

### Using React with Redux (ducks pattern)

> https://react-redux.js.org/

> https://github.com/erikras/ducks-modular-redux

### Using parcel to bundle application

> https://parceljs.org/recipes.html


```bash
# Install dependencies
npm install

# Run locally
npm run start
```

#### contains the store using createStore + redux devtools
> src/store/index.js

#### contains redux ducks pattern - actions, reducer, action creator
> src/store/ducks/session.js

#### contains conditional (ternary) login status using useSelector redux hook to plug into redux store
> src/components/Root/LoginStatus/LoginStatus.js

#### contains useDispatch on buttons to dipatch actions from above
> src/components/Root/Actions/Actions.js