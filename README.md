# Ngx-mobile-keyboard-watcher

> Ngx-mobile-keyboard-watcher is an ultra simple cnpj validator for Angular.io.

[![basic-merchandising](https://imgur.com/LNOYczf.png)](https://github.com/leopq)

**Disclaimer**: I use this module for personal projects, which means it is designed to fulfill their specific use cases. The code I develop is crafted with reuse and generalization in mind, still, it may or may not fulfill for your requirements. In case it does not, please feel free to submit a pull request, create a fork or contact me at lpachecoquevedo@gmail.com so we can figure something out together. Thank you for reading this!

## Installing

```sh
$ npm install --save ngx-mobile-keyboard-watcher
```

## Quickstart

#### Import

Import **ngx-mobile-keyboard-watcher** module in Angular app.

```typescript
import { NgxCreditCardBr } from 'ngx-mobile-keyboard-watcher'

(...)

@NgModule({
  (...)
  imports: [
    NgxCreditCardBr.forRoot()
  ]
  (...)
})
```

#### Usage

In your template, you can declare the ngx-mobile-keyboard-watcher as the following:
```html
<form>
    <!-- Input with the CPF validator -->
    <input type="tel" ngx-cnpj [(ngModel)]="user.cnpj" name="userCnpj" #cnpjInput >
</form>

```

### And that's all there is about it.
* Any doubts? Fell free to open an issue.
* Improvements? Pull requests are always come!
* Suggestions? Of course: Let's [talk](https://twitter.com/leopq)!

##### MIT @ Leonardo Quevedo. 2018.