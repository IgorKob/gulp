#                       gulp
   
//для додавання з caniuse.com префіксів
//https://www.npmjs.com/package/gulp-autoprefixer
const gulp = require('gulp');
const autoprefixer = require('gulp-autoprefixer');
 
gulp.task('default', () =>
     gulp.src('css/1.css')
    .pipe(autoprefixer({
    browsers: ['last 20 versions'],
    cascade: false
}))
    .pipe(gulp.dest('dist'))
);
          



                     css
З’єднує файли css
https://www.npmjs.com/package/gulp-concat-css

плагін для мінімізації CSS
https://www.npmjs.com/package/gulp-clean-css

плагін для легкого перейменування файлів.
https://www.npmjs.com/package/gulp-rename

Видаліть невикористаний CSS
https://www.npmjs.com/package/gulp-uncss-sp

автоматично форматує ваш стиль, щоб він був послідовним і легким для читання
https://www.npmjs.com/package/gulp-cssbeautify



                 js 
https://www.npmjs.com/package/gulp-concat

https://www.npmjs.com/package/gulp-jscs-with-reporter

https://www.npmjs.com/package/gulp-babel

https://www.npmjs.com/package/gulp-jshint





               image
https://www.npmjs.com/package/gulp-imagemin

Зміна розмірів зображення
https://www.npmjs.com/package/gulp-image-resize

https://www.npmjs.com/package/gulp-img-retina

Створює зображення різного розміру
https://www.npmjs.com/package/gulp-responsive

https://www.npmjs.com/package/gulp-imacss




               all
https://www.npmjs.com/package/gulp-less

https://www.npmjs.com/package/gulp-sass

https://www.npmjs.com/package/gulp-react-templates

https://www.npmjs.com/package/gulp-angular-templatecache

https://www.npmjs.com/package/gulp-autoprefixer

для запуску локального веб-сервера з перезавантаженням в реальному часі за допомогою socket.io
https://www.npmjs.com/package/gulp-server-livereload







