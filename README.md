# Income-Tax-Calculator

# The task:
To build an input form/calculator for checking gross and net income. Imagine you need to provide information to users about their clients income, before and after tax. One screen can be used for data entry and the second screen a table with results. You don't need to worry about using an exact tax % figure, you can choose how much tax goes for net income calculation.

To create a minimal SPA from scratch, using specified frameworks. Using core frameworks for just essential definitions/resets should be fine, but the idea is to see if the candidate can work with UI controls, customise the styles, follow the predefined guidelines and use the defined frameworks.

# Install Node and intialize an npm directory.

install node/npm.
create a folder called src in your project root.
run npm init -y in the root of your project (one level above your src folder).

# Install and configure prettier

run npm install -D prettier to install prettier (-D marks it as a dev dependency).
create a file in the root of your project called .prettierrc.
inside .prettierrc place an empty object {}. (this will tell prettier we just want to use the default setting)
inside your package.json delete the test script and create a script called
"format": "prettier --write \"src/**/*.{js,jsx}\""
- if you're using VS code you can skip this step if you want we will configure VS Code to auto format using prettier next.
install the prettier code formatter extention for VS Code.
go to your vs code settings search "format on save" and make sure the checkbox is checked.
while in settings search "prettier config" and check the box that enabales "require a prettier configuration file to format. (this will make sure prettier doesn't run in projects where you arn't using it).

# Install and Configure ESLint

run npm install -D eslint@7.18.0 eslint-config-prettier@8.1.0
create a file next to .prettierrc called .eslintrc.json. (this will be the config file for eslint).
enter the following in your .eslintrc.json
