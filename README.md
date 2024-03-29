# cld-form-unsigned-upload
An example showing how to use an unsigned upload preset to upload multiple files to Cloudinary using a form.

Note, for security reasons, the upload preset used in this example sets the [access control mode](https://cloudinary.com/documentation/control_access_to_media#access_controlled_media_assets) of the uploaded assets to restricted, so the URLs returned in the response will return 404 errors.


## Installation

Ensure you have a recent version of [node & npm](https://nodejs.org/en/download/) or [yarn](https://yarnpkg.com/en/docs/install) installed.

All of the following steps run on the command line within this directory. You can substitute `npm` for `yarn` depending on your preferences.

Install all the necessary packages:

```
npm install
```

## Build

To build for distribution:

```
npm run build
```

All of the final output will be dropped into the [/dist/](./dist) folder.

## Server

Run a local server that will automatically compile your code & refresh when you save a change!

```
npm run serve
```
