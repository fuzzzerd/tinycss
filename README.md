# tinycss

A very tiny CSS starter kit.

## Purpose

The purpose of this CSS starter kit, is to provide a decent out of the box experience, that does not get in the way of building your project.

## Getting Started

Take your pick. You have options:

- Copy the `.css` file and drop it in to your site as-is.
- Grab the `.scss` files and incorporate that in your build process.

There isn't a wrong way to use it.

## Build and Test Locally

To build and run locally, you need to install `sass`

```ps
choco install sass
```

Once installed, you can run

```ps
sass tinycss.scss tinycss.min.css --style compressed
```

to generate the files you see here, or use other cli options from sass to suit your specific needs. Use the `--watch` parameter for ongoing development.
