<p align="center">
<a href="https://dahliaos.io">Website</a> •
<a href="https://dahliaos.io/discord">Discord</a> •
<a href="https://dahliaos.io/download">Releases</a> •
<a href="https://dahliaos.io/donate">Donate</a> •
<a href="https://docs.dahliaos.io">Documentation</a>

# dahliaOS Flutter application development template
[![Powered by Mason](https://img.shields.io/endpoint?url=https%3A%2F%2Ftinyurl.com%2Fmason-badge)](https://github.com/felangel/mason)

 - **Application** development template for creating Flutter applications for dahliaOS

## Usage

To generate this template in order to start developing Flutter applications for dahliaOS follow the steps below:

### 1. Install Mason

- Pub.dev

```
dart pub global activate mason_cli
```

- Homebrew

```
brew tap felangel/mason
```
```
brew install mason
```

### 2. Initialize Mason

```
mason init
```

Running the command above Mason will generate a `mason.yaml` file.

### 3. Add our template brick
Edit the `mason.yaml` file and add our template brick, example shown below:

```yaml
bricks:
   dahliaos_app_template:
     git:
       url: https://github.com/dahliaOS/app_template.git
       path: template/dahliaos_app_template
```

### 4. Get all registered bricks

```
mason get
```

### 5. Generate the template files

```
mason make dahliaos_app_template
```
You should now have all the Flutter files generated and ready for editing, happy coding!

## Contribute

If you're wondering how to contribute to the project, please refer to [CONTRIBUTING.md](CONTRIBUTING.md)

## License

<p align="left">
  <img width="30%" src="https://github.com/dahliaOS/brand/blob/main/dahliaOS/logotype/svg/logotype-dark.svg#gh-dark-mode-only"/>
  <img width="30%" src="https://github.com/dahliaOS/brand/blob/main/dahliaOS/logotype/svg/logotype-light.svg#gh-light-mode-only"/>
</p>

Copyright @ 2019-2022 - The dahliaOS Authors - contact@dahliaos.io

This project is licensed under the [Apache 2.0 license](/LICENSE)
