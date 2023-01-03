# Enge

This is the project for manage 2 angular Library of tools developed by [StepoBiz](https://stepo.biz)

The libraries is
- common-app
- commpon-lib

The library is not dependent on each other. The guide is based on the firs module as example but all is the same.

## Development server

For use library cloned localy, in your project is necessary build it and use the dist folder as npm link, like in this example:
```
ng build common-app
cd dist/common-app
sudo npm link
```

after go in your project and link it to library
```
cd your_project_folder
npm link @enge/common-app
```

If you want edit library an se real time result in your project, execute the watch builder in library folder:
```
ng build common-app --watch
```

## Publish version

For publish version for first compile eht module and then publis on npm 
```
ng build common-app 
npm publish dist/common-app/
```