
# Kula Kula App
- Kula Kula is a user-friendly food delivery application designed to provide a seamless dining experience. With its intuitive interface built using React Native Expo, Kula Kula brings the finest local restaurants right to your fingertips. Whether you're craving a hearty meal or a quick snack, our app allows you to effortlessly explore a variety of restaurants in your vicinity and place food orders with just a few taps.


## Features

- Restaurant Exploration: Discover a diverse range of restaurants conveniently located in your area, making it easier than ever to satisfy your culinary cravings.
- Effortless Ordering: Enjoy a hassle-free ordering process that lets you browse menus, select your favorite dishes, and place orders with utmost simplicity.
- Sleek Design with Tailwind CSS: Our app boasts a sleek and modern design aesthetic, crafted using Tailwind CSS, enhancing both functionality and visual appeal.
- Seamless Backend with Sanity.io: Kula Kula utilizes the power of Sanity.io as its backend, ensuring a smooth and reliable connection between your device and the restaurants you love.

## Installation Steps

Clone the Kula Kula App repository from github:

```bash
  git clone https://github.com/your-username/kula-kula-app.git

```

Navigate to the kula-kula-app folder, which contains the Sanity project:

```bash
 cd kula-kula-app
  
```

Install Sanity CLI globally:

```bash
 npm install -g @sanity/cli
  
```

Initialize the Sanity project (follow the prompts to set up your project):

```bash
 sanity init
  
```
## Set Up React Native App

Navigate to the `client` folder, which contains the React Native app:

```bash
 cd ../client
  
```

Install dependencies:

```bash
 npm install

0r

 yarn install
```
## Configure Sanity API
In the `client` folder, open the .env file and add the following line:

```bash
 SANITY_API_KEY=your_sanity_api_key
  
```
Replace your_sanity_api_key with the actual API key from your Sanity project.

## Run the App
Start the Expo development server:

```bash
 yarn android

  or

 npm run android
```

Scan the QR code using the Expo Go app on your Android or iOS device, or run the app in a simulator.

Enjoy using Kula Kula App and bon appétit! 🍔🍕🥗
    

## Authors

- [Cliff Gor](https://github.com/cliffgor)