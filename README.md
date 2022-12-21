# Snow

Add snow to Aha! Develop.

<img width="1660" alt="CleanShot 2022-12-21 at 12 04 11@2x" src="https://user-images.githubusercontent.com/8016/208783145-33b01c18-d464-4015-a0f1-499fa7ad6f7d.png">

## Installing the extension

**Note: In order to install an extension into your Aha! Develop account, you must be an account administrator.**

Install the Snow extension by clicking [here](https://secure.aha.io/settings/account/extensions/install?url=https://github.com/jemmyw/aha-develop-snow/releases/download/v1.1.0/jemmyw.snow-v1.1.0.gz).

## Working on the extension

Install [`aha-cli`](https://github.com/aha-app/aha-cli):

```sh
npm install -g aha-cli
```

Clone the repo:

TODO: Add the repository URL here
```sh
git clone https://github.com/jemmyw/aha-develop-snow.git
```

**Note: In order to install an extension into your Aha! Develop account, you must be an account administrator.**

Install the extension into Aha! and set up a watcher:

```sh
aha extension:install
aha extension:watch
```

Now, any change you make inside your working copy will automatically take effect in your Aha! account.

## Building

When you have finished working on your extension, package it into a `.gz` file so that others can install it:

```sh
aha extension:build
```

After building, you can upload the `.gz` file to a publicly accessible URL, such as a GitHub release, so that others can install it using that URL.

To learn more about developing Aha! Develop extensions, including the API reference, the full documentation is located here: [Aha! Develop Extension API](https://www.aha.io/support/develop/extensions)
