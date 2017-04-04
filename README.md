# api documentation for  [react-intl (v2.2.3)](https://github.com/yahoo/react-intl)  [![npm package](https://img.shields.io/npm/v/npmdoc-react-intl.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-react-intl) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-react-intl.svg)](https://travis-ci.org/npmdoc/node-npmdoc-react-intl)
#### Internationalize React apps. This library provides React components and an API to format dates, numbers, and strings, including pluralization and handling translations.

[![NPM](https://nodei.co/npm/react-intl.png?downloads=true)](https://www.npmjs.com/package/react-intl)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-intl/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-react-intl_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-intl/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-react-intl/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-react-intl/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Eric Ferraiuolo",
        "email": "edf@ericf.me"
    },
    "browser": {
        "./locale-data/index": false,
        "./locale-data/index.js": false
    },
    "browserify-shim": {
        "react": "global:React"
    },
    "bugs": {
        "url": "https://github.com/yahoo/react-intl/issues"
    },
    "contributors": [
        {
            "name": "Caridy Patino",
            "email": "caridy@gmail.com"
        }
    ],
    "dependencies": {
        "intl-format-cache": "^2.0.5",
        "intl-messageformat": "^1.3.0",
        "intl-relativeformat": "^1.3.0",
        "invariant": "^2.1.1"
    },
    "description": "Internationalize React apps. This library provides React components and an API to format dates, numbers, and strings, including pluralization and handling translations.",
    "devDependencies": {
        "babel-cli": "^6.2.0",
        "babel-eslint": "^7.1.1",
        "babel-jest": "^18.0.0",
        "babel-plugin-external-helpers": "^6.18.0",
        "babel-plugin-react-intl": "^2.0.0",
        "babel-plugin-transform-class-properties": "^6.11.5",
        "babel-plugin-transform-es2015-modules-commonjs": "^6.18.0",
        "babel-plugin-transform-es3-member-expression-literals": "^6.3.13",
        "babel-plugin-transform-es3-property-literals": "^6.3.13",
        "babel-plugin-transform-object-rest-spread": "^6.1.18",
        "babel-plugin-transform-react-remove-prop-types": "^0.2.10",
        "babel-preset-es2015": "^6.1.18",
        "babel-preset-react": "^6.1.18",
        "babelify": "^7.2.0",
        "benchmark": "^2.1.0",
        "browserify": "^13.0.0",
        "browserify-shim": "^3.8.11",
        "cross-env": "^3.1.3",
        "eslint": "^3.10.2",
        "eslint-plugin-react": "^6.2.0",
        "expect": "^1.9.0",
        "expect-jsx": "^3.0.0",
        "express": "^4.13.3",
        "formatjs-extract-cldr-data": "^2.0.0",
        "glob": "^7.0.0",
        "intl": "^1.2.1",
        "intl-messageformat-parser": "^1.2.0",
        "jest": "^18.0.0",
        "mkdirp": "^0.5.1",
        "react": "^15.0.0",
        "react-addons-test-utils": "^15.0.0",
        "react-dom": "^15.0.0",
        "rimraf": "^2.4.2",
        "rollup": "^0.41.4",
        "rollup-plugin-babel": "^2.3.9",
        "rollup-plugin-commonjs": "^7.0.0",
        "rollup-plugin-memory": "^2.0.0",
        "rollup-plugin-node-resolve": "^2.0.0",
        "rollup-plugin-replace": "^1.1.0",
        "rollup-plugin-uglify": "^1.0.0",
        "serialize-javascript": "^1.1.1",
        "superagent": "^3.0.0",
        "watchify": "^3.7.0"
    },
    "directories": {},
    "dist": {
        "shasum": "8eebb03cddc38b337ed22fab78037ab53a594270",
        "tarball": "https://registry.npmjs.org/react-intl/-/react-intl-2.2.3.tgz"
    },
    "gitHead": "cc9ecff1405e8bc3149a829da776b061ecb08300",
    "homepage": "https://github.com/yahoo/react-intl",
    "jest": {
        "testRegex": "/test/(unit|functional)/.*\\.js",
        "testPathIgnorePatterns": [
            "/test/functional/support/"
        ],
        "collectCoverageFrom": [
            "src/**/*.js",
            "!src/en.js"
        ],
        "coverageReporters": [
            "lcov",
            "text",
            "text-summary",
            "html"
        ],
        "coverageThreshold": {
            "global": {
                "branches": 85,
                "functions": 100,
                "lines": 95,
                "statements": 95
            }
        }
    },
    "jsnext:main": "./lib/index.es.js",
    "keywords": [
        "intl",
        "i18n",
        "internationalization",
        "locale",
        "localization",
        "globalization",
        "react",
        "reactjs",
        "format",
        "formatting",
        "translate",
        "translation"
    ],
    "license": "BSD-3-Clause",
    "main": "./lib/index.js",
    "maintainers": [
        {
            "name": "caridy",
            "email": "caridy@gmail.com"
        },
        {
            "name": "juandopazo",
            "email": "dopazo.juan@gmail.com"
        },
        {
            "name": "ericf",
            "email": "eferraiuolo@gmail.com"
        },
        {
            "name": "clarle",
            "email": "cleung0@gmail.com"
        }
    ],
    "module": "./lib/index.es.js",
    "name": "react-intl",
    "optionalDependencies": {},
    "peerDependencies": {
        "react": "^0.14.0 || ^15.0.0-0"
    },
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/yahoo/react-intl.git"
    },
    "scripts": {
        "build": "npm run build:data && npm run build:lib && npm run build:dist",
        "build:data": "babel-node scripts/build-data",
        "build:dist": "npm run build:dist:dev && npm run build:dist:prod",
        "build:dist:dev": "cross-env NODE_ENV=development rollup -c rollup.config.dist.js",
        "build:dist:prod": "cross-env NODE_ENV=production rollup -c rollup.config.dist.js",
        "build:lib": "rollup -c rollup.config.lib.js",
        "clean": "rimraf src/en.js coverage/ dist/ lib/ locale-data/",
        "examples:install": "babel-node scripts/examples npm install",
        "examples:link": "npm link && babel-node scripts/examples npm link react-intl",
        "lint": "eslint .",
        "lint:fix": "eslint . --fix",
        "prepublish": "npm run clean && npm run build",
        "preversion": "npm run clean && npm run build && npm run test:all",
        "react:14": "npm run react:clean && npm i react@^0.14 react-dom@^0.14 react-addons-test-utils@^0.14",
        "react:15": "npm run react:clean && npm i react@^15 react-dom@^15 react-addons-test-utils@^15",
        "react:clean": "rimraf node_modules/{react,react-dom,react-addons-test-utils}",
        "test": "jest --coverage --verbose",
        "test:all": "npm run lint && npm run test && npm run test:react",
        "test:perf": "cross-env NODE_ENV=production babel-node test/perf",
        "test:react": "npm run react:14 && jest && npm run react:15 && jest",
        "test:watch": "jest --watch"
    },
    "version": "2.2.3"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module react-intl](#apidoc.module.react-intl)
1.  [function <span class="apidocSignatureSpan">react-intl.</span>FormattedDate (props, context)](#apidoc.element.react-intl.FormattedDate)
1.  [function <span class="apidocSignatureSpan">react-intl.</span>FormattedHTMLMessage (props, context)](#apidoc.element.react-intl.FormattedHTMLMessage)
1.  [function <span class="apidocSignatureSpan">react-intl.</span>FormattedMessage (props, context)](#apidoc.element.react-intl.FormattedMessage)
1.  [function <span class="apidocSignatureSpan">react-intl.</span>FormattedNumber (props, context)](#apidoc.element.react-intl.FormattedNumber)
1.  [function <span class="apidocSignatureSpan">react-intl.</span>FormattedPlural (props, context)](#apidoc.element.react-intl.FormattedPlural)
1.  [function <span class="apidocSignatureSpan">react-intl.</span>FormattedRelative (props, context)](#apidoc.element.react-intl.FormattedRelative)
1.  [function <span class="apidocSignatureSpan">react-intl.</span>FormattedTime (props, context)](#apidoc.element.react-intl.FormattedTime)
1.  [function <span class="apidocSignatureSpan">react-intl.</span>IntlProvider (props)](#apidoc.element.react-intl.IntlProvider)
1.  [function <span class="apidocSignatureSpan">react-intl.</span>addLocaleData ()](#apidoc.element.react-intl.addLocaleData)
1.  [function <span class="apidocSignatureSpan">react-intl.</span>defineMessages (messageDescriptors)](#apidoc.element.react-intl.defineMessages)
1.  [function <span class="apidocSignatureSpan">react-intl.</span>injectIntl (WrappedComponent)](#apidoc.element.react-intl.injectIntl)
1.  [function <span class="apidocSignatureSpan">react-intl.</span>intlShape ()](#apidoc.element.react-intl.intlShape)

#### [module react-intl.intlShape](#apidoc.module.react-intl.intlShape)
1.  [function <span class="apidocSignatureSpan">react-intl.</span>intlShape ()](#apidoc.element.react-intl.intlShape.intlShape)
1.  [function <span class="apidocSignatureSpan">react-intl.intlShape.</span>isRequired ()](#apidoc.element.react-intl.intlShape.isRequired)



# <a name="apidoc.module.react-intl"></a>[module react-intl](#apidoc.module.react-intl)

#### <a name="apidoc.element.react-intl.FormattedDate"></a>[function <span class="apidocSignatureSpan">react-intl.</span>FormattedDate (props, context)](#apidoc.element.react-intl.FormattedDate)
- description and source-code
```javascript
function FormattedDate(props, context) {
    classCallCheck(this, FormattedDate);

    var _this = possibleConstructorReturn(this, (FormattedDate.__proto__ || Object.getPrototypeOf(FormattedDate)).call(this, props
, context));

    invariantIntlContext(context);
    return _this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-intl.FormattedHTMLMessage"></a>[function <span class="apidocSignatureSpan">react-intl.</span>FormattedHTMLMessage (props, context)](#apidoc.element.react-intl.FormattedHTMLMessage)
- description and source-code
```javascript
function FormattedHTMLMessage(props, context) {
    classCallCheck(this, FormattedHTMLMessage);

    var _this = possibleConstructorReturn(this, (FormattedHTMLMessage.__proto__ || Object.getPrototypeOf(FormattedHTMLMessage)).
call(this, props, context));

    invariantIntlContext(context);
    return _this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-intl.FormattedMessage"></a>[function <span class="apidocSignatureSpan">react-intl.</span>FormattedMessage (props, context)](#apidoc.element.react-intl.FormattedMessage)
- description and source-code
```javascript
function FormattedMessage(props, context) {
    classCallCheck(this, FormattedMessage);

    var _this = possibleConstructorReturn(this, (FormattedMessage.__proto__ || Object.getPrototypeOf(FormattedMessage)).call(this
, props, context));

    invariantIntlContext(context);
    return _this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-intl.FormattedNumber"></a>[function <span class="apidocSignatureSpan">react-intl.</span>FormattedNumber (props, context)](#apidoc.element.react-intl.FormattedNumber)
- description and source-code
```javascript
function FormattedNumber(props, context) {
    classCallCheck(this, FormattedNumber);

    var _this = possibleConstructorReturn(this, (FormattedNumber.__proto__ || Object.getPrototypeOf(FormattedNumber)).call(this,
props, context));

    invariantIntlContext(context);
    return _this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-intl.FormattedPlural"></a>[function <span class="apidocSignatureSpan">react-intl.</span>FormattedPlural (props, context)](#apidoc.element.react-intl.FormattedPlural)
- description and source-code
```javascript
function FormattedPlural(props, context) {
    classCallCheck(this, FormattedPlural);

    var _this = possibleConstructorReturn(this, (FormattedPlural.__proto__ || Object.getPrototypeOf(FormattedPlural)).call(this,
props, context));

    invariantIntlContext(context);
    return _this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-intl.FormattedRelative"></a>[function <span class="apidocSignatureSpan">react-intl.</span>FormattedRelative (props, context)](#apidoc.element.react-intl.FormattedRelative)
- description and source-code
```javascript
function FormattedRelative(props, context) {
    classCallCheck(this, FormattedRelative);

    var _this = possibleConstructorReturn(this, (FormattedRelative.__proto__ || Object.getPrototypeOf(FormattedRelative)).call(this
, props, context));

    invariantIntlContext(context);

    var now = isFinite(props.initialNow) ? Number(props.initialNow) : context.intl.now();

    // 'now' is stored as state so that 'render()' remains a function of
    // props + state, instead of accessing 'Date.now()' inside 'render()'.
    _this.state = { now: now };
    return _this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-intl.FormattedTime"></a>[function <span class="apidocSignatureSpan">react-intl.</span>FormattedTime (props, context)](#apidoc.element.react-intl.FormattedTime)
- description and source-code
```javascript
function FormattedTime(props, context) {
    classCallCheck(this, FormattedTime);

    var _this = possibleConstructorReturn(this, (FormattedTime.__proto__ || Object.getPrototypeOf(FormattedTime)).call(this, props
, context));

    invariantIntlContext(context);
    return _this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-intl.IntlProvider"></a>[function <span class="apidocSignatureSpan">react-intl.</span>IntlProvider (props)](#apidoc.element.react-intl.IntlProvider)
- description and source-code
```javascript
function IntlProvider(props) {
    var context = arguments.length > 1 && arguments[1] !== undefined ? arguments[1] : {};
    classCallCheck(this, IntlProvider);

    var _this = possibleConstructorReturn(this, (IntlProvider.__proto__ || Object.getPrototypeOf(IntlProvider)).call(this, props
, context));

    invariant(typeof Intl !== 'undefined', '[React Intl] The 'Intl' APIs must be available in the runtime, ' + 'and do not appear
 to be built-in. An 'Intl' polyfill should be loaded.\n' + 'See: http://formatjs.io/guides/runtime-environments/');

    var intlContext = context.intl;

    // Used to stabilize time when performing an initial rendering so that
    // all relative times use the same reference "now" time.

    var initialNow = void 0;
    if (isFinite(props.initialNow)) {
        initialNow = Number(props.initialNow);
    } else {
        // When an 'initialNow' isn't provided via 'props', look to see an
        // <IntlProvider> exists in the ancestry and call its 'now()'
        // function to propagate its value for "now".
        initialNow = intlContext ? intlContext.now() : Date.now();
    }

    // Creating 'Intl*' formatters is expensive. If there's a parent
    // '<IntlProvider>', then its formatters will be used. Otherwise, this
    // memoize the 'Intl*' constructors and cache them for the lifecycle of
    // this IntlProvider instance.

    var _ref = intlContext || {},
        _ref$formatters = _ref.formatters,
        formatters = _ref$formatters === undefined ? {
        getDateTimeFormat: memoizeIntlConstructor(Intl.DateTimeFormat),
        getNumberFormat: memoizeIntlConstructor(Intl.NumberFormat),
        getMessageFormat: memoizeIntlConstructor(IntlMessageFormat),
        getRelativeFormat: memoizeIntlConstructor(IntlRelativeFormat),
        getPluralFormat: memoizeIntlConstructor(IntlPluralFormat)
    } : _ref$formatters;

    _this.state = _extends({}, formatters, {

        // Wrapper to provide stable "now" time for initial render.
        now: function now() {
            return _this._didDisplay ? Date.now() : initialNow;
        }
    });
    return _this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-intl.addLocaleData"></a>[function <span class="apidocSignatureSpan">react-intl.</span>addLocaleData ()](#apidoc.element.react-intl.addLocaleData)
- description and source-code
```javascript
function addLocaleData() {
    var data = arguments.length > 0 && arguments[0] !== undefined ? arguments[0] : [];

    var locales = Array.isArray(data) ? data : [data];

    locales.forEach(function (localeData) {
        if (localeData && localeData.locale) {
            IntlMessageFormat.__addLocaleData(localeData);
            IntlRelativeFormat.__addLocaleData(localeData);
        }
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-intl.defineMessages"></a>[function <span class="apidocSignatureSpan">react-intl.</span>defineMessages (messageDescriptors)](#apidoc.element.react-intl.defineMessages)
- description and source-code
```javascript
function defineMessages(messageDescriptors) {
  // This simply returns what's passed-in because it's meant to be a hook for
  // babel-plugin-react-intl.
  return messageDescriptors;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-intl.injectIntl"></a>[function <span class="apidocSignatureSpan">react-intl.</span>injectIntl (WrappedComponent)](#apidoc.element.react-intl.injectIntl)
- description and source-code
```javascript
function injectIntl(WrappedComponent) {
    var options = arguments.length > 1 && arguments[1] !== undefined ? arguments[1] : {};
    var _options$intlPropName = options.intlPropName,
        intlPropName = _options$intlPropName === undefined ? 'intl' : _options$intlPropName,
        _options$withRef = options.withRef,
        withRef = _options$withRef === undefined ? false : _options$withRef;

    var InjectIntl = function (_Component) {
        inherits(InjectIntl, _Component);

        function InjectIntl(props, context) {
            classCallCheck(this, InjectIntl);

            var _this = possibleConstructorReturn(this, (InjectIntl.__proto__ || Object.getPrototypeOf(InjectIntl)).call(this, props
, context));

            invariantIntlContext(context);
            return _this;
        }

        createClass(InjectIntl, [{
            key: 'getWrappedInstance',
            value: function getWrappedInstance() {
                invariant(withRef, '[React Intl] To access the wrapped instance, ' + 'the '{withRef: true}' option must be set when
 calling: ' + ''injectIntl()'');

                return this.refs.wrappedInstance;
            }
        }, {
            key: 'render',
            value: function render() {
                return React__default.createElement(WrappedComponent, _extends({}, this.props, defineProperty({}, intlPropName,
this.context.intl), {
                    ref: withRef ? 'wrappedInstance' : null
                }));
            }
        }]);
        return InjectIntl;
    }(React.Component);

    InjectIntl.displayName = 'InjectIntl(' + getDisplayName(WrappedComponent) + ')';
    InjectIntl.contextTypes = {
        intl: intlShape
    };
    InjectIntl.WrappedComponent = WrappedComponent;


    return InjectIntl;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-intl.intlShape"></a>[function <span class="apidocSignatureSpan">react-intl.</span>intlShape ()](#apidoc.element.react-intl.intlShape)
- description and source-code
```javascript
intlShape = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-intl.intlShape"></a>[module react-intl.intlShape](#apidoc.module.react-intl.intlShape)

#### <a name="apidoc.element.react-intl.intlShape.intlShape"></a>[function <span class="apidocSignatureSpan">react-intl.</span>intlShape ()](#apidoc.element.react-intl.intlShape.intlShape)
- description and source-code
```javascript
intlShape = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-intl.intlShape.isRequired"></a>[function <span class="apidocSignatureSpan">react-intl.intlShape.</span>isRequired ()](#apidoc.element.react-intl.intlShape.isRequired)
- description and source-code
```javascript
isRequired = function () { [native code] }
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
