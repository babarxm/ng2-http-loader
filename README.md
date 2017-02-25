# Ng2-Http-Loader

## ng2-http-loader [![Angular 2 Style Guide](https://mgechev.github.io/angular2-style-guide/images/badge.svg)](https://github.com/mgechev/angular2-style-guide)

Follow me [![twitter](https://img.shields.io/twitter/follow/babarxm.svg?style=social&label=%20babarxm)](https://twitter.com/babarxm) to be notified about new releases.

## Setup
`npm install ng2-http-loader --save`

## Properties and methods
  - `prop/method` description.

## Configuration
### Step 1
    import { Ng2HttpLoaderModule } from "ng2-http-loader";
    @NgModule({
      imports: [ Ng2HttpLoaderModule ]
    })
    export class AppModule { }

### Step 2
    @Component({
      selector: 'app-demo',
      templateUrl: '<ng2-http-loader></ng2-http-loader>'
    })

    export class DemoComponent{
      constructor(): void { }
    }

## TODO
  - Demo 

## Troubleshooting

Please follow this guidelines when reporting bugs and feature requests:

1. Use [GitHub Issues](https://github.com/babarxm/ng2-http-loader/issues) board to report bugs and feature requests (not our email address)
2. Please **always** write steps to reproduce the error. That way we can focus on fixing the bug, not scratching our heads trying to reproduce it.


### License

The MIT License (see the [LICENSE](https://github.com/babarxm/ng2-http-loader/blob/master/LICENSE) file for the full text)