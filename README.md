# Strapi Plugin - Raw Query

[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/creazy231/strapi-plugin-raw-query/graphs/commit-activity)
[![Maintaner](https://img.shields.io/badge/maintainer-creazy231-blue)](https://github.com/creazy231)
[![GitHub release](https://img.shields.io/github/release/creazy231/strapi-plugin-raw-query.svg)](https://github.com/creazy231/strapi-plugin-raw-query/releases/)
[![NPM release](https://img.shields.io/npm/v/strapi-plugin-raw-query)](https://www.npmjs.org/package/strapi-plugin-raw-query)
[![Github all releases](https://img.shields.io/npm/dt/strapi-plugin-raw-query)](https://GitHub.com/creazy231/strapi-plugin-raw-query/releases/)
[![GitHub forks](https://img.shields.io/github/forks/creazy231/strapi-plugin-raw-query.svg?style=social&label=Fork&maxAge=2592000)](https://GitHub.com/creazy231/strapi-plugin-raw-query/network/)
[![GitHub stars](https://img.shields.io/github/stars/creazy231/strapi-plugin-raw-query.svg?style=social&label=Star&maxAge=2592000)](https://GitHub.com/creazy231/strapi-plugin-raw-query/stargazers/)
[![GitHub watchers](https://img.shields.io/github/watchers/creazy231/strapi-plugin-raw-query.svg?style=social&label=Watch&maxAge=2592000)](https://GitHub.com/creazy231/strapi-plugin-raw-query/watchers/)

Raw Query allows you to send raw query strings to the database within [Strapi CMS](https://github.com/strapi/strapi) backend. That's it 🤷🏻‍♂️

<img src="https://github.com/haidong2099/strapi-plugin-raw-query-custom/blob/main/public/assets/preview.png" alt="Strapi Plugin - Raw Query" />


## ⏳ Installation

1.  Add an entry inside ```./package.json```
```json	
	"dependencies": {
	"strapi-plugin-raw-query-custom": "https://github.com/haidong2099/strapi-plugin-raw-query-custom.git"
	}
```

2.  Install  depedencies ```yarn install```

3.  Register plugin in ```./config/plugins.js```
	```js
	'raw-query': {
		enabled: true,
	},
	```
4.  yarn  ```build && yarn develop```

The **Raw Query** plugin should appear in the Plugins section of Strapi sidebar after you run app again.


# 🏚 Strapi v3 Support
For Strapi v3, you can install the plugin using the following command and continue with the installation:
```bash
yarn add strapi-plugin-raw-query@0.0.3

# or

npm i strapi-plugin-raw-query@0.0.3
```

## 🖐 Requirements

**Supported Strapi versions**:

- Strapi: >= 4.x.x


**Supported Node / NPM versions**:
- Node: >= 12.x.x <= 18.x.x
- NPM: >= 6.0.0


_We recommend always using the latest version of Strapi to start your new projects_.

## 🤝 Contributing

Feel free to fork and make a Pull Request to this plugin project. All the input is warmly welcome!

## ⭐️ Show your support

Give a star if this project helped you.

## 🔗 Links

- [NPM package](https://www.npmjs.com/package/strapi-plugin-raw-query)
- [GitHub repository](https://github.com/creazy231/strapi-plugin-raw-query)

## 📝 License

[MIT License](LICENSE.md) Copyright (c) 2022 [Tobias Thiele](https://tobias-thiele.de/).

[![ForTheBadge built-with-love](http://ForTheBadge.com/images/badges/built-with-love.svg)](https://GitHub.com/creazy231/)
