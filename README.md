# Potato Disease Classification

## Setup for Python:

1. Install Python ([Setup instructions](https://wiki.python.org/moin/BeginnersGuide))

2. Install Python packages

```
pip3 install -r training/requirements.txt
pip3 install -r api/requirements.txt
```

3. Install Tensorflow Serving ([Setup instructions](https://www.tensorflow.org/tfx/serving/setup))

## Setup for ReactJS

1. Install Nodejs ([Setup instructions](https://nodejs.org/en/download/package-manager/))
2. Install NPM ([Setup instructions](https://www.npmjs.com/get-npm))
3. Install dependencies

```bash
cd frontend
npm install --from-lock-json
npm audit fix
```

4. Copy `.env.example` as `.env`.

5. Change API url in `.env`.

## Setup for React-Native app

1. Go to the [React Native environment setup](https://reactnative.dev/docs/environment-setup), then select `React Native CLI Quickstart` tab.  

2. Install dependencies

```bash
cd mobile-app
yarn install
```

  - 2.1 Only for mac users
```bash
cd ios && pod install && cd ../
```

3. Copy `.env.example` as `.env`.

4. Change API url in `.env`.

