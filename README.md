# issue-and-fixes

- **Sometimes, Apostrophes and double quotes doesn't show up until we press another key**

  **Resolution** - Its because the keyboard settings are set to the dead key setting. So to resolve this:-

    1. Check your Keyboard and Language settings. It should not be US-International
    2. If it is US-International, change it to ENG-US.

    [Check this link for more info](https://superuser.com/questions/122625/apostrophes-and-double-quotes-dont-show-up-until-i-type-the-next-letter)

- **React Native - Getting "The development server returned response error code: 500" error**

  **Resolution** - There is bug in react-native 0.56. So, some dependencies need to be downgraded.

    1. Uninstall react-native - `npm uninstall react-native`
    1. Install react-native version 0.55.4 - `npm install --save reac-native@0.55.4`
    1. Uninstall babel-preset-react-native - `npm uninstall babel-preset-react-native`
    1. Install babel-preset-react-native version 4.0.0 - `npm install --save-dev babel-preset-react-native@4.0.0`
    1. `npm install babel-core@6.26.3 --save`
    1. `npm install babel-loader@7.1.5 --save`

