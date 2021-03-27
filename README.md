               ********
            ********
          ********
       ********                 ________
     ********   (*******/      / ____/ /__  ____ _   __
      ****    ********        / /_  / / _ \/ __ \ | / /
           ,////***          / __/ / /  __/ / / / |/ /
           //////%%         /_/   /_/\___/_/ /_/|___/
              %%%%%%%#
                %%%%%%%%

# Flenv

Flutter environment
This small script allows you to have multiple instances of Flutter environment
on one machine and change them depending on the project you're working on.

For now, there are two necessary commands:

- **`flenv init`** <- You use this command in your Flutter project. It creates `flenv.yaml` storing version of your current local Flutter version.
- **`flenv fit`** <- You use this command in your Flutter project. It reads the version from `flenv.yaml` and sets it as a current/local Flutter environment. Other environments are not modified. Script forks new one.

##Requirements

- **flutter**
- **git**

##Instalation

Go to directory where you want flenv to be placed.
Type:

```
git clone git@github.com:lukeurban/flenv.git
```

And then add flenv directory to yout PATH

```
cd flenv
export PATH="$PATH:`pwd`"
```

This command sets your PATH variable for the current terminal window only. To permanently add **flenv** to your path, add it to your .rc file (eg: ~/.bashrc)

### Acknowlagement

Created and maintained by [Luke Urban](https://github.com/lukeurban)

Follow me on [Twitter](https://twitter.com/ThatLukeUrban) for more Flutter/tech/programming related content.
