# Figwheel on Clojure CLI

This is an attempt at creating a skeleton project using [Figwheel](https://github.com/bhauman/lein-figwheel) together with [Clojure CLI](https://clojure.org/reference/deps_and_cli).

## How to use

0. Install [Clojure](https://clojure.org/guides/getting_started).
1. Download the code in this repo.
2. From wherever you downloaded it, run `clojure build.clj figwheel`. (Since figwheel uses rebel, a readline is already supplied, so we use `clojure` instead of `clj`.)
3. Attach to the web app on [localhost:3449](http://localhost:3449)
