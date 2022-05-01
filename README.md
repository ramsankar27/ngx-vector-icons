# 💝 ngx-vector-icons
![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)


![angular](https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white) ![typescript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white
)


An easy way to add icons to your Angular app.

![Ngx vector icons banner image](https://raw.githubusercontent.com/ramsankar27/ngx-vector-icons/main/ngx-vector-icon-banner.png)
## 🎉 Features
- It's a light-weight library.
- Six icon sets are included in the package and can be used for free.
- It may be used for commercial projects, open source projects, or nearly anything else.
- To have access to a set of six bundel icons, simply import one module.

## 📦 Bundled Icon Sets
- [AntDesign](https://ant.design/) by AntFinance (300+ icons)
- [Fontisto](https://github.com/kenangundogan/fontisto) by Kenan Gündoğan (650+ icons)
- [Font Awesome Icons](https://fontawesome.com/) by Fonticons, Inc. (2500+ cons)
- [Material Design Icons](https://materialdesignicons.com/) by MaterialDesignIcons.com (6600+ icons)
- [Material Icons](https://www.google.com/design/icons/) by Google, Inc. (1500+ icons)
- [SimpleLineIcons](https://simplelineicons.github.io/) by Sabbir & Contributors (200+ icons)

## 🚀 Demo
If you'd like to see an example, please [click here](#).
## 🔥 Installation
```sh
npm install ngx-vector-icons
```
## 📝 ️Usage
### 🚴 step 1 :
Import NgxVectorIconsModule in app.module.ts file 
```sh 
import { NgxVectorIconsModule } from 'ngx-vector-icons';
```    
### 🚴 step 2 :
In app.module.ts add NgxVectorIconsModule to your @NgModule 
```sh
@NgModule({
  ...,
  imports: [ ...,NgxVectorIconsModule ],
  ...
})
```
### 🚴 step 3 :
Add below code in your index.html file
```sh
<!-- ant design icons -->
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/ant-design-icons@1.3.3/dist/anticons.min.css">

<!-- fontisto icons -->
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/fontisto@v3.0.4/css/fontisto/fontisto.min.css">

<!-- fontawesome icons -->
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.1.1/css/all.css">

<!-- material icons -->
<link href="https://fonts.googleapis.com/css2?family=Material+Icons" rel="stylesheet">

<!-- materialdesign icons -->
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@mdi/font@6.5.95/css/materialdesignicons.min.css">

<!-- simple icons -->
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/simple-line-icons/2.5.5/css/simple-line-icons.min.css">
```
### 🚴 step 4 :
That's all, you're ready to use icons in your project now.
[Angular Vector icons directory ](#) has over 5000 icons to choose from.

##### Ant Design Icons example
```sh
<ant-design-icons class="ml-60" name="logout" [size]="22" color="limegreen"></ant-design-icons>
```
##### Fontisto Icons example
```sh
<fontisto-icons class="ml-60" name="podcast" [size]="22" color="pink"></fontisto-icons>
```
##### Font Awesome Icons example
```sh
<font-awesome-icons class="ml-20" name="address-book" [size]="32" color="grey"></font-awesome-icons> 
```
##### Material Design Icons example
```sh
<material-design-icons class="ml-20" name="pizza" [size]="32" color="blue"></material-design-icons>
```
##### Material Icons example
```sh
<material-icons class="ml-20" name="pizza" [size]="32" color="blue"></material-icons>
```
##### Simple Icons example
```sh
<simple-icons class="ml-40" name="people" [size]="22" color="red"></simple-icons>
```

## 📚 License

[MIT](http://opensource.org/licenses/MIT)

For ❤️ Angular developers 