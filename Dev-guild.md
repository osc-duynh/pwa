```Not working in windows```

#Require 
  `Node JS >= 10.14.1`
  `Yarn > 1.13.0 || npm `

#Install Project
  `yarn install`
#Create custom host domain
  `cd packages/sample-theme && yarn run buildpack create-custom-origin .`
#Run Dev project
  `yarn sample-theme watch`
#Run build production project
  `yarn sample-theme build`

#Enable SCSS[SASS] or LESS
  `open file packages/sample-theme/webpack.config.js::127--159`
