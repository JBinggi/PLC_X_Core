# Installation

Using composer

```bash
$ composer create-project oneplace/oneplace-core my-app
```

After you successfully installed core, you may add 3rd party
dependencies for certain features (they are disabled if libs are not found)

Add them to ./public/vendor

* [jQuery UI 1.12.1](https://jqueryui.com/download/)
> For Drag & Drop Index Columns
```
.
+-- jquery-ui
|   +-- jquery-ui.min.css
|   +-- jquery-ui.min.js
```

* [Apex Charts](https://apexcharts.com/)
> For all Daily Stats Charts and many more
```
.
+-- apexcharts
|   +-- apexcharts.css
|   +-- apexcharts.min.js
```

* [Font Awesome 5.12.0 Free or Pro](https://fontawesome.com/)
> For all icons across onePlace
```
.
+-- fontawesome
|   +-- css
|   |   +-- all.min.css
|   +-- webfonts
|   |   +-- fa-brands-400.eot/svg/ttf/woff/woff2
|   |   +-- ..(all fonts in package)
```

* [Filepond 4.9.4](https://github.com/pqina/filepond/releases)
    * [file-validate-size](https://github.com/pqina/filepond-plugin-file-validate-size/releases)
    * [file-validate-type](https://github.com/pqina/filepond-plugin-file-validate-type/releases)
    * [image-validate-size](https://github.com/pqina/filepond-plugin-image-validate-size/releases)
    * [image-crop](https://github.com/pqina/filepond-plugin-image-crop/releases)
    * [image-preview](https://github.com/pqina/filepond-plugin-image-preview/releases)
    * [image-resize](https://github.com/pqina/filepond-plugin-image-resize/releases)
    * [image-exif-orientation](https://github.com/pqina/filepond-plugin-image-exif-orientation/releases)
    * [image-transform](https://github.com/pqina/filepond-plugin-image-transform/releases)
> For Featured Image Upload
```
.
+-- filepond
|   +-- filepond.css
|   +-- filepond-plugin-image-preview.css
|   +-- filepond.min.js
|   +-- filepond-plugin-image-preview.js
```

* [Uppy 1.8.0](https://github.com/transloadit/uppy/releases)
    * + @uppy/xhr-upload@1.4.2 
> For Image Gallery Upload
```
.
+-- uppy
|   +-- filepond.css
|   +-- filepond-plugin-image-preview.css
|   +-- filepond.min.js
|   +-- filepond-plugin-image-preview.js
```

* [Select2 4.0.x](https://github.com/select2/select2/releases)
> For all Select und Multiselect Fields
```
.
+-- select2
|   +-- css
|   |   +-- select2.min.css
|   +-- js
|   |   +-- i18n
|   |   |   +-- *.js (all languages you want/need)
|   |   +-- select2.full.min.js
```