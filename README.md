# sta.radio
Custom URL shortener, currently deployed at https://sta-radio.herokuapp.com/.

To use setup locally:
- Extract and move items to a directory named `server`
- Install packages listed in `package.json`
- Ensure mongodb is running locally (can check by trying `mongo` in shell)
- Change constant on line 10 of `index.js` from `MONGODB_URI` to `MONGO_URI`
- Run `npm run dev`
