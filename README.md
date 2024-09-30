[Issue](https://youtrack.jetbrains.com/issue/KT-69824/Kotlin-JS-Compilation-failed-with-module-not-found-error-after-updating-to-2.0.20-Beta2)

Running `./gradlew clean :site:jsBrowserDevelopmentWebpack` 

Should yield 

```
FAILURE: Build failed with an exception.

* What went wrong:
Execution failed for task ':site:jsBrowserDevelopmentWebpack'.
> Module not found: Error: Can't resolve '../../../../../Kotlin-DateTime-library-kotlinx-datetime/kotlinx/datetime/Clock.mjs' in '/Users/azef/dev/kotlin/playground/datetime-module-notfound/build/js/packages/datetimemodulenotfound/kotlin/datetimemodulenotfound/org/example/datetimemodulenotfound/pages'
```
