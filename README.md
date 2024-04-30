# Italian Messages for React-Admin

Italian messages for [react-admin](https://github.com/marmelab/react-admin), the frontend framework for building admin applications on top of REST/GraphQL services.

[![react-admin-demo](https://marmelab.com/react-admin/img/react-admin-demo-still.png)](https://vimeo.com/268958716)

## Installation

```sh
npm install --save ra-language-italian
```

## Usage

```js
import italianMessages from 'ra-language-italian';
import polyglotI18nProvider from 'ra-i18n-polyglot';

const messages = {
    'it': italianMessages,
};
const i18nProvider = polyglotI18nProvider(locale => messages[locale]);

<Admin locale="it" i18nProvider={i18nProvider}>
  ...
</Admin>
```

## License

This translation is licensed under the MIT License.
