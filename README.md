# Amexio Angular Extensions for Visual Studio Code 

This Amexio Plugin will help the Angular developers using Visual Studio Code with a quick code snippet for the Angular and Amexio Directives as well as Angular TypeScript. Plugin support is available for Angular 4+ onwards. 

## Usage

### Demo
<img src="https://raw.githubusercontent.com/meta-magic/Amexio-VSC-Extension/master/images/Amexio-VSC-Example2.gif" />

### Select the Amexio Ui Component
<img src="https://raw.githubusercontent.com/meta-magic/Amexio-VSC-Extension/master/images/Amexio-VSC-Ex-1.jpg" />

### Fill up the required Component Params
<img src="https://raw.githubusercontent.com/meta-magic/Amexio-VSC-Extension/master/images/Amexio-VSC-Ex-2.jpg" />

## Requirements

Install Amexio to enhance your Angular Project. 

## Amexio Angular Extension - Installation
For installing on previous Amexio version ref http://amexio.org/api/v4.1/index.html#/getting-started
To install this Amexio 4.x follow the steps given below:

```bash
$ cd your-angular-project
$ npm install amexio-ng-extensions --save
```

and then from your Angular `AppModule`:

```typescript
import {BrowserModule} from '@angular/platform-browser';
import {NgModule} from '@angular/core';
import {FormsModule} from '@angular/forms';
import {AppComponent} from './app.component';
import {AmexioWidgetModule} from 'amexio-ng-extensions'; // Import Amexio library

//Dashboard,Charts & Maps are available as seperate module (not in AmexioWidgetModule)
import {AmexioChartsModule,AmexioDashBoardModule,AmexioEnterpriseModule,AmexioMapModule} from 'amexio-ng-extensions';

@NgModule({
  declarations: [AppComponent],
  imports: [BrowserModule, AmexioWidgetModule, FormsModule, AmexioChartsModule, AmexioDashBoardModule,AmexioEnterpriseModule,AmexioMapModule],
  bootstrap: [AppComponent]
})
export class AppModule {
}
```

Once your library is imported, you can use its components, directives and pipes in your Angular application:

```xml
<!-- You can now use your library component in app.component.html -->
<amexio-text-input></amexio-text-input>
```


## Installing Extension in Visual Studio Code

<img src="https://raw.githubusercontent.com/meta-magic/Amexio-VSC-Extension/master/images/Amexio-VSC-Installation.gif" />

[Microsoft Visual Studio Market Place](https://marketplace.visualstudio.com/items?itemName=MetaMagic.amexio)
```bash
ext install amexio
```


## Known Issues

--

## Release Notes

Amexio VSC Extension supports Amexio Moscow Release v5.0

## License

[Apache 2.0](http://www.amexio.org/metamagic-showcase/license.html) © [MetaMagic Global Inc](http://www.metamagicglobal.com/), 2017. [Amexio Angular Extensions](http://www.amexio.tech)

**Enjoy!**
