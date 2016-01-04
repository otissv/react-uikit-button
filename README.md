#React Uikit Button

Easily create nicely looking buttons, which come in different styles.

See [http://otissv.github.io/react-uikit-components/](http://otissv.github.io/react-uikit-components) for docs.

##Usage

###Installation

    npm install react-uikit-button --save;

    // ES6
    import Button from 'react-uikit-button';

    // ES5
    var Button = require('react-uikit-button');


###Example

    <Button body='Link' type='link' margin='bottom right'/>
    <Button body='Button' margin='bottom right'/>
    <Button body='Disabled' disabled margin='bottom right'/>
    <Button type='close'/>

##Tests

`npm run test`to run tests with minimal output.  
`npm run test:spec` to run tests with detailed output.  
`npm run test:watch` watches all directories and run tests with minimal output on file changes.

##Build
`npm run build` to build files fro distribution.  
`npm run build:watch` watches src directory and builds files on changes.

##Lint
`npm run lint` lints scripts in src directory.  
`npm run lint:watch` watches src directory and lints scripts in src directory.

##License
MIT
