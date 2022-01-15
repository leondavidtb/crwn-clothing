## CRWN Clothing 🎯

Clothing shop made using React & firebase with Stripe payments implemented.

## Features 🔥

✔️ Authentication with Google account <br />
✔️ Authentication with email and password <br />
✔️ Session storage and persistence <br />
✔️ Asynchronous events handling <br />
✔️ Stripe Payments <br />

## Technologies used 🛠️

**Design**: _Sass & Styled Components_<br />
**Authentication**: _Firebase auth_<br />
**Database**: _Firebase Firestore_<br />
**Libraries**: <br /> - **redux-logger**: console logging redux data flow <br /> - **redux**: state management <br /> - **redux-thunk**: handling asynchronous events <br /> - <del><strong>redux-saga</strong></del>: handling asynchronous events keeping actions pure <br /> - **reselect**: reusing redux selectors in a performant way <br /> - **redux-persist**: storing data in local storage <br />

## Usage 📋

<details open>
<summary>1. Server Setup</summary>

```bash
#1. clone this project
~ git clone https://github.com/leondavidtb/crwn-clothing.git
#2. cd into it
~ cd crwn-clothing
#3. install dependencies
~ yarn
#4. run app
~ yarn start
```

</details>

<details>
<summary>2. Firebase Setup</summary>

Remember to replace the `config` variable in your `firebase.utils.js` with your own config object from the firebase dashboard! Navigate to the project settings and scroll down to the config code. Copy the object in the code and replace the variable in your cloned code.

![alt text](https://i.ibb.co/6ywMkBf/Screen-Shot-2019-07-01-at-11-35-02-AM.png "image to firebase config")

</details>

<details>
<summary>3. Stripe Setup</summary>

## Publishable Key

Set the `publishableKey` variable in the `StripeButton.jsx` with your own publishable key from the stripe dashboard.

![alt text](https://i.ibb.co/djQTmVF/Screen-Shot-2019-07-01-at-2-18-50-AM.png "image to publishable key")

## Secret Key

**First of all** _You need first to get your secret key from_ [here](https://dashboard.stripe.com/test/apikeys) <br>
**Then**

```bash
# Rename example.env to .env
~ mv example.env .env
```

**Finally** _copy your secret key inside .env folder_

```
STRIPE_SECRET_KEY=YOUR_SECRET_KEY_GOES_HERE
```

</details>

## License 📄

This project is open-sourced under the [MIT license](https://opensource.org/licenses/MIT).
