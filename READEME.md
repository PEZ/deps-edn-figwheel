# Figwheel on Clojure CLI

This is an attempt at creating a skeleton project using Figwheel together with Clojure CLI.

It's not working yet, because I haven't figured out the right conf to make the Figwheel development web server find the `index.html` file. See [Issue #1](https://github.com/PEZ/deps-edn-figwheel/issues/1). Please feel free to comment with your tips on what could be wrong with the configuration.

## How to use

0. Install [Clojure](https://clojure.org/guides/getting_started).
1. Download the code in this repo.
2. From wherever you downloaded it, run `clj build.clj figwheel`.
3. Attach to the web app on [localhost:3449](http://localhost:3449)

Watch it fail to connect to your app (per [Issue #1](https://github.com/PEZ/deps-edn-figwheel/issues/1), mentioned above. Please comment on that issue if you figure out what's wrong.