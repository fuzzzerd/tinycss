# tinycss

A very tiny CSS starter kit.

## Purpose

The purpose of this CSS starter kit, is to provide a decent out of the box experience, that does not get in the way of building your project.

## Getting Started

Take your pick. You have options:

- Copy the `.css` file and drop it in to your site as-is.
- Grab the `.scss` files and incorporate that in your build process.

Then simply amend `:root` variables per your colors and specs. There isn't a wrong way to use it.

## Build and Test Locally

To build and run locally, you need to install `sass`

```ps
choco install sass
```

or using nodejs/npm:

```ps
npm install -g sass
```

Once installed, you can run:

```ps
sass tinycss.scss:demo/tinycss.css --watch --style expanded --embed-sources
```

to generate the files you see here. Use other cli options from sass to suit your specific needs. The `--watch` parameter is useful for local development.

To generate minified output:

```ps
sass demo/tinycss.css:demo/tinycss.min.css --style compressed
```
