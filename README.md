# Heroku Buildpack for Nim

![Nim Logo](https://telegra.ph/file/b9b18e05f675a5711a061.jpg)

#### Minimal Buildpack to install Nim-lang, and it's package manager Nimble in Heroku

**Note** - This is a beta release and very minimal. Contributions are welcome.

## Adding Buildpack

### Using Heroku CLI

```sh
heroku buildpacks:set https://github.com/StarkBotsIndutries/heroku-buildpack-nim.git
```

### Using Heroku GUI

1. Go to Heroku Dashboard and open your app.


2. Go to the settings tab

<p align="center">
    <a href="https://github.com/StarkBotsIndustries/heroku-buildpack-nim">
        <img src="https://telegra.ph/file/fc5409f9a91f0afaaaec5.jpg" alt="Settings Tab" width="650">
    </a>
</p>

3. Scroll below and find the buildpacks section

<p align="center">
    <a href="https://github.com/StarkBotsIndustries/heroku-buildpack-nim">
        <img src="https://telegra.ph/file/b4ac2af139f58bb37a83f.jpg" alt="Add Buildpacks" width="650">
    </a>
</p>

4. Click on 'Add Buildpack', put the url and save changes.

<p align="center">
    <a href="https://github.com/StarkBotsIndustries/heroku-buildpack-nim">
        <img src="https://telegra.ph/file/057a45d9b80bac216f837.jpg" alt="Save" width="650">
    </a>
</p>

5. The buildpack is now enabled. It'll be build in next deployment

<p align="center">
    <a href="https://github.com/StarkBotsIndustries/heroku-buildpack-nim">
        <img src="https://telegra.ph/file/8d7b5dba5d316f5e43770.jpg" alt="Done" width="650">
    </a>
</p>

You are good to go.